
Current firmware version v1.81 for DMDMK66 128x32.

Any question, suggestion or bug, contact pinballsp@gmail.com, Skype pinballsp, Whatsapp +34693344445, Facebook https://www.facebook.com/Pinballsp

Files:<br>
dmdmk66.bin --> v1.81 (Date 2-12-2017) <br>
<br>
<b>v1.81 Firmnware, wew features</b>
<ul>
<li>Add Multipalette (up to 4 palettes with auto change each 25 seconds)</li>
<li>Add 10 more direct colors (total 29 preconfigured RGB colors)</li>
<li>Add RGB configuration, allow custom colors with HEX RGB value</li>
<li>Fix minor bugs in WPC</li>
</ul>

<b>Update firmware Instructions</b>
<br><br>
Uncompress RAR file and copy dmdmk66.bin file to your SD card (FAT32 formated). Insert the SD card into your DMDMK66. The next time you start your DMDMK66, it will update automatically. <br><br>
When install a new version, remove the dmdmk66.txt file from your SD card, because may be there are new paramaters available, as soon as your DMDMK66 start will create a new dmdmk66.txt configuration file, you may edit to modify configuration (colors, brightness level, palettes, etc...)
<br><br>
<b>Configuration Instructions</b>
<br>
<ul>
<li>BRG, is the brightness level, configure a value between 0 a 9 (suggested 2 if no filter, higher with filter)</li>
<li>1PL, 1 Plane pinball, WPC, Spinball, Capcom (no yet available)</li>
<li>TPL, configure type of Led panel, RGB or RBG (RBG by default)</li>
<li>CC00 to CC28, define de RGB HEX value for each color, you may modify to create custom colors.</li>
<li>PA1 to PA4, colors palettes, each line has 16 colors, the first 4 colors are for 4 colors pinball machines
            (WPC, WhiteStar, Data East, Spinball, Capcom). 1-16 for 16 colors pinball (Spike, SAM). If you configure
            different colors for each line, the color palette will change on play automatically each 25 seconds.</li>
</ul>


<br><br>

![alt text](https://i.imgur.com/4dzc30F.jpg)
