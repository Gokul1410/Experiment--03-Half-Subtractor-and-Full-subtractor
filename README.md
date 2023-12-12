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

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

Developed by:GOKUL.C

RegisterNumber:23014093  

## Half Subtractor 
![Screenshot 2023-12-12 222809](https://github.com/Gokul1410/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153058321/c3e4f006-85d4-48a8-9192-1beae670ea08)
## Full Subtractor
![Screenshot 2023-12-12 222833](https://github.com/Gokul1410/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153058321/4827707d-f65f-46cf-992b-12a5b44d4cf0)

## Output:

## Truthtable
## Half Subtractor
![Screenshot 2023-12-12 222858](https://github.com/Gokul1410/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153058321/66279a5a-7acb-47aa-b198-1b03b930e60b)
## Full Subtractor
![Screenshot 2023-12-12 222919](https://github.com/Gokul1410/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153058321/f35ac5d2-2847-4317-89d5-0fd8871f23b6)



##  RTL realization
## Half Subtractor
![Screenshot 2023-12-12 222939](https://github.com/Gokul1410/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153058321/1a2097bc-b70c-4947-8436-bb689a3b2a90)
## Full Subtractor
![Screenshot 2023-12-12 223006](https://github.com/Gokul1410/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153058321/e9af2dba-1f35-4e45-a1e2-5fcddff9e875)



## Timing diagram 
## Half Subtractor
![Screenshot 2023-12-12 223027](https://github.com/Gokul1410/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153058321/7ab172ca-bbd6-4f37-8b88-05f64ea50600)
## Full Subtractor
![Screenshot 2023-12-12 223049](https://github.com/Gokul1410/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153058321/7f667c3d-7363-493d-9d3e-5003cee9b6d6)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
