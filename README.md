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

HALF ADDER

![half adder](https://github.com/user-attachments/assets/f5a96e0e-4c74-4f6b-b70b-60cff74a6132)


HALF SUBTRACTOR

![half-subtractor2](https://github.com/user-attachments/assets/99aa440c-5126-41bf-bb46-26391250210f)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber: 24009014
**RTL Schematic**

RTL SCHEMATIC FOR HALF ADDER

![Screenshot 2024-11-12 051740](https://github.com/user-attachments/assets/a0e92d95-38ed-4164-a77e-83b72505b437)


RTL SCHEMATIC FOR HALF SUBTRACTOR

![Screenshot 2024-11-19 032008](https://github.com/user-attachments/assets/b191aa50-7c7e-4bd1-803c-62e2b182feb2)


**Output/TIMING Waveform**

TIMING FOR HALF ADDER

![Screenshot 2024-11-12 054159](https://github.com/user-attachments/assets/092ac5af-4ce9-494a-a753-29d9da9021fe)


TIMING WAVEFORM FOR HALF SUBTRACTOR

![Screenshot 2024-11-19 032123](https://github.com/user-attachments/assets/de2dd8da-02ac-45fb-945b-defd401873df)


**Result:**
Thus the truth table of logic gates in Quartus || using Verilog programming are 
studied, verified and executed successfully.
