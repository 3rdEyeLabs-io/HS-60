# HS-60

The HS60 is a POK3R style, hot-swapable keyboard PCB. It is designed and manufactured through a collaboration between <a href="https://mechboards.co.uk/">Mechboards</a> and <a href="https://yiancar-designs.com/">Yiancar</a>.

All HS60s that are purchased through <a href="https://3rdeyelabs.io/">3rd Eye Labs (3eL)</a> come pre-flashed with the 3eL HS60 layout as illustrated in the following images.
![HS-60 Arabic layout](https://github.com/3rdEyeLabs-io/HS-60/blob/main/HS-60%20Arabic.PNG?raw=true)

*__English Layout__*
 
<p align='center'>

![GMK-Metropolis-Base-Layer-English](https://user-images.githubusercontent.com/84006123/124708334-c3f83e80-df17-11eb-9841-437ac611e117.png)

 </p>
  
__*Fn layer*__

<p align='center'>

![GMK-Metropolis-Fn-Layer-English](https://user-images.githubusercontent.com/84006123/124708372-d1152d80-df17-11eb-818d-1f66f482bcc3.png)

</p>

## LAYOUT CHANGES AND FIRMWARE DOWNLOAD

The __*.json*__ file within the repository is the contemporary default english layout. The language can be switched through your OS to arabic.
The firmware can also be downloaded from out repository __*.bin*__ extension is the firmware.

If any changes are required then __*.json*__ file can be uploaded unto the qmk configurator (https://config.qmk.fm/#/hs60/v2/ansi/LAYOUT_60_ansi) by clicking the button next to __*KEYMAP.JSON*__.

The layout and firmware along with the changes can be downloaded post compiling.

## FLASING / UPLOADING THE FIRMWARE ON YOUR KEYBOARD

Step 1: Download QMK Toolbox (https://github.com/qmk/qmk_toolbox/releases/download/0.0.21/qmk_toolbox.exe) \
Step 2: Open QMK Toolbox \
Step 3: Install Drivers (Only for Windows) \
Step 4: Launch QMK Toolbox and Open the correct firmware file \
Step 5: Select the MCU \
Step 6: Reset your keyboard (Enter Bootloader Mode) \
      * Step 6 Option 1: Keymap Reset \
      * Step 6 Option 2: Hold Space + B while plugging in \
      * Step 6 Option 3: Hold Esc while plugging in \
      * Step 6 Option 4: Physical Reset Button (Its a tiny button might be difficult to locate) \
Step 7: Press Flash

The video can be viewed on the given link: https://youtu.be/fuBJbdCFF0Q
