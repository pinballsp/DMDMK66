
Current firmware version v1.81 for DMDMK66 128x32..

Any question, suggestion or bug, contact pinballsp@gmail.com, Skype pinballsp, Whatsapp +34693344445, Facebook https://www.facebook.com/Pinballsp

Files:<br>
dmdmk66.bin --> v1.81 (Date 2-12-2017) <br>
<br>
<b>v1.81 Firmnware, wew features</b>
<ul>
<li>Add Multi palette option (up to 4 color palettes with automatic change every 25 seconds) </li>
<li>Add 10 more colors (a total of 29 preconfigured RGB colors)</li>
<li>Add RGB settings, allow custom colors with their RGB HEX value</li>
<li>Fix minor bugs in WPC</li>
</ul>

<b>Instructions for updating the Firmware</b>
<br><br>
Unzip the RAR file and copy the dmdmk66.bin file to your SD card (formatted to FAT32). Insert the SD card in the DMDMK66. The next time the DMDMK66 starts, it will update automatically.<br><br>
When you install a new version, delete the dmdmk66.txt file from the SD card, as there may be new parameters available. As soon as you start DMDMK66, a new configuration file dmdmk66.txt will be created, you can edit it to modify the configuration (colors, brightness level, palettes, etc.)
<br><br>
<b>Configuration Instructions</b>
<br>
<ul>
<li> BRG, is the brightness level, set a value between 0 and 9 (2 is suggested if there is no filter, higher with filter) </ li>
<li> 1PL, 1-Plane Pinball, WPC, Spinball, Capcom (not yet available) </ li>
<li> TPL, configures the type of Led panel, RGB or RBG (default RGB) </ li>
<li> CC00 to CC28, set the RGB HEX value for each color, you can modify it to create custom colors. </ li>
<li> PA1 to PA4, color palettes, each line has 16 colors, the first 4 colors for each line are for 4 color pinball machines (WPC, WhiteStar, Data East, Spinball, Capcom). 1-16 colors for 16 color pinball machines (Spike, SAM). If you configure
different colors in each line, the color palette will change automatically during the game, every 25 seconds. </ li>
</ul>


<br><br>

![alt text](https://i.imgur.com/4dzc30F.jpg)
