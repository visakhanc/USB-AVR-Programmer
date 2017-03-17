Instructions for flashing the firmware
--------------------------------------
1. Connect Another USBASP programmer to the ISP socket
2. Close both self programming(SELF) jumper and Target supply (VTARG) jumper. Also close the VTARG jumper of the other programmer.
3. Make sure AVR-GCC is installed (or WinAVR)
4. Go to firmware directory in the command line, type: make usbasp