# Anycubic Kobra Improved Firmware
### **This project is now discontinued as I changed the motherboard for my Anycubic Kobra. However, this firmware still implements all the features I wanted to implement and was likely close to the final version anyway. Hope you will enjoy it. I will still review pull requests and bugs but I won't be able to test anything from my side**

An improved firmware for the Anycubic Kobra 3d printer (ONLY the Anycubic Kobra)

### Disclaimer
I am not responsible for any damage or malfunction caused to your printer because of those files. Any modding made to your printer is made at your own risk, this includes any damage that could happen in real life.

### Description
This firmware tries to improve the Kobra in many way without compromising quality or lifespan. I will try to add more and more features over time, I'm still learning Marlin. One of my goal is to migrate to latest Marlin. 

### Features
- Replace booting music with a single bip
- Faster auto leveling
- Faster homing
- Slightly faster printing when using default printer settings
- Slightly faster booting speed
- Reduced noise (motherboard fan)

### Known issues
- Linear Advance causes layer shift, might be unfixable

# How to install
1. Go to your printer -> Settings -> About -> Firmware Version -> check your current version
2. Grab an empty SD card and drop the firmware.bin on it
3. Put the SD card in the printer and boot it. The printer will be stuck on the end of the splash screen, don't do anything and wait until the menu appears
4. When the menu appears, go back to About and check your firmware version again, you should see `jojos38 edited Kobra Vx.x.x`
5. Connect your printer to your PC and run the following commands in the same order: `M710 A1 I4 S5` `M500` (This makes the motherboard's fan more silent)
 
 # How to compile
 Full tutorial here: https://www.reddit.com/r/anycubic/comments/y2waxu/tutorial_how_to_build_anycubic_marlin_source_code/
 
 # FAQ
 ### Can I revert to the old version if I don't like it?
 Yes you can, just install the official Anycubic Firmware back
 
 ### Are there any risk in doing that?
 The risk shouldn't be very high but keep in mind that this firmware wasn't extremely tested yet, once again, do this at your own risk.

 ### Can I modify your files to make my own version?
 Yes you can, but please credit me if you publish it (unless you changed everything of course)
