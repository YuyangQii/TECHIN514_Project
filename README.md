# TECHIN514_Project
SpeakEase: Presentation Assistant
Introduction
SpeakEase is a discreet wearable device designed to enhance public speaking skills by providing real-time audio feedback. This system connects a wearable device with a desktop display unit via wireless technology, offering intuitive guidance for speakers.

Wearable Device
Sensors
Digital Microphone: MP34DT01-M
Vibration Motor: C0834B002F
OLED Display: SSD1306
Functionality
The wearable device performs the following functions:

Captures the speaker's voice in real-time.
Processes data with ESP32.
Transmits data to the display device.
Vibrates gently for adjustments when speech pace or volume deviates.
Alerts with vibration when time is running low.
Display Device
Components
RGB LED Light: WS2812B 5050
Standard LED
Stepper Motor: 28BYJ-48 5V with ULN2003 Driver
Rotary Encoder: EC11
Tactile Switch
Features
The display device offers the following features:

The stepper motor drives a gauge needle to display speech pace.
An RGB LED ring changes color and brightness based on speech pace for visual feedback.
The rotary encoder sets speech duration, and an adjacent LED alerts on time changes.
Device Communication
Method
ESP32 modules handle Bluetooth/Wi-Fi communication, ensuring synchronization between both devices.
