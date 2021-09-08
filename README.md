# MIUI debloater script
A universal and easy way to debloat your Xiaomi phone running Miui 12 (and above)

# PREREQUISITES
1. Adb installed on your PC(and its relative drivers if you're using Windows)
2. Device running MIUI (only tested on MIUI 12 and above)
3. Usb debugging enabled on device

# CHOOSING THE RIGHT SCRIPT FOR YOUR NEEDS
First off, there are 2 different scripts:
- Light version
- Extreme version

The light version uninstall only the useless bloatware, the extreme version also uninstalls some system apps which are not gonna break the system integrity, obviously.
If you're using Windows, download the latest .bat script
If you're using any Linux distribution, download the latest .sh script

# HOW TO INSTALL ADB DRIVERS ON WINDOWS
Download [the 15 seconds adb installer](https://forum.xda-developers.com/t/official-tool-windows-adb-fastboot-and-drivers-15-seconds-adb-installer-v1-4-3.2588979/) and follow the instructions and it should work (Otherwise follow [this](https://www.xiaomidriversdownload.com/xiaomi-adb-drivers-official/) guide for installing drivers manually.

# HOW TO INSTALL ADB DRIVERS ON LINUX DISTRIBUTIONS
-Debian & based distributions: sudo apt-get install android-tools-adb
Other distributions: google it lol

# USAGE
Windows: double-click .bat file 
Linux: open terminal in the directory where you saved the file and use the following command: ./<filename>.sh (replace filename with the file name and remove the brackets)
