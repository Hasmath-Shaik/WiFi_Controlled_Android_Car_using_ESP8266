# WiFi_Controlled_Android_Car_using_ESP8266
# Performance Improved Android Controlled Car using ESP8266

This project is a Wi-Fi controlled car that can be operated using an Android smartphone via a local Wi-Fi network.

## Technologies Used
- Arduino IDE
- ESP8266 Wi-Fi Module
- L298N Motor Driver
- Android Mobile Application (custom or generic TCP client)

## Features
- Real-time car control over Wi-Fi
- Commands: Forward, Backward, Left, Right, Stop
- Improved connection stability and control response
- Modular functions for easy expansion

## How to Run
1. Connect the motors to L298N Motor Driver and ESP8266 as per the circuit diagram.
2. Upload the code to ESP8266 using Arduino IDE.
3. Connect your phone to the same Wi-Fi network.
4. Use an Android TCP client app to send commands:
   - F: Forward
   - B: Backward
   - L: Left
   - R: Right
   - S: Stop

## Future Extensions
- Add speed control via PWM
- Add obstacle detection using ultrasonic sensors
- Integrate with Blynk or IoT platforms

## Wi-Fi Credentials and Notes
For security, Wi-Fi SSID and password are not included. Please add your own when testing.
