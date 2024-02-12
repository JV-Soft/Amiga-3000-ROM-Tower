ROM Tower is intended for installation in early revisions of the Amiga 3000,
in which there was an error in the PCB layout, and standard kickstart microcircuits cannot work there.

Attention ! Be very careful, the contacts on the ROM Tower board are very hard but fragile, 
if you bend them they will break and cannot be straightened. Install it carefully and remove it carefully.

ROM Tower is designed for installation only in sockets U182 and U183! It is designed that you can install standard kickstart or  27C400 EEPROM .
Do not install Intel 27C220 chips into it!

This adapter supports both standard ROM and ROM flashed in 27C400 chips. If you write ROM into 27C400 chips,
then you can get two kickstarts that will switch, to do this, you need to sequentially flash two parts of the kickstart versions you need,
which have a size of 256kb, into the HI and LO chips. Example 3.1 HI (256kb) 3.9 HI (256kb) and also 3.1 LO (256kb) 3.9 LO (256kb),
then connect a switch or jumper to the connector on the board and switch between these two versions.

You can use a patched kickstart of 1 megabyte in size, it must be divided into HI and LO files of 512 kb in size .
Next, connect address (A17) from the ROM Tower board to the Amiga board, for example this signal is on pin 40 of the CPU 68030

You can always contact me for consultation at - amigaforyou@gmail.com
