# PLCC-84-plug
A PLCC-84 plug adapter created out of PCBs

***
Please note, The first revision Rev1A of this plug isn't optimal for SMD-sockets, it is a little too small to give a solid connection on all pins. It fits well and gives good connection in the seemingly tighter PLCC-84-TH-sockets though. A new revision 1B is in the works aiming for that 30.1-30.2 mm sweetspot.

_UPDATE: The Rev.1B is finished and gerbers available for download under Releases as well:_

***

REV 1B:

<br />
<a href="images/PLCC_84_Plug_build_pic13.jpg">
<img src="images/PLCC_84_Plug_build_pic13.jpg" width="512" height="384">
</a>
<br />

Suitable pin headers to use with this plug:<br />
1.27 mm 50 P 1 x 50 Pin Header Single row Right Angle Male<br />
https://www.aliexpress.com/item/32767692043.html
<br /><br />
If you use the pins from the link (0.4mm square) you will get to ~30.2 mm, with the MPE 332-1-040 pins you will end up at ~30.4mm which is perhaps a bit too much for a TH-socket.
<br /><br />
<a href="images/PLCC_84_Plug_build_pic16.jpg">
<img src="images/PLCC_84_Plug_build_pic16.jpg" width="256" height="192">
</a>
<a href="images/PLCC_84_Plug_build_pic15.jpg">
<img src="images/PLCC_84_Plug_build_pic15.jpg" width="256" height="192">
</a>
<a href="images/PLCC_84_Plug_build_pic14.jpg">
<img src="images/PLCC_84_Plug_build_pic14.jpg" width="256" height="192">
</a>

***

With this kind of footprint on the PCB it will take both variants of the plug. Both one with the angled SMT headers like above and one with straight TH-pins like on pics below. As you can see there's no need for the base PCB in the latter case since that footprint is now directly on the main PCB.

***

<a href="images/PLCC_84_Plug_build_pic18.jpg">
<img src="images/PLCC_84_Plug_build_pic18.jpg" width="256" height="192">
</a>
<a href="images/PLCC_84_Plug_build_pic19.jpg">
<img src="images/PLCC_84_Plug_build_pic19.jpg" width="256" height="192">
</a>
<a href="images/PLCC_84_Plug_build_pic20.jpg">
<img src="images/PLCC_84_Plug_build_pic20.jpg" width="256" height="192">
</a>

***

REV 1A:

<br />
<a href="images/PLCC_84_HomebrewPlug_rev1a_vs_Winslow_plug.jpg">
<img src="images/PLCC_84_HomebrewPlug_rev1a_vs_Winslow_plug.jpg" width="512" height="192">
</a>
<br />

Suitable pin headers to use building this plug:<br />
_MPE 332-1-040 Pin headers 2.00 mm, 1X40, angled_ <br />
https://www.reichelt.com/se/en/pin-headers-2-00-mm-1x40-angled-mpe-332-1-040-p119983.html

***

Building: <br />

First use a TH-socket as a Jig and put three support PCBs in the socket, pay attention to orientation (the silk screen marking in the corner). Now put two straight header pins (taken from a 2.0mm pin pitch header) in each corner to center align the PCBs. Now put the bottom PCB in place and put fatter pins (from a 2.54mm pin pitch header) in each of the TH-pad corners and solder to lock everything in position. Cut the four pins with a wire cutter<br />

***

<a href="images/PLCC_84_Plug_build_pic1.jpg">
<img src="images/PLCC_84_Plug_build_pic1.jpg" width="256" height="192">
</a>
<a href="images/PLCC_84_Plug_build_pic2.jpg">
<img src="images/PLCC_84_Plug_build_pic2.jpg" width="256" height="192">
</a>
<br />
<a href="images/PLCC_84_Plug_build_pic3.jpg">
<img src="images/PLCC_84_Plug_build_pic3.jpg" width="256" height="192">
</a>
<a href="images/PLCC_84_Plug_build_pic4.jpg">
<img src="images/PLCC_84_Plug_build_pic4.jpg" width="256" height="192">
</a>

***

To remove the pins from the plastic strip give them a push with a heated solder iron and they will come out easy. Now remove one of the straight pins and start populate with angled pins using the straight pin as a spacer, and start solder them down. Rinse and repeat until done.

***

<a href="images/PLCC_84_Plug_build_pic5.jpg">
<img src="images/PLCC_84_Plug_build_pic5.jpg" width="256" height="192">
</a>
<a href="images/PLCC_84_Plug_build_pic6.jpg">
<img src="images/PLCC_84_Plug_build_pic6.jpg" width="256" height="192">
</a>
<br />
<a href="images/PLCC_84_Plug_build_pic7.jpg">
<img src="images/PLCC_84_Plug_build_pic7.jpg" width="256" height="192">
</a>
<a href="images/PLCC_84_Plug_build_pic8.jpg">
<img src="images/PLCC_84_Plug_build_pic8.jpg" width="256" height="192">
</a>

***

I discovered a good technique to use when soldering the 0.4mm square pins (1.27 mm pin pitch) is to reuse the plastic like in picture below while soldering to get everything to align and look very nice.

***

<a href="images/PLCC_84_Plug_build_pic17.jpg">
<img src="images/PLCC_84_Plug_build_pic17.jpg" width="512" height="384">
</a>

***

When done, use a flat screwdriver and work/lever on the corners elevating the plug a little at a time until it comes out of the socket.

***

<a href="images/PLCC_84_Plug_build_pic9.jpg">
<img src="images/PLCC_84_Plug_build_pic9.jpg" width="256" height="192">
</a>
<a href="images/PLCC_84_Plug_build_pic10.jpg">
<img src="images/PLCC_84_Plug_build_pic10.jpg" width="256" height="192">
</a>
<br />
<a href="images/PLCC_84_Plug_build_pic11.jpg">
<img src="images/PLCC_84_Plug_build_pic11.jpg" width="256" height="192">
</a>
<a href="images/PLCC_84_Plug_build_pic12.jpg">
<img src="images/PLCC_84_Plug_build_pic12.jpg" width="256" height="192">
</a>


***

All done! Happy Hackin'

***

REV 1A:<br /> built with pins used from a SMT header like this: <br />
https://www.aliexpress.com/item/1005002683388545.html <br />
They are not optimal in terms of pin-terminal length. <br />

<a href="images/PLCC_84_Plug_pic1.jpg">
<img src="images/PLCC_84_Plug_pic1.jpg" width="327" height="244">
</a>
<a href="images/PLCC_84_Plug_pic2.jpg">
<img src="images/PLCC_84_Plug_pic2.jpg" width="327" height="244">
</a>

<a href="images/PLCC_84_Plug_build.jpg">
<img src="images/PLCC_84_Plug_build.jpg" width="660" height="330">
</a>

***
REV 1A dimensions:<br /><br />
<a href="images/PLCC_84_Plug_pcbs.jpg">
<img src="images/PLCC_84_Plug_pcbs.jpg" width="660" height="660">
</a>



***


[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
