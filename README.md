# IoT Temperature Monitoring System

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![MicroPython](https://img.shields.io/badge/MicroPython-ESP8266-green)](https://micropython.org/)
[![IoT](https://img.shields.io/badge/Platform-IoT-ff69b4)](https://thingsboard.io/)

A real-time IoT system for monitoring temperature and humidity using ESP8266 modules and DHT11 sensors. The system triggers LED alerts for abnormal conditions and integrates with the ThingsBoard IoT platform for cloud-based data visualization.

---

## Key Features
- **Real-Time Monitoring**: Collect temperature and humidity data using DHT11 sensors.
- **LED Alerts**: Visual alerts (LEDs) for high/low temperature thresholds.
- **Multi-Client Support**: Python server handles multiple ESP8266 clients simultaneously.
- **Cloud Integration**: Data sent to ThingsBoard for dashboard visualization and analytics.
- **Configurable Thresholds**: Customize normal/abnormal temperature ranges on the server.

---

## Hardware Requirements
- 2x ESP8266 modules
- 2x DHT11 sensors
- 2x LEDs (red/yellow) + 220Ω resistors
- Breadboard and jumper wires
