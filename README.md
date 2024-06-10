# Voron-vt1286
https://docs.vorondesign.com/community/howto/EricZimmerman/BackupConfigToGithub.html

Voron Trident Magicphoenix CBT lite kit


# Config


Klipper configs for VT.1286 (VT 300) printer running Mainsail.



## Main Components

BOM: https://mpx.wiki/VORON-TRIDENT-CBT-KIT/Trident-CBT-Bom#trident-cbt-lite

### Coming:

* Monolith gantry in ASA CF. Eventually in laser cut alu

* AWD Wantai 811

* 24V + 48V UHP PSUs

* 4x BTT External 5160

* 6mm GT3 belts + bearings pulleys idlers etc



### Electronics

* A/B Motors: Moons MS17HD6P4200

* Z Motors: Moons 42SHDC4049YZ-300N

* MCU: BTT Manta M8P w/ TMC2209

* PSU 24v: Mean Well LRS-200-24

* Host: BTT CB1

* Display: None

* Camera: Aliexpress 4 eur very bad

* Relay: TP-Link Tapo P100 wifi plug


### CAN BUS toolhead

* Board: BTT EBB36

* Control board: BTT U2C

* CAN-cable: 3do CAN+USB cable


### Toolhead

* Toolhead: Xol + Sherpa mini in 3dxtech EZPCCF

* Hotend: Phaetus Dragon UHF

* Hotend fan: Delta 2510

* Partcooling fan: Delta Electronics 12v BFB0412HHA-A117 with xol recommended buck converter

* Extruder: Sherpa mini

* Nozzle: Undertaker 0.5mm

* Probe: Klicky00 in ezpccf


### Enclosure

* General enclosure: stock 3mm pc panels + embiggened monolith panels and 10mm "general" foam everywhere, except front and deck

* Front door: Embiggened monolith and stock panels

* Foamtape: [Funssor 3mm](https://www.aliexpress.com/item/1005005424399100.html)


### Mechanics & Frame

* Frame: Magicphoenix VT 300

* X linear rail: Magicphoenix non-stainless - MGN12H

* Y linear rail: Magicphoenix non-stainless - MGN9H

* Z linear rail: Magicphoenix non-stainless - MGN9H




### Bed

* SSR: SSR 120/230 V/AC, 10 Ampere

* Heater pad: MPX full size heater. Integrated 150c self-recovery fuse. Pre-installed RF125 fuse. Extra thermistor for build plate

* Buildplate: Universal, 300x300x8mm. Cast aluminium

* PEI: OSEQ 300x305 dual sided satin textured black PEI ~~General double sided textured PEI spring steel~~ 


### Modifications

* Embiggened monolith panels ~~Annex Panel 2020 Clips and Hinges~~

* Webcam mount: something very similar to [this](https://www.printables.com/model/404254-2020-alu-extrusion-webcam-mount-for-aukey-1080p-we) but for ov5648

* Motor thermistors

* Y steel backers

* Keystone Jack Universal Skirt Insert

* LED mounts

* Skirt mod for keystone and usb passthrough

* [Emergency stop button](https://www.aliexpress.com/item/1005005173725237.html) and [macros here](https://github.com/jontek2/V2-1645-klipper_config/blob/main/macros/emergency_stop.cfg)
  
* Nevermore v6 micro

* 4 bed fans with wagos under bed

* BFI Front idlers
 
* ~~Sturdy handles~~ Dont work with monolith panels

* Trident [internal spool holder](https://www.teamfdm.com/files/file/619-trident-simple-internal-spool-holder-bowden-guide-60degrees-curved/?tab=details) + holders [from here](https://github.com/elcrni/Voron-Mods/tree/main/Trident_Internal_Spool_Holder)

* Exhaust cover with PG7 and ptfe passthrough. Modified for embiggened monolith panels

* [Trident noodle](https://github.com/Diyshift/3D-Printer/tree/main/Trident%20Noodle) + [bowden tube guide](https://github.com/VoronDesign/VoronUsers/tree/main/printer_mods/Galvanic/Bowden_Tube_Guide)






