This section is for one complete design you can DIY at home for a **Portable Mini Fan.**

- ![linked image 1](https://grabcad.com/screenshots/pics/4f56a883c54c5d1d7b17bc6bc5b17dba/original.JPG)
- ![linked image 2](https://grabcad.com/screenshots/pics/464aac1533387c74e4982d23ad4b5705/original.JPG)
- ![photo of fanKit version1](img/fankit_06.jpg)

## Download

>
> Visit the [FanKit on grabCAD](https://grabcad.com/library/fankit-2) to download the models.  This contains STL for printing and native CAD files.
>
> Inside is post you can find the PDF with many details about the design, and full parts list as of the April 2026 version.
>

## Parts
The table below has links to all the parts we need to build the fan kit.  These are sourced from amazon except 2 or 3 parts.

| Item           | Description               | Link                    | price | quantity |
| -------------- | ------------------------- | ----------------------- | ----- | -------- |
| Actuator       | Fan, 40mm                 | https://amzn.to/3OViaFw | 9.99  | 2        |
| Switch         | mini switch, roller lever | https://amzn.to/4mSfl4A | 5.99  | 10       |
| USB charger    | TP4056                    | https://amzn.to/4tlib45 | 5.99  | 6        |
| DC boost       | MT3608                    | https://amzn.to/4mW9xqZ | 6.99  | 10       |
| Wires          | 22 AWG single-core        | https://amzn.to/48mFqTC | 15.89 | 150 ft   |
| Glass          | 24x76 microscope slide    | https://amzn.to/499wWPR | 7.99  | 50       |
| Screws         | screws kit m2.5           | https://amzn.to/4u8TQiG | 6.58  | 540      |
| Battery Holder | backup selection          | https://amzn.to/3Qzk8fr | 2.91  | 1        |

Above, each part comes in a multipack that gives you useful circuits for coming projects.  These parts are highly useful for a broad range of electronics, and they were chosen very intentionally to give the user more parts on-hand that are highly relevant for DIY electronics.

Two parts take a special effort to get the ideal model number. 
**Battery** The selected 18650 cell that is recommended for peak performance & reliability is the panasonic NCR18650GA, from a great deal of testing and it's considered the Gold Standard for cells we use with SCUTTLE Robotics.  But, most builders will chose their own out of many cells on the market and that is OK as well.
**Battery Tray** This unit is usually called a "battery cell holder" in the online shops but we call it a "tray" to differentiate it better.  Holder is too common of a term.  Most cheap no-brand trays implement a spiral spring and have less build quality, and no datasheet.  The specified tray for our project is made by Keystone and it's available at Mouser, Digikey, or other professional electronics distributors.  
* Find [tray at Mouser](https://www.mouser.com/ProductDetail/Keystone-Electronics/1043)
* Or [tray at Digikey](https://www.digikey.com/en/products/detail/keystone-electronics/1043/2745669)


## Circuits
Below, find the images of each component for the circuit in the fanKit.  The last image shows the original photo taken for the parts.  We can generate these clean graphics starting with the photo and asking Google Gemini "please generate an image for this part that is suitable for a technical diagram."

- ![circuit image](img/circuit_usbCharge.jpg)
- ![circuit image](img/circuit_dcboost.jpg)
- ![circuit image](img/circuit_fan40mm.jpg)
- ![circuit image](img/circuit_switch.jpg)
- ![circuit image](img/circuit_tray.jpg)
- ![placeholder](img/placeholder.jpg)


## Build
Follow along with the photos to build the kit. The key actuator is a 40mm fan, a standard for compact electronics & PC designs.  the first image shows the kit assembled with spare batteries.  The selected 18650 cell is a "protected cell" design, which is slightly less common than the plain version and usually has a taller tip including a round boss.  This makes better contact in a range of battery holders.

Photo 2 shows the selection of M2.5 fasteners and the heat set insert.  It's a brass threaded insert, popular among 3D printing projects.

Photo 3 shows the recommended wire.  It's copper with a silver-looking nickel cladding, for easy manipulation, easy bending and stripping by hand.  In most projects we use stranded wire but for this project the wire is part of the design which holds the circuits in place and you can choose solid core 22 AWG for the easiest effort in building and soldering.

- ![img1](img/fankit_14.jpg)
- ![img1](img/fankit_13.jpg)
- ![img1](img/fankit_15.jpg)

In the first photo, see the circuits recessed in the printed fan body.  At this moment I had added a small bit of sticky tack to hold items in place while I fit wires and do assembly.  The next image has the two main circuit boards (PCBs) soldered together with two wires from input to output.  Beginners will find it easier with a longer length of wire, and with soldering practice you may chose a short length as shown and have a more compact result.  Lastly, see the front of the fan assembled without a cell.  The pocket behind the battery tray gives an access point to push the battery out.  When you wish to remove the battery, if it's hard to pull it from the tray you can insert a tool from behind to push it through this passage.

- ![img1](img/fankit_11.jpg)
- ![img1](img/fankit_01.jpg)
- ![img1](img/fankit_08.jpg)
