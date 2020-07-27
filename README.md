# `ncKiibs` Support Repository

## Hello friends

This is a repo for the extra materials of the keyboards that I made. All these projects were just hobby projects, so I apologize that they are not professionally organized. 

## About the hardware fixtures that I used

I've got many questions regarding the materials that I used for my builds. The selection of the materials varies depending on one's configuration, so I can't really recommend definite choices, but I will try to describe my case so that you can take my case as an example. Do note that this is for a hotswap and case mounted PCB build. 

### Spacing between bottom plate and PCB

- The thickness of the top and bottom plate is 1.6mm
- The thickness of PCB is 1.6mm
- I use mill max 0305 for hot-swap. It adds about 3mm to the spacing btw/ bottom plate and PCB. If you go with 0305, you can save about 1mm of spacing.
- I use mil max ultra-low profile receptacles for MCU slots. It adds about 3mm, but it sits almost flat to mil max 0305, so it does not add up.
- Pro Micro adds about 3.75mm to the spacing btw/ bottom plate and PCB
- You also need to add the thickness of the USB cable head. Let' just add 3mm here. 
- In sum, I need 3 + 6.75 ~= 10mm spacing in my setup with a USB cable of which the thickness of the plug housing is less than 3mm. 
- So, I can use 10mm standoffs between PCB and the bottom plate. I can also go with 7mm standoffs, but then I will need to make some cutouts on the bottom plate for a USB cable head. 

### Spacing between PCB and switch plate 

- Usually, the space between the PCB and the top switch plate is 5mm for MX switches. 6mm is also fine if you go for a plate-mounted hot-swap setting.
- mill max 0305 pushes switches about 0.5mm above the top PCB surface .
- The switch plate that I made is 1.6mm.
- So, I can use 3mm standoffs or 4mm standoffs between the PCB and the switch plate, which will make the spacing 5.1mm and 6.1mm respectively. Let's say I go with 3mm standoffs.

### Height of the middleware and screws

- From the calculations above, the height of a middleware should be 10 + 1.6 + 3.5  = 15.1. So, I can make a 16mm middleware and use some fiber washers to fill the gaps. 
- From the bottom plate to the switch plate, it is  1.6 + 16 + 1.6 = 19.2. We need about 2mm of a screw thread for nuts. So, I can use 22mm m2 screws and nuts to assemble them all.

### If you go for non-hotswap builds

- Then, it is a bit different story. Because the PCB will be hanging fixed onto the switches and switch plates, You only need to put spacers between the bottom plate and the PCB. The calculation of the middleware height is the same. 

### Where to buy?

- I picked up parts at the local stores or ordered them on online stores, such as Amazon and Ebay for fast delivery. However, you will find that gather all different pieces is rather expensive. If you have time, I recommend to order bunch of them on Aliexpress, because it is way cheaper. You can buy 100  standoffs at 2 USD. It will take years to come to your house, but the price is incomparable and you can order more parts in different specs for your experiments. 

### Note

- Thin fiber washers like 0.3mm or 0.5mm ones are your friend. It will fill up the manufacturing errors and small gaps here and there, if you are ok with their look. 

### Parts that I usually use

- 3mm, 4mm standoffs for switch plate spacing (can be sourced from Ali)

- 6mm, 7mm, 9mm standoffs for bottom plate spacing (can be sourced from Ali)

- 0.3mm, 0.5mm fiber washer for filling errors and sound dampening (can be sourced from Ali)

- 18mm, 20mm, 22mm m2 screws (can be sourced from Ali)

- stainless steel, nylon m2 nuts (can be sourced from Ali)

- Mil Max 7305 or [0305](https://www.digikey.com/product-detail/en/mill-max-manufacturing-corp/0305-2-15-80-47-80-10-0/ED90584-ND/2639493) for hotswap build

- Mill Max ultra low profile [receptacles](https://www.digikey.com/product-detail/en/mill-max-manufacturing-corp/315-43-112-41-003000/ED4764-12-ND/4455232) for hotswap MCU build

- Mill Max machine [pins](https://www.digikey.com/product-detail/en/mill-max-manufacturing-corp/3320-1-00-15-00-00-03-0/ED1161-ND/4147393) for MCU assembly

  

 