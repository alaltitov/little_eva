# DIY ESPhome Sensors board

<p align="center">
 <img width="200px" src="https://github.com/alaltitov/little_eva/raw/806d1e9428d014455b41d5a6f9cc051d6284efd3/img/main.jpg">
 <img width="600px" src="https://github.com/alaltitov/little_eva/raw/806d1e9428d014455b41d5a6f9cc051d6284efd3/img/ha.png">
</p>

<p align="center">
    <img alt="Static Badge" src="https://img.shields.io/badge/made%20by-alaltitov-blue">
    <img alt="Static Badge" src="https://img.shields.io/badge/rev-v1.0-green">
    <img alt="Static Badge" src="https://img.shields.io/badge/license-MIT-orange">
</p>

## Features

- Power over Ethernet (PoE) (SDAPO DP1435 module).
- Ethernet (Wiznet W5500).
- Built-in sensors:
   * Temperature and humidity sensor (ENS210).
   * Temperature, humidity, and air quality sensor (Bosch BME680).
   * Temperature, humidity, and CO2 sensor (Sensirion SCD40).
   * Light sensor (BH1750FVI).
- Contact connector for soldering presence sensor (HLK-LD2410c).
- Buzzer.
- Outputs for five GPIOs, second I2C bus, GND, 3V3A, and 3V3D for testing.

## Instalation
Edit sensors.yaml file according to your configuration, for example wi-fi and ota fields.
Flash using a programmer. TX, RX, GND.

<p align="center">
 <img width="200px" src="https://github.com/alaltitov/little_eva/raw/806d1e9428d014455b41d5a6f9cc051d6284efd3/img/uart_ttl.jpg">
</p>

## Future updates

- Development of the enclosure
- Modification of the front PCB design for accurate temperature and humidity sensor readings
