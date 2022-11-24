# Lista de mods

## Índice

1. [Rendimiento](#rendimiento)
2. [Mobs en general](#mobs)
3. [Interfaz de usuario](#hud)
4. [Movimiento del jugador](#movimiento)
5. [Experiencia de juego](#experiencia)
6. [Físicas del juego](#fisicas)
7. [Audio del juego](#audio)
8. [Ajustes del juego](#ajustes)
9. [Items](#items)

---

### Rendimiento<a name="rendimiento"></a>

- **sodium-fabric-mc1.19.2-0.4.4+build.18**: Sodium is a free and open-source rendering engine replacement for the Minecraft client which greatly improves frame rates and stuttering while fixing many graphical issues.
- **lithium-fabric-mc1.19.2-0.10.2**: Lithium is a general-purpose optimization mod for Minecraft which works to improve a number of systems (game physics, mob AI, block ticking, etc) without changing any behavior.
- **phosphor-fabric-mc1.19.x-0.8.1**: Phosphor is a Minecraft mod which works to optimize one of game's most inefficient areas-- the lighting engine.
- **iris-mc1.19.2-1.4.2**: An open-source shaders mod compatible with OptiFine shaderspacks.
- **continuity-2.0.1+1.19**: Continuity is a Fabric mod built around modern APIs to allow for the most efficient connected textures experience possible.  
`requiere fabric-api, indium`
- **indium-1.0.9+mc1.19.2**: Indium is an addon for the rendering optimization mod Sodium, providing support for the Fabric Rendering API.  
`require sodium-fabric`
- **exordium-fabric-1.0.1-mc1.19.2**: Renders the GUI at a lower fixed framerate (configurable in the settings), freeing up CPU and GPU time for the world rendering. There is no good reason to render the hotbar at 100+ FPS.
- **FPS-Monitor-1.19-1.3.0-Fabric**: is a lightweight, configurable and versatile tool to display game information on screen for easy access and readability.

---

### Mobs<a name="mobs"></a>

- **BetterAnimationsCollection-v4.0.4-1.19.2-Fabric**: aims to improve the atmosphere of Minecraft by changing the in-game models to allow for better animations and subtle effects.  
`requiere fabric-api, PuzzlesLib, ForgeConfigAPIPort`
- **dungeon_difficulty-1.1.1+1.19**: Increase the difficulty and get matching rewards
- **spiders-fabric-1.19.2-2.0.2**: enables regular spiders and cave spiders to walk along walls and ceilings and it also improves their AI such that they can find their way around almost any obstacle.
- **naturalist-fabric-2.1.1-1.19.2**: Adds more animals to the game that behave as they do in real life.  
`requiere geckolib`

---

### Interfaz de usuario<a name="hud"></a>

- **dynamiccrosshair-3.11+1.19.2**: Dynamic Crosshair is a Minecraft mod for the Fabric launcher. It hides or changes the crosshair dependent on context.  
`requiere fabric-api, cloth-config`
- **dynamiccrosshair-compat-1.11.1+1.19.2**: This is an add-on to my mod Dynamic Crosshair that adds compatibility for some mods. By using this add-on, situational crosshairs will more accurately reflect modded items, blocks, and behaviors.  
`requiere dynamiccrosshair`
- **LegendaryTooltips-1.19.2-fabric-1.3.3**: Allows you to change the tooltips of a selection of items of your choice to embellished works of art.  
`requiere Iceberg, ForgeConfigAPIPort, Prism`  
`resourcepack Eclectic Trove`
- **EquipmentCompare-1.19-fabric-1.3.1**: Is a configurable client-side mod that simply makes it easier to compare equipment at a glance.  
`requiere Iceberg, ForgeConfigAPIPort, cloth-config`
- **appleskin-fabric-mc1.19-2.4.1**: Provides information about some mechanics that are invisible by default
- **BetterPingDisplay-Fabric-1.19.2-1.1.1**: A mod for displaying each player's ping in the player list as a number, with various configuration options.
- **Smooth+Swapping+0.5+(1.19.2)-0.5**: This mod moves items in inventories smoothly instead of letting them appear instantly.
- **AdvancementPlaques-1.19.2-fabric-1.4.6**: Replace those boring, anti-climactic advancement popups with fancy glowing plaques.  
`requiere Iceberg, ForgeConfigAPIPort`  
`resourcepack Vanilla+Advancement, FutureHUD, EmbellishedStone-1.19-1.0.0`
- **Xaeros_Minimap_22.16.2_Fabric_1.19.1**: Unlike many other minimap mods, Xaero's minimap keeps the aesthetic of vanilla Minecraft, which helps it be a more seamless addition to the game.
- **XaerosWorldMap_1.28.3_Fabric_1.19.1**: adds a self-writing fullscreen map to your Minecraft client. Works as a separate mod but is a lot better with Xaero's Minimap.

---

### Movimiento del jugador<a name="movimiento"></a>

- **BetterThirdPerson-Fabric-1.19-1.8.1**: Mod adds independent rotation of the camera in a third person view.
- **camerautils-1.19.2-1.0.2**: Camera Utils is a client side Fabric mod that adds convenient features related to the players camera.
- **Nimble-1.19-fabric-3.0.0**: Nimble is a simple that adds smooth transition animation on player perspective changes.  
`requiere Kiwi`
- **CameraOverhaul-1.3.1-fabric-universal**: a clientside Minecraft mod that attempts to improve overall satisfaction of the game through the introduction of various camera rotations, to emphasize on the player's movement and improve visual feedback.  
`requires cloth-config`
- **InvMove-1.19-0.8.1-Fabric**: adds the ability to walk around while in inventories  
`requiere cloth-config, fabric-api, modmenu`
- **InvMoveCompats-1.18-0.2.0-Fabric**: Addon for InvMove that adds additional mod compatibilities.  
`requiere InvMove`
- **bettercombat-fabric-1.4.5+1.19**: Easy, spectacular and fun melee combat system from Minecraft Dungeons.  
`requires cloth-config, player-animation-lib`
- **combatroll-fabric-1.0.8+1.19**: Ever wanted to roll/dodge/dash in Minecraft? Here is your chance!  
`requires cloth-config, player-animation-lib`

---

### Experiencia de juego<a name="experiencia"></a>

- **Jade-1.19.1-fabric-8.6.0**: It provides a small unobtrusive tooltip on top of the screen with information about the block the player is looking at
- **JadeAddons-1.19.2-fabric-3.0.0**: This mod adds more mod supports for Jade  
`requiere Jade`
- **jei-1.19.2-fabric-11.4.0.286**: JEI is an item and recipe viewing mod for Minecraft, built from the ground up for stability and performance.
- **effective-1.4.1+1.19.2**: Adds water and lava splashes to entities falling in liquids, as well as cascade visual and sound effects.  
`requiere midnightlib, satin`
- **VisualWorkbench-v4.2.0-1.19.2-Fabric**: makes items put into a crafting table stay inside. Breaking the block drops everything on the ground, just like you'd expect. Oh, and crafting ingredients as well as the resulting item are also rendered on top.  
`requires fabric-api, PuzzlesLib, ForgeConfigAPIPort`
- **MerchantMarkers-1.19.1-fabric-1.2.3**: Add custom markers above villagers to make them stand out and be easier to find than ever.  
`requiere Iceberg, ForgeConfigAPIPort`
- **Highlighter-1.19.1-fabric-1.1.4**: Quickly find new items by showing an animated star on all newly-picked up items.  
`requiere Iceberg`
- **ItemBorders-1.19-fabric-1.1.6**: Add colored borders to inventory slots to make your rare items stand out!  
`requiere Iceberg`
- **visuality-0.5.5**: Add a bunch of new particles such as crystal sparkles, particles on mob hitting, custom blob particles for slimes, environmental particles to your Minecraft world.

---

### Físicas del juego<a name="fisicas"></a>

- **SnowRealMagic-1.19.2-fabric-5.0.4**: This simple tweak mod can enrich the vanilla snow layer's behavior.  
`requiere Kiwi, cloth-config`
- **physics-mod-2.9.2-mc-1.19.x-fabric**: Collapsing caves, interactive Ragdolls, Item physics and much more
- ****: It allows to revive a player within 60 seconds after death.

---

### Audio del juego<a name="audio"></a>

- **DynamicSurroundings-RemasteredFabric-1.19-0.1.1**: This mod is a spiritual successor to the Forge based Dynamic Surroundings series.
- **PresenceFootsteps-1.6.3**This is the continuation of Huricaaan (Ha3)'s original mod, maintained and updated to the latest version of Minecraft.
- **auditory-0.0.4-1.19.x**: Auditory is a Minecraft mod for Fabric 1.19 that expands and improves upon block sounds, item sounds, and more!  
`requiere fabric-api`
- **extrasounds-2.3.1+1.19.2-1.19.1**: Adds more sounds to Minecraft, like sounds when you scroll the hotbar, the creative inventory, pick up or place items in inventories, and more!  
`requiere fabric-api`
- **dynamic-music-1.5.1**: Adds adaptive music cues, and makes The End more musical!
- **soundphysics-fabric-1.19.2-1.0.16**: provides realistic sound attenuation, reverberation, and absorption through blocks.
- **voicechat-fabric-1.19.2-2.3.16**: adds a proximity voice chat to your Minecraft server.
- **vcinteraction-1.19.2-1.0.2** This server side Fabric mod allows Simple Voice Chat to interact with your Minecraft world.
`requires voicechat`
- **AmbientSounds_FABRIC_v5.2.9_mc1.19.2**: Adds a more vibrant ambience.  
`requiere CreativeCore`

---

### Ajustes durante el juego<a name="ajustes"></a>

- **modmenu-4.1.1**: Adds a screen for viewing a list of installed mods.

---

### Items<a name="items"></a>

- **craftable_enchanted_golden_apple-1.0.3**: Adds the 1.8 crafting recipe for the Enchanted Golden Apple back into the game!

---

### Librerías

- **fabric-api-0.66.0+1.19.2**: Fabric API is the core library for the most common hooks and inter-compatibility measures utilized by mods using the Fabric toolchain.
- **PuzzlesLib-v4.3.12-1.19.2-Fabric**: is a rather light-weight library consisting of multiple frameworks and utility classes.  
`requiere fabric-api, ForgeConfigAPIPort, cardinal-components`
- **cardinal-components-api-5.0.2**: Cardinal Components is an API for attaching arbitrary data to various game objects.
- **ForgeConfigAPIPort-v4.2.6-1.19.2-Fabric**: is a modding library for the Fabric ecosystem providing the whole Forge config api.  
`requires fabric-api, modmenu`
- **cloth-config-8.2.88-fabric**: Cloth Config API is a config screen api.
- **Iceberg-1.19.1-fabric-1.0.46**: This library contains new events, helpers, and utilities to make modders lives easier.
- **Prism-1.19.2-fabric-1.0.3**: This library contains a powerful set of utilities to easily add color-related functionality to your mods.
- **Kiwi-1.19.1-fabric-8.1.2**: Kiwi is a Minecraft library mod which adds utilities for developers. It will do nothing with game itself.
- **midnightlib-fabric-1.0.0**: MidnightLib is a library that provides common utils and a configuration system for mods.
- **satin-1.9.0**: Satin is a simple library allowing modders to add interesting graphical effects to their mods.
- **player-animation-lib-fabric-0.4.0-test4**: Player animation library, animate the player using keyframes.
- **projectiledamage-fabric-2.2.0+1.19**: Adds new EntityAttribute to the game. This allows customization of damage done by individual Bow and Crossbow items in the game.
- **geckolib-fabric-1.19-3.1.37**: Is an animation engine for Minecraft Mods
- **CreativeCore_FABRIC_v2.9.1_mc1.19.2**: A simple core mod required by most of my mods, containing useful features like a gui-api, packet system, dynamic rendering system, easy asm transformation name manager and other useful stuff.

---
