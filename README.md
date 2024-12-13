NAME: DAKSHA C

REF NO: 24006768

**EXPERIMENT NO: 3 # HALF_ADDER_SUBTRACTOR**

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**EQUIPMENTS REQUIRED:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**HALF ADDER:**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**HALF SUBRACTOR**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**TRUTHTABLE:**

![2](https://github.com/user-attachments/assets/69c53e11-a9ba-4bc4-9669-3b14ff09f1af)


**PROCEDURE:**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM:**

![Screenshot 2024-12-13 111854](https://github.com/user-attachments/assets/4374c2ab-76c9-4dc9-a7a0-74dbb1d8a69d)

![3](https://github.com/user-attachments/assets/adadfeee-87f9-49e0-8d87-a0a2db260531)


**RTL SCHEMATIC:**

**Output/TIMING Waveform Half_adder** 

![4](https://github.com/user-attachments/assets/dcadfe86-501c-43ae-b63d-d86736322ebb)

**Half_subractor**

![5](https://github.com/user-attachments/assets/5f68271a-5380-4064-907e-1f48379be755)

**RESULT:**

 Thus the given logic functions are implemented using and their operations are verified using
 Verilog programming.
