# HeyPCB ESP32-S3 Sensors 1: Climate & Light

ESP32-S3 boards, one sensor each: temperature, humidity, pressure, CO2, gas, thermocouples and light. KiCad 10, JLCPCB-ready, CERN-OHL-S-2.0.

Every board is the same ESP32-S3 template with one sensor: ESP32-S3-WROOM-1-N16R8 (16 MB flash, 8 MB PSRAM, Wi-Fi + Bluetooth LE), USB-C with native USB and an ESD clamp, an AP2112K 3.3 V LDO, BOOT and RESET buttons, power and user LEDs; 30 x 48 mm, 4 layers.

| Wiring | ESP32-S3 pin |
|---|---|
| I2C SDA / SCL | IO8 / IO9 |
| Sensor interrupt | IO7 |
| Analog in | IO1 (ADC1 channel 0) |
| SPI SCK / MOSI / MISO / CS | IO12 / IO11 / IO13 / IO10 |
| Digital / 1-Wire / PDM | IO4, IO5, IO6 |
| User LED | IO48 |

## Boards (17)

| Board | Sensor | DRC errors / unconnected / parity |
|---|---|---|
| [S3 BME280](boards/bme280/) | Bosch BME280 pressure, humidity and temperature sensor | 0 / 0 / 0 |
| [S3 DS18B20](boards/ds18b20u/) | DS18B20 1-Wire temperature sensor (MSOP-8) | 0 / 0 / 0 |
| [S3 ENS210](boards/ens210/) | ScioSense ENS210 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 HDC1080](boards/hdc1080/) | TI HDC1080 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 HDC2080](boards/hdc2080/) | TI HDC2080 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 LMT86](boards/lmt86/) | TI LMT86 analog temperature sensor | 0 / 0 / 0 |
| [S3 LTR-303](boards/ltr303/) | Lite-On LTR-303ALS ambient light sensor | 0 / 0 / 0 |
| [S3 MCP9700](boards/mcp9700/) | Microchip MCP9700 analog temperature sensor | 0 / 0 / 0 |
| [S3 SHT31](boards/sht31/) | Sensirion SHT31 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 SHT35](boards/sht35/) | Sensirion SHT35 high-accuracy humidity and temperature sensor | 0 / 0 / 0 |
| [S3 SHT40](boards/sht40/) | Sensirion SHT40 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 SHTC3](boards/shtc3/) | Sensirion SHTC3 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 TMP100](boards/tmp100/) | TI TMP100 digital temperature sensor | 0 / 0 / 0 |
| [S3 TMP102](boards/tmp102/) | TI TMP102 digital temperature sensor | 0 / 0 / 0 |
| [S3 TMP112](boards/tmp112/) | TI TMP112 high-accuracy temperature sensor | 0 / 0 / 0 |
| [S3 TMP116](boards/tmp116/) | TI TMP116 0.2 C precision temperature sensor | 0 / 0 / 0 |
| [S3 TMP117](boards/tmp117/) | TI TMP117 0.1 C precision temperature sensor | 0 / 0 / 0 |

**Not fabricated, assembled or powered.** Every number in a board's README is measured by KiCad 10 on the files in its folder (`report.json`); parts carry LCSC numbers and were in JLCPCB's stock on the date each README gives.

Each board folder holds `kicad/` (project), `fab/` (Gerbers zip, BOM, CPL, STEP, schematic PDF), `media/` (renders) and `board.json` (the brief it was generated from).

Designed with the HeyPCB method on KiCad 10 by heypcb-kicad's headless pipeline with Freerouting 2.4.1.

## Licence

CERN-OHL-S-2.0, © 2026 heypcb.ai. See [LICENSE](LICENSE).
