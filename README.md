# 🤖 Arduino Motor Control using L298N Driver

This project demonstrates how to control two DC motors using an **L298N Motor Driver Module** with Arduino.  
The robot moves **forward continuously** using PWM speed control.

---

## 🚀 Features

- 🔄 Dual DC motor control
- ⚡ PWM speed regulation
- 🤖 Forward motion control logic
- 🔌 Easy hardware interface

---

## 🧰 Components Required

- Arduino Uno (or compatible board)
- L298N Motor Driver Module
- 2 × DC Motors
- Battery (7V–12V recommended)
- Jumper wires
- Chassis (optional)

---

## 🔌 Circuit Connections

### Motor Driver to Arduino

| L298N Pin | Arduino Pin |
|----------|------------|
| ENA      | 10         |
| IN1      | 9          |
| IN2      | 8          |
| IN3      | 7          |
| IN4      | 6          |
| ENB      | 5          |

### Power Connections

- Motor Power → External Battery (7V–12V)
- GND → Common Ground (Arduino + Driver)

---

## 🧠 Working Principle

- The L298N driver controls motor direction using **IN1–IN4 pins**
- Speed is controlled using **PWM signals on ENA and ENB**
- Both motors are driven forward by:
  - IN1 = HIGH, IN2 = LOW
  - IN3 = HIGH, IN4 = LOW

---
