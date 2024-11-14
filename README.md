# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![Screenshot 2024-10-28 142451](https://github.com/user-attachments/assets/614c3d98-2985-4c95-8e72-2fdd5b4f2f7b)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
Developed by:HARISH KUMAR S
RegisterNumber:24010415

module ex_2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
```
**RTL realization**
![expl1](https://github.com/user-attachments/assets/19ac9755-0f24-43dc-a222-6218fcd2bea4)


**Timing Diagram**
![WhatsApp Image 2024-10-28 at 14 45 15_2419bb71](https://github.com/user-attachments/assets/b6e27711-7c48-481e-a6ec-4f98340e7696)
**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

