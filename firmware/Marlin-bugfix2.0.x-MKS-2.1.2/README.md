## MKS Robin Nano V3.x build and update firmware

1. Build config:
     
- platformio.ini: 
     
     default_envs = mks_robin_nano_v3_usb_flash_drive_msc
- Configuation.h:   
     #define SERIAL_PORT -1  
     #define MKS_TS35_V2_0  
     #define MOTHERBOARD BOARD_MKS_ROBIN_NANO_V3     
     #define TFT_LVGL_UI  
     #define TOUCH_SCREEN

- Configuation_adv.h:    
     Now you can either use the TF card or USB disk, use TF card:   
    // #define USB_FLASH_DRIVE_SUPPORT  
    Use USB disk:  
     #define USB_FLASH_DRIVE_SUPPORT  

2. Update firmware:
   
- Enter the `.pio\build\mks_robin_nano35` directory, copy the `assets` folder and `Robin_nano35.bin` to the sd card or usb disk
- Insert sdcard or usb disk to the motherboard, and you can see the update interface after power on.

## If you need to compile the firmware

- [Open the example configuration file](https://github.com/makerbase-mks/Mks-Robin-Nano-Marlin2.0-Firmware/tree/master/config/MKS%20Robin%20nano%20v3.0).
- Modify the parameters, replace configuration.h and configuration_adv.h in the Marlin path of the source code.
- Compile the firmware.




