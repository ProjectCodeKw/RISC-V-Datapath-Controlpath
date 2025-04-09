# RISC-X Processor Simulation

This project implements a simplified RISC-X processor architecture using Verilog and Quartus II software. Developed as part of the Computer Organization course at Kuwait University, the project was completed in three phases:

## Phase 1: ALU and Register File
- Designed an 8-bit ALU supporting Add, Subtract, AND, and OR operations with control signals and zero-flag output.
- Implemented an 8-register file with two read ports and one write port.

## Phase 2: Memory Design
- Created a 16-bit instruction memory (ROM) and 8-bit data memory (RAM) using block diagram files (BDF).
- Simulated reading/writing operations and verified outputs with waveforms.

## Phase 3: RISC-X Datapath and Control Unit
- Designed a custom datapath and control unit to support RISC-X instructions (R-type, I-type, and S-type).
- Implemented program counter, multiplexers, control logic, and memory integration.
- Executed test programs with instructions like `addi`, `sb`, `add`, and `nand`, and verified outputs.

## Key Features
- Instruction decoding and execution via a custom control unit.
- Functional register file, ROM, RAM, ALU, and program counter.
- Fully simulated environment with waveform verification.
- Written entirely in Verilog HDL.

## Suggested Changes [FIXES]
- Change the sign extension used in the mux(s) to unsigned extend [add bit 0 rather than extending the last bit].
  
## Designed and Developed by:
- Asmaa Adel Alazmi 

Instructor: Dr. Sami Hbib  
TA: Eng. Zainab Bahbahani  
Date: December 13, 2024
