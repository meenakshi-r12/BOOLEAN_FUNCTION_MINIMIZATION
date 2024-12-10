# Exp no:

# Date:

# BOOLEAN_FUNCTION_MINIMIZATION

# AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

# Equipment Required:

Hardware – PCs, Cyclone II , USB flasher

# Software – Quartus prime

# Theory

# Logic Diagram

# Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


# Program:

# Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

(i)module funct1(a,b,c,d,f1);
  
  input a,b,c,d;
  
  output f1;
  
  assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
  
  end module

(ii)module funct2(w,x,y,z,f2);
    
   input w,x,y,z;
    
   output f2;
    
   assign f2=((~y&z)|(w&y)|(x&y));
    
   end module
   

Developed by:Meenakshi.R RegisterNumber:24003710

# TRUTH TABLE

![WhatsApp Image 2024-12-08 at 14 50 00_6f4f4aba](https://github.com/user-attachments/assets/4ea8c8ad-ec8f-4ded-b7bf-ff14700c7202)


# Output:

# RTL

![exp2 2](https://github.com/user-attachments/assets/a48e8244-cf8f-4dc7-b094-17377715c39a)

# Timing Diagram

![exp2 3](https://github.com/user-attachments/assets/dc734d6d-8857-4c00-ac36-0bbaaa13ba90)

# Result


Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

