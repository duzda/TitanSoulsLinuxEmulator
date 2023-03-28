# Titan Souls Linux Emulator
Bothered by how awful the game's keyboard support is? And where's the mouse support?  
This program solves all your problems!

Feel free to [grab the binary from the downloads](https://github.com/duzda/TitanSoulsLinuxEmulator/releases)!

## Usage

sudo ./emulator --keyboard="PATH" --mouse="PATH" -s8

"PATH" -> The path to the keyboard and mouse (should look something like /dev/input/eventX)

To exit the app, just send CTRL+C to the terminal or press Q followed by Enter.

## Keybinds
| Option | Description | Value |
| :---: | :---: | :---: |
| Up | Move up | W |
| Down | Move down | S |
| Left | Move left | A |
| Right | Move right | D |
| Roll | Press to roll <br> Hold to run | Left Shift |
| Fire | Hold to aim with mouse, release to fire <br> Hold to call arrow | Left Mouse |
| Camera | Hold to move camera with mouse | Right Mouse |
| Change Sensitivity | Changes mouse sensitivity between 1-15 | Mouse Wheel or PgUp/PgDn |

## Build

gcc emulator.c -o emulator


## Credits

Massive thanks to the original projects:

https://github.com/niehoff90/ControllerEmulator  
https://github.com/CommanderRag/xbox-controller-emulator-linux  
https://github.com/martinsomer/Titan-Souls-Keyboard