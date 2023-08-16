<div align="center">
	<img width="500" height="350" src="./media/logo.svg" alt="Awesome">
	<br>
	<br>
	<a href="https://awesome.re">
		<img src="https://awesome.re/badge-flat.svg" alt="Awesome">
	</a>
	<br>
</div>

# Awesome Adobe Launch

A curated list of awesome resources for Adobe Experience Platform Tags (Formerly known as Adobe Launch). 

Is this list missing something? I'd love to get your feedback! [Learn more](./CONTRIBUTING.md) about contributing to 
the list.

## Contents
 * [Using Launch](#using-launch)
   * [Migrating to Launch](#migrating-to-launch)
   * [Tutorials](#tutorials)
   * [Recommended Blogs](#recommended-blogs)
   * [Tools / Useful Services](#tools--useful-services)
   * [Browser Extensions](#browser-extensions)
   * [Getting Help](#getting-help)
 * [Extension Development](#extension-development)
   * [Building Extensions](#building-extensions)
   * [Example Extensions](#example-extensions)
   * [Extension Development Packages](#extension-development-packages)
 * [API Development](#api-development)


## Using Launch


#### Migrating to Launch

*A few resources on migrating to Launch. Reminder that you have until [2020-10-14 to migrate from DTM](https://medium.com/launch-by-adobe/dtm-plans-for-a-sunset-3c6aab003a6f)!*

 * [Common DTM to Launch Migration Issues](https://techdocs.searchdiscovery.com/adobe-solutions/dtm-to-launch-migration/most-common-issues) - Search Discovery's most commonly found issues when migrating to Launch.
 * [DTM to Launch Assessment App](https://www.searchdiscovery.com/solutions/partners/adobe/adobe-launch/dtm-launch-assessment/) - Search Discovery's tool to evaluate the migration readiness of your DTM container.
 * [DTM to Launch Migration Series](https://33sticks.com/dtm-launch-migration-series-1-options-considerations/) - 33 Sticks DTM to Launch migration series.
 * [Migrating from DTM to Launch](https://medium.com/launch-by-adobe/migrating-from-dtm-to-launch-57548251a86d) - Ben Robison from Adobe covers the migration process.


#### Tutorials

*Tutorials that cover various aspects of using Launch.*

 * [Adobe Experience Cloud Core Services Tutorials](https://docs.adobe.com/content/help/en/core-services-learn/tutorials/overview.html) - A collection of how-to videos and tutorials to make you a power-user of Adobe Experience Cloud Core Services.


#### Recommended Blogs

*These blogs have a primary focus on analytics, testing, and tag management. While not all entries are specific to Adobe 
Launch, the links below are pointing to the most relevant category.*

 * [33 Sticks](https://33sticks.com/category/tms/) - 33Sticks, an analytics boutique, covers a wide variety of topics for Adobe Launch.
 * [Adobe Tech Blog](https://medium.com/adobetech/search?q=launch) - The official Adobe Launch blog with technical articles from the Adobe team.
 * [Analytics Demystified](https://analyticsdemystified.com/tag-management/) - Analytics Demystified, a consulting group, covers a wide variety of topics for Adobe Launch.
 * [Datanalyst](https://www.datanalyst.info/category/web_analytics/adobe-launch/) - Julien Piccini's blog that focuses on the technical side of Adobe products, including examples on how to build Launch extensions.
 * [Digital Data Tactics](https://www.digitaldatatactics.com/index.php/category/dtm/launch/) - Jenn Kunz's blog has more technical-focused articles about Adobe Launch as well a variety of other analytics related topics.
 * [Evolytics](https://www.evolytics.com/blog/category/data-collection/) - Evolytics, a consulting group, has a variety of topics for Adobe Launch including extension development articles.
 * [Jimalytics](https://jimalytics.com/tag/adobe-launch/) - Jim Gordon's blog focuses on the technical aspects of the strategy and deployment of tag managers and analytics tools.
 * [Search Discovery](https://www.searchdiscovery.com/?s=launch) - Search Discovery, a consulting group, has a wide variety of topics for Adobe Launch.
 * [Web Analytics for Developers](https://webanalyticsfordevelopers.com/category/launch/) - Jan Exner's blog focuses on helping web developers implement Adobe Analytics, Launch, and more.


#### Tools / Useful Services

*Various services and tools that help you understand what is happening with Launch*

 * [Launch Library Parser](https://launch-parser.com/) - A library parser that detects potential problems, allows you to search for specific code, and see visualizations from the library's dependencies. Built by Urs Boller.
 * [reactor-downloader](https://github.com/adobe/reactor-downloader) - A command line tool for downloading a Launch property to a local directory.
 * [reactor-sync](https://github.com/adobe/reactor-sync) - A command line tool for syncing data to and from Adobe Launch to a local directory.


#### Browser Extensions

*Browser extensions that will make your life easier when deploying and troubleshooting Adobe Launch.*

 * [Adobe Experience Cloud](https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/) 
   [![Chrome](./media/chrome_16x16.png)](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj)
   \- A multi-purpose extension that gives insights to all Adobe products on the page, including switching the environment for Adobe Launch.
 * [dataslayer](https://dataslayer.org/) 
   [![Chrome](./media/chrome_16x16.png)](https://chrome.google.com/webstore/detail/dataslayer/ikbablmmjldhamhcldjjigniffkkjgpo) 
   [![Firefox](./media/firefox_16x16.png)](https://addons.mozilla.org/en-US/firefox/addon/dataslayer-firefox/)
   \- Debug the rules that Adobe Launch triggers.
 * [Launch and DTM Switch](https://www.searchdiscovery.com/how-we-help/technology/adobe-extensions/)
   [![Chrome](./media/chrome_16x16.png)](https://chrome.google.com/webstore/detail/adobe-dtm-switch/nlgdemkdapolikbjimjajpmonpbpmipk?hl=en)
   \- Allows environment selection and debug toggling for both Adobe DTM & Launch.
 * [Tagtician](https://tagtician.com/)
   [![Chrome](./media/chrome_16x16.png)](https://chrome.google.com/webstore/detail/tagtician-for-adobe-dtm/hiaoiehpkillodoeillmodjcadmfmcbg)
   \- Debug Adobe DTM & Launch libraries on your site.
 * [TALES](https://chrome.google.com/webstore/detail/tagticians-adobe-launch-e/gcoendnefeheadmoidembdncjohflakd)
   [![Chrome](./media/chrome_16x16.png)](https://chrome.google.com/webstore/detail/tagticians-adobe-launch-e/gcoendnefeheadmoidembdncjohflakd?hl=en) - Tagtician's Adobe Launch Enhancement Suite (TALES) updates the Adobe Launch UI, making it easier to navigate.


#### Getting Help

*There are several places to get help if you're stuck working with Adobe Launch.*

 * [Adobe Launch Developers Slack](http://join.launchdevelopers.chat/) - A Slack workspace for developers working on Launch extensions and the Launch API.
 * [Adobe Launch Forums](https://forums.adobe.com/community/experience-cloud/platform/launch) - The official Adobe Launch community forums.
 * [#measure Slack](https://www.measure.chat/) - A Slack workspace for all aspects of marketing technologies, including a dedicated channel for Adobe Launch.


## Extension Development

 
#### Building Extensions

 * [Official Documentation](https://experienceleague.adobe.com/docs/experience-platform/tags/extension-dev/overview.html)
 * [Extension Build Tutorial](https://www.youtube.com/watch?v=rxjtC9o4rl0) - Aaron Hardy walks through the entire extension development process in this video.


#### Example Extensions

 * [Hello World](https://github.com/adobe/reactor-helloworld-extension) - A simple hello world extension.
 * [Toaster Extension](https://github.com/Aaronius/toaster) - Add toast messages to your site.
 * [Sample Launch Extension](https://github.com/PerficientDigital/Sample-Launch-Extension) - A sample launch extension using gulp and eleventy to build the views, by Perficient Digital.
 

#### Extension Development Packages

*NPM Packages that will make your life easier when developing Launch extensions.*

 * [Extension Scaffolding](https://www.npmjs.com/package/@adobe/reactor-scaffold) - Quickly set up the initial extension files and folder structure.
 * [Extension Sandbox](https://www.npmjs.com/package/@adobe/reactor-sandbox) - Manually test your extensions locally.
 * [Extension Validator](https://www.npmjs.com/package/@adobe/reactor-validator) - Validate your extension (_note:_ this is included in several of the other development packages already).
 * [Extension Packager](https://www.npmjs.com/package/@adobe/reactor-packager) - Validate and package your extension.
 * [Extension Uploader](https://www.npmjs.com/package/@adobe/reactor-uploader) - A helper package to upload your Launch extension to Adobe's servers.
 * [Extension Releaser](https://www.npmjs.com/package/@adobe/reactor-releaser) - A helper package to release your Launch extension.

## API Development

 * [Official Documentation](https://experienceleague.adobe.com/docs/experience-platform/tags/api/overview.html?lang=en)
 * [Reactor Postman](https://github.com/adobe/reactor-postman) - A collection of examples for [Postman](https://www.getpostman.com/) with the Launch API

### SDKs

*Here are SDKs to help make developing with the API easier. Note that not all of these are supported by Adobe.*

 * [C#](https://github.com/chancity/Adobe-Reactor-Api-CSharp)
 * [JavaScript](https://github.com/adobe/reactor-sdk-javascript)
 * [Python](https://github.com/pitchmuc/pylaunch)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Philip Lawrence](https://misterphilip.com) has waived all copyright and related or neighboring rights to this work.
