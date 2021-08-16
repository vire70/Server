# NostalgiaEQ Core Server
|Travis CI (Linux)|Appveyor (Windows x86)   |Appveyor (Windows x64)   |
|:---:|:---:|:---:| 
|[![Linux CI](https://travis-ci.org/EQEmu/Server.svg?branch=master)](https://travis-ci.org/EQEmu/Server)   |[![Build status](https://ci.appveyor.com/api/projects/status/v3utuu0dttm2cqd0?svg=true)](https://ci.appveyor.com/project/KimLS/server)   |[![Build status](https://ci.appveyor.com/api/projects/status/scr25kmntx36c1ub?svg=true)](https://ci.appveyor.com/project/KimLS/server-87crp)   |

***

** See Related Repositories at the bottom to find precompiled server as well as database and client.

** NostalgiaEQ Server is a fork of EQEmulator which is a custom completely from-scratch open source server implementation for EverQuest built mostly on C++**
 * MySQL/MariaDB is used as the database engine (over 200+ tables)
 * Perl and LUA are both supported scripting languages for NPC/Player/Quest oriented events
 * Open source database (Nostalgia EQ) has classic content.
 * Game server environments and databases can be heavily customized to create all new experiences
 * Hundreds of Quests/events created and maintained by FVProject and NostalgiaEQ

## Server Installs
| |Windows|Linux|
|:---:|:---:|:---:|

### > Windows 

* [Install Guide](https://eqemu.gitbook.io/server/categories/installation/server-installation-windows)

### > Debian/Ubuntu/CentOS/Fedora

* [Install Guide](https://eqemu.gitbook.io/server/categories/installation/server-installation-linux)

* You can use curl or wget to kick off the installer (whichever your OS has)
> curl -O https://raw.githubusercontent.com/Vire70/Server/master/utils/scripts/linux_installer/install.sh install.sh && chmod 755 install.sh && ./install.sh

> wget --no-check-certificate https://raw.githubusercontent.com/Vire70/Server/master/utils/scripts/linux_installer/install.sh -O install.sh && chmod 755 install.sh && ./install.sh

## Supported Clients

|Titanium Edition|
|:---:|
|<img src="http://i.imgur.com/hrwDxoM.jpg" height="150">|

## Bug Reports <img src="http://i.imgur.com/daf1Vjw.png" height="20">
* Please use the [issue tracker](https://github.com/Vire70/Server/issues) provided by GitHub to send us bug
reports or feature requests.
* The [NostalgiaEQ Discord](https://discord.gg/e5hAyWfbsW) are also a place to submit and get help with bugs.

## Contributions <img src="http://image.flaticon.com/icons/png/512/25/25231.png" width="20">

* The preferred way to contribute is to fork the repo and submit a pull request on
GitHub. If you need help with your changes, you can always post to Discord.

## Contact <img src="http://gamerescape.com/wp-content/uploads/2015/06/discord.png" height="20">

 - Discord Channel: https://discord.gg/e5hAyWfbsW
 - **User Discord Channel**: `#classic-eq-talk`
 - **Getting Started**: `#get-started`
 - **Development Log**: `#development-log`

## Resources
- [NostalgiaEQ Discord](https://discord.gg/e5hAyWfbsW)

## Related Repositories
* [FVProject-quests](https://github.com/GiverofMemory/FVProject-quests)
* [NostalgiaEQ-server](https://github.com/GiverofMemory/NostalgiaEQ-server)
* [NostalgiaEQ-database](https://github.com/GiverofMemory/NostalgiaEQ-database)
* [NostalgiaEQ-client](https://github.com/GiverofMemory/NostalgiaEQ-client)
* [EQEmulator](https://github.com/EQEmu/Server)
* [Installer Resources](https://github.com/Akkadius/EQEmuInstall)
* [Zone Utilities](https://github.com/EQEmu/zone-utilities) - Various utilities and libraries for parsing, rendering and manipulating EQ Zone files.

## Other License Info

* The server code and utilities are released under **GPLv3**
* We also include some small libraries for convienence that may be under different licensing
  * SocketLib - GPL LibXML
  * zlib - zlib license
  * MariaDB/MySQL - GPL
  * GPL Perl - GPL / ActiveState (under the assumption that this is a free project)
  * CPPUnit - GLP StringUtilities - Apache
  * LUA - MIT

## Contributors

<a href="https://github.com/Vire70/server/graphs/contributors">
  <img src="https://contributors-img.firebaseapp.com/image?repo=Vire70/server" />
</a>

