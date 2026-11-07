# 🤖 Mimo – Interactive Digital Pet

**A little digital companion powered by ESP32.**

Mimo is an interactive desktop digital pet developed using the ESP32 microcontroller. It combines electronics, embedded programming, display animations, and wireless connectivity to create a companion that responds to user interactions.

## 🌟 Project Overview

Mimo is designed to express emotions, respond to touch, perform physical movements, and provide useful real-time information.

## ✨ Features

- Animated OLED eyes with multiple expressions.
- Normal, Happy, Sad, and Angry moods.
- Capacitive touch-based interaction.
- Servo-controlled head movement.
- Digital clock with automatic time synchronisation.
- Live weather updates through Wi-Fi.
- Interactive menu with multiple operating modes.

## 🔧 Hardware Components

| Component | Purpose |
|---|---|
| ESP32 DevKit V1 | Main microcontroller |
| 1.3-inch SH1106 OLED | Display and animations |
| SG90 Servo Motor | Head movement |
| TTP223 Touch Sensor | Touch interaction |

## 💻 Technologies Used

- Arduino IDE
- Embedded C++
- ESP32 Wi-Fi
- Adafruit SH110X Library
- NTP Time Synchronisation
- Open-Meteo Weather API

## ⚙️ Working Principle

The ESP32 acts as the main processing unit, receiving input from the touch sensor and controlling the OLED display and servo motor.

Based on user interactions, Mimo changes its facial expressions and performs programmed movements. Wi-Fi connectivity enables automatic time synchronisation and weather information retrieval.

## 📁 Repository Structure

```text
Mimo-Digital-Pet/
│
├── Code/
│   └── Mimo_Digital_Pet.ino
│
├── Circuit/
│   └── Mimo_Circuit_Diagram.png
│
└── README.md
```

## 🚀 Getting Started

1. Download the code from the `Code` folder.
2. Open the `.ino` file using Arduino IDE.
3. Install the required libraries.
4. Refer to the `Circuit` folder for hardware connections.
5. Configure your Wi-Fi credentials.
6. Select the correct ESP32 board and COM port.
7. Upload the code to your ESP32.

## 🔮 Future Improvements

- Additional facial expressions and animations.
- Improved interaction and movement.
- More operating modes and smart features.
- Enhanced customisation.

---

**Built with Creativity and Curiosity. ❤️**
