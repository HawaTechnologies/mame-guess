# mame-guess

A small tool to guess the proper MAME version for a zipped ROM.

## Usage

Clone this repository, properly symlink the `mame-guess` executable inside, and then run it like:

```shell
mame-guess some-game.zip
```

On success, it'll return something among:

- `mame2000_libretro.so`.
- `mame2003_libretro.so`.
- `mame2003_plus_libretro.so`.
- `mame2010_libretro.so`.
- `mame_libretro.so`.

Actually, `mame_libretro.so` is the default one. This tool is intended for DragonShark, which has
support only for those emulator options.
