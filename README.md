# C16-64-RAM-expansion-with-4464
64Kb RAM expansion for Commodore 16/116. DRAM 4464 in needed for this mod.

Adapter to put over the 74LS257 (U7 - U8 ) to be able to expand the computer memory.
You need to replace the standard 4416 (U5 - U6) with 4464 and connect 2 pin with A14,A15 

The schematic and gerber are in the PCB folder.

Test video: https://youtu.be/bT41rbG4aQM

*Please consider subscribing to the channel*

3D view:

![alt text](https://github.com/zeus074/C16-64-RAM-expansion-with-4464/blob/main/IMG/c16_64k_ram_solder.jpg)

**Components:**

U1,U2: 74LS257

Micro switch SMD : like MSS22D18  or JS202011SCQN 


PCB view:

![alt text](https://github.com/zeus074/C16-64-RAM-expansion-with-4464/blob/main/IMG/c16_64k_solder_pcb.jpg)

**Installation:**

To install this card you must first remove the two multiplexers U7, U8 and replace the ram U5, U6 (16k) with 4464 (64k).
The card must be installed in place of the multiplexers and above it must be positioned the unsoldered ones or two new 74LS257.
It is necessary to connect 2 signals, A14 and A15 from the C16 board.
These can be found on the TED, on the expansion port or next to the modulator in the 2 closest vias.
In this image it is possible to see where to take the signals. F is input A15 and H is A14, no matter the order if you connect in reverse.
![alt text](https://github.com/zeus074/C16-64-RAM-expansion-with-4464/blob/main/IMG/pcb16_2.jpg)


**Usage:**

the operation is simple, with the switch on 16k the computer will address the memory as if it were original.
By moving the switch we will use the additional inputs to redirect the memory and we will have 64kb in total.
