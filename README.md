**nuphy_air96_v2_ansi_via.numlock_indicator_right_side_led.ff932e.bin**

* numlock indicator on right side led
* custom key to set keyboard indicator color

  load "nuphy-air96-v2-via-indicator_color.json" definition file with usevia.app
  and map the custom key "Keyboard Indicator RGB".

  press "Keyboard Indicator RGB"  
  press 1 or 2 (1: caps lock, 2: num lock)  
  press red/green/blue values (0..255) each followed by enter key  

  example input after "Keyboard Indicator RGB" key to set caps lock indicator red:
  ```
  1255
  0
  0
  ```

  and back to default:
  ```
  10
  128
  128
  ```

