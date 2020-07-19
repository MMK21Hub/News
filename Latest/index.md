# 2020 week 29

 - Optifabric [will no longer continue to be updated](https://gist.github.com/modmuss50/deff1658c4550ca8b16cb5d40ceaa468).
 - Multi-language wikis (Commons, etc) use the [Translate](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Extension:Translate) extention. Missing translations will soon be highlighted, similar to how Outdated translations are highlighted pink.
   - 🔧<sup>1</sup> This highlighting [will soon be able to be disabled](https://phabricator.wikimedia.org/T256625) using a tag like `<translate nowrap>`.
 - 🔧<sup>3</sup> Wikimedia [will be moving](https://lists.wikimedia.org/pipermail/wikitech-l/2020-July/093577.html) onto GitLab instead of Gerrit for code review. See the linked email for more infomation.
 - The 'first step in cutting the release branch' for the MediaWiki 1.35 release happened on Monday. The focus is now on bugfixes: any new features will be targeted at 1.36. MediaWiki 1.35 is expected to land 'at the beginning of August'. [More infomation can be found in this email.](https://lists.wikimedia.org/pipermail/mediawiki-announce/2020-June/000250.html)
 - The Minecraft 1.12 panorama seed has sbeen found! Seed: `2151901553968352745`/`8091867987493326313` (both work) Coordinates: `61 75 68` (XYZ) Version: Beta 1.7.3 (or earlier). The [Minecraft@Home](https://minecraftathome.com/) team reverse-engineered it, and it was announced on [Reddit](https://www.reddit.com/r/minecraftseeds/comments/hthuu4/big_news_we_have_found_the_seed_of_minecrafts/) and the [LTT Forums](https://linustechtips.com/main/topic/1223925-minecrafthome-have-found-the-seed-of-minecrafts-title-screen-background-panorama/). [SalC1](https://www.youtube.com/channel/UClY084mbGLK_SLlOfgizjow) will upload a video about it soon.

## Releases
 - [**Conflict in Harmony**](https://curseforge.com/minecraft/mc-mods/conflict-in-harmony) has released. It allows you to bind multiple actions to one key.
 - [**Fabulously Optimized**](https://www.curseforge.com/minecraft/modpacks/fabulously-optimized) has released. It's a fabric modpack perfect for switching over from Optifine. It includes:
   -   [Sodium](https://www.curseforge.com/minecraft/mc-mods/sodium) - optimizes general rendering to improve FPS, adds some graphics options (configurable)
   -   [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) - optimizes chunk loading
   -   [Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor) - optimizes light rendering
   -   [LambDynamicLights](https://www.curseforge.com/minecraft/mc-mods/lambdynamiclights) - lets you light up the area by holding a torch and more (configurable)
   -   [Ok Zoomer](https://www.curseforge.com/minecraft/mc-mods/ok-zoomer) - the zoom feature, as you'd expect (configurable)
   -   [motioNO](https://www.curseforge.com/minecraft/mc-mods/motiono) - adds an option to disable dynamic FOV (disabled by default)
   -   [Jumploader](https://www.curseforge.com/minecraft/mc-mods/jumploader) - to make this modpack available on this site
   -   [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) - makes most mods work
   -   [Mod Menu](https://www.curseforge.com/minecraft/mc-mods/modmenu) - gives you the list of mods and lets you adjust their configuration
   -   [Better Mod Button](https://www.curseforge.com/minecraft/mc-mods/better-mod-button) - puts the "mods" button where you'd expect
   -   [Not Enough Crashes](https://www.curseforge.com/minecraft/mc-mods/not-enough-crashes) - lets you play after a crash and report it comfortably
   - And more mods planned!
   - *Hang on, that's all the mods that I use!*
 - [**Topaz HUD**](https://www.planetminecraft.com/data-pack/topaz-hud-v1-0/) has released. It adds a custom actionbar HUD displaying Health, Saturation. Elytra Durability, Coordinates and In-Game Time.

## Updates 
 - [**MediaWiki** 1.35.0-wmf.41](https://www.mediawiki.org/wiki/MediaWiki_1.35/wmf.41) is being rolled out this week: [Phabricator task](https://phabricator.wikimedia.org/T256669) • [Roadmap](https://www.mediawiki.org/wiki/MediaWiki_1.35/Roadmap#41) • [Current status](https://versions.toolforge.org/) • [Git](https://phabricator.wikimedia.org/source/mediawiki/history/wmf%252F1.35.0-wmf.41) • [Notes](https://phabricator.wikimedia.org/project/view/4807/) • [Commits](https://phabricator.wikimedia.org/source/mediawiki/compare/?head=wmf%2F1.35.0-wmf.41&against=master)
    - Group 0 is scheduled for Tuesday. Its [time slot](https://wikitech.wikimedia.org/wiki/Deployments#deploycal-item-20200714T1300  ) was 2:00pm to 4:00pm BST. It was pushed early, around 1pm.
    - Group 1 is scheduled for Wednesday. Its [time slot](https://wikitech.wikimedia.org/wiki/Deployments#deploycal-item-20200715T1300) was 2:00pm to 4:00pm BST. It was pushed at 2:04pm.
    - Group 2 is scheduled for Thursday. Its [time slot](https://wikitech.wikimedia.org/wiki/Deployments#deploycal-item-20200716T1300 ) was 2:00pm to 4:00pm BST.
 - **Minecraft** 20w29a has released.<!--[I need a proper template for snapshots]-->
 - [**Blockbench** v3.6](https://github.com/JannisX11/blockbench/releases/tag/v3.6.0), AKA The Streamer Update, has released. It includes Streamer Mode, thumbnails, layered textures, code signing... And plenty more!
 - [**Essentials for Fabric**](https://github.com/NyliumMC/Essentials) [v0.2.2](https://www.curseforge.com/minecraft/mc-mods/fabric-essentials/files/3003143) has released. It includes `/enderchest` and a claims API.
 - **Essentials for Fabric** [v0.2.3](https://www.curseforge.com/minecraft/mc-mods/fabric-essentials/files/3003771) has released. It includes `/trash` and a QoL tweak for the `teleport` module.
 - [**Roughly Enough Items**](https://github.com/shedaniel/RoughlyEnoughItems) [v4.9](https://www.curseforge.com/minecraft/mc-mods/roughly-enough-items/files/3003840) has released. It improves searching performance, along with a few other tweaks.
 - [**ChainsLink**](https://www.curseforge.com/minecraft/mc-mods/chains-link) [v1.1](https://www.curseforge.com/minecraft/mc-mods/chains-link/files/3004397) has released. It doesn't crash on startup now!
 - [**Don't Drop It!**](https://github.com/Leo40Git/DontDropIt) [v1.1](https://www.curseforge.com/minecraft/mc-mods/dont-drop-it/files/3004514) has released. Rebindable keys, ModUpdater support, and fulfilled requests!
 - **Don't Drop It!** [v1.2](https://github.com/Leo40Git/DontDropIt/releases/tag/v1.2.0%2B1.16      ) has released. [Conflict in Harmony](https://github.com/Leo40Git/ConflictInHarmony) is now included out-of-the-box.
 - [**ModMenu**](https://github.com/Prospector/ModMenu) [v1.14.2](https://www.curseforge.com/minecraft/mc-mods/modmenu/files/3006339) has released. It fixes [the bug that I reported](https://github.com/Prospector/ModMenu/issues/119).
 - **ModMenu** [v1.14.5](https://www.curseforge.com/minecraft/mc-mods/modmenu/files/3006672) has released. It fixes crashes.
 - [**LambDynamicLights**](https://github.com/LambdAurora/LambDynamicLights) [v1.2.2](https://discordapp.com/channels/507304429255393322/507982666755473427/733331014037930025) has released. The 'Dynamic Lights' buttton in Video Options now redirects to LambDynamicLights' config.
 - [**TinyMod**](https://github.com/Ficklampan/TinyMod) [v0.0.2](https://github.com/Ficklampan/TinyMod/releases/tag/0.0.2) has released. It improves the UI and polishes some stuff.
 - [**ReAuth**](https://github.com/TechnicianLP/ReAuth) [v3.9](https://www.curseforge.com/minecraft/mc-mods/reauth/files/3007486) has released. It includes a new 'Login and Retry' button on the error screen.
 - [**Conflict in Harmony**](https://curseforge.com/minecraft/mc-mods/conflict-in-harmony) [v1.0.1](https://www.curseforge.com/minecraft/mc-mods/conflict-in-harmony/files/3008090) has released. It fixes compatability with Fabric API.
 - [**Don't Drop It!**](https://github.com/Leo40Git/DontDropIt) [v1.2.1](https://www.curseforge.com/minecraft/mc-mods/dont-drop-it/files/3008093) has released. Conflict In Harmony was updated to v1.0.1.
 - [**Topaz HUD**](https://www.planetminecraft.com/data-pack/topaz-hud-v1-0/) v1.1 has released. It removes Health, adds more info to Elytra Durability, and improves proformance.
 - [**LambadaControls**](https://github.com/LambdAurora/LambdaControls) [v1.4](https://www.curseforge.com/minecraft/mc-mods/lambdacontrols/files/3008323) has released. It includes anologue controls and better compatability.
 - **LambadaControls** [v1.4.1](https://www.curseforge.com/minecraft/mc-mods/lambdacontrols/files/3008555) has released. It fixes a crash.

## Past events
 - 🔄 The official Terraria weekly stream is every Friday at 9pm BST, on [Twitch](https://www.twitch.tv/terrariaofficial).
 - 🔄 The [Terraria Community Team](https://discord.gg/chpcEC2) meeting is every Saturday at 8pm BST.

 ## Upcoming events
 - 🔄 The Terraria Event forecast releases every Sunday, too late to cover here. You can find it in #activities-announcement at the [Official Terraria Discord Server](http://discord.gg/terraria).
