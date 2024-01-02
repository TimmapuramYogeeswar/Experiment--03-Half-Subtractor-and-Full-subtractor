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

![image](https://github.com/TimmapuramYogeeswar/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154494746/e26b63f1-053f-4fae-8534-5ff6cdd977b9)

Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![image](https://github.com/TimmapuramYogeeswar/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154494746/b914e851-833c-4193-90c0-1c271b0f062c)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
![Screenshot 2023-11-26 163847](https://github.com/TimmapuramYogeeswar/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154494746/4e08758f-4ced-4c79-a20f-6e17cd05ae97)
![Screenshot 2023-11-26 150019](https://github.com/TimmapuramYogeeswar/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154494746/0f9d37bf-6574-435d-9c35-e191fabbea97)

Developed by: 
RegisterNumber:  
*/

## Output:

## Truthtable

![image](https://github.com/TimmapuramYogeeswar/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154494746/bbb8fd27-2734-4528-aaab-3d91ebae0f21)
![image](https://github.com/TimmapuramYogeeswar/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154494746/9728d63f-6454-4102-8eec-42f49366ea5f)


##  RTL realization


## Timing diagram 
![image](https://github.com/TimmapuramYogeeswar/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154494746/1ed995b7-ba82-482d-bed3-16c6c4da3c64)
![image](https://github.com/TimmapuramYogeeswar/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154494746/158df922-6349-4140-9841-57ff399292f3)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
