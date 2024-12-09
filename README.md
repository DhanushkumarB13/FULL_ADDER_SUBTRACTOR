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
![Screenshot 2024-12-09 133755](https://github.com/user-attachments/assets/d9985ad6-8490-4bad-8e0e-5a87e09deb74)


![Screenshot 2024-12-09 133810](https://github.com/user-attachments/assets/4ea431af-8c66-4621-bab7-2b1e24a2985e)

# Procedure

 Full Adder:
 1.Open Quartus II and create a new project. 
 2. Use schematic design entry to draw the full adder circuit. 
 3. The circuit consists of XOR, AND, and OR gates. 
 4. Compile the design, verify its functionality through simulation. 
 5. Implement the design on the target device and program it.
 
 Full Subtractor:
 1. Follow the same steps as for the full adder.
 2. Draw the full subtractor circuit using schematic design.
 3. The circuit includes XOR, AND, OR gates to perform subtraction.
 4. Compile, simulate, implement, and program the design similarly to the full adder.

# Program:

full adder
![Screenshot 2024-12-09 134334](https://github.com/user-attachments/assets/eecd8ec7-660d-45e1-8c2d-142a8591697f)


full subtractor
![Screenshot 2024-12-09 134344](https://github.com/user-attachments/assets/eac9e1a9-4b10-42a2-b23d-df5803265cea)


# RTL Schematic:

full adder
![Screenshot 2024-12-09 134451](https://github.com/user-attachments/assets/dbb52dea-88b7-440c-aa95-654dfbe41182)

full subtractor
![Screenshot 2024-12-09 134501](https://github.com/user-attachments/assets/a7681bdf-bc65-4dfb-87f8-1cc70bd2f469)

# Output Timing Waveform:

full adder
![Screenshot 2024-12-09 134556](https://github.com/user-attachments/assets/4a95332f-6a60-4020-8fce-9fabb0d33333)

full subtractor
![Screenshot 2024-12-09 134608](https://github.com/user-attachments/assets/7f4d5f65-dee4-4f8c-9aa2-5a12691d1208)


# Result:

Designed a full adder and full subtractor circuit and verified its truth table in quartus using verilog programming.



