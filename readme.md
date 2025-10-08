# This version of the PCB has been verified. To prevent malicious patent applications and reselling, the project's relevant source files will not be made available for open source at this time. Only relevant files sufficient for replication will be made available for open source.
 
# Flipper Zero ESP32 Marauder&NRF24&CC1101&L80-R 4 IN 1 board
[中文版本](readme_cn.md)
 
##  Flipper Zero ESP32 Marauder&NRF24&CC1101&L80-R 4 IN 1 board  Design documents
 
## Contents:
* /PCB - PCB gerber files - Daifresne （TSGP LAB）

* /BIN - BIN files - biebaowoyouci（Wanjia Technology）

* /STL - STL files - zjywlive
 
 
 
## License:
* The designs are licensed under the GNU GENERAL PUBLIC LICENSE v3.0 - Permissive. See the LICENSE file for details.
 
* The designs are provided as is, and zjywlive & TSGP LAB & Wanjia Technology are not responsible for any damage or injury that may result from using these designs.
 
* The open source license agreement allows private use, TSGP LAB retains the right to hardware-schematic & PCB design patents, Wanjia Technology retains the right to program design patents, and zjywlive retains the right to hardware-shell model design patents.Unauthorized commercial use of the design is not allowed.If you want to use the design for commercial purposes, please first understand the details with us.



## Replica Guide:
1. Please purchase the components listed in /pcb file/BOM_元件配单用——4in1 - TSGP LAB, then order /pcb file/Gerber_4in1.zip on the PCB manufacturer's ordering page. You can then solder the components according to the component numbers in the BOM.

2. After soldering the components on the PCB, find the firmware version you need in /bin file. The Chinese firmware is "4OR1.bin" and the English firmware is "4OR1_en.bin." Then use a USB-to-TTL programmer to connect the TTL port on the ESP-01F module to flash the firmware.

3. If you would like to use a case to protect the PCB, you can download the case model in /STL FILE, 3D print it, and then install it.



## Usage Guide:
After completing the above re-installation guide, you can use the USB-C port near the ESP32 S3 to flash your preferred firmware for use with the Flipper ZERO. ESP32 S3 firmware is not listed here. You can turn the module on and off using the button next to the OLED screen.
