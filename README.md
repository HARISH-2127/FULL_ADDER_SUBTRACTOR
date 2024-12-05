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

FULL ADDER

![Screenshot 2024-12-05 200737](https://github.com/user-attachments/assets/72df5678-8c37-4039-9fca-764f38ed3070)

FULL SUBTRACTOR

![Screenshot 2024-12-05 201054](https://github.com/user-attachments/assets/bdd6edd5-d580-4811-aa47-a2503ed93a3b)


Developed by: **RegisterNumber**: HARISH 24900739

**RTL Schematic**

FULL ADDER

![Screenshot 2024-12-05 201214](https://github.com/user-attachments/assets/f05bc66b-bcf3-4878-9aa9-e01f69db5608)


FULL SUBTRACTOR

![Screenshot 2024-12-05 201248](https://github.com/user-attachments/assets/d2b3b144-a690-456b-beff-2c38780332e0)



**Output Timing Waveform**

FULL ADDER

![Screenshot 2024-12-05 201808](https://github.com/user-attachments/assets/65a005cd-2686-411f-97e0-a36f9ab6b294)


FULL SUBTRACTOR

![Screenshot 2024-12-05 201725](https://github.com/user-attachments/assets/58071f6b-347a-453c-8b47-0e629a1941ef)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



