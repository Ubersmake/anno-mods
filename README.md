# Anno Mods

A place for Anno mods.

A note on versioning. These mods _do not_ use [SemVer](https://semver.org/). They instead line up with the latest version of Anno that they were tested against.

## Anno 117

- [Processing Time Formats](https://github.com/Ubersmake/anno-mods/tree/main/processing-time-formats): Provides different formats for Processing Time values on production buildings. This defaults to changing the `mm:ss` format to just the number of seconds in addition to rounded tons per minute.

### Installation

Anno 117 doesn't have a built-in mod browser, and nothing here is published on [mod.io](https://mod.io/g/anno-117-pax-romana) (yet). To install:
- Download this repository as a ZIP.
- Extract that ZIP somewhere convenient.
- Place the desired mod folder in your user's Anno 117 mod folder, which should be `<user documents>/Anno 117 - Pax Romana/mods/`.
- Launch the game.

Things should Just Work. By default Anno 117 will attempt to enable any new mods and add it to your list of enabled mods. If things don't work:
- Open `<user documents>/Anno 117 - Pax Romana/mods/active-profile.txt` and make sure there is no `#` before `EnableNewMods`, and try again.
- If things still don't work, open a [new issue](https://github.com/Ubersmake/anno-mods/issues).
