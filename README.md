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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: VIKAASH P RegisterNumber:212223240180*/
```
 module EX2(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
 endmodule

module EX2(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y&z)|(w&y)|(x&y));
 endmodule

```


**RTL realization**
**RTL**


**Output:**
![image](https://github.com/user-attachments/assets/b2f291e2-22cb-4d08-bfc2-2a3ac81b87bc)

![image](https://github.com/user-attachments/assets/5c0f78b5-ff7f-46e9-bb3c-0700123249ab)


**Timing Diagram**
![image](https://github.com/user-attachments/assets/7416a170-38f0-48ec-89d3-53fcac030884)

![image](https://github.com/user-attachments/assets/1bb9d5d3-b6d6-4af4-822b-cb8c78833bd0)



**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

