# STM8-Based Classroom Clicker PCB

## Overview

Designed a compact, low-power classroom response (clicker) device PCB using an STM8 microcontroller. The system is optimized for large-scale deployments (50–1000 devices) with focus on power efficiency, reliable RF communication, and manufacturability.

---

## Key Features

* Coin cell powered design (CR2032) for long battery life
* Multi-button interface (MCQ + response inputs)
* RF communication support via external transceiver module
* Compact and lightweight PCB suitable for handheld devices
* Scalable architecture for classroom response systems

---

## Hardware Design

### Microcontroller

* STM8 series microcontroller for low-power embedded control

### Power System

* CR2032 coin cell battery operation
* Decoupling capacitors for stable voltage supply
* Optimized low-power design for extended usage

### Input System

* Multiple SMD tactile switches for user interaction
* Designed for durability and minimal tactile noise

### RF Considerations

* Dedicated antenna region with minimal copper interference
* Battery placement isolated from antenna for signal integrity
* Routing optimized to reduce EMI and improve transmission reliability

---

## PCB Design Highlights

* Single-layer optimized routing for cost-effective manufacturing
* Use of SMD components for compactness and assembly efficiency
* Proper decoupling and power distribution layout
* Clean separation of signal and RF regions
* Designed using EasyEDA

---

## Bill of Materials (BOM)

* STM8 microcontroller
* SMD resistors (0603)
* Decoupling capacitors (100nF typical)
* SMD tactile switches
* Coin cell battery holder (CR2032)
* RF transceiver module support components

(All components sourced from LCSC for manufacturability)

---

## Files Included

* Schematic design files
* PCB layout files
* Gerber files (fabrication-ready)
* 2D and 3D PCB renders

---

## Status

PCB design completed and ready for fabrication and testing.

---

## Future Improvements

* Firmware integration and testing
* RF protocol optimization for low latency
* Power consumption benchmarking
* Enclosure design for product-level finish

---

## Author

Tatipamula Baladitya
Embedded Systems Developer | IoT | Hardware Design
