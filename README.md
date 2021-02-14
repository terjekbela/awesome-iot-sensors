# IoT sensors tested
| Sensor | Type                   | I2C address | Range      | Accuracy | Resolution | Manufacturer |
| ------ | ---------------------- |:-----------:| ---------- | --------:| ---------- | ------------ |
|SHT2x   |temp, humidity          |0x13         |            |          |            |[Sensirion](https://www.sensirion.com/sht21)|
|VL53L0X |tof ranging             |0x29         |            |          |            |[STMicro](https://www.st.com/en/imaging-and-photonics-solutions/vl53l0x.html)|
|LSM6DS3 |accelerometer, gyro     |0x6a         |            |          |            |[STMicro](https://www.st.com/resource/en/datasheet/lsm6ds3.pdf)|
|BME280  |temp, humidity, pressure|0x76, 0x77   |-40 ~ 85C; 0 ~ 100%rH; 300 ~ 1100hPa; |1C; 3%rH; 1hPa|0.01C; 0.008%rH; 0.18Pa|[BOSCH](https://www.bosch-sensortec.com/products/environmental-sensors/humidity-sensors-bme280)|
|SI1145  |uv, ir, visible light   |0x60         |            |          |            |[SiLabs](https://www.silabs.com/documents/public/data-sheets/Si1145-46-47.pdf)|
|MLX90614|infrared temp           |0x5a         |            |          |            |[Melexis](https://www.melexis.com/en/product/MLX90614/Digital-Plug-Play-Infrared-Thermometer-TO-Can)|
|MLX90615|infrared temp           |0x5b         |            |          |            |[Melexis](https://www.melexis.com/en/product/MLX90615/Digital-Plug-Play-Infrared-Thermometer-Ultra-Small-TO-Can)|
|MCP9808 |precision temp          |0x18         |-40C ~ +125C|     0.25C|0.0625C     |[Microchip](https://ww1.microchip.com/downloads/en/DeviceDoc/25095A.pdf)|
|CCS811  |air quality (co)        |0x5a, 0x5b   |            |          |            |[ScioSense](https://www.sciosense.com/products/environmental-sensors/ccs811-gas-sensor-solution/)|
|BH1750  |light intensity         |0x23, 0x5c   |0~65000lux  |          |            |[Rohm](http://rohmfs.rohm.com/en/products/databook/datasheet/ic/sensor/light/bh1721fvc-e.pdf)|

# IoT sensors ordered
| Sensor    | Manufacturer | Type                         | I2C address | Range | Accuracy | Resolution |
| --------- | ------------ | ---------------------------- | ----------- | ----- | -------- | ---------- |
| APDS-9960 | Broadcom     |rgb and gesture               | https://www.broadcom.com/products/optical-sensors/integrated-ambient-light-and-proximity-sensors/apds-9960
| VEML607x  | Vishay       |uv light                      | https://www.vishay.com/ppg?84277
| SHT3x     | Sensirion    |temp, humidity                | https://www.sensirion.com/sht30/
| TMP102    | TI           |temp                          | https://www.ti.com/product/TMP102
| BME680    | BOSCH        |temp, humidity, pressure, voc |
| MAX44009  | Maxim        |light intensity               |

# Possible # IoT sensors for testing
------------------------------------------------------------------------
SI7021          - SiLabs    - temp, humidity                - https://www.silabs.com/documents/public/data-sheets/Si7021-A20.pdf
HDC1080         - TI        - temp, humidity                - https://www.ti.com/product/HDC1080
MAX301x         - Maxim     - reflectance, particle, pulse  -
MAX31889        - Maxim     - precision temp                -
TSL2591         -           - precision light intensity     -
TSL2561         -           - precision light intensity     -

