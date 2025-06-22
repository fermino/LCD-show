Refactor of https://github.com/goodtft/LCD-show

I wanted to understand what it was doing and the scripts were not super clean, so I decided to do a refactor for the 3.5 inch screen I had. 
It also fixes the broken touchscreen calibration using xorg_calibrate.

```shell
./install
./set_rotation [0/90/180/270]
reboot
./calibrate_touchscreen
reboot
```
