# [Horiceon](https://github.com/shiftgeist/horiceon) dwm fork

May the source be with you.

## Included patches

| Patch              | Description                                                                                               | Link                                                           |
| ------------------ | --------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| alpha              | Translucent bars, while keeping all the text on it opaque.                                                | [source](https://dwm.suckless.org/patches/alpha)               |
| barpadding         | Adds variables for verticle and horizontal space between the statusbar and the edge of the screen.        | [source](https://dwm.suckless.org/patches/barpadding/)         |
| centeredwindowname | Center the WM_NAME of the currently selected window on the status bar.                                    | [source](https://dwm.suckless.org/patches/centeredwindowname/) |
| cyclelayouts       | Cycles through all avaiable layouts using `MOD-CTRL-,` and `MOD-CTRL-.`.                                  | [source](https://dwm.suckless.org/patches/cyclelayouts/)       |
| fibonacci          | Adds new layout that arranges all windows in Fibonacci tiles.                                             | [source](https://dwm.suckless.org/patches/fibonacci/)          |
| fullscreen         | Applies the monocle layout with the focused client on top and hides the bar.                              | [source](https://dwm.suckless.org/patches/fullscreen/)         |
| movestack          | This plugin allows you to move clients around in the stack and swap them with the master.                 | [source](https://dwm.suckless.org/patches/movestack/)          |
| uselessgap         | Adds useless gaps around windows and removes gaps and borders when in monocle mode for aesthetic purpose. | [source](https://dwm.suckless.org/patches/uselessgap/)         |

## Dependencies

`dmenu` `slock`

## Install

`make` and then `make install`

## Features

- [x] Panda theme
- [ ] Keep default dwm keybindings and don't override defaults (super 2nd mod: `#define MOD2KEY Mod4Mask`)
  - [ ] Add custom keyboard bindings to `dwm.1` key definitions
- [ ] Media control

## Branches

- `main` = master + patches + config
- `master` - copy of `https://git.suckless.org/dwm`
- `patch-\*` - patch applied to master

## Usefull (not included) patches

mpdcontrol, scratchpad, swallow and warp
