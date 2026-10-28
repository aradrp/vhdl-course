# VHDL Coursework

A collection of selected VHDL projects developed as part of university coursework in digital systems design and FPGA development.

This repository includes a 16×16-bit register file implementation and an FPGA-based game featuring VGA graphics, developed using VHDL and Xilinx ISE.

## Projects

### 1. Register File

A 16-entry, 16-bit register file implemented in VHDL with a validity bit for each entry.

**Features:**
- Insert and delete data
- Search and retrieve values
- Count valid entries
- Reverse and rotate register contents
- Sort register values
- Clear the register file

The project includes a self-checking testbench designed to verify the implemented operations.

**Technologies:** VHDL-93, Active-HDL

### 2. ButterflyScape

A university group project developed as part of a Computer-Aided Design (CAD) course.

ButterflyScape is an FPGA-based game featuring VGA graphics, button input, LED indicators, and seven-segment display output.

**Features:**
- VGA-based game graphics
- Game state and rendering logic
- FPGA board input and output interfaces
- VGA timing and synchronization
- Hardware pin configuration

**Technologies:** VHDL, Xilinx ISE 14.7, Spartan-6 FPGA

**Team Members:**
- Arad Razpour
- Reza Yaghoubi

## Repository Structure

```text
vhdl-course/
├── register-file/
│   ├── reg.vhd
│   ├── reg_pkg.vhd
│   ├── tb_reg.vhd
│   ├── reg_TB_runtest.do
│   └── README.md
│
├── butterflyscape/
│   ├── ButterflyScapeGame.vhd
│   ├── ButterflyScapeTop.vhd
│   ├── VGA_controller.vhd
│   ├── VGA.ucf
│   ├── ButterflyScape.xise
│   └── README.md
│
└── README.md
```

## Tools and Technologies

- VHDL
- Active-HDL
- Xilinx ISE 14.7
- Spartan-6 FPGA
- VGA interface
- Digital system design
- Simulation and testbench development

## Learning Objectives

These projects demonstrate practical experience with:

- Digital logic design using VHDL
- Register-based data storage and manipulation
- Hardware description and simulation
- Testbench development and functional verification
- FPGA-based system design
- VGA timing and graphics output
- Hardware input and output interfacing

## Notes

These projects were developed as part of university coursework.

The repository contains the original source files and relevant project configurations. Generated simulation and synthesis outputs are excluded.

Simulation and synthesis have not been rerun in the prepared repository copy.

For project-specific setup and instructions, refer to the README file inside each project folder.
