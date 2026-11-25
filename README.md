## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:** |M.Hema | **Reg. No.:** |26018380 |
|---|---|---|---|
| **Date:** |25/11/2026 | **Batch / Section:** | 26ODJ121 |

---

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Component | Range / Rating | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Resistor | 1 kΩ | 3 |
| 2 | DC Voltmeter | 0–30 V | 3 |
| 3 | DC Ammeter | 0–0.2 A | 3 |
| 4 | Breadboard | — | 1 |
| 5 | Regulated Power Supply (RPS) | 0–30 V | 1 |
| 6 | Connecting wires | As required | As required |
| 7 | Simulation software | Proteus Design Suite | 1 |

## THEORY

**Kirchhoff's Voltage Law (KVL):** The algebraic sum of all voltage rises and voltage drops around any closed loop in an electrical circuit is zero.

**Kirchhoff's Current Law (KCL):** The algebraic sum of currents at any node is zero. In other words, the total current entering a node is equal to the total current leaving the node.

## PROCEDURE

### A. Verification of KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Ensure that the RPS output is set to zero volts before switching it on.
3. Check that all meters are correctly connected and set to their zero positions.
4. Switch on the RPS and gradually set the required input voltage within the specified range.
5. Measure and record the voltage across each resistor using the voltmeters.
6. Repeat the measurements for different input-voltage values and tabulate the readings.

### B. Verification of KCL

7. Connect the circuit as shown in the KCL circuit diagram.
8. Ensure that the RPS output is set to zero volts before switching it on.
9. Check that all meters are correctly connected and set to their zero positions.
10. Switch on the RPS and gradually set the required input voltage within the specified range.
11. Measure and record the current in each branch using the ammeters.
12. Repeat the measurements for different input-voltage values and tabulate the readings.

## CIRCUIT DIAGRAMS

### A. KVL circuit diagram

<img width="1280" height="1165" alt="WhatsApp Image 2026-11-25 at 12 27 14 PM" src="https://github.com/user-attachments/assets/b4916bc3-1d0e-46cd-84bb-8889b75e8c84" />


**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="1280" height="1208" alt="WhatsApp Image 2026-11-25 at 12 28 46 PM" src="https://github.com/user-attachments/assets/4b789609-8a89-4835-85d6-b67f8b1dedd8" />


**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

<img width="1913" height="1017" alt="Screenshot 2026-11-12 174442" src="https://github.com/user-attachments/assets/fb49cfd6-fc7d-4ffc-aa1d-ae60ed9aee67" />



**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="1908" height="1008" alt="Screenshot 2026-11-12 174529" src="https://github.com/user-attachments/assets/e8d1720f-5832-47d9-ac16-37b94e095c27" />


**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

<img width="332" height="156" alt="Screenshot 2026-11-13 182640" src="https://github.com/user-attachments/assets/bc590bda-1dfe-4bee-86a3-9302c51a0894" />


### B. KCL – Current measurements

<img width="337" height="160" alt="Screenshot 2026-11-13 182650" src="https://github.com/user-attachments/assets/2b2a3054-a9f9-4c7d-b4ea-6a7a32f68ebf" />

## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

<img width="1592" height="1022" alt="image" src="https://github.com/user-attachments/assets/2b641487-8695-4ab5-9cf4-0f97b593cb69" />

<img width="1600" height="816" alt="image" src="https://github.com/user-attachments/assets/3492a29b-9378-424d-b4a8-d9616656513e" />


**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="1560" height="1038" alt="image" src="https://github.com/user-attachments/assets/2f184103-7920-410d-852d-6b5d5512edf5" />

<img width="1552" height="1138" alt="image" src="https://github.com/user-attachments/assets/b5f99fc0-0cfa-4273-9ced-f6639aa7d50d" />


**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
