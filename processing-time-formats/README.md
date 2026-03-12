# Processing Time Formats

A mod for Anno 117. Tested on 1.4.1.

Provides different formats for Processing Time values on production buildings. This defaults to changing the `mm:ss` format to just the number of seconds in addition to rounded tons per minute.

The Anno series uses tons as the de facto unit of mass. These formats are available for UI elements in the Construction Menu / Hotbar / Radial Menu, and the currently selected Production Building info in the bottom right corner:
- This mod's default, seconds with rounded tons per minute: `01:30` -> `90s (0.7 t/m)`
- Anno's default with rounded tons per minute: `01:30` -> `01:30 (0.7 t/m)`
- Just seconds: `01:30` -> `90s`

To use a different format, after installing this mod open `processing-time-formats/data/infotips/export.bin.xml`, then make sure the format you want is uncommented and the others are commented out. Or make your own!

## Potential Issues

As of patch 1.4.1, this mod should have no issues with any of the production chains in Anno 117. However, the modding community has played around with production chains where input good quantities aren't all just `1`, and these mods for Anno _1800_ surface those changes:
- [shared_TT_MenuInputOutputAmounts](https://github.com/Serpens66/Anno-1800-SharedMods-for-Modders-/tree/main/shared_TT_MenuInputOutputAmounts)
- [shared_TT_MultipleInputAmountUpgrade](https://github.com/Serpens66/Anno-1800-SharedMods-for-Modders-/tree/main/shared_TT_MultipleInputAmountUpgrade)

It's entirely possible that someone will make something interesting for _117_ that uses mixed input quantities for production chains. It could even happen in official DLC. And if that happens this mod _should_ gracefully stop working.
