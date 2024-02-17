
[nuphy_air96_v2_ansi_via.6450219c.bin](https://github.com/bugbuster-dev/nuphy-firmware/blob/main/nuphy_air96_v2_ansi_via.6450219c.bin)
--------------------------------

nuphy air96 v2 qmk firmware forked from https://github.com/nuphy-src/qmk_firmware/commit/1389eccac3457edd52b100d2c78a7a7fde90dd77

* caps/num lock indicator can be configured to set indicator off, on side led or on the lock key
* default rgb matrix "reactive wide"  
* default num lock indicator on num lock key led

keyboard indicator configuration
--------------------------------

1.  load [nuphy-air96-v2-via-keyb_indicator_config.json](https://github.com/bugbuster-dev/nuphy-firmware/blob/main/nuphy-air96-v2-via-keyb_indicator_config.json) definition file with usevia.app and map the custom key "Keyboard Indicator config".
2.  press "Keyboard Indicator config"  
3.  press **c** or **n** for caps/num lock selection followed by 0|1|2 to select indicator led: 0=off, 1=side led, 2=lock key
4.  press red/green/blue values (0..255) each followed by "enter" key to select color  

examples
--------

press "Keyboard Indicator config" key before each example

caps lock indicator on "caps lock key" in red
```
c2255
0
0
```

caps lock indicator on (left) side led in green
```
c10
255
0
```

caps lock indicator disabled
```
c0
<esc>
```

num lock indicator on (right) side led in blue
```
n10
0
255
```

