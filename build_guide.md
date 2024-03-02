# USB Router Build Guide
### This module *does require this build guide*. Seriously, do not try to build it without, the order of soldering is very important in making it actually possible to assemble.
Okay, warning out of the way, this is a pretty easy build, but because of the way the USB sockets have to slot through the front panel, this build guide must be followed accurately and in order if you want your build to go smoothly.  

# Assembly

### 1. Collect together all of the components in the [Bill of Materials](bill_of_materials.md)

![all components](images/all-components.jpg)

### 2. Press the 16 pin shrouded Eurorack power header into place on the side of the PCB with a small marking that says "PWR1" and a marking at the end saying "RED STRIPE"

![press the power header into the pcb](images/bg-1.jpg)

### 3. Press the back USB-A connector into the PCB footprint marked "USB_2" until it clicks into place

![press the back usb-a connector into the pcb](images/bg-2.jpg)

### 4. Use an elastic band to hold the USB-A connector firmly in place

![using an elastic band](images/bg-3.jpg)

### 5. Solder all of the pins on the power header, and *only the two big lugs* on the USB-A connector, not any of the 4 pins in the middle

![soldered components](images/bg-4.jpg)

### 6. After soldering the two big lugs on the USB-A connector, remove the elastic band, make sure that the connector is on straight, and only then solder the 4 pins in the middle

### 7. Push the resistor into the footprint labelled "R1" and the diode into the footprint labelled "D1". Make sure the line on the diode itself lines up with the line on the PCB

![resistor and diode in place](images/bg-5.jpg)

### 8. Solder the resistor and the diode, and then flip the PCB over and snip off their legs

![snipping legs](images/bg-6.jpg)

### 9. Now, if you want the +5V rail of your Eurorack power supply to power the USB sockets, then use a small amount of solder to bridge the two small pads labelled "VBUS" and "5V RAIL". If you leave this disconnected, the module will still transfer power and data between the two USB sockets, but they will not be powered by your +5V rail

![solder jumper](images/bg-7.jpg)

### 10. Line up the second USB-A connector with the PCB footprint labelled "USB-1" but don't push it in, just orient it so that the 4 smaller middle pins are lined up with the holes in the PCB

![lining up usb connector](images/bg-8.jpg)

### 11. Now push the USB-A connector through the front panel in this orientation. You might need to slightly bend the two big lugs inward to make it fit through, and then bend them out again once it's through

![pushing usb connector through the panel](images/bg-9.jpg)

### 12. Push the LED into the footprint labelled "LED1". IMPORTANT: If your PCB just says "usbr" underneath where it says "www.allensynthesis.co.uk" then you need to insert the LED 'backwards' i.e. with the short pin going into the footprint hole without the white stripe. If instead your PCB reads "usbr v2.0", insert it the normal way with the short pin going into the hole with the white stripe

![pressing led into pcb](images/bg-10.jpg)

### 13. Press the USB-A socket which you just pushed through the panel into its footprint, labelled "USB_1"

![pressing the usb connector into the pcb](images/bg-11.jpg)

### 14. Use an elastic band again to hold it in place, and then solder the two big lugs again, then remove the elastic band and solder the 4 smaller middle pins

![using an elastic band](images/bg-12.jpg)

### 15. Now insert the lower 13mm standoff and screw it in, using two M3 screws, through both the front of the front panel, and the back of the PCB. *NOTE: If your PCB just reads 'usbr' and your standoff is M3, you will need to push the screw quite hard from the back as you turn. It is perfectly safe to do this, but it might require a little effort to get the screw to begin cutting its way through the hole. If your PCB reads 'usbr v2.0' then the hole is large enough that this isn't required*

![screwing in the standoff](images/bg-13.jpg)

### 16. Now you can press the flat top of the LED (or the domed top if you chose to buy different ones, this step is purely aesthetic) flush with the front panel, and splay the legs out slightly to kepe it in place

![pressing the led flush](images/bg-14.jpg)

### 17. Solder the LED legs, then turn over the PCB and snip off the excess

![snipping the leads](images/bg-15.jpg)

### 18. Finally screw in the upper 13mm standoff using two M3 screws through the front and back. Follow the advice in step 15 if your PCB reads 'usbr' instead of 'usbr v2.0' again

![screwing in the other standoff](images/bg-16.jpg)

# Testing
### Test that there is no continuity between the top and bottom out of the smaller 4 pins of the top USB socket

![pressing in the power cable](images/bg-19.jpg)

### If you chose to solder the solder jumper and connect your +5V rail to the sockets, then plug your USB Router into your Eurorack system with no other modules plugged in

![power cable connected](images/bg-17.jpg)

### Turn on your power supply, and test the same two pins as before, but this time using a voltmeter

![testing continuity](images/bg-19.jpg)

### If the voltage reads anywhere outside the range 4.4V-5.5V, then *do not* connect this module to any other USB capable module, or to a computer, until you have checked all your solder joints and components, and remedied whatever was causing this voltage difference. You could permanently damage any other modules or computer connected if the voltage reads outside this range

![voltage range on a voltmeter](images/bg-20.jpg)

# Enjoy your build!
Well done for assembling an Allen Synthesis USB Router, mount it in your case and use as you please!  
Tag us in any posts on Instagram to show off your new build, or post about it in the Discord server.

![completed build](images/in-rack.jpg)

