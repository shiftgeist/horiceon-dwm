# [Horiceon](https://github.com/shiftgeist/horiceon) dwm fork

May the force of git be with you.

## Included patches

| Patch              | Description                                                                                        | Link                                                           |
| ------------------ | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| alpha              | Allow dwm to have translucent bars, while keeping all the text on it opaque.                       | [source](https://dwm.suckless.org/patches/alpha)               |
| barpadding         | Adds variables for verticle and horizontal space between the statusbar and the edge of the screen. | [source](https://dwm.suckless.org/patches/barpadding/)         |
| centeredwindowname | A little patch to center the WM_NAME of the currently selected window on the status bar.           | [source](https://dwm.suckless.org/patches/centeredwindowname/) |
| cyclelayouts       | Cycles through all avaiable layouts using `MOD-CTRL-,` and `MOD-CTRL-.`.                           | [source](https://dwm.suckless.org/patches/cyclelayouts/)       |
| fibonacci          | This patch adds new layout that arranges all windows in Fibonacci tiles.                           | [source](https://dwm.suckless.org/patches/fibonacci/)          |

## Branches

- `main` = master + patches + config
- `master` - copy of `https://git.suckless.org/dwm`
- `patch-\*` - patch applied to master
