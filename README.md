# ST-Link v2.1 REV Type-C

Programmer ST-Link V2-1 is an on-chip debugger and programmer for STM32 series microcontrollers. The programmer has SWD, SWO, RESET and UART (logic level 3.3 Volt but with 5 Volt logic also works) interfaces to work with any STM32 microcontroller installed on the programming board. Support automatic firmware upgrade to ensure ST's future support.

## Installation process

 1) Install the STM32 ST-LINK Utility **v4.3.0** program from soft directory. **Exactly** this version _(it will not work with later ones)_.

 2) Upload `Protected-2-1-Bootloader.bin` via SWD or DFU (whichever is more convenient) into the programmer we created.

 3) Connect the just-flashed programmer via USB and select **UPDATE** in the _ST-LINK Utility v4.3.0_ program.

 4) Select _STM32+VCP+MSD_ option and click update.

 5) Next, download the latest version of the STM32CubeProgrammer program and update our device to the latest firmware.

 6) Install drivers for VCP.
