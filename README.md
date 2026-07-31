# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools

## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    <img width="1920" height="1077" alt="Screenshot 2026-07-24 161635" src="https://github.com/user-attachments/assets/c0aca7d5-f7d3-4d8e-afc6-8a4b5e8b0636" />

### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. CMOS Inverter:

![image](https://github.com/user-attachments/assets/e3e06487-52b2-4b56-9dcd-03c5c9394a4c)

#### 2. Schematic of CMOS Inverter:

   <img width="1600" height="896" alt="WhatsApp Image 2026-07-23 at 11 45 37" src="https://github.com/user-attachments/assets/08aee496-b2a3-454c-b01e-bc75975097f9" />

#### 3. Transient Response Setup:


<img width="1020" height="759" alt="WhatsApp Image 2026-07-23 at 11 46 33" src="https://github.com/user-attachments/assets/ecc51694-875f-4007-b088-5837c4768073" />


## Output
#### 1.Transient Analysis and DC Response Output

<img width="1600" height="899" alt="WhatsApp Image 2026-07-23 at 11 46 02" src="https://github.com/user-attachments/assets/61cbe300-1196-4db2-92b4-fdcbf065a39a" />

## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











