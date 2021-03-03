## ST7920 GLCD and LAUNCHXL-F28377S connections

| ST7920   | GLCD   | TMS320F2837xS | LAUNCHXL-F28377S |   SPI    |
| :----:   | :----: | :-----------: | :--------------: | :------: |
| PSB      | PSB    |     GPIO15    |     J4 Pin 37    |   N/A    |
| RS(CS*)  | RS     |     GPIO19    |     J8 Pin 75    |  CS/SS   |
| RW(SID*) | R/W    |     GPIO16    |     J4 Pin 38    | MOSI/SDI |
| E(SCLK*) | E      |     GPIO18    |     J8 Pin 76    |   SCLK   |


#### * These naming is used for SPI Communication

## GLCD pinout seen from above with LED on the left side.

| 20  | 19  |  18  | 17  | 16 | 15  | 14  | 13  | 12  | 11  | 10  |  9  |  8  |  7  | 6 |  5  | 4  | 3  |  2  |  1  |
| :-: | :-: | :--: | :-: |:--:| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |:-:| :-: |:--:|:--:| :-: | :-: |
| BLK | BLA | VOUT | RST | NC | PSB | DB7 | DB6 | DB5 | DB4 | DB3 | DB2 | DB1 | DB0 | E | R/W | RS | V0 | VCC | GND |
