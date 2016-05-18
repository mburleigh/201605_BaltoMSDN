# Notes
May 2016 BaltoMSDN presentation: Build 2016 recap

https://www.microsoft.com/en-us/download/details.aspx?id=51691 (desktop app converter)

Xamarin is free!
* for all versions of Visual Studio
* Open source
* MIT license
* iOS emulator in Visual Studio
* [Xamarin workbooks/inspector](https://developer.xamarin.com/guides/cross-platform/workbooks/)

Windows 10 Anniversary Edition
* ink space
* Bash
  * Windows Subsystem for Linux
  * Uservoice (https://wpdev.uservoice.com/forums/266908-command-prompt-console-bash-on-ubuntu-on-windo)
  * command line tools only
  * users/(username)/AppData/Local/lxss
  * 64 bit only

Universal Windows Platform

Docker for Windows

[Microsoft Bot framework](www.botframework.com)
* conversation canvas
* bot as assistant
* bot builder sdk
* bot connector
* [bot emulator](http://docs.botframework.com/connector/tools/bot-framework-emulator/)
* [Facebook bots](https://developers.facebook.com/blog/post/2016/04/12/bots-for-messenger/)
* host anywhere
* register at dev.botframework command (gets your appId & app secret)
* use FormBuilder to generate interactive dialogs with bot
  * use annotation attributes to get rich experience
  * can include validations
  * can be integrated with LUIS to prefilled information
* session B855

Machine learning
* [LUIS](https://www.luis.ai/) (http://www.androidcentral.com/parsey-mcparseface-googles-open-source-bid-help-machines-understand-english)
  * intent
  * entities
  * utterance
* Cortana Intelligence Suite
* cognitive APIs (https://www.microsoft.com/cognitive-services/)
* [CRIS](https://www.microsoft.com/cognitive-services/en-us/custom-recognition-intelligent-service-cris)

.NET Core
* nothing you can't build with .Net
* PCL targets a set of platforms
  * not all APIs on all platforms
* => .Net Standard Library (most common denominator across all platforms)
* http://dotnet.github.io (all commits go through the same quality checks)
* .Net Foundation
* XAML edit & continue (like F12 tools in browser) in VA "15" (not VS2015!!!)
* F# support in .Net Core
* Roslyn code analyzers (need link) (NuGet based)
* Code Style
* indexing remote source code
* fully supported on RHEL

ASP.Net Core 1.0 (formerly known as ASP.NET 5)
* VS15 installs in under 2 minutes
* unified controller classes
* runs on 4.6 *AND* Core 1.0
* completely OSS when running on Core 1.0
* 10x performance improvement
* modular composable Middleware (use only the parts needed for a specific URL)
* include support for Bower, NPM
  * NuGet for server side .Net code
* event bindings for Gulp tasks
* Tag helpers (asp-* attributes)
* runs on any cloud (Azure, EC2, GDE, Docker)
* RC2 release?

Future of C#
* Run everywhere 
* deploy with app
* compile to native
* Open compiler APIs (Roslyn)
* use your favorite editor
* Open source
* -> one code base for understanding C#
* C# 7
  * tuple function returns (useful for async)
  * named tuple elements (shows up in Intellisense)
  * local functions (keeps context)
  * tuple is like parameter list
  * new underlying tuple is struct
  * use tuple as dictionary key
  * patterns in C# (V is Int i)
  * patterns can be used as case switches (and can include conditions)
    * implies order of evaluation
  * ref function return
* 

Xbox dev mode

Hololens

Azure
* [IoT](https://azure.microsoft.com/en-us/solutions/iot-suite/)
* Service Fabric GA

Power BI

Modern Office Addins


# Day 1 Keynote featuring Satya Nadella, Terry Myerson, Kevin Gallo, Phil Spencer, Alex Kipman, Lili Cheng and others.
* [00:53] Satya Nadella Kicks off Build 2016
* [04:47] Microsoft Mission
* [05:47] Mobile First Cloud First
* [11:13] Terry Myerson, Executive Vice President, Windows and Devices Group
* [13:47] Windows 10 - 270+ Million People
* [15:34] Windows 10 2016 Anniversary Update
* [17:28] Bryan Roper - Cortana, Ink and more 
* [23:19] The Ruler rocks...
* [28:58] Terry Myerson on Universal Windows Platform
* [30:38] Facebook Universal Windows Platform App's, including Audience Network and App Install SDK
* [33:08] Kevin Gallo - Windows is Home of Developers
* [37:13] 1000+ New Invocations, Visual Studio 2015 Update 2 & Anniversary SDK Preview
* [38:27] Bash is coming to Windows
* [42:18] Desktop App Converter
* [46:03] Targeting Xamarin & Microsoft Band 2
* [50:08] Phil Spencer, Corporate Vice President, Windows and Devices Group, Head of Xbox 
* [52:20] Windows 10, best platform for game developers
* [57:55] Xbox Dev Mode, with Ashley Speicher
* [1:03:50] DirectX 12
* [1:05:31] Alex Kipman, Technical Fellow, Windows and Devices Group
* [1:06:39] HoloLens Ships!
* [1:11:27] Pamela B. Davis, M.D.m Ph.D., Dean, School of Medicine, Case Western Reserve University and the HoloLens
* [1:17:37] Let's go to Mars!
* [1:20:36] Satya Nadella, "Making Windows the Dev Box of Choice"
* [1:28:23] Conversations as a Platform
* [1:30:23] Marcus Ash, Cortana, Partner Group Program Manager
* [1:32:23] Cortana Scheduling in Outlook
* [1:37:42] Cortana actions and developer portal
* [1:38:17] Just Eat
* [1:40:34] Conversation Canvases
* [1:42:35] Lilian Rincon, Principal Group Program Manager, Skype Consumer
* [1:49:02] Skype Video Bots
* [1:49:20] Skype Bot SDK, www.skype.com/developer 
* [1:52:17] Satya Nadella, "Every developer will build a bot"
* [1:52:55] Cortana Intelligence Suite
* [1:54:02] Dan Driscoll, Senior SDE
* [1:55:14] Got Bot?
* [1:55:17] No Bot?
* [1:55:36] Meet Bot
* [1:56:00] Pizza Bot!
* [1:59:22] Lili Cheng, Distinguished Engineer, "Building the Pizza Bot's Brains"
* [2:05:50] Cornelia Carapcea, Senior PM, Cognitive APIs
* [2:07:13] "What is in this image" demo
* [2:07:58] CaptionBot
* [2:09:32] CRIS
* [2:12:55] Satya Nadella, "Imagine what's possible"
* [2:13:37] Imagine today and the future with Saqib Shaikh

# Day 2 keynote

* [00:01] Scott Guthrie, Executive Vice President, Cloud + Enterprise, Kicks off Day Two of Build 2016 
* [05:25] Azure Momentum 
* [06:54] Web + Mobile 
* [10:23] Migel de Icaza, Xamarin Co-Founder, shows off Xamarin 
* [15:40] Xamarin Workbooks 
* [18:32] Scott Guthrie announces Xamarin is available at no extra charge to every Visual Studio Developer 
* [20:00] Xamarin Runtime to be open source 
* [21:12] New .NET Foundation Members, Unity, Jet Brains, Red Hat 
* [22:55] Donovan Brown, Senior Program Manager, demonstrates DevOps, Xamarin Test Cloud HockeyApp and Visual Studio Team Services 
* [34:32] Azure IoT 
* [35:23] Tom Brenner, BMW VP Digital Live Services & Engineering, BMW and Azure IoT 
* [44:01] Azure IoT Suite 
* [44:34] Announcing Azure Functions Preview 
* [45:47] Cameron Skinner, Program Director Software Engineer, Azure talks about Azure IoT Suite 
* [51:05] Cameron's "Azure IoT" connected T-Shirt 
* [51:57] Azure IoT Starter Kits, Azure IoT Hub Device Management Preview, Azure IoT Gateway SDK preview 
* [53:30] Azure Container Service 
* [57:20] Scott Hanselman, Principal Program Manager, shows off Age of Ascent 
* [1:06:33] Announcing Azure Service Fabric General Availability 
* [1:09:06] Chris Patti, CTO, AccuWeather, Azure at AccuWeather 
* [1:12:56] DocumentDB 
* [1:17:26] Announcing Power BI Embedded 
* [1:20:22] Lara Rubbelke, Principal SDE Manager demonstrates Power BI 
* [1:27:16] MyDriving, http://azure.com/mydriving 
* [1:28:45] Qi Lu, Executive Vice President, Applications and Services Group, on Microsoft Office 365 
* [1:39:28] Yina Arenas, Senior PPM Manager, demos Microsoft Graph 
* [1:48:31] Building a modern Office Add-in 
* [1:56:46] Gerri Martin-Flickinger, CTO, Starbucks 
* [2:03:38] Conversations as a platform 
* [2:07:59] Office 365 Group Connectors and Skype for Business Web & Mobile SDK 
* [2:15:27] http://dev.office.com 
* [2:16:18] Steve "Guggs" Guggenheimer, Corporate Vice President & Chief Evangelist and John Shewchuk, Technical Fellow on Developer conversations 
* [2:18:09] "New Developer" at Muzik 
* [2:27:53] Highspot Bot 
* [2:30:34] Edge, Vorlon.js and Page Analyzer Extension 
* [2:35:55] Rita Zhang, Senior SDE on Azure Proxy 
* [2:45:15] Vuforia/Caterpillar AR application demo 
* [2:51:44] Students and Imagine Cup 
* [2:52:40] NASA Quest
