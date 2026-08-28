
---

# 📁 Task 3 — `README.md`

Your Task 3 video shows an **Arduino Uno + PIR motion sensor + buzzer + LED** prototype. The code uses **digital pin 2 for the PIR sensor, pin 8 for the buzzer, and pin 13 for the indicator LED**.

```markdown
# IoT Prototype with Arduino

## CodeAlpha IoT Internship – Task 3

### 📌 Project Overview

This project demonstrates a simple **IoT-based motion detection and alarm system** using an Arduino Uno.

A **PIR (Passive Infrared) sensor** is used to detect motion. When motion is detected, the Arduino activates a buzzer and LED as an alarm indication.

The prototype is developed and simulated using **Tinkercad Circuits**.

### 🎯 Objective

The main objectives of this task are:

- Interface a PIR sensor with Arduino Uno.
- Detect motion using a PIR sensor.
- Control an LED based on sensor input.
- Activate a buzzer when motion is detected.
- Understand basic IoT prototype development.

### 🛠️ Components Used

- Arduino Uno R3
- PIR Motion Sensor
- Buzzer
- LED
- Connecting Wires
- Tinkercad Circuits

### 🔌 Pin Configuration

| Component | Arduino Pin |
|-----------|-------------|
| PIR Sensor | Digital Pin 2 |
| Buzzer | Digital Pin 8 |
| LED | Digital Pin 13 |

### ⚙️ Working Principle

The PIR sensor continuously monitors for motion.

When motion is detected:

```text
PIR Sensor
     ↓
Arduino Uno
     ↓
Motion Detected
     ↓
 ┌───────────┐
 ↓           ↓
Buzzer      LED
 ON          ON
