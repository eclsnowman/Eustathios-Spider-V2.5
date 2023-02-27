# Eustathios-Spider-V2.5
V2.5 of Eustathios Spider (Includes Many Community Mods)

![Eustathios Spider - V2.5 Render Image](https://github.com/eclsnowman/Eustathios-Spider-V2.5/raw/master/Images/Front%20Right.png)

Hello and welcome to my Github for Eustathios Spider V2.5 3D printer. This printer is an updated version of the original Eustathios Spider, Eustathios Spider 2.0, and the addition of Community Modifications which have improved the design. The community added so many great improvements to this design, and I wanted to share an updated design that integrates all these wonderful improvements to the design, form, and function of this printer. I also wanted to update the design with newer more modern controls and components which have become available since the initial design.

This design stands on the shoulders of many great designers of Crossrod Gantry Printers that came before it. Most notable of these is the design of the original Eustathios by Jason Smith. This family of printers had a very devoted community in the G+ heydays, but now that Google+ has died the Community around the HercuLien printer and the Eustathios printer have moved to: https://forum.makerforums.info/c/herculien . This is thanks in great part to Michael K Johnson, who worked his magic to retain the years of great community interaction on G+ and ported it into the Discourse community over on Makerforums. If you are looking for support or community interaction on these printers moving forward, this is the place to go.

This family of printers is all based on the X/Y gantry mechanics of the Ultimaker. Ultimaker style mechanics utilizes a light hot-end/carriage which gets constrained by one X and one Y cross rod. Connected to these crossrods are rod ends which ride on side shafts that act both for power transmission of one axis (rotation) and as the linear guide for travel of the other axis (translation).

 Originally a gentleman who goes by the name Sublime (https://github.com/Intrinsically-Sublime/Tantillus/) created a small format variant of the Ultimaker mechanics which he called the Tantillus. Then GoopyPlastic (aka Brad Hill) created an extrusion version of the Tantillus called the Tslot Tantillus (https://github.com/goopyplastic/tslot-tantillus). Following in Brad’s footsteps Tim Rastall (https://plus.google.com/u/0/+TimRastall/posts) created the very popular Ingentis printer (https://www.youmagine.com/designs/ingentis-a-tantillus-variant) which is a larger version of Tantilus using thicker linear guide components, spectra drive system, and a much larger build envelope. The next printer in this design family was by Jason Smith (https://plus.google.com/u/0/103009815307828556107/posts) call the Eustathios (https://github.com/jasonsmit4/Eustathios). This is the printer that got me excited about this family of printers. Jason made several design choices like GT2 belts which I felt were great upgrades to the platform. I lucked out because his release was timed perfectly with a promotion Misumi was running where your first order from them up to $150 in value was free. I wanted to be able to modify Jason’s files slightly, but he had modeled everything in Sketchup. My limited experience was with Solidworks (self taught) so rather than learn new software I redrew Jason’s Eustathios design files from scratch. And so my Eustathios Spider V1 variant , named due to the color scheme, was born (https://github.com/eclsnowman/Lien3D_Eustathios_Spider). I built the Eustathios and fell in love with the smooth operation, clean prints, and overall reliability. So after operating the Eustathios for several months I converted my existing large CoreXY Printer (https://github.com/eclsnowman/Lien3D_CoreXY ) into a X/Y gantry printer with larger cross rods and dual extrusion. The name of this printer is HercuLien (https://github.com/eclsnowman/HercuLien). Prior to this latest revision (V2.5) there was the Eustathios Spider V2 which can be found here: https://github.com/eclsnowman/Eustathios-Spider-V2

I apologize for the long history lesson, but as you can see there is a lot of progress and talented people involved in these projects. I want to make sure credit is properly attributed to the many great makers who have come before me. The caliber of people involved and all the creativity in the platform is what keeps me so motivated. I would like to specifically mention some of the wonderful community members who added to this project over the years which have inspired or directly contributed to the Eustathios project. 

Specifically:

1.) Walter Hsiao (https://www.thingiverse.com/walter/about) for his elegant designs on the bed leveling corners, passthrough corner 6900-2RS bearing blocks, and Z Axis Bed Supports which have been integrated into the current design. In addition to these parts Walter has many additional designs for alternative components which can be used on the Eustathios like his Space Invaders Center Carriage, his Flying Extruder, and tons more. He is a prolific designer and his ability to simplify a design to its core and make it look elegant in the process inspires me and pushes me in my own designs. 

2.) Next, I would like to thank Zane Baird (https://www.linkedin.com/in/zane-baird-59096923). Over the years on Google Plus, at MRRF, and via Hangouts I am lucky to call Zane a friend. He made numerous design improvements which he implemented on his HercuLien printer. Like Water, Zane has a design style and elegance which is beyond my own ability. His designs for the Center Carriage and Side Carriages strike an balance between style and function which makes this V2.5 of the printer better than ever. Not only do these components work better and improve servicability, but they increase the printable area from previous design. Zanes input and passion on the project pushed me to do better in my own designs. I thank him for his friendship, inspiration and knowledge.

There are of course many more people to thank through this process: Martin Bondéus of Bondtech (who is a true friend with a brilliant mind), Roy Cortes from Panucatt (his boards and components are second to none), everyone from the G+ and Makerforums.info communities (Joe Spanier and Ray Kholodovsky I am looking at you), SeeMeCNC and John Olafson for years of inspiration and community through MRRF, and countless others. I can't name everyone, but you know who you are. Thank you, without you my journey of 3D Printing would not have been so fulfilling and so enjoyable.

Eustathios Spider V2.5 Overview:

* Max Travel Limits (X = 312mm / Y = 314mm / Z = 306mm)
* Designed Print Area (300mm x 300mm x 300mm)
* 32bit Controller = SKR V1.4 running Marlin 2
* TMC2209 Drivers (Qty:5) Independant Z for Marlin Auto Tram
* 24V Power with 500W Mains Powered Bed controled via SSR Relay
* Endstops:
   X&Y = switches or TMC Endstopless homing
   Z = single or dual switches, or BLTouch/3DTouch homing
* Leveling:
   Manual with endstops or autolevel w/ BLTouch/3DTouch

Documentation:

BOM = https://github.com/eclsnowman/Eustathios-Spider-V2.5/raw/master/BOM/ES25%20BOM.xlsx

Printable STL Parts = https://github.com/eclsnowman/Eustathios-Spider-V2.5/tree/master/3D%20Models/STL

Solidworks Files = https://github.com/eclsnowman/Eustathios-Spider-V2.5/tree/master/3D%20Models/Solidworks

Other 3D model formats in zip due to github file size limit) = https://github.com/eclsnowman/Eustathios-Spider-V2.5/tree/master/3D%20Models

Onshape Link: https://cad.onshape.com/documents/dcaaf87ad04323c8f9846c66/w/0537fe6b9eb1e2bc47668a76/e/4ce5ea03b6ef98527d9025d3

3D renders: https://github.com/eclsnowman/Eustathios-Spider-V2.5/tree/master/Images

Image of printed parts:

![Eustathios Spider - V2.5 Printed Parts Image](https://github.com/eclsnowman/Eustathios-Spider-V2.5/raw/master/Images/Printed_Parts%20(1).jpg)

Additional Renders:

![Eustathios Spider - V2.5 Render2](https://github.com/eclsnowman/Eustathios-Spider-V2.5/raw/master/Images/Front%20Left.png)

![Eustathios Spider - V2.5 Render3](https://github.com/eclsnowman/Eustathios-Spider-V2.5/raw/master/Images/Back%20Left.png)

![Eustathios Spider - V2.5 Render4](https://github.com/eclsnowman/Eustathios-Spider-V2.5/raw/master/Images/Back%20Right.png)

![Eustathios Spider - V2.5 Render5](https://github.com/eclsnowman/Eustathios-Spider-V2.5/raw/master/Images/Bottom%20Angled.png)

