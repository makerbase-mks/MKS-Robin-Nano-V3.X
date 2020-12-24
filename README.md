# MKS-Robin-Nano-V3.X
Robin nano V3 is an upgraded version of [Robin Nano V2.0](https://github.com/makerbase-mks/MKS-Robin-Nano-V2.X). The upgrade changes are quite large, including upgrading the MCU to the M4 core, and adding support for U disks.

## Compare between Robin Nano V2.0 and V3.0
| ITEMS      |  Robin Nano V2.0  | Robin Nano V3.0 |
|------------|--------------------|--------------------|
| MCU        | STM32F103VET6(72MHz) | STM32F407VGT6（168MHz）|
| FLASH/RAM | 512KB FLASH/64KB RAM | 1024KB FLASH/192KB RAM |
| USB Disk | Not support |  Support |
| TF card | Support(SDIO) |  Support(SPI3) |
| WIFI connect |	USART1	| USART1+SPI2 |
| Virtural USB Device|  Not support |  Support |
| Motor interface| 5 axis | 6 axis(Two Z axis share the same driver)|
| PWM FAN(s) | 1 channel | 2 channels |
| PWM TTL | Not Support |  Support|
| Independent serial port | Not support | Support(UART3) |
| Power TVS protect |	No | Yes |
| Expansion SD slot | Support | Not support |
| MAX31855 interface | Support | Not support |
| EEPROM | *4KB AT24C32DM*	| *4KB AT24C32DM*	 |
| SPI Flash | *8M W25Q64JVSIQ*	| *8M W25Q64JVSIQ*	|
| LCD support | *MKS TS35/MKS H43\*/LCD12864/LCD2004* |*MKS TS35/MKS H43/LCD12864/LCD2004* |

*Note: As MKS Robin Nano V2.0 doesn't has an independent serial port, so if using with the MKS H43, V2.0 cannot work with Wifi module, but V3.0 can make it.

## Hardware
The hardware design is openned source on : https://github.com/makerbase-mks/MKS-Robin-Nano-V3.X/tree/main/hardware

## Firmware
The same as the Robin Nano V2.0, firmware of MKS Robin Nano V3.0 is also based on Marlin 2.X. Actually, we directly use the same respository:https://github.com/makerbase-mks/Mks-Robin-Nano-Marlin2.0-Firmware. Just modify the type of motherboard to compile the related firmware.

### How to build


