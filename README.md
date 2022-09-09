# Apotheosis
![](https://raw.githubusercontent.com/aljoxo/Apotheosis/main/Apotheosis_Banner_MAIN.png)


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
  - [Post-Installation and Optional Setup](#post-installation-and-optional-setup)
    - [Game Folder](#game-folder)
    - [Widescreen Fixes](#widescreen-fixes)
    - [Controller and Gamepad Support](#controller-and-gamepad-setup)
    - [Documentation](#documentation)
    - [BethINI](#bethini)
  - [Playing the List](#playing-the-list)
    - [Starting the Game](#starting-the-game)
    - [In Game MCM Options](#in-game-mcm-options)
  - [Updating Apotheosis](#updating-the-modlist)
  - [FAQ](#faq)
   - [Tweaking the Game Settings](#tweaking-the-game-settings)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

# <ins>**Apotheosis requires the *full* AE upgrade, which means you must *purchase* the AE edition of the game for the list to function.**<ins>

## Preamble

Apotheosis is a Wabbajack modlist centered around providing the player a brand new combat experience by utilizing various mods such as MCO, Precision, and SCAR, as well as an extensive amount of custom movesets to help provide a strong animation foundation. The list uses a mix of SimonMagus' and EnaiSiaion's mods to offer balanced and interesting paths of progression for the player, they are also tweaked to ensure compatibility with the aforementioned combat core.

The full modlist can be viewed [here](https://loadorderlibrary.com/lists/apotheosis).

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

### Minimum Specifications for ~60 fps gameplay at 1920x1080

>  Please note these specs are the best idea of a baseline that I can provide at the current moment, based on feedback I have gotten from testers and my own experiences. In the future this will be updated depending on feedback received.

| Spec Category | Default Profile |
|     :---:    |     :---:     |
| **CPU**   | R7 3700x / i5 10600k |  
| **Video Card**    | RTX 3060 Ti / RTX 2070 / RX 6700 XT       |
| **Ram**    | 16gb (2x16) DDR4 3200mhz RAM     |
| **Storage**    | SATA SSD     |

>  Due to the age of Skyrim, it's hard to pinpoint exactly what specs you will need to run this list. Out of testers who I know the hardware for, one has a 9700k/2070/32gb RAM, one has a 9900k/2080/16gb RAM, and I have a 9700k/3080/32gb RAM. Based on feedback I have gotten the list runs very well with few problematic areas, however I will collect more data before attempting to update these system requirements as to not try and mislead people. 

>  I will **not** be supporting any AMD GPUs from before or from the Polaris Series (RX 500) and any NVIDIA GPUs from before or from the Maxwell Series (GTX 700/900), the only exception for this is the GTX 980 Ti, which is relateively equivelent to a 1660 Ti. These GPUs are simply not powerful enough to handle modded skyrim with an ENB on at 60 frames.

Space required: 
- Approx 380GB (Downloads should be roughly 150GB)

Size without downloads: 
- Approx 230GB

Why is there a discrepancy in what I list as the Approx space required and what the WJ manifest lists? I have no idea, the values I give originally are what my test compiles usually end up around.

### Setting Up Pagefile

Due to the resources required to run modlists like these, you will need to configure the pagefile on your system in order to avoid crashes and bugs that may occur from running out of memory. This step is **NOT** optional, I do not care how much RAM or VRAM you have, please do this step.
  I suggest a 40GB fixed-size pagefile for Apotheosis solely for safety, but it is very possible that you could get away with a 20GB (20480 instead of 40960 in the **Initial** and **Maximum Size** boxes). While a 20GB pagefile may be usable, I do not plan on testing it any time soon, so do so at your own risk.

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

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v6 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime).
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
![](https://raw.githubusercontent.com/iAmMe27/Tahrovin/main/img/ShaderCache.png)

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

Some files require loverslab for this list (none of them are sex mods).
- [Nether's Follower Framework v2.7.9](https://www.loverslab.com/files/file/6188-nethers-follower-framework/)
- [Tempered Skins for Males - SOS Light Version - part 2 of 2 v2.051](https://www.loverslab.com/files/file/3692-sos-light-version-with-tempered-skins-for-males-sse/)
- [SOS - Schlongs of Skyrim - LightSE](https://www.loverslab.com/files/file/3705-schlongs-of-skyrim-light-se/)

Sometimes Google Drive and MEGA will experience bandwidth caps, so below I have included the links to the files that require them.
- [High Poly Head](https://drive.google.com/file/d/15_0njBUjHKidNnJPmLXEygzGVWsA3Zbq)
- [Eskyrim Spear](https://mega.nz/folder/jQdSTTiS#cvXiRP6SSHNm5-RERVrhQw)
- [Olivier Kenjutsu Battleaxe and Warhammer](https://drive.google.com/file/d/1rX4INfO3ieWp25gPh0NiLPl1ktLoegZ9)
- [Olivier Kenjutsu Katana](https://drive.google.com/file/d/14cix5FZNgPiAJV8mfwB2Yfcqchkd1KqJ)
- [Olivier Kenjutsu Sword 2.0](https://drive.google.com/file/d/1MHmaAQnX89tssUziX9NZWoV66B_WwEBf)
- [Olivier Kenjutsu Sword 1.1](https://drive.google.com/file/d/1A8ZQrzA675l1PcDJEOVe3j7rjcnHvp9q)
- [OCPA 1.2](https://mega.nz/file/UOEA0CyL#RP6q-q4zRtc2X0k45FIXfBLh5yS7IrsPAIG7FEZ5Hbc)
- [Tullfx Bloodstorm](https://drive.google.com/file/d/1wu9hwP_7QJC9tWxLwR8QU41txry5u9vA)
- [dint BDOR Hair pack](https://drive.google.com/file/d/16cEFQinG9utc-P5LvOJ3SFtOpfbX24M2)
- [ADXP/SCAR Sneak Fix](https://drive.google.com/file/d/14WLQgjMaExudmcExtXUAfESc0eV_8k6N)
- [Cosmofujia's EldenRing Spears](https://drive.google.com/file/d/1ZEB7-JAPY5OuLESb8jbKLgl57tru5RbX)

Sometimes the SkyrimGuild website also runs into issues so I suggest downloading these in advanced as well.
- [ADXP 1.4.3](https://www.skyrim-guild.com/s/ADXP-Beta-143.zip)
- [DMCO](https://www.skyrim-guild.com/s/DMCO-095.7z)
- [Vanguard](https://www.skyrim-guild.com/s/Vanguard-2_2.rar)
- [Impactful Blocking](https://www.skyrim-guild.com/s/Impactful-Blocking-14.rar)
- [MikeNike Elder Souls](https://www.skyrim-guild.com/s/Elder-Souls-The-Collection-v09-SE-AMR.7z)

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.


- **X** is not a whitelisted download:

	 - This may happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation and Optional Setup

### Game Folder

Apotheosis uses a Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called `Stock Game`. You don’t need to copy anything at all.

### Widescreen Fixes

Apotheosis offers some mods to provide (potential) Ultrawide and Widescreen Support. Under the **(Possible) Ultrawide Support** Separator in MO2 you will find some mods that you will want to activate if you are playing on Ultrawide or Widescreen resolutions (21:9 or 32:9).

**IN ORDER FOR THESE FIXES TO WORK YOU NEED TO DO THE FOLLOWING**
 1. Search for **SunHelm Survival** in the left pane of MO2 and delete or hide the following files:
    a. /interface/skyui/bottombar.swf
    b. /interface/skyui/itemcard.swf
 2. Search for **Experience** in the left pane of MO2 and delete or hide the following files:
    a. /interface/statsmenu.swf

Failing to follow these instructions and asking in support channels how to make the Widescreen fixes work correctly will result in moderator action.

### Controller and Gamepad Setup

Apotheosis offers some mods to provide support for individuals who wish to play with a controller or gamepad. In order to set it up correctly please follow these steps:
 1. Under the **Gamepad Support** Separator in MO2, activate **Gamepad Controlmap Fixed**
 2. **(Optional)** To reduce chances of error, go to `(Path To Modlist)\Stock Game` folder and delete *ControlMap_Custom.txt*
 3. Search for **OCPA Custom for ADXPMCO** in the left pane of MO2
 4. Right Click the mod > Information > INI Files and click on *SKSE\Plugins\OneClickPowerAttack.ini*
 5. Change the following value(s):
   a. **Keycode=47** to **Keycode=281**
     - This will change the power attack bind to right trigger, if you wish to use a different key please refer to [this link](https://www.creationkit.com/index.php?title=Input_Script).

Failing to follow these instructions and asking in support channels how to use a controller or gamepad correctly will result in moderator action.

### Documentation

 - To get an idea of what animations are used in the list, click [here](https://github.com/aljoxo/Apotheosis/blob/main/Animation%20Documentation.md).
 - To know what graphic mods are used in the list, click [here](https://github.com/aljoxo/Apotheosis/blob/main/Graphics%20Documentation.md)

## Playing the List

### Obligatory DAR Cache warning: due to the nature of this list and the amount of DAR based animations it uses, it does take some time (usually 15-30 seconds) at the start of each play session for DAR to cache all the folders and animations. While cleaning up the folder setup to try and alleviate this issue is a long term goal for the list, please do realize that this issue is out of our control as it is an issue with DAR itself since it does not allow for pre-cacheing animations via Nemesis or during loading screens. If you complain about this in the discord, on nexus, or on the github page, you will be linked back here.

### Starting the Game
 - **(Optional)** For those of you with arachnophobia, the list includes a mod called *bingus hates spiders.esp*, this is my personal patch that removes spiders from the leveled list and replaces spiders with other creatures within the list. It also has a few other tweaks to make it a bit more in depth than something like *Insects begone*.
    - At the current moment the patch only affects spiders (so chaurus and similar will still be present, tho if requested I could make another version of this patch that also removes those mobs).
 - Launch the "Play Apotheosis!" Executable in MO2
 - Apotheosis comes with a start save by default, so when you load into the main menu, choose "Continue".
 - For alternate start mods, Apotheosis uses [Skyrim Unbound](https://www.nexusmods.com/skyrimspecialedition/mods/27962).
    - In order to start chargen hit **Enter** as soon as you load in
        - If your character seems to be frozen during RaceMenu, just swap race or gender and swap back, it should unfreeze them. This is an issue with DAR Cacheing.
    - Once you are finished with chargen, feel free to open up the **Skyrim Unbound** MCM menu and customize your Standing Stone, whether or not you're a vampire, equipment, spells, and starting location.
        - You may also want to choose whether or not your character is the Dragonborn; and if they are not, whether or not they are able to use shouts.
     - Once you are finished choosing your options for the Alternate Start you desire, hit **Enter** again and choose **Continue**.
 - Read over the Control map.
![](https://github.com/aljoxo/Apotheosis/blob/main/apotheosis-standard-keybinds%20(1).png)

### In-Game MCM options

 - **Skyrim Unbound**: Choose your Standing Stone, starting location, starting equipment, starting wealth, etc. By default the player is set to become Dragonborn, so if you do not want that for some reason, turn it off.
 - **AGO**: By default Apotheosis disables many features of AGO, if you wish to re-enable them then do so here
 - **Better Third Person Selection**: Enables the filters to reduce the possibility that the player character accidentally steals items when trying to interact with the world. Turn these filters off if you do not like them.
 - **Bow Charge Plus**: Dodge Shot does not work with DMCO.
 - **Dodge Framework**: Change your *dodge* keybind here.
 - **Dual Wield Block**: Change your *Dual Wield Block* keybind here. **REMEBER TO CHANGE IT IN VALHALLA MCM MENU AS WELL**
 - **Hide Your Quests**: Allows you to hide quests from your journal (not useful on startup, obviously).
 - **Leveling Freedom**: By default the list should use the "Recommended" settings. Feel free to choose another preset or make your own to customize the leveling curve.
 - **Lucien**: Can choose a name or nickname for Lucien to call you by (if available).
 - **Optimal Potion Hotkey**: Change your *Health potion hotkey*. Add a hotkey for stamina/magicka potions.
 - **Seiro's Hotkeys**: Set up additional hotkeys here.
 - **Simplest Horses**: Change your *Horse Control hotkey* here.
 - **Static Skill Leveling**: MCM menu does not work, if you wish to tweak this, do it in xedit.
 - **SunHelm**: Disabled by default, can be activated through the MCM or by sleeping in a bed.
    - I suggest putting the "Widget Display Type" to *Alpha Based*
 - **Taunt Your Enemies**: Change you *Taunt* keybind here.
 - **True Directional Movement**: Change your *Target Lock* keybind here.
 - **Valhalla Combat**: The core of the combat balance in the list. 
    - Stamina: The settings here have been configured for what has been determined to be the most balanced gameplay. Feel free to tweak them to your liking.
    - Timed Block: You can enable or disable the *Tackle* mechanic (default: enabled).
    - Stun&Execution: By default the list disables dTry's stun system as it is not well balanced right now.
    - Compatibility: Please **do not** enable the Poise compatibility option. While the list does use Poise, due to the DAR setup and witchcraft we have done to make it play nicely, enabling this compatibility option breaks the setup. If you changed your *Dual Wield Block* keybind in **Dual Wield Block** MCM, then please also change it here. 
      - If *TrueHUD API* does not say "Obtained" next to them, try updating TrueHUD and True Directional Movement (this should not be a problem unless you modify the list). 
      - If *Special Meter Control* says "Not Obtained", do not worry about this. As of current the Stun System is disabled due to balancing reasons.

### Anniversary Edition

Apotheosis is on a [downgraded](https://www.nexusmods.com/skyrimspecialedition/mods/57618) version (1.5.97) of Skyrim. As stated at the top of this document, it **does require** the paid update.



## Updating the modlist

Before updating, please check the [changelog](https://github.com/aljoxo/Apotheosis/blob/main/ApotheosisChangelog.md) and back up your saves. You may need to start a new game after certain updates. If you are curious to know if an update is save safe or not, then refer to the version number. The first digit should indicate major version, second digit should indicate minor version (these are likely to be save safe unless otherwise specified), the third digit will mostly represent bug fixes, etc.
  - If the modlist is updated from 1.0.0 to 2.0.0, then this version is absolutely, under no circumstances, save safe.
  - If the modlist is updated from 1.0.0 to 1.1.0, then this version is unlikely to be save safe, but it is possible depending on my consistency.
  - If the modlist is updated from 1.0.0 to 1.0.1, then this version should only contain bug fixes and other miscellaneous tweaks that should have no affect on saves.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating. To not have mods delete, add **[NoDelete]** at the beginning of said mod.
**ALWAYS** back up saves before an update. Because of the method Wabbajack uses to include the start save, any save within the profile will be wiped. Please Please Please make sure you back up your saves if you plan on continuing a playthrough across a **save safe** update.

## FAQ

I will update this section as I see fit.

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

Please check the [issues](https://github.com/aljoxo/Apotheosis/issues) tab on github first if you have any issues. PLEASE DO NOT DM ME ON DISCORD. If you have an issue with the list, please join the [Waking Dreams](https://discord.gg/4WwqfK5yHg) discord server for support.

## Credits and Thanks

- _YOU_ for reading this.
- Ylikollikas for doing the lion's share of the animation work on this project. Without his assistance and feedback, this list would be nowhere near as advanced as it currently is animations and combat wise.
- Curly for allowing me to use his graphical baseline as the core of my list (check out Ascensio whenever it releases).
- Bingus for helping me with ENB, testing, and tweaking some assets (also many mod page screenshots and the logo/banner and MO2 splash)
- iAmMe for helping me with the CK, documentation, and general WJ related things. As well as fixing some of my Facegen (check out [Tahrovin](https://github.com/iAmMe27/Tahrovin) if you have a VR headset).
- [Jolly Co-Operators](https://discord.gg/jolly-coop) for getting me more comfortable with modding
- JustThatKing and jdsmith2816 for their help with graphics and some miscellaneous
- Noggog for Mutagen and the xEdit team for xEdit and their tools
- Halgari and the WJ Team for this amazing platform
