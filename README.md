<div align="center">
	<img width="500" height="350" src="./media/logo.svg" alt="Awesome">
	<br>
	<br>
	<a href="https://awesome.re">
		<img src="https://awesome.re/badge-flat.svg" alt="Awesome">
	</a>
	<br>
	<sub>Follow me on <a href="https://twitter.com/_MisterPhilip">Twitter</a> for more Launch stuff!</sub>
</div>

# Awesome Adobe Launch

A curated list of awesome resources for Adobe Launch. 

Is this list missing something? I'd love to get your feedback! [Learn more](./CONTRIBUTING.md) about contributing to 
the list.

## Contents
 * [Using Launch](#using-launch)
   * [Migrating to Launch](#migrating-to-launch)
   * [Recommended Blogs](#recommended-blogs)
   * [Browser Extensions](#browser-extensions)
   * [Getting Help](#getting-help)
 * [Extension Development](#extension_development)
   * [Building Extensions](#building-extensions)
   * [Example Extensions](#example-extensions)
   * [Extension Development Packages](#extension-development-packages)
 * [API Development](#api_development)


## Using Launch


#### Migrating to Launch

*A few resources on migrating to Launch.*

 * [DTM to Launch Assessment App](https://www.searchdiscovery.com/solutions/partners/adobe/adobe-launch/dtm-launch-assessment/) - Search Discovery's tool to evaluate the migration readiness of your DTM container.
 * [Migrating from DTM to Launch](https://medium.com/launch-by-adobe/migrating-from-dtm-to-launch-57548251a86d) - Ben Robison from Adobe covers the migration process.

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
 * [MisterPhilip](https://misterphilip.com/tag/adobe-launch/) - Philip Lawrence's blog focus primarily on the technical aspects of Adobe Launch.
 * [Search Discovery](https://www.searchdiscovery.com/?s=launch) - Search Discovery, a consulting group, has a wide variety of topics for Adobe Launch.
 * [Web Analytics for Developers](https://webanalyticsfordevelopers.com/category/launch/) - Jan Exner's blog focuses on helping web developers implement Adobe Analytics, Launch, and more.


#### Tutorials

*Tutorials that cover various aspects of using Launch.*

 * [Adobe Experience Cloud Core Services Tutorials](https://docs.adobe.com/content/help/en/core-services-learn/tutorials/overview.html) - A collection of how-to videos and tutorials to make you a power-user of Adobe Experience Cloud Core Services.

#### Browser Extensions

*Browser extensions that will make your life easier when deploying and troubleshooting Adobe Launch.*

 * [Adobe Experience Cloud](https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/) 
   [![Chrome](./media/chrome_16x16.png)](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj)
   \- A multi-purpose extension that gives insights to all Adobe products on the page, including switching the environment for Adobe Launch.
 * [dataslayer](https://dataslayer.org/) 
   [![Chrome](./media/chrome_16x16.png)](https://chrome.google.com/webstore/detail/dataslayer/ikbablmmjldhamhcldjjigniffkkjgpo) 
   [![Firefox](./media/firefox_16x16.png)](https://addons.mozilla.org/en-US/firefox/addon/dataslayer-firefox/)
   \- Debug the rules that Adobe Launch triggers.
 * [Launch and DTM Switch](https://www.searchdiscovery.com/solutions/partners/adobe/adobe-launch/launch-dtm-switch/)
   [![Chrome](./media/chrome_16x16.png)](https://chrome.google.com/webstore/detail/adobe-dtm-switch/nlgdemkdapolikbjimjajpmonpbpmipk?hl=en)
   \- Allows environment selection and debug toggling for both Adobe DTM & Launch.
 * [Tagtician](https://tagtician.com/)
   [![Chrome](./media/chrome_16x16.png)](https://chrome.google.com/webstore/detail/tagtician-for-adobe-dtm/hiaoiehpkillodoeillmodjcadmfmcbg)
   \- Debug Adobe DTM & Launch libraries on your site.



#### Getting Help

*There are several places to get help if you're stuck working with Adobe Launch.*

 * [Adobe Launch Developers Slack](http://join.launchdevelopers.chat/) - A Slack workspace for developers working on Launch extensions and the Launch API.
 * [Adobe Launch Forums](https://forums.adobe.com/community/experience-cloud/platform/launch) - The official Adobe Launch community forums.
 * [#measure Slack](https://www.measure.chat/) - A Slack workspace for all aspects of marketing technologies, including a dedicated channel for Adobe Launch.



## Extension Development

 
#### Building Extensions

 * [Official Documentation](https://developer.adobelaunch.com/extensions/)
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

 * [Official Documentation](https://developer.adobelaunch.com/api/)

### SDKs

*Here are SDKs to help make developing with the API easier. Note that not all of these are supported by Adobe.*

 * [C#](https://github.com/chancity/Adobe-Launch-API-Client)
 * [JavaScript](https://github.com/adobe/reactor-sdk-javascript)
 * [Python](https://github.com/pitchmuc/pylaunch)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Philip Lawrence](https://misterphilip.com) has waived all copyright and related or neighboring rights to this work.
