# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

```
/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by:Aadithya.R RegisterNumber:212223240001*/
```
## CODE:
### HALF ADDER:
![Screenshot 2024-03-23 232746](https://github.com/Aadithya2201/HALF_ADDER_SUBTRACTOR/assets/145917810/53f78446-1982-43fd-8168-dd9f115ca3e6)

### HALF SUBTRACTOR:
![Screenshot 2024-03-23 232801](https://github.com/Aadithya2201/HALF_ADDER_SUBTRACTOR/assets/145917810/50f3b976-beaf-4a7b-8ee8-82ba0a1cc90d)

**RTL Schematic**
### HALF ADDER:
![Screenshot 2024-03-23 232817](https://github.com/Aadithya2201/HALF_ADDER_SUBTRACTOR/assets/145917810/cf71bd7d-edb7-4c7f-8993-6e3142076e60)

### HALF SUBTRACTOR:
![Screenshot 2024-03-23 232838](https://github.com/Aadithya2201/HALF_ADDER_SUBTRACTOR/assets/145917810/21ca84cc-537d-48e3-9ba3-a53976a0765d)

**Output/TIMING Waveform**
### HALF ADDER:
![Screenshot 2024-03-23 232859](https://github.com/Aadithya2201/HALF_ADDER_SUBTRACTOR/assets/145917810/440aced0-44b6-4234-be48-704ea16c8a71)

### HALF SUBTRACTOR:
![Screenshot 2024-03-23 232911](https://github.com/Aadithya2201/HALF_ADDER_SUBTRACTOR/assets/145917810/9f40aa3c-409c-4b37-b803-60db746d3a46)

## Result:
Thus, a half adder and half subtractor circuit is designed to verify its truth table in Quartus using Verilog programming.
