# USB Router
### A module to route a USB signal between the front and back of your Eurorack system with optional +5V rail power

The USB Router features one USB-A socket on the front, and an identical USB-A socket on the back.  
The power and data lines of the two sockets are always connected to each other, so you can always use the module for its most basic functions - programming Eurorack modules which feature USB connectors on the back.

### +5V Rail Power
There is a solder jumper on the rear of the USB Router which, if bridged with solder, will power both the front and back USB sockets using the +5V rail of your Eurorack system. This connection happens through a Schottky diode with a small voltage drop, so your +5V rail is still protected from reverse powering via the USB sockets (plugging a USB cable in which supplies +5V can never power the +5V rail of your system, only the other way around).  
This feature allows you to use the USB Router to power 5V devices, for example MIDI keyboards or lighting, or even to charge your phone.

### Potential Uses
- Programming or updating [EuroPi](https://github.com/Allen-Synthesis/EuroPi) modules or other USB supporting modules such as [Uncertainty](https://oamodular.org/products/uncertainty) by OA Modular, without needing to remove them from the rack
- Powering a MIDI keyboard such as an Arturia Keystep
- Configuring a MIDI keyboard, for example the Arturia Keystep without having to rearrange your whole setup


### LICENSES
Hardware: [CERN-OHL-S-2.0](https://spdx.org/licenses/CERN-OHL-S-2.0.html)
Documentation: [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/)
