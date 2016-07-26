Kitten Paw controller firmware
======================
Custom controller for the Costar keyboard controllers designed by bpiphany.

*Note that this is not the official firmware*


Build
-----
Move to the appropriate directory then just run `make` like:

  $ make -f Makefile.lufa

At the moment only the LUFA stack is supported.


Bootloader
---------
To enter bootloader by hardware use a magnet above the controller

It is still possible to use Boot Magic and Command (LSFT+RSFT+PAUS) to access the bootloader.