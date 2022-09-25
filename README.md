# rpi-useful-stuff-md
In this Repository there will be some useful guides for Raspberry Pi's.

---

## CPU Fan control

A permanent fan can be anoying. In the official Raspberry Pi OS there is a option to enable the fan on a specific temperature (only between 60°C and 120°C). It can be found under the 'raspi-config' in performance options -> fan. Please note, that this will only work for 3-wired-fans.
A forum thread about this topic can be found [here](https://forums.raspberrypi.com/viewtopic.php?t=315716).

### CPU Temperature check

```bash
/usr/bin/vcgencmd measure_temp
`````
