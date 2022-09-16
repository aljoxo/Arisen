# Changelog

- [1.3.1](#131)
- [1.3.0.1](#1301)
- [1.3.0](#130)

## 1.3.1

### Updated

 - Inconvenient Dungeons
 - Wash That Blood Off 2
 - Inconvenient Dungeons
 - Animation Motion Revolution

### Removed 

 - CLOUDS
    - Reason: Skybox seams.
 - Dwemer Gates No Relock
    - Reason: Redundant mod.
 - Sharpen Other Swords
    - Reason: Redundant mod.

### Added

 - Tru Torches
 - ETHEREAL CLOUDS
 - AnimObject Swapper
 - Sahrotaar Must Die (for LOTD)
 - Inconvenient Dungeons - LOTD Patch
 - Inconvenient Dungeons - Forgotten Seasons
 - Inconvenient Dungeons - USSEP Patch
 - Inconvenient Dungeons - Spawns On The Way Back
 - Sharpen Other Swords 2
 - Poise Staggerlock Prevention

### Dev Notes

 - Changed the name of the list for reasons.
 - Remade Start Save to get rid of the "Missing plugin" error from [1.3.0.2](#1302).
 - Added NFF Ignore tokens to some followers to disincetivize people from importing certain followers. 
 - Fixed Skybox seams.
 - Fixed an incorrect value in the Experience.ini.
 - Fixed the lighting in Snapleg Cave, Tolvald's Crossing, Kolbjorn Barrow, and Ironbind Barrow.
 - DAR Optimizations and SCAR fixes for some movesets.
 - Fixed the Quick Draw perk causing bows to draw at 20% speed rather than 120% speed.
 - Fixed load order issues that were brought up.
 - **IF YOU PLAN ON CONTINUING A SAVE, PLEASE FOLLOW THESE STEPS FOR SAFETY:**
    1. Before updating, go into a cell with no NPCs and make a save (Heimskr's House in Whiterun works pretty well).
       - No NPCs means you also need to dismiss your followers or tell them to wait outside of the cell.
    2. Update the list
    3. Load your save, make a new save, and quit the game
    4. Load your save up in ReSaver and clean any unattached scripts and unidentified references.
    5. When you load/continue your save, you will get a missing plugins warning. Ignore it.
    6. Upon loading into your character, stare at a wall for 10-15 minutes to allow any stuck scripts to clean themselves up.
    7. Go into the `Honed Metal` MCM menu and set `Material Cost Multiplier` to `1.0` (Default: `1.5`).
    8. After following these steps you should safely be able to continue your save.

## 1.3.0.2

### Removed

 - Complete Widescreen Fix
 - Experience - Widescreen Fix
    - Reason: Issues were fixed by the Nordic UI Patches.
 - Alternate Fire FX
    - Reason: Caused issue with fire shaders for player.

### Added

 - Nordic UI 21:9 Patch
 - Nordic UI 32:9 Patch

### Dev Notes

 - Fixed shader effect when the player is on fire.
 - Updated Instructions and Fixed mods for UW Fixes.
 - Note: The main menu for UW is a bit off center, this will be fixed in a future update, for now it's a feature :).

## 1.3.0.1

### Updated

 - Jumping Attack
 - SCAR
 - Borkel's Remiros' Ebony Blade

### Removed

 - Anthology Menus and Music
 - Inferno - Fire Effects Redux
    - Reason: Removing it provided more consistent Fire FX

### Added

 - AutoGibbon's CBPC Settings
 - Glenmoril Throw Animation
 - The Eyes of Beauty Vampire Eyes SE AI
 - Nordic UI Icons for Sunhelm - Nordic...ish UI TrueHUD Color Matched
 - Blunderbuss Animations
 - Simple Pistol Shooting Animation by loop
 - Shiny ENB Eyebrows Begone
 - Skyrim 3D Furniture SMIM Patch

### Dev Notes

 - Main Menu has been updated.
 - Fixed an issue that caused Direction Power Attacks to occur with Jump Attack.
 - Fixed Katana's weapon being invisible.
 - Fixed issue with Auri's facegen that caused crashes when entering her home/a cell with her.
 - Made some changes to the Valhalla Combat MCM setup (recommended by dTry) in an attempt to try and counter issues that may arise between Valhalla's feature system and Skyrim's NPC AI.
 - Fixed some Mod tags for WJ so there should be less issues downloading certain files and some mods that were not installed correctly will now be.
 - Minor Separator reordering.
 - Changed MO2 Separator colors because the Monkeys complained.
 - Fixed a DAR condition error that caused a lack of diversity in Sword movesets for NPCs.
 - Misc DAR folder and conditions optimization.
 - Edits to Dialogue Camera to make it more consistent.
 - Fixed issue with Killmoves.
 - Fixed issue with Vampire Eyes not being correctly given to the player.
 - Fixed issue with Vampire Lords and Werewolves being invisible upon transformation.
 - Fixed issue with unique dragons having their names overridden.
 - Fixed Bound Weapon perks not being applied to Bound Weapons added by New Armoury.
 - Fixed invisible furniture in the College of Winterhold.
 - Optimized some .nifs from Fluffworks - Skyrim Immersive Creatures Patch. 
 - Rebuilt Nemesis due to updating SCAR and Jumping Attack.
 - Updated the Blacklist for some Synthesis Patchers to avoid rogue edits.
 - Reran Synthesis due to updating EasyNPC.
 - ENB Tweaks.
 - Remade Start Save.
 - **This Update SHOULD be save safe with the pre-release versions of 1.3.0, however I make no promises if your save corrupts for some weird reason.**

## 1.3.0

### Updated

 - Synthesis
 - Adamant
 - Daedric Shrines by Mandragorasprouts - LOTD Addon
 - LodGen
 - Grass Resources
 - TexGen
 - DynDOLOD
 - Hand to Hand
 - Lux Via
 - Lux Variants
 - Mysticism
 - Poisebreaker
 - Precision
 - Ryn's Robber's Gorge
 - SCAR
 - Better Chests
 - BnP Child Skin
 - NORDIC UI - Miscellaneous Patches
 - Nemesis Creature Behaviour Compatibility

### Removed

 - s6o6t LORE - Oblivion gates
    - Reason: did not have proper object lods and the popping was a bit unsightly.
 - Vanilla Rain and Snow Remake
    - Reason: True Storms + ENB tweaking makes this redundant
 - IFrame Generator
    - Reason: IFrame Generator RE Released
 - Demoniac CBBE
    - Reason: Swapped skin setup to Realore + PB's Crystal Clear Musclemaps
 - Pride of Valhalla
    - Reason: Swapped skin setup to Realore + PB's Crystal Clear Musclemaps
 - Smooth Random Equip Animations
    - Reason: Trying to reduce DAR Cache time, these animations did not feel fun to play with either. 
 - Realistic Combat AI
    - Reason: Replaced it with Modern Combat AI
 - Heritage
    - Reason: I wanted to cut down some bloat in my NPCs and LVL Lists, Hertiage 2 does a great job by itself as well.
 - Heritage - Reflexive Mysticism Patch
    - Reason: Was a patch dependent on Heritage.
 - Cumulative fix for Eye Meshes
    - Reason: Fixed eye issues with different mods
 - Player extra bright and glowing eyes fix
    - Reason: Fixed eye issues with different mods
 - Taekwondo WTF
    - Reason: Black released his Judge Eyes animation and it fits the role better for what we were trying to accomplish
 - No Enchantment Restriction SKSE Remake
    - Reason: Balancing
 - Archery Tweaks
    - Reason: Mod was redundant and every function it had was already covered elsewhere.
 - Alternate Conversation Camera Plus
    - Reason: Superseded by Improved Alternate Conversation Camera
 - Alternate Conversation Camera Plus Tweaks
    - Reason: Superseded by Improved Alternate Conversation Camera

### Added

 - Katana - Journey in the Shadows
 - Akaviri Katana - LOTD Patch
 - Daedric Shrines Namira - Navmesh
 - Daedric Shrines by Mandragorasprouts - Solstheim Add-On
 - ENB Complex Grass for Veydosebrom
 - Rock Grass for ENB Complex Grass
 - IFrame Generator RE
 - Cosmofujia's Elden Ring Spears
 - Lunar Armory - A Silent Moons Overhaul
 - Missile's IED Presets
 - Obsidian Mountain Fogs Tweaked
 - Sacrosanct and Sacrilege - Remove Auspex Sound
 - True Storms
 - Wait I know You - Forcegreet Tweak
 - Compass Navigation Overhaul
 - Infinity UI
 - Smaller Potion of Blood
 - Creation Club - Gallows Hall - Daedric Shrines Vaermina
 - PB's Crystal Clear Musclemaps
 - Realore Skin Ultima
 - Jarl Sitting Animation Replacer
 - exm42's ADXP | MCO ER Katana
 - Smooth's For Honor in Skyrim Gladiator
 - exm42's ADXP | MCO ER Spear Basic Aniamtion
 - Skysa Nero's redqueen moveset
 - Skysa Dante's rebellion reframed moveset
 - Immersive Impact Redux
 - Perks for Questing
 - Draugr One-handed Animations
 - Modular Armory ROM Patch
 - Legacy of the Dragonborn - Replicas for the Good Guys - House of Horrors Quest Expansion
 - Modern Combat AI
 - Borkel's Remiros' Ebony Blade
 - Smooth Weapon Jump Animation
 - Universal Cured Serana Eye Fix
 - Project Cougar - Inge Six-FIngers
 - Heritage Hand to Hand Integration
    - This mod was actually already in my patches collection of the list but now it's an actual mod...
 - Zim's Dragon Improvements
 - OnMagicEffectApplyReplacer
 - SUEMR SSE with Bijin AIO 2019 Support
 - Eyes AO Clipping Fix
 - Haugbui SimonRim Patch
 - ADXP I MCO JUDGE EYES Crane
 - Jump Attacks
 - Precision Creatures
 - Improved Alternate Conversation Camera

### Dev Notes

 - **Lots** of bug fixes
 - Bloodskaal Blade enchantment fixed
 - Updated patches
 - Assorted mesh, texture, and cubemap fixes
 - Fixed actor fade issues due to incorrect Display Tweaks setup
 - Fixed inventory zoom issues on certain items
 - Fixed the ability to Jump during Dodge animations
 - Removed redundant OCPA mod to avoid confusion
 - Tweaked Projectiles on Concentration spells to be more like the ones from Distar's Projectile mod (Projectiles DXP), they are faster, but also dodgeable unlike previously.
 - Grass should be a bit denser in the tundra now
    - Grass Density was increased by a bit this update, however the performance was similar as I only increased the density on grass in areas that seemed a bit too sparse
 - Lots of Ruvaak ENB Tweaks (thanks bingus)
 - Rebuilt Nemesis
 - Reran Synthesis
 - Rebuilt EasyNPC
 - Added (Possible) Ultrawide and Widescreen Support
 - Cleaned up RaceMenu Presets
 - Cleaned up Bodyslide Presets