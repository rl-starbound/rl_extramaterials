# Starbound mod: RL Extra Materials

This mod provides extra building materials, including:

* a variety of sloped glass panels

Also provided are invisible blocks that administrators can spawn and place for use in specialty builds.

## Sloped Glass Panels

A number of sloped glass panels have been provided, each framed in one of the four styles of the vanilla sloped panels:

* `rl_slopedglasspanel` - Glass Panel
* `rl_slopedglasspanelinset` - Inset Glass Panel
* `rl_slopedglasspanelrusty` - Rusty Glass Panel
* `rl_slopedglasspanelscrap` - Scrap Glass Panel

These are also available in black glass varieties:

* `rl_slopedblackglasspanel` - Blk Glass Panel
* `rl_slopedblackglasspanelinset` - Inset Blk Glass Panel
* `rl_slopedblackglasspanelrusty` - Rusty Blk Glass Panel
* `rl_slopedblackglasspanelscrap` - Scrap Blk Glass Panel

All of these blocks can be found in space encounters among the basic and trash loot pools, but are most likely to be found on hostile spaceship encounters. The recipes are learned upon pickup.

## Invisible Materials

Three invisible materials are provided:

* `rl_invisibleblock` - A light-opaque invisible block
* `rl_invisibleblocklight` - A light-transparent invisible block
* `rl_invisibleplatform` - A light-transparent invisible platform

These materials must be spawned by admin commands and are fully invisible, except when painted magenta. They drop nothing if broken, and are all relatively strong (30 health) to avoid accidental breakage.

## Tilesets

Tilesets have been provided with this mod, for importation into Tiled maps.

## Compatibility Notes

Material IDs have been registered at: https://starbounder.org/Modding:Materials:Mods

## Uninstall Notes

Due to how the vanilla Starbound code handles removed mod assets, some issues may crop up. None of these issues are major, but you should be aware of them before removing this mod. If this mod is removed:

* When any world containing blocks from it is loaded, those blocks will be converted automatically into dirt.
* The first time you load each character who has learned a recipe from this mod, the game may crash. However, you should be able to load the character again, and play should resume with the character returned to their ship.

## License

Permission to include this mod or parts thereof in derived works, to distribute copies of this mod verbatim, or to distribute modified copies of this mod, is granted unconditionally to Chucklefish LTD.
