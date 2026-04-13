# 🖥️ Simple Digital Computer Design (8-Bit CPU)

A comprehensive implementation of an 8-bit digital computer architecture, designed from the ground up using **Logisim-evolution** and **VHDL**. This project features a custom Instruction Set Architecture (ISA), a hardwired control unit, and a dedicated Python-based assembler.

---

## 📸 Project Overview
This project demonstrates the design and simulation of a functional CPU based on the **Von Neumann architecture**. It includes the complete datapath design, control logic, and software tools to program the hardware.

> **Note:** The project files (Logisim `.circ` and VHDL source) are currently private. This repository serves as a showcase of the design, results, and documentation.

### Key Components:
- **CPU (8-bit):** Custom-designed Central Processing Unit.
- **ISA:** 13 unique instructions including MRI (Memory Reference Instructions) and RRI (Register Reference Instructions).
- **Control Unit:** Hardwired logic with a 3-bit sequence counter (T0-T7 timing pulses).
- **Memory:** Integrated RAM and ROM units.
- **Assembler:** A custom Two-Pass Assembler developed in Python with a GUI.

---

## 🛠️ Tools & Technologies
- **Hardware Design:** [Logisim-evolution](https://github.com/logisim-evolution/logisim-evolution) (Logic simulation).
- **Hardware Description:** VHDL (Hardware synthesis and verification).
- **Software Tools:** Python (Assembler development), Custom GUI for the assembler.
- **Verification:** MAX+PLUS II (Waveform simulation and timing analysis).

---

## 📜 Instruction Set Architecture (ISA)
The computer supports a tailored set of 13 instructions to perform arithmetic, logic, and control operations:

| Type | Instructions |
| :--- | :--- |
| **Memory Reference (MRI)** | AND, ADD, LDA, STA, BUN, BSA, ISZ |
| **Register Reference (RRI)** | CLA, CLE, CMA, CME, CIR, CIL, INC, SPA, SNA, SZA, SZE, HLT |

---

## 🚀 Results & Visuals
The design has been fully verified through hierarchical simulation. You can find detailed screenshots of the architecture in this repository:

### Core Components

#### Main System Architecture
![Main System Architecture](./MAIN.png)

#### Instruction Decoder
![Instruction Decoder](./IR_DEC.png)

#### CPU Datapath
- **[CPU Datapath (PDF)](./A3_CPU.pdf):** Detailed PDF showing the CPU internal structure.

### Simulation and Test Runs

#### Simulation Test Run
![Simulation Test Run](./TEST_RUN.png)

### Additional Screenshots

![Screenshot 2025-08-26 230248](./Screenshot%202025-08-26%20230248.png)
![Screenshot 2025-08-26 230305](./Screenshot%202025-08-26%20230305.png)
![Screenshot 2025-08-27 002231](./Screenshot%202025-08-27%20002231.png)
![Screenshot 2025-08-27 002247](./Screenshot%202025-08-27%20002247.png)
![Screenshot 2025-08-27 002439](./Screenshot%202025-08-27%20002439.png)
![Screenshot 2025-08-27 002454](./Screenshot%202025-08-27%20002454.png)
![Screenshot 2026-04-07 195042](./Screenshot%202026-04-07%20195042.png)
![Screenshot 2026-04-07 195143](./Screenshot%202026-04-07%20195143.png)
![Screenshot 2026-04-07 195245](./Screenshot%202026-04-07%20195245.png)
![Screenshot 2026-04-07 195326](./Screenshot%202026-04-07%20195326.png)
![Screenshot 2026-04-07 195431](./Screenshot%202026-04-07%20195431.png)
![Screenshot 2026-04-08 200816](./Screenshot%202026-04-08%20200816.png)
![Screenshot 2026-04-08 200838](./Screenshot%202026-04-08%20200838.png)

---

## 📋 Requirements
- **Simulation:** Logisim-evolution (for `.circ` files).
- **VHDL Environment:** Any VHDL-compatible simulator (e.g., ModelSim, GHDL) or synthesis tool (e.g., MAX+PLUS II, Quartus).
- **Assembler:** Python 3.x with standard libraries for the GUI.

---

## 👥 Team Members
This project was developed by a dedicated team at **Sana'a University, Faculty of Engineering**:

- **Mutasim Al-Kamil** ([GitHub](https://github.com/Asoomkamel) | [LinkedIn](https://www.linkedin.com/in/mutasim-al-kamil-40a299318))
- **Mamdouh Abdul-Fattah**
- **Hussein Abdul-Mueen**
- **Osama Mohammed Moawad**

**Supervised by:**
- Prof. Abdul-Raqeeb Abdu As'ad
- Eng. Iman Bashar

---

## 📞 Contact Information
For inquiries or collaborations, feel free to reach out:

- **Developer:** Mutasim Al-Kamil
- **Phone:** [+967 776 725 574](tel:+967776725574)
- **LinkedIn:** [Mutasim Al-Kamil](https://www.linkedin.com/in/mutasim-al-kamil-40a299318)
- **GitHub:** [@Asoomkamel](https://github.com/Asoomkamel)

---
*© 2025 Sana'a University - Digital Computer Design Project*
