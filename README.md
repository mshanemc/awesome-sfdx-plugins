# Awesome SFDX Plugins

In the spirit of `awesome-[whatever]`, it's a public directory of open source sfdx plugins.

## Contributing

Fork, PR, and add your plugins to share with the world
Also feel free to reorganize these as the list grows

## Official plugins/modules from Salesforce

- [falcon](https://github.com/sfdx-isv/sfdx-falcon) template/framework for ISVs
- [sfdx-core](https://github.com/forcedotcom/sfdx-core) auth, connections, and client-side tools for your plugins
- [sfdx-plugin-generate](https://github.com/forcedotcom/sfdx-plugin-generate) sfdx-specific version of the oclif generate
- [sfdx-command](https://github.com/forcedotcom/cli-packages) the thing we're all extending
- [isvte](https://github.com/forcedotcom/isvte-sfdx-plugin) tools for ISVs from Salesforce's [ISV Technical Evangelism](https://medium.com/inside-the-salesforce-ecosystem/build-better-apps-for-your-customers-with-this-new-dx-plug-in-4877fa0fc305) team

## Community supported plugins

Shared by people out of love, for the community. No guarantees.

- [shane-sfdx-plugins](https://github.com/mshanemc/shane-sfdx-plugins) (Shane McLaughlin, [@mshanemc](https://github.com/mshanemc))

  Too many commands to even attempt to describe--just go read the README.

- [muenzpraeger/sfdx-plugin](https://github.com/muenzpraeger/sfdx-plugin) (Rene Winkelmeyer, [@muenzpraeger](https://github.com/muenzpraeger))

  Sets api version, deletes Aura empty boilerplate files, and turns swagger defts into Apex classes

- [sfdx-waw-plugin](https://github.com/wadewegner/sfdx-waw-plugin) (Wade Wegner, [@wadewegner](https://github.com/wadewegner))

  Shortcuts for connected apps, codeclean, packaging, and more

- [mo-dx-plugin](https://github.com/msrivastav13/mo-dx-plugin) (Mohith Shrivastava, [@msrivastav13](https://github.com/msrivastav13))

  Retrieving and deploying via tooling api, convert package source to Salesforcedx source all in one command, rename CRUD based metadata

- [sfdx-cmdt-plugin](https://github.com/shunkosa/sfdx-cmdt-plugin) (Shun Kosaka, [@shunkosa](https://github.com/shunkosa))

  Convert csv to custom metadata

- [texei-sfdx-plugin](https://github.com/texei/texei-sfdx-plugin) (folks from Texei, especially [@FabienTaillon](https://github.com/FabienTaillon))

  Crawls package dependencies and automatically installs the prerequisites | update your user fields | enables SharedActivities in scratch orgs | and more

- [ETCopyData](https://github.com/eltoroit/ETCopyData) ( Andres Perez [@eltoroit](https://github.com/eltoroit))

  Extract and populate data to sandboxes and scratch orgs

- [sfdx-browserforce-plugin](https://github.com/amtrack/sfdx-browserforce-plugin) (Matthias Rolke [@amtrack](https://github.com/amtrack))

  Configurable tool for browser-driving through the setup menu to get at all those non-accessible features

- [sfdx-migration-automatic](https://github.com/stomita/sfdx-migration-automatic) (Shinichi Tomita [@stomita](https://github.com/stomita))

  Dump/load record data to/from CSV files to easily migrate data between orgs

- [sfdx-devhub-pool](https://github.com/stomita/sfdx-devhub-pool) (Shinichi Tomita [@stomita](https://github.com/stomita))

  Generate scratch orgs without hitting daily limit by using multiple DevHub orgs as a pool

- [sfdx-toolbox-package-utils](https://github.com/ImJohnMDaniel/sfdx-toolbox-package-utils) (John M. Daniel [@ImJohnMDaniel](https://github.com/ImJohnMDaniel))

  Plugin devoted to better managing second generation package dependencies.  

- [sfpowerkit](https://github.com/Accenture/sfpowerkit) (Accenture)

  Too many powerful things.Read the documentation on the git repo.

- [soqlx-opener](https://github.com/ImJohnMDaniel/soqlx-opener) (John M. Daniel [@ImJohnMDaniel](https://github.com/ImJohnMDaniel))

  For those SalesforceDevs that love [@Superfell](https://github.com/Superfell)'s [#SoqlXplorer](https://github.com/superfell/SoqlX), this plugin brings the power of SoqlX to DX Scratch orgs.

- [sfdx-git-packager](https://github.com/ChuckJonas/sfdx-git-packager) (Charles Jonas [@ChuckJonas](https://github.com/ChuckJonas))

  Generates Metadata packages from differences between git refs.

- [JSON-Bourne-SFDX](https://github.com/realestate-com-au/json-bourne-sfdx-cli) (REA Group [@realestate-com-au](https://github.com/realestate-com-au))

  Source control your org reference data, and treat it as metadata (make changes in scratch org, commit the changes to source control and "deploy" through CI).

- [SFDX Essentials](https://github.com/nvuillam/sfdx-essentials) (Nicolas Vuillamy & contributors [@nvuillam](https://github.com/nvuillam))

  Filter metadata folders according to a package.xml, generate automatically permission sets , check the consistency between a SFDX project sources and related package.xml file(s), change package dependencies versions and apiVersion, reorder package.xml file content, migrate SFDX sources from an object model to a new objects model, filter metadatas XML before deployment.

- [Flowdoc] (https://github.com/shunkosa/sfdx-flowdoc-plugin) (Shun Kosaka @shunkosa) (https://github.com/shunkosa)

  Still in alpha, but very promising approach to create documentation from your Flows as PDF! 

## Not plugins, but useful

- [yo-sfdx-commands-generator](https://github.com/vyuvalv/yo-sfdx-commands-generator) (Yuval Vardi) [](https://github.com/vyuvalv)

  interactive generators for projects and scratch org features/settings

- [yo-sfdx-commands-autocomplete](https://github.com/vyuvalv/yo-sfdx-commands-autocomplete) (Yuval Vardi) [](https://github.com/vyuvalv)

  run commands interactively (autocomplete for sfdx commands and flags)

## Documentation

- [Oclif](https://oclif.io/)

  A few layers down the stack, and for when you want to build CLI for other things that may not be sfdx-specific

- [Plugin developer guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_plugins.meta/sfdx_cli_plugins/cli_plugins_architecture_sf_cli.htm)

## Issues

core sfdx commands have an [issues-only repo](https://github.com/forcedotcom/cli)
