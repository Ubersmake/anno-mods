# Processing Time Formats

A mod for Anno 117. Tested on 1.4.

Provides different formats for Processing Time values on production buildings. This defaults to changing the `mm:ss` format to just the number of seconds, in addition to a number for (rounded) tons per minute.

The Anno series uses tons as the de facto unit of mass. These formats are available for UI elements in the Construction Menu / Hotbar / Radial Menu, and the currently selected Production Building info in the bottom right corner:

- Seconds with tons per minute, rounded up: `01:30` -> `90s (0.7 t/m)`
- Default With tons per minute, rounded up: `01:30` -> `01:30 (0.7 t/m)`

To use a different format, after installing this mod open `processing-time-formats/data/infotips/export.bin.xml`, then make sure the format you want is uncommented and the others are commented out. Or make your own!

## TODOs

- [X] Change version to 0.0.1 until ready to "publish"
- [X] Update for Patch 1.4
- [X] Add text to specify Anno 117
- [-] Review https://github.com/anno-mods/modding-guide/blob/main/documentation/infotips.md#compatibility-with-other-mods-please-read-if-you-mod-infotips
- [ ] Expand README to call out potential mod incompatibilities
- [ ] Test for mods that increase production amount within CycleTime
