# 🛠️ AMIRALI IMANIPANAH | EMBEDDED SYSTEMS & ROBOTICS

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=700&size=23&pause=1100&color=8A2BE2&center=true&v=4&width=680&lines=STM32+EMBEDDED+SYSTEMS;AUTONOMOUS+ROBOTICS+%26+ROS+2;PCB+DESIGN+%26+SYSTEM+INTEGRATION;FPGA+%26+DIGITAL+HARDWARE" alt="Engineering focus: STM32, robotics, PCB and FPGA" />
</p>

<p align="center">
  <a href="https://iocraft.ir"><img src="https://img.shields.io/badge/PORTFOLIO-iocraft.ir-8A2BE2?style=flat-square&logo=opsgenie&logoColor=white" alt="Portfolio" /></a>&nbsp;
  <a href="mailto:amir.imanipanah@gmail.com"><img src="https://img.shields.io/badge/EMAIL-CONTACT-FF00FF?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>&nbsp;
  <a href="./Amirali_Imanipanah_CV.pdf"><img src="https://img.shields.io/badge/RESUME-VIEW_PDF-8A2BE2?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="View resume PDF" /></a>
</p>

---

## ⚡ MISSION CONTROL | About Me

I'm an **Electrical Engineering (Electronics) graduate** from the **University of Isfahan** (September 2026; **GPA: 16.80/20**), focused on **STM32-based embedded systems, autonomous robotics, and PCB design**.

I enjoy building at the intersection of **firmware, electronics, and system integration**: from microcontroller peripherals and control logic to ROS 2 robotics, custom circuit boards, and graphical embedded interfaces. **FPGA-based digital design** is a complementary area of my work.

- **Embedded development:** STM32 (F1/F4/H7), C/C++, FreeRTOS, DMA, TouchGFX, and peripheral interfaces.
- **Robotics:** ROS 2, Raspberry Pi 5, RP2040 motor control, sensing, odometry, and distributed software architecture.
- **Hardware:** schematic capture, multilayer PCB design, board-level integration, and prototyping.
- **Digital systems:** Verilog, pipelined CORDIC architectures, and MATLAB-based design exploration.

> **Engineering approach:** Document what is implemented, distinguish simulation from physical tests, and make technical claims reproducible.

---

## 🛠️ EXPERTISE MATRIX | Technical Stack

| Embedded & Firmware | Robotics & Linux | Hardware & PCB | Digital Design & Tools |
|:---|:---|:---|:---|
| STM32 F1/F4/H7, ESP32 | ROS 2, Raspberry Pi 5 | Altium Designer, KiCad | FPGA, Verilog |
| RP2040, AVR, STM8 | Embedded Linux, Python | Schematic & PCB Design | MATLAB, Git |
| C/C++, FreeRTOS, DMA | Sensor interfaces, odometry | PSpice, Proteus | Linux CLI, SolidWorks |
| TouchGFX, UART, SPI, I²C | Hardware–software integration | SMD assembly & prototyping | Digital system design |
| ADC, PWM | | | |

*FreeRTOS, DMA, and TouchGFX are skills gained through embedded development work; they are not presented below as implemented features of the HMI V1 or V2 projects.*

---

## 📁 SELECTED ENGINEERING PROJECTS

<details>
<summary><b>🤖 01 — ROS 2-Based Autonomous Mobile Robot | B.Sc. Thesis</b></summary>

<br>

**Distributed mobile-robot platform** with Raspberry Pi 5 for ROS 2 integration, RP2040 for time-sensitive wheel control and safety, and a separate vision-processing architecture.

- Implemented a **CRC-protected Pico–Pi communication protocol**, closed-loop motor-control firmware, wheel odometry, and LiDAR sample aggregation.
- Developed an embedded **Neuro-PID inference path** with separate offline training scripts.
- Documented **five KiCad PCB designs** for power distribution, motor power, Pico interfacing, Pi protection, and thermal management.
- Host-side testing reported **18/18 behavior checks** and **10/10 fail-safe checks**; evaluated processing/offloading using **software emulation**.

**Validation boundary:** These results are not measurements of the finished physical robot, SLAM/Nav2 navigation, or real GPU inference. The repository does not contain a fully evaluated Nav2/SLAM deployment.

*Thesis repository is private; source access can be provided on request.*

</details>

<details>
<summary><b>🎛️ 02 — STM32 Graphical HMI & Embedded Instrument Platform | V1 → V2</b></summary>

<br>

**V1 — STM32F407**

- Developed a TFT/capacitive-touch HMI concept with graphical plotting and matrix-processing functionality.

**V2 — STM32H723 (in development)**

- Designing a **four-layer embedded instrument** with shared FMC interfaces for **SDRAM and TFT**, capacitive touch, **ESP32-C6** connectivity, and expansion I/O.
- Investigated **FMC timing, MCU pin allocation, memory/display integration, and PCB placement constraints**.

**Status:** V2 is an ongoing hardware architecture/schematic project; final PCB operation and hardware performance have **not** been validated.

</details>

<details>
<summary><b>⚡ 03 — Zero-DSP FPGA Multi-Sensor Accelerator | Verilog + MATLAB</b></summary>

<br>

A multiplierless digital processing architecture for LiDAR/IMU-related computation on **Xilinx Spartan-6**.

- Designed **CORDIC coordinate transforms**, adaptive shift-based Kalman filtering, and a **4-tap distributed-arithmetic FIR** filter.
- Compared **MATLAB HDL Coder** approaches with a custom **13-stage pipelined Verilog CORDIC** core.
- Project reports **115.399 MHz tool-estimated Fmax** and **zero DSP slice usage**; these are implementation-tool results, not a claimed board-level throughput measurement.

🔗 **[Explore the FPGA project](https://github.com/Amir-imani/FPGA-MultiSensor-Accelerator)**

</details>

---

## 🎓 EDUCATION & TEACHING

**B.Sc. in Electrical Engineering (Electronics)** — University of Isfahan  
**Sep 2022 – Sep 2026** · **GPA: 16.80 / 20.00**

**Teaching Assistant (4 courses, 2025–2026)** — University of Isfahan

- **Microcontrollers:** AVR/STM32 instruction and interfacing support for **80+ students**.
- **Electronics I; Electric Circuits I; Fundamentals of Programming:** circuit analysis, transistor circuits, C++ fundamentals, and debugging.

### 📜 Selected Certifications & Training

- **IEEE Student Branch:** Professional PCB Design (Advanced, 2024); Introductory PCB Design (2023).
- **Faradars:** Four-Layer PCB Design (Altium Designer); Practical Four-Layer FPGA Board Design.

---

## 🎮 GITHUB ACTIVITY

<p align="center">
  <img src="https://raw.githubusercontent.com/Amir-imani/Amir-imani/output/github-contribution-grid-snake.svg" alt="GitHub contribution activity" />
</p>

---

<p align="center">
  <sub><i>"From embedded firmware to complete hardware systems — build, measure, and iterate."</i></sub>
</p>
