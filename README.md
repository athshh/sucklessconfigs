# sucklessconfigs

this is just some configs that might help me later when i mess around too much with my linux distro.

## dependencies:
pactl (in dwm configs)(for volume control; switch out config.h or config.def.h with preferred program if you want)
brightnessctl (in dwm configs)(for brightness control; switch out config.h or config.def.h with preferred program if you want)

## dwm:
MODKEY changed to the windows key or whatever key it is on your keyboard
added volume controls (Win+F1 = mute toggle, Win+F2 = lower volume by 5%, Win+F3 = increase volume by 5%)
added brightness controls (Win+F5 = decrease brightness by 10%, Win+F6 = increase volume by 10%)

## dmenu:
added fuzzymatch patch (http://tools.suckless.org/dmenu/patches/fuzzymatch/)

## st:
added scrollback patch, along with mouse scrollback (shift+scrollwheel)(tools.suckless.org/st/patches/scrollback/)

