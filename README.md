**nuphy_air96_v2_ansi_via.6450219c.bin**

caps/num lock indicator configuration support added, forked from  
https://github.com/nuphy-src/qmk_firmware/commit/1389eccac3457edd52b100d2c78a7a7fde90dd77  
default rgb matrix "reactive wide"  
default num lock indicator on num lock key led  

keyboard indicator configuration
--------------------------------

  load "nuphy-air96-v2-via-keyb_indicator_config.json" definition file with usevia.app
  and map the custom key "Keyboard Indicator config".

  press "Keyboard Indicator config"  
  press 'c' or 'n' followed by 0..2 to select indicator led for caps/numlock  
  press red/green/blue values (0..255) each followed by <enter> key to select color  

examples
--------

  press "Keyboard Indicator config" key before each example

  caps lock indicator on "caps lock key led" in red
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

