# C02-Pocket-SBC
A Pocket-sized 65C02 SBC with SCC2691 UART console

This is small 4-layer PCB that is 3.8" x 2.5" in size
  ExpressPCB was used for the schematic and PCB layout.
  
  Boards were acquired via their Miniboard Pro service.
  
Atmel Wincupl was used to create the files needed to program the ATF22V10CQZ.

WDC Tools was used to assemble and link all of assembler source files.

C02BIOS and C02Monitor are separate source files

  C02BIOS provides a JMP table and access to the hardware
    SCC2691 UART provides Console via USB/Serial.
    16-bit timer for RTC and accurate software delays
    
  C02Monitor provides a JMP table for core functions accessible from other progams
    A rich set of monitor features/functions are included
    * see source code for details
