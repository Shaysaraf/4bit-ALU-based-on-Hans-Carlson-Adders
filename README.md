# 4bit-ALU-based-on-Hans-Carlson-Adders
Verilog design of a 4-bit Arithmetic Logic Unit (ALU) using Hans-Carlson adders for operands represented in two's complement form.
The ALU performs as following:
inputs: clk, [3:0] A, [3:0] B, [3:0] C.    
outputs: [4:0] X, [5:0] Y.     
functionality: X = A + B, Y = X - C

The ALU uses 2 HCA, one of 4 bits (for calculating X) and one of 5 bits (for calculating Y)


