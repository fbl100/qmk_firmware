# Input Club ErgoDox Infinity Layout

Adapted from https://configure.ergodox-ez.com/ergodox-ez/layouts/ZqR6/latest/0

## Features

Base Layers

- QWERTY
- Function Keys
- Numpad

## Building and flashing

1. Put your board in DFU mode with either the button on the bottom, or with a software key in your current firmware
2. Flash left half:
    ```bash
    make ergodox_infinity:hacker:dfu-util
    ```
3. Flash right half:
    ```bash
    make ergodox_infinity:hacker:dfu-util MASTER=right
    ```
