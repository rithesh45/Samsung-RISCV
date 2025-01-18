# Decoding RISC-V Instructions: A Visual Guide


---

#### Instruction Types and Fields
RISC-V instructions are categorized as:
- **R-type**: Register type
- **I-type**: Immediate type
- **S-type**: Store type
- **B-type**: Branch type
- **U-type**: Upper immediate type
- **J-type**: Jump type

#### Opcode and Function Fields
- **Opcode**: Determines the type of instruction.
- **func3 and func7**: Specify operations within an instruction type.
----
### R type
![Alt text](Snapshots/r.png)
- **Opcode**: Specifies the operation (e.g., 0110011 means it's for register-register operations).
- **rd**: The destination register where the result will be stored.
- **funct3**: It helps to narrow down the operation within the R-Type family (like addition or subtraction).
- **rs1**: The first source register.
- **rs2**: The second source register.
- **funct7**: Further helps specify the operation.
Similar to all the other types
### I type 
![Alt text](Snapshots/i.png)
### S Type
![Alt text](Snapshots/s.png
### B type 
![Alt text](Snapshots/r.png)
