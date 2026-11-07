# 🤖 Mimo – Interactive Digital Pet

Mimo is an interactive desktop digital pet developed using the ESP32 DevKit V1. It combines embedded systems, electronics, programming, and wireless connectivity to create a companion that responds to user interactions.

Mimo brings personality to a physical device through animated facial expressions, touch gestures, servo-controlled movement, and real-time information.

---

## 🌟 Project Overview

The main objective of Mimo is to develop a compact and interactive digital companion that combines hardware functionality with expressive behaviour.

Using an OLED display, Mimo presents different facial expressions and responds to touch inputs. Its servo motor enables physical head movement, while Wi-Fi connectivity provides access to clock synchronisation and weather information.

## ✨ Features

- **Animated Eyes:** Custom-designed OLED eye animations.
- **Multiple Expressions:** Normal, Happy, Sad, and Angry moods.
- **Touch Interaction:** Capacitive touch sensing with multiple gestures.
- **Automatic Mood Changes:** Expression changes based on user interaction and inactivity.
- **Servo Movement:** Physical head movement using an SG90 servo motor.
- **Digital Clock:** Automatic time synchronisation using NTP.
- **Live Weather:** Temperature and humidity information through Open-Meteo.
- **Interactive Menu:** Dedicated Normal, Clock, and Weather modes.

## 🔧 Hardware Components

| S.No. | Component | Specification |
|:---:|---|---|
| 1 | Microcontroller | ESP32 DevKit V1 |
| 2 | OLED Display | 1.3-inch SH1106, 128 × 64 |
| 3 | Touch Sensor | TTP223 Capacitive Touch Sensor |
| 4 | Servo Motor | SG90 Micro Servo |

## 💻 Software & Technologies

| Technology | Application |
|---|---|
| Arduino IDE | Firmware development |
| Embedded C++ | Programming |
| ESP32 Wi-Fi | Wireless connectivity |
| Adafruit SH110X | OLED display control |
| NTP | Time synchronisation |
| Open-Meteo API | Weather information |

## ⚙️ Working Principle

Mimo uses the ESP32 as its central processing unit.

1. **Input:** The TTP223 sensor detects user touch gestures.
2. **Processing:** The ESP32 processes the input and determines the appropriate response.
3. **Display:** The OLED displays the corresponding facial expressions and information.
4. **Movement:** The SG90 servo performs programmed head movements.
5. **Connectivity:** Wi-Fi enables time synchronisation and weather data retrieval.

## 📁 Repository Structure

```text
Mimo-Digital-Pet/
│
├── Code/
│   └── Mimo_Digital_Pet.ino
│
├── Circuit/
│   └── README.md
│
└── README.md
```

## 🔌 Circuit Configuration

The hardware uses the following ESP32 pin assignments:

| Component | Pin | ESP32 GPIO |
|---|---|---|
| OLED Display | SDA | GPIO 21 |
| OLED Display | SCL | GPIO 22 |
| TTP223 Touch Sensor | OUT | GPIO 4 |
| SG90 Servo Motor | Signal | GPIO 18 |

For detailed hardware connections and power configuration, refer to the [Circuit folder](Circuit/README.md).

## 🚀 Getting Started

1. Clone or download this repository.
2. Open the `Code` folder.
3. Download and open the Arduino firmware.
4. Install the required Arduino libraries.
5. Configure your Wi-Fi credentials.
6. Connect the hardware according to the circuit configuration.
7. Select the ESP32 board and correct COM port.
8. Upload the firmware and power on Mimo.

---

**Built with Creativity and Curiosity. ❤️**
