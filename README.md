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

![428110069-dce1d820-c663-4ca2-96c5-bd9129a69770](https://github.com/user-attachments/assets/c1f54eca-b092-41a9-9ec0-e6816826ddc9)



## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematic of 2-Bit Multiplier:
![439800413-241052f7-c451-463e-92bd-9e2ccd1842e2](https://github.com/user-attachments/assets/ae85c977-3ac9-4a96-9fbf-f4a5d7aeb284)

![439800474-f5dce6e6-7934-49e9-bdc7-8475d90dd809](https://github.com/user-attachments/assets/34ce9dc0-cc77-4e22-a578-0962de2956f0)

![439800524-b7be0d9b-70e4-4d81-b0bc-99f29f3b60e5](https://github.com/user-attachments/assets/f133e6b7-ea7b-49ac-b734-eb9041a64124)

## Output
### Transient Analysis Output:

![439800598-0f37bb9a-7418-408c-93aa-e47760dcf713](https://github.com/user-attachments/assets/a2475928-4360-487e-bf4e-083bc315683a)


![445914347-ef3b83a5-e1a3-45f1-b565-8459b54da50d](https://github.com/user-attachments/assets/52ab3241-3d4c-4d7d-abdd-af005e11f402)


Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
