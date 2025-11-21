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

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
##Half-Adder
<img width="569" height="238" alt="add" src="https://github.com/user-attachments/assets/f49822c7-92c7-4aff-ad0b-2d2d0f5071fc" />

##Half-subtractor

<img width="651" height="214" alt="sub (3)" src="https://github.com/user-attachments/assets/a33f4144-b30e-4598-ab8e-fb375d204f79" />

Developed by:LAL RHIDHISHAN R, RegisterNumber:25015767*/

**RTL Schematic**

##Half-Adder
<img width="1617" height="910" alt="add (3)" src="https://github.com/user-attachments/assets/22794efa-a4b8-48b8-895c-b13155880d3e" />

##Half-subtractor
<img width="1614" height="944" alt="sub" src="https://github.com/user-attachments/assets/45f39a5b-da04-4fe4-8f9a-4d28dba3bb07" />

**Output/TIMING Waveform**

##Half-Adder
<img width="905" height="671" alt="add (2)" src="https://github.com/user-attachments/assets/acd335bb-5b34-46c4-8ec6-48377a61a10f" />

##Half-subtractor
<img width="905" height="671" alt="sub (4)" src="https://github.com/user-attachments/assets/fa8835c0-a18f-4a7c-875d-b74470c3f367" />

**Result:**
Thus the a half adder and half subtractor circuit is designed and its truth table is verified in Quartus using Verilog programming .
