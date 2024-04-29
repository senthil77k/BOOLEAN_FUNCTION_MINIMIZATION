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
~~~
module experiment2(E,F,A,B,C,D);
output E,F;
input A,B,C,D;
assign E=A||(B&&C)||((!B)&&D);
assign F=((!B)&&C)||(B&&(!C)&&(!D));
endmodule

~~~
# Name: senthilkumaran c
# Register Number:212223220103


**Truth Table**

![WhatsApp Image 2024-04-04 at 14 56 21_aac75d60](https://github.com/Dharsanrameshkumar/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870430/2b368c66-759e-4aef-9db7-d1b2bf6746bb)


**RTL**
![WhatsApp Image 2024-04-04 at 14 06 48_dad00aa9](https://github.com/Dharsanrameshkumar/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870430/8fae5a41-dbce-4653-8a93-3ae7fefb7f77)

**Output:**
![WhatsApp Image 2024-04-04 at 14 07 01_0397bcca](https://github.com/Dharsanrameshkumar/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870430/a3cab865-f1eb-406e-8636-40ca430ddc08)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

