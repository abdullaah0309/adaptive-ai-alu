# 32-Bit Workload-Adaptive AI ALU & CMOS ASIC Silicon Layout
Lead Silicon Architect: Mohammed Abdullah
FPGA Verified on AMD Artix-7 (107 mW, 689 LUTs) | Custom GDSII Silicon Layout (108 Bond Pads)

[![Verilog](https://img.shields.io/badge/HDL-Verilog%20%7C%20SystemVerilog-orange?style=for-the-badge)](https://github.com/abdullaah0309)
[![ASIC Layout](https://img.shields.io/badge/ASIC-GDSII%20Layout%20Verified-blueviolet?style=for-the-badge)](https://github.com/abdullaah0309)
[![Live Portfolio](https://img.shields.io/badge/Portfolio-abdullaah0309.github.io-00f5d4?style=for-the-badge)](https://abdullaah0309.github.io)

---

## 🏛️ Architecture Highlights
1. Dynamic Operand Isolation: Automatically detects low-magnitude operand states and gates the upper 16-bit adder/multiplier logic trees, eliminating redundant switching energy.
2. 4-Lane INT8 SIMD Vector Mode: Reconfigures the 32-bit datapath into four parallel 8-bit dot-product lanes for AI inference workloads.
3. Hardware Activation: Integrated single-cycle ReLU unit for zero-bubble inference pipelines.

---

## 🔬 Silicon Implementation & Physical Design
- FPGA Implementation: Synthesized, placed, and routed on AMD Artix-7 (xc7a35tcsg324-1) with 100 MHz timing closure, 107 mW total power, and 689 Logic LUTs.
- Custom CMOS ASIC Layout: Complete GDSII chip layout generated in KLayout (adaptive_ai_alu_chip.gds) featuring:
  - 108 I/O peripheral wire-bond pads
  - Dual concentric VDD and VSS low-IR-drop power rings
  - Symmetrical power delivery grid across the compute core

---

## 📁 Repository Structure
- rtl/ : Synthesizable Verilog/SystemVerilog sources and timing constraints
- layout/ : Complete ASIC GDSII physical layout stream file (adaptive_ai_alu_chip.gds)
- reports/ : Synthesis, timing, and power consumption reports

---
(c) 2026 Mohammed Abdullah. Designed for high-performance silicon engineering.
