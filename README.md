# Xiaomi-Dafang-as-Wifi-Access-Point
This is a version of the firmware_mod SD card files which uses hostapd to make your wifi cam accessible as a wifi access point

firmware_mod.zip is a functioning example that can be applied straight to the SD card as of [cfw 1.3](https://github.com/EliasKotlyar/Xiaomi-Dafang-Hacks/blob/master/hacks/cfw/dafang/cfw-1.3.bin) on a wyze pan

The config files and the run.sh file are the main things that set up the access point.

For debugging, you can check out the sdcard/log/startup.log after trying to start it up on your device.

This version of run.sh outputs more stuff to that log file to try to see what's up if it doesn't start up right.

The contents of this repository are for educational purposes only.
