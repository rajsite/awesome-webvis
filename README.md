<div align="center">
    <div>
        <!-- WebVI logo Copyright 2019 National Instruments -->
        <a href="https://www.webvi.io">
            <img width="140" height="140" src="assets/logo.png" alt="Awesome WebVIs">
        </a>
    </div>
    <br>
    <a href="https://awesome.re">
        <img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
    </a>
    <br>
    <p align="center">
        <a href="https://www.webvi.io">Visit webvi.io</a>&nbsp;&nbsp;&nbsp;
        <a href="#what-are-webvis">What are WebVIs</a>&nbsp;&nbsp;&nbsp;
        <a href="https://www.ni.com/en-us/support/downloads/software-products/download.labview-nxg-web-module.html">Download</a>&nbsp;&nbsp;&nbsp;
        <a href="CONTRIBUTING.md">Contribute Awesome WebVIs</a>
    </p>
</div>

# Awesome WebVIs

A curated list of awesome WebVIs and resources for making awesome free-range organic WebVIs 🤘.

## Contents

- [What are WebVIs](#what-are-webvis)
- [Latest News](#latest-news)
- [Documentation](#documentation)
- [Add-Ons](#add-ons)
- [Tutorials](#tutorials)
- [Presentations](#presentations)
- [Just for Fun](#just-for-fun)
- [Spotted in the Wild](#spotted-in-the-wild)
- [Experimental](#experimental)
- [Non-English Resources](#non-english-resources)

## What are WebVIs

WebVIs are web applications created using the LabVIEW NXG Web Module 🧙‍♂️.

WebVIs build standalone HTML + JS + CSS webpages that can acquire data (usually from a web service), do some analysis, and present the data in scientific and engineering web controls. The Web Module allows you to use LabVIEW graphical programming to create web applications.

Find out more at [webvi.io](https://www.webvi.io) or on NI's [What is the LabVIEW NXG Web Module?](https://www.ni.com/en-us/shop/electronic-test-instrumentation/add-ons-for-electronic-test-and-instrumentation/what-is-labview-nxg-web-module.html) page.

## Latest News

- [LabVIEW NXG Web Module 5.1 New Features and Changes](https://www.ni.com/documentation/en/labview-web-module/5.1/manual/new-features-and-changes/) - LabVIEW NXG and Web Module 5.1 released.
- [Future of the LabVIEW NXG Web Module](https://www.ni.com/en-us/shop/labview/future-of-web-module.html) - LabVIEW NXG development to cease as Web Module and WebVIs become a stand-alone product and continue development.

## Documentation

Documentation and examples provided by National Instruments 🦅.

### Examples

- [Call 3rd Party Web Service](https://github.com/ni/webvi-examples/blob/master/Call3rdPartyWebService) - Acquire data from the US Geological Survey Earthquake API and present in a WebVI. [Demo](https://ni.github.io/webvi-examples/Call3rdPartyWebService/Builds/WebApp_Web%20Server).
- [Call JavaScript From a WebVI](https://github.com/ni/webvi-examples/blob/master/CallJavaScriptFromAWebVI) - Create a JavaScript Library Interface (JSLI) document to interact with JS in a page. [Demo](https://ni.github.io/webvi-examples/CallJavaScriptFromAWebVI/Builds/WebApp_Web%20Server).
- [Call LabVIEW Web Service](https://github.com/ni/webvi-examples/blob/master/CallLabVIEWWebService) - Acquire data with a LabVIEW Web Service to share with a WebVI. [Demo](https://ni.github.io/webvi-examples/CallLabVIEWWebService/Builds/WebApp_Web%20Server).
- [Call SystemLink Data Services](https://github.com/ni/webvi-examples/blob/master/CallSystemLinkDataServices) - Communication with high-level tags, messages, and file APIs included with LabVIEW NXG Web Module. [Demo](https://ni.github.io/webvi-examples/CallSystemLinkDataServices/Builds/Full%20Data%20Services%20App_Web%20Server).
- [Connect WebVI to WebSocket Echo Server](https://github.com/ni/webvi-examples/blob/master/ConnectWebVIToWebSocketEchoServer) - Stream data to WebVIs with WebSockets. [Demo](https://ni.github.io/webvi-examples/ConnectWebVIToWebSocketEchoServer/Builds/WebApp_Web%20Server).
- [Customize WebVI with CSS](https://github.com/ni/webvi-examples/blob/master/CustomizeWithCss) - Advanced customization of a WebVI's style with CSS. [Demo](https://ni.github.io/webvi-examples/CustomizeWithCss/Builds/WebApp_Web%20Server).
- [Embed Content into a WebVI](https://github.com/ni/webvi-examples/blob/master/EmbedContentIntoWebVI) - Add custom HTML to a WebVI. [Demo](https://ni.github.io/webvi-examples/EmbedContentIntoWebVI/Builds/WebApp_Web%20Server).
- [Incorporate User Resource into WebVI](https://github.com/ni/webvi-examples/blob/master/IncorporateUserResources) - Add resource files such as images, CSS files, JavaScript files, and HTML files to your web application. [Demo](https://ni.github.io/webvi-examples/IncorporateUserResources/Builds/WebApp_Web%20Server).
- [Multiple Top-Level WebVIs](https://github.com/ni/webvi-examples/blob/master/MultipleTopLevelWebVIs) - Create a web application with multiple pages linked together. [Demo](https://ni.github.io/webvi-examples/MultipleTopLevelWebVIs/Builds/WebApp_Web%20Server).
- [SystemLink Web Interface Template](https://github.com/ni/systemlink-web-interface-template) - Create custom tiles for WebVIs on the NI Web Server landing page. [Forum post describing configuration](https://forums.ni.com/t5/SystemLink/Webvi-plugin-template-required-changes-to-avoid-duplicates/m-p/4036080/highlight/true#M1338).

### Manuals

- [LabVIEW NXG Web Module](http://www.ni.com/documentation/en/labview-web-module) - Creating, building, and hosting WebVIs.
  - [Communicating Data with Web Services Using WebVIs](http://www.ni.com/documentation/en/labview-web-module/latest/manual/communicating-data-with-webvi/)
  - Hosting WebVIs - [NI Web Server](http://www.ni.com/documentation/en/labview-web-module/latest/manual/hosting-ni-web-server), [LabVIEW Web Service](http://www.ni.com/documentation/en/labview-web-module/latest/manual/hosting-labview-server), and [SystemLink Cloud](http://www.ni.com/documentation/en/systemlink-cloud/latest/manual/hosting-web-application-on-systemlink-cloud).
- [SystemLink Cloud](http://www.ni.com/documentation/en/systemlink-cloud) - Cloud service from NI to securely make WebVIs available on the internet.
- [HTTP Nodes](http://www.ni.com/documentation/en/labview/latest/node-ref/http-nodes) - LabVIEW HTTP Nodes documentation with important compatibility notes for WebVIs (Web Server target).

### Training

- [Creating Web Applications Using LabVIEW NXG](https://education.ni.com/training/resources/1330/creating-web-applications-using-labview-nxg) - Online training course introducing WebVIs and guiding you through creation and publishing of a WebVI.
- [Build a Web App for Your Test System in 30 Minutes](https://event.on24.com/eventRegistration/EventLobbyServlet?target=reg30.jsp&referrer=&eventid=2503837&sessionid=1&key=31D72E0DC82DF56CB36E1F1C341A479C&regTag=&sourcepage=register) - Course showing how to web-enable an existing LabVIEW test system with LabVIEW NXG Web Module and SystemLink Cloud. **Registration required (free)**.

### Forums

- [Example Code](https://forums.ni.com/t5/Example-Code/tkb-p/3039/label-name/software-labview%20nxg%20web%20module?labels=software-labview%20nxg%20web%20module) - Examples tagged as `LabVIEW NXG Web Module` in the NI Example Code forum.

### Videos

- [LabVIEW NXG: Getting started with Web VIs](https://www.youtube.com/watch?v=2R5x5bzp3uk) - Introduction to the WebVI editing experience in NXG 2.

## Add-Ons

Libraries from the community to add new capabilities to WebVIs 🧩.

<!--lint ignore double-link-->
- [Debug Tools for WebVIs](https://bit.ly/debugtools) - Advanced debugging tools for WebVIs. Includes the Debug Log VI to enable logging arbitrary values to the console. See [`bit.ly/debugtools`](https://bit.ly/debugtools).
- [ECharts](https://github.com/rajsite/webvi-experiments/tree/master/ECharts) - 2D and 3D charting libraries. [Demo](https://rajsite.github.io/webvi-experiments/ECharts).
- [File](https://github.com/rajsite/webvi-experiments/tree/master/File) - Open, modify, and download files from the browser. Capture and preview images using the Uppy library.
- [Map](https://github.com/rajsite/webvi-experiments/tree/master/Map) - Interactive maps and markers. Google Maps and Leaflet + Open Street Maps examples. [Demo](https://rajsite.github.io/webvi-experiments/Leaflet).
- [Rich Text](https://github.com/rajsite/webvi-experiments/tree/master/RichText) - Different rich text editor examples. Demos for [CKEditor](https://rajsite.github.io/webvi-experiments/RichText/ckeditor.html), [Quill](https://rajsite.github.io/webvi-experiments/RichText/quill.html), and [Trix](https://rajsite.github.io/webvi-experiments/RichText/trix.html).
- [Sweet Alert](https://forums.ni.com/t5/Example-Programs/SweetAlert-Highly-configurable-popups-for-WebVIs-in-LabVIEW-NXG/ta-p/4011222) - Highly configurable modal dialogs. [Demo](https://rajsite.github.io/webvi-experiments/SweetAlert).

## Tutorials

Tutorials, blogs, hands-ons, social media, and articles on WebVIs 📰.

### Articles

- [Boring Engineer: Web Monitor and Control application using NI SystemLink APIs](https://boringengineer.com/2018/10/21/web-monitor-and-control-application-using-ni-systemlink-apis) - WebVIs + SystemLink APIS for monitoring. October 2019.
- [TestStand Executor](https://github.com/joshuaprewitt/teststand-executor) - WebVIs + SystemLink to remotely execute TestStand sequences. October 2019.
- [SystemLink file browser](https://github.com/joshuaprewitt/systemlink-file-browser) - Use SystemLink jobs to read a file in a WebVI from a RT target. [Community](https://forums.ni.com/t5/SystemLink/Target-User-Management-Feature-and-other-features-of-target-web/m-p/3972164/highlight/true?profile.language=en#M1073). September 2019.
- [Hands-on: Create Web-Ready User Interfaces with the LabVIEW NXG Web Module](https://github.com/eyesonvis/niweek2019-webVI-hands-on) - Create WebVIs that communicate with LabVIEW applications. NIWeek May 2019.
- [Boring Engineer: NI Web Technology: Monitor and Control Systems](https://boringengineer.com/2018/07/29/ni-web-technology-monitor-and-control-systems) - WebVIs + LabVIEW Web Services for monitoring. July 2018.
- [Boring Engineer: NXG WebVI: How to access and embed web service and resources](https://boringengineer.com/2018/07/15/webvi-accessing-and-embedding-web-service-and-resources) - Embed images, iframes, and use HTTP with web services. July 2018.
- [Boring Engineer: NXG WebVI : Develop, Deploy and Host a Simple Web Game](https://boringengineer.com/2018/07/15/develop-deploy-host-webvi) - Learn the basics of making WebVIs by creating a math game! July 2018.
- [Latest enhancements to LabVIEW NXG include WebVI, expanded instrument coverage](https://www.testandmeasurementtips.com/latest-enhancements-labview-nxg-include-webvi-expanded-instrument-coverage) - WebVIs are here! January 2018.
- [First WebVI Prototype](https://github.com/rajsite/webvi-experiments/tree/master/FirstPrototype) - The first `Hello World!` of WebVIs. [Demo](https://rawcdn.githack.com/rajsite/webvi-experiments/8a0858cb5d4a2e301a9dc9c8f6f363530d7f096e/FirstPrototype/test.html). May 2013.

### Social media

- [@wimtormans on twitter](https://twitter.com/wimtormans/status/1125314404562681856) - *"Finally had some time to do some work on my hobby project. Indoor monitoring with #LabVIEW on a #RaspberryPi and visualize the data with a #LabVIEWNXG #WebVI on a #SystemLink server… Everything is running at the @VI_Technologies offices :-)"* - WebVIs on Raspberry Pis! [Source](https://github.com/wimtormans/LabVIEWRaspberryPI_IndoorMonitoring). May 2019.
- [@rajsite on twitter](https://twitter.com/rajsite/status/955978573181079552) - *"THE #WebVI IS NOW OFFICIALLY RELEASED IN LabVIEW NXG 2 WEB MODULE! WE MADE A THING, USE IT TO MAKE SOME TOO! @NIglobal @LabVIEW #LabVIEW #NXG"* - WebVIs released! 🎉. January 2018.
- [@rajsite on twitter](https://twitter.com/rajsite/status/867074013478170624) - *"LabVIEW running in a browser with the #WebVI and LabVIEW NXG 2 Beta! #LabVIEW #NIWeek #NIWeek2017"* - NI showing WebVIs as would first be available in the NXG 2.0 beta. NIWeek May 2017.
- [@rajsite on twitter](https://twitter.com/rajsite/status/760869975363944448) - *"A glimpse into the future! 🔮✨ #WebVI @LabVIEW #NIWeek2016 #NIWeek"* - NI first teasing WebVI technology. NIWeek August 2016.

## Presentations

Presentations about WebVIs from NIWeek, LabVIEW User Groups, and the community 🗣.

- [NXG WebVIs and SystemLink Tags​](https://forums.ni.com/t5/Minneapolis-LabVIEW-User-Group/NXG-Web-VIs-and-SystemLink-Tags/gpm-p/3975714) - Working with Symation to make a tablet UI to communicate with a PLC and other instruments. October 2019.
<!--lint ignore double-link-->
- [Creating Powerful Web Apps With the LabVIEW NXG Web Module](https://www.youtube.com/watch?v=AjAXcuzY9rk) - Matthias details creating a sophisticated web application with a responsive UI, user login, and database backend. [Studio Bods](https://www.studiobods.com/en/niweek2019-ts170) / [LabVIEW Wiki](https://labviewwiki.org/wiki/NIWeek_2019). NIWeek May 2019.
<!--lint ignore double-link-->
- [Customizing Your WebVIs](https://www.youtube.com/watch?v=Q19tdIw5MgE) - Darin and Milan follow-up the NIWeek 2018 presentation talking about styling WebVIs and creating Add-On libraries with the JSLI. [Community page](https://forums.ni.com/t5/LabVIEW-Web-Development/NIWeek-2019-Customizing-Your-WebVIs/ta-p/3928168) / [LabVIEW Wiki](https://labviewwiki.org/wiki/NIWeek_2019). NIWeek May 2019.
- [Using LabVIEW NXG Web Technologies to Enhance Existing Applications](https://www.youtube.com/watch?v=eGWHaZC2t2g) - Rita introduces WebVIs and shows communication techniques and Matthias introduces creating web applications backed by databases. [LabVIEW Wiki](https://labviewwiki.org/wiki/NIWeek_2019). NIWeek May 2019.
- [LabVIEW NXG web module Remote server client](https://www.youtube.com/watch?v=v81cUhdLeIc) - Creating a WebVI, setting up the NI Web Server, testing, and deploying a WebVI. June 2018.
- [Styling and Customizing WebVIs](https://education.ni.com/center-of-excellence/resources/1144/styling-and-customizing-webvis) - Mark and Milan go over common styling scenarios, a deep dive using devtools to style WebVIs, and tease the future of the JSLI document. NIWeek May 2018.
- [Creating Web Enabled HMIs with LabVIEW NXG](https://www.youtube.com/watch?v=N4XCNfGapc4) - WebVI demonstration by Omid, Mark, and Eli. NIWeek May 2017.

## Just for Fun

Games and other fun WebVIs you can play right away in the browser 🕹.

- [Avalanche 🌠](https://rajsite.github.io/webvi-experiments/Avalanche) - Dodge the shooting stars. [Source](https://github.com/rajsite/webvi-experiments/tree/master/Arcade/Avalanche/nxg).
- [Cyclone 🌀](https://boringengineer.com/gameview/cyclone/) - Use your reflexes to land on the cyclone. [Homepage](https://boringengineer.com/gameview/home/). [Source](https://github.com/navinsubramani/BoringGames).
- [Dr. Emoji 💊](https://rajsite.github.io/webvi-experiments/DrEmoji) - Save the animals by matching their hearts ❤💙💛. [Source](https://github.com/rajsite/webvi-experiments/tree/master/Arcade/DrEmoji/nxg).
<!--lint ignore double-link-->
- [Fire 🔥](https://rajsite.github.io/webvi-experiments/build/Fire) - The PSX Doom fire animation ported to [HTML 5](https://github.com/fabiensanglard/DoomFirePSX) to [LabVIEW](https://github.com/dataflowg/labview-psx-doom-fire) to [LabVIEW NXG](https://github.com/rajsite/webvi-experiments/tree/master/Arcade/Fire) to [WebVIs](https://github.com/rajsite/webvi-experiments/tree/master/Arcade/Fire). [Source](https://github.com/rajsite/webvi-experiments/tree/master/Arcade/Fire).
- [Nibbles 🐍💡](http://ccm-ee.com/Nibbles/Nibbles.html) - Snake made out of LEDs. [Facebook post](https://www.facebook.com/ccmelectronic/posts/1887095178035968).
- [Reflex tester 👉](https://rajsite.github.io/webvi-experiments/Reflex) - Test your reflexes. [Source](https://github.com/rajsite/webvi-experiments/tree/master/Arcade/Reflex).
- [Snake 🐍](https://rajsite.github.io/webvi-experiments/Snake) - Snake with extra steps. [Source](https://github.com/rajsite/webvi-experiments/tree/master/Arcade/Snake/nxg).

## Spotted in the Wild

Screenshots and videos of WebVIs being used inconspicuously in the wild 🔍.

- [DAM Group Leak Test Platform @ 2:13](https://www.youtube.com/watch?v=REhYcX-w3iU&t=133) - Looks like the NXG 2 button border style. Not running in a normal browser. Awesome music. <br> Rating ⭐⭐⭐⭐⭐.
- GCentral - The [GCentral Package Search](https://www.gcentral.org) tool is a WebVI. A sophisticated LabVIEW Web Service backend with user authentication, database storage, and a WebVI frontend. [Source](https://github.com/gcentral/Website). <br> Rating ⭐⭐⭐⭐⭐.

Discover WebVIs on GitHub using the [`webvi`](https://github.com/topics/webvi) GitHub topic, find WebVI source by searching for the [`gviweb`](https://github.com/search?q=VirtualInstrument+extension%3Agviweb&type=Code) file extension, or find [built WebVIs](https://github.com/search?q=enqueue+filename%3A.via.txt&type=Code) with a clever search.

If you find a built WebVI on GitHub you can also use an online tool like [githack.com](https://raw.githack.com) to quickly preview and run the built WebVI in your browser.

## Experimental

Crazy experiments that try to push WebVIs to their limits 🧪.

- [FFTDemo](http://bit.ly/FFTDemo) - Historical experiment using analysis functions in WebVIs.
- [WebVINode](https://github.com/rajsite/webvi-experiments/tree/master/WebVINode) - Create Node.js server and desktop applications from WebVIs.

## Non-English Resources

Awesome WebVI resources in non-english languages 🌐.

- [LabVIEW NXG Web Module Training Slide (Japanese)](https://forums.ni.com/t5/%E3%82%B5%E3%83%B3%E3%83%97%E3%83%AB%E3%82%B3%E3%83%BC%E3%83%89%E3%81%A8%E3%83%89%E3%82%AD%E3%83%A5%E3%83%A1%E3%83%B3%E3%83%88/LabVIEW-NXG-%E3%83%88%E3%83%AC%E3%83%BC%E3%83%8B%E3%83%B3%E3%82%B0%E3%82%B9%E3%83%A9%E3%82%A4%E3%83%89/ta-p/4043720)
- [`Réaliser des applications Web avec LabVIEW (CG & NXG) pour publier vos données`](https://forums.ni.com/t5/luc-desruelle-s-Blogue/R%C3%A9aliser-des-applications-Web-avec-LabVIEW-CG-amp-NXG-pour/ba-p/3943768)
- [`Simuladores - Departamento de Ingeniería Eléctrica - Universidad de Valladolid`](http://die.uva.es/simuladores)
  - [`Corriente Alterna`](http://simuladoresdie.uva.es/alterna)
  - [`Transitorios eléctricos`](http://simuladoresdie.uva.es/transitorios)
  - [`Máquina asíncrona`](http://simuladoresdie.uva.es/asincrona)
  - [`Teorema de Ferraris`](http://simuladoresdie.uva.es/ferraris)
  - [`Transformadores eléctricos`](http://simuladoresdie.uva.es/transformador)
- [`NIが提供する新しい遠隔監視ツール 「SystemLink」を学ぼう`](https://forums.ni.com/t5/LabVIEW-Caf%C3%A9/NI%E3%81%8C%E6%8F%90%E4%BE%9B%E3%81%99%E3%82%8B%E6%96%B0%E3%81%97%E3%81%84%E9%81%A0%E9%9A%94%E7%9B%A3%E8%A6%96%E3%83%84%E3%83%BC%E3%83%AB-SystemLink-%E3%82%92%E5%AD%A6%E3%81%BC%E3%81%86/gpm-p/3967644)
- [`LabView NXG si aggiorna: arrivano i WebVI`](https://www.innovationpost.it/2018/01/25/labview-nxg-si-aggiorna-arrivano-webvi)
