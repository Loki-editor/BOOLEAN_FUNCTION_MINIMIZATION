# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![WhatsApp Image 2024-12-03 at 20 05 34_c34c3cf8](https://github.com/user-attachments/assets/746f65f6-45ab-4cab-ae8b-11380dda5e1d)


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module boolean (f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor,a,b);
input a,b;
output f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor;
and (f_and,a,b);
or (f_or,a,b);
not (f_not,a);
nor (f_nor,a,b);
nand (f_nand,a,b);
xor (f_xor,a,b);
xnor (f_xnor,a,b);
endmodule

```
 

Developed by: LOKESH S

RegisterNumber: 24009455



**RTL**

![Screenshot (11)](https://github.com/user-attachments/assets/45de8fa9-0b10-4c01-82b4-4919f1b47a07)


**Timing Diagram**

![Screenshot (12)](https://github.com/user-attachments/assets/e1cdafe3-beaf-4f29-9804-960da20f063d)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

