## Latest update



[Update On The Project](https://www.youtube.com/watch?v=Y3GoYqw6YXA&list=PLBWrS0_J_mZ2AYpXI1URpqJv-m0bLa1Cb)



# Project

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Iso-Link is a control board that provides access to multiple industrial/automotive ports such as RS485, CAN, LIN, and DALI. The main propose of this board is to log line activites and or develope/implement new features to your system. It's possible to monitor and analyze the system for any troubleshooting purposes. In addition, the goal is to develop and eliminate the hassle of implmenting low level drivers and OS stack layer for industrial/automotive protocols. Here is a list of protocols that will be implemented in this project

|RS485|CANBus|LIN|DALI|I2C|
|:---|:---|:---|:---|:---|
|1. Modbus ASCII<br>2. Modbus RTU <br>3. Profibus DP <br>4. DNP3 <br>5. BACnet MS/TP<br>6. HART<br>7. IEC 61850<br>8. IEC 62056|1. CANOpen<br>2. J1939<br>3. DeviceNet<br>4. NMEA 2000<br>5. SAE J1708<br>6. OBD-II <br>7. CANopen Safety<br>8. FlexRay<br>9. ISO 11898-1|1. SAE J2602 <br>2. UDS on LIN<br>3. BWM LIN Protocol|1. DALI-2<br>2. DALI-2/DT8<br>3. DALI-2/DT6<br>4. DALI+<br>5. BACnet<br>6. KNX|1. I2C<br>2. SMBus<br>3. PMBus|

## Category

__IOT, Development Board__

## Features

- Remote Access to the ports.
- Isolated & SVP Ports
- 1 x USB2.0 OTG Port
- Single Power Supply (+6V ~ +36V)
- Accessing to API to interact with popular industrial/automotive protocol.

## Hardware System Design Block Diagram

![HardwareDesign](https://github.com/mend0z0/Iso-Link/blob/main/DOC/Block%20Diagrams/_FBD_SYS_HW_ISO-LINK.svg)

## Firmware System Design Block Diagram

![FirmwareDesign]()

## WBS Block Diagram

![WBSDesign]()

## Technology

|Specification|
|:---|
|<table><tbody><tr><td colspan="2" align="center">__Hardware__</h4></td></tr><tr><td>__Microchip :__</td> <td> Std.: ESP32-S3 / Prem.: STM32U5 </td></tr> <tr><td>__PCB Layers :__</td> <td> 4 Layers </td></tr> <tr><td>__Board Dimensions :__ </td> <td> 75 x 50 mm </td></tr> <tr><td>__CAD :__</td> <td> KiCAD </td></tr><tr><td colspan="2" align="center">__Firmware__</h4></td></tr><tr><td>__Language :__</td> <td> C </td></tr> <tr><td>__OS :__</td> <td> FreeRTOS </td></tr> <tr><td>__IDE :__</td> <td> Espressif-IDE / STM32CubeIDE </td></tr><tr><td colspan="2" align="center">__Application__</h4></td></tr><tr><td>__Language :__</td> <td> Python </td></tr> <tr><td>__App Type :__</td> <td> Web Application </td></tr> <tr><td>__IDE :__</td> <td> VSC </td></tr></table>|

|PCB Top View|PCB Bottom View|
|:---:|:---:|
|![Latest Version_Top](https://github.com/mend0z0/Iso-Link/blob/main/DOC/Pictures/_3DView_Top_IsoLink_v1.0.png)|![Latest Version_Bottom](https://github.com/mend0z0/Iso-Link/blob/main/DOC/Pictures/_3DView_Bottom_IsoLink_v1.0.png)|

|Final Device Top|Final Device Bottom|
|:---:|:---:|
|![_Final Device_Top](https://github.com/mend0z0)|![_Final Device_Bottom](https://github.com/mend0z0)|

## Demo

Not ready yet for demo...

## Author

- [@Siavash Taher Parvar](https://www.linkedin.com/in/mend0z0)


![Logo](https://github.com/mend0z0/Scoreboard/blob/main/LOGO.png)