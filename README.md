# 65% Keyboard Project Files
## Summary
  Creating a 65% Keyboard from scratch without any prior engineering knowledge.

## Next steps:
  * Connect LEDs to power and ground



## To Do List:
* PCB:
  1. Side Rotary Encoder Implementation -- Incorporated component, need to integrate wiring
  2. Flex Cuts -- Done
  3. Mounting System
  4. LEDs                               -- Done
  5. Daughter Board
  6. Magnetic connection
* Plate
* Case
  1. Design
  2. Backweight
  3. OLED Screen
* Battery
* Program Software QMK/VIA

## BOM:
| Item # | Ref Des | Qty | Manufacturer        | Vendor     | Mfg Part #         | Description/Value                                                                     | Package | Type | Include in PCB |
| ------ | ------- | --- | ------------------- | ---------- | ------------------ | ------------------------------------------------------------------------------------- | ------- | ---- | -------------- |
| 1      |         | 1   | STMicroelectronics  | Mouser     | STM32F103RET6TR    | ARM Microcontrollers - MCU 32BIT Cortex M3 H/D Performance LINE                       | LQFP-64 | SMD  | Yes            |
| 2      |         | 1   | Espressif Systems   | Mouser     | ESP32-S3-MINI-1-N8 | Multiprotocol Modules SMD module, ESP32-S3FN8, 8 MB SPI flash, PCB antenna            |         | SMD  | No             |
| 3      |         | 1   | Adafruit            | Mouser     | 5099               | Adafruit Accessories 1N4148 SMT SOD-123 Diodes - 100 Pack                             |         | SMD  | No             |
| 4      |         | 1   | Kailh               | Cannonkeys |                    | Kailh MX Hotswap Sockets - 110 Pack                                                   |         |      | No             |
| 5      |         | 1   | Azoteq              | Mouser     | IQS6243200DNR      | Board Mount Motion & Position Sensors 2 x Capacitive, Hall rotation                   | DFN-10  | SMD  | Yes            |
| 6      |         |     | Murata Electronics  | Mouser     | GCM188R71C104KA37J | Multilayer Ceramic Capacitors MLCC - SMD/SMT 0.1 uF 16 VDC 10% 0603 X7R AEC-Q200      | 0603    | SMD  | No             |
| 7      |         |     | Murata Electronics  | Mouser     | GRT188C80J475KE01D | Multilayer Ceramic Capacitors MLCC - SMD/SMT 4.7 uF 6.3 VDC 10% 0603 X6S AEC-Q200     | 0603    | SMD  | No             |
| 8      |         |     | Murata Electronics  | Mouser     | GCE188R72A103MA01D | Multilayer Ceramic Capacitors MLCC - SMD/SMT 0.01 uF 100 VDC 20% 0603 X7R AEC-Q200    | 0603    | SMD  | No             |
| 9      |         |     | Murata Electronics  | Mouser     | GCM1885C1H101FA16D | Multilayer Ceramic Capacitors MLCC - SMD/SMT 100 pF 50 VDC 1% 0603 C0G (NP0) AEC-Q200 | 0603    | SMD  | No             |
| 10     |         |     | Murata Electronics  | Mouser     | GRJ188R60J106ME11D | Multilayer Ceramic Capacitors MLCC - SMD/SMT 10 uF 6.3 VDC 20% 0603 X5R               | 0603    | SMD  | No             |
| 11     |         |     | Yageo               | Mouser     | RC0603FR-0710KL    | Thick Film Resistors - SMD 10 kOhms 100mW 0603 1%                                     | 0603    | SMD  | No             |
| 12     |         |     | Yageo               | Mouser     | AC0603FR-07470RL   | Thick Film Resistors - SMD 470 Ohms 100mW 0603 1% AEC-Q200 Standard Power Version     | 0603    | SMD  | No             |
| 13     |         |     | Yageo               | Mouser     | AR0603FR-072KL     | Thick Film Resistors - SMD 2k Ohms 1/10 W 0603% 1% AEC-Q200                           | 0603    | SMD  | No             |
| 14     |         |     | Yageo               | Mouser     | RC0603FR-074K7L    | Thick Film Resistors - SMD 4.7 kOhms 100mW 0603 1%                                    | 0603    | SMD  | No             |
| 15     |         | 1   | TPOWER              |            | TP4056             | 4V~6V Lithium-ion/Polymer 1 1A ESOP-8 Battery Management ROHS                         | ESOP-8  | SMD  | Yes            |
| 16     |         | 1   | Analog Devices Inc. | Mouser     | MAX17048G+T10      | Battery Management 3 A 1-Cell/2-Cell Fuel Gauge with ModelGauge                       | TDFN-8  | SMD  | Yes            |


## Current Component Costs:

* [STM32F103RET6TR:](https://www.mouser.com/ProductDetail/STMicroelectronics/STM32F103RET6TR?qs=SU4Xa%252BYHGQoo%252BSdhqS8onA%3D%3D)
* [ESP32 S3 Mini1](https://www.mouser.com/ProductDetail/Espressif-Systems/ESP32-S3-MINI-1-N8?qs=XAiT9M5g4x82rl6F%2FIYUQg%3D%3D)
* [LEDs:](https://www.aliexpress.us/item/2251832648616581.html?gatewayAdapt=glo2usa4itemAdapt) $2.29 per 70
* [Logitech MX Master 3s Side Scroll](https://www.aliexpress.us/item/3256805736389448.html?spm=a2g0o.order_list.order_list_main.5.6ac41802afgPFI&gatewayAdapt=glo2usa): $33
* [SOD-123 Diodes](https://www.adafruit.com/product/5099): $4.95 for 100
* [Kailh Hotswap Sockets](https://cannonkeys.com/products/kailh-mx-hotswap-sockets?variant=40866971091055) $13.50 for 110
* [Azoteq IQS6243200DNR](https://www.mouser.com/ProductDetail/Azoteq/IQS6243200DNR?qs=T%252BzbugeAwjhoI7UzUjJguA%3D%3D): $.92 for 1, $7.16 for 10
* [Silicone Feet](https://kbdfans.com/products/rubber-feet-pads-hemispherical-shape-eva-silicone-anti-slip?variant=34477878739083): $1.00
* [100nF Capacitors](https://www.mouser.com/ProductDetail/Murata-Electronics/GCM188R71C104KA37J?qs=sGAEpiMZZMsh%252B1woXyUXjz%2FTpxBjfgy%252B4saLU%2F5YL9A%3D)
* [4.7uF Capacitors](https://www.mouser.com/ProductDetail/Murata-Electronics/GRT188C80J475KE01D?qs=drgMNd%252BkGPPmUwtvkdc9pQ%3D%3D)
* [10nF Capacitors](https://www.mouser.com/ProductDetail/Murata-Electronics/GCE188R72A103MA01D?qs=QzBtWTOodeUor5WrvjqxNQ%3D%3D)
* [100pF Capacitors](https://www.mouser.com/ProductDetail/Murata-Electronics/GCM1885C1H101FA16D?qs=QzBtWTOodeVRXxalURqQhA%3D%3D)
* [10uF Capacitors](https://www.mouser.com/ProductDetail/Murata-Electronics/GRJ188R60J106ME11D?qs=qkDYIeTQ%252BEmCBtkqbbJPvw%3D%3D)
* [10k Resistor](https://www.mouser.com/ProductDetail/YAGEO/RC0603FR-0710KL?qs=grNVn54RoB%252B3GtjbJj3wJQ%3D%3D)
* [470 Resistor](https://www.mouser.com/ProductDetail/YAGEO/AC0603FR-07470RL?qs=UoPT7wUmgYIL%252BAaSNjie7Q%3D%3D)
* [2k Resistor](https://www.mouser.com/ProductDetail/YAGEO/AR0603FR-072KL?qs=tggtontpCXNkJWoQ6gNIHQ%3D%3D)
* [4.7k Resistor](https://www.mouser.com/ProductDetail/YAGEO/RC0603FR-074K7L?qs=gt6vzsuosg37y0l7Vt36bQ%3D%3D)
* [TC4056A IC Charger](https://www.aliexpress.us/item/3256807307886458.html?spm=a2g0o.productlist.main.1.61d9610cVypmQt&algo_pvid=f1e5b57a-4862-4e24-9ad6-958678745c93&algo_exp_id=f1e5b57a-4862-4e24-9ad6-958678745c93-0&pdp_ext_f=%7B%22order%22%3A%2262%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%211.10%211.10%21%21%217.98%217.98%21%402103146c17452144318487111e4714%2112000041015484232%21sea%21US%216338026576%21X&curPageLogUid=NGtgRrsVeeht&utparam-url=scene%3Asearch%7Cquery_from%3A)
* [Fuel Gauge IC (Battery Monitoring)](https://www.mouser.com/ProductDetail/Analog-Devices-Maxim-Integrated/MAX17048G%2bT10?qs=D7PJwyCwLAoGnnn8jEPRBQ%3D%3D)