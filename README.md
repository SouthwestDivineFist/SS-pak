# Sega Saturn Emulator (YabaSanshiro v1.9.0) for NextUI

Standalone Sega Saturn emulator pak for NextUI running on the TrimUI Brick.

This pak integrates the Yabause v1.9.0 emulator into the NextUI pak system and supports standard Sega Saturn game formats.

## Installation

1. Copy `SS.pak` to `/Emus/`.
2. Place your Sega Saturn ROMs in:

```
/Roms/Sega Saturn(SS)/
```

3. Provide a **legally obtained Sega Saturn BIOS** in `/bios/SS/`.

## Supported formats

- .cue
- .bin
- .iso
- .m3u (multi-disc playlists)

## Folder launching

Clicking a game folder will automatically load the corresponding `.cue` or `.m3u`.

## Renderer

Default: OpenGL

## Save Location

All game saves will be stored in `/Saves/SS/`.

## Tested games

- Saturn Bomberman
- Lunar: Silver Star Story

2D titles run well with OpenGL.

## Controls

Standard NextUI mapping. Emulator menu works normally.

## Exit

Menu → Exit → NextUI

## Notes

- BIOS must be placed in `/bios/SS/`
- Emulator UI slightly differs from NextUI
- Best suited for 2D Saturn titles

## Emulator

YabaSanshiro (standalone)
