# FlappyBirdGame 
A simple Flappy Bird game implemented on an ESP32 microcontroller with an OLED display and a push-button for controls.
This project uses an ESP32, an SSD1306 OLED display, and a push button to recreate the classic Flappy Bird game. The bird moves through obstacles, and you control it by pressing the button to "flap" and keep it in the air.

# Hardware Requirements
1. ESP32 (DevKit V1 or similar)
2. 0.96-inch OLED Display (SSD1306, I2C)
3. Push Button 
4. Buzzer (Optional for sound effects)
5. Breadboard & Jumper Wires
   
# Troubleshooting
🛑 Common Issues & Fixes
## OLED screen stays blank?
1. Check wiring (SDA, SCL connections).
2. Try changing the I2C address (default: 0x3C).
## Compilation Errors?
1. Ensure all required libraries are installed.
2. Make sure .h files are in the same directory.
## ESP32 not detected?
1. Try a different USB cable/port.
2. Check if the correct COM Port is selected.

# Software Requirements
1. Arduino IDE
2. ESP32 Board Package
3. (Add this URL in Board Manager:)
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

# Libraries to Install:
1. Adafruit GFX Library
2. Adafruit SSD1306
3. ESP8266 and ESP32 OLED Driver for SSD1306
