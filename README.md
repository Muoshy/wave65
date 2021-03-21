![top](https://raw.githubusercontent.com/Muoshy/wave65/main/img/front.jpg)

# wave65
discipline65 inspired keyboard

  - QMK firmware
  - Acrylic sandwich case
  - Encoder support
  - VIA-configurable
  
## Schematic
Standard ATMega32u4 setup with Wurth/Amphenol USB-C connector
![sch](https://raw.githubusercontent.com/Muoshy/wave65/main/img/MCU_schem.png)


## PCB
![pcb](https://raw.githubusercontent.com/Muoshy/wave65/main/img/pcb.jpg)

## Case
WIP

## Software
Running on QMK firmware. Use QMK Toolbox to flash with provided HEX file.
Then use VIA configurator to configure keybinds.
For further customization (encoder keycodes), setup a QMK build environment and compile your own HEX files.

## Flashing
  - Download and open QMK Toolbox
  - Select HEX file
  - Choose ATMega32u4 as microcontroller
  - Push reset button on board and then press flash button in toolbox.

## Keybinds
  - Download and install VIA Configurator
  - Open VIA and go to File->Import Keymap
  - Select the keymap.json file
  - Plug in the keyboard
  

## BOM
WIP