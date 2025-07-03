# How to use

This is my KICAD library, including symbols, footprints and 3d models. The folder `3dmodels` is a submodule, so after cloning this repository, use the command:

```sh
git submodule init
git submodule update
```

This will fetch the data from the submodule.

The folder `template` provides templates for different PCB manufacturers based on their capabilities.

In the KICAD _Config Path_ settings, add the path environment varibles (`**` is the where you place this repository):
| **Variable Name** | **Path** |
| :------------------------ | :---------------------------- |
| `USER_LIB_DIR` | `**\kicad-user-lib\` |
| `USER_3DMODEL_DIR` | `**\kicad-user-lib\3dmodels\` |
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

| **File Name**                 | **Description**  |
| :---------------------------- | :--------------- |
| LED_SMD_0402.step             | SMD LED 0402     |
| LED_SMD_0603.step             | SMD LED 0603     |
| UHD111A-FKA-C3K23E1L3VG5ZB3Z3 | LED RGB 0404 SMD |

## MCU

| **File Name**  | **Description**                                                                                |
| :------------- | :--------------------------------------------------------------------------------------------- |
| STM32F103C8T6  | ARM® Cortex®-M3 STM32F1 Microcontroller IC 32-Bit Single-Core 72MHz 64KB (64K x 8) FLASH       |
| STM32U5G9ZJJ6Q | ARM® Cortex®-M33 STM32U5 Microcontroller IC 32-Bit 160MHz 4MB (4M x 8) FLASH 144-UFBGA (10x10) |
| CYUSB3065-BZXI | USB SuperSpeed Peripherals, 2/4-Lanes MIPI CSI-2, GPIO, I2C, SPI, I2S, UART, BGA-121, RoHS     |
| USB5744        | USB Hub Controller USB 2.0, USB 3.2 USB Interface 56-VQFN (7x7)                                |

## Regulator

| **File Name**       | **Description**                                                                 |
| :------------------ | :------------------------------------------------------------------------------ |
| LM1117IMPX-3.3/NOPB | Linear Voltage Regulator IC Positive Fixed 1 Output 800mA SOT-223-4             |
| AMS1117-3.3V        | LDO Fixed 3.3V Output 1A SOT-89                                                 |
| TLV62569ADRLR       | Buck Switching Regulator IC Positive Adjustable 0.6V Output 2A SOT-563, SOT-666 |

## Crystals, Oscillators, Resonators

| **File Name**          | **Description**                                                                    |
| :--------------------- | :--------------------------------------------------------------------------------- |
| ECS-80-12-33-JGN-TR    | 8 MHz ±20ppm Crystal 12pF 400 Ohms 4-SMD, No Lead                                  |
| ECS-327MVATX-2-CN-TR3  | 32.768 kHz XO (Standard) CMOS Oscillator 1.6V ~ 3.6V Enable/Disable 4-SMD, No Lead |
| ECS-.327-12.5-34B-TR   | 32.768 kHz ±20ppm Crystal 12.5pF 70 kOhms 2-SMD, No Lead                           |
| ECS-2520MVLC-192-BN-TR | 19.2 MHz XO (Standard) CMOS Oscillator 1.6V ~ 3.6V Enable/Disable 4-SMD, No Lead   |

## Connector

| **File Name**             | **Description**                                                                                                                                    |
| :------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| GSB343K331HR              | USB - micro B USB 3.2 Gen 1 (USB 3.1 Gen 1, Superspeed (USB 3.0)) Receptacle Connector 10 Position Surface Mount, Right Angle; Through Hole        |
| USB4105-GF-A              | USB-C (USB TYPE-C) USB 2.0 Receptacle Connector 24 (16+8 Dummy) Position Surface Mount, Right Angle; Through Hole                                  |
| USB4056-03-A              | USB-C (USB TYPE-C) USB 3.2 Gen 2 (USB 3.1 Gen 2, Superspeed + (USB 3.1)) Receptacle Connector 24 Position Surface Mount, Right Angle; Through Hole |
| 10152803-00011LF          | USB-C (USB TYPE-C) USB 3.2 Gen 2 (USB 3.1 Gen 2, Superspeed + (USB 3.1)) Receptacle Connector 24 Position Surface Mount, Right Angle               |
| DF12NB(5.0)-40DP-0.5V(51) | 40 Position Connector Header                                                                                                                       |
| DF12NB-40DS-0.5V(51)      | 40 Position Connector Header                                                                                                                       |
| BM06B-NSHSS-TBT           | Connector Header Surface Mount 6 position 0.039" (1.00mm)                                                                                          |

## Switches

| **File Name**        | **Description**                                |
| :------------------- | :--------------------------------------------- |
| PTS810SJM250SMTR LFS | SMD Tactile Switch SPST-NO, 4 Pin, 4.2 x 3.2mm |

## Misc

| **File Name**                    | **Description**                                                             |
| :------------------------------- | :-------------------------------------------------------------------------- |
| Castellated_PinHeader_xxx_2.54mm | 邮票孔 2.54mm 间距                                                          |
| Jumper_SMD_xxx                   | SMD Solder Jumper                                                           |
| PI5USB30213AXEAEX                | USB3.0 bi-directional MUX, (NRND)                                           |
| TPD4E05U06DQAR                   | ESD Suppressors / TVS Diodes 4Chnl U-Lo Capacitnc IEC ESD Prot Diodes       |
| TPD2E2U06DRLR                    | TVS DIODE 5.5VWM 12.4VC SOT5                                                |
| SN74AHC1G32DRLR                  | OR Gate IC 1 Channel SOT-5                                                  |
| W25Q16JVSSIM                     | IC FLASH 16MBIT SPI/QUAD 8SOIC                                              |
| TCA9801DGKT                      | Voltage Level Translator Bidirectional 1 Circuit 2 Channel 8-VSSOP          |
| NCP360SNT1G                      | USB Interface IC USB OVP SUPERVISORY                                        |
| SN74LVC2G17DBVR                  | Buffer, Non-Inverting 2 Element 1 Bit per Element Push-Pull Output SOT-23-6 |
| HD3SS3220RNHR                    | USB3.0 bi-directional MUX, CC controller                                    |
