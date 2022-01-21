![Gen3 2 Orbiter Dragon 1](https://user-images.githubusercontent.com/68491566/132848046-67d77863-799a-4bd1-ae1e-968a23e3ffc2.png)
# Tiki3_Dragon
<b>Update 21 Nov 2022: </b> \
Till date, I had several requests to design the Tiki3 Dragon mount with a 4010/4020 fan to replace the 3010 fan that cools the hotend. The objective I set on Tiki3 mount system are ease of print, compact, light-weight and efficient. 
\
\
Looking at the side profile of the dragon or V6 hotend, the window needed to push air through is around 25mmx25mm = 625mm sq. For a 4010 the fan diameter is around 38mm which equates to an area of 1134mm sq. For a 3010 fan with a diameter of 28mm it is 616mm sq.
\
\
To install a 4010 fan. The reduction in air path is roughly 2:1. This would mean I have to include proper funneling to reduce the air path which result in the increase the width of the mount, making it not compact. So screw-it and make a short funnel. An axial fan produces low pressure air, when faced with drastic decrease in duct size, back pressure will be a problem. The motor will spin at a slower rpm due to resistance, making efficiency an issue. 
\
\
For a 3010 fan, the air path is roughly 1:1, hence no funneling needed. If there is a need to push more air through the heatbreak fins (using the HF version), a higher rpm fan is recommended ie. Gdstime sells 3010 fan 24V at 12,000 rpm or 8.4V at 20,000 rpm.
\
\
To conclude, I am not going to design Tiki3 Dragon to fit a 4010/4020 fan. 
\
\
<b>Update 12 Nov 2021: </b> This mount is for Orbiter V1.5. There will not be an update of Tiki3_Dragon for Orbiter V2.0. Why? https://github.com/thrutheframe/Tiki3_O2

<b>Update 17 Oct 2021: </b> included fan_duct V2 and added body_top and fanduct_bracket for adxl345. Please note the distance for the mounting holes are 19mm. you will also need to directly solder your wire or use L-pins.
\
\
<b>Update 27 Sep 2021: </b> I have included the step and stl file for the body_base.
\
\
<b>Update 12 Sep 2021: </b> shorter version of cable relief added. reduce by 20mm from the original. This is to prevent the cable from hitting the top bar during tall prints. 
\
\
<b>Update 11 Sep 2021: </b> The existing opening for the heater and thermistor cables enlarge slightly. Do note that if you orientate the heater block is the opposing direction. The opening should not be used. The wire will then run outside the BLT bracket and tied to the cable relief. 
\
\
\
\
<u> BOM of screw:\
-4pcs M3x12 or M3x14 for 3010 fan\
-2pcs M3x12 or M3x14 for fan duct (washer maybe needed as the slot are larger for horizontal adjustments)\
-2pcs M3x8 for body_base to ender carriage\
-2pcs M3x8 for cable relief\
-4pcs M3x8 for BL Bracket\
-1pc  M3x8 for fan duct bracket to body_top\
-2pcs M3x20 for mounting the orbiter and orbiter bracket to the body\
-4pcs M2.5x8 for dragon to Orbiter bracket (it should have come with the dragon)
\
\
BOM\
-3010 fan (Please use the high static pressure version, those that runs at 8500rpm will not push enough air)\
-5015 fan\
\
BLT offset: X= 35.5 Y=0

Please print in high temp filament. PLA and PLA+ will warp at the area closest to the heatblock. I print mine in CF petg. 

I have designed 2 sets; one for self-tapping M3 and another for M3x4x6.3 brass inserts. I recommend using the brass insert version if you can.

There are 2 versions for the mount. adxl and non-adxl. adxl is for Klipper users who want to install adxl1345. If you are a Marlin user, the non adxl version is better.

If printing in ABS or any material that will shrink, please remember to scale while slicing.

Holes on the self tap version are design at 3mm to accomodate for some shrinkage during print which will come to 2.8mm.

mount holes BLT bracket, fan duct bracket are slotted for 1-1.5mm for adjustments 

fanduct has a +-2mm vertical and +-0.7mm horizontal for adjustments 
\
\
  <b>CREDITS:</b>
I have to give credit where credit was due, so here goes: 
  
My wife, for putting up with me as I dive into this insanity of mine. 

20four80five: https://www.thingiverse.com/thing:3354741
For first planting the idea of a side mount cooling fan and front mount part cooling fan

Hangtight: https://www.thingiverse.com/thing:4725293
For using his fan duct in version 3.1 when I was still learning Fusion360 and basing some of the design from him work as they are good.

lorinczroby: https://www.thingiverse.com/thing:4725897
For designing the Orbiter which I used for the direct drive design.

Grabcad community for coming up with all the STEP files that I need ie; 5015, 4010, BL touch, etc

Mellow for sharing with me the STEP file of their NF-Zone hotend. 

Thingiverse and anyone/organisation that I forgot to give credit to.

Please do share your make on Thingiverse: https://www.thingiverse.com/thing:4949727
 

![Gen3 2 Orbiter Dragon 3](https://user-images.githubusercontent.com/68491566/132848101-29a7b8e5-de1d-4984-afe6-a267c87956ab.png)
![Gen3 2 Orbiter Dragon 2](https://user-images.githubusercontent.com/68491566/132848111-75af560b-2698-4bdb-8179-77fc8113f430.png)
![Gen3 2 Orbiter Dragon 4](https://user-images.githubusercontent.com/68491566/132848134-5716cac6-c493-4ef6-8b96-6383cbf3f3f8.png)
![Gen3 2 Orbiter Dragon 5](https://user-images.githubusercontent.com/68491566/132848147-4f660563-f890-4758-bbab-ac142b082de8.png)

<b>FAQs:</b>

Q:Will this design be suitable for the E3D V6 mount?

A: No. This design is specifically rigid mounting the Phaetus Dragon Hotend (and its clones with the same mounting holes), Hence the name. 

Q: If No. Would you be adapt this design for the V6 hotend?

A: Not at the moment. One of the main reasion is that I do not use V6 mount. 

Q: Will this system fit the Sovol/Tronxy/TwoTrees etc etc?

A: Honestly, I would not know as I do not have those printers to work with.

Q: Would you release the STEP file for others to remix your design?

A: I asked this question once and the answer was "if u can remix it, u can design it on your own". He was kindof an asshole, but he was not wrong either. That is why I ended up designing my own mount system. I prefer not to be an asshole. Hence, I would release the STEP files for the body and BL bracket, which will be a good foundation to built your own version/remix. 

Q: Did you test print it in PLA? How did you get even get such specific numbers? "...I find stuff like this very misleading with serious potential to cause damage to printers when people try to do it..." 

A: I try my best to answer questions pertaining to the design. Constructive suggestions and contributions are greatly apperciated. Please be polite and nice.

Q: How accurate is the CFD simulation on your fan duct? Did u consider turbulance of of the 5015? Did u take into account of hotend movement? This design is misleading/shit/rubbish etc etc.

A: My basic CFD simulation of the particles movement (air) is to provide a validation that the air is directed under the nozzle when designing the fan duct. There are many other parameters that I would not know. tbh, it's a fanduct for 3D printer, not a cooling system of a nuclear plant... so take a chill pill and dun go karen/kevin on me. 

Q: Why do you add a heat sink to your motor? it is counter-productive as it add weight? 

A: Simple. I like it. 

Q: Why it is called Tiki3

A: Tiki was the name of our family dog. He passed away several years ago and we still miss him dearly. So I named this system after him. 

<b>Contributions</b>\
 My 3D printing hobby is running on Fun-Funds which is usually in fumes state. Contribution to this funds are from small print jobs, servicing 3D printers and the once-in-a-blue-moon tip to my paypal.me account. If you like using this system and would like to thanks me, a $2 coffee tip will be greatly appreciated (I like coffee). Thank you. https://www.paypal.com/paypalme/shannonheng
