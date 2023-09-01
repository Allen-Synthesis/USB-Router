# USB Router Build Guide
### This module *does require this build guide*. Seriously, do not try to build it without, the order of soldering is very important in making it actually possible to assemble.
Okay, warning out of the way, this is a pretty easy build, but because of the way the USB sockets have to slot through the front panel, this build guide must be followed accurately and in order if you want your build to go smoothly.  

# Assembly

### 1. Collect together all of the components in the [Bill of Materials](bom.md)

![_DSC4078](https://github.com/roryjamesallen/usb-router/assets/79809962/7044e7f6-c5c7-419a-8efc-a28bd59c7e60)

### 2. Press the 16 pin shrouded Eurorack power header into place on the side of the PCB with a small marking that says "PWR1" and a marking at the end saying "RED STRIPE"

![_DSC4105](https://github.com/roryjamesallen/usb-router/assets/79809962/3243018a-4f2d-45cd-a506-0aef53b1af5f)

### 3. Press the back USB-A connector into the PCB footprint marked "USB_2" until it clicks into place

![_DSC4106](https://github.com/roryjamesallen/usb-router/assets/79809962/aef84ace-dccb-40e7-8b7a-4c527ae53c58)

### 4. Use an elastic band to hold the USB-A connector firmly in place

![_DSC4107](https://github.com/roryjamesallen/usb-router/assets/79809962/c63c2ad7-a73f-4de3-9865-d0fff365d938)

### 5. Solder all of the pins on the power header, and *only the two big lugs* on the USB-A connector, not any of the 4 pins in the middle

![_DSC4108](https://github.com/roryjamesallen/usb-router/assets/79809962/c3ab40ed-fe90-4945-84f8-606f8aea6d23)

### 6. After soldering the two big lugs on the USB-A connector, remove the elastic band, make sure that the connector is on straight, and only then solder the 4 pins in the middle

### 7. Push the resistor into the footprint labelled "R1" and the diode into the footprint labelled "D1". Make sure the line on the diode itself lines up with the line on the PCB

![_DSC4110](https://github.com/roryjamesallen/usb-router/assets/79809962/9e5c3eee-b105-4f20-9f9a-30a76f9d2541)

### 8. Solder the resistor and the diode, and then flip the PCB over and snip off their legs

![_DSC4111](https://github.com/roryjamesallen/usb-router/assets/79809962/f2e2f235-9988-4470-910c-1dd3f13280ff)

### 9. Now, if you want the +5V rail of your Eurorack power supply to power the USB sockets, then use a small amount of solder to bridge the two small pads labelled "VBUS" and "5V RAIL". If you leave this disconnected, the module will still transfer power and data between the two USB sockets, but they will not be powered by your +5V rail

![_DSC4112](https://github.com/roryjamesallen/usb-router/assets/79809962/c4a25dcc-277b-4c20-b052-aa347e814253)

### 10. Line up the second USB-A connector with the PCB footprint labelled "USB-1" but don't push it in, just orient it so that the 4 smaller middle pins are lined up with the holes in the PCB

![_DSC4113](https://github.com/roryjamesallen/usb-router/assets/79809962/283da137-aca8-4ac4-9bdd-6309fa30a141)

### 11. Now push the USB-A connector through the front panel in this orientation. You might need to slightly bend the two big lugs inward to make it fit through, and then bend them out again once it's through

![_DSC4114](https://github.com/roryjamesallen/usb-router/assets/79809962/0732b956-e2fb-46d8-8d0e-e7f2c372daf1)

### 12. Push the LED into the footprint labelled "LED1". IMPORTANT: If your PCB just says "usbr" underneath where it says "www.allensynthesis.co.uk" then you need to insert the LED 'backwards' i.e. with the short pin going into the footprint hole without the white stripe. If instead your PCB reads "usbr v2.0", insert it the normal way with the short pin going into the hole with the white stripe

![_DSC4115](https://github.com/roryjamesallen/usb-router/assets/79809962/334c5be2-53c0-4a91-96a0-770ce8c778d4)

### 13. Press the USB-A socket which you just pushed through the panel into its footprint, labelled "USB_1"

![_DSC4118](https://github.com/roryjamesallen/usb-router/assets/79809962/df1f5df3-e948-4335-a589-8a6704eade0f)

### 14. Use an elastic band again to hold it in place, and then solder the two big lugs again, then remove the elastic band and solder the 4 smaller middle pins

![_DSC4119](https://github.com/roryjamesallen/usb-router/assets/79809962/299b7aea-f19c-4779-8016-39a693f25d32)

### 15. Now insert the lower 13mm standoff and screw it in, using two M3 screws, through both the front of the front panel, and the back of the PCB

![_DSC4120](https://github.com/roryjamesallen/usb-router/assets/79809962/56a27f2a-065b-48ef-a81e-b7120f461307)

### 16. Now you can press the flat top of the LED (or the domed top if you chose to buy different ones, this step is purely aesthetic) flush with the front panel, and splay the legs out slightly to kepe it in place

![_DSC4121](https://github.com/roryjamesallen/usb-router/assets/79809962/570ec12a-bf8d-44f5-b3b5-9a7e707e188e)

### 17. Solder the LED legs, then turn over the PCB and snip off the excess

![_DSC4122](https://github.com/roryjamesallen/usb-router/assets/79809962/022a9789-a4be-4006-9750-3ef7ace9cb2c)

### 18. Finally screw in the upper 13mm standoff using two M3 screws through the front and back

![_DSC4124](https://github.com/roryjamesallen/usb-router/assets/79809962/937cfa63-3678-4dad-9605-43f81d6e55c2)

# Testing
### Test that there is no continuity between the top and bottom out of the smaller 4 pins of the top USB socket

![_DSC4131](https://github.com/roryjamesallen/usb-router/assets/79809962/2bfeb806-1e01-480a-ba21-e1f5f7f83a1a)

### If you chose to solder the solder jumper and connect your +5V rail to the sockets, then plug your USB Router into your Eurorack system with no other modules plugged in

![_DSC4125](https://github.com/roryjamesallen/usb-router/assets/79809962/d9a895fb-ca72-4273-b0e5-626944cb88d5)

### Turn on your power supply, and test the same two pins as before, but this time using a voltmeter

![_DSC4131](https://github.com/roryjamesallen/usb-router/assets/79809962/881c1d15-0415-442d-885f-f13cfe1309f0)

### If the voltage reads anywhere outside the range 4.4V-5.5V, then *do not* connect this module to any other USB capable module, or to a computer, until you have checked all your solder joints and components, and remedied whatever was causing this voltage difference. You could permanently damage any other modules or computer connected if the voltage reads outside this range

![_DSC4132](https://github.com/roryjamesallen/usb-router/assets/79809962/957f4297-e1fd-4ff3-85ff-2a21ccff177e)

# Enjoy your build!
Well done for assembling an Allen Synthesis USB Router, mount it in your case and use as you please!  
Tag us in any posts on Instagram to show off your new build, or post about it in the Discord server.

![_DSC4076](https://github.com/roryjamesallen/usb-router/assets/79809962/553c5197-b33d-428a-a5a9-e07cb683d33c)

