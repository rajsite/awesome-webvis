<!-- markdownlint-disable MD041 -->
<!--lint disable double-link-->
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
        <a href="https://www.ni.com/en-us/support/downloads/software-products/download.g-web-development-software.html">Download</a>&nbsp;&nbsp;&nbsp;
        <a href="CONTRIBUTING.md">Contribute Awesome WebVIs</a>
    </p>
</div>

# Awesome WebVIs

A curated list of awesome WebVIs and resources for making awesome free-range organic WebVIs 🤘.

## Contents

- [What are WebVIs](#what-are-webvis)
- [Getting Started](#getting-started)
- [Documentation](#documentation)
- [Add-Ons](#add-ons)
- [Tutorials](#tutorials)
- [Presentations](#presentations)
- [Just for Fun](#just-for-fun)
- [Spotted in the Wild](#spotted-in-the-wild)
- [Experimental](#experimental)
- [Non-English Resources](#non-english-resources)

## What are WebVIs

WebVIs are web applications created using G Web Development Software 🧙‍♂️.

WebVIs build standalone HTML + JS + CSS webpages that can acquire data (usually from a web service), do some analysis, and present the data in scientific and engineering web controls. G Web Development Software allows you to use the LabVIEW graphical programming language (also known as the G programming language) to create web applications.

Find out more at [webvi.io](https://www.webvi.io), on NI's [What Is G Web Development Software?](https://www.ni.com/g-web-development-software) page, or from the video [What is G Web?](https://www.youtube.com/watch?v=agqu6zV5n9s).

## Getting Started

- [How to Build a Web UI for Your LabVIEW-Based Test System](https://www.youtube.com/watch?v=U9IhlcgCU5E) - Christina and Milan give a step-by-step overview of how to modify your LabVIEW test system to web-enable it using G Web Development Software.
- [Resources to help you get started with G Web Development Software](https://forums.ni.com/t5/G-Web-Development-Software/Resources-to-help-you-get-started-with-G-Web-Development/td-p/4174607) - Useful links for getting started with G Web.

## Documentation

Documentation and examples provided by National Instruments 🦅.

### Examples

- [Call 3rd Party Web Service](https://github.com/ni/webvi-examples/blob/main/Call3rdPartyWebService) - Acquire data from the US Geological Survey Earthquake API and present in a WebVI. [Demo](https://ni.github.io/webvi-examples/Call3rdPartyWebService/Builds/WebApp_Default%20Web%20Server/).
- [Call JavaScript From a WebVI](https://github.com/ni/webvi-examples/blob/main/CallJavaScriptFromAWebVI) - Create a JavaScript Library Interface (JSLI) document to interact with JS in a page. [Demo](https://ni.github.io/webvi-examples/CallJavaScriptFromAWebVI/Builds/WebApp_Default%20Web%20Server/).
- [Call LabVIEW Web Service](https://github.com/ni/webvi-examples/blob/main/CallLabVIEWWebService) - Acquire data with a LabVIEW Web Service to share with a WebVI. [Demo](https://ni.github.io/webvi-examples/CallLabVIEWWebService/Builds/WebApp_Default%20Web%20Server/).
- [Call SystemLink Data Services](https://github.com/ni/webvi-examples/blob/main/CallSystemLinkDataServices) - Communication with high-level tags, messages, and file APIs included with G Web Development Software. [Demo](https://ni.github.io/webvi-examples/CallSystemLinkDataServices/Builds/Full%20Data%20Services%20App_Default%20Web%20Server/).
- [Connect WebVI to WebSocket Echo Server](https://github.com/ni/webvi-examples/blob/main/ConnectWebVIToWebSocketEchoServer) - Stream data to WebVIs with WebSockets. [Demo](https://ni.github.io/webvi-examples/ConnectWebVIToWebSocketEchoServer/Builds/WebApp_Default%20Web%20Server/).
- [Customize WebVI with CSS](https://github.com/ni/webvi-examples/blob/main/CustomizeWithCss) - Advanced customization of a WebVI's style with CSS. [Demo](https://ni.github.io/webvi-examples/CustomizeWithCss/Builds/WebApp_Default%20Web%20Server/).
- [Embed Content into a WebVI](https://github.com/ni/webvi-examples/blob/main/EmbedContentIntoWebVI) - Add custom HTML to a WebVI. [Demo](https://ni.github.io/webvi-examples/EmbedContentIntoWebVI/Builds/WebApp_Default%20Web%20Server/).
- [Incorporate User Resource into WebVI](https://github.com/ni/webvi-examples/blob/main/IncorporateUserResources) - Add resource files such as images, CSS files, JavaScript files, and HTML files to your web application. [Demo](https://ni.github.io/webvi-examples/IncorporateUserResources/Builds/WebApp_Default%20Web%20Server/).
- [Multiple Top-Level WebVIs](https://github.com/ni/webvi-examples/blob/main/MultipleTopLevelWebVIs) - Create a web application with multiple pages linked together. [Demo](https://ni.github.io/webvi-examples/MultipleTopLevelWebVIs/Builds/WebApp_Default%20Web%20Server/).
- [SystemLink Web Interface Template](https://github.com/ni/systemlink-web-interface-template) - Create custom tiles for WebVIs on the NI Web Server landing page. [Forum post describing configuration](https://forums.ni.com/t5/SystemLink/Webvi-plugin-template-required-changes-to-avoid-duplicates/m-p/4036080/highlight/true#M1338).

### Manuals

- [G Web Development Software](https://www.ni.com/docs/en-US/bundle/g-web-development/page/manual-overview.html) - Creating, building, and hosting WebVIs.
  - [G Web Development Software API Reference](https://www.ni.com/docs/en-US/bundle/g-web-development-api-ref) - API Reference for VIs and Node in G Web Development Software.
  - [Communicating Data with Web Services Using WebVIs](https://www.ni.com/docs/en-US/bundle/g-web-development/page/communicating-data-with-webvi.html)
  - [Hosting WebVIs](https://www.ni.com/docs/en-US/bundle/g-web-development/page/hosting-web-application-on-server.html) - See several options available for hosting built WebVIs.
- [SystemLink Cloud](https://www.ni.com/docs/en-US/bundle/systemlink-cloud/page/manual-overview.html) - Cloud service from NI to securely make WebVIs available on the internet.
- [HTTP Nodes](https://www.ni.com/docs/en-US/bundle/g-web-development-api-ref/page/http-nodes.html) - LabVIEW HTTP Nodes documentation with important compatibility notes for WebVIs (Web Server target).

### Training

- [Build a Web App for Your Test System](https://bit.ly/3959Smc) - Course showing how to web-enable an existing LabVIEW test system with G Web Development Software and SystemLink Cloud. **Registration required (free)**. [Webinar Example Code](https://forums.ni.com/t5/Example-Code/Webinar-Example-Code-Build-a-Web-App-for-Your-Test-System/ta-p/4175994).
- [Creating Web Applications Using G Web Development Software](https://learn.ni.com/learning-paths/creating-web-applications-using-g-web-development-software) - Online training course introducing WebVIs and guiding you through creation and publishing of a WebVI. **Requires SSP**.

### Forums

- [G Web Development Software Forum](https://forums.ni.com/t5/G-Web-Development-Software/bd-p/g-web-development) - The official community forum for G Web Development Software.
- [Example Code](https://forums.ni.com/t5/Example-Code/tkb-p/3039/label-name/Software-G%20Web%20Development%20Software) - Examples tagged as `Software-G Web Development Software` in the NI Example Code forum.

### Videos

- [What is G Web?](https://www.youtube.com/watch?v=agqu6zV5n9s) - David talks about web application architecture and shows example control and monitoring WebVIs.
- [Tom's LabVIEW Adventure - What's New In LabVIEW 2021 ?!](https://www.youtube.com/watch?v=1hm6ngsSVsw&t=1093s) - Tom shows the G Web Development Software environment and runs a simple WebVI.
- [SystemLink - G Web Development & Deployment](https://www.youtube.com/watch?v=jLvSI_My5yA) - Makkal shows a walkthrough of web application development using G Web Development Software and deploys the web app in SystemLink.

## Add-Ons

Libraries from the community to add new capabilities to WebVIs 🧩.

- [Debug Tools for WebVI](https://bit.ly/debugtools) - Advanced debugging tools for WebVIs. Includes the Debug Log VI to enable logging arbitrary values to the console. See [`bit.ly/debugtools`](https://bit.ly/debugtools).
- [ECharts](https://github.com/rajsite/webvi-experiments/tree/main/ECharts) - 2D and 3D charting libraries. [Demo](https://rajsite.github.io/webvi-experiments/ECharts).
- [File for WebVI](https://forums.ni.com/t5/Example-Code/File-for-WebVI/ta-p/4129229) - Open, modify, and download files from the browser. Capture and preview images using the Uppy library. [Demo](https://rajsite.github.io/webvi-experiments/File/).
- [Maps for WebVI](https://forums.ni.com/t5/Example-Code/Maps-for-WebVI-Google-Maps-and-Open-Street-Maps/ta-p/4106124) - Interactive maps and markers. Google Maps and Leaflet + Open Street Maps examples. [Demo](https://rajsite.github.io/webvi-experiments/Leaflet).
- [Rich Text](https://github.com/rajsite/webvi-experiments/tree/main/RichText) - Different rich text editor examples. Demos for [CKEditor](https://rajsite.github.io/webvi-experiments/RichText/ckeditor.html), [Quill](https://rajsite.github.io/webvi-experiments/RichText/quill.html), and [Trix](https://rajsite.github.io/webvi-experiments/RichText/trix.html).
- [Custom Popup Dialogs for WebVI](https://forums.ni.com/t5/Example-Code/Custom-Popup-Dialogs-for-WebVI-SweetAlert/ta-p/4011222) - Highly configurable modal dialogs. [Demo](https://rajsite.github.io/webvi-experiments/SweetAlert).

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
- [First WebVI Prototype](https://github.com/rajsite/webvi-experiments/tree/main/FirstPrototype) - The first `Hello World!` of WebVIs. [Demo](https://rawcdn.githack.com/rajsite/webvi-experiments/8a0858cb5d4a2e301a9dc9c8f6f363530d7f096e/FirstPrototype/test.html). May 2013.

### Social media

- [G Web Dev Software Tweet Collection](https://twitter.com/rajsite/timelines/1498347150060703744) - Curated tweets about NI G Web Development Software and LabVIEW Web technologies.

## Presentations

Presentations about WebVIs from NIWeek, LabVIEW User Groups, and the community 🗣.

- [All you wanted to know about LabVIEW and Web Services but feared to ask – Part 2](https://www.youtube.com/watch?v=tl19HHisXOc) - Matthias dives into calling web services from LabVIEW. While the presentation does not cover G Web Development Software directly it has invaluable information on using web services which is applicable to all G Web apps. [Studio Bods Abstract](https://bit.ly/GLA2022-WebServices). GLA Summit November 2022.
- [All you wanted to know about LabVIEW and Web Services but feared to ask – Part 1](https://www.youtube.com/watch?v=72hoDQEv-xk) - Matthias gives a great discussion of making Web Services with LabVIEW. Featuring a live audience poll web application made with G Web Development Software. [Studio Bods Abstract](https://bit.ly/GDevCon2022-WebServices). GDevCon September 2022.
- [How to Build a Web UI for Your LabVIEW-Based Test System](https://www.youtube.com/watch?v=U9IhlcgCU5E) - Christina and Milan give a step-by-step overview of how to modify your LabVIEW test system to web-enable it using G Web Development Software. Initially presented at NI Connect May 2022. YouTube recording July 2022.
- [G Web. Is it any good?](https://www.youtube.com/watch?v=UE9S1ADsm_M) - Brian Powell talks about their experience with G Web Development Software web-enabling a data logger LabVIEW application. GDevConNA July 2022.
- [NXG WebVIs and SystemLink Tags​](https://forums.ni.com/t5/Minneapolis-LabVIEW-User-Group/NXG-Web-VIs-and-SystemLink-Tags/gpm-p/3975714) - Working with Symation to make a tablet UI to communicate with a PLC and other instruments. October 2019.
- [Creating Powerful Web Apps With the LabVIEW NXG Web Module](https://www.youtube.com/watch?v=AjAXcuzY9rk) - Matthias details creating a sophisticated web application with a responsive UI, user login, and database backend. [Studio Bods](https://www.studiobods.com/en/niweek2019-ts170). NIWeek May 2019.
- [Customizing Your WebVIs](https://www.youtube.com/watch?v=Q19tdIw5MgE) - Darin and Milan follow-up the NIWeek 2018 presentation talking about styling WebVIs and creating Add-On libraries with the JSLI. [Community page](https://forums.ni.com/t5/LabVIEW-Web-Development/NIWeek-2019-Customizing-Your-WebVIs/ta-p/3928168). NIWeek May 2019.
- [Using LabVIEW NXG Web Technologies to Enhance Existing Applications](https://www.youtube.com/watch?v=eGWHaZC2t2g) - Rita introduces WebVIs and shows communication techniques and Matthias introduces creating web applications backed by databases. [LabVIEW Wiki](https://labviewwiki.org/wiki/NIWeek_2019). NIWeek May 2019.
- [LabVIEW NXG web module Remote server client](https://www.youtube.com/watch?v=v81cUhdLeIc) - Creating a WebVI, setting up the NI Web Server, testing, and deploying a WebVI. June 2018.
- [Styling and Customizing WebVIs](https://www.youtube.com/watch?v=aHWJ1YjgfTI) - Mark and Milan go over common styling scenarios, a deep dive using devtools to style WebVIs, and tease the future of the JSLI document. NIWeek May 2018.
- [Creating Web Enabled HMIs with LabVIEW NXG](https://www.youtube.com/watch?v=N4XCNfGapc4) - WebVI demonstration by Omid, Mark, and Eli. NIWeek May 2017.

## Just for Fun

Games and other fun WebVIs you can play right away in the browser 🕹.

- [Avalanche 🌠](https://rajsite.github.io/webvi-experiments/Avalanche) - Dodge the shooting stars. [Source](https://github.com/rajsite/webvi-experiments/tree/main/Arcade/Avalanche/).
- [Cyclone 🌀](https://boringengineer.com/gameview/cyclone/) - Use your reflexes to land on the cyclone. [Homepage](https://boringengineer.com/gameview/home/).
- [Dr. Emoji 💊](https://rajsite.github.io/webvi-experiments/DrEmoji) - Save the animals by matching their hearts ❤💙💛. [Source](https://github.com/rajsite/webvi-experiments/tree/main/Arcade/DrEmoji/).
- [Fire 🔥](https://rajsite.github.io/webvi-experiments/build/Fire) - The PSX Doom fire animation ported to [HTML 5](https://github.com/fabiensanglard/DoomFirePSX) to [LabVIEW](https://github.com/dataflowg/labview-psx-doom-fire) to [LabVIEW NXG](https://github.com/rajsite/webvi-experiments/tree/main/Arcade/Fire) to [WebVIs](https://github.com/rajsite/webvi-experiments/tree/main/Arcade/Fire). [Source](https://github.com/rajsite/webvi-experiments/tree/main/Arcade/Fire).
- [Nibbles 🐍💡](http://ccm-ee.com/Nibbles/Nibbles.html) - Snake made out of LEDs. [Facebook post](https://www.facebook.com/ccmelectronic/posts/1887095178035968).
- [Reflex tester 👉](https://rajsite.github.io/webvi-experiments/Reflex) - Test your reflexes. [Source](https://github.com/rajsite/webvi-experiments/tree/main/Arcade/Reflex).
- [Snake 🐍](https://rajsite.github.io/webvi-experiments/Snake) - Snake with extra steps. [Source](https://github.com/rajsite/webvi-experiments/tree/main/Arcade/Snake/).
- [T-Rex 🦖](https://boringengineer.com/gameview/T-Rex/LabVIEW%20T-Rex.html) - Your favorite offline dinosaur game made online.

## Spotted in the Wild

Screenshots and videos of WebVIs being used inconspicuously in the wild 🔍.

- [DAM Group Leak Test Platform @ 2:13](https://www.youtube.com/watch?v=REhYcX-w3iU&t=133) - Looks like the NXG 2 button border style. Not running in a normal browser. Awesome music.
- GCentral - The [GCentral Package Search](https://www.gcentral.org) tool is a WebVI. A sophisticated LabVIEW Web Service backend with user authentication, database storage, and a WebVI frontend. [Source](https://github.com/gcentral/Website).

Discover WebVIs on GitHub using the [`webvi`](https://github.com/topics/webvi) GitHub topic, find WebVI source by searching for the [`gviweb`](https://github.com/search?q=VirtualInstrument+path%3Agviweb&type=code) file extension, or find [built WebVIs](https://github.com/search?q=enqueue+path%3A.via.txt&type=code) with a clever search.

If you find a built WebVI on GitHub you can also use an online tool like [githack.com](https://raw.githack.com) to quickly preview and run the built WebVI in your browser.

## Experimental

Crazy experiments that try to push WebVIs to their limits 🧪.

- [WebVI Experiments](https://github.com/rajsite/webvi-experiments#webvi-experiments) - Playground with lots of examples and experiments using the JSLI with G Web. [Demo](https://github.com/rajsite/webvi-experiments/tree/gh-pages#webvi-experiments).

## Non-English Resources

Awesome WebVI resources in non-english languages 🌐.
<!-- spell-checker:disable -->
- [`Réaliser des applications Web avec LabVIEW (CG & NXG) pour publier vos données`](https://forums.ni.com/t5/luc-desruelle-s-Blogue/R%C3%A9aliser-des-applications-Web-avec-LabVIEW-CG-amp-NXG-pour/ba-p/3943768)
- [`Software Web – Aulamoisan`](https://aulamoisan.uva.es/software-web/)
    - [`Laboratorio remoto monofásico`](https://salamoisan.uva.es/labmono/)
    - [`Laboratorio remoto trifásico`](https://salamoisan.uva.es/labtrif/)
    - [`Simulador WEB arranque motor asíncrono`](http://salamoisan.uva.es/asincrona2/)
    - [`Simulador WEB de Corriente Alterna`](https://salamoisan.uva.es/alterna/)
    - [`Simulador WEB de Fasores Temporales`](http://salamoisan.uva.es/fasores/)
    - [`Simulador WEB de Flujos de Carga en Red Monofásica`](https://salamoisan.uva.es/flujocarga/)
    - [`Simulador WEB de Flujos de Carga en Red Trifásica`](https://salamoisan.uva.es/flujocarga3/)
    - [`Simulador WEB de máquinas asíncrona`](http://salamoisan.uva.es/asincrona/)
    - [`Simulador WEB de Transformador Monofásico`](http://salamoisan.uva.es/transformador/)
    - [`Simulador Web de Transitorios de Primer Orden`](http://salamoisan.uva.es/tr1/)
    - [`Simulador WEB del Teorema de Ferraris`](http://salamoisan.uva.es/ferraris/)
- [`NIが提供する新しい遠隔監視ツール 「SystemLink」を学ぼう`](https://forums.ni.com/t5/LabVIEW-Caf%C3%A9/NI%E3%81%8C%E6%8F%90%E4%BE%9B%E3%81%99%E3%82%8B%E6%96%B0%E3%81%97%E3%81%84%E9%81%A0%E9%9A%94%E7%9B%A3%E8%A6%96%E3%83%84%E3%83%BC%E3%83%AB-SystemLink-%E3%82%92%E5%AD%A6%E3%81%BC%E3%81%86/gpm-p/3967644)
- [`LabView NXG si aggiorna: arrivano i WebVI`](https://www.innovationpost.it/2018/01/25/labview-nxg-si-aggiorna-arrivano-webvi)
<!-- spell-checker:enable -->
