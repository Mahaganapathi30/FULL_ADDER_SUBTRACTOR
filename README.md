# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

Full Adder


![exp4a prog](https://github.com/user-attachments/assets/170e1986-cc70-487d-81a5-06032844fab3)

Full Subtractor


![exp4b prog](https://github.com/user-attachments/assets/60be2306-86a1-422d-8ebc-2380b60f3c37)



/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**

Full adder

![exp4a rlt](https://github.com/user-attachments/assets/c60926b3-b9eb-4344-aa40-888237e972c1)


Full subtractor


![exp4b rlt](https://github.com/user-attachments/assets/9684e8e5-83c1-4c2c-933a-eae4243e4d72)



**Output Timing Waveform**

Full adder

![exp4a wave](https://github.com/user-attachments/assets/de20a9fe-368e-41e3-9ac0-fe04463d2ecf)



Full subtractor


![exp4b wave](https://github.com/user-attachments/assets/116cfd6a-7199-4bd1-82eb-b744665e9a90)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



