# DogPicoBase
Board with Electronic Assembly DOG graphic display for the Raspberry Pi Pico

## pin usage

### Raspberry Pi Pico connector CN1

| **Pin** | **Pin Name** | **Signal**    | **Description**                  |
|:-------:|:------------:|:-------------:|:--------------------------------:|
| 1       | GP0          | DIS_A0        | data/command for display         |
| 2       | GP1          | DIS_RESET     | reset for display                |
| 3       | GND          | GND           |                                  |
| 4       | GP2          |               |                                  |
| 5       | GP3          |               |                                  |
| 6       | GP4          |               |                                  |
| 7       | GP5          |               |                                  |
| 8       | GND          | GND           |                                  |
| 9       | GP6          | DIS_CLK       | clock for display on SPI0        |
| 10      | GP7          | DIS_SI        | data for display on SPI0         |
| 11      | GP8          |               |                                  |
| 12      | GP9          |               |                                  |
| 13      | GND          | GND           |                                  |
| 14      | GP10         |               |                                  |
| 15      | GP11         |               |                                  |
| 16      | GP12         | I2C0_SDA      | to connector CN3                 |
| 17      | GP13         | I2C0_SCL      | to connector CN3                 |
| 18      | GND          | GND           |                                  |
| 19      | GP14         | DIS_CS        | chip select for display          |
| 20      | GP15         |               |                                  |
| 21      | GP16         | UART0_TX      | to connector CN2                 |
| 22      | GP17         | UART0_RX      | to connector CN2                 |
| 23      | GND          | GND           |                                  |
| 24      | GP18         | I2C1_SDA      | to connector CN4                 |
| 25      | GP19         | I2C1_SCL      | to connector CN4                 |
| 26      | GP20         | DISPLAY_BL_3  | backlight channel 3              |
| 27      | GP21         | DISPLAY_BL_2  | backlight channel 2              |
| 28      | GND          | GND           |                                  |
| 29      | GP22         | DISPLAY_BL_1  | backlight channel 1              |
| 30      | RUN          | RESET         | Reset for Board                  |
| 31      | GP26         | KEYPAD_A0     | analog input for keys            |
| 32      | GP27         |               |                                  |
| 33      | GND          | GND           |                                  |
| 34      | GP28         |               |                                  |
| 35      | ADC_VREF     |               |                                  |
| 36      | 3V3 (OUT)    | 3V3-rail      | supply voltage for board         |
| 37      | 3V3_EN       |               |                                  |
| 38      | GND          | GND           |                                  |
| 39      | VSYS         |               |                                  |
| 40      | VBUS         | 5V-rail       | supply voltage for board         |

### Qwiic I2C connector CN3

compatible to Sparkfun Qwiic. JST SH 1mm 4-pin.

| **Pin** | **Signal**    | **Description**                  |
|:-------:|:-------------:|:--------------------------------:|
| 1       | GND           |                                  |
| 2       | VCC           |                                  |
| 3       | I2C0_SDA      |                                  |
| 4       | I2C0_SCL      |                                  |

### Qwiic I2C connector CN4

compatible to Sparkfun Qwiic. JST SH 1mm 4-pin.

| **Pin** | **Signal**    | **Description**                  |
|:-------:|:-------------:|:--------------------------------:|
| 1       | GND           |                                  |
| 2       | VCC           |                                  |
| 3       | I2C1_SDA      |                                  |
| 4       | I2C1_SCL      |                                  |

### serial connector CN2

JST SH 1mm 4-pin.

| **Pin** | **Signal**    | **Description**                  |
|:-------:|:-------------:|:--------------------------------:|
| 1       | GND           |                                  |
| 2       | VCC           |                                  |
| 3       | UART0_TX      |                                  |
| 4       | UART0_RX      |                                  |

