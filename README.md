# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

## Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
## Developed by:VIJIYALAKSHMI A
## RegisterNumber:25017569 

```
F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule

```
**RTL realization**

<img width="1061" height="545" alt="Screenshot 2025-11-22 090817" src="https://github.com/user-attachments/assets/71b1c6d2-f431-432d-8a58-64c836118d71" />

**Output:**

**RTL**

<img width="1070" height="507" alt="Screenshot 2025-11-22 090856" src="https://github.com/user-attachments/assets/357cc54a-4f98-4795-ab1f-1bcc8c6106bb" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

