# dz60

## Features

| Output                                                                              | Input                                                                                      |
| :---------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------- |
| Arrows (:arrow_up_small: / :arrow_forward: / :arrow_down_small: / :arrow_backward:) | <kbd>Right Shift</kbd> / <kbd>Right Control</kbd> / <kbd>Menu</kbd> / <kbd>Right Alt</kbd> |
| Esc                                                                                 | <kbd>Caps Lock</kbd> + <kbd>Esc</kbd>                                                      |
| F1 ~ F12                                                                            | <kbd>Caps Lock</kbd> + <kbd>1</kbd> ~ <kbd>12</kbd>                                        |
| RGB Toggle                                                                          | <kbd>Caps Lock</kbd> + <kbd>R</kbd>                                                        |

## Requirements

| Name                                              | Download from                                                        |
| :------------------------------------------------ | :------------------------------------------------------------------- |
| [QMK Toolbox](https://github.com/qmk/qmk_toolbox) | [qmk/qmk_toolbox](https://github.com/qmk/qmk_toolbox)                |
| [VIA](https://caniusevia.com/)                    | [the-via/releases](https://github.com/the-via/releases)              |
| `dz60_via.hex`                                    | [Firmware Downloads](https://caniusevia.com/docs/download_firmware/) |

## Usage

### Flash firmware

- Launch QMK Toolbox
- Clear EEPROM
- Open `dz60_via.hex`
- Flash

### Load keymap

- Launch VIA
- Load [via.json](./via.json)
