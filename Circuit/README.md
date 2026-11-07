# Mimo – Hardware Circuit Configuration

This document provides the hardware connection details and pin configuration for **Mimo – Interactive Digital Pet**, developed using the ESP32 DevKit V1.

## Hardware Overview

Mimo consists of the following hardware components:

- ESP32 DevKit V1 – Main controller
- 1.3-inch OLED Display (SH1106) – Displays animated eyes and information
- TTP223 Touch Sensor – Detects user touch interactions
- SG90 Servo Motor – Controls head movement

## Component Connections

## 1. ESP32 DevKit V1

| Pin | Connection |
|---|---|
| GPIO 21 | OLED SDA |
| GPIO 22 | OLED SCL |
| GPIO 4 | TTP223 OUT |
| GPIO 18 | SG90 Signal |

## 2. OLED Display (1.3-inch SH1106)

| Pin | Connection |
|---|---|
| SDA | ESP32 GPIO 21 |
| SCL | ESP32 GPIO 22 |
| VCC | ESP32 3.3V |
| GND | ESP32 GND |

## 3. TTP223 Touch Sensor

| Pin | Connection |
|---|---|
| OUT | ESP32 GPIO 4 |
| VCC | ESP32 3.3V |
| GND | ESP32 GND |

## 4. SG90 Servo Motor

| Pin / Wire | Connection |
|---|---|
| Signal (Orange) | ESP32 GPIO 18 |
| VCC (Red) | External 5V |
| GND (Brown) | Common GND |

## Power Supply Configuration

- ESP32 is powered through USB.
- OLED display and TTP223 sensor receive 3.3V from the ESP32.
- SG90 servo motor uses a separate regulated 5V supply.
- The external servo supply and ESP32 must share a common ground.

## Communication Interfaces

| Component | Interface |
|---|---|
| OLED Display | I²C |
| TTP223 Touch Sensor | Digital Input |
| SG90 Servo Motor | PWM Control |

## Important Notes

- Check all connections before powering the circuit.
- Ensure the servo receives a suitable external power supply.
- Maintain a common ground between the ESP32 and servo power supply.
- Avoid short circuits and incorrect polarity.
