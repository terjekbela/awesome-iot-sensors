# Awesome IoT Sensors
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
> A curated list of awesome Internet of Things sensors and resources.
Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

# IoT sensors
| Sensor | Type                         | I2C address | Range      | Accuracy | Resolution | Manufacturer                                                                                                         |
| ------ | ---------------------------- |:-----------:| ---------- | --------:| ---------- | -------------------------------------------------------------------------------------------------------------------- |
|VEML6075|uv light                      |0x10         |            |          |            |[Vishay](https://www.vishay.com/ppg?84277)                                                                            |
|MCP9808 |precision temp                |0x18         |-40C ~ +125C|     0.25C|     0.0625C|[Microchip](https://ww1.microchip.com/downloads/en/DeviceDoc/25095A.pdf)                                              |
|BH1750  |light intensity               |0x23, 0x5c   |  0~65000lux|          |            |[Rohm](http://rohmfs.rohm.com/en/products/databook/datasheet/ic/sensor/light/bh1721fvc-e.pdf)                         |
|VL53L0X |tof ranging                   |0x29         |            |          |            |[STMicro](https://www.st.com/en/imaging-and-photonics-solutions/vl53l0x.html)                                         |
|APDS9960|rgb and gesture               |0x39         |            |          |            |[Broadcom](https://www.broadcom.com/products/optical-sensors/integrated-ambient-light-and-proximity-sensors/apds-9960)|
|SHT2x   |temp, humidity                |0x40         |            |          |            |[Sensirion](https://www.sensirion.com/sht21)                                                                          |
|SHT3x   |temp, humidity                |0x44, 0x45   |            |          |            |[Sensirion](https://www.sensirion.com/sht30)                                                                          |
|TMP102  |precision temp                |0x48         |-40C ~ +125C|      0.5C|     0.0625C|[TI](https://www.ti.com/product/TMP102)                                                                               |
|MAX44009|light intensity               |0x4a, 0x4b   |            |          |            |Maxim                                                                                                                 |
|MLX90614|infrared temp                 |0x5a         |            |          |            |[Melexis](https://www.melexis.com/en/product/MLX90614/Digital-Plug-Play-Infrared-Thermometer-TO-Can)                  |
|MLX90615|infrared temp                 |0x5b         |            |          |            |[Melexis](https://www.melexis.com/en/product/MLX90615/Digital-Plug-Play-Infrared-Thermometer-Ultra-Small-TO-Can)      |
|CCS811  |air quality (co)              |0x5a, 0x5b   |            |          |            |[ScioSense](https://www.sciosense.com/products/environmental-sensors/ccs811-gas-sensor-solution/)                     |
|SI1145  |uv, ir, visible light         |0x60         |            |          |            |[SiLabs](https://www.silabs.com/documents/public/data-sheets/Si1145-46-47.pdf)                                        |
|LSM6DS3 |accelerometer, gyro           |0x6a, 0x6a   |            |          |            |[STMicro](https://www.st.com/resource/en/datasheet/lsm6ds3.pdf)                                                       |
|VEML6070|uv light                      |0x70         |            |          |            |[Vishay](https://www.vishay.com/ppg?84277)                                                                            |
|BME280  |temp, humidity, pressure      |0x76, 0x77   |-40 ~ +85C<br/>0 ~ 100%rH<br/>300 ~ 1100hPa; |1C<br/>3%rH<br/>1hPa|0.01C<br/>0.008%rH<br/>0.18Pa|[BOSCH](https://www.bosch-sensortec.com/products/environmental-sensors/humidity-sensors-bme280)|
|BME680  |temp, humidity, pressure, voc |0x76, 0x77   |            |          |            |BOSCH                                                                                                                 |
|LM75A   |temp                          |0x48 ~ 0x4f  |-55C ~ +125C|        2X|        9bit|[TI](https://www.ti.com/lit/ds/symlink/lm75a.pdf)                                                                     |
|TMP175  |temp                          |             |            |        1C|     0.0625C|                                                                                                                      |

# Possible # IoT sensors for testing
| Sensor | Type                         | I2C address | Range      | Accuracy | Resolution | Manufacturer                                                                                                         |
| ------ | ---------------------------- |:-----------:| ---------- | --------:| ---------- | -------------------------------------------------------------------------------------------------------------------- |
|SI7021  |temp, humidity                |             |            |          |            |[SiLabs](https://www.silabs.com/documents/public/data-sheets/Si7021-A20.pdf)                                          |
|SI7051  |precision temp                |             |            |          |            |SiLabs                                                                                                                |
|HDC1080 |temp, humidity                |             |            |          |            |[TI](https://www.ti.com/product/HDC1080)                                                                              |
|MAX301x |reflectance, particle, pulse  |             |            |          |            |Maxim                                                                                                                 |
|MAX31889|precision temp                |             |            |          |            |Maxim                                                                                                                 |
|TSL2591 |precision light intensity     |             |            |          |            |                                                                                                                      |
|TSL2561 |precision light intensity     |             |            |          |            |                                                                                                                      |
|TSYS01  |                              |             |            |          |            |                                                                                                                      |
|BMP390  |precision pressure            |             |            |          |            |BOSCH                                                                                                                 |
|AHT10   |                              |             |            |          |            |                                                                                                                      |
|SHTC3   |temp, humidity                |0x70         |            |          |            |[Sensirion](https://www.sensirion.com/shtc3)                                                                          |

# Contributing
Your contributions are always welcome! Please submit a pull request or create an issue to add a new sensor.
