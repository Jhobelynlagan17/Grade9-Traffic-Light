# 🚦 Grade 9 Traffic Light Controller

## 📌 Project Overview
A simple traffic light system using Arduino Uno that cycles through Green, Yellow, and Red LEDs — with **only one LED ON at any time**.

## 🔧 Components Used
| Component | Quantity | Connection |
|-----------|----------|------------|
| Arduino Uno | 1 | — |
| Red LED | 1 | Pin 8 (with 220Ω resistor to GND) |
| Yellow LED | 1 | Pin 9 (with 220Ω resistor to GND) |
| Green LED | 1 | Pin 10 (with 220Ω resistor to GND) |
| 220Ω Resistor | 3 | For each LED |
| Breadboard & Jumper Wires | As needed | — |

## ⏱️ Traffic Light Sequence
| Signal | Duration | Action |
|--------|----------|--------|
| 🟢 Green | 5 seconds | Only Green LED ON |
| 🟡 Yellow | 2 seconds | Only Yellow LED ON |
| 🔴 Red | 5 seconds | Only Red LED ON |

> **Rule:** Only ONE LED is ever ON at the same time for safety.

## 🔗 Wokwi Simulation Link
[Click here to run the simulation][(](https://wokwi.com/projects/479182929503935489)

## 💻 Code File
- `sketch.ino` — Contains the full Arduino program using `pinMode()`, `digitalWrite()`, and `delay()`.
