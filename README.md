# IoT sensors tested
| Sensor | Manufacturer | Type |  I2C address | Range | Accuracy | Resolution | Unit |
| ------ | ------------ | ---- | ----- | -------- | ----- | -------- | ---- |
|SHT2x|[Sensirion](https://www.sensirion.com/sht21)|temp, humidity|0x13|
|VL53L0X|[STMicro](https://www.st.com/en/imaging-and-photonics-solutions/vl53l0x.html)|tof ranging|0x29||||mm
|LSM6DS3|[STMicro](https://www.st.com/resource/en/datasheet/lsm6ds3.pdf)|accelerometer, gyro|0x6a|
|BME280|[BOSCH](https://www.bosch-sensortec.com/products/environmental-sensors/humidity-sensors-bme280)|temp, humidity, pressure|0x76, 0x77|-40 ~ 85C; 0 ~ 100%rH; 300 ~ 1100hPa; |1C; 3%rH; 1hPa|0.01C; 0.008%rH; 0.18Pa| C, rH%, hP
|SI1145|[SiLabs](https://www.silabs.com/documents/public/data-sheets/Si1145-46-47.pdf)|uv, ir, visible light|0x60|
|MLX90614|[Melexis](https://www.melexis.com/en/product/MLX90614/Digital-Plug-Play-Infrared-Thermometer-TO-Can)|infrared temp|0x5a|
|MLX90615|[Melexis](https://www.melexis.com/en/product/MLX90615/Digital-Plug-Play-Infrared-Thermometer-Ultra-Small-TO-Can)|infrared temp|0x5b|
|MCP9808|[Microchip](https://ww1.microchip.com/downloads/en/DeviceDoc/25095A.pdf)|precision temp|0x18|-40C ~ +125C|0.25C|0.0625C|C
|CCS811|[ScioSense](https://www.sciosense.com/products/environmental-sensors/ccs811-gas-sensor-solution/)|air quality (co)|0x5a, 0x5b
|BH1750|[Rohm](http://rohmfs.rohm.com/en/products/databook/datasheet/ic/sensor/light/bh1721fvc-e.pdf)|light intensity|0x23, 0x5c|0~65000lux|||lux

# IoT sensors ordered
------------------------------------------------------------------------
APDS-9960       - Broadcom  - rgb and gesture               - https://www.broadcom.com/products/optical-sensors/integrated-ambient-light-and-proximity-sensors/apds-9960
VEML607x        - Vishay    - uv light                      - https://www.vishay.com/ppg?84277
SHT3x           - Sensirion - temp, humidity                - https://www.sensirion.com/sht30/
TMP102          - TI        - temp                          - https://www.ti.com/product/TMP102
BME680          - BOSCH     - temp, humidity, pressure, voc -.
MAX44009        - Maxim     - light intensity               -.

# Possible # IoT sensors for testing
------------------------------------------------------------------------
SI7021          - SiLabs    - temp, humidity                - https://www.silabs.com/documents/public/data-sheets/Si7021-A20.pdf
HDC1080         - TI        - temp, humidity                - https://www.ti.com/product/HDC1080
MAX301x         - Maxim     - reflectance, particle, pulse  -
MAX31889        - Maxim     - precision temp                -
TSL2591         -           - precision light intensity     -
TSL2561         -           - precision light intensity     -
