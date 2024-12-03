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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

     module funct1(a,b,c,d,f1);
     input a,b,c,d;
     output f1;
     assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
     endmodule

     module funct2(w,x,y,z,f2);
     input w,x,y,z;
     output f2;
     assign f2=((~y & z)|( w & y )|(x & y));
     endmodule

Developed by: Raagavi RM RegisterNumber: 24900010


**RTL realization**

![DE Exp 2 lg 1](https://github.com/user-attachments/assets/2bd222cb-480a-4feb-b03e-f95805792f6a)

![DE Exp 2 lg 2](https://github.com/user-attachments/assets/743b684a-1f68-4054-a22b-ef63349f20c4)

**Truth Table**

![DE Exp 2 tt 1](https://github.com/user-attachments/assets/f0824015-294b-4eea-97d2-e7d7cf417820)

![DE Exp 2 tt 2](https://github.com/user-attachments/assets/e6083c23-4585-423b-84a4-fb631a199677)

**Output:**

![DE Exp 2 wf 1](https://github.com/user-attachments/assets/43ccf6b0-2f31-4328-98d4-35cb765d48e0)

![DE Exp 2 wf 2](https://github.com/user-attachments/assets/cd0f4874-683d-4814-99c8-60248a5ab346)

**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

