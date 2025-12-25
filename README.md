# pizero-slidetop-combined
This repo combines many of the parts that will need to be glued together in the original pizero-slidetop repo into singular parts.


# what is the pizero-slidetop?
The pizero-slidetop is like the pi5-slidetop that I am currently developing except it is more compact and is compatible with the Orange Pi Zero 2 W, the RADXA Zero 2 Pro(though the battery may not provide enough power), The RADXA Zero 3W/E, and the Raspberry Pi Zero 2/W.

This obviously will not come with the features of my original slidetop such as a camera module or an NVMe slot, but it wil be less power hungry. I am also changing the sliding hinge design to one that is more simular to the hinge design found in [this video](https://www.youtube.com/watch?v=jntHraUABHo).
# WARNING
This is still under development and its not even under the beta prototype testing phase of the project. I will once again update the CAD files as I work on this and hopefully make proper documentation in the near future.

# TO-DO

1. I will wan't to replace the Orange Pi Zero 2 W with the more powerfull and slightly larger RADXA Zero 2 Pro at some point in the future. -Acheived*
2. I will also wan't to replace many of the parts which we're cut from an acryllic panel with 3D-printed parts. -Acheived
3. I will wan't to create better documentation some time in the future.

# Parts & Dimensions
![display](/img/display.jpg)
Display: 
1. Display Area：196.608(W)×147.456(H) mm
2. Outline Size：208.88(W)×167.12(H) mm
3. Panel Model:LP097QX1-SPC1
4. Panel Type:a-Si TFT-LCD , LCM
5. Bezel Opening：201.01(W)×151.86(H) mm
6. Panel size:9.7 inch
7. Resolution：2048(RGB)×1536 , QXGA

Display Controller board: 
![controller-board](/img/controller-board.jpg)
1. HD LCD Controller Board VS-RTD09705-V1
2. Board Size: 120mm x 62.5mm x 5mm
3. Audio Output: Earphone Support Speaker 4ohm 2W or 8ohm 1.5W
4. Video Input: Mini HD HD Version 1.4 Mini HD
5. Input Power Supply: DC Connector 3.5mmx1.35mm 5~12Vdc Mirco USB 5Vdc

Wireless Keyboard:
1. Bluetooth specification: V3.0
2. Bluetooth name: Bluetooth Keyboard 
3. Chip: Broadcom 3.0 chip
4. Compatible system: For Windows/Android/iOS
5. Battery capacity: 280mAh
6. Operating voltage: 3.1-4.2V
7. Operating range: Up to 10m / 33ft
8. Continue working time: 90 hours
9. Charging port: Micro USB 
10. Key number: 59
11. Color: Black
12. Material: Plastic keys + iron bottom cover
13. Dimension: Approx. 200 * 126 * 6.2mm / 7.9 * 5.0 * 0.24inch 
14. Package weight: 192g
15. JTLB Ultraslim Mini Wireless Keyboard with Touchpad

Speakers:
1. waveshare 2030 Cavity Speaker, 8Ω 2W, Sound, Compact Size, 4PIN PH1.25 Connector

Battery:
1. Minthouz Magnetic Power Bank with Foldable Holder, 5,000mAh Battery Pack with 20W USB-C: MT-Charge π 5H
2. Size: 10.3*6.7*1.2cm/4*2.6*0.4in
3. Battery Capacity: 5000mAh/19.25WhWeight: 124g/4.4oz
4. Magnetic Force: 10 Newtons
5. Max Input(Type-C 1/2): 18W(9V/2A)
6. Type-C 2 Output: 20W(Max)
7. USB-A Output: 22.5W(Max)
8. Wireless Output: 15W
9. USB-A + Type-C 2 Output: 15W(Total)

SD Extender cable adapter
1. Micro SD Card Extension Cable TF Card Adapter FPC Micro SD Card Extension Cable with Screw Holes External Self-Ejecting Card Holder for Micro SD Cards Prevents Holder Wear and Tear (3.93in/10cm)
2. Size: 2.15x1.81cm
3. Thickness: Approx. 2.6mm

Metal Balls for friction:
1. Amount: alot of them
2. Size: 2mm x 2mm 
3. Material: Stainless Steel

# Cables
1. Headphone port: male 3.5mm AUX to female 3.5mm AUX cable
2. Connect SBC to controller board: (for RADXA Zero 2 PRO or RPI Zero 2/2W) Micro-HDMI male to Mini-HDMI male cable
3. Connect SBC to controller board: (for Orange Pi Zero 2W) Mini-HDMI male to Mini-HDMI male cable
4. Charging port: USB0-C male to USB-C female cable
5. Charge SBC: USB-C male to USB-C male
6. Charge screen & controller board: USB male to DC barrel-port/micro-USB male
7. HDMI-in port: HDMI male to HDMI/mini-HDMI/micro-HDMI female




# Footnote

1. I am currently still working on the 3d models, but I've made screw mounts for both the Orange Pi Zero 2W (or any SBC of the same dimensions) and for the slightly larger RADXA Zero 2 Pro.

# Problems
1. Since I've opted for the cheapest and smallest bluetooth keyboard and touchpad I could find, the touchpad quality is horrible. I would recommend slowing down the touchpad speed on whichever desktop environment you are running.


