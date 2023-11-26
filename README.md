# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: RAKSHITHA P

RegisterNumber: 23003502


Code:

Half Subtractor:

![Exp4 hs code](https://github.com/rakshithaprakashkumar11/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150994181/c47e62a2-6ca3-4212-87b5-22440dea9448)

Full Subtractor:

![Exp4 fs code](https://github.com/rakshithaprakashkumar11/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150994181/efca4f11-06f0-41b9-91bb-7fa1203f2093)

Truth Table:

Full  Subtractor:

![Exp4 truthtable fs](https://github.com/rakshithaprakashkumar11/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150994181/cc123107-1103-4af2-963b-43cf660f2670)

Half Subtractor:

![Exp4 truthtable hs](https://github.com/rakshithaprakashkumar11/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150994181/2957a519-d3be-4f9b-a317-c8158c611b46)

RTL Diagram:

Full Subtractor:

![Exp4 fs RTL diagram](https://github.com/rakshithaprakashkumar11/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150994181/be02dddf-530b-4108-85e5-ff79a75e3301)

Half Subtractor:

![Exp4 hs RTL diagram](https://github.com/rakshithaprakashkumar11/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150994181/8a6c954b-d7d6-4666-8ec2-2cb2c3c311c2)

Output:

Half Subtractor:

![Exp3 hs wave](https://github.com/rakshithaprakashkumar11/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150994181/f2e30c13-11a7-474d-b1f9-d19a76b67104)

Full Subtractor:

![Exp3 fs wave](https://github.com/rakshithaprakashkumar11/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150994181/de069742-7d22-4f63-9fa1-5b84b242e0fc)





## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
