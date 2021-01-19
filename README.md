# Clover-EFI-for-Asus-ROG-GL552VX
# Gl552VX-Mojave
# Hackintosh GL552VX Mojave 10.14.5

Base on https://github.com/xuanquydsr/Gl552VX-Mojave

# Use Hotpatch
# Working:
- Wifi, Bluetooth (BCM94352Z DW1560)
OR
- Wifi, Bluetooth (AC8260 using https://openintelwireless.github.io/)


- Card Reader
- sleep (Fn+F1 icon)
- Airplane mode (Fn+F2 icon)
- shutdown
- Intel HD 530
- HDMI
- All USB ports
- Keyboard 16 (Support Automatically turn off lights)
- TouchPad with VoodooI2C (Turn off fn+f9 and ignore built-in trackpad when mouse or wireless trackpad is present )
- Fn Keys
- Keyboard Backlighting
- Ethernet (LAN)
- Battery Status
- UVC HD Webcam
- Speaker + Internal Microphone
- iMessage + FaceTime
- Disable Touch ID

# SOURCE:

Wifi + airDrop + Bluetooth: Remove kext IntelBluetoothFirmware.kext, IntelBluetoothInjector.kext, itlwm.kext
https://www.tonymacx86.com/threads/broadcom-wifi-bluetooth-guide.242423/
OR 
Wifi  + Bluetooth:
https://openintelwireless.github.io/


Install Fake-pci-id (FOLDER INSTALL S:L:E):
https://bitbucket.org/RehabMan/os-x-fake-pci-id

# Audio:

1. AppleALC. (recommendation)

Install AppleALC on "Clover"

OR
2. AppleHDA Patcher:
https://olarila.com/forum/viewtopic.php?t=6528


