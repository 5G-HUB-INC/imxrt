# IMXRT1062
The IMXRT1062 Evaluation Kit (EVK) is a powerful EVK based on NXP IMXRT1062 CPU. The EVK comes equiped with miniPCIe and M.2 socket inetrface to be used with cellular and GPS modems

The board supports Windows 7/8/8.1/10, Linux and Android.

The EVK board is a rich board that can be used for a variety of smart and 5G applications. It enables applications such as wireless POS, smart metering, tracking, smart transportation, smart buildings, smart city, and smart homes, navigation, location, and tracking. 

# Arduino IDE Compatibility
This Repository is compatible with:

* Arduino IDE 2.3.10
* Arduino IDE 2.1.1

# Software and Tools Included with the Board
-Bootloader: Contains *.hex file to flash tot he IMXRT board to work as Arduino-compatible.

-imxrt-Core.zip: Contains the board manager (used with Arduino IDE).

-IMXRT1062_Arduino.zip: Contains the library (used with Arduino IDE).

-Kit sketches: Folder contains more Arduino sketches for sensors and hardwrae devices

-SerialFlash: Contains File system for the Flash memory

-u-blox_GNSS: Contains examples for using the u-blox SAM-M8Q GNSS module

# How to Use Arduino IDE with the Board

1.	Install Arduino IDE for Windows from the following web site:
https://www.arduino.cc/en/Main/Software

2.	Launch Arduino IDE and choose File->Preferences. In the Additional Boards Manager URLs, insert the following URL:
https://raw.githubusercontent.com/5ghub/imxrt/main/package_IMXRT1062_index.json

3.	In Arduino IDE, choose Tools->Board->Boards Manager and install “IMXRT1062 (NXP 32-bits ARM Cortex-M7) Boards”.

4.	Choose “IMXRT1062”

5. In the Arduino IDE, Choose Sketch->Include Library->Add .Zip Library and select the file IMXRT1062_Arduino.zip 

6.	You are ready now to use the Arduino IDE and write the first sketch.
