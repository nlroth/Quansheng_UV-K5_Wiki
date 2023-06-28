# 1. Body
## Mainboard
# 2. Antenna


# 4. Charger
<img width="296" alt="image" src="https://github.com/ludwich66/Quansheng_UV-K5_Firmware/assets/12202733/c0781eef-aea1-4ad5-883b-f422187845b2">


# 5. USB-C Charging
* Works only with USB-A to USB-C Cable
* Don't work with USB-C PD (Power-Delivery) to USB-C Cable
# 6. Schematik (KiCad) 
# 7. Parts



Label | Typ | Name | Pin | Case | Manufacturer | Datasheet-Link | Param1 | Param2 | Param3
-- | -- | -- | -- | -- | -- | -- | -- | -- | --
WA | Zenerdiode | PZU10*A/DG | 2 |   | NXP |   | 1,0V |   |  
WD | Zenerdiode | BZT52C8V2 | 2 |   |   |   | 8,2V |   |  
WL | Zenerdiode | PZU12*A/DG | 2 |   | NXP |   | 1,2V |   |  
SS14 | Schottkydiode | SS14 | 2 | DO-214AC |   |   | 40V | 1A |  
R24 |   | 2SC3356 |   | SOT-23 |   |   |   |   |  
R24 SC-70 |   | 2SC4226 |   | SOT-323 |   |   |   |   |  
UD |   | KDS114E |   |   |   |   |   |   |  
TY |   | 1SS241 |   |   |   |   |   |   |  
2TY | PNP | S8550 | 3 |   |   | https://github.com/amnemonic/Quansheng_UV-K5_Firmware/blob/main/hardware/S8550-2TY-PNP_Datasheet.pdf |   |   |  
P6003 |   |   | 3 |   |   |   |   |   |  
NJ |   |   | 3 |   |   |   |   |   |  
BK1080 | FM Receiver IC | BK1080 Beken | 4 x 6 |   | Beken | https://github.com/amnemonic/Quansheng_UV-K5_Firmware/blob/main/hardware/BK1080_Datasheet_V2.7.pdf |   |   |  
XS5822 | Charge IC | 2-4 Cell Bat Charger | 2 x 4 + 1 | E SOP8 | ShenZen ChipSourceTek | https://github.com/amnemonic/Quansheng_UV-K5_Firmware/blob/main/hardware/XS5822_Datasheet_V1.0.pdf |   |   |  
ST7565P | Sitronix ST7565 | 65 x 132 Dot Matrix LCD Controller/Driver |   |   | Sitronix | https://github.com/amnemonic/Quansheng_UV-K5_Firmware/blob/main/hardware/ST7565P_Datasheet_V2.3.pdf |   |   |  
ST7565R | Sitronix ST7566 | 66 x 132 Dot Matrix LCD Controller/Driver |   |   | Sitronix | https://github.com/amnemonic/Quansheng_UV-K5_Firmware/blob/main/hardware/ST7565R_Datasheet_V1.7.pdf |   |   |  
DP32G030 | MicControler |   |   |   | Action Dynamic Tech.(HK) Trading Co. |   |   |   |  
LBF32G030 | MicControler |   |   |   |   |   |   |   |  
LN4898 | AudioAmpl. | Natlinear LN4898 | 2 x 4 | SOP8 | Natlinear | https://github.com/amnemonic/Quansheng_UV-K5_Firmware/blob/main/hardware/LN4898_Datasheet.pdf | 1W |   |  
BL24C64 | EEPROM | Two-wire Serial EEPROM |   | JEDEC SOIC | Shanghai Belling Corp., Ltd | https://github.com/ludwich66/Quansheng_UV-K5_Firmware/blob/main/hardware/BL24C64_Datasheet.pdf | 64K 8192*8 |   |  
2301A | P-Mosfet | Si2301DS | 3 | TO-236 (SOT-23) | Vishay | https://github.com/amnemonic/Quansheng_UV-K5_Firmware/blob/main/hardware/2301A_SI2301_Datasheet.pdf | 2,5V |   | 1,25W
C4 | DualPowermanagemet Transistor | EMC4 / UMC4N / FMC4A | 5 |   |   |   |   |   |  
AN26.0 |   |   |   |   |   |   |   |   |  
Q533 | LDO | AQ533 | 3 | SOT89 | acutechnoligy | https://github.com/amnemonic/Quansheng_UV-K5_Firmware/blob/main/hardware/AQ533_AcutechnologySemiconductor.pdf | 3,3V |   |  
  | LCD | FG12864390-FKFW | 12 |   |   |   | 128x64 px |   |  
AO8814 | Mosfet |   |   |   | Alpha & Omega Semiconductor, Ltd. |   |   |   |  
more... |   |   |   |   |   |   |  




