# ESP32 Soil Moisture Monitoring and Pump Control

This project involves monitoring soil moisture levels using an ESP32 microcontroller and controlling a pump based on the moisture readings. It also provides temperature and humidity monitoring using a DHT11 sensor. The system is integrated with the Blynk platform for remote monitoring and control.

## Components Required

- ESP32 Development Board
- Soil Moisture Sensor
- DHT11 Temperature and Humidity Sensor
- Water Pump
- Jumper Wires

## Setup Instructions

1. **Hardware Setup**:
   - Connect the soil moisture sensor to the analog pin of the ESP32 (e.g., pin 34).
   - Connect the DHT11 sensor to the specified pin of the ESP32 (e.g., pin 4).
   - Connect the water pump to a digital pin of the ESP32 (e.g., pin 2).

2. **Software Setup**:
   - Install the Arduino IDE on your computer.
   - Install the necessary libraries:
     - BlynkSimpleEsp32
     - DHT sensor library
   - Open the Arduino IDE and create a new sketch.
   - Copy the provided code into the sketch.
   - Replace `"YourAuthToken"`, `"YourWiFiSSID"`, and `"YourWiFiPassword"` with your actual Blynk authentication token and Wi-Fi credentials.

3. **Blynk App Setup**:
   - Download the Blynk app from the App Store or Google Play Store.
   - Create a new project and select ESP32 as the device.
   - Add three value display widgets to monitor temperature, humidity, and soil moisture.
   - Add a notification widget to receive pump status notifications.
   - Customize the widgets as needed and obtain the authentication token.

4. **Upload Code**:
   - Connect the ESP32 board to your computer via USB.
   - Select the appropriate board and port from the Arduino IDE.
   - Click on the upload button to upload the code to the ESP32 board.

5. **Monitor and Control**:
   - Open the serial monitor to view debug messages.
   - Open the Blynk app and monitor temperature, humidity, and soil moisture readings.
   - Control the water pump manually through the app or let the system automatically control it based on soil moisture levels.

## Troubleshooting

- If you encounter any issues during setup, double-check the connections and ensure that the libraries are correctly installed.
- Make sure the Blynk app is configured with the correct authentication token and widgets.
- Verify that the sensors are functioning correctly and providing accurate readings.


