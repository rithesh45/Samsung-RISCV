# **Three Bit Calculator**
---
## Overview
This project involves the implementation of a calculator that performs Addition, Subtraction, OR, and AND operations using the VSDSquadron Mini, a RISC-V-based SoC development kit. This project showcases the practical application of digital logic, GPIO operations, and RISC-V programming. Push-button switches are used to input binary data and select operations, and the results are displayed using LEDs.

---
## Components Required
- VSDSquadron Mini Board: RISC-V-based development kit.
- Push Buttons (7):
3 for binary inputs of A (A2, A1, A0).
3 for binary inputs of B (B2, B1, B0).
1 for operation selection.
- 5 LEDs:
3 for the Result (Sum/Difference/OR/AND for bits R2, R1, R0).
2 for Carry/Borrow (C2, C1).
- Resistors (330Ω): To protect LEDs.
- Breadboard: For easy prototyping.
- Jumper Wires: For circuit connections.
- VS Code with PlatformIO: For writing and uploading code.


---
## Logical Expressions and Truth Table
Addition:

| **Input A** | **Input B** | **Sum (Result LED)** | **Carry (LED)** |
|-------------|-------------|----------------------|-----------------|
| 0           | 0           | 0                    | 0               |
| 0           | 1           | 1                    | 0               |
| 1           | 0           | 1                    | 0               |
| 1           | 1           | 0                    | 1               |


Subtraction:

| **Input A** | **Input B** | **Difference (Result LED)** | **Borrow (LED)** |
|-------------|-------------|----------------------------|------------------|
| 0           | 0           | 0                          | 0                |
| 0           | 1           | 1                          | 1                |
| 1           | 0           | 1                          | 0                |
| 1           | 1           | 0                          | 0                |

OR: Result = A OR B
| **Input A** | **Input B** | **OR Result (LED)** |
|-------------|-------------|---------------------|
| 0           | 0           | 0                   |
| 0           | 1           | 1                   |
| 1           | 0           | 1                   |
| 1           | 1           | 1                   |


AND: Result = A AND B
| **Input A** | **Input B** | **AND Result (LED)** |
|-------------|-------------|----------------------|
| 0           | 0           | 0                    |
| 0           | 1           | 0                    |
| 1           | 0           | 0                    |
| 1           | 1           | 1                    |



---


---
