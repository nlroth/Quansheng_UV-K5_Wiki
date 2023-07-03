1. Cheat code for Portable Radio CPS V1.0.38 Windows-Program<br>
Show special submenu **"Advance para"**<br>
to show: type qs975gcms<br>
to hide: type rmgcms<br>
<img width="965" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/2c54d2ce-a1a3-4a2b-ba6d-d2002f0bcc1e">

(found by @EDB88320)

2. 

Add possiblity to use USB-PD-Cable (USB-C-to-USB-C) or USB-A-to-USB-C-Cable

<img width="600" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/79a76a31-6c8b-4c9c-968b-cb66362b6c9a">
<br>
<img width="600" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/ff91c870-f76d-4424-ae78-a4a790c51e0f">


USB-C Port |  |  |  |  |  |  |  |  |  |  |  | USB-C
-- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | --
Soldersite  | **GND**| Vbus | **CC** | SBU | bD- | aD+ | aD- | bD- | **CC**  | SBU | Vbus | **GND**
  |▮ ▮|▮ ▮|▮|▮|▮|▮|▮|▮|▮|▮|▮ ▮|▮ ▮
  |   ┃  |   | ┃ |  |  |  |  |  | ┃ |  |  | 
  |   ┃  |  | 5,1kΩ  |  |  |  |  |  | 5,1kΩ |  |  | 
  |   ┃  |    | ┃ |  |  |  |  |  |┃  |  |  |
  |   ┗  | ━ |┻| ━━ | ━  | ━  | ━  | ━ | ┛  ||  | 

<img width="600" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/e54d4466-6392-4ecd-9c17-81ec3de9c037">

Insert 2 resistors of 5.1 kΩ each from ground to the CC pins (A5 / B5). This hack requires a good eye and good nerves ;-)<br>
Wiring the two configuration pins CC (Pin3 / Pin10 with 5.1kΩ signals the PD charger that it can apply 5V. Without this resistor-combination, no voltage is applied.

