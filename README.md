# 32-Bit Workload-Adaptive AI ALU & CMOS ASIC Silicon Layout
Lead Silicon Architect: Mohammed Abdullah
FPGA Verified on AMD Artix-7 (107 mW, 689 LUTs) | Custom GDSII Silicon Layout (108 Bond Pads)

[![Verilog](https://img.shields.io/badge/HDL-Verilog%20%7C%20SystemVerilog-orange?style=for-the-badge)](https://github.com/abdullaah0309)
[![ASIC Layout](https://img.shields.io/badge/ASIC-GDSII%20Layout%20Verified-blueviolet?style=for-the-badge)](https://github.com/abdullaah0309)
[![Live Portfolio](https://img.shields.io/badge/Portfolio-abdullaah0309.github.io-00f5d4?style=for-the-badge)](https://abdullaah0309.github.io)

---

## 🏛️ Silicon ASIC Floorplan Architecture
Floorplan Layout Structure (adaptive_ai_alu_chip.gds):
- Outer Perimeter: 108 Peripheral Wire-Bond I/O Pads (Power, Clock, Inputs, Outputs)
- Dual Power Ring: Concentric VDD (Core) and VSS (Ground) Low-IR-Drop Power Rings
- Core Region: 4-Lane INT8 SIMD Dot-Product Multiply-Accumulate Engine
- Adaptive Power Logic: 16-bit Dynamic Operand Isolation and Hardware ReLU

---

## 🔬 Silicon Implementation Scorecard
- FPGA Target: Synthesized and routed on AMD Artix-7 (xc7a35tcsg324-1)
- Timing: 100 MHz Timing Met (Zero Timing Violations)
- Total Power: 107 mW
- Resource Footprint: 689 Logic LUTs
- Full-Custom ASIC Stream: layout/adaptive_ai_alu_chip.gds (Verified in KLayout)

---

## 📁 Repository Structure
- rtl/ : Synthesizable Verilog source files
- layout/ : Physical GDSII layout stream file (adaptive_ai_alu_chip.gds)
- reports/ : Synthesis, timing, and power consumption reports

---
(c) 2026 Mohammed Abdullah. Designed for high-performance silicon engineering.
