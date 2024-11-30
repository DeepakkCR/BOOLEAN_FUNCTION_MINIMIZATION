# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![image](https://github.com/user-attachments/assets/16ce842c-4b02-44c7-bff2-7ac406baceff)


**Logic Diagram**


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

```
module exp2booleanfunctionminimization(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule 
```

Developed by:C.R.DEEPAKK

RegisterNumber:24007006


**RTL realization**

**Output:**

**RTL**

![image](https://github.com/user-attachments/assets/5a28e311-7196-41c5-826e-cf6cdd0f69d4)

**Timing Diagram**

![image](https://github.com/user-attachments/assets/92dc24bc-246f-49ae-a085-0264468fa873)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

