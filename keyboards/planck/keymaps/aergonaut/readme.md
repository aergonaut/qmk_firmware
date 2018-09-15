# aergonaut's Planck layout

This is my lightly customized Planck layout. For the most part it is the same as
the default layout. The primary difference is that Tab and Esc are swapped, and
Esc is replaced with Grave Escape. This lets me use Cmd+\` to switch windows
without having to hold a layer key. I also replaced Enter with Shift Enter,
which allows me to have a key that performs Enter when tapped and Shift when
held down.

## Building and Flashing

First put the keyboard into flash mode.

Then build and flash the firmware using:

```
make planck/rev6:aergonaut:dfu-util
```

This will build the .bin file and then invoke `dfu-util` to flash the board.
