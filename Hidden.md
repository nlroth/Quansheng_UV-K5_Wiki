1. Cheat code for Portable Radio CPS V1.0.38 Windows-Program<br>
Show special submenu **"Advance para"**<br>
to show: type qs975gcms<br>
to hide: type rmgcms<br>
<img width="965" alt="image" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/2c54d2ce-a1a3-4a2b-ba6d-d2002f0bcc1e">

(found by @EDB88320)

2. 

Add possiblity to use USB-PD-Cable (USB-C-to-USB-C) or USB-A-to-USB-C-Cable

USB-C Port | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12
-- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | --
  | **GND**| **Vcc** | A8/B8 | CC | d- | d+ | d- | d+ | A8/B8 | CC | **Vcc** | **GND**
  |   ┃  |   |  |┃  |  |  |  |  |  |┃  |  | gnd
  |   ┃  |  |   | 5,1kΩ |  |  |  |  |  | 5,1kΩ |  | 
  |   ┃  |    |  | ┃ |  |  |  |  |  | ┃ |  | gnd
  |   ┗  | ━ | ━━|┻  | ━  | ━  | ━  | ━ | ━━   |┛|  | 

<img width="600" alt="image" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/c36c19d0-7a4b-4ed0-b442-51c84e6e5610">

Insert 2 resistors of 5.1 kΩ each from ground to the CC pins (A5 / B5). This hack requires a good eye and good nerves ;-)<br>
Wiring the two configuration pins CC (Pin3 / Pin10 with 5.1kΩ signals the PD charger that it can apply 5V. Without this resistor-combination, no voltage is applied.

