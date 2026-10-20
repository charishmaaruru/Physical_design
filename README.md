# Physical Design Implementation of SPI Using Qflow

## Project Overview
This project focuses on the physical design implementation of a **Serial Peripheral Interface (SPI)** using the open-source Qflow digital synthesis flow. It covers the process from Verilog RTL design through synthesis, placement, routing, timing analysis, physical verification, and GDSII generation.

## Internship Details
- **Organization:** Maven Silicon
- **Course:** VLSI Physical Design
- **Project:** Physical Design Implementation of SPI Using Qflow
- **Duration:** May–July 2025

## Tools and Technologies
- **Qflow** – Digital synthesis and physical design flow
- **Verilog HDL** – RTL design
- **Yosys** – RTL synthesis
- **Graywolf** – Placement
- **Qrouter** – Routing
- **OpenSTA / Vesta** – Static timing analysis
- **Magic** – Layout generation and DRC
- **Netgen** – Layout-versus-schematic (LVS) verification
- **Linux** – Design environment

## SPI Overview
Serial Peripheral Interface (SPI) is a synchronous serial communication protocol used for communication between a master and one or more slave devices. Its main signals are:

- **MOSI:** Master Out, Slave In
- **MISO:** Master In, Slave Out
- **SCK:** Serial Clock
- **SS:** Slave Select

## Physical Design Flow
1. **RTL Design:** Prepare the Verilog source files.
2. **Synthesis:** Convert RTL into a gate-level netlist using Yosys.
3. **Placement:** Arrange standard cells using Graywolf.
4. **Static Timing Analysis:** Analyze circuit timing.
5. **Routing:** Connect cells using Qrouter.
6. **DRC:** Check layout against design rules using Magic.
7. **LVS:** Verify layout connectivity using Netgen.
8. **GDSII Generation:** Export the final physical layout.

## Key Learning Outcomes
- Understood the RTL-to-GDSII physical design flow.
- Gained exposure to synthesis, placement, and routing.
- Learned the purpose of static timing analysis.
- Studied DRC and LVS verification.
- Explored open-source EDA tools in a Linux environment.

## Final Output
The project report documents the generation of a GDSII layout for the SPI design using Qflow.

## Repository Contents
- `README.md` – Project overview and documentation
- `screenshots/` – Tool and layout screenshots
- `docs/` – Project report

## Author
**Aruru Charishma**

*Academic project completed as part of VLSI Physical Design training with Maven Silicon.*
