# Tips & Tricks

## Keymaps

QMK can be used to flash the keyboard with a keymap. A full list of the keycodes you can use & their compabilitiy can be found [here](https://github.com/qmk/qmk_firmware/blob/master/docs/keycodes.md).

- QMK Keycodes: https://github.com/qmk/qmk_firmware/blob/master/docs/keycodes.md)

### Media Keys

Some of the media keys didn't work on Linux for me. Can use [playerctl](https://github.com/altdesktop/playerctl) to play, pause & skip. 
On my i3 setup I used [xev](https://linux.die.net/man/1/xev) to get the ID for the keystroke & used [bindcode to map it](https://i3wm.org/docs/userguide.html#keybindings).

- playerctl: https://github.com/altdesktop/playerctl
- xev: https://linux.die.net/man/1/xev
- i3 user guide: https://i3wm.org/docs/userguide.html#keybindings

### Mouse Keys

Use Mouse keys to use the cursor, click, scoll, etc.
- Mouse Keycodes: https://github.com/qmk/qmk_firmware/blob/master/docs/keycodes.md#mouse-keys-idmouse-keys