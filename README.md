# Anycubic Kobra Improved Firmware
An improved firmware for the Anycubic Kobra 3d printer (ONLY the Anycubic Kobra)

### Disclaimer
I am not responsible for any damage or malfunction caused to your printer because of those files. Any modding made to your printer is made at your own risk, this includes any damage that could happen in real life.

### Description
For now it's still very basic I only enabled Linear Advance, but maybe I will change other things in the future

### Features
- Replace booting music with a single bip
- Faster auto leveling
- Faster homing
- Slightly faster printing when using default printer settings
- Slightly faster booting speed
- Reduced noise (motherboard fan)
- Linear Advance enabled

### Known issues
- None

### Other things to know
I can provide the list of softwares I used to build my own firmware if needed here is my Discord: jojos38#1337

# How to install
1. Go to your printer -> Settings -> About -> Firmware Version -> check your current version
2. Grab an empty SD card and drop the firmware.bin on it
3. Put the SD card in the printer and boot it. The printer will be stuck on the end of the splash screen, don't do anything and wait until the menu appears
4. When the menu appears, go back to About and check your firmware version again, you should see `jojos38 edited Kobra Vx.x.x`
5. Connect your printer to your PC and run the following commands in the same order: `M710 A1 I4 S5` `M500` (This makes the motherboard's fan more silent)
 
 # FAQ
 ### Can I revert to the old version if I don't like it?
 Yes you can, just install the official Anycubic Firmware back
 
 ### Are there any risk in doing that?
 In the current state there should be no risk but keep in mind that this firmware wasn't extremely tested yet, once again, do this at your own risk.

 ### Can I modify your files to make my own version?
 Yes you can, but please credit me if you publish it (unless you changed everything of course)
