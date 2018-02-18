
Current stable firmware version v1.83 for DMDMK66 128x32.<br>
Last BETA version v1.84, Add support to SPIKE (yet under test)

Any question, suggestion or bug, contact pinballsp@gmail.com, Skype pinballsp, Whatsapp +34693344445, Facebook https://www.facebook.com/Pinballsp

<b>Files:</b> dmdmk66.bin --> v1.83 (Date 20-12-2017) <br>
<b>Files:</b> dmdmk66.bin --> v1.84 Beta (Date 18-2-2018) <br>

<br><b>v1.84 BETA Firmware, new features</b>
<ul><li>Added SPIKE pinball. This is a Beta under test. Automatic detection: the user does not need to configure the pinball manufacturer, the firmware detects it automatically. Automatic synchronization, avoids the loss of horizontal synchronism (lateral displacements of the image). </ Li></ul>


<br><b>v1.83 Firmware, new features</b><ul><li>Added CAPCOM pinball. Tested, works at 100%, Automatic detection: the user does not need to configure the pinball manufacturer, the firmware detects it automatically. Automatic synchronization, avoids the loss of horizontal synchronism (lateral displacements of the image). </ Li></ul>
<b>v1.82 Firmware, new features</b><ul>
<li>Added Auto Sync routine: avoids the problems of loss of horizontal synchronism (lateral displacements of the image) that happened with Bally/Williams, now all works perfectly.</li>
</ul>
<b>v1.81 Firmnware, new features</b>
<ul>
<li>Added Auto Palette option (up to 4 color Palettes with automatic change every 25-30 seconds)</li>
<li>Added 10 more colors (total, 29 pre-configured colors available)</li>
<li>Added RGB configuration, allows to create customized colors with their RGB HEX value</li>
<li>Fixed minor bugs in WPC</li>
</ul>

<b>Instructions for updating the Firmware</b>
<br><br>
Copy the dmdmk66.bin file to your SD card (formatted to FAT32). Insert the SD card in the DMDMK66. The next time the DMDMK66 starts, it will update automatically.<br><br>
When you install a new version, delete the dmdmk66.txt file from the SD card, as there may be new parameters available. As soon as you start DMDMK66, a new configuration file dmdmk66.txt will be created, you can edit it to modify the configuration (colors, brightness level, palettes, etc.)
<br><br>
<b>Configuration Instructions</b>
<br>
<ul>
<li> BRG, is the brightness level, set a value between 0 and 9 (suggest, 0 without filter, 2 with Amber filter) </ li>
<li> TPL, configures the type of Led panel, RGB or RBG (default RGB) </ li>
<li> CC00 to CC28, set the RGB HEX value for each color, you can modify it to create custom colors. </ li>
<li> PA1 to PA4, color palettes, each line has 16 colors, the first 4 colors for each line are for 4 color pinball machines (WPC, WhiteStar, Data East, Spinball, Capcom). 1-16 colors for 16 color pinball machines (Spike, SAM). If you configure
different colors in each line, the color palette will change automatically during the game, every 25 seconds. </ li>
</ul>


<br><br>

![alt text](https://i.imgur.com/4dzc30F.jpg)
