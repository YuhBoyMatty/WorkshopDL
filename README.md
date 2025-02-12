[![Banner](https://raw.githubusercontent.com/VovoloGames/WorkshopDL/main/screenshots/banner_opaque_red_download.png)](https://github.com/VovoloGames/WorkshopDL/releases/download/v1.9.9/WorkshopDL.v1.9.9.zip)

<em>Since most of the popular workshop downloading websites have shutdown or instruct users to download & use SteamCMD, a command-line program,
I've decided to make my own standalone workshop downloader with a GUI to make things easier.</em>
# WorkshopDL [![Version](https://img.shields.io/github/v/tag/VovoloGames/WorkshopDL?label=version&style=flat-square&color=black)](https://github.com/VovoloGames/WorkshopDL/releases) [![GitHub all releases](https://img.shields.io/github/downloads/VovoloGames/WorkshopDL/total?style=flat-square)](https://github.com/VovoloGames/WorkshopDL/releases)

### Screenshots
[![Screenshot](https://raw.githubusercontent.com/VovoloGames/WorkshopDL/main/screenshots/screenshot1.png)](https://github.com/VovoloGames/WorkshopDL/releases)
<details closed>
<summary>Click to view more screenshots</summary>
<br>

[![Screenshot](https://raw.githubusercontent.com/VovoloGames/WorkshopDL/main/screenshots/screenshot2.png)](https://github.com/VovoloGames/WorkshopDL/releases)

[![Screenshot](https://raw.githubusercontent.com/VovoloGames/WorkshopDL/main/screenshots/screenshot3.png)](https://github.com/VovoloGames/WorkshopDL/releases)
</details>

----

#### [Youtube tutorial on how to use WorkshopDL (Made by Assassinator162)](https://youtu.be/lB3nz7k5Ao4?t=16)
----

# What is WorkshopDL?
It is a Steam workshop downloader. Do you own a game on a different platform than Steam (Like GOG or the Epic Games Store) and you always wanted to use mods from the Steam workshop? WorkshopDL allows you to download mods from the Steam workshop for free! It currently supports more than 900+ games!

###### <em>Note 1: For certain garry's mod addons you must use SteamWebAPI instead of SteamCMD!
###### Note 2: For some games, you might need to manually add the file extension to the mod.</em>

## Features
- Very easy to use.
- User-friendly GUI.
- Supports 1GB+ mods.
- Includes a handy mod installer.
- Includes a Garry's mod, <em>mod</em> unpacker!
- You can download workshop collections!
- Automatically finds the game id (workshop homepage).
- You can download both anonymously or using your personal Steam account (Optional).
- You can Import URLs from a text file.
- You can save your mod queue as a text file.
- Auto-URL detection and Auto-Queueing.
- The program is self-contained. No setups, no bloat.
- It offers multiple ways to download mods. SteamCMD, SteamWebAPI... and more to come!
- Automatically clears leftover files from canceled downloads and corrupted files, that occupy free space.

## WorkshopDL in comparison with similar downloaders
| Features  |  [WorkshopDL](https://github.com/VovoloGames/WorkshopDL) |  [Community Workshop](https://github.com/CommunityWorkshop/CommunityWorkshopDownloader) |  [Nether Workshop Downloader](https://github.com/NethercraftMC5608/NetherWorkshopDownloader) |  [SCMD Workshop Downloader 2](https://github.com/BerdyAlexei/SCMD-Workshop-Downloader-2) |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Open-source | ✔  | ✔  | ❌  | ✔  | 
| Support for SteamCMD | ✔  | ✔  | ❌  | ✔  | 
| Support for SteamWebAPI  | ✔  | ❌  | ❌  | ❌ | 
| Support for Nether API  | ✔  | ❌  | ✔  | ❌ | 
| Support for GGNetwork API  | Cached mods  | ✔  | ❌  | ❌ | 
| Mod Installer | ✔  | ~  | ~  | ~ | 
| Workshop Collections | ✔  | ❌  | ✔  | ✔ | 
| Support for Steam accounts | ✔  | ❌  | ✔  | ✔ | 
| URL Auto-Detection from clipboard | ✔  | ❌  | ❌  | ❌ | 
| Automatic support for 1GB+ mods (Through SteamCMD) | ✔  | ❌  | ❌  | ❌ | 
| Automaticly downloads and extracts SteamCMD | ✔  | ✔ (Pre-packaged)  | ❌ | ❌ | 
| Automatic disposal of steamcmd's temporary files (They can exceed 20gb in size, if never cleared) | ✔  | ❌  | ❌  | ❌ |
###### Updated 2022/12/11

## How To Use
<details closed>
<summary>Click to read</summary>
<br>

`(You can read more information for various issues, inside WorkshopDL by going at "Help>Support".)`

1. Execute "WorkshopDL.exe"
Do *not* open the "steamcmd.exe" located inside the steamcmd folder.

2. At the "Workshop Homepage" box simply copy & paste, inside the box, the game's workshop homepage URL.
For example, here is a workshop homepage https://steamcommunity.com/app/4000/workshop/.

3. At the "Workshop mod URL" box simply copy & paste, inside the box, the URL of the mod you want to download.

4. Click download.
(Note: The first time it might take longer to download cause SteamCMD is downloading some necessary files.
This will *only* happen on your very first launch.)

5. After the download is completed the folder containing the mod will open on a separate window.
6. Installation of mods differs from game to game.

Note 1: Games that aren't listed here https://steamdb.info/sub/17906/apps/ are not guaranteed to work.

Note 2: If a game does not work, try to download the mods using the AppID (Homepage) of it's dedicated server. You can also try downloading with SteamWebAPI. It works with a lot of SteamCMD unsupported games, usually single-player ones.
</details>

## FAQ
<details closed>
<summary>Click to read</summary>
<br>

Q: Why would I need this?  
>  A: If you own a game on a different platform like GOG or the Epic Games store, you can not download mods for the game, as the majority of mods are locked inside Steam's workshop. So instead of buying the game a second time to access the mods, you can simply use WorkshopDL.

Q: How does this work?  
>  A: It pretty much is a GUI that launches Valve's SteamCMD commandline tool with the needed parameters to download the workshop item you want.  
>
>  As of version 1.4.4 and above, it has a lot more complicated features, like workshop collection support, the ability to download mods using the >SteamWebAPI, a download queue... and the list goes on!

Q: Which games are supported by WorkshopDL?  
>  A: Games listed here https://steamdb.info/sub/17906/apps/ will work with no issues.
Other games might work too, but it is not guaranteed.

Q: Is this safe to use?  
>  A: Yes. It is completely safe! It is impossible to get banned for using this tool.
>If you mean virus-wise, it is clean and open-source! Here is a [VirusTotal scan](https://www.virustotal.com/gui/file/d9d8306339ad71f6e941cdc5426ab5fefdfcfcb3cee8e54780e703d6c1e1ac77) of the latest version.  

<em>Note: it looks like a single garbage anti-virus marks WorkshopDL as suspicious because it contacts raw.githubusercontent.com to check for updates and to update the supported games list. This is a false-positive. I've send an email to the company that owns said anti-virus. Hopefully they will fix it.</em>
</details>

# Miscellaneous
[![rin forum](https://img.shields.io/badge/Forum%20Post-cs.rin.ru-darkgray?style=flat-square)](https://cs.rin.ru/forum/viewtopic.php?f=29&t=124583)
[![Virus Total](https://img.shields.io/badge/Virus%20Total%20Scan-v1.9.9%20Clean%20(False%20positive)-brightgreen?style=flat-square)](https://www.virustotal.com/gui/file/d9d8306339ad71f6e941cdc5426ab5fefdfcfcb3cee8e54780e703d6c1e1ac77)

The best direct downloads site for Workshop mods: [(smods.ru)](https://catalogue.smods.ru/)  
My email: vovologames (at) proton (dot) me

## Third Party Download Providers used in WorkshopDL
[GGNetwork](https://ggntw.com/steam) <em>(If some mods don't download through WorkshopDL, try using their website)</em>  
[Nether API](https://github.com/NethercraftMC5608/NetherWorkshopDownloader/wiki/Supported-API-games)

# About the Source Code
You need a legitimate copy of [Clickteam Fusion 2.5 (Build R294.X)](https://www.clickteam.com/clickteam-fusion-2-5) to open the .mfa file.  
<em>Previous versions will work too, but they might mess the layer order.</em>

#
###### <em>WorkshopDL is not affiliated with Valve Corporation or Steam. WorkshopDL is not affiliated with other downloading software.</em>
