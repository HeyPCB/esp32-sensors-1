# HeyPCB ESP32-S3 Sensors 1: Climate & Light

50 ESP32-S3 boards, one sensor each: temperature, humidity, pressure, CO2, gas, thermocouples and light. KiCad 10, JLCPCB-ready, CERN-OHL-S-2.0.

Every board is the same ESP32-S3 template with one sensor: ESP32-S3-WROOM-1-N16R8 (16 MB flash, 8 MB PSRAM, Wi-Fi + Bluetooth LE), USB-C with native USB and an ESD clamp, an AP2112K 3.3 V LDO, BOOT and RESET buttons, power and user LEDs; 30 x 48 mm, 4 layers.

| Wiring | ESP32-S3 pin |
|---|---|
| I2C SDA / SCL | IO8 / IO9 |
| Sensor interrupt | IO7 |
| Analog in | IO1 (ADC1 channel 0) |
| SPI SCK / MOSI / MISO / CS | IO12 / IO11 / IO13 / IO10 |
| Digital / 1-Wire / PDM | IO4, IO5, IO6 |
| User LED | IO48 |

## Boards (50)

| Board | Sensor | DRC errors / unconnected / parity |
|---|---|---|
| [S3 AM2302](boards/am2302/) | Aosong AM2302 (DHT22) humidity and temperature module | 0 / 0 / 0 |
| [S3 APDS-9306](boards/apds9306/) | Broadcom APDS-9306 ambient light sensor | 0 / 0 / 0 |
| [S3 BME280](boards/bme280/) | Bosch BME280 pressure, humidity and temperature sensor | 0 / 0 / 0 |
| [S3 BME680](boards/bme680/) | Bosch BME680 gas, pressure, humidity and temperature sensor | 0 / 0 / 0 |
| [S3 BME688](boards/bme688/) | Bosch BME688 gas, pressure, humidity and temperature sensor | 0 / 0 / 0 |
| [S3 DHT11](boards/dht11/) | Aosong DHT11 humidity and temperature module | 0 / 0 / 0 |
| [S3 DS18B20](boards/ds18b20/) | DS18B20 1-Wire temperature sensor (TO-92) | 0 / 0 / 0 |
| [S3 DS18B20](boards/ds18b20u/) | DS18B20 1-Wire temperature sensor (MSOP-8) | 0 / 0 / 0 |
| [S3 DS28EA00](boards/ds28ea00/) | Maxim DS28EA00 1-Wire temperature sensor with chain I/O | 0 / 0 / 0 |
| [S3 ENS210](boards/ens210/) | ScioSense ENS210 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 GXHTC3](boards/gxhtc3/) | GXCAS GXHTC3 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 HDC1080](boards/hdc1080/) | TI HDC1080 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 HDC2080](boards/hdc2080/) | TI HDC2080 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 KTY82](boards/kty82/) | NXP KTY82 silicon PTC temperature sensor | 0 / 0 / 0 |
| [S3 LDR](boards/ldr/) | GL5528 photoresistor light sensor | 0 / 0 / 0 |
| [S3 LM20](boards/lm20/) | TI LM20 analog temperature sensor | 0 / 0 / 0 |
| [S3 LM75B](boards/lm75b/) | NXP-style LM75B digital temperature sensor | 0 / 0 / 0 |
| [S3 LMT86](boards/lmt86/) | TI LMT86 analog temperature sensor | 0 / 0 / 0 |
| [S3 LMT87](boards/lmt87/) | LMT87 analog temperature sensor | 0 / 0 / 0 |
| [S3 LPS25HB](boards/lps25hb/) | ST LPS25HB MEMS pressure sensor | 0 / 0 / 0 |
| [S3 LTR-303](boards/ltr303/) | Lite-On LTR-303ALS ambient light sensor | 0 / 0 / 0 |
| [S3 MAX31855](boards/max31855/) | Maxim MAX31855K K-thermocouple converter | 0 / 0 / 0 |
| [S3 MAX31856](boards/max31856/) | Maxim MAX31856 universal thermocouple converter | 0 / 0 / 0 |
| [S3 MAX6675](boards/max6675/) | Maxim MAX6675 K-thermocouple converter | 0 / 0 / 0 |
| [S3 MCP9700](boards/mcp9700/) | Microchip MCP9700 analog temperature sensor | 0 / 0 / 0 |
| [S3 MCP9701A](boards/mcp9701/) | Microchip MCP9701A analog temperature sensor | 0 / 0 / 0 |
| [S3 MCP9808](boards/mcp9808/) | Microchip MCP9808 +-0.25 C digital temperature sensor | 0 / 0 / 0 |
| [S3 MPL3115A2](boards/mpl3115a2/) | NXP MPL3115A2 precision altimeter | 0 / 0 / 0 |
| [S3 MS5607](boards/ms5607/) | TE MS5607 barometric pressure sensor (10 cm altimeter) | 0 / 0 / 0 |
| [S3 MS5837](boards/ms5837/) | TE MS5837-30BA waterproof pressure / depth sensor | 0 / 0 / 0 |
| [S3 NTC](boards/ntc/) | Murata 10k NTC thermistor temperature sensor | 0 / 0 / 0 |
| [S3 SCD40](boards/scd40/) | Sensirion SCD40 photoacoustic CO2 sensor | 0 / 0 / 0 |
| [S3 SCD41](boards/scd41/) | Sensirion SCD41 photoacoustic CO2 sensor | 0 / 0 / 0 |
| [S3 SHT30](boards/sht30/) | Sensirion SHT30 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 SHT31](boards/sht31/) | Sensirion SHT31 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 SHT35](boards/sht35/) | Sensirion SHT35 high-accuracy humidity and temperature sensor | 0 / 0 / 0 |
| [S3 SHT40](boards/sht40/) | Sensirion SHT40 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 SHT41](boards/sht41/) | Sensirion SHT41 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 SHT45](boards/sht45/) | Sensirion SHT45 high-accuracy humidity and temperature sensor | 0 / 0 / 0 |
| [S3 SHTC3](boards/shtc3/) | Sensirion SHTC3 humidity and temperature sensor | 0 / 0 / 0 |
| [S3 TC1047A](boards/tc1047/) | Microchip TC1047A analog temperature sensor | 0 / 0 / 0 |
| [S3 TMP100](boards/tmp100/) | TI TMP100 digital temperature sensor | 0 / 0 / 0 |
| [S3 TMP101](boards/tmp101/) | TMP101 digital temperature sensor | 0 / 0 / 0 |
| [S3 TMP102](boards/tmp102/) | TI TMP102 digital temperature sensor | 0 / 0 / 0 |
| [S3 TMP1075](boards/tmp1075/) | TI TMP1075 digital temperature sensor | 0 / 0 / 0 |
| [S3 TMP112](boards/tmp112/) | TI TMP112 high-accuracy temperature sensor | 0 / 0 / 0 |
| [S3 TMP116](boards/tmp116/) | TI TMP116 0.2 C precision temperature sensor | 0 / 0 / 0 |
| [S3 TMP117](boards/tmp117/) | TI TMP117 0.1 C precision temperature sensor | 0 / 0 / 0 |
| [S3 TMP20](boards/tmp20/) | TI TMP20 analog temperature sensor | 0 / 0 / 0 |
| [S3 TMP235](boards/tmp235/) | TI TMP235 analog temperature sensor | 0 / 0 / 0 |

**Not fabricated, assembled or powered.** Every number in a board's README is measured by KiCad 10 on the files in its folder (`report.json`); parts carry LCSC numbers and were in JLCPCB's stock on the date each README gives.

Each board folder holds `kicad/` (project), `fab/` (Gerbers zip, BOM, CPL, STEP, schematic PDF), `media/` (renders) and `board.json` (the brief it was generated from).

Designed with the HeyPCB method on KiCad 10 by heypcb-kicad's headless pipeline with Freerouting 2.4.1.

## Licence

CERN-OHL-S-2.0, © 2026 heypcb.ai. See [LICENSE](LICENSE).
