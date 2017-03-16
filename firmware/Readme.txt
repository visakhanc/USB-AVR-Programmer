First, program the ATmega8 with this hex file
For initial programming with avrdude, use slow sck option or use avrdude command line option -B12

Then, change the Fuse bits of ATmega8 to: HFUSE = 0xC9, LFUSE = 0xEF