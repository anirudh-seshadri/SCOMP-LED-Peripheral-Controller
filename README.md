# SCOMP LED Peripheral Controller

This project implements a dual-mode LED control peripheral for the SCOMP architecture using VHDL. It supports both **PWM-based brightness modulation** and **toggle-based LED state control**, allowing for flexible and programmable LED behavior.

## Features

- **Dual-Mode Operation**:
  - **PWM Mode**: Supports four discrete brightness levels (25%, 50%, 75%, 100%) with gamma correction for improved visual fidelity and efficient power management.
  - **Toggle Mode**: Allows specific LEDs to change state without using physical switches, enabling software-driven flashing patterns.

- **Simulation and Deployment**:
  - Verified through **ModelSim simulation**.
  - Synthesized and deployed on a **Cyclone V FPGA** using **Quartus Prime**.
  - Integrated with SCOMP through **instruction-level control using assembly**.

## Technologies Used

- VHDL
- Assembly
- Quartus Prime
- ModelSim
- Cyclone V FPGA

## Authors

- Anirudh Seshadri and team (Spring 2025, Georgia Tech ECE 2031)
