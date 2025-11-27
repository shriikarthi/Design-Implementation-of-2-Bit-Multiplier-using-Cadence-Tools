# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d5b3df30-1bac-4d0a-bcdf-a73ab557f7da" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7700604c-1f7e-4d89-9b10-7c99421b3811" />


### Schematicand Symbol of 2-Input EX-OR Gate:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f3319f15-54eb-4ee9-89af-380634fccd79" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9418c68f-a799-4afc-bb3b-114a5f8bad02" />


### Schematicand Symbol of Half Adder:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c0b2184d-da1b-4712-85f4-fa51c8c499d2" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/123bbaa9-74c0-415a-a46a-013893b6b36c" />


### Schematic of 2-Bit Multiplier:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cf53f174-de7f-4b5a-9a88-1ad171656252" />


## Output
### Transient Analysis Output:
![Screenshot 2025-05-15 153033](https://github.com/user-attachments/assets/2c94f184-525c-49ba-8733-27c982f0dffa)

![image](https://github.com/user-attachments/assets/55864d90-af08-4836-bc90-4cbba80573f8)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dcc8768e-edba-4dd7-b130-7948aaecf57d" />


Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
