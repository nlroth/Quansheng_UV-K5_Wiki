# 1. Sound

<img width="600" alt="image" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/7e408fac-2379-46d8-a14e-c20e10f2b681"><br>
1. violet ⇅ 1nF<br>
2. red ⇅ 1µF

<img width="600" alt="image" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/0581399f-fdf2-41b6-971d-51a20a20e985"><br>
<img width="600" alt="image" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/40b9697b-411f-4a08-8b09-2bf3b42278ac">
<br>
who did it?<br> 
Matteo?<br> 
BK7IKD<br>
<br>
[YT-Video "Quansheng uv-k5 - audio Hi-Cut (1nF capacitor) hardware mod. AirBand test." from Andrzej Kuczwara](https://www.youtube.com/watch?v=j4ccuYOg2NU)
<br>
# 2. Possiblity to use USB-PD-Cable (USB-C-to-USB-C) or USB-A-to-USB-C-Cable

USB-C Port | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12
-- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | --
  | **GND**| **Vcc** | A8/B8 | CC | d- | d+ | d- | d+ | A8/B8 | CC | **Vcc** | **GND**
  |   ┃  |   |  |┃  |  |  |  |  |  |┃  |  | gnd
  |   ┃  |  |   | 5,1kΩ |  |  |  |  |  | 5,1kΩ |  | 
  |   ┃  |    |  | ┃ |  |  |  |  |  | ┃ |  | gnd
  |   ┗  | ┻ | ━━| ━  | ━  | ━  | ━  | ━ | ━━   |┛|  | 

<img width="600" alt="image" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/c36c19d0-7a4b-4ed0-b442-51c84e6e5610">

Insert 2 resistors of 5.1 kΩ each from ground to the CC pins (A5 / B5). This hack requires a good eye and good nerves ;-)<br>
Wiring the two configuration pins (Pin3 / Pin10 with 5.1kΩ signals the PD charger that it can apply 5V. Without this resistor-combination, no voltage is applied.

↧↥ ⇅ 