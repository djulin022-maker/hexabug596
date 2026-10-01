# hexabug596
# HexaBug - 6-Legged Autonomous Robot

A 3D-printed 6-legged walking robot (hexapod) powered by a **Raspberry Pi Pico 2 W** and controlled via Inverse Kinematics (IK) and Wi-Fi interface. Built as part of Hack Club's Half-Life program.

---

## 📌 Project Overview

- **Microcontroller:** Raspberry Pi Pico 2 W
- **Servo Driver:** PCA9685 16-Channel 12-bit PWM Controller (I2C)
- **Actuators:** 18× SG90 Micro Servos (3 Degrees of Freedom per leg)
- **Power System:** 7.4V 2S LiPo Battery with 5V 5A Buck Converter
- **Chassis Design:** Custom 3D-printed body (PLA) with low center of gravity

---

## 🛠 Features & Goals

- **3-DOF Leg Geometry:** Enables multi-directional tripods and wave gaits.
- **Inverse Kinematics:** Onboard coordinate conversion for fluid body movement and pitch/roll stabilization.
- **Wireless Control:** Web GUI hosted directly on the Pico 2 W via MicroPython / C++.

---

## 📂 Project Logs & Syncing

This repository automatically syncs with Hack Club:![Uploading IMG_20261001_172222.jpg…]()

- `JOURNAL.md` - Engineering log and weekly session updates
- `BOM.md` - Full itemized hardware Bill of Materials
