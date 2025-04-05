# 🔐 IoT-Based Keypad Door Lock System

## 📌 Overview
This project simulates an **IoT-enabled keypad-based smart lock system** using **Arduino Uno**, **C++**, and **Tinkercad**. It allows users to input a secure password through a 4x4 keypad and unlocks the door using a **servo motor**. For enhanced user interaction and security, it includes an **LCD Display** for real-time status updates and a **Piezo Buzzer** for audio feedback. The system also features **security lockouts** to deter unauthorized access attempts.

---
![System Circuit Diagram](assets/circuit-diagram.jpg)


## ✨ Features
- 🔢 **Password Input**: Secure 4-digit password input via a 4x4 keypad.
- 🔓 **Servo Motor Control**: Unlocks and locks the door mechanism based on authentication.
- 📺 **LCD Display (16x2)**: Shows instructions, input status, and alerts.
- 🔊 **Piezo Buzzer**: Audible feedback on successful or failed attempts.
- 🔐 **Security Lockout**: 
  - **Temporary Lockout** after a few wrong attempts.
  - **Permanent Lockout** after repeated failures (can be reset manually).
- ⬅️ **Backspace Functionality**: Correct mistakes during input.
- 🛠️ **Reset Option**: System can be reset by pressing a special key or restarting the Arduino.

---

## 🧰 Technologies Used
- **Microcontroller**: Arduino Uno
- **Programming Language**: C++
- **Simulation Platform**: Tinkercad
- **Peripherals**:
  - 4x4 Keypad
  - Servo Motor
  - 16x2 LCD Display
  - Piezo Buzzer

---

## 📦 Components Required
| Component         | Quantity |
|------------------|----------|
| Arduino Uno       | 1        |
| 4x4 Keypad        | 1        |
| Servo Motor       | 1        |
| LCD Display (16x2)| 1        |
| Piezo Buzzer      | 1        |
| Breadboard        | 1        |
| Jumper Wires      | Several  |
| Potentiometer     | 1 (for LCD contrast) |

---

## 🚀 How to Use
1. **Assemble the Circuit**  
   Connect all components as per the provided circuit diagram in the repository or Tinkercad simulation.

2. **Upload the Code**  
   Use the Arduino IDE to upload the source code from the repository to your Arduino Uno board.

3. **Power On the System**  
   After powering up, the LCD will prompt you to enter the password.

4. **Authenticate**  
   - Enter the correct password to unlock the door.  
   - Once the door is unlocked, press `#` on the keypad to re-lock it manually.  
   - Incorrect passwords trigger the buzzer and display warnings.

5. **Lockout Logic**  
   - After _3 incorrect attempts_, the system locks temporarily.
   - After _5 total incorrect attempts_, it locks permanently.

6. **Reset (Optional)**  
   Use a designated reset button or power cycle the Arduino to reset the lockout state (configurable in code).

---

## 📂 GitHub Repository
Find the full source code, schematic diagram, and simulation file here:  
🔗 [GitHub Repository](https://github.com/Thusaniv/IoTDoorlock/)

---


