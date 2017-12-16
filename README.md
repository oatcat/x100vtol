## x100vtol
a 100mm 4-rotor small drone using brushed motors, 2s li-po battery, 60mm prop.
One piece PCB-as-chassic, onboard mosfet motor driver, GY-86 as IMU.
Uses taulabs software. Hardware compatible as DISOVERY F4.

#To make one:
Order the PCB from a fab house, buy the necessary parts, solder the PCB.
Connect a S.BUS reciever to the port and fix the reciever on the PCB.
Flash taulabs firmware using ST-LINK, configure the UAV.

#BOM
Apart from the PCB BOM, you will need to secure the motors onto the PCB.
The motor mount I used is bought on taobao.com. If you can't get one you can change the PCB to suit your motor mount.

A small FPV Camera with built in VTX is needed if FPV is desireable.

A ~550mAh 2S battery is needed, and you will need a strap to fix the battery.
There are 2 slots on the PCB you can use to strap the battery.

For proper takeoff and landing you will need some kind of landing gear.
Just glue a small piece of plastic under each motor mount will be fine.

To flash the STM32 you will need ST-Link. Either a standalone one or a builtin on the Discovery board will be fine.
