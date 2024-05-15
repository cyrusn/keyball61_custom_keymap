# Keymap for keyball61

## Reference
- [keyball](https://github.com/Yowkees/keyball)
- [QMK](https://qmk.fm/)


## Config keyboard and keymap first
```sh
qmk config user.keyboard=keyball/keyball61
qmk config user.keymap=cyrusn
```

## Flash
``` sh
# in qmk_firmware path, run the following command to build and flash to keyboard

# to have a compile the firmware, use -c for clean build
qmk compile -c 
```

```sh
# to flash the firmware to keyboard
qmk flash -c 
```
