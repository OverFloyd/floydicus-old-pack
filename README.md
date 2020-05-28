# Floydicus-Old-Pack
Hello people, last year I started a private resource pack which had the goal of reproducing Minecraft Beta as much as possible. Using classic textures, custom models, blockstates and everything in the between.

After working on it for nearly a year with feedback from several people, I've decided to make this public to everyone to enjoy.

The resource pack is being developed for both versions 1.15.X and 1.12.2 (still in development), an older version for 1.12.2.
The packs for each version are under <code>src/</code>

[Planet Minecraft](https://www.planetminecraft.com/texture_pack/floydicus-old-pack/) page.


**CHANGELOG**

**v1.1.1**
- Rotated 3D models for lapis and redstone block (GUI)
- Retextured:
* loom
* barrel
* cartography table
* fletching table
* smithing table
* end stone and end portal frame
* redstone block (uses a retextured version of the first version of the iron block)
* lectern
* petrified wooden slab
* observer (from 16w43a)
* mirrored oak door from Infdev

**v1.2**
- Cleaned up the pack from redundant textures
- Added textures and related json files when necessary:
* Old infdev rails
* Andesite, diorite, granite, stone bricks variants and end	stone bricks now have a custom made double slab texture
* Old water
* Old-styled ender chest (pre beta 1.8 model)
* Old leaves (custom model for avoiding smooth lighting)
* Old beta wool
* Cactus, pressure plates, fences trapdoors and stairs now have a bigger model (and rotated in the inventory) when dropped
* Furnace sounds from 1.9 for campfire
* Old grass dead bush in swamplands (optifine)
* Removed squid ink, falling dust particles, added unused angry villager
* Campfire now has regular fire texture
* Readded early counduit particles
* Reverted enderman emitting smoke
* Implemented bed sprites from BE
* Petrified oak slabs now have the regular block model, with missing texture (from 1.8)
* Snowballs particles for thrown eggs
* lower half slabs now use the top texture for the block they refer to
* Single level enchants made like pre 1.9 (Silk Touch I)
* Brought back pressure plates, buttons and nether portal travel sounds
* Removed item frame background texture, corner uses oak planks texture once again (ref: http://media.dinnerbone.com/uploads/2012-08/screenshots/Minecraft_2012-08-15_16-20-33.png)
* Lantern uses stone sounds
* Beta looking colormap (grass/foliage)
* Grass block: old top texture (flipped to the right)
* Sugar canes: now use "cross" instaed of the "tinted_cross" template, deleted dedicated custom colormap file in "optifine" folder
* Old spawn eggs colors (optifine, from 11w49a)
* Enhanced old light system
* Deleted newer music tracks (2013 music update), deleted redundant files, reworked sounds.json heavily
* Nether portal frames: now all 6 sides are rendered
* Fixed magenta glass panes showing up as lime panes when placed
* Old fire animation on burning mobs
* b1.7 cobblestone texture for infested cobble
* Old end portal frames from b1.9-pre3 (weird trasparency when placed on blocks - 1.14.4+)
* Bad omen icon changed to quiver, Hero of the village icon changed to ruby
* Wool sounds for step on coral fans
* Delete sounds for achievements
* "Underwater" color added in optifine (1.14.4)
* Sandstone/red sandstone and variants slabs added
* Rotated wood bark blocks (GUI)
* Minecart with chests and hoppers now display just "Minecart"
* Big model for ender eye (3rd person)
* Hopper uses cauldron texture once again
* Powered rail in inventory uses the on state texture
* Removed dark prismarine and prismarine bricks from C.A.
* Carrot item sprite from 12w34a
* Golden carrot sprite from 12w36a

- Retextured:
* Lantern
* Allium and lily of the valley
* Accessibility button now has the old cog texture
* "Toast" pop ups made a bit more old style
* Made the Mojang logo have trasparency
* Cod (entity) using the old cod sprite from 1.12.2
* Scaffold

- Moved doors variants, old rails and old furnace stone top into the new Alpha Overlay pack
* adjusted dispensers/droppers in Old Pack


- 1.12.2
* Added petrified oak texture for wooden slabs
* Different textures for some double slabs, seamless variants

- Updated #Cretits and features and #Copyright



**v1.2_01**
- Both 1.12.2 and 1.14.4
* Fixed banners facing right in the GUI, now they're flipped to the left as for all the other blocks in the pack
* Last update for 1.14.4

- 1.12.2
* Fixed trapdoors models (up and open models weren't present)

- 1.14.4
* Moved glass panes json files from models to models/block/panes (edited relative block states)
* Removed terrain.png files



**- 1.2_02 (1.12.2)**
* Fixed lit furnace (had leftover texture from Alpha Overlay)
* Updated lightmap
* Removed mcpatcher folder
* Added flat heads textures
* Rotated fence gates
* Cleaned a lot of jsons and useless sounds, edited "block" template
* Old wooden planks/slabs now emit stone particles
* Fixed trapdoor upper state displaying incorrect texture section



**v1.3 - 1.15.X**
- Updated to 1.15
* Removed item frame background image file
* Randomized opening/closing sound events for doors/fence gates/trapdoors/chests
* Made honey blocks look and sound like slime blocks
* Petrified oak slabs now emit stone particles like it was in beta
* Reworked campfire's model, now uses block/fire and fire_0 textures
* Removed iron golem's cracked states
* Added custom texture for barrel in inventory (inspired from a BE unused texture)
* Rotated walls and fences
* Fixed chests (updated to 1.15's new format)
* Lectern: fixed awful side texture, fixed rotation angles (GUI)
* Cleaned a lot of useless files (GUI display moved to block.json)
* Stairs now have a custom model for GUI
* Correct angle for buttons and onground bigger model
* Trapdoors now have the "correct" side texture and they're now centered (GUI)
* Correct model for pressure plates (original is 4 pixed high, old one was 3)
* Moved various sprites by 1 pixel
* Carved pumpkin, jack o' lantern, furnace, blast furnace, smoker, beehive, bee nest, dispenser and dropper now have separate models for all orientations
* Beds now have stone particles
* Removed critical hit particles
* Chest/trapped/echest now have the old model in the gui
* Made water texture vanilla friendly (gray scaled) and additional colormap texture for when using optifine
* Removed beta 1.9 pre3 sun/moon, now uses Alpha Overlay's version
* Mirrored all the blocks (cube.json/orientable.json): both #top and #bottom textures now face north
* Fixed fence gates, original one was 1 px higher (custom fence_gate_inv.json)
* Stairs: old model and glitched textures, adapted inner and outer bottom/top states (a lot of jsons and blockstates)
* Block.json: makes all the blocks render left in the gui (with correct top texture) and old orientation in 1st person
* Adapted various block models due to the custom cube.json (grass block, path, snow layers, petrified wooden slabs)
* Emerald block now has a gold/diamond/iron blockish texture
* Stripped logs now have oak top
* Fixed fishes angle in inventory (1st person from beta 1.8)
* Hopper has the "wip" sprite
* Fixed spawn egg overlay (now shows up correctly without z fighting)
* Conduit now uses texture from mob_effect

- Retextured:
* Beehive
* Campfire (based on the early 1.14 snapshots model)
* Lantern
* Smithing table (again)
* Smoker (wooden part now uses oak_log texture)

1.12.2 (WIP!)
* Added smooth variant for cobblestone and a separated texture for infested cobble



**v1.3.1**
* Fixed leaves.json being broken
* Fixed Iron Golems having sounds
* Fixed wrong textures on sandstone/red sandstone stairs
* End stone texture obtained from the original
* Retextured bee nest (fixed some issues with its and beehive custom models)
* Removed "drip" and "work" sounds from bee nest/hive, "shear" sound changed to wool.break
* Gray scaled gui wise: leaves, grass and ferns (normal, tall)
* Fixed wrong orientations 1st/3rd person
* Grass block now has 6 sided texture properly, aswell as mycelium and podzol
* Fixed player death sound having the newer one (event uses blank.ogg due to the sound overlapping with entity.player.hurt)
* Retextured lectern (uses spruce textures and old golden base)
* Custom player heads now display player's face texture again
* "You can only sleep at night" is back again
* XP orbs don't make sounds when collected again
* Removed sound for flowing water
* Removed sounds for infecting/curing a villager
* Fixed nether brick stairs having cobblestone texture
- Fixed inner_stairs and variants (one cube was badly mapped and causing issues on sandstone stairs)
- Retextured tulips (flowers)
- Added old end sky
- Fixed walls, fences and fence gates bad texture mapping (more custom models)
- Fixed z-fighting on e-chest front texture (for vanilla model)
- Minecon 2018 corals + new textures for missing ones



**v1.3.2**
- Bamboo (w/ potted version) now uses 2D "cross" template, adjusted sounds
- Removed grass block side texture overlay
- Cornerless legs for cauldrons (pre 1.8)
- "Can't reach server" and "Polling..." text on multiplayer menu
- Retextured honey block (off the slime block texture)
- Retextured magma block
- Fixed a bunch of names in lang.json
- Old Enderman sounds
- Fixed incorrect texture mapping in template_trapdoor_open.json
- Fixed acacia trapdoor having wrong side texture for the open state
- Cauldron has grass_block_top texture in the inventory
- Fixed hitting sand having new sounds



**v1.4 - 1.16**
- Retextured nether grass, basalt, mushrooms, lightshroom, nether planks/stem, netherite block, nether vines, ancient debris
- Added custom models for new fences, fencegates, trapdoors, pressure plates, doors etc
- Pots and redstone don't have a bottom texture again
- Reverted and adjusted newer sounds (TO DO)
