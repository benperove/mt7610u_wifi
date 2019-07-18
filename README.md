# mt7610u_wifi_sta_v3002_dpo_20130916

Modified for RaspberryPI 3b kernel 4.14.37-v7+ armv7l GNU/Linux
* modified: include/os/rt_linux.h
* modified: os/linux/rt_linux.c

Modified again for RaspberryPI 3b kernel >= 4.15 armv7l GNU/Linux (2019-JUL-18)
* modified: include/os/rt_linux.h
* modified: os/linux/rt_linux.c

https://benperove.com/compiling-drivers-for-raspberry-pi-edimax-ac450-ew-7711ulc-nano-usb-wifi-adapter/

# how to use
```
$ sudo apt-get update && apt-get upgrade
$ rpi-source 
$ sudo rpi-update
$ sudo reboot

$ make -j4
$ sudo make install
$ cp RT2870STA.dat /etc/Wireless/RT2870STA/RT2870STA.dat
$ sudo reboot
```
