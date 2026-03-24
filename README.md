# Daniel Lee
**ECE @ University of Toronto** · Computer Hardware & Architecture

I build things at the intersection of hardware and software — from FPGA-based navigation systems to battery management research. Currently a 2nd year ECE student at UofT with hands-on experience in RTL design, embedded firmware, and hardware bring-up.

---

## What I Work On

| Area | Details |
|---|---|
| **Digital Design / HDL** | Verilog, SystemVerilog — FSMs, pipelines, VGA controllers on DE1-SoC |
| **Embedded Systems** | C/C++, memory-mapped I/O, interrupt-driven design, RISC-V assembly |
| **Analog Electronics** | BJT/MOSFET amplifier design, small-signal modeling, LTSpice simulation |
| **PCB & Schematic** | Altium Designer — currently designing an HF radio receiver front-end |
| **Research** | Adaptive Kalman filter-based state-of-charge estimation for Li-ion BMS |

---

## Featured Projects

### 🔧 [ObstacleOdyssey](https://github.com/lee-lung/obstacle-odyssey)
> Interactive self-driving car simulation · Bug 2 pathfinding · 320×240 VGA · DE1-SoC · Verilog &nbsp;·&nbsp; [▶ Demo](https://www.youtube.com/watch?v=9vhl6w_qnwg)

Hardware implementation of an autonomous vehicle simulation on FPGA. Users place obstacles interactively via switches and keys; the car navigates from start to goal in real time using a Bug 2-style pathfinding algorithm rendered as a live bird's-eye VGA display.

`Verilog` `DE1-SoC` `FSM` `VGA` `Quartus Prime`

---

### 📡 [Ultrasonic Sonar Radar](https://github.com/lee-lung/sonar-radar)
> Real-time proximity mapping · HC-SR04 + Servo Sweep · Nios V · Embedded C · VGA Polar Display

Embedded sonar system on the DE1-SoC featuring an HC-SR04 ultrasonic sensor mounted on a servo for angular sweep. An Arduino front-end handles sensor timing and sends distance data over UART to the Nios V soft processor, which computes obstacle positions using fixed-point arithmetic and renders a live polar sonar map on VGA. Includes voltage-level-shifted GPIO interfacing between 5V and 3.3V logic domains.

`Embedded C` `Nios V (RISC-V)` `UART` `VGA` `DE1-SoC` `Arduino`

---

### 📡 Tayloe Quadrature Mixer
> HF Radio Receiver Front-End

Designed and validated a Tayloe quadrature mixer subsystem for an HF hybrid software-defined radio receiver. Verified in LTSpice simulation; transitioned to Altium for PCB schematic capture.

`Altium Designer` `LTSpice` `Analog RF` `SDR`

---

### 🔋 Adaptive Kalman Filter BMS — Smart Power Integration and Semiconductor Devices Research Group
> State-of-Charge Estimation · Li-ion Battery Systems · MATLAB

Undergraduate research on adaptive Kalman filter algorithms for real-time SoC estimation in lithium-ion battery packs. Work conducted at UofT's Smart Power Integration & Semiconductor Devices Research Group.

`MATLAB` `Kalman Filter` `Battery Systems` `Research`

---

## Tools & Skills

```
Languages    Verilog  |  C/C++  |  Python  |  MATLAB  |  RISC-V Assembly
EDA          Quartus Prime  |  ModelSim  |  Altium Designer  |  LTSpice
Hardware     DE1-SoC (Cyclone V FPGA)  |  STM32  |  Oscilloscope  |  Logic Analyzer
```

---

## Currently

- 🎓 2nd Year ECE @ University of Toronto (cGPA focused on Areas 3 & 5)
- 🔬 Undergraduate Researcher @ DSEL — BMS & SoC estimation
- 🏎️ Hardware/Firmware — Blue Sky Solar Racing & UofT Supermileage
- 🔍 Seeking Summer 2026 internships in **cleantech · EV · semiconductors · embedded systems**

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Daniel_Lee-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/lee-lung)
[![Website](https://img.shields.io/badge/Portfolio-daniellee.lovable.app-000000?style=flat&logo=vercel)](https://daniellee.lovable.app)
[![Email](https://img.shields.io/badge/Email-lungshinglee@mail.utoronto.ca-EA4335?style=flat&logo=gmail)](mailto:lungshinglee@mail.utoronto.ca)
