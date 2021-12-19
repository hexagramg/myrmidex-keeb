# myrmidex-keeb
Myrmidex is split ergo hotswappable keyboard with two rotary encoders. 
Supports controllers with Pro-Micro layout, has footprints for power switch and battery. 

![Myrmidex keyboard](https://live.staticflickr.com/65535/51756809526_140cf8454c_k.jpg)

In this repository you will find gerbers and schematics. Gerbers were exported with jlcpcb support in mind. Schematics were made in kicad. 



Right now qmk support is implemented, you can find it [here](https://github.com/hexagramg/qmk_firmware/tree/myrmidex/keyboards/myrmidex)

To build this keyboard you will need:
- SOD323 diodes of your choice x50
- PJ 320A trrs x2
- 0805 10k resistors x8
- 0805 10nf capacitors x4
- Kailh hotswap CPG151101S11 x48
- Alps ec11 encoders x2
- 48 mx compatible switches of your choice
- Pro-Micro x2
- Trrs cable


There are places for m2 standoffs, I used these:
- m2 4mm male-female standoff x16 (3mm is possible to fit) https://aliexpress.ru/item/4001271908929.html This one goes between pcb and bottom plate
- m2 3mm female-female standoff x16 https://aliexpress.ru/item/4001271908929.html This one between pcb and top plate
- m2 low profile screws x32 https://aliexpress.ru/item/32981714992.html Screw them tight on the bottom plate and somewhat loose on the top. 


Be careful on soldering left side, one diode on the bottom row is flipped. I will probably correct this in the next version, if there will be one. 
