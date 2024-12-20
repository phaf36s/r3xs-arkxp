# r3xs-arkxp
Windows XP-esque logo and GIF animation for R3XS portable game consoles.

Made by phaf36s (phafael_ on Reddit).

You may share this anywhere you want.

## UPDATE: New versions with colored squares representing the R3XS's face buttons. 
There are two versions: labeled, with gray squares and colored ABXY buttons, and colored, with the squares following the same color pattern as the console's buttons.

![Screenshot](/ArkXP/Windows_XP-esque_logo_white_w_colored_buttons_+_black_bg_1000px.png)

![Screenshot](/ArkXP/Windows_XP-esque_logo_white_w_labeled_buttons_+_black_bg_1000px.png)

# Installation
**OPTIONAL: An old PC BIOS screen with three different variations depending on your SD card setup is also available [here](https://www.reddit.com/r/R36S/comments/1gcs774/boot_logo_and_loading_screen_mega_pack_400_images/). Shoutout to u/\_manster\_ for making these!**

**Attention: The theme may change the OS build version data on Emulation Station's main menu. To fix this, you will have to adjust the "title=ArkOS 2.0 (VERSION NUMBER)(AeUX)" line on the .plymouth file to match your current version.**


## Plymouth theme installation
Make sure ArkOS is updated to the latest [community version](https://github.com/AeolusUX/ArkOS-R3XS). Thanks u/AeolusUX!
* Insert your TF1-OS card in your computer and navigate to EASYROMS/tools and create a folder there named plymouthThemes (make it case sensitive, just in case. I recommend doing the same on the TF2-GAME card, if you have a two-card setup).
* Download [Plymouth Theme Selector](https://www.reddit.com/r/R36S/comments/1gnri3v/plymouth_theme_selector/). Thanks to u/Sucharek233 for creating this tool.
* Paste the Plymouth-cp.sh script in the tools folder.
* Extract the two themes folders from the latest release of the XP-esque boot screen into tools/plymouthThemes.
* On the console, go to the options menu.
* Open the Tools folder (if folders are visible in the menu), select and run Plymouth (if you have a black screen, press start + select, wait a few minutes and try again).
* In the theme selector menu, select the first option and check if the themes are visible there. If not, repeat the third and fourth steps on the TF2-GAME card.
* Select your desired theme and make sure it's working by selecting the "Preview theme" option.

## EmulationStation logo installation
Requires a computer running Linux to access root partition of TF1-OS.
* Rename Windows XP-esque_logo_white_low_detail.svg to splash.svg.
* Copy splash.svg to root/bin/emulationstation/resources.
* Replace existing file if prompted.
* Insert SD card into the TF1-OS slot of the console and boot. 

<!-- 
## Loading GIF installation (
Make sure ArkOS is updated to the latest [community version](https://github.com/AeolusUX/ArkOS-R3XS)!
* Rename winxpesque.gif to loading.gif.
* Copy loading.gif to the launchimages folder in your TF1 Card.
* Replace existing file if prompted.
* Insert SD Card into the TF1-OS slot of the console and boot.
* Move over to Options on the main screen and scroll down until you see the option "Set Launchimage to gif". Select it and hit the A button. -->
