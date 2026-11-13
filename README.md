<h1 align="center">Hi, I'm Mohan Sai 👋</h1>

<p align="center">
  <b>Embedded Systems · RTOS · IoT · VLSI / ASIC Physical Design</b><br>
  I take ideas from the transistor to the cloud: register-level firmware, real-time scheduling, connected devices and RISC-V silicon.<br>
  Everything I ship comes with tests, CI and documentation.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohan-sai-potnuru-0b274a299"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Kaumodaki_NexusGrid-Embedded_&_IoT-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" alt="Kaumodaki NexusGrid">
  <img src="https://img.shields.io/badge/IETE_Student_Forum-Chairperson-8A2BE2?style=for-the-badge" alt="IETE Student Forum Chairperson">
  <img src="https://img.shields.io/badge/Visakhapatnam-India-FF6F00?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location">
</p>

---

### 🧑‍💻 About me

- 🔌 **Embedded Systems & IoT Engineer** at **Kaumodaki NexusGrid**: ESP32 / ESP32-CAM devices, sensor networks, gas and air-quality analog front-ends (KiCad), 4G LTE + GPS trackers, BLE load cells and health-monitoring hardware
- 🎓 B.Tech ECE at Dr. Lankapalli Bullayya College of Engineering (2027), after a Diploma in ECE (82%) and a **6-month industrial training at CEMS** with 50+ embedded and IoT prototypes
- 🧠 I like owning the whole stack: **datasheet → registers → drivers → RTOS tasks → protocols → dashboard → silicon**
- 🧪 Engineering bar: deterministic timing, tested pure logic, sanitizer-clean C, reproducible builds and signoff-clean layouts
- 🎯 Open to **embedded firmware, RTOS, IoT and VLSI / physical-design** roles

---

### 🧭 Engineering depth across ECE

| Domain | What I actually do | Proof |
|---|---|---|
| **Bare-metal firmware** | Cortex-M4 register-level drivers, timer input capture for µs edge timing, ISR→main deferred work, CRC-protected wear-levelled flash config | [IRSense](https://github.com/MohansaiPotnuru/IRSense-NUCLEO-F401RE) |
| **RTOS & real-time** | Preemptive priority scheduling, task/ISR split, queues, semaphores, mutexes and priority inversion, timers, stack and timing budgets (2-month RTOS internship) | IRSense scheduler, RTOS internship (CSC India / APSCHE) |
| **IoT & connectivity** | ESP32 Wi-Fi + MQTT with echo-loop-safe topic design, web dashboards, RFID, energy metering, BLE, 4G LTE / GPS | [SmartHomeAutomation](https://github.com/MohansaiPotnuru/SmartHomeAutomation), DRE-MachGuard |
| **Digital design & VLSI** | Verilog SoC integration (PicoRV32, boot ROM, MMIO UART), self-checking testbenches, synthesis, floorplan, CTS, routing, **multi-corner STA**, DRC / LVS / antenna signoff | [RISC-V SoC on SKY130](https://github.com/MohansaiPotnuru/riscv-uart-sky130-soc) |
| **Embedded Linux** | Yocto-based SAMA5D2 board bring-up with libmraa: GPIO, ADC, PWM, SPI, Wi-Fi | [MRAA RuggedBoard](https://github.com/MohansaiPotnuru/MRAA---RuggedBoard---A5D2X) |
| **Hardware & sensors** | Sensor interfacing and conditioning (NPTEL *Sensors & Actuators*, Elite), KiCad PCB design, power and battery systems, EV charging and BMS | Solar EV charging station, EV workshop |
| **Data & ML at the edge** | Leakage-free scikit-learn pipelines, model comparison, feature engineering on sensor time series | [AQI Prediction](https://github.com/MohansaiPotnuru/Air-Quality-Prediction-by-AICTE) |

---

### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### 📟 [IRSense: IR counter & conveyor monitor](https://github.com/MohansaiPotnuru/IRSense-NUCLEO-F401RE)
Bare-metal STM32F401 firmware that turns an IR sensor into a measurement instrument: **µs edge timing**, jam/rate/intrusion alarms, serial CLI and **wear-levelled, CRC-protected flash config**.

`C` `STM32` `Cortex-M4` `45 unit tests` `ASan/UBSan CI` `v1.0.0 release`

</td>
<td width="50%" valign="top">

#### 🧬 [RISC-V UART SoC on SKY130](https://github.com/MohansaiPotnuru/riscv-uart-sky130-soc)
32-bit **PicoRV32** SoC with boot ROM and memory-mapped UART, hardened **RTL → GDSII** with LibreLane on the SkyWater 130 nm PDK. **Warning-free signoff across 9 PVT/RC corners**: DRC, LVS, antenna, slew, cap and fanout all clean.

`Verilog` `RISC-V` `LibreLane` `OpenROAD` `9-corner STA` `GDS release`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🏠 [ESP32 Smart Home Automation](https://github.com/MohansaiPotnuru/SmartHomeAutomation)
Modular home-automation firmware: environment and gas/smoke safety sensing, **RFID door access**, PZEM-004T energy metering, MQTT, web dashboard and OLED, with manual override.

`C++` `ESP32` `MQTT` `arduino-cli CI (2 cores)`

</td>
<td width="50%" valign="top">

#### 🛠️ DRE-MachGuard: offline machinery fault monitor
ESP32 condition monitor for remote sites with no internet: DS18B20 temperature, supply voltage, current and vibration events, rule-based diagnostics, OLED and 3-colour alerts. **Top 6 finalist with prize, DRE Enterprise Hackathon '26.**

`ESP32` `DS18B20` `condition monitoring` `offline-first`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🌫️ [AQI Prediction (AICTE × Shell)](https://github.com/MohansaiPotnuru/Air-Quality-Prediction-by-AICTE)
Daily Air Quality Index prediction for 26 Indian cities with leakage-free scikit-learn pipelines. 5 models compared, **Random Forest R² 0.91**. **Top 40 project nationally.**

`Python` `scikit-learn` `pandas` `Jupyter`

</td>
<td width="50%" valign="top">

#### 🐧 [MRAA on RuggedBoard-A5D2X](https://github.com/MohansaiPotnuru/MRAA---RuggedBoard---A5D2X)
GPIO / ADC / PWM / SPI / Wi-Fi guides and Python examples for an industrial **Microchip SAMA5D2 Yocto Linux** board.

`Embedded Linux` `Yocto` `libmraa`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### 📚 [100 Advanced C & Python Programs](https://github.com/MohansaiPotnuru/C_-_Python_Programs)
Self-testing programs on bit manipulation, pointers, memory layout, function pointers, metaprogramming and concurrency, checked with **GCC/Clang sanitizers** and Python 3.10–3.13 in CI.

`C` `Python` `embedded C interview prep`

</td>
</tr>
</table>

---

### 📐 How I build firmware

```text
 Requirements → timing budget → state machines → pure, host-tested logic → thin HAL/BSP → on-target test → CI → release
```

- **Determinism first:** every ISR is short, every loop has a bounded worst case, and every task has a period and a deadline
- **Split pure from hardware:** CRC, filters, parsers and state machines compile on the host and run under ASan/UBSan
- **Fail loudly, recover safely:** watchdogs, CRC-checked config, defaults on corruption, alarms with hysteresis
- **Signoff mindset from VLSI:** no "it works on my board"; numbers, corners and reports or it didn't happen

---

### 🏆 Achievements & leadership

| | |
|---|---|
| 🥇 **Top 6 Finalist + prize**, DRE Enterprise Hackathon '26 (Team INVENTORS, DRE-MachGuard) | Oct 2026 |
| 🏅 **Top 40 project nationally**, AICTE × Shell India Skills4Future (AI & Data Analytics) | 2025 |
| 🛰️ **Lead Support**, NASA International Space Apps Challenge, Visakhapatnam | 2025 & 2026 |
| 📡 **Chairperson**, IETE Student Forum, DLBCE | current |
| ⚡ **Resource Person**, 3-day EV Technology workshop (DIET × APSSDC): batteries, BMS, motors, charging | 2026 |
| 🇮🇳 **Stage II qualifier**, Viksit Bharat Young Leaders Dialogue 2026 | 2026 |
| 🎪 **Main Student Coordinator**, Technotsav (ECE) · represented Kaumodaki NexusGrid at **IoT Summit '26** and **Future Skills Summit 2026** | 2026 |
| 🔋 **Team Lead**, solar-powered EV charging station (Diploma final-year project) | 2023 |

---

### 📜 Certifications & training

- **NPTEL** Sensors and Actuators (Elite, 12 weeks) · **Cisco** Introduction to IoT · Introduction to IoT and Digital Transformation
- **RTOS internship** (CSC India / APSCHE, 2 months) · **Full Stack Python & Agentic AI internship** (CSC India / APSCHE)
- **CII** Applied Machine Learning & AI (INDIAai) · **CII DX-EDGE** Digital Maturity Diagnostic Framework (NITI Aayog / AICTE)
- **MongoDB** Basics for Students · **Automation Anywhere** Essentials · **Salesforce** Agentblazer Champion · **Agnirva** Space & AI internships (AICTE recognised)
- 30+ certifications in total, from Cisco, NIELIT, ISRO, TCS iON, Coursera and Great Learning

---

### 🧰 Tech stack

**Languages**<br>
<img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C">
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Verilog-8A2BE2?style=flat-square" alt="Verilog">
<img src="https://img.shields.io/badge/ARM_Assembly-0091BD?style=flat-square&logo=arm&logoColor=white" alt="ARM Assembly">

**MCUs, SoCs & boards**<br>
<img src="https://img.shields.io/badge/STM32_(Cortex--M4)-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32">
<img src="https://img.shields.io/badge/ESP32_·_ESP32--CAM-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32">
<img src="https://img.shields.io/badge/Arduino_·_NodeMCU-00878F?style=flat-square&logo=arduino&logoColor=white" alt="Arduino and NodeMCU">
<img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">
<img src="https://img.shields.io/badge/Microchip_SAMA5D2-EE2223?style=flat-square&logo=microchiptechnology&logoColor=white" alt="Microchip SAMA5D2">
<img src="https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white" alt="RISC-V">

**Real-time, embedded & protocols**<br>
<img src="https://img.shields.io/badge/RTOS_·_FreeRTOS-5CB85C?style=flat-square" alt="RTOS and FreeRTOS">
<img src="https://img.shields.io/badge/Yocto_Linux-4A8FCC?style=flat-square&logo=linux&logoColor=white" alt="Yocto Linux">
<img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white" alt="MQTT">
<img src="https://img.shields.io/badge/BLE_·_Wi--Fi-0082FC?style=flat-square&logo=bluetooth&logoColor=white" alt="BLE and Wi-Fi">
<img src="https://img.shields.io/badge/4G_LTE_·_GPS-6E6E6E?style=flat-square" alt="4G LTE and GPS">
<img src="https://img.shields.io/badge/UART_·_SPI_·_I²C_·_1--Wire-555555?style=flat-square" alt="UART SPI I2C 1-Wire">

**EDA & VLSI**<br>
<img src="https://img.shields.io/badge/LibreLane_·_OpenLane-1F6FEB?style=flat-square" alt="LibreLane and OpenLane">
<img src="https://img.shields.io/badge/Yosys_·_OpenROAD-1F6FEB?style=flat-square" alt="Yosys and OpenROAD">
<img src="https://img.shields.io/badge/Magic_·_KLayout_·_Netgen-1F6FEB?style=flat-square" alt="Magic, KLayout and Netgen">
<img src="https://img.shields.io/badge/Icarus_Verilog-1F6FEB?style=flat-square" alt="Icarus Verilog">
<img src="https://img.shields.io/badge/SkyWater_SKY130-1F6FEB?style=flat-square" alt="SKY130 PDK">
<img src="https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white" alt="KiCad">

**Tools & workflow**<br>
<img src="https://img.shields.io/badge/STM32CubeIDE-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32CubeIDE">
<img src="https://img.shields.io/badge/PlatformIO-F5822A?style=flat-square&logo=platformio&logoColor=white" alt="PlatformIO">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter">

---

### 🔭 Currently working on

- ⏱️ FreeRTOS on STM32: task-set design with rate-monotonic priorities, response-time analysis and watchdog supervision
- 🧬 Next SoC revision: SPI/GPIO peripherals, a Wishbone bus and gate-level simulation against the signed-off netlist
- 📶 Low-power IoT nodes: sleep-mode budgets, battery-life estimation and OTA-safe update layouts

---

### 🐍 Contribution activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MohansaiPotnuru/MohansaiPotnuru/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MohansaiPotnuru/MohansaiPotnuru/output/snake.svg">
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/MohansaiPotnuru/MohansaiPotnuru/output/snake.svg">
</picture>

---

<p align="center">
  📫 Reach me on <a href="https://www.linkedin.com/in/mohan-sai-potnuru-0b274a299">LinkedIn</a> · browse <a href="https://github.com/MohansaiPotnuru?tab=repositories">all repositories</a>
</p>
