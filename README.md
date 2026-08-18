# STM32F411 Custom 4-Layer PCB Design

A custom 4-layer STM32F411 development board designed in Altium Designer, integrating an MPU6050 IMU, USB power/data interface, 3.3V power supply, SWD programming/debugging interface, and supporting decoupling circuitry.

The project focuses on developing the schematic, defining PCB constraints and layer stackup, and performing systematic component placement and layout refinement for a manufacturable embedded hardware design.

# Project Overview

The objective of this project is to design a compact, reliable STM32F411-based custom PCB rather than relying on a development board.

# Main Features
MCU: STM32F411

PCB: 4-layer board

IMU: MPU6050

Programming/Debugging: SWD

Communication/Power: USB

Logic Supply: 3.3V

PCB Design Tool: Altium Designer

Fabrication Target: JLCPCB

# Schematic Design

The schematic was developed in Altium Designer with dedicated circuitry for the STM32F411, MPU6050, USB interface, power supply, SWD programming/debugging, and decoupling.
![image alt](https://github.com/AmitBastia/STM32-Custom-PCB-Design-and-Development/blob/main/PCB_Schematic.png)



# PCB Design

The PCB was developed as a 4-layer board with the layer stackup and design constraints configured according to PCB fabrication requirements.

Layer Stackup

The 4-layer stackup was configured to support proper power distribution, signal routing, and controlled-impedance requirements.






# Component Placement

Component placement was performed by separating the major functional sections of the board, including:

STM32F411 MCU

MPU6050 IMU

USB interface

Power supply

SWD programming interface

Decoupling components

Placement was refined with consideration for signal paths, power distribution, accessibility, and PCB layout constraints.

# PCB Placement

# Tools Used
       Tool	                           Purpose

Altium Designer               Schematic and PCB design

STM32CubeIDE	                STM32 pinout/configuration reference

JLCPCB	                      Fabrication requirements and design-rule reference
