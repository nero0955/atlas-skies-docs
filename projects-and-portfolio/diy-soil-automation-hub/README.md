# 📁 DIY Soil Automation Hub

## Open-Source Soil Moisture Sensor Hub

**Project Classification:** Low-Power IoT / Environmental Mechatronics\
**Core Microcontroller:** Arduino Nano ESP32\
**Firmware Architecture:** Object-Oriented MicroPython\
**Fabrication:** Custom 3D-Printed Portable Enclosure

***

### 1. Project Overview

This project is a portable, modular soil moisture sensing hub designed to monitor agricultural substrates and microgreen setups in real time. Instead of relying on cheap, fragile consumer sensors that rust out over time, this hub utilizes a robust, weatherized central housing with modular probe connections.

It serves as a key case study in low-power data collection, showing how custom software logic and tailored hardware fabrication can track vital environmental variables in the field.

***

### 2. Technical Features & Integration

* **Wireless Data Pipeline:** Leveraging the ESP32’s onboard Wi-Fi/Bluetooth capabilities to transmit localized moisture percentages to a persistent data hub.
* **Modular Probe Interface:** Features a quick-swap sensor pin setup allowing individual analog or capacitive soil probes to be replaced or recalibrated on the fly without rewriting the main controller code.
* **Ruggedized Enclosure:** Designed in CAD and fabricated out of high-density filament to ensure internal electronics are completely sealed against humidity, soil dust, and water splashes during greenhouse monitoring cycles.

***

### 3. Engineering Documentation chapters

_Dive deeper into the technical execution via the sub-pages below:_

#### [📁 System Hardware & Pinouts](https://atlas-skies.gitbook.io/atlas-skies-docs/~/revisions/mLfENyZ4vkfejXHSxUl9/projects-and-portfolio/diy-soil-automation-hub/system-hardware-and-pinouts)

_Schematics tracking battery management, power regulation for the ESP32 board, and specific microcontroller pin assignments for the sensor triggers._

#### [📁 MicroPython Control Logic](https://atlas-skies.gitbook.io/atlas-skies-docs/~/revisions/YOIDxWHmfEJwWDODyFlG/projects-and-portfolio/diy-soil-automation-hub/micropython-control-logic)

_The raw, modular codebase handling power-saving deep sleep cycles, raw analog signal conversion formulas, and data packet structures._
