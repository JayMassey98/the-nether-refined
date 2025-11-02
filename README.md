# The Nether Refined

This Minecraft data pack refines The Nether dimension whilst maintaining a vanilla-like feel.


## World Generation

In general, the generated shape of the Nether looks almost identical from y=0 to y=128 to how it does in vanilla Minecraft. However, there have been various changes made to the Nether in order to refine it.

### General

* Changed maximum y value from 128 to 320.
* Changed minimum y value from 0 to -64.
* Changed patch fire to spawn on all infinitely burning blocks.
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
    * Contain 2x2 trunks that can be anywhere from 8 to 48 blocks tall.
    * Have large wart blocks canopies spreading outwards from the stem trunk.
    * Feature weeping vines and shroomlights hanging down from the wart blocks.
    * Spawn densely, featuring hyphae roots and no shroomlights on ground level.
* Replaced gravel with smooth basalt.

### Nether Wastes

* Replaced gravel with smooth basalt.

### Soul Sand Valley

**[TODO]**

### Warped Forest

**[TODO]**


## Mob Spawns

Several mob spawns have been altered in the biomes below.

### Crimson Forest

* Reduced the weight of Hoglin spawns from 9 to 7.2.
* Increased the weight of Zoglin spawns from 0 to 1.8.

### Nether Wastes

zombified_piglin
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
    * Stop the explosions from being used to mine ancient debris.

* Disabled building above the Nether roof, in order to:
    * Discourage safe creation of mob farms without danger.
    * Discourage safe travelling without setting up infrastructure.


## Compatibility

The following Minecraft versions are supported:

* 1.21.9


## FAQ

### Will previous versions be supported in the future?
Yes, although this isn't a high priority at the moment. Please note though that certain features will not be possible to backport to older versions, such as dried ghasts spawning in nether fossils.