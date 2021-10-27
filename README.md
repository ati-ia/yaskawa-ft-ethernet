# yaskawa-ft-ethernet
Resources for integrating data from ATI Ethernet-based Force/Torque sensors into Yaskawa robots. Compatible with Ethernet-Axia sensors and sensors using a Net Box. This repository contains a Smart Pendant YIP as well as a standalone MotoPlus Application and robot jobs. Not all files are needed for all installations. Refer to the [yaskawa-ft-ethernet Wiki](https://github.com/ati-ia/yaskawa-ft-ethernet/wiki) for system requirements, install instructions, and other software documentation.

Maintained by: ATI Industrial Automation

Contact: ftsupport@ati-ia.com

# Resources for ATI F/T Sensors on Yaskawa Robots
www.ati-ia.com/YaskawaFTSW 
## ATI’s Yaskawa-Ready F/T Sensor Kits:
Sensor hardware kits are available for common sensor and robot model combinations. Other sensor models may also be used, but accesories like compatible cables and interface plates (if available) will need to be purchased individually.
### Kits Include:
  - Sensor with communication electronics compatible with Yaskawa robots
  - Cables
  - Interface plate(s) and fasteners for mounting to the robot
  - Drawings available
## Software from ATI for Yaskawa Users:
  - For Smart Pendant Users:
    - ATI Yaskawa-Ready YIP which includes:
      - ATI Ethernet F/T Smart Pendant Extension
      - ATI NETFTS (Ethernet F/T Sensor) MotoPlus Application
      - ATI NETFTS Robot Jobs for Force Searching, biasing F/T data, and applying Tool Transforms
      - Variable Configuration
      - 
  - For Standard Pendant Users:
    - ATI NETFTS (Ethernet F/T Sensor) MotoPlus Application
    - ATI NETFTS Robot Jobs for Force Searching, biasing F/T data, and applying Tool Transforms

# Yaskawa Smart Pendant
The Yaskawa Smart Pendant provides simplified programming and fast implementation. Its easy-to-understand, tablet-based interface offers a simple learning curve compared to the standard pendant and is ideal for novice robot programmers. Not just for collaborative robots, Smart Pendant is available for use with select Yaskawa Motoman YRC-controlled robots. ATI Industrial Automation has partnered with Yaskawa to provide an easy-to-use Smart Pendant Extension for integrating data from and programming applications with ATI's 6-axis force/torque sensors. Contact your Yaskawa representative to learn more about how the Smart Pendant could work for your application.

# Yaskawa MotoPlus
MotoPlus SDK is a software development kit from Yaskawa. MotoPlus applications run on the robot controller concurrently with the standard robot software, but cannot be opened or edited on the robot pendant. ATI has developed a free MotoPlus driver which integrates data from ATI's Ethernet-based force/torque sensors with certain Yaskawa controllers. This MotoPlus Application powers the sensor communication in the background of the ATI NETFTS Smart Pendant Extension, but can also be installed as a standalone Application.
