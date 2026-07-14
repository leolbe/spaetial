Utility Minecraft mod for faster building and world editing.

# Installation

Place the mod's .jar file into your minecraft installation's `mods/` directory. See releases at [releases/](https://github.com/leolbe/spaetial/releases).

Dependencies (make sure Minecraft version is matching):
- [Fabric Loader](https://fabricmc.net/)
- [Fabric API](https://modrinth.com/mod/fabric-api/)
- [Mod Menu](https://modrinth.com/mod/modmenu/) (optional)

# Features

## Fast copying/moving

Copy and move regions and blocks with a few quick inputs:

`Alt LMB`, `LMB` to select a region.

`X` to activate 'Cut' mode and `Ctrl Scroll` to move the selection.

`LMB` to confirm. `Z` to undo.

## Quick set/replace

Fill volumes of blocks with the currently held block, or randomly select from items in a bundle:

`Y`, `LMB` to replace non-air blocks in a volume.

`Ctrl Y`, `LMB` to replace all blocks in a volume.

# Usage

While in game, toggle the mod ON/OFF with the `\` key.

The mod's functionality is split between so called 'editing states', which are controlled using keyboard/mouse input. The default state when the mod is toggled ON is `Normal`.

The following hotkeys are common to multiple editing states:

| Key          | Function                           |
|--------------|------------------------------------|
| LMB          | Confirm                            |
| RMB          | Cancel                             |
| Z            | Undo                               |
| Alt Z        | Redo                               |
| Ctrl Scroll  | Move selection                     |
| Alt RMB      | Move selection to cursor           |
| Ctrl Alt RMB | Move selection to cursor (surface) |
| G            | 2D move selection                  |

## `Normal` state

| Key          | Function                         |
|--------------|----------------------------------|
| Alt LMB      | Start cuboid selection           |
| Ctrl Alt LMB | Start cuboid selection (surface) |
| Y            | Quick replace                    |
| Ctrl Y       | Quick replace (surface)          |
| Alt Y        | Quick set                        |
| Ctrl Alt Y   | Quick set (surface)              |
| V            | Paste                            |
| Ctrl V       | Paste (surface)                  |
| Alt V        | Paste (including air)            |
| Ctrl Alt V   | Paste (surface, including air)   |

### Quick set/replace

Select a volume (see controls above). 'Quick set' replaces all blocks in the volume with the block in your main hand, while 'quick replace' replaces only non-air blocks. If your main hand is empty, all blocks are replaced with air. If your main hand holds a bundle, a random selection of blocks are selected from the bundle's contents.

## `Cuboid selection` state

Selection manipulation:

| Key             | Function                           |
|-----------------|------------------------------------|
| LMB             | Extend selection                   |
| Alt LMB         | Extend selection (surface)         |
| Alt Scroll      | Resize selection                   |
| Ctrl Alt Scroll | Resize selection (from back)       |
| Alt G           | 2D resize selection                |

Operations:

| Key   | Function             |
|-------|----------------------|
| X     | Cut                  |
| Alt X | Cut (including air)  |
| C     | Copy                 |
| Alt C | Copy (including air) |

## `Copy/Cut` state

| Key   | Function                                   |
|-------|--------------------------------------------|
| Tab   | Cycle mode (Clone/Line stack/Volume stack) |
| 1     | Switch to Clone mode                       |
| 2     | Switch to Line stack mode                  |
| 3     | Switch to volume stack mode                |
| V     | Confirm and continue                       |
| Alt V | Confirm (including air) and continue       |

Line stack mode:

| Key             | Function             |
|-----------------|----------------------|
| Alt Scroll      | Change stacking size |
| Ctrl Alt Scroll | Change spacing       |
| Ctrl Alt G      | 2D Change spacing    |

Volume stack mode:

| Key             | Function                |
|-----------------|-------------------------|
| Alt Scroll      | Change stacking size    |
| Alt G           | 2D Change stacking size |
| Ctrl Alt Scroll | Change spacing          |
| Ctrl Alt G      | 2D Change spacing       |
