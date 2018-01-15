
Current firmware version v1.85 for DMDMK66 192x64.

Any question, suggestion or bug, contact pinballsp@gmail.com, Skype pinballsp, Whatsapp +34693344445, Facebook https://www.facebook.com/Pinballsp

Files:<br>
dmdmk66.bin --> v1.85 (Date 16-1-2018) <br>
<br>

<b>v1.85 Firmware, new features</b>
<ul>
<li> Fixed a bug with Panel Type; RGB, RBG, BGR.</li>
</ul>


<b>v1.84 Firmware, new features</b>
<ul>
<li> Fixed a bug (first/last row, already  it works well)</li>
<li> Added Auto Palette option (up to 4 color Palettes with automatic change every 25-30 seconds)</li>
<li> Added 10 more colors (total, 29 pre-configured colors available)</li>
<li> Added RGB configuration, allows to create customized colors with their RGB HEX value.</li>
<li> Added configuration of LED Panel type; RGB, BGR, RBG, to install led panels from several manufacturers.</li>
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
<li> TPL, configures the type of Led panel, RGB, RBG or BGR (default RGB) </ li>
<li> CC00 to CC28, set the RGB HEX value for each color, you can modify it to create custom colors. </ li>
<li> PA1 to PA4, color palettes, each line has 16 colors, the first 4 colors for each line are for 4 color pinball machines (WPC, WhiteStar, Data East, Spinball, Capcom). 1-16 colors for 16 color pinball machines (Spike, SAM). If you configure
different colors in each line, the color palette will change automatically during the game, every 25 seconds. </ li>
</ul>


<br><br>

![alt text](https://i.imgur.com/2psMDcu.jpg)
