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
 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
Developed by:GOKUL V E
RegisterNumber:24002047
```
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```

**RTL realization**
![1 EX 2](https://github.com/user-attachments/assets/f54dd596-0829-414a-bc6e-4ba62f9c8744)


**Output:**
![2 EX2](https://github.com/user-attachments/assets/6e9a497d-0c78-45ca-87a1-ff1677f7a719)

**RTL**
![3 EX 2](https://github.com/user-attachments/assets/d7448f14-67bd-478b-ab11-f9e94618395b)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

