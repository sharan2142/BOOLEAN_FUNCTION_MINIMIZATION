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
i) module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii) module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule
```
Developed by: M SHARAN KUMAR

RegisterNumber: 212225040403



**RTL realization**
<img width="903" height="473" alt="image" src="https://github.com/user-attachments/assets/a6b5ef86-85a2-463d-8f3e-54dc27e9a299" />

**Output:**

<img width="1919" height="1032" alt="image" src="https://github.com/user-attachments/assets/d943a9db-3a83-4e9e-964c-0de3ba731764" />


**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


