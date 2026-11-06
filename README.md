# yafth.h - You should buy Skyrim

A single-header C and C++ library for [terminal hacking in Fallout 3 and New Vegas](https://fallout.fandom.com/wiki/Hacking#Fallout_3/New_Vegas).
The entire library fits in under 1 KLOC.

## Quick start

Copy [yafth.h](yafth.h) into your project. Add this to one C or C++ source file.

~~~c
#define YAFTH_IMPLEMENTATION
#include "yafth.h"
~~~

In other source files, include the header normally.

The header starts with an example that prints a terminal frame. Save it as
`demo.c` next to `yafth.h` and run it.

~~~sh
cc -std=c99 demo.c -o demo
./demo
~~~

For a playable example, see the [FTXUI application](https://github.com/gshigin/yet-another-fallout-terminal-hacking-game).

## Licence

Choose either the MIT License or The Unlicense. See [LICENCE](LICENCE).
