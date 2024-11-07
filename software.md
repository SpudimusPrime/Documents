# Table of Contents <!-- omit from toc -->
- [Forward](#forward)
- [Keywords](#keywords)
- [7-Zip](#7-zip)
- [Adobe Reader](#adobe-reader)
- [Advanced IP Scanner](#advanced-ip-scanner)
- [Azure Data Studio](#azure-data-studio)
- [Baretail](#baretail)
- [Bitwarden](#bitwarden)
- [Chrome](#chrome)
- [CPUZ](#cpuz)
- [DaVinci Resolve](#davinci-resolve)
- [DBGate](#dbgate)
- [Everything](#everything)
- [Firefox](#firefox)
- [Flameshot](#flameshot)
- [GIMP](#gimp)
- [Greenshot](#greenshot)
- [Image Burn](#image-burn)
- [Krita](#krita)
- [mRemoteNG](#mremoteng)
- [MySQL Workbench](#mysql-workbench)
- [Notepad++](#notepad)
- [OBS Studio](#obs-studio)
- [PDQDeploy](#pdqdeploy)
- [PDQInventory](#pdqinventory)
- [PGAdmin](#pgadmin)
- [Putty](#putty)
- [Remmina](#remmina)
- [Remote Desktop Connection Manager](#remote-desktop-connection-manager)
- [Rufus](#rufus)
- [Snap](#snap)
- [SQL Server Management Studio](#sql-server-management-studio)
- [Teracopy](#teracopy)
- [Ventoy](#ventoy)
  - [Clonezilla](#clonezilla)
  - [Hirens BootCD](#hirens-bootcd)
  - [Ubuntu](#ubuntu)
  - [Ultimate Boot CD](#ultimate-boot-cd)
  - [Windows 10](#windows-10)
- [VLC Media Player](#vlc-media-player)
- [VSCode](#vscode)
  - [Extension: DBML Entity-Relationship Diagrams visualizer](#extension-dbml-entity-relationship-diagrams-visualizer)
  - [Extension: DuckDB Sql Tools](#extension-duckdb-sql-tools)
  - [Extension: Markdown All in One](#extension-markdown-all-in-one)
  - [Extension: Markdown Preview Mermaid Support](#extension-markdown-preview-mermaid-support)
  - [Extension: SQL Formatter VSCode](#extension-sql-formatter-vscode)
  - [Extension: SQL Server (mssql)](#extension-sql-server-mssql)
  - [Extension: SQL Tools](#extension-sql-tools)
  - [Extension: vscode-dbml](#extension-vscode-dbml)
- [WinDirStat](#windirstat)
- [WinGet](#winget)
- [WinSCP](#winscp)


# Forward

The tools listed below can have been discovered over the years and this document is developed to reduce the amount of time needed to re-research them when we need them again.

# Keywords
| | | | | | |
|---|---|---|---|---|---|
|`22`|`1433`|`3306`|`5432`|`7-zip`|`acrobat`|
|`adobe`|`bootable`|`browser`|`chrome`|`code`|`compression`|
|`copy`|`Cpu-z`|`cpuz`|`db`|`Db-gate`|`dbgate`|
|`deployment`|`dvd`|`editing`|`editor`|`file`|`firefox`|
|`flameshot`|`gif`|`graphical`|`greenshot`|`hardware`|`I.T.`|
|`image`|`img`|`inventory`|`ip`|`ise`|`iso`|
|`IT`|`jpg`|`log`|`manager`|`media`|`mkv`|
|`mp3`|`mp4`|`mysql`|`network`|`notepad++`|`package`|
|`password`|`pdf`|`png`|`postgresql`|`rdp`|`reader`|
|`recording`|`scanner`|`screencapture`|`screenshot`|`Snag-it`|`snagit`|
|`software`|`sound`|`sql`|`ssh`|`ssms`|`storage`|
|`streaming`|`svg`|`telnet`|`tool`|`transfer`|`txt`|
|`usb`|`vault`|`video`|`vlc`|`vnc`|`winamp`|
|`zip`|

# 7-Zip
| | |
|---|---|
|**Usage**|Universal* lightweight file compression tool.|
|**Official Repo**|https://www.7-zip.org/ |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows 2000 through Current Windows Release, MacOS, and Linux.|
|**Winget**|`winget install -e --id 7zip.7zip`|
|**apt**|`apt install p7zip-desktop`|
|**snap**|`snap install p7zip-desktop`|
|**brew**||
|**Keywords**|`compression` `zip` `7-zip`|

# Adobe Reader
| | |
|---|---|
|**Usage**|Reading and printing PDF files|
|**Official Repo**|https://get.adobe.com/reader/ |
|**Offline Installer**|https://get.adobe.com/reader/enterprise/ |
|**Price**|Free|
|**Compatibility**|Windows, MacOS|
|**Winget**|`winget install -e --id Adobe.Acrobat.Reader.64-bit`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`pdf` `adobe` `acrobat` `reader`|

# Advanced IP Scanner
| | |
|---|---|
|**Usage**|Finds all local network devices, and displays options to remote control them or browse shared folders|
|**Official Repo**|https://www.advanced-ip-scanner.com/  |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows 7 through Current Windows Release, no Mac or Linux support at this time.|
|**Winget**|`winget install -e --id Famatech.AdvancedIPScanner`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`tool` `network` `ip` `scanner`|

# Azure Data Studio
| | |
|---|---|
|**Usage**|Alternative to SSMS, DB agnostic. Utilizes Plugins|
|**Official Repo**|https://learn.microsoft.com/en-us/azure-data-studio/  |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows, MacOS, Linux|
|**Winget**|`winget install -e --id Microsoft.AzureDataStudio`|
|**apt**||
|**snap**|`sudo snap install azuredatastudio`|
|**brew**|`brew install --cask azure-data-studio`|
|**Keywords**|`tool` `network` `ip` `scanner`|
|**Other**|Snap package is not offically supported, refer to the offical repo for the supported version and install instructions.|

# Baretail
| | |
|---|---|
|**Usage**|Useful for watching and filtering text files update live, such as log files.|
|**Official Repo**|https://www.baremetalsoft.com/baretail/ 
|**Offline Installer**||
|**Price**|Free/$25 to remove splash screen|
|**Compatibility**|Windows|
|**Winget**||
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`tool` `log` `reader`|

# Bitwarden
| | |
|---|---|
|**Usage**|Cloud based password manager, browser plugins available.|
|**Official Repo**|https://bitwarden.com/download/ |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows 10/11, MacOS 12+, Linux|
|**Winget**|`winget install -e --id Bitwarden.Bitwarden`|
|**apt**||
|**snap**|`sudo snap install bitwarden`|
|**brew**|`brew install bitwarden`|
|**Keywords**|`tool` `password` `vault`|

# Chrome
| | |
|---|---|
|**Usage**|HTML5 web viewer, ignition and confluence pages tend to perform best|
|**Official Repo**|https://www.google.com/chrome/dr/download/?brand=SJWC&ds_kid=43700075934933123&gad_source=1&gclsrc=ds|
|**Offline Installer**|https://www.google.com/intl/en/chrome/?standalone=1 |
|**Price**|Free|
|**Compatibility**|Windows, MacOS, Linux|
|**Winget**|`winget install -e --id Google.Chrome`|
|**apt**||
|**snap**||
|**brew**|`brew install --cask google-chrome`|
|**Keywords**|`browser` `chrome`|

# CPUZ
| | |
|---|---|
|**Usage**|Tool that makes it really easy to identify the specifications of the PC without much work.|
|**Official Repo**|https://www.cpuid.com/softwares/cpu-z.html |
|**Offline Installer**|https://www.cpuid.com/downloads/cpu-z/cpu-z_2.09-en.zip |
|**Price**|Free|
|**Compatibility**|Windows|
|**Winget**|`winget install -e --id CPUID.CPU-Z`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`tool` `cpuz` `cpu-z`|

# DaVinci Resolve
| | |
|---|---|
|**Usage**|Video Editing Software|
|**Official Repo**|https://www.blackmagicdesign.com/products/davinciresolve |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows, MacOS, Linux|
|**Winget**||
|**apt**||
|**snap**||
|**brew**|`brew install --cask davinci-resolve`|
|**Keywords**|`video` `sound` `editing`|

# DBGate
| | |
|---|---|
|**Usage**|Useful for accessing multiple databases among many platforms, not as robust as a platform specific tool|
|**Official Repo**|https://dbgate.org/ |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows, MacOS, Linux|
|**Winget**|`winget install -e --id JanProchazka.dbgate`|
|**apt**||
|**snap**|`sudo snap install dbgate`|
|**brew**|`brew install --cask dbgate`|
|**Keywords**|`tool` `dbgate` `db-gate` `sql`|

# Everything
| | |
|---|---|
|**Usage**|File Search tool, faster than built-in search|
|**Official Repo**|https://www.voidtools.com/|
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows|
|**Winget**|`winget install -e --id voidtools.Everything`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`file` `search` `everything`|

# Firefox
| | |
|---|---|
|**Usage**|HTML5 Web viewer, not as comprehensive as chrome, runs lighter|
|**Official Repo**|https://www.mozilla.org/en-US/firefox/new/ |
|**Offline Installer**|https://www.mozilla.org/en-US/firefox/all/  |
|**Price**|Free|
|**Compatibility**|Windows, MacOS, Linux|
|**Winget**|`winget install -e --id Mozilla.Firefox`|
|**apt**||
|**snap**|`sudo snap install firefox `|
|**brew**|`brew install --cask firefox`|
|**Keywords**|`browser` `firefox`|

# Flameshot
|||
|---|---|
|**Details**|Another screen shot tool with options to edit in during capture|
|**Offical Repo**|https://flameshot.org/|
|**Offline Installer**||
|**Price**|Free|
|**compatibility**|Windows, Linux, MacOS|
|**Winget**|`winget install -e --id Flameshot.Flameshot`|
|**apt**|`apt install flameshot`|
|**snap**|`snap install flameshot`|
|**brew**|`brew install --cask flameshot`|
|**keywords**|`flameshot` `screenshot` `screencapture` `snagit` `snag-it`|

# GIMP
| | |
|---|---|
|**Usage**|Image Editing Software, edits and saves most known formats.<br><br>***Can Create SVGs***|
|**Official Repo**|https://www.gimp.org/  |
|**Offline Installer**|https://www.gimp.org/downloads/|
|**Price**|Free|
|**Compatibility**|Windows, MacOS, Linux|
|**Winget**|`winget install -e --id GIMP.GIMP`|
|**apt**|`apt install gimp`|
|**snap**|`snap install gimp`|
|**brew**|`brew install --cask gimp`|
|**Keywords**|`image` `png` `jpg` `gif` `img` `svg`|

# Greenshot
| | |
|---|---|
|**Usage**|Screenshot tool with built-in editor|
|**Official Repo**|https://getgreenshot.org/ |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows|
|**Winget**|`winget install -e --id Greenshot.Greenshot`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`screenshot` `snagit` `snag-it` `screencapture` `greenshot`|

# Image Burn
| | |
|---|---|
|**Usage**|Creates bootable DVDs and is useful for backing up installation disks to ISO formats.|
|**Official Repo**|https://www.imgburn.com/ |
|**Offline Installer**||
|**Price**|Free| 
|**Compatibility**|Windows|
|**Winget**|`winget install -e --id LIGHTNINGUK.ImgBurn`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`iso` `dvd`|

# Krita
| | |
|---|---|
|**Usage**|Image Editing Software, edits and saves most known formats.<br><br>***Does not create SVGs***|
|**Official Repo**|https://krita.org/en/  |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows, MacOS, Linux, <span style="color:red">Non Arm Processors on all platfoms</span>|
|**Winget**|`winget install -e --id KDE.Krita`|
|**apt**|`apt install krita`|
|**snap**|`snap install krita`|
|**brew**|`brew install --cask krita`|
|**Keywords**|`image` `png` `jpg` `gif` `img`|

# mRemoteNG
| | |
|---|---|
|**Usage**|Remote desktop connection manager supporting multiple protocols including RDP, SSH, and VNC. Not all connection errors are returned though so other software may be needed if you are unable to connect. Supports inherited credentials|
|**Official Repo**|https://mremoteng.org/  |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows|
|**Winget**|`winget install -e --id KDE.Krita`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`RDP` `ssh` `telnet` `vnc`|


# MySQL Workbench
| | |
|---|---|
|**Usage**|Used to manage MySQL databases|
|**Official Repo**|https://www.mysql.com/products/workbench/ |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows, MacOS, Linux|
|**Winget**||
|**apt**|`apt-get install mysql-workbench-community`|
|**snap**||
|**brew**|`brew install --cask mysqlworkbench`|
|**Keywords**|`mysql` `3306` `db`|

# Notepad++
| | |
|---|---|
|**Usage**|Notepad++ is an enhanced Notepad application that includes tabs and code highlighting by default. It additionally has a suite of available plugins to further enhance its feature set. When building a new computer this generally considered an “automatic install” due to its large number of supported features.|
|**Official Repo**|https://notepad-plus-plus.org/  
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows 95 through Current Windows Release, no Mac or Linux support at this time.|
|**Winget**|`winget install -e --id Notepad++.Notepad++`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`notepad++` `txt`|

# OBS Studio
| | |
|---|---|
|**Usage**|Used for recording screens and audio|
|**Official Repo**|https://obsproject.com/ |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows, MacOS, Linux|
|**Winget**|`winget install -e --id OBSProject.OBSStudio`|
|**apt**|`add-apt-repository ppa:obsproject/obs-studio && apt install obs-studio`|
|**snap**||
|**brew**|`brew install --cask obs`|
|**Keywords**|`recording` `streaming` `video`|

# PDQDeploy
| | |
|---|---|
|**Usage**|Useful for deploying software to computers over a network on a schedule|
|**Official Repo**|https://www.pdq.com/downloads/ |
|**Offline Installer**||
|**Price**|Trial|
|**Compatibility**|Windows|
|**Winget**||
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`tool` `I.T.` `IT` `software` `deployment`|

# PDQInventory
| | |
|---|---|
|**Usage**|Useful for maintaining a dynamic network inventory|
|**Official Repo**|https://www.pdq.com/downloads/ |
|**Offline Installer**||
|**Price**|Trial|
|**Compatibility**|Windows|
|**Winget**||
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`tool` `I.T.` `IT` `software` `hardware` `inventory`|

# PGAdmin
| | |
|---|---|
|**Usage**|Manages PostgreSQL Databases|
|**Official Repo**|https://www.pgadmin.org/ |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows, MacOS, Linux|
|**Winget**|`winget install -e --id PostgreSQL.pgAdmin`|
|**apt**||
|**snap**|`sudo snap install pgadmin4`|
|**brew**|`brew install --cask pgadmin4`|
|**Keywords**|`sql` `postgresql` `5432`|

# Putty
| | |
|---|---|
|**Usage**|Used to communicate with remote and local systems via SSH, Telnet, and Serial|
|**Official Repo**|https://www.putty.org/ |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows, Linux|
|**Winget**|`winget install -e --id PuTTY.PuTTY`|
|**apt**|`apt-get install putty`|
|**snap**|`snap install putty-gtk --edge`|
|**brew**|`brew install putty`|
|**Keywords**|`telnet` `ssh`|

# Remmina
| | |
|---|---|
|**Usage**|Allows support and developers to easily manage multiple remote desktop connections.  Connections can be stored as part of groups, and those groups can inherit logon credentials and other settings from their parents.|
|**Official Repo**||
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Linux|
|**Winget**||
|**apt**||
|**snap**|`snap install remmina`|
|**brew**||
|**Keywords**|`rdp` `telnet` `ssh` `vnc`|

# Remote Desktop Connection Manager
| | |
|---|---|
|**Usage**|Allows support and developers to easily manage multiple remote desktop connections.  Connections can be stored as part of groups, and those groups can inherit logon credentials and other settings from their parents.|
|**Official Repo**|https://learn.microsoft.com/en-us/sysinternals/downloads/rdcman |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows|
|**Winget**|`winget install -e --id Microsoft.Sysinternals.RDCMan`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`rdp`|

# Rufus
| | |
|---|---|
|**Usage**|Useful for creating bootable USB drives and downloading specific Windows Releases.<br><br>Example: ABB Patch is only approved on Windows 10 22H2, this tool will help you download it.|
|**Official Repo**|https://rufus.ie/en/ |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows|
|**Winget**|`winget install -e --id Rufus.Rufus`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`usb` `iso`|

# Snap
| | |
|---|---|
|**Usage**|Linux based package manager agnostic to most distributions. Generally auto included, but not always.|
|**Official Repo**|https://snapcraft.io|
|**Price**|Free|
|**Compatibility**|Linux|
|**Debian**|` apt update && apt install snapd`|
|**Fedora**|`dnf install snapd`|
|**Keywords**|`package` `manager`|

# SQL Server Management Studio
| | |
|---|---|
|**Usage**|Robust MSSQL management tool|
|**Official Repo**|https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16#download-ssms |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows|
|**Winget**|`winget install -e --id Microsoft.SQLServerManagementStudio`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`SSMS` `1433` `SQL`|

# Teracopy
| | |
|---|---|
|**Usage**|Alternative Copy/Paste tool. Displays more information regarding the progress, adds improved functionality for pausing and resuming jobs.|
|**Official Repo**|https://codesector.com/teracopy 
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows, MacOS|
|**Winget**|`winget install -e --id CodeSector.TeraCopy`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`file` `copy`|

# Ventoy
| | |
|---|---|
|**Usage**|Turns any USB drive into a multi-bootable drive. After drive is formatted with the tool, save bootable ISO files to the new directory. On boot the user will be able to select the appropriate boot file.|
|**Official Repo**|https://www.ventoy.net/en/index.html |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows for tool creation|
|**Winget**|`winget install -e --id ventoy.Ventoy`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`bootable` `usb`|

## Clonezilla
| | |
|---|---|
|**Usage**|Clones an entire hard drive to a file and writes that file to a hard drive of the same size or larger.|
|**Official Repo**|https://clonezilla.org/downloads.php |
|**Price**|Free|

## Hirens BootCD
| | |
|---|---|
|**Usage**|Boots into a Windows environment and includes a suite of tools for installing drivers, repairing boot records, and backing up files among other things.|
|**Official Repo**|https://www.hirensbootcd.org/ |
|**Price**|Free|

## Ubuntu
| | |
|---|---|
|**Usage**|Boots a system into a Ubuntu Linux environment.|
|**Official Repo**|https://ubuntu.com/ |
|**Price**|Free|

## Ultimate Boot CD
| | |
|---|---|
|**Usage**|Another suite of tools designed to recover a local pc|
|**Official Repo**|https://www.ultimatebootcd.com/ |
|**Price**|Free|

## Windows 10
| | |
|---|---|
|**Usage**|Launches Windows 10 installation media. The software is free to use for 30 days without a license. The download link downloads a tool to download the version of your choice. |
|**Official Repo**|https://www.microsoft.com/en-us/software-download/windows10 |
|**Price**|Free*|

# VLC Media Player
| | |
|---|---|
|**Usage**|Multi-format Media Player|
|**Official Repo**|https://www.videolan.org/ |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows, MacOS, Linux|
|**Winget**|`winget install -e --id VideoLAN.VLC`|
|**apt**||
|**snap**|`sudo snap install vlc`|
|**brew**|`brew install --cask vlc`|
|**Keywords**|`media` `winamp` `mkv` `mp4` `mp3` `vlc`|

# VSCode
| | |
|---|---|
|**Usage**|Customizable Code Editor. Can connect to your git repo.|
|**Official Repo**|https://code.visualstudio.com/|
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows, MacOS, Linux|
|**Winget**|`winget install -e --id Microsoft.VisualStudioCode`|
|**apt**||
|**snap**|`snap install --classic code`|
|**brew**|`brew install --cask visual-studio-code`|
|**Keywords**|`code` `editor`|

## Extension: DBML Entity-Relationship Diagrams visualizer
| | |
|---|---|
|**Usage**|Transforms .dbml files into easy to read diagrams|
|**Official Repo**|[bocovo.dbml-erd-visualizer](https://marketplace.visualstudio.com/items?itemName=bocovo.dbml-erd-visualizer)|
|**Price**|Free|

## Extension: DuckDB Sql Tools
| | |
|---|---|
|**Usage**|Plugin to allow in VSCode Management of DuckDBs|
|**Official Repo**|[RandomFractalsInc.duckdb-sql-tools](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.duckdb-sql-tools)|
|**Price**|Free|

## Extension: Markdown All in One
| | |
|---|---|
|**Usage**|Makes the markdown pretty and gives a preview option|
|**Official Repo**|[yzhang.markdown-all-in-one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)|
|**Price**|Free|

## Extension: Markdown Preview Mermaid Support
| | |
|---|---|
|**Usage**|Allows mermaid to be previewed in your markdown files|
|**Official Repo**|[bierner.markdown-mermaid](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)|
|**Price**|Free|

## Extension: SQL Formatter VSCode
| | |
|---|---|
|**Usage**|Makes SQL easier to read|
|**Official Repo**|[ReneSaarsoo.sql-formatter-vsc](https://marketplace.visualstudio.com/items?itemName=ReneSaarsoo.sql-formatter-vsc)|
|**Price**|Free|
|**Note**|There is another extension with the same icon and more downloads, that one was retired and this is the fork that lives on in its place.|

## Extension: SQL Server (mssql)
| | |
|---|---|
|**Usage**||
|**Official Repo**|[ms-mssql.mssql](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql)|
|**Price**|Free|


## Extension: SQL Tools
| | |
|---|---|
|**Usage**|Creates the SQL Connections for many DBs|
|**Official Repo**|[mtxr.sqltools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools)|
|**Price**|Free|

## Extension: vscode-dbml
| | |
|---|---|
|**Usage**|Most complete version of DBML availiable in the vscode marketplace to date.|
|**Official Repo**|[matt-meyers.vscode-dbml](https://marketplace.visualstudio.com/items?itemName=matt-meyers.vscode-dbml)|
|**Price**|Free|
|**Note**|Not *actively* maintained, but dev says they'll push updates if asked, of the available options for dbml pluggins, still the best. The extension does support all paid features of dbdiagrams.io, but none of the preview tools have been able to fully render the paid features.|

# WinDirStat
| | |
|---|---|
|**Usage**|Helps visually identify large files on a hard drive|
|**Official Repo**|https://windirstat.net/ |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows|
|**Winget**|`winget install -e --id WinDirStat.WinDirStat`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`storage` `graphical` `ISE`|

# WinGet
| | |
|---|---|
|**Usage**|Already installed on Windows, allows users to install software using the `winget` command in powershell. For more options check https://winget.run/|
|**Official Repo**| |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows|

# WinSCP
| | |
|---|---|
|**Usage**|Useful tool for moving files between Windows and Linux when other tools are unavailable.|
|**Official Repo**|https://winscp.net/eng/index.php |
|**Offline Installer**||
|**Price**|Free|
|**Compatibility**|Windows|
|**Winget**|`winget install -e --id WinSCP.WinSCP`|
|**apt**||
|**snap**||
|**brew**||
|**Keywords**|`file` `transfer` `22`|