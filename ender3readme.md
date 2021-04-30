# compile for ender3PRO 4.2.7

## Steps taken before
1. installed pio and vscode
2. cloned marlin repo (https://github.com/MarlinFirmware/Marlin) branch bugfix-2.0.x
3. change platform.ini, set ```default_envs = STM32F103RET6_creality```
3. copied these files https://github.com/MarlinFirmware/Configurations/tree/bugfix-2.0.x/config/examples/Creality/Ender-3%20Pro/CrealityV427 into /Marlin folder

## Additionally for BLTouch
1. set some settings (TODO specify)
2. run through this calibration process: https://www.youtube.com/watch?v=y_1Kg45APko
3. used bed leveling visualizer plugin for octoprint and leveled bed based on that (to .1 difference)
4. run through step 2 again
5. printed bed level thingy
6. adjusted z offset based on that result (-.3 in this case)


## build and install
1. run the command ```pio run```
2. put the firmware-xxx-xxx.bin on a SD card and put it into the printer
3. wait a bit

