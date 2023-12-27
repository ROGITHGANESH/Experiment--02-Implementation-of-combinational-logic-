# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
## Program:
```
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: Rogith Ganesh.R
RegisterNumber:212223100046

module ex_02(a,b,c,d,f1);
input a,b,c,d;
output f1;
wire x1,x2,x3,x4,x5;
assign x1=(~a)&(~b)&(~c)&(~d);
assign x2=(a)&(~c)&(~d);
assign x3=(~b)&(c)&(~d);
assign x4=(~a)&(b)&(c)&(d);
assign x5=(b)&(~c)&(d);
assign f1=x1|x2|x3|x4|x5;
endmodule
```
## RTL realization
![image](https://github.com/ROGITHGANESH/Experiment--02-Implementation-of-combinational-logic-/assets/152588322/c31a049a-3819-4d6c-a210-7e47617e3165)
## TRUTH TABLE 
![image](https://github.com/ROGITHGANESH/Experiment--02-Implementation-of-combinational-logic-/assets/152588322/476b86d9-3f27-46c6-bf62-3ffca770caea)
## Timing Diagram
![image](https://github.com/ROGITHGANESH/Experiment--02-Implementation-of-combinational-logic-/assets/152588322/9c8997f5-e98a-4fa0-afc7-76c0ef6c8d0c)
## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
