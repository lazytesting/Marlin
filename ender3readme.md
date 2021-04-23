# compile for ender3PRO 4.2.7

## Steps
1. installed pio and vscode
2. cloned marlin repo (https://github.com/MarlinFirmware/Marlin) branch bugfix-2.0.x
3. change platform.ini, set ```default_envs = STM32F103RET6_creality```
3. copied these files https://github.com/MarlinFirmware/Configurations/tree/bugfix-2.0.x/config/examples/Creality/Ender-3%20Pro/CrealityV427 into /Marlin folder
4. run the command ```pio run```
5. put the firmware-xxx-xxx.bin on a SD card and flash it to the printer