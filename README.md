# 8--bit-ALU-design-with-16-choices-IC
8-bit ALU Design in VHDL with testbench and constraint file

## Documentation

- 📄 [Project Report](docs/VLSI_INNOVATORS.docx)
- 📊 [Project Presentation](docs/VLSI_INNOVATORS.pptx)

- # 8-bit ALU Design using VHDL

## 📌 Project Overview
This project implements an 8-bit Arithmetic Logic Unit (ALU) using VHDL.  
The ALU performs multiple arithmetic and logical operations based on control signals.

The design was simulated using ModelSim and synthesized using Xilinx Vivado.

---

## ⚙️ Features
The ALU supports the following operations:

- Addition (A + B)
- Subtraction (A - B)
- Bitwise AND
- Bitwise OR
- Bitwise XOR
- NOT operation
- Increment
- Decrement
- Left Shift
- Right Shift

Operation selection is controlled using a 4-bit select line.

---

## 🏗 Block Diagram
The ALU consists of:
- Two 8-bit input operands (A and B)
- 4-bit select line
- Arithmetic unit
- Logic unit
- Output multiplexer
- 8-bit result output
- Carry / Zero flags (if implemented)

---
---

## 🛠 Tools Used
- VHDL
- ModelSim (Simulation)
- Xilinx Vivado (Synthesis & Implementation)
- FPGA Board (if used)

---

## ▶️ Simulation Procedure
1. Compile alu.vhd
2. Compile alu_tb.vhd
3. Run simulation
4. Verify waveform outputs for different select inputs

---

## 📊 Output
The ALU generates:
- 8-bit Result
- Carry flag
- Zero flag (if implemented)

Waveforms verify correct operation for all select conditions.

---

## 🎯 Applications
- Microprocessors
- Digital Signal Processing
- Embedded Systems
- FPGA-based system design

---

## 🚀 Future Improvements
- Add overflow flag
- Add multiplication/division
- Design pipelined ALU
- Integrate with CPU architecture

---

## 👨‍💻 Author
SOUMYADEEP MUKHERJEE 
B.Tech - Electronics & Telecommunication Engineering

## 💡 Concepts Used
- Finite State Design
- Combinational Logic
- Multiplexer Design
- Behavioral Modeling in VHDL

## 📂 Project Structure

