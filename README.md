# BPS-MinionShieldPCB
Author: Champers Fu

This board sits on top of the minionshield to interface with the temperature sensors. 
The board provides a low pass filter between the thermistors and the LTC6811 input. 


## BOM
[**Interactive BOM (Must download and open in browser)**](ibom.html)

[**Mouser Cart**](https://www.mouser.com/ProjectManager/ProjectDetail.aspx?AccessID=0a4c326737)
Note: The PADP-24V-1-S connector is not available on mouser, but may be purchased through [**digikey**](https://www.digikey.com/en/products/detail/jst-sales-america-inc/PADP-24V-1-S/1300227)

## Connectors
| Reference | Name | Type | Pin 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | Notes |
| - | - | - | - | - | - | - | - | - | - | - | - | - | - |
| J1 | MinionPCB Connector | 1x10xP2.54mm Male | 5V | TempSensor1 | TempSensor2 | TempSensor3 | TempSensor4 | TempSensor5 | TempSensor6 | TempSensor7 | TempSensor8 | GND |
| J2 | MinionPCB Connector | 1x10xP2.54mm Male | 5V | TempSensor9 | TempSensor10 | TempSensor11 | TempSensor12 | TempSensor13 | TempSensor14 | TempSensor15 | TempSensor16 | GND |
| J3 | Thermistors | PADP-24V-1-S | See Schematic | | | | | | | | | | |

## PCB
[**PDF without traces**](PCB.pdf)
![image](https://github.com/lhr-solar/BPS-MinionShieldPCB/blob/standardization2/PCB.pdf)

## Schematic
[**PDF with all sheets**](Schematic.pdf)
![image](https://github.com/lhr-solar/BPS-MinionShieldPCB/blob/standardization2/Schematic.pdf)
