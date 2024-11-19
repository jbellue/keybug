# Keybug - a small 5-keys macro keypad

It was initially designed to handle a debugger (Start/Stop/Step Into/Step Out/Step).

It runs [RMK](https://github.com/HaoboGu/rmk) (free vial!), but will be extremely simple to add to QMK. I might do that someday.

## Default Keymap

Here it is with the default keys to debug on IntelliJ:

```text
╭──────┬──────┬──────┬──────┬──────╮
│ Ctrl │  F9  │  F8  │  F7  │ Shft │
│  F2  │      │      │      │  F8  │
╰──────┴──────┴──────┴──────┴──────╯
```

## Remapping

Remapping is done through [Vial](https://vial.rocks/) on a browser supporting WedHID (i.e. Chrome).

Due to the way RMK works, reflashing probably doesn't update the keymap.
