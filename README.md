# 🧪 Laboratory Practices - Practice 2 - Redes de sensores electrónicos

This repository contains the second laboratory practice for the **Redes de sensores electrónicos** course. Each section is organized in its own folder and includes the necessary files along with a brief description.
In this practice, we will explore the usage of Machine Learning on embedded electronics, particularly on the Arduino Nano 33 sense BLE. In this case, we will be using  **Edge Impulse** as the way of deploying our Machine Learning proyects.

## 📖 Section Overview

### 📁 Section 1 - 01_capture-info-from-sensors-arduino-nano-33-ble-sense
📌 Scripts used to flash on our Arduino Nano BLE 33 and obtain info from sensors in order to get processed on Edge Impluse platform.  As indicated by Edge Impulse, Arduino CLI & Edge Impulse CLI.
📄 Main files:  
- `flash_windows.bat`: In order to flash on Arduino, program for Windows OS.
- `flash_linux.sh`: Same for Linux.
- `flash_mac.command`: Same for MacOS.


### 📁 Section 2 - nano_ble33_sense_microphone_continuous
📌 Implementation of Model and working script to check if name is recognized
📄 Main files:  
- `nano_ble33_sense_microphone_continuous.ino`: main code used in order to see if the Arduino recognizes the name, by blinking an LED on the board. Tested and working with "Dani" as an input parameter on the mic.

### 📁 Section 3 - lib
📌 Includes ZIP file with installable library that gets used in order to recognize 'Dani' as the name evaluate correctly. Downloaded from Edge Impulse, after training model.