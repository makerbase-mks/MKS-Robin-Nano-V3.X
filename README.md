# MKS-Robin-Nano-V3.X
Robin nano V3 is an upgraded version of [Robin Nano V2.0](https://github.com/makerbase-mks/MKS-Robin-Nano-V2.X). The upgrade changes are quite large, including upgrading the MCU to the M4 core, and adding support for USB disk.

## Related tutorials and Notice
- User Manual.[click here](https://github.com/makerbase-mks/MKS-Robin-Nano-V3.X/wiki)
- Welcome to follow us on Facebook to learn about the company's latest developments.[click here](https://www.facebook.com/Makerbase.mks/)

## How to buy
- [Amazon link](https://www.amazon.com/s?me=A25AM6LC3BZ7LE&marketplaceID=ATVPDKIKX0DER)

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
| EEPROM | *4KB*	| *4KB*	 |
| SPI Flash | *8M*	| *8M*	|
| LCD support | *MKS TS35/MKS H43/MKS MINI12864 V3/LCD12864/LCD2004* |*MKS TS35/MKS H43/MKS MINI12864 V3/LCD12864/LCD2004* |
| Firmware | Marlin 2.0.x, Klipper | Marlin 2.0.x, Klipper, Reprap firmware(MKS version) |

**Note**: As MKS Robin Nano V2.0 doesn't has an independent serial port, so if using with the MKS H43, V2.0 cannot work with Wifi module, but V3.0 can make it.

## Hardware
The hardware design is openned source on : https://github.com/makerbase-mks/MKS-Robin-Nano-V3.X/tree/main/hardware

## Firmware
The factory firmware of Nano V3 is based on Marlin 2.x, actually, we directly use the same respository of Nano V1.2/2.0:https://github.com/makerbase-mks/Mks-Robin-Nano-Marlin2.0-Firmware. Just modify the type of motherboard to compile the related firmware.

Now Nano V3 also supports RepRapFirmware (RRF). For details, please refer to:https://github.com/makerbase-mks/RepRapFirmware-for-MKS-Boards

Nano V3 has supported klipper firmware. For details, please refer to:https://github.com/makerbase-mks/Klipper-for-MKS-Boards

## Note
- Thank you for using MKS products. If you have any questions during use, please contact us in time and we will work with you to solve it.
- For more product dynamic information and tutorial materials, you can always follow MKS's Facebook/Twitter/Discord/Reddit/Youtube and Github. Thank you!
- MKS Github: https://github.com/makerbase-mks  
- MKS Facebook: https://www.facebook.com/Makerbase.mks/  
- MKS Twitter: https://twitter.com/home?lang=en  
- MKS Discord: https://discord.gg/4uar57NEyU
- MKS Reddit: https://www.reddit.com/user/MAKERBASE-TEAM/ 

![mks_link](https://user-images.githubusercontent.com/12979070/149611647-1819afd8-0241-42ec-8817-41a290827f0a.png)


