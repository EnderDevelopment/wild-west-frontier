# Wild West Adventure Modpack Research

**Target:** Minecraft Java 1.20.1, Forge. **Prepared:** 2025-09-15.

## Verification status

CurseForge live search and page reading were unavailable while preparing this guide. I cannot honestly claim live verification of exact file versions, dependency versions, or multiplayer tests. Every linked project below is a real project page to check, not proof that it currently has a 1.20.1 Forge file. Select only files explicitly tagged **Minecraft 1.20.1 + Forge**, then install the dependencies listed on those files. Omit any project without a matching file.

A true RDR2-style total conversion is not available for this target. No confirmed combination here provides AAA breed-specific horse animation, autonomous armed outlaw factions, scripted train/bank robberies, law/wanted simulation, and a full campaign out of the box. The guide distinguishes actual systems from authored/configured approximations; it does not promise unsupported features.

**Side labels:** Client = each player; Server = dedicated server; Both = install on client and server for multiplayer. These are typical scopes and must be checked against each selected file's instructions.

## Ranked picks

1. **Horse and cart: [AstikorCarts Redux](https://www.curseforge.com/minecraft/mc-mods/astikorcarts-redux)** — the most relevant cart candidate here; not an RDR-quality wagon or horse overhaul. Verify file and dependencies. Both.
2. **Player animation: [Not Enough Animations](https://www.curseforge.com/minecraft/mc-mods/not-enough-animations)** — makes player actions visible in third person; does not animate NPCs. Client.
3. **Combat: [Timeless and Classics Zero (TaCZ)](https://www.curseforge.com/minecraft/mc-mods/timeless-and-classics-zero)** — firearm handling/reloading candidate; weapon selection depends on matching content packs. Verify Forge file and libraries. Both.
4. **NPC authoring: [Easy NPC](https://www.curseforge.com/minecraft/mc-mods/easy-npc)** — placeable/configurable NPCs for authored encounters; not autonomous gang AI. Verify 1.20.1 Forge file. Both.

## Curated candidate list (47 projects)

All entries are candidates pending the version/loader check above. A candidate list is not a recommendation to install every item.

### Horses and transport

- **AstikorCarts Redux** — horse carts/transport; verify matching file and dependencies. Both.
- **Horse Expert** — horse breeding/stat progression candidate; verify project status and target file before inclusion. Both.
- **Horse Tack** — horse equipment candidate; verify project status and target file before inclusion. Both.
- **[Create](https://www.curseforge.com/minecraft/mc-mods/create)** — mechanical construction and rail systems, not horse-drawn wagons. Both; follow file dependencies.
- **[Create: Steam 'n' Rails](https://www.curseforge.com/minecraft/mc-mods/create-steam-n-rails)** — Create railway additions; verify matching Create and Forge files. Both.

**Important limitation:** Vanilla horses remain the baseline unless a confirmed compatible horse overhaul is found. [SWEM](https://www.curseforge.com/minecraft/mc-mods/swem) is a notable horse project, but do not include it unless its files explicitly list 1.20.1 Forge. No claim of AAA horse animation or numerous authentic breeds is made here.

### Combat, law, and hostile encounters

- **TaCZ** — firearm handling/reloading and content-pack ecosystem; verify matching files and libraries. Both.
- **[Point Blank](https://www.curseforge.com/minecraft/mc-mods/point-blank)** — firearm framework candidate; verify 1.20.1 Forge file and weapon content. Both.
- **[MrCrayfish's Gun Mod](https://www.curseforge.com/minecraft/mc-mods/mrcrayfishs-gun-mod)** — firearm framework candidate; verify 1.20.1 Forge file and required library. Both.
- **[Guard Villagers](https://www.curseforge.com/minecraft/mc-mods/guard-villagers)** — village defenders; can approximate town guards, not sheriffs with law systems. Both.
- **[Illager Invasion](https://www.curseforge.com/minecraft/mc-mods/illager-invasion)** — additional illager encounters, not human outlaws. Both.
- **[Improved Mobs](https://www.curseforge.com/minecraft/mc-mods/improved-mobs)** — hostile mob difficulty/behavior configuration. Both.
- **[Zombie Awareness](https://www.curseforge.com/minecraft/mc-mods/zombie-awareness)** — sensory behavior for zombies only. Both.
- **[Epic Siege](https://www.curseforge.com/minecraft/mc-mods/epic-siege)** — hostile mob challenge candidate; verify exact supported version. Both.
- **[Enhanced AI](https://www.curseforge.com/minecraft/mc-mods/enhanced-ai)** — hostile mob behavior candidate; verify exact file. Both.
- **[Champions](https://www.curseforge.com/minecraft/mc-mods/champions)** — elite hostile mobs can serve as marked targets; not bounty contracts. Both.
- **[In Control!](https://www.curseforge.com/minecraft/mc-mods/in-control)** — configurable spawn rules and encounter pacing. Server controls spawns; check matching client/server requirements.

No listed mod supplies autonomous armed human bandit factions, bounty hunters, or a wanted-level law system. Avoid presenting generic hostile mobs as armed NPCs.

### Frontier world and locations

- **[Towns and Towers](https://www.curseforge.com/minecraft/mc-mods/towns-and-towers)** — expanded settlements, not specifically Western architecture. Both.
- **[When Dungeons Arise](https://www.curseforge.com/minecraft/mc-mods/when-dungeons-arise)** — large exploration structures, not Western towns. Both.
- **[Repurposed Structures](https://www.curseforge.com/minecraft/mc-mods/repurposed-structures)** — structure variants. Both.
- **[YUNG's Better Desert Temples](https://www.curseforge.com/minecraft/mc-mods/yungs-better-desert-temples)** — desert exploration; requires YUNG's API. Both.
- **[YUNG's Better Mineshafts](https://www.curseforge.com/minecraft/mc-mods/yungs-better-mineshafts)** — improved mine exploration; requires YUNG's API. Both.
- **[YUNG's Better Dungeons](https://www.curseforge.com/minecraft/mc-mods/yungs-better-dungeons)** — exploration structures; requires YUNG's API. Both.
- **[YUNG's Better Strongholds](https://www.curseforge.com/minecraft/mc-mods/yungs-better-strongholds)** — exploration structures; requires YUNG's API. Both.
- **[YUNG's Better Witch Huts](https://www.curseforge.com/minecraft/mc-mods/yungs-better-witch-huts)** — additional structures; requires YUNG's API. Both.
- **[Terralith](https://www.curseforge.com/minecraft/mc-mods/terralith)** — terrain and biome generation; confirm Forge support for the target file. Both/world generation.
- **[Regions Unexplored](https://www.curseforge.com/minecraft/mc-mods/regions-unexplored)** — biome variety; verify file and dependencies. Both/world generation.
- **[Biomes O' Plenty](https://www.curseforge.com/minecraft/mc-mods/biomes-o-plenty)** — biome generation; verify Forge release and world setup. Both/world generation.
- **[Tectonic](https://www.curseforge.com/minecraft/mc-mods/tectonic)** — terrain shaping; test with selected biome stack. Both/world generation.
- **[Structory](https://www.curseforge.com/minecraft/mc-mods/structory)** — environmental structures; verify target Forge file. Both.
- **[Structory: Towers](https://www.curseforge.com/minecraft/mc-mods/structory-towers)** — structure addition; verify matching dependency/version. Both.
- **[Repurposed Structures Compatibility Datapack](https://www.curseforge.com/minecraft/mc-datapacks/repurposed-structures-compatibility-datapack)** — optional datapack, not a standalone mod. Both/world data.

These provide general terrain and exploration, not an authentic Western town set. For saloons, banks, ranches, forts, and hideouts, use a tested Western map or compatible structure datapack. Worldgen alone will not create a coherent Old West region.

### Activities and progression

- **[FTB Quests](https://www.curseforge.com/minecraft/mc-mods/ftb-quests-forge)** — authored mission chapters and rewards; check file dependencies. Both.
- **[FTB Teams](https://www.curseforge.com/minecraft/mc-mods/ftb-teams-forge)** — party/team support for FTB workflows. Both.
- **[FTB Library](https://www.curseforge.com/minecraft/mc-mods/ftb-library-forge)** — shared dependency where required. Both.
- **[Bountiful](https://www.curseforge.com/minecraft/mc-mods/bountiful)** — configurable board-based delivery/bounty objectives; not a wanted-level system. Both.
- **[Villager Markets](https://www.curseforge.com/minecraft/mc-mods/villager-markets)** — villager trading interface candidate; verify target file/dependencies. Both.
- **[Farmer's Delight](https://www.curseforge.com/minecraft/mc-mods/farmers-delight)** — cooking and food production for camp/ranch play. Both.
- **[Supplementaries](https://www.curseforge.com/minecraft/mc-mods/supplementaries)** — utility blocks; requires Moonlight Lib. Both.
- **[Waystones](https://www.curseforge.com/minecraft/mc-mods/waystones)** — configurable travel; limit/disable for frontier-distance pacing. Both.
- **[Lootr](https://www.curseforge.com/minecraft/mc-mods/lootr)** — per-player exploration loot for multiplayer. Both.
- **[Artifacts](https://www.curseforge.com/minecraft/mc-mods/artifacts)** — exploration rewards; verify matching Curios dependency. Both.
- **[FTB Ultimine](https://www.curseforge.com/minecraft/mc-mods/ftb-ultimine-forge)** — configurable mining convenience, not gold panning. Both.

There is no verified native train robbery, bank heist, or gold-panning system in this list. Model heists as quest objectives around authored structures, guarded loot, timed encounters, and rewards. Use vanilla ore plus quest/economy balancing for gold-mining progression.

### Missions, NPCs, and events

- **Easy NPC** — configurable authored NPC encounters; verify file and test on a dedicated server. Both.
- **FTB Quests** — campaign chapters, objectives, rewards, and progression. Both.
- **Bountiful** — repeatable board objectives. Both.
- **[Custom NPCs](https://www.curseforge.com/minecraft/mc-mods/custom-npcs)** — historical project; include only if its page has an explicit 1.20.1 Forge file.
- **[Taterzens](https://www.curseforge.com/minecraft/mc-mods/taterzens)** — NPC candidate; verify target file and feature scope.
- **[F.A.T.E.](https://www.curseforge.com/minecraft/mc-mods/fate)** — event candidate; verify target file and active project status.

**Progression design:** Build chapters for arrival, ranch setup, rail access, local contracts, mine exploration, and a gang-hideout finale. Use FTB Quests for gating/rewards, Bountiful for repeatable jobs, Easy NPC for authored dialogue, and configured hostile encounters for danger. Wanted levels, law pursuit, reputation, and dynamic scripted events need a separately verified system or custom development; they are not provided automatically by this setup.

### Immersion and performance

- **Not Enough Animations** — visible player actions; client.
- **[Shoulder Surfing Reloaded](https://www.curseforge.com/minecraft/mc-mods/shoulder-surfing-reloaded)** — over-shoulder camera; client.
- **[Camera Overhaul](https://www.curseforge.com/minecraft/mc-mods/cameraoverhaul)** — camera motion candidate; verify Forge file. Client.
- **[Sound Physics Remastered](https://www.curseforge.com/minecraft/mc-mods/sound-physics-remastered)** — spatial/occlusion sound effects. Client.
- **[AmbientSounds 5](https://www.curseforge.com/minecraft/mc-mods/ambientsounds)** — environmental ambience. Client.
- **[Dynamic Surroundings](https://www.curseforge.com/minecraft/mc-mods/dynamic-surroundings)** — environment effects candidate; verify exact project/version. Client.
- **[Weather, Storms & Tornadoes](https://www.curseforge.com/minecraft/mc-mods/weather-storms-tornadoes)** — severe weather candidate; verify 1.20.1 Forge release and server impact. Both.
- **[Serene Seasons](https://www.curseforge.com/minecraft/mc-mods/serene-seasons)** — seasonal cycles. Both.
- **[Alex's Mobs](https://www.curseforge.com/minecraft/mc-mods/alexs-mobs)** — additional wildlife; requires Citadel. Both.
- **[Naturalist](https://www.curseforge.com/minecraft/mc-mods/naturalist)** — wildlife candidate; verify target Forge file. Both.
- **[Embeddium](https://www.curseforge.com/minecraft/mc-mods/embeddium)** — client rendering performance; check visual-mod compatibility. Client.
- **[Oculus](https://www.curseforge.com/minecraft/mc-mods/oculus)** — shader support candidate; check Forge/renderer compatibility. Client.
- **[Jade](https://www.curseforge.com/minecraft/mc-mods/jade)** — information overlay; client, server optional for extra data.
- **[JEI](https://www.curseforge.com/minecraft/mc-mods/jei)** — recipe viewer; client, server optional.

## Multiplayer assembly and testing

Use the same Forge 1.20.1 build and matching gameplay mod files on server and clients. Keep camera, sound, shader, HUD, animation, and rendering candidates client-only only where their project pages explicitly confirm it. Put gameplay, quests, NPCs, structures, and worldgen on both sides unless project instructions say otherwise. Install all required libraries at compatible versions.

Before release, test server startup, joining, NPC interactions, quest persistence, firearm synchronization, horse/cart behavior, structure generation in a fresh world, and multiplayer loot/reward claims. Do not add or remove worldgen mods after exploring chunks without planning for mixed terrain.

**Quality-first starting set:** one verified firearm framework (TaCZ is the first candidate), Easy NPC, Guard Villagers, FTB Quests with required libraries, Bountiful, one compatible biome stack, Towns and Towers, a small YUNG structure selection, AstikorCarts Redux only if its target file checks out, and client immersion additions. Add optional wildlife/structures after multiplayer testing. Do not stack multiple firearm frameworks or overlapping biome generators without compatibility tests.
