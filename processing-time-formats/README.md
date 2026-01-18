# Processing Time Formats

Provides several different formats for Processing Time values on production buildings. This defaults to tons per minute.

The Anno series uses tons as the de facto unit of mass. These formats are available for UI elements in the Construction Menu / Hotbar / Radial Menu, and the currently selected Production Building info in the bottom right corner:

- Seconds only: `01:30` -> `90 s`
- Tons per minute, rounded up: `01:30` -> `0.7 t/m`
- Tons per hour: `01:30` -> `40 t/h`

Along with variants of the default format with the new ones, like `01:30 (0.7 t/m)`.

To use a different format, after installing this mod open `processing-time-formats/data/infotips/export.bin.xml`, then make sure the format you want is uncommented and the others are commented out.
