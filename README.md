# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
module funct1(a,b,c,d,f1);
```
F1
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

F2
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

Developed by:A.DIVIYADHARSHINI
RegisterNumber:*/24008491


**RTL**
F1
![Experiment 2 f1](https://github.com/user-attachments/assets/65a348c3-7cda-483a-8153-6e44566b6d9b)
F2
![experiment 2 funct f2](https://github.com/user-attachments/assets/a1ac9a6a-9d20-4121-b1e9-9df0f8b4540d)


**Output:**
F1

![Exp 2 f1 output](https://github.com/user-attachments/assets/cc14ef7a-ee12-443f-a218-d360ed6aedb1)
F2

![exp 2 f2 output](https://github.com/user-attachments/assets/99ade095-43c1-488d-abce-31db40e31af7)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming. 

