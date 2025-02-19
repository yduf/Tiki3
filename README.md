![Tiki3 Gen3 2 remixed](https://user-images.githubusercontent.com/13983772/147852731-8d33813a-e173-44be-b609-18d6d286b3eb.png)



# Tiki3 (version 3.2) Remixed

Change the orientation of the orbiter Extruder to be over the ender rail.
This has been done, by modifying the step files provided, mostly moving the screws
and rotating top parts.

It works well with orbiter 1.5 and LDO motors  LDO-36STH20-1004AHG(XH), but the gap leave between the ender 3 struture is quite small: 1/2 mm. A wider motor won't fit the rail.

Remixed step files integrated into repos.

Everything else is the same.


<b>Update 14 Oct 2021: </b> 
- Updated fan duct design to V2. used a CFD simulation to check for air path.
- Added body_top with adxl mount. Mounting holes are 19mm apart. Please measure your adxl to check fitting. Will only work with fan_duct V2. 
![body_top adxl04](https://user-images.githubusercontent.com/68491566/137341981-c3b58017-7957-454d-a814-c8dbd1234d59.png)

\
\
<b>Update 12 Sep 2021: </b> shorter version of cable relief added. reduce by 20mm from the original. This is to prevent the cable from hitting the top bar during tall prints. 
\
\
\
\
<b>Introduction</b>\
A mount and fan duct system for Creality Ender 3/3pro/3V2 and Ender 5/5plus

This mount and fan duct system is designed for the hotend carriage of some Creality Ender machines.  
- Ender 3/3pro/3V2
- Ender 5/5pro/5plus

Hotend that has been designed for:
- Creality stock CR10 hotend (tested)
- Mellow NF-Zone CR10 (tested)
- Mellow NF-Smart 
- MicroSwiss All Metal and clones
- Red Lizard (need mod)
 
Tiki3 can be used as direct drive system with the Orbiter V1.5 or in a bowden configuration (No need to print "3_2 Orbiter bracket.stl" for bowden config)

A 5015 fan is required as the stock 4010 fan is underpowered for a dual fan duct system. 
 
Please see the other files for print orientation and BOM of screws and nuts required. 
 
There are many mount and fan duct system out there, what I think differs mine from others is the design focus on:
- Printability
- Functionality
- Modular system
 
As with all one-man-show, I would need the help of the community use/test this system and provide constructive suggestion to help me improve the existing design. 
Thank you for visiting my github page. 


I have to give credit where credit was due, so here goes: 

<b>CREDITS:</b>

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

<b>FAQs:</b>

Q: Is there any major design changes between this version (3.2) and the previous versions that are uploaded on Thingiverse?

A: Most of the changes structual improvements, but the position of the mounting holes are the same. The major changes is the fan duct. but it will still fit the over versions as the mounting holes are the same. 

Q:Will there be a design for V6 /Dragon hotend?

A: Yes. I am working on the Dragon version. You can download it from https://github.com/thrutheframe/Tiki3_Dragon. The V6 version is a bit tricky. so it will take time.

Q: Would you be able to include a custom design for bracket/fan duct/holder etc etc?

A: Due to my engineering background and training, I have a habit to print and test the designs to my level best before I release them. Without the actual item (or part that are close the the same dimensions) I would not be able to do that. Either I can borrow the items from friends or someone/company is willing to sponsor me the item. There is not much I can do. 

Q: Will this system fit the Sovol/Tronxy/TwoTrees etc etc?

A: Honestly, I would not know as I do not have those printers to work with.

Q: Would you release the STEP file for others to remix your design?

A: I asked this question once and the answer was "if u can remix it, u can design it on your own". He was kindof an asshole, but he was not wrong either. That is why I ended up designing my own mount system. I prefer not to be an asshole, but I am cheeky. Hence, I would release the STEP files for the body and BL bracket, which will be a good foundation to built your own version/remix.  

Q: Did you test print it in PLA? How did you get even get such specific numbers? "...I find stuff like this very misleading with serious potential to cause damage to printers when people try to do it..." 

A: I try my best to answer questions pertaining to the design. Constructive suggestions and contributions to the design are greatly apperciated. Please be polite and nice. 

Q: How accurate is the CFD simulation on your fan duct? Did u consider turbulance of of the 5015? Did u take into account of hotend movement? etc etc.

A: My basic CFD simulation of the particles movement (air) is to provide a validation that the air is directed under the nozzle when designing the fan duct. There are many other parameters that I would not know. tbh, it's a fanduct for 3D printer, not a cooling system of a nuclear plant... so take a chill pill and dun go karen/kevin on me. 

Q: Why do you add a heat sink to your motor? it is counter-productive as it add weight? 

A: Simple. I like it. 

Q: Why it is called Tiki3

A: Tiki was the name of our family dog. He passed away several years ago and we still miss him dearly. So I named this system after him. 

<b>Contributions</b>\
 My 3D printing hobby is running on Fun-Funds which is usually in fumes state. Contribution to this funds are from small print jobs, servicing 3D printers and the once-in-a-blue-moon tip to my paypal.me account. If you like using this system and would like to really thanks me, a $2 coffee tip will be greatly appreciated (I like coffee). Thank you. https://www.paypal.com/paypalme/shannonheng
