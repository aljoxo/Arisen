# Apotheosis



<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	

</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Contents
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
    - [Setting up Page File](#setting-up-pagefile)  
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing Apotheosis](#downloading-and-installing-apotheosis)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [Documentation](#documentation)
    - [BethINI](#bethini)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
    - [Starting the Game](#starting-the-game)
  - [Updating Apotheosis](#updating-the-modlist)
  - [FAQ](#faq)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

# <ins>**Apotheosis requires the *full* AE upgrade, which means you must *purchase* the AE edition of the game for the list to function.**<ins>

## Preamble

Apotheosis is a Wabbajack modlist centered around providing the player a brand new combat experience by utilizing various mods such as MCO, ﻿Precision, and SCAR, as well as an extensive amount of custom movesets to help provide a strong animation foundation. The list uses a mix of SimonMagus' and EnaiSiaion's mods to offer balanced and interesting paths of progression for the player, they are also tweaked to ensure compatibility with the aforementioned combat core.

The full modlist can be viewed [here](https://loadorderlibrary.com/lists/apotheosis).

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

### Minimum Specifications for ~60 fps gameplay at 1920x1080

>  Please note these specs are the best idea of a baseline that I can provide at the current moment, as I only have one PC to play and test on, your mileage may vary depending on a variety of factors. In the future this will hopefully be updated to be more accurate.

| Spec Category | Default Profile |
|     :---:    |     :---:     |
| **CPU**   | R7 3700x / i5 10600k |  
| **Video Card**    | RTX 3060 Ti / RTX 2080 / RX 6700 XT       |
| **Ram**    | 32gb (2x16) DDR4 3200mhz RAM     |
| **Storage**    | SATA SSD     |

>  I will **not** be supporting any AMD GPUs from before or from the Polaris Series (RX 500) and any NVIDIA GPUs from before or from the Maxwell Series (GTX 700/900), the only exception for this is the GTX 980 Ti, which is relateively equivelent to a 1660 Ti. These GPUs are simply not powerful enough to handle modded skyrim with an ENB on at 60 frames.

Space required: 
- Approx 450GB (Downloads included)

Size without downloads: 
- Approx 280GB

### Setting Up Pagefile

Due to the resources required to run modlists like these, you will need to configure the pagefile on your system in order to avoid crashes and bugs that may occur from running out of memory. I suggest a 40GB fixed-size pagefile for Apotheosis solely for safety, but it is very possible that you could get away with a 20GB (20480 instead of 40960 in the **Initial** and **Maximum Size** boxes). This step is **NOT** optional, I do not care how much RAM or VRAM you have, please do this step.

To set up your pagefile:
1. Press **Win Key + R**
2. Type *sysdm.cpl ,3* and hit **ENTER**
3. Navigate to *Performance* and click the box "Settings..."
4. Click the *Advanced* tab at the top
5. Under *Virtual Memory* click the box "Change..."
6. Uncheck *Automatically manage* if it is checked
7. Select your disk drive, ideally your fastest solid state drive
8. Click the **Custom size:** button
9. In the box next to **Initial Size (MB)** type 40960
10. In the box next to **Maximum Size (MB)** type 40960
11. Click the *Set* button
12. Click *OK*
13. Click *Apply*
14. Click *OK*
15. Restart your computer in order for your new pagefile to take effect.

## Installation

Installing Apotheosis is relatively easy and, if you have Nexus Premium and a LoversLab account, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating-the-modlist).

### Pre-Installation

Prior to installing Apotheosis, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Right click on Skyrim SE and click on properties, untick the "Enable Steam Overlay while in-game."
4. You also need to start the games to the main menu in order to download all the creations. **DO NOT SKIP THIS STEP, IF YOU DO SO WABBAJACK WILL FAIL**_

 Additionally, if you have an NVIDIA GeForce Graphics Card, please do the following. 

 1. Right click on your desktop and select **NVIDIA Control Panel**
 2. Navigate and click on **Manage 3D settings**. It is the 2nd one to the top.
 3. Scroll down in Global Settings until you see **Shader Cache Size**
 4. Double Click **Driver Default** to the right of Shader Cache Size and select **10 GB**
 5. Click **Apply** in the bottom right hand corner. 
 6. You may exit out of the application.

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) on this github and place it in a folder such as `C:\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing Apotheosis

Downloading and installing Apotheosis can take a while depending on your internet connection and computer. To install Apotheosis, complete the following steps.

1. Download the Wabbajack Installer on this github,.
2. Press the download button on Apotheosis and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\Apotheosis. **Do not install it to your desktop, downloads folder, or Skyrim's Steam Folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

Some files require loverslab for this list (none of them are nsfw).
- [Nether's Follower Framework v2.7.9](https://www.loverslab.com/files/file/6188-nethers-follower-framework/)
- [Tempered Skins for Males - SOS Light Version - part 2 of 2 v2.051](https://www.loverslab.com/files/file/3692-sos-light-version-with-tempered-skins-for-males-sse/)
- [SOS - Schlongs of Skyrim - LightSE](https://www.loverslab.com/files/file/3705-schlongs-of-skyrim-light-se/)

Sometimes Google Drive and MEGA will experience bandwidth caps, so below I have included the links to the files that require them.
- [Eskyrim Spear](https://mega.nz/folder/jQdSTTiS#cvXiRP6SSHNm5-RERVrhQw)
- [Olivier Kenjutsu Battleaxe and Warhammer](https://drive.google.com/file/d/1rX4INfO3ieWp25gPh0NiLPl1ktLoegZ9)
- [Olivier Kenjutsu Katana](https://drive.google.com/file/d/14cix5FZNgPiAJV8mfwB2Yfcqchkd1KqJ)
- [Olivier Kenjutsu Sword 2.0](https://drive.google.com/file/d/1MHmaAQnX89tssUziX9NZWoV66B_WwEBf)
- [Olivier Kenjutsu Sword 1.1](https://drive.google.com/file/d/1A8ZQrzA675l1PcDJEOVe3j7rjcnHvp9q)
- [OCPA 1.2](https://mega.nz/file/UOEA0CyL#RP6q-q4zRtc2X0k45FIXfBLh5yS7IrsPAIG7FEZ5Hbc)
- [Tullfx Bloodstorm](https://drive.google.com/file/d/1wu9hwP_7QJC9tWxLwR8QU41txry5u9vA)
- [dint BDOR Hair pack](https://drive.google.com/file/d/16cEFQinG9utc-P5LvOJ3SFtOpfbX24M2)

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.


- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Game Folder

Apotheosis uses a Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called “Stock Game”. You don’t need to copy anything at all.

### Documentation

WIP

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `SKSE` and press the `Run` button. 

### In-Game MCM options

- This serves as a placeholder in case you want to use the Readme as some sort of template.

### Starting the Game

- By default, Apotheosis uses [Skyrim Unbound](https://www.nexusmods.com/skyrimspecialedition/mods/27962).
- More relevant details...
	
## Adding mods to Apotheosis

- WIP...

### Anniversary Edition

Apotheosis is on a [downgraded](https://www.nexusmods.com/skyrimspecialedition/mods/57618) version (1.5.97) of Skyrim. As stated at the top of this document, it **does require** the paid update.



## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates. If you are curious to know if an update is save safe or not, then refer to the version number. The first digit should indicate major version, second digit should indicate minor version (these are likely to be save safe unless otherwise specified), the third digit will mostly represent bug fixes, etc.
  - If the modlist is updated from 1.0.0 to 2.0.0, then this version is absolutely, under no circumstances, save safe.
  - If the modlist is updated from 1.0.0 to 1.1.0, then this version is unlikely to be save safe, but it is possible depending on my consistency.
  - If the modlist is updated from 1.0.0 to 1.0.1, then this version should only contain bug fixes and other miscellaneous tweaks that should have no affect on saves.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating. To not have mods delete, add **[NoDelete]** at the beginning of said mod. 

## FAQ

WIP

### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Ambient Occlusion`: Either use this or the ENB version. The ENB version is more intensive. Do not have both turned on.
- `Remove Shadows`: I really don’t recommend turning this on, but if you must, then you can.

If you want to tweak your ENB to improve performance, consider looking at Annakin's [ENB Tips](https://github.com/The-Animonculory/Modding-Resources/blob/main/ENB%20Tips.md) guide. 

To quote her, here is a short answer to improve performance with an ENB turned on.
> #### How can I improve performance?
> - Uncheck `EnableLens`.
> - Uncheck `EnableBloom`.
> - Uncheck `EnableDepthofField`.
> - Uncheck `EnableTessellation` in `WATER`.
> - Uncheck `ComplexFireLights` and `ComplexFireLights` OR
>   - Uncheck `EnableBigRange` in these two settings.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Contact

Please check the [issues](LINK) tab on github first if you have any issues. PLEASE DO NOT DM ME ON DISCORD. If you have an issue with the list, please join the [N/A](LINK) discord for support.

You are welcome to [contribute](LINK) to the list, however please check the [changelog](LINK) before you do.

## Credits and Thanks

- _YOU_ for reading this.
- Ylikollikas for doing the lion's share of the animation work on this project. Without his assistance and feedback, this list would be nowhere near as advanced as it currently is animations and combat wise.
- Curly for allowing me to use his graphical baseline as the core of my list
- [Jolly Co-Operators](https://discord.gg/jolly-coop) for getting me more comfortable with modding
- JustThatKing for his (indirect) help with the graphics
- Bingus, Curly, and iAmMe for helping me with the creation of the list
- Noggog for Mutagen and the xEdit team for xEdit and their tools
- Halgari and everyone the WJ Team
