# How to use
This is my KICAD library, including symbols, footprints and 3d models. The folder `3dmodels` is a submodule, so after cloning this repository, use the command:

```sh
git submodule init
git submodule update
```
This will fetch the data from the submodule.

The folder `template` provides templates for different PCB manufacturers based on their capabilities.

In the KICAD *Config Path* settings, add the path environment varibles (`**` is the where you place this repository):
| **Variable Name**         | **Path**                      |
| :------------------------ | :---------------------------- |
| `USER_LIB_DIR`            | `**\kicad-user-lib\`          |
| `USER_3DMODEL_DIR`        | `**\kicad-user-lib\3dmodels\` |
| `KICAD_USER_TEMPLATE_DIR` | `**\kicad-user-lib\template\` |

## Resistor
Footprint design based on Samsung Electronics resistors. 
reference: https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/39/RC_Series_ds.pdf

| **File Name**   | **Description**   |
| :-------------- | :---------------- |
| R_SMD_0402.step | SMD Resistor 0402 |
| R_SMD_0603.step | SMD Resistor 0603 |
| R_SMD_0805.step | SMD Resistor 0805 |
| R_SMD_1206.step | SMD Resistor 1206 |
| R_SMD_2512.step | SMD Resistor 2512 |

## Capacitor
Footprint design based on Murata capacitors.
reference: https://search.murata.co.jp/Ceramy/image/img/A01X/G101/ENG/GRM155R71C103KA01-01.pdf

| **File Name**   | **Description**    |
| :-------------- | :----------------- |
| C_SMD_0402.step | SMD Capacitor 0402 |
| C_SMD_0603.step | SMD Capacitor 0603 |
| C_SMD_0805.step | SMD Capacitor 0805 |

## Diodes, LEDs

| **File Name**     | **Description** |
| :---------------- | :-------------- |
| LED_SMD_0402.step | SMD LED 0402    |
| LED_SMD_0603.step | SMD LED 0603    |

## MCU

| **File Name**  | **Description**                                                                            |
| :------------- | :----------------------------------------------------------------------------------------- |
| STM32F103C8T6  | ARM® Cortex®-M3 STM32F1 Microcontroller IC 32-Bit Single-Core 72MHz 64KB (64K x 8) FLASH   |
| CYUSB3065-BZXI | USB SuperSpeed Peripherals, 2/4-Lanes MIPI CSI-2, GPIO, I2C, SPI, I2S, UART, BGA-121, RoHS |
| USB5744        | USB Hub Controller USB 2.0, USB 3.2 USB Interface 56-VQFN (7x7)                            |

## Regulator

| **File Name**       | **Description**                                                     |
| :------------------ | :------------------------------------------------------------------ |
| LM1117IMPX-3.3/NOPB | Linear Voltage Regulator IC Positive Fixed 1 Output 800mA SOT-223-4 |

## Crystals, Oscillators, Resonators

| **File Name**         | **Description**                                                                    |
| :-------------------- | :--------------------------------------------------------------------------------- |
| ECS-80-12-33-JGN-TR   | 8 MHz ±20ppm Crystal 12pF 400 Ohms 4-SMD, No Lead                                  |
| ECS-327MVATX-2-CN-TR3 | 32.768 kHz XO (Standard) CMOS Oscillator 1.6V ~ 3.6V Enable/Disable 4-SMD, No Lead |

## Connector

| **File Name** | **Description**                                                                                                                             |
| :------------ | :------------------------------------------------------------------------------------------------------------------------------------------ |
| GSB343K331HR  | USB - micro B USB 3.2 Gen 1 (USB 3.1 Gen 1, Superspeed (USB 3.0)) Receptacle Connector 10 Position Surface Mount, Right Angle; Through Hole |
| USB4105-GF-A  | USB-C (USB TYPE-C) USB 2.0 Receptacle Connector 24 (16+8 Dummy) Position Surface Mount, Right Angle; Through Hole                           |
