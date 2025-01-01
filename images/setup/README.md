# Switchless Floppy Drive 8x Multi Floppy Speeder for the Commodore 1541 floppy disk drive (V2.2c)



<img title="" src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/MS_SMD.jpg?raw=true" alt="" data-align="inline" style="zoom:10%;"><img title="" src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/MS_DIP.jpg?raw=true" alt="" data-align="inline" style="zoom:13%;">

On the left the 8x Multi-Speeder in the SMD and on the right in the THT version.

## Setup

<img title="" src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup0_1541-II.jpg?raw=true" alt="" style="zoom:15%;" data-align="inline">

Assembly using the example of a 1541 II.



### Setup 1

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup1_PCB_Setup.jpg?raw=true" title="" alt="" style="zoom:15%;">

Positioning of the circuit board.

### Setup 2

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup2_PCB_Soldering.jpg?raw=true" title="" alt="" style="zoom:15%;">

Soldering the components. For me it has proven to be a good idea to solder the SMD components first and then the PIN header for the CPU socket, then the CPU socket, then the capacitors, resistors, buttons and PIN connections for LEDs etc.

### Setup 3

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup3_HeaderPIN.jpg?raw=true" title="" alt="" style="zoom:15%;">

The PIN headers connect the board via the CPU socket. Please remember that the mainboard of the 1541 must first be fitted with a socket. Likewise the VIA 6522 next to the CPU. If the SMD board is to be operated in a 1541 II, then I solder the CPU directly onto the multi-speeder board, as otherwise the drive mechanics will no longer fit via the multi-speeder.

### Setup 4

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup3_HeaderPIN.jpg?raw=true" title="" alt="" style="zoom:15%;">

The PIN headers connect the board via the CPU socket. Please remember that the mainboard of the 1541 must first be fitted with a socket. Likewise the VIA 6522 next to the CPU. If the SMD board is to be operated in a 1541 II, then I solder the CPU directly onto the multi-speeder board, as otherwise the drive mechanics will no longer fit via the multi-speeder.

### Setup 5 (1541-I)

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup6_HeaderPIN.jpg?raw=true" title="" alt="" style="zoom:15%;">

If the board is to be used in a 1541-I, I add a socket to the PIN header. This way, the board is slightly higher in the 1541-I and does not touch any other components on the mainboard. However, this is not absolutely necessary if you check the distances between the multi-speeder board and the mainboard.

### Setup 6

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup7_TOP_THT.jpg?raw=true" title="" alt="" style="zoom:15%;"><img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup8_TOP_SMD.jpg?raw=true" title="" alt="" style="zoom:15%;">

The ready-soldered boards 8x Multi-Speeder 32KB as THT and SMD version.



### Setup 7

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup9_1541-II-PCB.jpg?raw=true" title="" alt="" style="zoom:15%;">

In the 1541-II and 1541-I, all ROMs for the firmware/kernals must be removed. The 1541-II has one ROM, the 1541-I has two ROMs. The firmware/ROMs are provided by the Multi-Speeder for the 1541. If the original ROMs are not removed, the floppy disk drive will not start correctly (RED LED lights up or flashes continuously).

### Setup 8 (1541-II)

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup17_Para_6522.jpg?raw=true" title="" alt="" style="zoom:15%;">

**Only with the 1541-II** the PIN 1-2 must be disconnected. PIN 1 (GND) connects PIN 2 (PA0) to GND. However, PIN 2 is required for parallel data transmission and must therefore not be permanently set to GND. Therefore, the bridge between PIN1 and PIN2 on the mainboard (rear) must be disconnected from U6! Diese Prozedur ist nur bei der 1541-II oder 1541C. Bei der 1541-I ist dieser Schritt nicht notwendig.This procedure is only required for the 1541-II or 1541C. This step is not necessary for the 1541-I.

### Setup 9

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup10_1541-II-PCB.jpg?raw=true" title="" alt="" style="zoom:15%;">

This is what the correctly prepared mainboard of the 1541-II looks like for the installation of the multi-speeder board. Sockets are installed instead of the 6502 CPU and the VIA 6522. The ROM(s) have been removed.



### Setup 10

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup11_Para.jpg?raw=true" title="" alt="" style="zoom:15%;"><img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup12_Para.jpg?raw=true" title="" alt="" style="zoom:15%;"><img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup13_Para.jpg?raw=true" title="" alt="" style="zoom:15%;"><img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup14_Para.jpg?raw=true" title="" alt="" style="zoom:15%;">

I soldered the adapter board with Gold Round Female Male PINs. Alternatively, you can also use the Round PINs from sockets and use them with the adapter board.  

### Setup 11

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup16_Para.jpg?raw=true" title="" alt="" style="zoom:15%;"><img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup15_Para.jpg?raw=true" title="" alt="" style="zoom:15%;">

For the parallel cable I use a Micromatch 2.54mm Pitch Double Row Female IDC Box Header Connector.

### Setup 12

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup21_1541-I-PCB.jpg?raw=true" title="" alt="" style="zoom:15%;">

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup22_1541-I-PCB.jpg?raw=true" title="" alt="" style="zoom:15%;">

<img src="https://github.com/FraEgg/commodore-1541-switchless-floppydrive-8x-multi-floppy-speeder/blob/master/images/setup/Setup20_1541-II-PCB.jpg?raw=true" title="" alt="" style="zoom:15%;">

Installation of the 8x Multi-Speeder 32KB with parallel adapter in the 1541-I and 1541-II.

## Disclaimer

I have designed and tested this project with great care, but errors can always happen. This project is a hobby project. Therefore, I do not guarantee its functionality or take responsibility for any potential damage caused by the installation or use of this project in any way.


