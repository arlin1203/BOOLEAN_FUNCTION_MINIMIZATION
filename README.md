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
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
module EXP2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1 = ~b&~d | a&b&~c | ~a&b&d;
assign f2 = ~y&z | x&y | w&y;
endmodule
Developed by: R.ARLIN REJ
RegisterNumber:
212225040027*/

```

**RTL**
<img width="1624" height="874" alt="Screenshot 2026-03-12 110502" src="https://github.com/user-attachments/assets/05b6bcf3-0dc2-4c0b-98b6-93b2424fd7ce" />

**RTL realization**
<img width="1453" height="972" alt="Screenshot 2026-03-12 110517" src="https://github.com/user-attachments/assets/4ae094ae-1921-44a2-9a7f-f96692503d0a" />





**Timing Diagram**
<img width="1354" height="895" alt="Screenshot 2026-03-12 110544" src="https://github.com/user-attachments/assets/efdd9e3f-2094-4fbe-9b64-73411e2c8f60" />
**Output:**
<img width="1626" height="967" alt="Screenshot 2026-03-12 110531" src="https://github.com/user-attachments/assets/6aa15b8e-be24-4df8-a226-40f011037c0a" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

