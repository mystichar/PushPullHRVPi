# PushPullHRVPi
Project files associated with running the DIY Push-Pull Heat Regeneration Ventilator

## Diagram

![Wiring Diagram](bad_diagram.png)

| Raspberry Pi | H-Bridge |
| ------ | ---- |
| Pin 2  | +5V  |
| Pin 6  | GND  |
| Pin 12 | PWMI |
| Pin 11 | IN1  |
| Pin 13 | IN2  |
| Pin 15 | IN3  |
| Pin 16 | IN4  |
| Pin 22 | INA  |

|  Psu   |   H-Bridge   |
| ------ | ------------ |
| DC+24V (with 15 amp breaker) |  '15A Fuse'  |
| DC-24V |   '6.5-27V'  |

## Parts:

Raspberry Pi 4B+

### Electronics
![PSU Diagram](https://m.media-amazon.com/images/I/61sPRhs5poL._AC_SL1000_.jpg)
PSU: https://www.amazon.com/dp/B06XK2ZNKC?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1

![Motor Driver Diagram](https://m.media-amazon.com/images/I/71mdTEIyb-L._AC_SX679_.jpg)
Motor Driver Board: https://www.amazon.com/dp/B06XGD5SCB?ref=ppx_yo2ov_dt_b_fed_asin_title

10 Amp breakers: https://www.amazon.com/dp/B08QVHQ5WR?ref=ppx_yo2ov_dt_b_fed_asin_title

15 Amp breakers: https://www.amazon.com/dp/B08QV7WMFH?ref=ppx_yo2ov_dt_b_fed_asin_title

![Radial Blower Diagram](https://m.media-amazon.com/images/I/61qU3xpEIjL._AC_SL1001_.jpg)
Radial Blower: https://www.amazon.com/dp/B00ZFPDLE2?ref=ppx_yo2ov_dt_b_fed_asin_title

### HVAC
End-Caps: https://www.amazon.com/dp/B0BWKBY232?ref=ppx_yo2ov_dt_b_fed_asin_title
Y-Splitter: https://www.amazon.com/dp/B0CF9XGQP9?ref=ppx_yo2ov_dt_b_fed_asin_title
Vent Filter: https://www.amazon.com/dp/B0DP71H3J6?ref=ppx_yo2ov_dt_b_fed_asin_title
Vent Cap: https://www.amazon.com/dp/B09MYMDRP3?ref=ppx_yo2ov_dt_b_fed_asin_title
Catalytic Converter (ERV Core): https://www.amazon.com/dp/B0CNQTBZLS?ref=ppx_yo2ov_dt_b_fed_asin_title


