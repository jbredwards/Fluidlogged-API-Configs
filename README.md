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
| [Aether II: Phosphor Not Included](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/aether) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/the-aether-ii-phosphor-not-included/files/4771846) ⏐ |
| [AgriCraft](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/agricraft) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/agricraft/files/3317747) ⏐ |
| [Alternating Flux](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/alternatingflux) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/alternating-flux/files/2693578) ⏐ |
| [Apotheosis](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/apotheosis) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/apotheosis/files/2906487) ⏐ |
| [ArchitectureCraft - TridentMC Version](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/architecturecraft) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/architecturecraft-tridev/files/4344128) ⏐ [Modrinth](https://modrinth.com/mod/architecture-craft/version/1.12-3.108) |
| [ArmorPlus](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/armorplus) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/armorplus/files/2952741) ⏐ |
| [Artisan Worktables 1.12](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/artisanworktables) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/artisan-worktables/files/3205284) ⏐ |
| [Astral Sorcery](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/astralsourcery) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/astral-sorcery/files/3044416) ⏐ |
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
| [Decorative Ladders](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/ahmed4363laddersmod) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/decorative-ladders/files/2978098) ⏐ |
| [Embers' Construct](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/embersconstruct) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/embersconstruct/files/3735109) ⏐ [Modrinth](https://modrinth.com/mod/embersconstruct/version/1.3.5) |
| [IGauntlet](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/igauntlet) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/igauntlet/files/2792298) ⏐ |
| [Telepad](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/danknull) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/telepad/files/2773932) ⏐ |
| [The Betweenlands](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/thebetweenlands) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/angry-pixel-the-betweenlands-mod/files/4479688) ⏐ |
| [The Weirding Gadget](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/weirdinggadget) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/the-weirding-gadget/files/2708729) ⏐ |
| [World Plus](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/worldplus) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/world-plus/files/2692400) ⏐ |
| [XPTeleporters 2](https://github.com/jbredwards/Fluidlogged-API-Configs/tree/1.12.2/internal/danknull) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/xpteleporters-2/files/2827714) ⏐ |
