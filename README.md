# TinyBasic Plus on Arduino Nano

*A Minimal BASIC Computer Using Arduino, VGA, and PS/2 Keyboard*

---

## 📌 Project Overview

This project implements a **basic computer system** using **TinyBasic Plus (TBXL)** running on **Arduino Nano** hardware.
It combines **retro computing concepts** with modern microcontrollers to create a simple, educational, and interactive programmable system.

The system uses:

* **Two Arduino Nano boards**

  * **Master**: VGA video output
  * **Slave**: PS/2 keyboard input
* **TinyBasic Plus interpreter**
* **Serial communication** between Master and Slave

This project is designed for **learning purposes**, especially for students interested in:

* Embedded systems
* Retro computing
* Programming language interpreters
* Low-level hardware–software integration

---

## 🧠 Project Features

* Tiny BASIC interpreter running on Arduino
* VGA text output
* PS/2 keyboard input
* Master–Slave Arduino architecture
* EEPROM program storage
* BASIC commands for:

  * Math
  * Control flow
  * Digital & Analog I/O
  * Delay and sound
* Educational and expandable design

---

## 🧩 Hardware Architecture

### 1. Master Arduino Nano

* Generates **VGA signals**
* Displays BASIC program output
* Communicates with Slave via **Serial RX**

### 2. Slave Arduino Nano

* Handles **PS/2 keyboard input**
* Sends key data to Master via **Serial TX**
* Supplies **5V & GND** to Master

---

## 🛠 Components Used

* Arduino Nano × 2
* VGA (DB-15) Connector
* PS/2 (Mini-DIN-6) Connector
* Header Pins (Male & Female)
* Resistors (68Ω, 470Ω, 1kΩ)
* LEDs (Red & Green)
* Push Buttons
* Double-Sided PCB
* PS/2 Keyboard

---

## 🖥 Software Details

* **Language:** C / Embedded C
* **Platform:** Arduino IDE
* **Interpreter:** TinyBasic Plus (TBXL)
* **Communication:** UART Serial

---

## 📜 Supported BASIC Commands (Summary)

* **System:** `RUN`, `NEW`, `MEM`, `END`, `BYE`
* **Control:** `IF`, `FOR`, `NEXT`, `GOTO`, `GOSUB`, `RETURN`
* **Math:** `+ - * /`, `ABS()`, `RND()`
* **I/O:** `PRINT`, `INPUT`
* **Pin Control:** `DWRITE`, `AWRITE`, `DREAD`, `AREAD`
* **EEPROM:** `ESAVE`, `ELOAD`, `EFORMAT`, `ELIST`
* **Sound:** `TONE`, `NOTONE`

---

## 🧪 Example Program

```basic
10 PRINT "Hello, World"
20 GOTO 10
RUN
```

---

## 🏛️ Credits & Acknowledgements

*(Important – Please Read)*

This project builds upon decades of work by pioneers in computer science and open-source contributors.

### 🔹 Original BASIC Language

* **John G. Kemeny**
* **Thomas E. Kurtz**

  * Creators of the original **BASIC language** at Dartmouth College (1964)

### 🔹 Tiny BASIC

* **Dr. Li-Chen Wang**

  * Creator of **Tiny BASIC** (1975)
  * Published in *Dr. Dobb’s Journal*
  * Designed for early microcomputers like Intel 8080

### 🔹 TinyBasic Plus (TBXL)

* Developed by **open-source contributors**
* Extended Tiny BASIC with:

  * Better error handling
  * EEPROM support
  * File I/O
  * Arduino compatibility
* Written in **C** for embedded platforms

### 🔹 Arduino Platform

* **Arduino Open-Source Community**
* **Arduino.cc**
* AVR & ATmega328P contributors

### 🔹 Project Implementation

* **Mitesh S. Gorad**

  * S.Y. B.Sc (Computer Science)
  * Department of Electronics
  * Prof. Ramkrishna More Arts, Commerce & Science College, Pune
  * Academic Year: 2023–2024

This project is strictly for **educational and non-commercial use**.

---

## 🔮 Future Enhancements

* SD card support
* External RAM
* GUI shell
* Sound chip integration
* Single-board version
* Bootloader-based startup

---

## 📄 License

This project follows the **original licenses of Tiny BASIC and TinyBasic Plus**, and is shared for **educational purposes only**.
Please credit the original authors when reusing or modifying this work.

---

## 🙏 Final Note

This project demonstrates how **simple hardware + classic software concepts** can still teach powerful lessons in computing.

> *“Old ideas never die — they just reboot.”*

---
