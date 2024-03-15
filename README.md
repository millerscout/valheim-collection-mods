<h1>Introduction</h1>
My name is DrPine.  I am uploading some mods that are only over at NexusMods so that everyone can use them in the Thunderstore Mod Manager with ease.  Below is the description from Nexus Mods.

Developed by aedenthorn

## Description

Lets you tweak what happens when you die, including item dropping and keeping, whether a tombstone is created, whether food levels are kept, whether to reduce skill levels, etc.

This mod contains the following config options:

- KeepItemTypes - a list of item types to always keep on death
- DropItemTypes - a list of item types to always drop on death
- DestroyItemTypes - a list of item types to always destroy on death
- KeepAllItems - whether to keep all items
- DestroyAllItems - whether to destroy all items
- KeepEquippedItems - whether to keep equipped items
- KeepQuickSlotItems - whether to keep items in Equipment and Quick Slots quick slots
- KeepTeleportableItems - whether to keep all items that are teleportable
- UseTombStone - whether to create a tomb stone
- CreateDeathEffects - whether to create a ragdoll
- KeepFoodLevels - whether to keep food levels on death
- ReduceSkills - whether to reduce skills on death
- SkillReduceFactor - the fraction of skill xp to lose
- NoSkillProtection - whether to force skill loss on every death
- SpawnAtStart - Whether to force respawning at start location
- UseFixedSpawnCoordinates - Whether to use custom fixed spawn coordinates

Only use either KeepItemTypes or DropItemTypes. DestroyItemTypes overrides both. KeepEquippedItems and KeepQuickSlotItems override the lists and KeepAllItems or DestroyAllItems overrides all the others.

As of version 0.3.0 it should work with Equipment and Quick Slots.

## Config

A config file **BepInEx/config/aedenthorn.DeathTweaks.cfg** is created after running the game once with this mod).

You can adjust the config values by editing this file using a text editor or in-game using the [Config Manager](https://valheim.thunderstore.io/package/Pineapple/EnhancedBepInExConfigurationManager/).

To reload the config from the config file, type **deathtweaks reset** into the game's console (F5).

## Installation

- Automated

  - Suggested to use the [R2ModMan](https://thunderstore.io/package/ebkr/r2modman/) Mod Manager

- Manual

  - Copy the DeathTweaks.dll to your /Valheim/BepInEx/plugins directory

If you want to complain or ask for help or help me test my mods, you can visit [my Discord server](https://discord.gg/bs6zHuj).

[Click here for a list of all my mods for Valheim.](https://www.nexusmods.com/valheim/articles/104)

## Source Code

[https://github.com/aedenthorn/ValheimMods](https://github.com/aedenthorn/ValheimMods)

## Change Log

v1.3.0

- fix for update

v1.2.0

- Fix for 0.217.14

v1.1.0

- Fix for new version

v1.0.0

- Added keep teleportable items

v0.11.1

- Fix for keeping hotkeybar items

v0.11.0

- Bug Fixes

v0.10.0

- Compatibility Fix

v0.9.1

- Fix for skill exp loss

v0.9.0

- Added named item lists

v0.8.1

- Removed serversync

v0.8.0

- Fix for new update

v0.7.0

- Added variable skill reduction
- Added custom spawn location

v0.6.2

- Fixed exception

v0.6.1

- Possible fix for duplicate items

v0.6.0

- Added option to destroy all items on death

v0.5.2

- Fix for collection changed

v0.5.1

- Fixed no skill protection option

v0.5.0

- Added option to keep Quick Slot items

v0.4.0

- Added skill protection toggle

v0.3.0

- Added compatibility with Equipment and Quick Slots

v0.2.0

- Added keep hotbar items option
