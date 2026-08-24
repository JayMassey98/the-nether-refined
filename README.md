# The Nether Refined

This Minecraft data pack refines The Nether dimension whilst maintaining a vanilla-like feel.


## World Generation

The generated shape of the Nether looks almost identical from y=0 to y=128 to how it does in vanilla Minecraft. However, there have been various changes made in order to refine the Nether.

### General

* Changed maximum y value from 128 to 320.
* Changed minimum y value from 0 to -64.
* Changed patch fire to spawn on all infinitely burning blocks.
* Removed Nether fog (render distance fog is still present).
* Replaced gravel beaches with soul soil.
* Replaced gravel walls with smooth basalt.

### Basalt Deltas

* Added basalt roof columns.
* Changed basalt areas to be slightly harder to traverse.
* Changed blackstone areas to be slightly easier to traverse.
* Changed blackstone blobs to be 4x more abundant.
* Changed deltas to have a minimum magma block rim size of 1 (was 0).
* Changed spring deltas to spawn within basalt or blackstone blocks, but only when lava is detected up to 15 blocks below.
* Removed glowstone.
* Removed mushrooms.

### Crimson Forest

* Added netherrack roof columns.
* Changed crimson forest vegetation so that only crimson related vegetation appears.
* Changed weeping vines to spawn more frequently, some of which are now much longer.
* Removed glowstone.
* Removed mushrooms.
* Replaced crimson fungi with crimson trees, which:
    * Spawn densely, with hyphae roots but no shroomlights on ground level.
    * Contain 2x2 solid trunks that can be anywhere from 8 to 48 blocks tall.
    * Have large wart block canopies spreading outwards from the stem trunk.
    * Feature weeping vines and shroomlights hanging down from the wart blocks.

### Soul Sand Valley

* Added blackstone blobs.
* Removed basalt pillars.
* Replaced crimson root patches with vegetation that spawns ~4x as frequently.
    * New nether wart patches spawn ~3x as frequently than the replaced crimson root.
    * New wither roses spawn ~1x as frequently, but individually rather than in patches.

### Warped Forest

* Added warped wart ceiling columns.
* Changed warped forest vegetation so that only warped related vegetation appears.
* Changed twisting vines to spawn more frequently, some of which are now much longer.
* Removed glowstone.
* Removed mushrooms.
* Replaced warped fungi with warped trees, which:
    * Spawn densely, growing downwards from warped wart ceilings and canopies. 
    * Contain 3x3 hollow trunks that can be anywhere from 8 to 48 blocks tall.
    * Have large wart block canopies spreading outwards from the stem trunk.
    * Feature weeping vines and shroomlights raising up from the wart blocks.


## Mob Spawns

Several mob spawns have been altered in the biomes below.

### Crimson Forest

* Reduced the weight of Hoglin spawns from 9 to 7.2.
* Increased the weight of Zoglin spawns from 0 to 1.8.

### Nether Wastes

* Reduced the weight of Magma Cube spawns from 2 to 0.
* Increased the weight of Zoglin spawns from 0 to 2.
* Reduced the weight of Piglin spawns from 15 to 0.
* Increased the weight of Blaze spawns from 0 to 15.

### Soul Sand Valley

* Replaced Ghast spawns with Vex spawns.
* Reduced the weight of Skeleton spawns from 20 to 10.
* Increased the weight of Wither Skeleton spawns from 0 to 10.

### Warped Forest

* Reduced the weight of Strider spawns from 60 to 30.
* Increased the weight of Ghast spawns from 0 to 30.


## General Changes

To refine the Nether further, the following changes have been made.

* Added the following to the list of blocks that infinitely burn in the Nether:
    * Basalt
    * Crimson Nylium
    * Nether Wart Block
    * Warped Nylium
    * Warped Wart Block

* Changed the coordinate scale from 8 to 1, in order to:
    * Align the world borders of the Overworld and the Nether; this is useful when playing on a server that relocates the Overworld spawn and updates the world border to match it. 
    * Inspire building up infrastructure for travelling, instead of quick walks between portals.

* Disabled beds blowing up when right-clicked, in order to:
    * Stop new players from dying to an unexplained game mechanic.
    * Stop the explosions from being used to mine for ancient debris.

* Disabled building above the Nether roof, in order to:
    * Discourage safe creation of mob farms without any danger.
    * Discourage safe travelling without setting up infrastructure.


## Compatibility

The following Minecraft versions are supported:

* 26.2
* 26.1.2
* 26.1.1
* 26.1
* 1.21.11
* 1.21.10
* 1.21.9


## FAQ

### Will previous versions be supported in the future?
Maybe, although this isn't a high priority at the moment.