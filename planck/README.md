# Planck Layout
My Planck keyboard layout and the environment to flash it with QMK firmware (tested on commit c11a26ba5 of firmware repo)

## How to enter Boot Mode:
Press `RAISE` and `LOWER` keys + secord key from top row

## Instructions to flash keyboard:
1. [Setup windows environment](https://docs.qmk.fm/#/newbs_getting_started)
2. Copy user keymaps: `cp ~/projects/qmk_keymaps/corne/dpitty ~/qmk_firmware/keyboards/crkbd/keymaps/dpitty`
3. From qmk msys, run `qmk compile -kb planck/rev3 -km dpitty`
4. Open QMK Toolbox
5. Enter Boot Mode on keyboard with RESET key on layout (see section above)
6. Flash keyboard

## Notes:
Keycodes are available here: https://github.com/qmk/qmk_firmware/blob/master/docs/keycodes.md
