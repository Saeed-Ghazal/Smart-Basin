# Smart Basin

An innovative Smart Basin designed for the **IEEE Pitchinno 2025** competition. The project integrates IoT and AI to monitor and optimize environmental conditions automatically, reducing water consumption and improving productivity.

---

## Smart Basin Images


  <img src="https://github.com/Saeed-Ghazal/Smart-Basin/blob/main/Image%202025-11-22%20at%2016.24.33_682d78d1.jpg?raw=true" alt="Smart Basin 1" style="width: 500px; height: auto;" />
  <img src="https://github.com/Saeed-Ghazal/Smart-Basin/blob/main/Image%202025-11-22%20at%2016.24.33_c474761a.jpg?raw=true" alt="Smart Basin 2" style="width: 500px; height: auto;" />
  <div style="text-align: center;">
    <img src="https://github.com/Saeed-Ghazal/Smart-Basin/blob/main/Screenshot%202025-11-22%20161850.png?raw=true" alt="Smart Basin App" style="width: 500px; height: auto;" />
    <p><em>Mobile App Interface for controlling the Smart Basin</em></p>


---

## Features

- Remote control via a mobile application.
- Monitors water level, temperature, humidity, and sunlight.
- Controls RGB lighting with color picker and preset moods.
- Automated water pump management based on sensor readings.

---

## Components

| Component | Function |
|-----------|----------|
| ESP32 Microcontroller | Main processor, controls sensors and actuators, provides Wi-Fi connectivity for the app. |
| Power Distribution Board | Organizes and distributes power to all components. |
| DHT11/DHT22 Sensor | Measures temperature and humidity of the environment. |
| Soil Moisture Sensor | Detects soil moisture to manage watering automatically. |
| Water Level Sensor | Measures water level in the basin to prevent dry operation. |
| LDR / Photo Diode | Measures sunlight intensity. |
| RGB LED Strip (WS2812B) | Provides customizable lighting controlled via the app. |
| Mini Water Pump | Supplies water to the basin based on sensor readings. |
| Relay Module (1-Channel) | Acts as a switch to safely control the water pump. |
| Power Adapter / Battery | Provides main power to the system. |
| Voltage Regulator (LM2596) | Converts main voltage to 5V to safely power ESP32 and sensors. |

---

## How It Works

1. Sensors collect real-time environmental data (temperature, humidity, soil moisture, sunlight, water level).
2. ESP32 processes data and controls actuators:
   - Turns water pump ON/OFF based on soil moisture or water level.
   - Adjusts RGB lighting according to selected color or mood.
3. Mobile app allows manual control and monitoring, with real-time display of all parameters.
