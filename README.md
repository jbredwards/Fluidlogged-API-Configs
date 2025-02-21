## Fluidlogged-API-Configs
By default, Fluidlogged API only adds fluidlogging to [certain types of blocks](https://github.com/jbredwards/Fluidlogged-API#fluidloggable-blocks), and requires players to manually add other blocks (like pipes) to their whitelist. In most cases, the blocks from mods that should be fluidloggable are the same regardless of who you ask, which is where this project comes in.

Fluidlogged API downloads the configurations from this project and applies them in-game (this functionality can be disabled via `fluidlogged_api/general.cfg` if desired). If there are any blocks here that you don't wish to be fluidloggable, you can either disable the community configs or remove the blocks by blacklisting them in your `fluidlogged_api/blacklist.cfg` file! It should be noted that all configurations in this project are designed to work with Fluidlogged API v3.0.0 or later, and might not work with previous versions of Fluidlogged API. If you would like to see more community configs, more supported mods, or would like to contribute your own configs for other people to use, create an issue or pull request!

---

**Mods that still offer 1.12.2 support are not supported by this project, and should instead look into adding their own Fluidlogged API support**. This is because maintained mods might add/change/remove blocks at any given time, which poses a number of problems:
- High risk of breaking community configs between updates.
- Players having to wait for the community configs to be fixed for the latest version of the maintained mod.
- Players unknowningly using a previous version of the maintained mod, thus having potentially broken configs that only support the latest version.
- This project is looking to support hundereds (maybe even thousands) of mods. Allowing support for mods that are still maintained would mean that lots of time would be put into monitoring potentially hundereds or thousands of mods for updates, and keeping their respective community configs up-to-date. This is time that I simply don't have.

---

| Supported Mods | Downloads |
| --- | --- |
| [/dank/null/](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/danknull)  | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/dank-null/files/2962052) ⏐ |
| [/dank/null/no_RCE/](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/danknull) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/dank-null-no_rce/files/all?version=1.12.2) ⏐ [Modrinth](https://modrinth.com/mod/danknull-rce/versions?g=1.12.2) |
| [Actually Additions](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/actuallyadditions) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/actually-additions/files/3117927) ⏐ |
| [Additional Lanterns](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/additionallanterns) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/additional-lanterns/files/4729425) ⏐ [Modrinth](https://modrinth.com/mod/additional-lanterns/version/1.1.1b-forge-mc1.12) |
| [Additional Lights](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/additional_lights) | [CurseForge](https://curseforge.com/minecraft/mc-mods/additional-lights/files/2989463) ⏐ |
| [Advanced Rocketry](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/advancedrocketry) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/advanced-rocketry/files/4671856) ⏐ |
| [Advanced Rocketry - Reworked](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/advancedrocketry) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/advanced-rocketry-2/files/all?version=1.12.2) ⏐ [Modrinth](https://modrinth.com/mod/advanced-rocketry-reworked/versions?g=1.12.2) |
| [Advent of Ascension](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/aoa3) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/advent-of-ascension-nevermine/files/3054253) ⏐ [Modrinth](https://modrinth.com/mod/adventofascension/version/1.12.2-3.3.6) |
| [AE2](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/appliedenergistics2) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/applied-energistics-2/files/2747063) ⏐ |
| [AE2 Unofficial Extended Life](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/appliedenergistics2) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ae2-extended-life/files/all?version=1.12.2) ⏐ |
| [Aether](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/aether_legacy) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/aether/files/5035622) ⏐ [Modrinth](https://modrinth.com/mod/aether/version/1.12.2-v1.5.4.0) |
| [Aether Continuation](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/aether_legacy_addon) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/aether-addon/files/3070803) ⏐ |
| [Aether II: Phosphor Not Included](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/aether) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/the-aether-ii-phosphor-not-included/files/4771846) ⏐ |
| [AgriCraft](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/agricraft) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/agricraft/files/3317747) ⏐ |
| [Alternating Flux](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/alternatingflux) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/alternating-flux/files/2693578) ⏐ |
| [Apotheosis](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/apotheosis) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/apotheosis/files/2906487) ⏐ |
| [ArchitectureCraft - TridentMC Version](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/architecturecraft) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/architecturecraft-tridev/files/4344128) ⏐ [Modrinth](https://modrinth.com/mod/architecture-craft/version/1.12-3.108) |
| [ArmorPlus](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/armorplus) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/armorplus/files/2952741) ⏐ |
| [Artisan Worktables 1.12](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/artisanworktables) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/artisan-worktables/files/3205284) ⏐ |
| [Astral Sorcery](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/astralsorcery) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/astral-sorcery/files/3044416) ⏐ |
| [Atum 2: Return to the Sands](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/atum) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/atum/files/3116599) ⏐ |
| [Avaritiaddons](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/avaritiaddons) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/avaritiaddons/files/4745387) ⏐ |
| [Better Displays](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/betterdisplays) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/better-displays/files/4284175) ⏐ |
| [BetterNether](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/betternether) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/betternether/files/2859893) ⏐ |
| [BetterNether: RotN Edition](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/betternether) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/betternether-rotn-edition/files/all?version=1.12.2) ⏐ |
| [BetterNether Continuation](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/betternether) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/better-nether-continuation/files/all?version=1.12.2) ⏐ [Modrinth](https://modrinth.com/mod/betternether-continuation/versions?g=1.12.2) |
| [Bewitchment (Legacy)](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/bewitchment) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/bewitchment-legacy/files/3256343) ⏐ |
| [Beyond The Veil](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/beyondtheveil) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/beyond-the-veil/files/3616140) ⏐ |
| [BiblioCraft](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/bibliocraft) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/bibliocraft/files/3647708) ⏐ |
| [Blockcraftery](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/blockcraftery) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/blockcraftery/files/2716712) ⏐ |
| [Blood Magic](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/bloodmagic) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/blood-magic/files/2822288) ⏐ [Modrinth](https://modrinth.com/mod/blood-magic/version/1.12.2-2.4.3-105) |
| [Botania](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/botania) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/botania/files/3330934) ⏐ [Modrinth](https://modrinth.com/mod/botania/version/1.10-364.4-forge) |
| [BuildCraft](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/buildcraft/files/3204475) ⏐ [Modrinth](https://modrinth.com/mod/buildcraft/version/7.99.24.8) |
| [BuildCraft Builders](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/buildcraftbuilders) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/buildcraft-builders/files/3204465) ⏐ [Modrinth](https://modrinth.com/mod/buildcraft-builders/version/7.99.24.8) |
| [BuildCraft Core](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/buildcraftcore) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/buildcraft-core/files/3204464) ⏐ [Modrinth](https://modrinth.com/mod/buildcraft-core/version/7.99.24.8) |
| [BuildCraft Energy](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/buildcraftcore) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/buildcraft-energy/files/3204466) ⏐ [Modrinth](https://modrinth.com/mod/buildcraft-energy/version/7.99.24.8) |
| [BuildCraft Factory](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/buildcraftfactory) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/buildcraft-factory/files/3204467) ⏐ [Modrinth](https://modrinth.com/mod/buildcraft-factory/version/7.99.24.8) |
| [BuildCraft Silicon](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/buildcraftsilicon) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/buildcraft-silicon/files/3204468) ⏐ [Modrinth](https://modrinth.com/mod/buildcraft-silicon/version/7.99.24.8) |
| [BuildCraft Transport](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/buildcrafttransport) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/buildcraft-transport/files/3204469) ⏐ [Modrinth](https://modrinth.com/mod/buildcraft-transport/version/7.99.24.8) |
| [CC: Tweaked](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/computercraft) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/cc-tweaked/files/all?version=1.12.2) ⏐ |
| [Charm](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/charm) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/charm/files/3146596) ⏐ |
| [Chicken Chunks](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/chickenchunks) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/chicken-chunks-1-8/files/2755785) ⏐ [Modrinth](https://modrinth.com/mod/chicken-chunks/version/2.4.2.74) |
| [Chisels & Bits](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/chiselsandbits) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/chisels-bits/files/2720655) ⏐ |
| [Chunk Loaders](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/chunkloaders) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/chunk-loaders/files/5723240) ⏐ [Modrinth](https://modrinth.com/mod/chunk-loaders/version/1.2.8b-forge-mc1.12) |
| [CompactStorage](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/compactstorage) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/compactstorage/files/2572444) ⏐ |
| [ComputerCraft](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/computercraft) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/computercraft/files/2478952) ⏐ |
| [Construct's Armory](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/conarm) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/constructs-armory/files/3174535) ⏐ [Modrinth](https://modrinth.com/mod/constructs-armory/version/1.12.2-1.2.5.10) |
| [Cooking for Blockheads](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/cookingforblockheads) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/cooking-for-blockheads/files/2862651) ⏐ |
| [Custom NPCs](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/customnpcs) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/custom-npcs/files/2996912) ⏐ |
| [Cyclic](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/cyclicmagic) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/cyclic/files/4075832) ⏐ [Modrinth](https://modrinth.com/mod/cyclic/version/1.12.2-1.20.14) |
| [Dark Utilities](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/darkutils) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/dark-utilities/files/2813586) ⏐ [Modrinth](https://modrinth.com/mod/dark-utilities/version/1.8.230) |
| [Decorative Ladders](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/ahmed4363laddersmod) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/decorative-ladders/files/2978098) ⏐ |
| [Delightful Cuisine for Woodheads](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/cookingforblockheads) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/delightful-cuisine-for-woodheads/files/4326433) ⏐ |
| [Disenchanter](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/disenchanter) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/the-disenchanter-mod/files/3519704) ⏐ |
| [Draconic Evolution](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/draconicevolution) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/draconic-evolution/files/3431261) ⏐ [Modrinth](https://modrinth.com/mod/draconic-evolution/version/2.3.28.354) |
| [Embers' Construct](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/embersconstruct) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/embersconstruct/files/3735109) ⏐ [Modrinth](https://modrinth.com/mod/embersconstruct/version/1.3.5) |
| [Ender IO](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/enderio) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ender-io/files/4674244) ⏐ [Modrinth](https://modrinth.com/mod/enderio/version/5.3.72) |
| [Ender-Rift](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/enderrift) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ender-rift/files/2983035) ⏐ |
| [Ender Storage](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/enderstorage) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ender-storage-1-8/files/2755787) ⏐ [Modrinth](https://modrinth.com/mod/ender-storage/version/2.4.6.137) |
| [EnderTanks](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/endertanks) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/endertanks/files/2664673) ⏐ |
| [Endorium (End Reborn)](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/endreborn) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/end-reborn/files/3006659) ⏐ |
| [Engineer's Decor](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/engineersdecor) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/engineers-decor/files/3783239) ⏐ |
| [Environmental Tech](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/environmentaltech) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/environmental-tech/files/2691536) ⏐ [Modrinth](https://modrinth.com/mod/environmental-tech/version/1.12.2-2.0.20.1) |
| [Extended Crafting](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/extendedcrafting) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/extended-crafting/files/2777071) ⏐ [Modrinth](https://modrinth.com/mod/extended-crafting/version/1.5.6) |
| [Extended Crafting: Nomifactory Edition](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/extendedcrafting) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/extended-crafting-nomifactory-edition/files/all?page=1&pageSize=20) ⏐ |
| [ExtraPlanets](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/extraplanets) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/extraplanets/files/5339029) ⏐ [Modrinth](https://modrinth.com/mod/extraplanets/version/0.8.0) |
| [Extra Utilities](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/extrautils2) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/extra-utilities/files/2678374) ⏐ |
| [Fairy Lights](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/fairylights) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/fairy-lights/files/3068499) ⏐ |
| [Fancy Lamps](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/fancylamps) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/fancy-lamps/files/2863411) ⏐ |
| [Flopper](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/flopper) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/flopper/files/2689287) ⏐ |
| [Flux Networks](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/fluxnetworks) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/flux-networks/files/3178199) ⏐ |
| [Forestry](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/forestry) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/forestry/files/6104316) ⏐ |
| [Galacticraft Core](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/galacticraftcore) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/galacticraft-legacy/files/4671122) ⏐ [Modrinth](https://modrinth.com/mod/galacticraft-legacy/version/4.0.6) |
| [Galacticraft Planets](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/galacticraftplanets) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/galacticraft-legacy/files/4671122) ⏐ [Modrinth](https://modrinth.com/mod/galacticraft-legacy/version/4.0.6) |
| [Growthcraft Apples](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/grothcraft_apples) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/growthcraft-community-edition/files/5172498) ⏐ |
| [Growthcraft Bamboo](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/grothcraft_bamboo) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/growthcraft-community-edition/files/5172498) ⏐ |
| [Hopper Ducts](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/hopperducts) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/hopper-ducts/files/2454832) ⏐ |
| [Horizontal Glass Panes](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/hgp) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/horizontal-glass-panes/files/2536711) ⏐ |
| [Ice And Fire](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/iceandfire) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ice-and-fire-dragons/files/2939529) ⏐ [Modrinth](https://modrinth.com/mod/ice-and-fire-dragons/version/1.9.1) |
| [IGauntlet](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/igauntlet) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/igauntlet/files/2792298) ⏐ |
| [Industrial Craft](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/ic2) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/industrial-craft/files/3838713) ⏐ |
| [Large Fluid Tank](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/fluidtank) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/largefluidtank/files/3366145) ⏐ |
| [Survivalist](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/survivalist) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/survivalist/files/2625075) ⏐ |
| [Telepad](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/danknull) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/telepad/files/2773932) ⏐ |
| [The Betweenlands](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/thebetweenlands) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/angry-pixel-the-betweenlands-mod/files/4479688) ⏐ |
| [The Erebus](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/erebus) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/the-erebus/files/3211974) ⏐ |
| [The Weirding Gadget](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/weirdinggadget) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/the-weirding-gadget/files/2708729) ⏐ |
| [Varied Commodities](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/variedcommodities) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/varied-commodities/files/4466956) ⏐ |
| [World Plus](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/worldplus) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/world-plus/files/2692400) ⏐ |
| [XPTeleporters 2](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/danknull) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/xpteleporters-2/files/2827714) ⏐ |
