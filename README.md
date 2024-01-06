# Farm-Automation-Monitoring-System


This project showcases how to create an IoT sensor monitoring and control system using the ESP32 microcontroller. The system keeps track of temperature, humidity, gas levels, and water levels, enabling real-time data visualization through the Blynk mobile app. It also allows for remote control of a fan and a water pump based on sensor readings.

## Features

- Real-time temperature and humidity monitoring using a DHT11 sensor.
- Gas level monitoring through an analog gas sensor.
- Water level measurement using an ultrasonic sensor.
- Remote control of a fan and a water pump.
- Data visualization on a 16x2 I2C LCD display and via the Blynk mobile app.

## Hardware Requirements

- ESP32 development board.
- DHT11 temperature and humidity sensor.
- MQ-series gas sensor.
- Ultrasonic sensor (HC-SR04) for water level measurement.
- 16x2 I2C LCD display.
- Relay modules for fan and water pump control.

## Software Requirements

- Arduino IDE.
- Blynk IoT platform for real-time data visualization and remote control.

## Getting Started

1. Clone this repository to your local machine:
2. git clone https://github.com/yourusername/Farm-Automation-Monitoring-System.git

2. Install the necessary libraries using the Arduino IDE or PlatformIO.

3. Open the Arduino IDE and load the `iot_sensor_monitoring.ino` sketch.

4. Update the `BLYNK_AUTH_TOKEN` with your Blynk authentication token and configure your Wi-Fi credentials in the sketch.

5. Upload the sketch to your ESP32 board.

6. Open the Blynk mobile app, create a new project, and scan the provided QR code in the app to connect your device.

7. You can now monitor sensor data and control the fan and water pump remotely using the Blynk app.

## Usage

- The LCD display will show the current temperature, humidity, and gas levels.
- The Blynk app offers real-time graphs and control widgets for the fan and water pump.
- Adjust the threshold values in the sketch to customize fan and pump control based on sensor readings.


