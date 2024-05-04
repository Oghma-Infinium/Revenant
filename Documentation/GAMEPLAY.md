![](https://raw.githubusercontent.com/Oghma-Infinium/Revenant/main/images/banner.png)
<p align="center">
  [ <a href="https://www.nexusmods.com/skyrimspecialedition/mods/95364">Nexus</a> |
  <a href="https://github.com/Oghma-Infinium/Revenant/blob/main/README.md">Installation</a> |
  <a href="https://github.com/Oghma-Infinium/Revenant/blob/main/Documentation/GAMEPLAY.md">Gameplay Guide<a/> |
  <a href="https://github.com/Oghma-Infinium/Revenant/blob/main/CHANGELOG.md">Changelog</a> |
  <a href="https://github.com/Oghma-Infinium/Revenant/blob/main/Documentation/FAQ.md">FAQ</a> |
  <a href="https://github.com/Oghma-Infinium/Revenant/blob/main/Documentation/CONFIG.md">Config</a> |
  <a href="https://loadorderlibrary.com/lists/Revenant">Modlist</a> ]
</p>

---

## Initial Setup

Before reading this guide, please follow the [readme](https://github.com/Oghma-Infinium/Revenant/blob/main/README.md) as it will answer the vast majority of technical questions related to getting the list setup and running. Be sure to check out the [configuration](https://github.com/Oghma-Infinium/Revenant/blob/main/Documentation/CONFIG.md) page to learn more about the optional tweaks and addons and MCM options.

## Basics

This section will cover the absolute basics of the list. I suggest reading, or skimming all of the linked mod pages in this section if you are unfamiliar with the preceding mods.

Before reading this section, I suggest looking over the [keybinds](https://github.com/Oghma-Infinium/Revenant/blob/main/images/keyboard-layout_Revenant.jpg) or [gamepad binds](https://github.com/Oghma-Infinium/Revenant/blob/main/images/controlmap3.png) (partially outdated) and [load order](https://loadorderlibrary.com/lists/Revenant).

## Core Mods

- [Requiem](https://www.nexusmods.com/skyrimspecialedition/mods/60888) and [3Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/44044) define the entire gameplay of the list

   > It is highly recommended to read [3Tweaks documentation](https://sites.google.com/view/3bftweaksrequiem/home) is it explains many of the core gameplay systems.

    > However, the Insight potion leveling system **IS NOT USED** in revenant. Leveling is handled by [Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751) and [Static Skill Leveling](https://www.nexusmods.com/skyrimspecialedition/mods/89940)

- [Starfrost](https://www.nexusmods.com/skyrimspecialedition/mods/97536) handles the survival mechancis, complemented by [Campsite](https://www.nexusmods.com/skyrimspecialedition/mods/22353) and [Simple Hunting Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/95943)

## Saving practices and you

Bad saving practices can quickly corrupt your save with a modlist this large. For this reason we highly recommend to follow good practices for keeping your save health:

- **Do not** "save scum" by saving and reloading frequently, typically more often than every five minutes. If you want to know why this is bad, please check out this [post](https://old.reddit.com/r/skyrimmods/comments/116raxm/psa_engine_bug_when_reloading_saves/).
  - Currently we're stress-testing the list's save robustness. For now you can do "save scumming" for experimentation sake, but regardless your save might get corrupted.
- **Do not** play the game at a lower framerate than 30 fps, if this is a problem for you regularly, consider another list.
- **Avoid** saving the game when in a combat state, moving at high speeds, or transitioning through cells (using doors). Other examples of when to avoid saving include active dialogue, crafting, TFC-mode screenshots, or animations.
- Trust the [Skyrim SafeSave System Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/70179) to handle your saves.
  > The mod automatically saves every 5 minutes, but it waits until the game state is safe for saving.

  > You can also manually request save with F5. If the save doesn't happen immediately it means the game state is not safe for saving.
- Do not enable autosaves. They can often save the game at troublesome moments like the above.  
  > Autosaves created by Skyrim SafeSave System Overhaul, are safe and can be trusted
- Do not load saves when caught doing crimes. The list has alternative mechanics to evade bounties.



### Leveling and Progression

Revenant uses [Static Skill Leveling](https://www.nexusmods.com/skyrimspecialedition/mods/30410) for leveling skills. I have configured it with my custom settings:
- Gain skill points equal to 4 + 0.5 * level for each level up, which caps at 30 points at level 50.
- You can only store maximum of 30 per level, therefore **after level 50 you must spend all your skills points at level up or you will waste some points.**
  > Skill costs are as follows:
  > - 0 to 50: 1
  > - 51 to 75: 2
  > - 76 to 100: 3

- You gain experience from:
  - Completing quests
  - Clearing locations
  - Defeating enemies
  - Successful lockpicking
  - Successful pickpocketing

- You start with three (3) perk points.
  > These are given to you after you have activated Requiem from the prompt that appears on-screen shortly after opening the inventory for the first time.
- You gain one (1) perk point from level up.

### Combat


- [MCO - Modern Combat Overhaul](https://modding-guild.com/mod/attack-mcodxp/) is the core mod for melee combat. It overhauls melee attacks to use attack commitment and combo chaining, similar to other modern action games like Elden Ring and Assassin's Creed Valhalla.

- Ash of War, a special attack for all weapon types is available in powers menu.

  > Requires the perk Ash of War from Dexterity tree to unlock.

  > Some unique artifacts have unique Ash of War. These will be expanded in the future as I update the list.

- [Maxsu Poise](https://github.com/max-su-2019/MaxsuPoise/releases) is the stagger system in the list, with my custom tweaks:
  > Light attacks and ranged attacks inflict a very short small stagger on poise break.
  > Heavy attacks inflict longer large stagger on poise break.
  > Some Ash of War attacks inflict special staggers like knockback.

- [Oblivion-like Spell Casting](https://www.nexusmods.com/skyrimspecialedition/mods/65398) allows you to caste spells without equiping them on your hands. Read up the mod page for more info.
  > This mod is a little jank sometimes. Don't try to spam spells too quickly or it will get "stuck" and you'll have wait few seconds for it to work again.

### Crime

- [Crime Bounty Decay SE](https://www.nexusmods.com/skyrimspecialedition/mods/25457) makes bounties slowly decay by default. You can speed that up with some perks.  
- [Book of Shadows](https://www.nexusmods.com/skyrimspecialedition/mods/76086) adds a mask mechanic for evading bounties. When wearing a mask, the bounty accumulates for the mask only. When not wearing the mask, your bounty is not recognized by guards.  
  > You can craft a mask at tanning rack.

### Perk Tweaks

- Most combat trees are overhauled from base 3Tweaks to fit action combat.
  - It is highly recommended to take the first perk in block tree or evasion tree to have realistic chance of defending yourself in melee combat.

## New Content

### Vanilla Quest Changes

- [End Times](https://www.nexusmods.com/skyrimspecialedition/mods/39201) gives the player 365 days to save the world before Alduin consumes it.

  > 365 days is way longer than some would expect, you're not in particular hurry to complete the main quest

- First few quests of the main story are skipped. The main quest starts With Way of the Voice after you kill your first dragon. Dragon Rising quest doesn't exist
  - Dragons start spawning at word walls after level 2 and rest of the world after level 20.
- Rest of the main quest after Way of the Voice is handled by [At Your Own Pace](https://www.nexusmods.com/skyrimspecialedition/mods/52704)
- [At Your Own Pace](https://www.nexusmods.com/skyrimspecialedition/mods/52704) is also used for Companions, College of Winterhold, Dawnguard and Dragonborn questlines.

  > You **absolutely should** read this modpage as that will save you from a lot of confusion with several questlines.

- [The Choice is Yours](https://www.nexusmods.com/skyrimspecialedition/mods/3850) gives you the freedom to reject quests you may not want to take at the time.
- [Penitus Oculatus](https://www.nexusmods.com/skyrimspecialedition/mods/21061) and [Destroy the Thieves Guild](https://www.nexusmods.com/skyrimspecialedition/mods/43244) add ways to obtain unique rewards from Dark Brotherhood and Thieves Guild questlines without joining the factions.

### Other Vanilla Quest Expansions

- [Bring Meeko To Lod](https://www.nexusmods.com/skyrimspecialedition/mods/25246)
- [Search and Seizure - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/67066)
- [College of Winterhold - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/66666)
- [Caught Red Handed - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/65708)
- [The Heart of Dibella - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/94863)
- [Deceive Degaine](https://www.nexusmods.com/skyrimspecialedition/mods/51863)
- [The Only Cure - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/57683)
- [The Whispering Door - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/76606)
- [Paarthurnax - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/51711)
- [House of Horrors - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/57285)
- [Nilheim - Misc Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/53792)
- [Boethiah for Good Guys](https://www.nexusmods.com/skyrimspecialedition/mods/329)
- [Defeat the Dragon Cult](https://www.nexusmods.com/skyrimspecialedition/mods/86625)
- [Innocence Lost - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/80974)
- [ACDB - Additional Contracts for the Dark Brotherhood](https://www.nexusmods.com/skyrimspecialedition/mods/59211)
- [Unmasking Sybille](https://www.nexusmods.com/skyrimspecialedition/mods/109265)
- [Blood on the Ice Redux SE](https://www.nexusmods.com/skyrimspecialedition/mods/6126)
- [Save the Icerunner - Lights Out Alternate Routes](https://www.nexusmods.com/skyrimspecialedition/mods/34681)
- [Get both rewards from Clavicus Vile's quest](https://www.nexusmods.com/skyrimspecialedition/mods/43574)

### New Lands

- Vicn Trilogy:
  - [Vigilant](https://www.nexusmods.com/skyrimspecialedition/mods/11849) requires completion of [Kindred Judgment](https://en.uesp.net/wiki/Skyrim:Kindred_Judgment) (Dawnguard DLC main story) and [House of Horrors](https://en.uesp.net/wiki/Skyrim:The_House_of_Horrors)
  - [Glenmoril](https://www.nexusmods.com/skyrimspecialedition/mods/32998) requires completion of [At the Summit of Apocrypha](https://en.uesp.net/wiki/Skyrim:At_the_Summit_of_Apocrypha) (Dragonborn DLC main story) and [Discerning the Transmundane](https://en.uesp.net/wiki/Skyrim:Discerning_the_Transmundane)
    - This quest mod is not finished yet. Play at your own discretion.
  - [Unslaad](https://www.nexusmods.com/skyrimspecialedition/mods/11789) requires completion of [Dragonslayer](https://en.uesp.net/wiki/Skyrim:Dragonslayer) (main quest)
- [Skyrim Extended Cut - Saints and Seducers](https://www.nexusmods.com/skyrimspecialedition/mods/72772)
- [Wyrmstooth](https://www.nexusmods.com/skyrimspecialedition/mods/45565)
- [Clockwork](https://www.nexusmods.com/skyrimspecialedition/mods/4155)

### New Quests

- [SIRENROOT - Deluge of Deceit](https://www.nexusmods.com/skyrimspecialedition/mods/70917)
- [Meridia's Order](https://www.nexusmods.com/skyrimspecialedition/mods/102584)
- [The Welkynar Knight](https://www.nexusmods.com/skyrimspecialedition/mods/89510)
- [Leaps of Faith](https://www.nexusmods.com/skyrimspecialedition/mods/53074)
- [Skyrim on Skooma](https://www.nexusmods.com/skyrimspecialedition/mods/80975)
- [Belethor's Sister](https://www.nexusmods.com/skyrimspecialedition/mods/92381)

### New Dungeons

- [EasierRider's Dungeon Pack](https://www.nexusmods.com/skyrimspecialedition/mods/2218)
- [Taarengrav Barrow](https://www.nexusmods.com/skyrimspecialedition/mods/84371)
- [Morthal Barrow](https://www.nexusmods.com/skyrimspecialedition/mods/90737)


## Tips and Help

