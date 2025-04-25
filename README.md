# Ex No: 04 - Design & Implementation of 6T SRAM Cell Using Cadence EDA Tools

## Aim
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
   - Open the Cadence Virtuoso tool and set up the working library.
   - Create a new schematic cell view for the 6T SRAM cell design.

### 2. Schematic Design:
   - Select NMOS and PMOS transistors from the library.
   - Construct the 6T SRAM cell with two cross-coupled inverters and access transistors.
   - Connect the wordline (WL), bitlines (BL, BLB), and power supply connections.

### 3. Simulation:
   - Check the design for errors and proceed with simulation.
   - Launch the Analog Design Environment (ADE).
   - Perform transient analysis to verify read and write operations.
   - Set up input stimulus and analyze the output waveform.

## Circuit Diagram

![Screenshot 2025-04-17 254336](https://github.com/user-attachments/assets/c22930fc-f396-4787-807d-51088ad7959e)


## 6T SRAM Truth Table

![Screenshot 2025-04-17 235798](https://github.com/user-attachments/assets/29a8a036-d65d-4a25-ba18-3f1f0e358576)


## Schematic Diagram

#### 1. Schematic of 6T SRAM Cell:

   ![image](https://github.com/user-attachments/assets/7989089d-6336-4b9a-84ee-2943ca579e20)



   ![image](https://github.com/user-attachments/assets/c28aea2b-9e73-48e6-abdb-11c430321b86)


## Output
#### 1. Transient Analysis Output:

   ![Screenshot 2025-04-17 124566](https://github.com/user-attachments/assets/1817d67f-ae2d-42ee-92db-2c7a9fc0dd24)


  ![Screenshot 2025-04-17 125446](https://github.com/user-attachments/assets/687c2167-bb37-4e1e-85b6-2514dbb0ef0f)



## Results:
1. Successfully designed the 6T SRAM cell schematic using Cadence EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.


