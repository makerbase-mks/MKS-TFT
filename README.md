# MKS-TFT
## We has open all MKS TFT source code and schematic ...
## Source code
If you want to change some function or add new function and so on, you can refer to MKS TFT source code and build it, update it to MKS TFT, Link as below:
- MKS TFT24 Source code.[click here](https://github.com/makerbase-mks/MKS-TFT24-Firmware)    
- MKS TFT28/32 Soucrce code.[click here](https://github.com/makerbase-mks/MKS-TFT28-32-Firmware)        
- MKS TFT35 Source code.[click here](https://github.com/makerbase-mks/MKS-TFT35-Firmware)    
- MKS TFT70 Source code.[click here](https://github.com/makerbase-mks/MKS-TFT70-Firmware)    

## Hardware
You can check morn info about MKS TFT. For example, size, layout, Schematic and so on. Link as below:
- MKS TFT24 Hardware[click here](https://github.com/makerbase-mks/MKS-TFT24)
- MKS TFT28 Hardware[click here](https://github.com/makerbase-mks/MKS-TFT28)
- MKS TFT32 Hardware[click here](https://github.com/makerbase-mks/MKS-TFT32)
- MKS TFT35 Hardware[click here](https://github.com/makerbase-mks/MKS-TFT35)
- MKS TFT70 Hardware[click here](https://github.com/makerbase-mks/MKS-TFT70)

# Related tutorials and Notice
- User Manual.[click here]()
- Thank you very much for DenisShelema's UI theme.[click here](https://github.com/DenisShelema/MKS-TFT3.5-light-and-dark-themes)
- Welcome to follow us on Facebook to learn about the company's latest developments.[click here](https://www.facebook.com/Makerbase.mks/)

# Firmware version description
## Attentions
- MKS TFT includes TFT2.4, TFT3.5,TFT2.8，TFT3.2,MKS-TFT_CNC and TFT7.0.
- Since TFT7.0 and TFT3.5 is standalone version, the following are TFT2.4, 2.8, and 3.2
- If using MKS TFT_WIFI module, it’s necessary to upgrade the WIFI firmware. 
- The file name must not be changed when upgrading the firmware, otherwise, upgrading fails.

## Release Firmware version description
- MKS TFT24: mkstft24.bin 
- MKS TFT28/32：mkstft28.bin
- MKS TFT35：mkstft35.bin
- MKS TFT70：mkstft70.bin

### V3.05
 - Fix the problem that the babystep adjustment value is too large.
    
### V3.04
  - Added babystep adjustment buttons to the "More" screen during printing.
    
### V3.03
the content of V3.0.3 firmware modification(2018/10/23)
  - Bootloader display can be rotated 180°. 
  - Add configuration items to block error reporting.
  - Manually add temperature function when power failure is not saved to the extrusion head temperature.
  - Add configuration item:the length and speed of Load filament before unloader filament. 
  - Add a prompt box when the material is paused at the beginning of printing.
  - Fix bug: When the break detection is configured as a high level trigger, no loading can resume printing.
  - Add configuration item: You can choose whether to configure the M110 command for different Marlin versions.
  - Fix bug of print stop.
  - Adjust the position of the Z axis before X and Y move when manually leveling.
  
### V3.0.2
the content of V3.0.2 firmware modification(2018/05/05)
  - Add the "M-off" button to the "Home" interface
  - We changed default temperature 180 to 0 in the "Preheat" interface
  - Add the function of display mainboard eeror
  - in the fan inerface,press the "+" or "-",the fan work
  - fixed the bug of  click "more" restart  
  - The board will stop operating more than 5 times when using the M110 re-instruction command
  - Increase the configuration item to shield power failure detection function
  - Modify the bug that serial port interrupt sending will be interrupted
  - Modify the bug of read failure in U disk or SD card printing
  - Increase configuration items to support dual extruder single nozzle.
  - Add a button in the WIFI interface to control wifi module  function open or close
  - Fixed bug that the simple version and the retro version manual leveling wasn't go home
  - Wifi firmware was fixed bug that function incorrect when password less than 8 digits 
  
### V3.0.1
  - Add configuration variables to the mks_config.txt file: >cfg_leveling_z_high
  - Fixed the problem of screen display.
  
### V3.0.0
  - Added multi-language, available to switch 5 languages on line.
  - Fixed “WIFI transfer” problems.
  - Optimized the “filament replacement” function.
  
### V2.0.1
  - Fixed the socket of “auto-off after printing”.
  - Available to choose “manual leveling” or “auto-leveling”.
  -Compatible with “MKS TFT-WIFI” , “MKS HLK-WIFI” and the latest version phone APP “MKSCloud”.
  - Added “cloud service” and “mobile transfer files” functions.
  - Added Windows style.
  
### V2.0.0
  - Updated screen interface,added 3 different home pages for 3 different firmwares.
  - Added 'print from breakpoint' function.(Continue button).
  - Deleted Baud Rate 'connect' button,but available to set it on config.
  - Updated leveling interface.
  - Fixed E position error after printing pause and filament change.

### V1.2.0
  - Improved display speed and screen touching, faster and more sensitive.
  - Available to switch title languages,including simplified Chinese,Chinese traditional,English.
  - Fixed info error of wifi display.
  - Support manual leveling and filament change.
  - Added "More" icon on printing operation interface for user-defined.
  - Deleted screen calibration function.

### V1.1.5
  - Available to set 'Auto Off After Printing Finishes' function on config. And display it inside 'More' interface.

### V1.1.4
  - Available to set the Max temp of extruder and bed on config.
  - Available to set value to trigger filament monitoring(high/low leveling).
  - Fixed U dish frozen BUG.
  - Bed leveling icon does not display by default.

### V1.1.3
  - Fixed the problem that TFT can't not communicate with mainboard after firmware or baud rate updates.
  - Fixed error bug of More Menu .
    
# Note
- Thank you for using MKS products. If you have any questions during use, please contact us in time and we will work with you to solve it.
- For more product dynamic information and tutorial materials, you can always follow MKS's Facebook and GitHub and YouTube. Thank you!
![](https://github.com/makerbase-mks/MKS-Robin-Nano/blob/master/hardware/Image/MKS_FGA.png)
    
