_[I'm sorry but I'm now super busy, If you want to be a maintainer of the project please feel me to contact me! You've to be passionate about programming]_

# Live Server

**Live Server loves** 💘 **your multi-root workspace**

> **Live Server for server side pages like PHP. [Check Here](https://github.com/ritwickdey/live-server-web-extension)**

> ***[For 'command not found error' [#78](https://github.com/ritwickdey/vscode-live-server/issues/78)]***

[![VSCode Marketplace](https://img.shields.io/vscode-marketplace/v/ritwickdey.LiveServer.svg?style=flat-square&label=vscode%20marketplace)](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) [![Total Installs](https://img.shields.io/vscode-marketplace/d/ritwickdey.LiveServer.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) [![Avarage Rating](https://img.shields.io/vscode-marketplace/r/ritwickdey.LiveServer.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)  
[![Travis branch](https://img.shields.io/travis/ritwickdey/vscode-live-server/master.svg?style=flat-square&label=travis%20branch)](https://travis-ci.org/ritwickdey/vscode-live-server) [![Appveyor branch](https://img.shields.io/appveyor/ci/ritwickdey/vscode-live-server.svg?style=flat-square&label=appveyor%20branch)](https://ci.appveyor.com/project/ritwickdey/vscode-live-server) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/ritwickdey/vscode-live-server/) 
<br>

**Launch a local development server with live reload feature for static & dynamic pages.**
<br>

![Live Server Demo VSCode](./images/Screenshot/vscode-live-server-animated-demo.gif)

## Shortcuts to Start/Stop Server

**_[NOTE: In case if you don't have any `.html` or `.htm` file in your workspace then you have to follow method no 4 & 5 to start server.]_**

1. Open a project and click to `Go Live` from the status bar to turn the server on/off. 
![Go Live Control Preview](./images/Screenshot/vscode-live-server-statusbar-3.jpg)

2. Right click on a `HTML` file from Explorer Window and click on `Open with Live Server`.
![Explorer Window Control](./images/Screenshot/vscode-live-server-explorer-menu-demo-1.gif).

3. Open a HTML file and right-click on the editor and  click on `Open with Live Server`.
![Edit Menu Option Preview](./images/Screenshot/vscode-live-server-editor-menu-3.jpg)

4. Hit `(alt+L, alt+O)` to Open the Server and `(alt+L, alt+C)` to Stop the server (You can change the shortcut form keybinding). *[On MAC, `cmd+L, cmd+O` and `cmd+L, cmd+C`]*

5. Open the Command Pallete by pressing `F1` or `ctrl+shift+P` and type `Live Server: Open With Live Server ` to start a server or type `Live Server: Stop Live Server` to stop a server.


## Features
* A Quick Development Live Server with live browser reload.
* Start or Stop server by a single click from status bar.
* Open a HTML file to browser from Explorer menu.[[Quick Gif Demo](./images/Screenshot/vscode-live-server-explorer-menu-demo-1.gif?raw=true)].
* Support for excluding files for change detection. 
* Hot Key control.
* Customizable Port Number, Server Root, default browser.
* Support for any browser _(Eg: Firefox Nightly)_ using advance Command Line.
* Support for Chrome Debugging Attachment (_[More Info](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)_). [[Quick Gif Demo](./images/Screenshot/ChromeDebugging.gif?raw=true)].
* Remote Connect through WLAN (E.g.: Connect with mobile) _[Need Help? See FAQ Section]_
* Use preferable host name *(localhost or 127.0.0.1)*.
* Customizable Supporting Tag for Live Reload feature. (Default is `Body` or `head`)
* SVG Support
* `https` Support. 
* Support for proxy.
* CORS Enabled
* Multi-root workspace supported.
* Support for any file even dynamic pages through *[Live Server Web Extension](https://github.com/ritwickdey/live-server-web-extension)*.

## Installation
Open VSCode and type `ctrl+P`, type `ext install ritwickdey.liveserver`.

## Settings
All settings are now listed here  [Settings Docs](./docs/settings.md).

## FAQs
*All FAQs are now listed here [FAQ Docs](./docs/faqs.md)*

## What's new ?

* ### Version 5.2.0 (16.11.18)
  * ***[Features]*** Live Server + Live Share = 💘. Share your live server over the internet with live reload feature! You'll be prompted to share live server using live server when you click to `Go Live`. *(Thank you so much [Alex Panov](https://github.com/alpaix) for opening PR [#232](https://github.com/ritwickdey/vscode-live-server/pull/232) )*
  
  * ***[Docs fixing /  update]*** #170, #185, #201, #233 *(Thanks [Shaurya Shubham](https://github.com/coolshaurya), [Benjamin Vincent](https://github.com/luxcium), [Jan Dittrich](https://github.com/jan-di),  [Karsten 7.](https://github.com/Karsten7))*



## Changelog
To check full changelog [click here](CHANGELOG.md).


## Special Thanks To Maintainers
A special thanks to [Max Schmitt](https://github.com/mxschmitt)  & [Joydip Roy](https://github.com/rjoydip) for contributing their valueable time on this project.

[![Max Schmitt](https://avatars2.githubusercontent.com/u/17984549?s=64)](https://github.com/mxschmitt)
[![Joydip Roy](https://avatars2.githubusercontent.com/u/15318294?s=64)](https://github.com/rjoydip)


## LICENSE
This extension is licensed under the [MIT License](LICENSE)
