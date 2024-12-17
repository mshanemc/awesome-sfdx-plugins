# Awesome SFDX Plugins

In the spirit of `awesome-[whatever]`, it's a public directory of open source sfdx plugins.

## Contributing

Fork, PR, and add your plugins to share with the world
Also feel free to reorganize these as the list grows

## Official plugins/modules from Salesforce

-   [falcon](https://github.com/sfdx-isv/sfdx-falcon) template/framework for ISVs
-   [sfdx-core](https://github.com/forcedotcom/sfdx-core) auth, connections, and client-side tools for your plugins
-   [sfdx-plugin-generate](https://github.com/forcedotcom/sfdx-plugin-generate) sfdx-specific version of the oclif generate
-   [sfdx-command](https://github.com/forcedotcom/cli-packages) the thing we're all extending
-   [isvte](https://github.com/forcedotcom/isvte-sfdx-plugin) tools for ISVs from Salesforce's [ISV Technical Evangelism](https://medium.com/inside-the-salesforce-ecosystem/build-better-apps-for-your-customers-with-this-new-dx-plug-in-4877fa0fc305) team
-   [@salesforce/analytics](https://sfdc.co/adx_cli_help) commands for working with Salesforce Analytics apis
-   [sfdx-scanner](https://github.com/forcedotcom/sfdx-scanner) runs quality and security checks (PMD) - does not replace Checkmarx for Partners
-   [sfdmu](https://github.com/forcedotcom/SFDX-Data-Move-Utility) Salesforce Data Move Utility - plugin and GUI
-   [sfdx-plugin-lwc-test](https://github.com/salesforce/sfdx-plugin-lwc-test) Helpful for setting up Jest Tests
-   [@salesforce/analytics](https://sfdc.co/adx_cli_help) commands for working with Salesforce Analytics apis
-   [dependency](https://github.com/forcedotcom/dependencies-cli) helps you leverage Dependency API
-   [lwc-dev-mobile](https://github.com/forcedotcom/lwc-dev-mobile) local preview of LWC in ios/android emulation

## Community supported plugins

Shared by people out of love, for the community. No guarantees.

-   [shane-sfdx-plugins](https://github.com/mshanemc/shane-sfdx-plugins) (Shane McLaughlin, [@mshanemc](https://github.com/mshanemc))

    Too many commands to even attempt to describe--just go read the README.

-   [muenzpraeger/sfdx-plugin](https://github.com/muenzpraeger/sfdx-plugin) (Rene Winkelmeyer, [@muenzpraeger](https://github.com/muenzpraeger))

    Sets api version, deletes Aura empty boilerplate files, and turns swagger defts into Apex classes

-   [sfdx-waw-plugin](https://github.com/wadewegner/sfdx-waw-plugin) (Wade Wegner, [@wadewegner](https://github.com/wadewegner))

    Shortcuts for connected apps, codeclean, packaging, and more

-   [mo-dx-plugin](https://github.com/msrivastav13/mo-dx-plugin) (Mohith Shrivastava, [@msrivastav13](https://github.com/msrivastav13))

    Retrieving and deploying via tooling api, convert package source to Salesforcedx source all in one command, rename CRUD based metadata

-   [sfdx-cmdt-plugin](https://github.com/shunkosa/sfdx-cmdt-plugin) (Shun Kosaka, [@shunkosa](https://github.com/shunkosa))

    Convert csv to custom metadata

-   [texei-sfdx-plugin](https://github.com/texei/texei-sfdx-plugin) (folks from Texei, especially [@FabienTaillon](https://github.com/FabienTaillon))

    Crawls package dependencies and automatically installs the prerequisites | update your user fields | enables SharedActivities in scratch orgs | and more

-   [ETCopyData](https://github.com/eltoroit/ETCopyData) ( Andres Perez [@eltoroit](https://github.com/eltoroit))

    Extract and populate data to sandboxes and scratch orgs

-   [sfdx-browserforce-plugin](https://github.com/amtrack/sfdx-browserforce-plugin) (Matthias Rolke [@amtrack](https://github.com/amtrack))

    Configurable tool for browser-driving through the setup menu to get at all those non-accessible features

-   [sfdx-migration-automatic](https://github.com/stomita/sfdx-migration-automatic) (Shinichi Tomita [@stomita](https://github.com/stomita))

    Dump/load record data to/from CSV files to easily migrate data between orgs

-   [sfdx-devhub-pool](https://github.com/stomita/sfdx-devhub-pool) (Shinichi Tomita [@stomita](https://github.com/stomita))

    Generate scratch orgs without hitting daily limit by using multiple DevHub orgs as a pool

-   [sfdx-toolbox-package-utils](https://github.com/ImJohnMDaniel/sfdx-toolbox-package-utils) (John M. Daniel [@ImJohnMDaniel](https://github.com/ImJohnMDaniel))

    Plugin devoted to better managing second generation package dependencies.

-   [sfpowerkit](https://github.com/Accenture/sfpowerkit) (Accenture)

    Too many powerful things.Read the documentation on the git repo.

-   [sfpowerscripts](https://github.com/Accenture/sfpowerscripts) (Accenture)
  
    A build system for package based development model using sfdx-project.json as source of truth.

-   [soqlx-opener](https://github.com/ImJohnMDaniel/soqlx-opener) (John M. Daniel [@ImJohnMDaniel](https://github.com/ImJohnMDaniel))

    For those SalesforceDevs that love [@Superfell](https://github.com/Superfell)'s [#SoqlXplorer](https://github.com/superfell/SoqlX), this plugin brings the power of SoqlX to DX Scratch orgs.

-   [sfdx-git-packager](https://github.com/ChuckJonas/sfdx-git-packager) (Charles Jonas [@ChuckJonas](https://github.com/ChuckJonas))

    Generates Metadata packages from differences between git refs.

-   [JSON-Bourne-SFDX](https://github.com/realestate-com-au/json-bourne-sfdx-cli) (REA Group [@realestate-com-au](https://github.com/realestate-com-au))

    Source control your org reference data, and treat it as metadata (make changes in scratch org, commit the changes to source control and "deploy" through CI).

-   [SFDX Essentials](https://github.com/nvuillam/sfdx-essentials) (Nicolas Vuillamy & contributors [@nvuillam](https://github.com/nvuillam))
    
    Filter metadata folders according to a package.xml, generate automatically permission sets , check the consistency between a SFDX project sources and related package.xml     file(s), change package dependencies versions and apiVersion, reorder package.xml file content, migrate SFDX sources from an object model to a new objects model, filter       metadatas XML before deployment.

-   [sfdx-mohanc-plugins](https://www.npmjs.com/package/sfdx-mohanc-plugins) (Mohan Chinnappan, [@mohan-chinnappan-n](https://github.com/mohan-chinnappan-n))

  Too many commands to even attempt to describe--just go read the README.

-   [Flowdoc](https://github.com/shunkosa/sfdx-flowdoc-plugin) (Shun Kosaka [@shunkosa](https://github.com/shunkosa))

    Still in alpha, but very promising approach to create documentation from your Flows as PDF, Word (docx) and JSON!

-   [sfdx-valkyrie](https://github.com/jonathanwiesel/sfdx-valkyrie) (Jonathan Wiesel [@jonathanwiesel](https://github.com/jonathanwiesel))

    Detect and report on lack of implementation of the bypassing pattern.

-   [adp](https://github.com/americanexpress/sfdx-cli-plugin) (American Express)

    Various devops tools (e.g. to login into an org), run jars (includes talend jobs)

-   [jayree](https://github.com/jayree/sfdx-jayree-plugin)

    Deploys changesets, updates state and country picklists and other helpful time-savers.

-   [sedmockdata](https://github.com/msrivastav13/testdata) (Mohith Shrivastava, [@msrivastav13](https://github.com/msrivastav13))

    A plugin for Salesforce DX CLI that provides ability to generate test data using mockaroo schema.You will need to sign up for the mockaroo API services and generate a schema.

-   [DXB](https://github.com/davidbrowaeys/DXB) (David Browaeys, [@davidbrowaeys](https://github.com/davidbrowaeys))

    A set of cool commands that extend the salesforce cli such as delta deployment, scratch org creation, profile json conversion, optimize soql queries by running your query plan locally, transfer sample or ref data from one org to another using bulk api, search why user as access to a object or a field, clean permisson set. 
    
-   [sfdx-ci-plugin](https://github.com/fransflippo/sfdx-ci-plugin) (Frans Flippo, [@fransflippo](https://github.com/fransflippo))

    A plugin to create a connected app suitable for JWT authentication (`sfdx auth:jwt:grant`) with "one click". Especially useful for CI/CD which requires being able to non-interactively connect your org. The plugin takes care of creating the certificate and private key, creating and assigning permission sets, and creating the actual connected app. It even tells you exactly which `sfdx` command to include in your CI pipeline script to connect to the org. The plugin is agnostic of which CI/CD tool you happen to use.

-   [sfdx-hardis](https://github.com/hardisgroupcom/sfdx-hardis) ([Hardis Group](https://www.customer-platform.com/), [@hardisgroupcom](https://github.com/hardisgroupcom))

    A lot of commands allowing to orchestrate sfdx commands and other sfdx plugins commands in order to easy the use of Git and Salesforce DX
    
-   [Aura Helper SFDX](https://github.com/JJLongoria/aura-helper-sfdx) ([@JJLongoria](https://github.com/JJLongoria))

    Powerfull plugins to work with Salesforce Projects. Has commands to create packages from GIT differences (Between branches, commits, tags and more), merge several packages into one file by type among other options, list and describe metadata from your local project or connected org, compare metadata between two orgs or between your local project and the project org, check dependencies errors or repair it automatically, import and export data in tree format (including relationships) without salesforce limits, execute an apex anonymous script file iteratively an N selected times and other interesting tools (and future features). Designed to support devops and CI workflows. Work with source and Metadata API Formats and Support Aura Helper VSCode Extension. (Developed using Aura Helper NodeJS Framework).  

-   [sfdx-deliverability-access](https://github.com/gfarb/sfdx-deliverability-access) ([@gfarb](https://github.com/gfarb))

    Uses Selenium, Chromedriver and headless browsing to set Email Deliverability Access Level via command line (works in CI/CD flows)

-   [move-qcp](https://github.com/PreziosiRaffaele/move-qcp) ([@PreziosiRaffaele](https://github.com/PreziosiRaffaele))

    The Javascript Quote Calculator Plugin is useful to add extra functionality to the quote line editor in Salesforce CPQ.
Unfortunately the code is stored as data within Salesforce, making it difficult to manage and track changes effectively.
With this plugin, you can now create a dedicated QCP folder within your repository and effortlessly deploy it to the target org.

-   [kc-sf-plugin](https://github.com/k-capehart/kc-sf-plugin) (Kyle Capehart, [@k-capehart](https://github.com/k-capehart))

    Various commands including automatic generation of Apex Trigger frameworks. Create custom templates to quickly create standardized triggers, handler classes, test classes, and fields for a given Salesforce object. Also, display differences between source tracked org and local project.

-   [lightning-flow-scanner](https://github.com/Lightning-Flow-Scanner/lightning-flow-scanner-sfdx) ([Lightning Flow Scanner Group](https://github.com/Lightning-Flow-Scanner))

    Pinpoint deviations from Industry Best Practices in Salesforce Flows, ensuring standards of business automation excellence.

-   [sfdx-git-delta]([https://github.com/Lightning-Flow-Scanner/lightning-flow-scanner-sfdx](https://github.com/scolladon/sfdx-git-delta)) ([@scolladon](https://github.com/scolladon))

    SFDX plugin to generate Incremental Salesforce deployments manifests and artifacts.

-   [sf-decomposer](https://github.com/mcarvin8/sf-decomposer) ([@mcarvin8](https://github.com/mcarvin8))

    Plugin to create smaller metadata files for version control and recombine them for deployments.

-   [apex-code-coverage-transformer](https://github.com/mcarvin8/apex-code-coverage-transformer) ([@mcarvin8](https://github.com/mcarvin8))

    Plugin to create Apex code coverage files in SonarQube or Cobertura format.

-   [sf-package-combiner](https://github.com/mcarvin8/sf-package-combiner) ([@mcarvin8](https://github.com/mcarvin8))

    Plugin to combine multiple manifest files (package.xml) into 1 for deployments.

-   [apex-tests-list](https://github.com/renatoliveira/apex-test-list) ([@renatoliveira](https://github.com/renatoliveira))

    List Apex tests for your CI/CD pipeline.

## Not plugins, but useful

-   [yo-sfdx-commands-generator](https://github.com/vyuvalv/yo-sfdx-commands-generator) (Yuval Vardi) [](https://github.com/vyuvalv)

    interactive generators for projects and scratch org features/settings

-   [yo-sfdx-commands-autocomplete](https://github.com/vyuvalv/yo-sfdx-commands-autocomplete) (Yuval Vardi) [](https://github.com/vyuvalv)

    run commands interactively (autocomplete for sfdx commands and flags)

## IDE Plugins

-   [vscode-sfdx-hardis](https://github.com/hardisgroupcom/vscode-sfdx-hardis) ([Hardis Group](https://www.customer-platform.com/), [@hardisgroupcom](https://github.com/hardisgroupcom))

    [Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=NicolasVuillamy.vscode-sfdx-hardis) with a menu and UI integration allowing to use Git and Salesforce DX without knowing Git or Salesforce DX

## Documentation

-   [Oclif](https://oclif.io/)

    A few layers down the stack, and for when you want to build CLI for other things that may not be sfdx-specific

-   [Plugin developer guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_plugins.meta/sfdx_cli_plugins/cli_plugins_architecture_sf_cli.htm)

## Issues

core sfdx commands have an [issues-only repo](https://github.com/forcedotcom/cli)
