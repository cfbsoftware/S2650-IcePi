The S2650 IcePi is a Signetics 2650 computer which uses an actual 2650 IC (an 8-bit CPU from the 1970's), an Olimex PICO2-XL RP2350-based microcontroller development board and a CP2102 UART to USB Converter.

A binary image of PipBug (the Signetics Monitor ROM) is loaded into RAM on the RP2350B and the S2650 executes the code. The RP2350B firmware, developed using the Oberon-07 programming language, generates the 1 MHz clock and manages the CPU's read and write access to the RAM.  

A terminal emulator an a PC is used to communicate with the USB to UART converter connected to the sense and flag pins of the 2650. The S2650 IcePi is powered by the 5V USB C connector on the Olimex board.
