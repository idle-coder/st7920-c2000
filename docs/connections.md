## ST7920 GLCD and LAUNCHXL-F28377S connections

| ST7920   | GLCD   | TMS320F2837xS | LAUNCHXL-F28377S |   SPI    |
| :----:   | :----: | :-----------: | :--------------: | :------: |
| PSB      | PSB    |     GPIO15    |     J4 Pin 37    |   N/A    |
| RS(CS*)  | RS     |     GPIO19    |     J8 Pin 75    |  CS/SS   |
| RW(SID*) | R/W    |     GPIO16    |     J4 Pin 38    | MOSI/SDI |
| E(SCLK*) | E      |     GPIO18    |     J8 Pin 76    |   SCLK   |


#### * These naming is used for SPI Communication
