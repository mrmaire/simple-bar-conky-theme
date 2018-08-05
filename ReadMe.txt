Bar Conky Theme - V 0.1
===================
I've tested this running an up-to-date Majanro Linux 64bit installation, but I do not know if it works in other distributions.

Installation steps:
====================
1) Put the conkyrc in you ~/.conky folder o install through conky-manager.
2) Make sure your conky version stupport lua and nvidia (arch amd Manjaro: conky-lua-nv)
3) Make sure you've got all the dependencies (hddtemp, iostat, ...) and they are running (also on startup)
4) Make conky_start (and all files in /lua and /scripts) executable.
5) Add conky_start to your startup programs
6) Make sure you've installed the fonts in /fonts
7) Edit the system specific setting, for example in conky_network change it to your wifi/eth interface

Enjoy!
(you can ignore the debug folder)


Updates
====================
-V 0.1 Initial commit

Credits
====================
Based on ideas and code from others themes, especially in "Bottom bar conky config" by Cronosse (https://www.deviantart.com/cronosse/art/Bottom-bar-conky-config-201410602)

Feel free to fork/improve

