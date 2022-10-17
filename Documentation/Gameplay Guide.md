# Arisen Gameplay Guide

![](https://raw.githubusercontent.com/aljoxo/Arisen/main/Media/Arisen_Banner_with_Logo.png)

> *You thought to reject me, and yet here you are. Your journey towards enlightenment has finally led you here, to my realm, as I knew it would.*

## Initial Setup

Before reading this guide, please follow the [readme](https://github.com/aljoxo/Arisen/blob/main/README.md) as it will answer the vast majority of technical questions related to getting the list setup and running. It also has information regarding customizing certain aspects of the list via the MCM menus. Note that this list is meant to be played in 3rd Person. **If you hate reading, I recommend, at the very least, that you read the [Foundations](#the-foundations), [New Mechanics](#new-mechanics), and [Special Attacks](#special-attacks) sections in order to have a grasp over how the list will play.**

### Skryim Unbound Reborn
> *So you are the one the tides of fate carried here to stop this trangression.*

Press `Enter` to start character generation and to get the popup box if you want to "Swap Gear" or choose to "Stay Here" after creating your character. On top of the chest to your left there will be a free Vanity Mirror, it is suggested that you pick it up before leaving if you wish to customize your character at any point during your playthrough (if you miss it here, then it can be crafted at a tanning rack later). **If you want to customize the MCM menus you must choose "Stay Here" after completing character creation.**

## Gameplay - Combat
> *One of you must fall. Let it be your opponent.*

### The Foundations

 - [ADXP | MCO](https://www.skyrim-guild.com/distars-mods/adxp-mco) is the core framework mod in the list. ADXP takes the modern approach to Skyrim's Combat, introducing movement lock and adding attack commitment. [SCAR](https://www.nexusmods.com/skyrimspecialedition/mods/72014) is utilized to allow NPCs to properly utilize combos within MCO's framework. To view what animations are used within the list, check out the Animation Documentation [here](https://github.com/aljoxo/Arisen/blob/main/Documentation/Animation%20Documentation.md).  
 - [True Directional Movement](https://www.nexusmods.com/skyrimspecialedition/mods/51614) massively overhauls the 3rd person experience, allowing the player to move and attack in any direction, includes a custom target lock feature, and many other miscellaneous improvements. [SmoothCam](https://www.nexusmods.com/skyrimspecialedition/mods/41252) provides a highly configurable third-person camera framework to further improve and modernize 3rd person gameplay.  
 - [DMCO](https://www.skyrim-guild.com/distar/mods/dmco) is the Dodge mod of choice. Using custom animations and sounds. The keybind is configurable via the Dodge Framework MCM menu, and by default is set to `Left Alt`.  
 - [Precision](https://www.nexusmods.com/skyrimspecialedition/mods/72347) and [Precision Creatures](https://www.nexusmods.com/skyrimspecialedition/mods/74887) are used to solve the age long problem of hit cones in skyrim, making it so that collision is based on the mesh of the actors rather than the controller's colliders. Leading to a more consistent gameplay feel.  
 - [One Click Power Attack](https://www.nexusmods.com/skyrimspecialedition/mods/60878) separates the Light and Heavy (or Power) attack binds, allowing you to more easily chain combos. The keybind for Power attacks is configurable via the `OneClickPowerAttack.ini` file, and by default is set to `V`.  
 - [Dual Wield Block](https://www.nexusmods.com/skyrimspecialedition/mods/58548) allows you to block as a spellsword. The keybind is configurable via the MCM menu, and by default is set to `B`.  

### New Mechanics

You will quickly notice that Arisen is not the Skyrim that you once knew, and in conjunction with the frameworks above, many mods are used to improve upon the Combat experience.
 - [Valhalla Combat](https://www.nexusmods.com/skyrimspecialedition/mods/64741) is the main combat mod of the list and is responsible for features like timed blocking, projectile parrying, the stamina management system, and much more. Many of these features can be tweaked via the MCM menu.
     - **Key mechanics to note**:  
         - Valhalla's Stamina system is **disabled** in Arisen due to balancing issues.  
         - Blocking now costs Stamina, once an actor's Stamina is depleted, blocking will cost Health.  
         - Blocking Projectiles (Spells & Arrows) costs Magicka, once an actor's Magicka is depleted, blocking projectiles will cost Health.  
         - **Timed Blocks** can be achieved by pressing the block button within 0.3 seconds of being hit, timed blocks consume half as much stamina as normal blocks.  
         - **Perfect Timed Blocks** can be achieved by pressing the block button within 0.15 seconds of being hit, perfect timed blocks will fully refill your stamina bar and stagger the attacker.  
         - **Tackle** can be performed by pressing the block button during a Power Attack animation, tackle will grant 0.2 seconds of invulnerability after activated.  
 - [Fenix Stamina Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/50502) is the framework used to modify Stamina costs.  
     - Light attacks and power attacks now BOTH cost stamina. The Stamina cost is primarily dependent on weapon weight.  
     - Stamina costs decrease as you become more proficient in your weapon skill.  
     - Stamina regeneration is very high, both in and out of combat.  
 - [Elden Parry](https://www.nexusmods.com/skyrimspecialedition/mods/70240) allows you to parry attacks by pre-emptively bashing an enemy before they hit you. Light bashes will also no longer deal any damage or stagger your opponents, but they do cost stamina as they act as failed parries.
 - [POISE](https://www.nexusmods.com/skyrimspecialedition/mods/72653) and [Poisebreaker](https://www.nexusmods.com/skyrimspecialedition/mods/74032) combine to cover the core of the stagger and knockback system within the list. 
 - [Block Enchantments](https://www.nexusmods.com/skyrimspecialedition/mods/60833) and [Paulicus Poison Block](https://www.nexusmods.com/skyrimspecialedition/mods/51046) will improve the blocking experience by allowing the player (and NPCs) to block previously unblockable effects.
 - [Action Based Projectiles](https://www.nexusmods.com/skyrimspecialedition/mods/54611) and my personal tweaks will make spells and arrows feel more balanced and dodgeable. Allowing for more interesting gameplay.
 - [Rapid Bow Combo](https://www.nexusmods.com/skyrimspecialedition/mods/65461) and [Bow Charge Plus](https://www.nexusmods.com/skyrimspecialedition/mods/59124) seek to provide some new gameplay benefits for Archery and Marksmanship focused gameplay. You can learn more about these mods on their mod pages.
 - [Conduit](https://www.nexusmods.com/skyrimspecialedition/mods/58023) allows you to temporarily infuse your weapon, granting a clean interaction between spell and blade.
 - [ZUPA](https://www.nexusmods.com/skyrimspecialedition/mods/45182) and [Smart Optimal Salves](https://www.nexusmods.com/skyrimspecialedition/mods/42402) improve potion gameplay by adding animations for drinking potions (for both player and npc) and providing an easy keybind, changeable via MCM. (Default: `F`)

### Special Attacks

Special Attacks, inspired by Elden Ring's [Ashes of War](https://eldenring.wiki.fextralife.com/Ashes+of+War) are a system UNIQUE to Arisen and were developed in house. It's still a work in progress development, however as of **Version 1.4.0** they will be implemented into the list and gradually expanded upon. Special Attacks are activated pressing a modifer key and the Power Attack keybind.  
 - The modifier key can be changed in the `Ashes of War.ini` found in the `[Path to Modlist]\mods\!!! Ashes of War !!!\SKSE\plugins\dtryKeyUtil\config\custom` folder. By default, the modifier key is set to `L CTRL` for Keyboards and `A` for Gamepads.  
     - **DO NOT SET THE MODIFIER KEY TO BE THE SAME AS YOUR SPRINT KEY**.  
 - The default power attack key is stated in multiple places on the ReadMe and in this guide, as well as being visible on the controlmap image.

### AI and Enemies

Enemies have been drastically improved in Arisen to try and create a more engaging gameplay experience.
 - [Know Your Enemy](https://www.nexusmods.com/skyrimspecialedition/mods/13807) adds a trait based system to edit the resistances and weaknesses of creatures and armors, incentiving the player to seek out creative ways of dealing with certain enemies. I would suggest reading the mod page to learn more.
 - A tweaked version of [Arena](https://www.nexusmods.com/skyrimspecialedition/mods/33487) reworks the encounter zones across Skyrim to be more consistent dependent on the types of enemies you expect to face.
 - [Ultimate Combat](https://www.nexusmods.com/skyrimspecialedition/mods/17196) and [Ultimate Dragons](https://www.nexusmods.com/skyrimspecialedition/mods/26374) makes fighting creatures, such as Draugr, Falmer, Centurions, and Dragons (duh) more engaging by augmenting their movesets.
 - [Modern Combat AI](https://www.nexusmods.com/skyrimspecialedition/mods/74716) makes enemies more aggressive and more reckless in groups, so be cautious when trying to fight off the hordes.
 - [Dragon War](https://www.nexusmods.com/skyrimspecialedition/mods/51310) is the Dragon Overhaul of choice. 
 - [Populated Dungeons](https://www.nexusmods.com/skyrimspecialedition/mods/2820) and [Populated Forts](https://www.nexusmods.com/skyrimspecialedition/mods/1514) seek to make the world more lived in, increasing enemy density in a fair, and not excessive, way.
 - [Real Bosses](https://www.nexusmods.com/skyrimspecialedition/mods/18183) and my own tweaks help overhaul the boss fights from Vanilla Skyrim, making them more difficult and memorable.
 - [Draugr MCO Enabled](https://www.nexusmods.com/skyrimspecialedition/mods/75165) replaces certain types of Draugr with new NPCs who look and act like draugr, but are able to take full advantage of the elevated combat of the list.
 - [Haugbui](https://www.nexusmods.com/skyrimspecialedition/mods/26188), [Draugr Upgrades and Improvements](https://www.nexusmods.com/skyrimspecialedition/mods/21775), and [Cannibal Draugr on Solsetheim](https://www.nexusmods.com/skyrimspecialedition/mods/21238) further improve the encounters with Skyrim's most infamous enemy type.
 - [Skyrim Immersive Creatures](https://www.nexusmods.com/skyrimspecialedition/mods/12680), [opusGlass's](https://www.nexusmods.com/skyrimspecialedition/users/6123863?tab=user+files) Bloodmoon Creature Restoration Project, and select creatures from [4thUnknown](https://www.nexusmods.com/skyrimspecialedition/users/49002333?tab=user+files) seek to increase the variety of enemies within the world, while staying lore friendly.
 - Distar's [Creatures](https://www.skyrim-guild.com/distar/mods/creatures) improve the animations of bears and sabrecats, giving them telegraphed attacks.
 - [Heritage 2](https://www.nexusmods.com/skyrimspecialedition/mods/55989) adds some much needed diversity and unique enemy types, making Bandits, Warlocks, and Vampires more unique and challenging opponents.
 - [Smart NPC Potions](https://www.nexusmods.com/skyrimspecialedition/mods/40102) gives NPCs potions to use in combat.

## Gameplay - Overhauls
> *Knowledge for knowledge. That is my price.*

### Perk Trees, Races, and Standing Stones

Arisen seeks to provide the player with lightweight systems from which to build their character off of, while this can be argued to detract from some of the RPG elements, it helps maintain the approach to balance that the list has.
 - [Adamant](https://www.nexusmods.com/skyrimspecialedition/mods/30191) and the [Hand to Hand](https://www.nexusmods.com/skyrimspecialedition/mods/59790) addon for the perk trees. Perks have been tweaked to ensure they meld better with the rest of the gameplay in the list.
 - [Phylogeny](https://www.nexusmods.com/skyrimspecialedition/mods/44371) is the race mod of choice for the list.
 - A mashup of [Constellations](https://www.nexusmods.com/skyrimspecialedition/mods/43763) and [Mundus](https://www.nexusmods.com/skyrimspecialedition/mods/33411) provide the standing stone buffs. For more information see the [Standing Stones](#standing-stones) section.  
 - [Sacrilege](https://www.nexusmods.com/skyrimspecialedition/mods/42408) and [Growl](https://www.nexusmods.com/skyrimspecialedition/mods/31245) overhaul Vampires and Werewolves.
 - [Forceful Tongue](https://www.nexusmods.com/skyrimspecialedition/mods/36276), [Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/41950), [Sil Gahrot](https://www.nexusmods.com/skyrimspecialedition/mods/52007), and [True Teacher Durnehviir](https://www.nexusmods.com/skyrimspecialedition/mods/44969) improve the progression and learning of Shouts.
 - [Honed Metal](https://www.nexusmods.com/skyrimspecialedition/mods/61015) provides the player a new gold sink and a way to improve their gear without over investing into crafting trees.
 - [Perks from Questing](https://www.nexusmods.com/skyrimspecialedition/mods/29402) gives the player new and unique perks upon completion of specific quests. 

### Progression

Now that we've discussed the perks and general progression itself, let's talk about how you will actually improve your character within the list. Gone are the days of traditional Skyrim leveling. As of version 1.4, Arisen has changed to a system in which perks are rewarded by completing content and exploring.
 - [Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751) and [Static Skill Leveling](https://www.nexusmods.com/skyrimspecialedition/mods/30410?tab=description) completely overhaul the way you improve skills and level within the list.
     - The skill caps for experience are as follows: 20 base skill, increasing by 2 every level, plus racial bonus. For example, a nord at level 2 would have a skill cap of 32 in Two-Handed (20 base + 10 from racial + 2 from level), but only a skill cap of 22 in Destruction (20 base + 0 from racial + 2 from level).
     - You must **sleep** in a bed after leveling up in order to advance your skills via the Static Skill Leveling menu.
 - [Skyshards](https://www.nexusmods.com/skyrimspecialedition/mods/60748) Hunting for Skyshards has (finally) been added to Arisen! You can now travel the map and find Skyshards, which can be identified by their enormous pillar of blue light, inspired by ESO. You receive 1 perk point for every 3 Skyshards absorbed.
 - [Radiant Quest Point System](https://www.nexusmods.com/skyrimspecialedition/mods/67956) Introducing a unique point system that rewards completion of radiant quests with perks points, providing fresh incentive to do so. Include a variety of mod patches.
 - [Quests Award Perk Points](https://www.nexusmods.com/skyrimspecialedition/mods/33081) You earn perk points for completing large-scale objectives in this ESO-inspired system. Includes patch for VIGILANT.
 - [Smart Training - Tweaked](https://www.nexusmods.com/skyrimspecialedition/mods/18048) If you don't train the maximum number of times permitted on your current level, your training will now carry over to the following level. Additionally, each time you train you gradually acquire a new perk point.
 - [Potion Of Obtainable Progress](https://www.nexusmods.com/skyrimspecialedition/mods/74888) One perk point can be obtained by drinking each of the (approx.) 25 potions that have been manually placed in certain dungeons. Placements have been considerably increased from the base mod. Be sure to be thorough when looting!
 - [Special Perks from Questing](https://www.nexusmods.com/skyrimspecialedition/mods/29402) As specific quest lines and quests are completed, Special Perks are awarded (located in the Active Effects Menu). This mod is different from the others in that it gives you passive bonuses to fit your build and playstyle rather than perk points.
 - [Ish's Respec Mod](https://www.nexusmods.com/skyrimspecialedition/mods/1960) adds a potion to the game that allows you to respec your perk points. You can find them at Elgrim's Elixirs in Riften.

### Magic, Artifacts, and the Arcane

Continuing with a lightweight and balanced approach, these are some more mods you can expect to find within the list.
 - [Mysticism](https://www.nexusmods.com/skyrimspecialedition/mods/27839) provides a complete overhaul of Skyrim's magic system, balancing existing spells and adding some new types.
 - [Apocalypse](https://www.nexusmods.com/skyrimspecialedition/mods/1090) is a classic, adding a ton of new spells to the game to provide some new tools for mages.
 - [Thaumaturgy](https://www.nexusmods.com/skyrimspecialedition/mods/57138) and [Apothecary](https://www.nexusmods.com/skyrimspecialedition/mods/52130) overhaul the Enchanting and Alchemy systems in a balanced way.
 - [Oblivion](https://www.nexusmods.com/skyrimspecialedition/mods/69513) improves upon Skyrim's Atronach Forge, expanding its functionality by adding many new recipes and exclusive spells.
 - [Arachnomancy](https://www.nexusmods.com/skyrimspecialedition/mods/67272) overhauls the spider scrolls crafting system added in the Dragonborn DLC.
 - [Reliquary of Myth](https://www.nexusmods.com/skyrimspecialedition/mods/31612) and select [Zim's Immersive Artifacts](https://www.nexusmods.com/skyrimspecialedition/mods/9138) are used to overhaul the artifacts.
 - [Wintersun](https://www.nexusmods.com/skyrimspecialedition/mods/22506) is the religion mod of choice for the list, granting the player new paths and powers.

### Survival (Optional)

For those who seek to make their gameplay a little more intense and/or immersive, Arisen includes an optional Survival Addition.
- [SunHelm](https://www.nexusmods.com/skyrimspecialedition/mods/39414) was opted for over the Creation Club Survival Mode, due to being a relatively lightweight mod with a solid survival framework.
     - **Key mechanics to note**:  
         - Configurable via MCM.  
         - You **must** sleep to level up if you activate SunHelm.  
- [Harsher SunHelm Cold](https://www.nexusmods.com/skyrimspecialedition/mods/63548) makes the cold regions of Skyrim a bit more reflective of their true nature. By making the cold mechanics of SunHelm more dangerous, it is advised that you plan accordingly.
- [SunHelm Auto Eat and Drink](https://www.nexusmods.com/skyrimspecialedition/mods/66772) is there for individuals who like playing Survival Mode for the realism and gameplay it creates, but don't enjoy the tedium of having to remember to eat and drink.

## Gameplay - Content
> *I have been watching you, mortal. Most impressive.*

### Vanilla Quest Improvements and Expansions

Arisen includes a significant amount of tweaks and improvements to the vanilla guilds and quests, here are some notable ones.
 - [Enhanced Skyrim Factions - Companions](https://www.nexusmods.com/skyrim/mods/22650) provides a better progression curve to the Companions questline and makes it so that you must actually be a warrior to progress through the entire questline.
 - [Thieves' Night on the Town](https://www.nexusmods.com/skyrimspecialedition/mods/42069) overhauls the radiant quests for the Thieves Guild.
 - [College of Winterhold - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/66666), [Improved College Entry - Questline Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/22184), and [Finding Velehk Sain](https://www.nexusmods.com/skyrimspecialedition/mods/19815) expand upon the content within the College of Winterhold.
 - [Choose Your Own Arch-Mage](https://www.nexusmods.com/skyrimspecialedition/mods/30887) lets **YOU** decide who should be the Arch-Mage of the college.
 - [Paarthurnax - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/51711) a fully voiced expansion to the Paarthurnax Quest, allowing you to spare the best character in the game.
 - [The Only Cure - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/57683) and [House of Horrors - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/57285) provide some alternate routes for 2 of the Daedric Quests.
 - [Nilheim - Misc Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/53792) and [Caught Red Handed - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/65708) expand upon some vanilla quests.
 - [Penitus Oculatus](https://www.nexusmods.com/skyrimspecialedition/mods/21061) allows you to join the Penitus Oculatus after destroying the Dark Brotherhood, providing an alternative way to reap the rewards.
 - [Realistic Dark Brotherhood Kidnapping](https://www.nexusmods.com/skyrimspecialedition/mods/68260) makes the conditions for the abduction event a little more realistic.
 - [After the Civil War - Siege Damage Repairs](https://www.nexusmods.com/skyrimspecialedition/mods/20668) allows you to clean up the damage left over from the Civil War after its conclusion.


### New Quests and Content

Arisen's "ideal" content progression is outlined in the ReadMe [here](https://github.com/aljoxo/Arisen/blob/main/README.md#faq), however it includes much more than what is discussed there.
 - [Legacy of the Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/11802), I don't think anything needs to be said about this mod, while some may argue that it makes the game too focused on the Museum and hoarding items, I believe this to be specific to the player. This list does not include Curator's Companion which should lessen the feel that the entire game revolves around collecting for the Museum.
 - The Vicn Trilogy including [VIGILANT](https://www.nexusmods.com/skyrimspecialedition/mods/11849), [GLENMORIL](https://www.nexusmods.com/skyrimspecialedition/mods/32998), and [UNSLAAD](https://www.nexusmods.com/skyrimspecialedition/mods/11789) comprise the core of the "added content."
 - [Identity Crisis](https://www.nexusmods.com/skyrimspecialedition/mods/39634) investigate the madness afflicting the Northern Asylum of Julianos, and encounter the Madgod himself.
 - [Waking Nightmare](https://www.nexusmods.com/skyrimspecialedition/mods/34329) a journey into Quagmire, allowing the player to earn the favor of Vaermina.
 - [The Tale of Tsatampra Xiros](https://www.nexusmods.com/skyrimspecialedition/mods/36707) a questline that allows you to further explore the realm and earn the favor of Hermaeus Mora.
 - [Carved Brink](https://www.nexusmods.com/skyrimspecialedition/mods/24351) explore Peryite's realm - The Pits, and an unbeforeseen realm of Oblivion - Faceted Stones.
 - [Moon and Star](https://www.nexusmods.com/skyrimspecialedition/mods/4301) a short questline revolving around a powerful criminal from Morrowind who has been spotted in Skyrim.
 - [Nordic Lore Integration - The Stone of Snow-Throat](https://www.nexusmods.com/skyrimspecialedition/mods/21250) explore the caverns beneath the Throat of the World and discover the a place of Nordic legend.
 - [Missives](https://www.nexusmods.com/skyrimspecialedition/mods/17576) and [Headhunter](https://www.nexusmods.com/skyrimspecialedition/mods/51847) overhauls the bounty system and adds onto the radiant questing system.
 - [Cheesemod](https://www.nexusmods.com/skyrimspecialedition/mods/36506), because who doesn't love some fine cheese?

### New Followers and NPCs

What good is a world without NPCs? Here are the added followers and other NPC related mods included in the list.
 - [Serana Dialogue Add-On](https://www.nexusmods.com/skyrimspecialedition/mods/32161) and [Queen of the Damned - Dealier Serana](https://www.nexusmods.com/skyrimspecialedition/mods/16815) to make Serana the best ~~waifu~~ follower.
 - [Improved Follower Dialogue - Lydia](https://www.nexusmods.com/skyrimspecialedition/mods/38473) a complete revamp of Lydia, offering new lines, new quests, and more for one of Skyrim's most famous supporting characters.
 - [Teldryn Serious](https://www.nexusmods.com/skyrimspecialedition/mods/5541) is a lore-friendly, fully voiced quest about Teldryn Sero's past.
 - [Kaidan 2](https://www.nexusmods.com/skyrimspecialedition/mods/19075) is a staple follower who swears a lot. He can be found under captivity of the Thalmor in the Abandoned Prison.
 - [Song of the Green (Auri Follower)](https://www.nexusmods.com/skyrimspecialedition/mods/11278) another ~~waifu~~ good follower mod, with dialogue and banter interactions. She can be found in the forests of Falkreath.
 - [Lucien](https://www.nexusmods.com/skyrimspecialedition/mods/20035) is an expansive, lore-friendly follower who will grow alongside the player. He can be found in Falkreath's Dead Man's Drink.
 - [Katana - Jounery in the Shadows](https://www.nexusmods.com/skyrimspecialedition/mods/69622) offers two custom-voiced followers (rogue and healer), a quest, and a unique relationship system. You can find Katana in the Winking Skeever in Solitude.
 - [Xelzaz - Custom Fully Voiced Argonian Telvanni Follower](https://www.nexusmods.com/skyrimspecialedition/mods/62893) adds a fully voiced, feature full Argonian companion with a significant amount of dialogue and unique relationship system. You can find Xelzaz near Dayspring Canyon at the Southern Morrowind Gate. 
 - [Nebarra - Fully Custom Voiced Altmer Follower](https://www.nexusmods.com/skyrimspecialedition/mods/42343) adds a High Elf mercenary with a unique outfit system and a significant amount of dialogue. You can find him near Knife Point Ridge at the remains of a scorched carriage.  
 - [Remiel-Custom Voiced Dwemer Specialist and Companion](https://www.nexusmods.com/skyrimspecialedition/mods/51874) adds a Breton engineer with a deep appreciation and curiousity about the Dwemer. You can find her in the Silver Blood Inn in Markarth.
 - [Khash The Argonian (A Fully Custom Voiced Follower) (SOT - Sidekicks of Tamriel)](https://www.nexusmods.com/skyrimspecialedition/mods/40122) adds a stupid Argonian to the game, she's annoying and swears a lot. You can find her at the Sleeping Giant Inn in Riverwood.  
     - According to fray, "she's an inspiring merc hoping someone will give her a chance." But I still think she's annoying.
 - [Meeko Reborn](https://www.nexusmods.com/skyrimspecialedition/mods/17572), [Vigilance Reborn](https://www.nexusmods.com/skyrimspecialedition/mods/17571), and [Unique Barbas Retexture](https://www.nexusmods.com/skyrimspecialedition/mods/17540) give the dogs of Skyrim a more unique look.
 - [Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194) and [Citizens of Tamriel](https://www.nexusmods.com/skyrimspecialedition/mods/29069) make the world feel more lived in and fleshed out by adding many new, fully voiced NPCs.

### Managing Followers

Because people asked for it and do not know how to read mod pages, here I will go over what mods manage followers in the list.
 - [Simple Offence Suppression](https://www.nexusmods.com/skyrimspecialedition/mods/41764) and [Simple Offence Suppression MCM - Block Friendly Fire](https://www.nexusmods.com/skyrimspecialedition/mods/41774) stop friendly fire. If you're unable to kill an NPC for whatever reason, this mod is the cause. You can disable it in the MCM. 
 - [Simple Offence Suppression](https://www.nexusmods.com/skyrimspecialedition/mods/41764) and [Simple Offence Suppression MCM - Block Friendly Fire](https://www.nexusmods.com/skyrimspecialedition/mods/41774) stop friendly fire. If you're unable to kill an NPC for whatever reason, this mod is the cause. You can disable it in the MCM. 
 - [Simple Follower Extension](https://www.nexusmods.com/skyrimspecialedition/mods/36060) increases the follower count to 10 (does not include 3DNPCs, which still only allows 1, but you can use set 3dnpcfollowercount 0 in console to have more 3DNPCs followers), stops them from triggering traps, allows them to relax when waiting, tries to stop your followers from getting too far away, and tries to stop them from fighting each other. 
 - [Party Damage Control](https://www.nexusmods.com/skyrimspecialedition/mods/62613) nerfs you and your followers based on how many people are in party (including you!).
 - [Disable Follower Collision](https://www.nexusmods.com/skyrimspecialedition/mods/35925) simply allows you to walk through followers. This doesn't allow you to walk through Pets of Skyrim followers however, to do that you need to do setplayerteammate 1 on them in console command (bare in mind this will allow enemies to target and attack them, so consider making them essential in console too!).
 - [Configurable Commentary Rate Slider](https://www.nexusmods.com/skyrimspecialedition/mods/38670) allows you to set how much followers talk as you explore. If they talk too little or too much, you can edit it in the MCM.

### Dungeons

This section is an addition to the gameplay guide because I (aljo) am tired of explaining and justifying why Arisen uses the mod [Inconvenient Dungeons](https://www.nexusmods.com/skyrimspecialedition/mods/66784).
 - [Inconvenient Dungeons](https://www.nexusmods.com/skyrimspecialedition/mods/66784) is a mod that removes or otherwise alters the back-exits from **65** dungeons in Skyrim. I included this mod for a few reasons that I will go into here.  
     1. **It's immersive.** Have you ever watched a video analyzing the Elder Scrolls series that discusses how the back-exists in most dungeons both make no sense and are bad design (or even better the [Senile Scribbles Skit](https://www.youtube.com/watch?v=hAbLhKvBDec&t=1059s))? Because I have, and I agree.  
     2. **It freshens up the dungeon experience.** Some (a lot) of people like to complain about how this mod is "tedious" and only causes inconvenience for the player. I disagree. Especially with the "Spawns on the way back" addon that was introduced in the 2.0 version of the mod, I think inconvenient dungeons is fun and allows you to experience the combat more.  
     3. **The paraglider (and other mechanics).** There are many dungeons in the list in which you can utilize the paraglider (or similar mechanics from other mods) to get around or otherwise negate many of the added "inconveniences" from Inconvenient Dungeons. I highly suggest that you utilize every tool available to you as the player.  
     4. **Ok aljo, I understand what you're saying, but I still don't like the mod and would like to remove it.** While I do not, and will not, support the modification of the list in such a way, someone else has made a guide on how to do so [here](https://github.com/aljoxo/Arisen/blob/main/README.md#removing-the-modlist).  

### Loot

Now that that is out of the way, let's talk about loot.  
 - [Open World Loot](https://www.nexusmods.com/skyrimspecialedition/mods/49681) is the framework utilized by Arisen to distribute loot within the world. I have made many edits to the way in which loot is distributed.
     - All mod added armors and weapons have been integrated into the loot system in one way or another. 
         - More unique weapons and armors have been either hand placed within the world or locked behind specific quests, after which point they will become craftable (or given to the player depending on specifics).  
         - More generic armors and weapons, especially those of the steel and under categories, have been integrated into the game world as cleanly as possible to increase diversity.  
 - On top of Open World Loot, I have handplaced a significant amount of "generic" and "unique" items, similar to MorrowLoot (for those who are familiar). This does mean that it is possible to get very strong loot very early on for those with the knowledge and will to seek them out.  

When it comes to loot, boss chests are not what you should be primarily focusing on when trying to look for upgrades, the vast majority of Higher Tier items shall be found in the game world by way of hand placements or by way of quests. Unique items and Artifacts *should* be stronger than anything the player can enchant, outside of niche scenarios in which an enchanted item can be made for a very specific purpose. I have very little intention of changing the way loot is handled in the list, at least for the time being.  

## Gameplay - Aljo's Extended Cut

### Standing Stones

While checking out the [Constellations](https://www.nexusmods.com/skyrimspecialedition/mods/43763) and [Mundus](https://www.nexusmods.com/skyrimspecialedition/mods/33411) mod pages can give a fairly good idea as to what the standing stones do, here are the actual effects for when they are not well communicated in game.

#### Mage Signs

 - **The Apprentice Stone**: Magicka regenerates **100%** faster and Novice and Apprentice spells cost **50%** less Magicka. Magic Resistance is decreased by **50%**.
 - **The Atronach Stone**: All Spells cost **25%** less Magicka and you have **25%** increased Spell Absorbtion. You can not regenerate Magicka in combat. 
 - **The Mage Stone**: Magicka is increased by **50** points and spells are more effective and last longer when cast above **50%** Magicka.
 - **The Ritual Stone**: Spells cast from Scrolls and Staves are **200%** stronger. Spells cast outside of combat are **50%** stronger and last **50%** longer. Spells cast in combat require **25%** more Magicka.

#### Thief Signs

 - **The Lover Stone**: Stamina regenerates **100%** faster and you take **25%** less damage from power attacks. Take **50%** more damage from unblocked light attacks. 
 - **The Shadow Stone**: Sneaking is **25%** more effective and sneak attacks and spells cast while undetected deal **25%** more damage. When exposed to light, armor rating is decreased by **100** points. 
 - **The Thief Stone**: Stamina is increased by **50** points and attacks deal **10 to 20** less damage while Stamina is above **50%**.
 - **The Tower Stone**: Lockpicking and Pickpocketing are **25%** easier and you can detect the movement of others while sneaking and not moving. When Stamina is below **50%**, blocking is **50%** less effective.

#### Warrior Signs

 - **The Lady Stone**: Health regeneration is increased by **100%** and Armor is increased by **50** points. All attacks deal **25%** less damage.
 - **The Lord Stone**: Magic, Poison, and Disease Resistance is increased by **25%** and Power Attacks deal **25%** more damage. Power Attacks cost **50%** more stamina.
 - **The Steed Stone**: Carry Weight is increased by **100** points and Sprinting is **25%** faster. Health, Magicka, and Stamina regenerate **10%** slower.
 - **The Warrior Stone**: Health is increased by **50** points and physical attacks deal more damage while above **50%** Health.

#### Unaffiliated

 - **The Serpent Stone**: Poison Resistance is increased by **50%**, potions last **50%** longer, and poisons last for an additional hit. Reflect **10%** of melee damage.
