Work in Progress

A self-blinking matrix of LEDS forming a 'supercomputer' which can calculate whatever you feel like. No computation, programming, coding or SOC or anything else needed to build it - entirely 'electromechanical' in function.

## Materials
* **Smoked perspex front/diffuser** - Frosted Grey S2 9T21 Perspex Acrylic 'Frost Stone Grey' or equivalent, has a 38% light transmission so fairly heavy diffusion. Cut to 315w x 111h - see dimensions in the CDR schematic file if you wanted to alter this size.
* **Brushed steel effect bottom plate** This is brushed steel effect laminated on black perspex, available from several brands often called 'Metalgraph' or 'Brushed stainless laminate' or similar. This can be either laser cut and engraved or CNC cut and engraved. My laser cut and engrave file is provided here in the CDR files folder in both Illustrator and CDR format.
* **Modular PCB** - all files included here for you to have this produced, I used JLCPCB including SMD assembly service for the resistors/diodes on the back. This PCB can be stacked if you so desire, it has output pads to make this super easy. Arranged for though-hole LEDs.
* **Baffle plate** to stop light leakage between LEDs - important and also allows different shapes. All the 3d printing files are enclosed here as STL files.
* **5mm Self-blinking through hole LEDs** These are 0.5Hz (one blink every 2 seconds) and are in red (625nm) and orange (600nm) with a forward voltage of 3-3.5V and 20mA power draw. The board has individual SMD resistors at 160 ohm to provide slightly less than operating specs to maximise lifespan, plus 3 diode options to supply even less voltage for less brightness. Ths both allows for selectable brightness as well as maximal lifespan.
* **LED Sourcing** I ordered in bulk from Alibaba see here - various colour options as well as different speeds but a hefty minimum order number [Alibaba JSTronic](https://www.alibaba.com/product-detail/Jstronic-0-5Hz-1-5Hz-2Hz_60724851074.html) but they can also be found in smaller quantities on eBay as self-blinking 5mm LEDs. It's absolutely critical they are self-blinking as this is the whole point of the project - zero code, zero computing, just slightly out of sync randomness turned into patterns. You can choose different speeds but higher speeds can be a bit chaotic.
* **Switches etc** Your choice as to what cool switches and dials you use. For this project I used the following  
[Momentary pushbutton - metal illuminated](https://thepihut.com/products/rugged-metal-pushbutton-with-red-led-ring) - 'reset' button on the front  
[Rotary selector - 4P3T](https://www.amazon.co.uk/dp/B0CZDS1686) - voltage selector to change brightness  
[Latching pushbutton](https://thepihut.com/products/16mm-illuminated-pushbutton-yellow-latching-on-off-switch) - side mounted on/off switch
* **Power Supply** 5V in is the designed power supply so this is a simple USB female socket mounted in the side or back of the case.
* **Case** No files here as I made it from wood - you could quite easily design and print something by 3D printing. My wood case is a simple long strip of wood with a 3mm channel cut into it for the perspex and 4 mitred corners to bring it into a box. Back plate is a piece of scrap ply cut to size placed in a rebate.

## Assembly
* Fairly straightforward - solder all your LEDs to your PCB. Test and ensure all working, they will happily self blink provided a 5V input to the input pads, and self blink with less brightness at each of the D1, D2, D3 in options.
* Add the control mechanisms - for simplicity in order your 5V should go through your on/off switch, reset button, rotary selector and the rotary selector output options be wired into whichever of the 3 pad 5v/D1/D2/D3 options you feel you like best. You could also add complexity by using the on/off pushbutton as a selctable toggle switch along with the rotary selector to choose a different set of output pins as well for example.
* -----to do - draw schematic----
* Assemble all the bits into a case of your choosing, done!
