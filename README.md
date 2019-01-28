# Fork
This is a fork of the original firmware published by Velleman.
This fork adds new Marlin (1.1.9) version that was recreated by using 
the original modifications and making new ones in the new source tree of 
Marlin.
In order to use the updated version you must init submodules after 
cloning, run `git submodule update --init`.
Thanks to psychokiller from the vertex delta forum for being the first 
one to update the firmware, I used some of his work here. 

I may also tweak the 1.1.4 code a bit but there's no point in using 
1.114 anymore.

# Vertex Delta 3D Printer Firmware
Based on the Marlin Firmware.
Additional documentation can be found in [The Marlin Wiki](https://github.com/MarlinFirmware/Marlin/wiki).
Also place our altered version of U8glib in your arduino libraries folder

## License
Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.
While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
