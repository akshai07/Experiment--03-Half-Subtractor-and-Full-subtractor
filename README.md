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

![Screenshot 2023-12-24 132704](https://github.com/akshai07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152007451/f36d11cb-e841-44bf-b1b3-2c860c1ebb62)



Write the detailed procedure here 


## Program:

##Half subtractor

![Screenshot 2023-12-24 132710](https://github.com/akshai07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152007451/9d9ca474-3706-482c-b5d6-05b037bcda34)

##Full subtractor

![Screenshot 2023-12-24 132716](https://github.com/akshai07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152007451/a6e7ca78-4390-46ac-964e-92ee481ce2fb)

/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:Akshai Khanna-D 
RegisterNumber: 23014144
*/

## Output:

##  RTL realization

##Half subtractor

![Screenshot 2023-12-24 132721](https://github.com/akshai07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152007451/b8bd8cc5-74e6-41d7-990f-3e9a12402c33)
##Full subtractor

![Screenshot 2023-12-24 132726](https://github.com/akshai07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152007451/c92b3621-c10e-4699-97da-3e57d4847955)


## Truthtable

##Half subtractor

![Screenshot 2023-12-24 132733](https://github.com/akshai07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152007451/7c87643a-1fc2-4c03-bdf9-0d762b3c7794)


##Full subtractor

![Screenshot 2023-12-24 132740](https://github.com/akshai07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152007451/641c1bee-bbcf-4f36-9b6d-14ff36ff913c)

## Timing diagram

##Half substractor

![Screenshot 2023-12-24 132746](https://github.com/akshai07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152007451/7051aafe-fe48-46d5-8e5e-6fcb97468c8e)

##Full subtractor

![Screenshot 2023-12-24 132802](https://github.com/akshai07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152007451/15023609-e354-455c-a4a2-72e1d9b5365f)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
