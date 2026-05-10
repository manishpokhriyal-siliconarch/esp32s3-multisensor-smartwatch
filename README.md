# esp32s3-multisensor-smartwatch
# Compact ESP32-S3 Smartwatch PCB with Multi-Sensor Integration

A compact two-layer smartwatch PCB designed using KiCad for wearable embedded applications based on the ESP32-S3 wireless microcontroller.

---

## Project Overview

This project presents the design and implementation of a compact smartwatch printed circuit board integrating sensing, communication, display interfacing, and power-management subsystems within a wearable form factor.

The smartwatch platform integrates:

* ESP32-S3 wireless MCU
* MAX30102 PPG heart-rate sensor
* BNO086 9-axis IMU
* MMICT5848 MEMS microphone
* 1.83-inch IPS capacitive touch display
* USB Type-C charging and programming
* Li-ion battery management subsystem
* Multi-voltage power architecture

The PCB was designed using KiCad 9.0.7 with emphasis on compact routing, subsystem integration, manufacturability, and wearable mechanical compatibility.

---

# Features

* ESP32-S3-WROOM-1-N8R8 MCU
* Wi-Fi and Bluetooth connectivity
* Heart-rate sensing using MAX30102
* Motion sensing using BNO086 IMU
* Digital audio acquisition using MEMS microphone
* SPI display interfacing
* I2C touch controller interfacing
* USB Type-C firmware flashing and charging
* TPS63001 buck-boost power regulation
* LD56020 1.8V low-noise LDO regulation
* Compact 35 mm × 42 mm smartwatch PCB
* Two-layer PCB architecture

---

# Hardware Architecture

## Processing Subsystem

* ESP32-S3-WROOM-1-N8R8
* Dual-core Xtensa LX7 processor
* Native USB support
* Integrated Wi-Fi and BLE

## Sensors

* MAX30102 PPG sensor
* BNO086 9-axis IMU
* MMICT5848 digital MEMS microphone

## Display

* 1.83-inch IPS touch LCD
* 240 × 284 resolution
* ST7789P display driver
* CST816D capacitive touch controller

## Power System

* USB Type-C input
* MCP73831 Li-ion charging IC
* TPS63001 buck-boost converter
* LD56020 1.8V LDO regulator

---

# PCB Design

* Compact two-layer PCB implementation
* Dedicated antenna keep-out region
* Rear-side PPG placement for skin alignment
* Display-aligned PCB geometry
* Strap mounting slots for smartwatch assembly
* Test pads for debugging and validation

Standard 0402 passive components were utilized for compact PCB integration, while 0603 LEDs improved visual indication and assembly reliability.

---

# Communication Interfaces

* I2C
* SPI
* I2S
* USB
* Wi-Fi
* Bluetooth Low Energy (BLE)

---

# Design Verification

* ERC verified
* DRC verified
* Manufacturability verified
* Compact routing optimization completed
* Stable 3.3V and 1.8V power rails achieved

---

# PCB Images

## Front Side PCB

(Add image here)

## Rear Side PCB

(Add image here)

## PCB Routing

(Add image here)

## 3D PCB View

(Add image here)

---

# Tools Used

* KiCad 9.0.7
* ESP32-S3 Platform
* Embedded Hardware Design

---

# Future Improvements

* Firmware optimization
* BLE-only low-power mode
* Battery-life optimization
* Smartwatch enclosure development
* Additional wearable sensing features

---

# Repository Structure

```text
Hardware/
├── Schematic/
├── PCB/
├── Gerbers/
├── 3D/

Docs/
├── Report.pdf

Images/

README.md
```

---

# Author

Manish Pokhriyal
M.Tech ECE (VLSI)
IIIT Bangalore

GitHub:
https://github.com/manishpokhriyal-siliconarch

---

# Project Report

Add your IEEE report PDF inside:

```text
Docs/Report.pdf
```
