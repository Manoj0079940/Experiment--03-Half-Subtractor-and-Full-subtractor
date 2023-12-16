# Experiment--03-Half-Subtractor-and-Full-subtractor
## Name: Manoj M
## Register Number: 23004560

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
1.Use module projname(input,output) to start the Verilog programmming.

2.Assign inputs and outputs using the word input and output respectively.

3.Use defined keywords like wire,assign and required logic gates to represent the boolean expression.

4.Use each output to represnt onre for differnce and the other for borrow.

5.End the verilog program using keyword endmodule
## Program:

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: Manoj M
RegisterNumber: 23004560

## Half Subracter
![image](https://github.com/Manoj0079940/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149366208/5838dddf-498c-498e-8714-323739fe7654)

## Full Subracter
![image](https://github.com/Manoj0079940/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149366208/1e743874-99d7-49c7-ab9e-be78118ee756)

## Truthtable
## Half Subracter
![image](https://github.com/Manoj0079940/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149366208/9a507d36-2d8e-4ca8-b2e1-75e672c5a12e)

## Full Subracter
![image](https://github.com/Manoj0079940/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149366208/bca95d29-d875-4427-865e-46a4d0d6dd69)


##  RTL realization
## Half Subracter
![image](https://github.com/Manoj0079940/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149366208/fba0c703-e9cf-43de-9c11-65f273fd1a12)

## Full Subracter
![image](https://github.com/Manoj0079940/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149366208/fba18cd4-e3b1-4576-93f7-e5466e31cfa4)


## Timing diagram 
## Half Subracter
![image](https://github.com/Manoj0079940/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149366208/8670c1a9-7ef7-44ab-9cf2-3b930eb2134c)

## Full Subracter
![image](https://github.com/Manoj0079940/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149366208/8dc2a9ff-788a-4a31-92b6-6bf7e84f63e3)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
