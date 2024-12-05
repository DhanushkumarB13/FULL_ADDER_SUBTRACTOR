### NAME: B. DHANUSH KUMAR
### REG NO: 24900615
### EXP 4- FULL_ADDER_SUBTRACTOR

# AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

# Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

# Full Adder and Full Subtractor

# Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![ae4aa81f-0f34-4490-88be-e163e1c30dba](https://github.com/user-attachments/assets/d3362742-6daa-47e4-b8bf-65dc05c28186)

# Figure -1 FULL ADDER

# Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![1adc2330-6e0e-4fba-a646-ca00ccecee02](https://github.com/user-attachments/assets/0c57a816-0c69-4e68-a76e-f710a0e8f42b)



Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

# Truthtable

# Procedure

Write the detailed procedure here

# Program:


# RTL Schematic:

# Output Timing Waveform:

# Result:

Designed a full adder and full subtractor circuit and verified its truth table in quartus using verilog programming.



