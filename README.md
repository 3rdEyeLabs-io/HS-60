# HS-60

The HS60 is a POK3R style, hot-swapable keyboard PCB. It is designed and manufactured through a collaboration between <a href="https://mechboards.co.uk/">Mechboards</a> and <a href="https://yiancar-designs.com/">Yiancar</a>.

All HS60s that are purchased through <a href="https://3rdeyelabs.io/">3rd Eye Labs (3eL)</a> come pre-flashed with the 3eL HS60 layout as illustrated in the following images.
<br><br>
<b><i>Layout in Arabic </b></i><br><br>
<p align='center'>
<img width="800" alt="HS-60 Arabic" src="https://user-images.githubusercontent.com/84006123/124785832-d3ea3f80-df64-11eb-9a3a-fd8ddffd1bfc.PNG">
</p>
<br>
<b><i>Layout in English </b></i><br><br>
<p align='center'>
<img width="800" src="https://user-images.githubusercontent.com/84006123/125206241-dcfc4900-e2a3-11eb-8c37-e4e2894504ae.png" alt="Metropolis Eglish Layout">
</p>
<b><i>Fn layer </b></i><br><br>
<p align='center'>
<img width="800" src="https://user-images.githubusercontent.com/84006123/125286535-87727b80-e339-11eb-9aec-c88cdbd7cd06.png" alt="Fn layer">
     Press and hold the 'Fn' key to access this layer.
</p>

## PROGRAMMING THE HS60

The HS60 can be programmed using <a href="https://config.qmk.fm/#/hs60/v2/ansi/LAYOUT_60_ansi">QMK</a> or <a href="https://github.com/the-via/releases/releases/tag/v1.3.1">VIA</a>.

## VIA

Download <a href="https://github.com/the-via/releases/releases/tag/v1.3.1">VIA</a> by selecting the installer for your OS. Plug in the HS60 amd make your changes to the layout. VIA will automatically update the keyboard with the changes you are making in real-time. 

## QMK

## LAYOUT FILES 

The __*.json*__ file within the repository can be used to edit the 3eL HS60 layout using the <a href="https://config.qmk.fm/#/hs60/v2/ansi/LAYOUT_60_ansi">QMK Configurator Tool</a>.

Import the __*.json*__ file to customize the layout. Don't forget to export you changes to save them. Click on 'Compile' and once compiled, download your firmware file for flashing.

## FIRMWARE 

The layout and firmware along with the changes can be downloaded post compiling. Use the downloaded __*.bin*__ file to flash your keyboard with the firmware.

The 3eL HS60 firmware can also be downloaded from out repository as a __*.bin*__ file.

## FLASING THE FIRMWARE

**NOTE: Installing QMK may trigger your computer's antivirus**

Step 1: Download QMK Toolbox for <a href="https://github.com/qmk/qmk_toolbox/releases">Windows or MacOS</a> \
Step 2: Launch QMK Toolbox \
Step 3: Install Drivers (only for Windows) by right-clicking on the 'Flash' button and selecting 'Install Drivers' \
Step 4: Load your firmware file by clicking 'Open' and selecting the __*.bin*__ file \
Step 5: Select the MCU as 'atmega32u4' \
Step 6: Reset your keyboard (Enter Bootloader Mode) \
      * Option 1: Keymap Reset \
      * Option 2: Hold Space + B while plugging in \
      * Option 3: Hold Esc while plugging in \
      * Option 4: Physical Reset Button (Its a tiny button might be difficult to locate) \
Step 7: Click on 'Flash'


