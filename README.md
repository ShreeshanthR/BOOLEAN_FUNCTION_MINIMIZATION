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


Program:F(A,B,C,D)=AB+CD+AD
```
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
Developed by: Shreeshnth R RegisterNumber: 25012265*/

**RTL realization**

**Output:**
![517694590-19cdbf9d-aeea-40c7-967f-ca6e3dbba08d](https://github.com/user-attachments/assets/77be57d6-aecd-4e2d-abf2-f4fd82c8964c)

**RTL**

**Timing Diagram**
![517694606-c0c0f5bb-8117-405d-895f-2a68c46e22cb](https://github.com/user-attachments/assets/4d78f94e-eec4-4258-aa85-ea0bcd694b7d)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

