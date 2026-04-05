🔹 Intro

This project demonstrates multitasking on ESP32 using FreeRTOS. It reads environmental data and updates an OLED display in real-time using queues for safe task communication.

🔹 Features
FreeRTOS-based multitasking
Inter-task communication using queues
DHT22 temperature & humidity sensing
Button press detection with debouncing
OLED display output (SSD1306)
🔹 Hardware Used
ESP32
DHT22 Sensor
SSD1306 OLED Display (I2C)
Push Button
🔹 Task Breakdown
Task	Function
Sensor Task	Reads temperature & humidity every 2 seconds
Button Task	Detects button presses with debounce
Display Task	Updates OLED with latest data
🔹 Concepts Used
FreeRTOS Tasks
Queues
Multitasking
Embedded UI handling
🔹 Output
Displays:
Temperature
Humidity
Button press count
🔹 Future Improvements
WiFi + Cloud integration
Data logging
Mobile dashboard