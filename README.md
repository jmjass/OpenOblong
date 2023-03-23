# OpenRectangleCubsMod
Custom PCBs for a RP2040 powered rectangle controller.

Modified version of https://github.com/Armastardo/OpenRectangle that decreases size of the PCB and changes button layout to accomodate.

Original Dimensions: 339.13mm x 141.22mm

Modified Dimensions: 282.7mm x 136.22mm

Please note that this design is untested for now.

Includes stacked acrylic case design with aluminum switchplate or fully acrylic design with acrylic switchplate. 

Case Dimensions: 298.8mm x 160.4mm x ~16.6mm (~11.76" x ~6.31" x ~0.654") Thickness calculated based off of 3mm top panel, 1.6mm switchplate, 3 pcb layers/2 pcb layers and a hotswap layer all 3mm, and a 3mm base layer.

(Thickness of the case varies based on thickness of acrylic layers)

## Part Links:

Case Standoffs: 

https://www.aliexpress.us/item/2251832708378430.html?gatewayAdapt=glo2usa4itemAdapt&_randl_shipto=US or https://www.amazon.com/dp/B07H3SRSDG?psc=1&ref=ppx_yo2ov_dt_b_product_details (ymmv on amazon stock but shipping is faster)

Calculate the thickness of your case and order standoffs about 1mm shorter than the case.

Case Screws: 
https://www.amazon.com/dp/B0798227SK?psc=1&ref=ppx_yo2ov_dt_b_product_details

Any M2 screws will work, I got these because I wanted black ones that are flush with the case.

Acrylic:

https://houstonacrylic.com/

There is a huge variety of colors and different designs of acrylic offered by these guys but they are a bit more expensive than other places. Also I had to pay about $17 for shipping so be sure to account for shipping costs in budget. If you order a 12 x 19 inch sheet from here you are able to cut 3 layers out of it as long as you are very careful about the alignment of sheet on the laser cutter but you risk runing the edge cuts of the layers if you are not accurate. You can comfortably cut 2 layers out of each sheet if you do not want to take this risk.

If you are trying to make it as cheap as possible, I would recommend shopping around for clear acrylic because clear seemed to be the cheapest when I was looking. Here are a couple different thickness ones from amazon that I found:

1/8" For Top/Bottom Layers + PCB Layers on Aluminum Switchplate Design: https://www.amazon.com/dp/B09XR8NB28?psc=1&ref=ppx_yo2ov_dt_b_product_details

Acrylic Switchplate (.06"): https://www.amazon.com/dp/B09LTYDYKP?psc=1&ref=ppx_yo2ov_dt_b_product_details

PCB Layer/Hotswap Cutout Layer on Acylic Switchplate Design (.08"): https://www.amazon.com/dp/B09N3PN8PG?ref=ppx_yo2ov_dt_b_product_details&th=1

I recommend doing some searching on your own as there may be different options that are cheaper. 8" x 12" works the best for cutting 1 panel per sheet and for getting mroe than 1 panel per sheet you need multiples of 6.315" x 12". For example, 12" x 19" can get you 3 layers with very little margin of error or 12" x 21" would get you 3 layers way more comfortable although you are unlikely to find this size and would more commonly find 12" x 24"
### For Aluminum Switchplate Design:
PCB Standoffs:

https://www.ebay.com/itm/195557042245?var=495436584888 or https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/97730356330R/10056365

I would recommend going with the ebay ones, I got the digikey ones because I didn't find the ebay ones before I ordered but they are much more expensive. If you go with the ebay ones you can make the mounting holes in the switchplate 1.8mm and screw them in from both sides. If you go with the digikey ones then you will have to mount the standoffs to the bottom of the switchplate (I am using JBWeld for this https://www.amazon.com/dp/B0006O1ICY?psc=1&ref=ppx_yo2ov_dt_b_product_details). You can probably do the same thing with the ebay ones as well if you don't want to do screws on both sides.

PCB Screws:

https://www.ebay.com/itm/175115568734?var=474301837905

If you are gluing the standoffs to the board then you want M1.6 x 4mm screws but if you are doing 1 screw on each side then you should get M1.6 x 3mm.

### For Acrylic Switchplate Design:
https://www.mcmaster.com/97155A202/


Looking into a way to 3D print something like this. There needs to be something to keep the PCB from sliding around in the case so my current plan is to get pins to put through the screw holes on PCB and glue them to the layer the PCB rests on. Pins should be ~1.6mm in diameter (holes on pcb are 1.8mm) and minimum length of 3mm but I think that 4-4.5mm would be ideal.

