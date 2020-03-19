# MKS-TFT
If you want to change some function or add new function and so on, you can refer to MKS TFT source code and build it, update it to MKS TFT, Link as below:
- MKS TFT24 Source code.[click here](https://github.com/makerbase-mks/MKS-TFT24-Firmware)
- MKS TFT28/32 Soucrce code.[click here](https://github.com/makerbase-mks/MKS-TFT28-32-Firmware)
- MKS TFT35 Source code.[click here](https://github.com/makerbase-mks/MKS-TFT35-Firmware)
- MKS TFT70 Source code.[click here](https://github.com/makerbase-mks/MKS-TFT70-Firmware)

1.  Attentions

  1.1 MKS TFT includes TFT2.4, TFT3.5,TFT2.8，TFT3.2,MKS-TFT_CNC and TFT7.0.
  
  1.2 Since TFT7.0 and TFT3.5 is standalone version, the following are TFT2.4, 2.8, and 3.2

  1.3 If using MKS TFT_WIFI module, it’s necessary to upgrade the WIFI firmware. 

  1.4 The file name must not be changed when upgrading the firmware, otherwise, upgrading fails.

2.  Firmware options

MKS TFT2.4: mkstft24.bin
  
MKS TFT2.8/3.2：mkstft28.bin
  
3.  Release Notes

  MKS -TFT Firmware version description

V1.1.3

  1.Fixed the problem that TFT can't not communicate with mainboard after firmware or baud rate updates.

  2.Fixed error bug of More Menu .

V1.1.4

  1.Available to set the Max temp of extruder and bed on config.

  2.Available to set value to trigger filament monitoring(high/low leveling).

  3.Fixed U dish frozen BUG.

  4.Bed leveling icon does not display by default.

V1.1.5

  1.Available to set 'Auto Off After Printing Finishes' function on config. And display it inside 'More' interface.

V1.2.0

  1.Improved display speed and screen touching, faster and more sensitive.

  2.Available to switch title languages,including simplified Chinese,Chinese traditional,English.

  3.Fixed info error of wifi display.

  4.Fixed display error,that can't find sd card or u disk after reboots.

  5.Support manual leveling and filament change.

  6.Added "More" icon on printing operation interface for user-defined.

  7.Deleted screen calibration function.

V2.0.0

  1.Updated screen interface,added 3 different home pages for 3 different firmwares.

  2.Added 'print from breakpoint' function.(Continue button).

  3.Deleted Baud Rate 'connect' button,but available to set it on config.

  4.Updated leveling interface.

  5.Fixed E position error after printing pause and filament change.

V2.0.1

  1.Fixed the socket of “auto-off after printing”.

  2.Available to choose “manual leveling” or “auto-leveling”.

  3.Compatible with “MKS TFT-WIFI” , “MKS HLK-WIFI” and the latest version phone APP “MKSCloud”.

  4.Added “cloud service” and “mobile transfer files” functions.

  5.Added Windows style.

V3.0.0

  1.Added multi-language, available to switch 5 languages on line.

  2.Fixed “WIFI transfer” problems.

  3.Optimized the “filament replacement” function.
  
V3.0.1

  1.Add configuration variables to the mks_config.txt file: >cfg_leveling_z_high
  
  2.Fixed the problem of screen display.
 
V3.0.2

  1.the content of V3.0.2 firmware modification(2018/05/05)
  
    (1).Add the "M-off" button to the "Home" interface
    
    (2).We changed default temperature 180 to 0 in the "Preheat" interface
    
    (3).Add the function of display mainboard eeror
    
    (4).in the fan inerface,press the "+" or "-",the fan work
    
    (5).fixed the bug of  click "more" restart  
    
    (6).The board will stop operating more than 5 times when using the M110 re-instruction command
    
    (7).Increase the configuration item to shield power failure detection function
    
    (8).Modify the bug that serial port interrupt sending will be interrupted
    
    (9).Modify the bug of read failure in U disk or SD card printing
    
    (10).Increase configuration items to support dual extruder single nozzle.
    
    (11).Add a button in the WIFI interface to control wifi module  function open or close
    
    (12).Fixed bug that the simple version and the retro version manual leveling wasn't go home
    
    (13).Wifi firmware was fixed bug that function incorrect when password less than 8 digits 
  
V3.03

  1.the content of V3.0.3 firmware modification(2018/10/23)
    
    (1).Bootloader display can be rotated 180°.
    
    (2).Add configuration items to block error reporting.
    
    (3).Manually add temperature function when power failure is not saved to the extrusion head temperature.
    
    (4).Add configuration item:the length and speed of Load filament before unloader filament. 
    
    (5).Add a prompt box when the material is paused at the beginning of printing.
    
    (6).Fix bug: When the break detection is configured as a high level trigger, no loading can resume printing.
    
    (7).Add configuration item: You can choose whether to configure the M110 command for different Marlin versions.
    
    (8).Fix bug of print stop.
    
    (9).Adjust the position of the Z axis before X and Y move when manually leveling.
    
V3.04

    (1).Added babystep adjustment buttons to the "More" screen during printing.
      
V3.05

    (1).Fix the problem that the babystep adjustment value is too large.
    
    
    
