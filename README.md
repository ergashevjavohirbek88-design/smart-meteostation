# 🌡️ Smart Meteostation

Arduino weather station simulation built with Wokwi.

## Description
Smart weather station using Arduino Uno. Reads temperature and humidity
from DHT22 sensor and displays data on LCD 16x2 screen.
Three LEDs show the temperature status.

## Components
- Arduino Uno
- DHT22 Temperature & Humidity Sensor
- LCD 16x2 (I2C)
- Blue LED — cold (< 20°C)
- Yellow LED — normal (20–28°C)
- Red LED — hot (> 28°C)
- 3x Resistors 220Ω

## How it works
| Temperature | LED | Status |
|-------------|-----|--------|
| < 20°C | 🔵 Blue | COLD |
| 20–28°C | 🟡 Yellow | NORMAL |
| > 28°C | 🔴 Red | HOT |

## Simulation
[▶️ Run on Wokwi](СЮДА_ВСТАВЬ_ССЫЛКУ_WOKWI)

## Author
Javokhir Ergashev 4250
