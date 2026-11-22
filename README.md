# Hi, I'm Kanav 👋

**Final-year Computer Engineering student at Dalhousie University** (graduating April 2027) · Halifax, NS 🇨🇦

I build embedded systems end to end: schematics and PCB layout in KiCAD, C/C++ firmware, and real-time control on TI, STM32, ESP32 and AVR microcontrollers. Most recently I was an **Electrical Engineering co-op on the Naval Engineering team at Leonardo DRS**, where I worked on power conversion firmware for TI microcontrollers in Code Composer Studio, PI control-loop tuning, PSIM simulation and CAN bus communication for high-reliability UPS systems.

- 🔭 **Currently building:** an off-grid, chemical-free **Varroa mite excluder** for beehives (my senior capstone), plus a **FreeRTOS teleoperated marine cargo crane**
- 🌱 **Learning:** real-time scheduling, power electronics, embedded Linux
- 💬 **Ask me about:** firmware, FreeRTOS, PCB design, control loops
- 🤝 **Open to:** new-grad embedded / firmware / hardware roles starting 2027

---

## 🛠️ Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-555555?style=flat)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**Microcontrollers & RTOS**

![Texas Instruments](https://img.shields.io/badge/TI_MCUs-CC0000?style=flat&logo=texasinstruments&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Atmel_/_Arduino-00878F?style=flat&logo=arduino&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-5BA300?style=flat)
![Embedded Linux](https://img.shields.io/badge/Embedded_Linux-FCC624?style=flat&logo=linux&logoColor=black)

**IDEs & Dev Tools**

![Code Composer Studio](https://img.shields.io/badge/Code_Composer_Studio-CC0000?style=flat&logo=texasinstruments&logoColor=white)
![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)

**Hardware Design & CAD**

![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat&logo=kicad&logoColor=white)
![SolidWorks](https://img.shields.io/badge/SolidWorks-D22630?style=flat)
![AutoCAD](https://img.shields.io/badge/AutoCAD-E51050?style=flat&logo=autodesk&logoColor=white)
![3D Printing](https://img.shields.io/badge/3D_Printing-555555?style=flat)

**Simulation & Data**

![PSIM](https://img.shields.io/badge/PSIM-444444?style=flat)
![MATLAB/Simulink](https://img.shields.io/badge/MATLAB_/_Simulink-0076A8?style=flat)
![ModelSim](https://img.shields.io/badge/ModelSim-0071C5?style=flat)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat&logo=ros&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)

**Protocols & Interfaces:** UART · I2C · CAN · PWM / H-bridge · ADC/DAC · ESP-NOW · Wi-Fi

**Control & Power:** PI/PID loop tuning · feedback control · single-phase power systems · UPS power electronics · power regulation

**Lab & Test:** oscilloscopes · logic analyzers · multimeters · fault finding · soldering & assembly · unit testing & validation

---

## 🚀 Featured Projects

| Project | What it is | Stack |
|---|---|---|
| 🐝 **Varroa Mite Excluder** *(capstone, in progress)* | Solar-powered device for beehive entrances. A camera spots bees carrying Varroa mites and a servo trap door diverts them, with no chemicals. Includes a local Wi-Fi dashboard showing bee counts, infections and battery status. | ESP32-S3, C++, computer vision, solar/battery power design |
| 🏗️ **Wireless Marine Cargo Crane** *(in progress)* | Scaled teleoperated crane with hard real-time safety interlocks driven by limit-switch ISRs, an ESP-NOW handheld remote with a connection watchdog, and a custom 2-layer controller PCB. | FreeRTOS, dual-core ESP32, KiCAD |
| 🎮 **ESP32 Bluetooth Mouse + Gamepad** *(side project)* | Wireless controller that pairs over BLE as a standard HID device, with no drivers needed. Hold a button to switch between mouse and gamepad mode. It calibrates the joystick at boot and applies a deadzone, debounces buttons without blocking, and reconnects automatically. | ESP32, C++, BLE HID, PlatformIO |
| 🖥️ **XM23 CPU Emulator** | Emulator for a 16-bit RISC-style CPU, written from scratch in about 4,800 lines of C. It runs the full instruction set, including conditional execution, along with memory-mapped timer, keyboard and screen devices, priority interrupts with nesting and tail-chaining, and fault handling. It includes a configurable cache simulator (direct-mapped or LRU associative, write-through or write-back) and an interactive debugger with breakpoints. | C |
| 🤖 **Robo Heist Challenge** | Autonomous robot that navigates a secured arena, defeats simulated RFID and laser-tripwire security, and retrieves targets. | C++, Arduino, ultrasonic sensors, encoders |
| 🌊 **Underwater Coral Monitoring Station** | Waterproof sensor station (temperature, pH, turbidity) with custom PCBs and wireless data logging. | KiCAD, MCU firmware, 3D printing |
| 📈 **[EKG Earth-Resistance Prediction](https://github.com/KanavTyagi/resistance-temperature-prediction)** | ML model (Random Forest and clustering, 15k+ data points, 85% accuracy) predicting protective-earth resistance of medical devices to IEC 60601. Built at CSIR NPL. | Python, scikit-learn, Seaborn |
| 🌙 **Lunar Ice Cave Explorer** | Two-part team project. A terminal map builder draws multi-layer cave maps and saves them to a binary record file, with each layer's cells linked inside the file and deleted cells reused. An autonomous rover then loads a map and searches it for ice using recursive backtracking, while managing battery, radiation, a gap-crossing bridge and a spare battery. | C, VT100 terminal graphics |

---

## 💼 Experience

- **Leonardo DRS**: Electrical Engineering Co-op, Naval Engineering: power conversion firmware on TI MCUs (Code Composer Studio), PI tuning, CAN *(Jan–Sep 2026)*
- **CSIR National Physical Laboratory, India**: Lab Intern, medical device safety testing *(Summer 2024)*
- **Dalhousie University**: TA and Marker, Engineering Technical Communication *(2023–2026)*
- **Tetra Society, Dal Chapter**: Technical Lead, assistive devices for people with disabilities *(2024–2025)*

---

## 📫 Get in Touch

[![Email](https://img.shields.io/badge/Email-Kanav.tyagi%40dal.ca-D14836?style=flat&logo=gmail&logoColor=white)](mailto:Kanav.tyagi@dal.ca)
<!-- Add your LinkedIn: replace YOUR-HANDLE below and uncomment
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-HANDLE)
-->
