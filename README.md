 ESP32 IoT Weather Monitoring System
-------------------------------------------------
## 📌 Project Overview

The **ESP32 IoT Weather Monitoring System** is a hardware simulation project that measures **temperature and humidity** using a DHT22 sensor and displays the data on an OLED display. The system is built using the ESP32 microcontroller and simulated using Wokwi.

This project demonstrates **IoT sensor integration, embedded programming, and real-time data monitoring**.

----------------------------------------------------
🧰 Components Used
-------------------------------------------------
* ESP32 Microcontroller
  
* DHT22 Temperature & Humidity Sensor
  
* SSD1306 OLED Display (I2C)
  
* Jumper Wires


## ⚙️ Features
-------------------------------------------------
* Real-time temperature monitoring
  
* Humidity measurement
  
* OLED display output
  
* Serial monitor logging
  
* Easy simulation using Wokwi


## 🔌 Circuit Connections
-------------------------------------------------
### DHT22 Sensor
-------------------------------------------------
| Sensor Pin | ESP32 Pin |
| ---------- | --------- |
| VCC        | 3.3V      |
| GND        | GND       |
| DATA       | GPIO 15   |

### OLED Display (I2C)
-------------------------------------------------
| OLED Pin | ESP32 Pin |
| -------- | --------- |
| VCC      | 3.3V      |
| GND      | GND       |
| SDA      | GPIO 21   |
| SCL      | GPIO 22   |



## 💻 How the System Works
-------------------------------------------------
1. The **DHT22 sensor** reads temperature and humidity from the environment.
   
2. The **ESP32 processes the sensor data**.
   
3. The values are printed on the **Serial Monitor**.
 
4. The readings are displayed on the **OLED display**.
   
5. The system updates the data every **2 seconds**.
    

## 🚀 Future Improvements
-------------------------------------------------
* Send data to IoT cloud platforms
  
* Build a web dashboard
  
* Mobile app monitoring
  
* Add air quality sensors
  
 ## 🧪 Simulation
-------------------------------------------------
This project was created and tested using **Wokwi Arduino Simulator**.


