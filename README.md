# How to use
This is my KICAD library, including symbols, footprints and 3d models. The folder `3dmodels` is a submodule, so after cloning this repository, use the command:

```sh
git submodule init
git submodule update
```
This will fetch the data from the submodule.

The folder `template` provides templates for different PCB manufacturers based on their capabilities.

## Resistor

| **File Name**   | **Description** |
| :-------------- | :-------------- |
| R_SMD_0402.step | SMD 0402        |
| R_SMD_0603.step | SMD 0603        |
| R_SMD_0805.step | SMD 0805        |
| R_SMD_1206.step | SMD 1206        |
| R_SMD_2512.step | SMD 2512        |

## MCU

| **File Name**  | **Description**                                                                            |
| :------------- | :----------------------------------------------------------------------------------------- |
| STM32F103C8T6  | ARM® Cortex®-M3 STM32F1 Microcontroller IC 32-Bit Single-Core 72MHz 64KB (64K x 8) FLASH   |
| CYUSB3065-BZXI | USB SuperSpeed Peripherals, 2/4-Lanes MIPI CSI-2, GPIO, I2C, SPI, I2S, UART, BGA-121, RoHS |

## Regulator

| **File Name**       | **Description**                                                     |
| :------------------ | :------------------------------------------------------------------ |
| LM1117IMPX-3.3/NOPB | Linear Voltage Regulator IC Positive Fixed 1 Output 800mA SOT-223-4 |

## Connector

| **File Name** | **Description**                                                                                                                             |
| :------------ | :------------------------------------------------------------------------------------------------------------------------------------------ |
| GSB343K331HR  | USB - micro B USB 3.2 Gen 1 (USB 3.1 Gen 1, Superspeed (USB 3.0)) Receptacle Connector 10 Position Surface Mount, Right Angle; Through Hole |