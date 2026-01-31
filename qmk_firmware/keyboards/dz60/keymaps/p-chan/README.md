# dz60

## Features

| Output                                                                           | Input                                                                                   |
| :------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------- |
| Arrows (:arrow_up_small:, :arrow_forward:, :arrow_down_small:, :arrow_backward:) | <kbd>Right Shift</kbd>, <kbd>Right Control</kbd>, <kbd>Menu</kbd>, <kbd>Right Alt</kbd> |
| Esc                                                                              | <kbd>Caps Lock</kbd> + <kbd>Esc</kbd>                                                   |
| F1 ~ F9                                                                          | <kbd>Caps Lock</kbd> + <kbd>1</kbd> ~ <kbd>9</kbd>                                      |
| F10                                                                              | <kbd>Caps Lock</kbd> + <kbd>0</kbd>                                                     |
| F11, F12                                                                         | <kbd>Caps Lock</kbd> + <kbd>-</kbd>, <kbd>Caps Lock</kbd> + <kbd>+</kbd>                |
| Globe                                                                            | <kbd>Caps Lock</kbd> + <kbd>Space</kbd>                                                 |
| RGB Toggle                                                                       | <kbd>Caps Lock</kbd> + <kbd>R</kbd>                                                     |

## Requirements

- [QMK CLI](https://docs.qmk.fm/cli)

## Usage

### Setup (one-time)

Create symlink to QMK firmware directory:

```sh
# Replace with your actual paths
ln -s /path/to/keyboards/qmk_firmware/keyboards/dz60/keymaps/p-chan /path/to/qmk_firmware/keyboards/dz60/keymaps/p-chan
```

### Build and Flash

```sh
qmk flash -kb dz60 -km p-chan
```
