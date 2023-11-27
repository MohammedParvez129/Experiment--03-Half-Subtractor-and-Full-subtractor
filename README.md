![Exp4 hs RTL diagram](https://github.com/MohammedParvez129/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/143175737/39a55573-8dce-428b-ae06-994bd41980c9)# Experiment--03-Half-Subtractor-and-Full-subtractor
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

1. Connect the supply (+5V) to the circuit.
2. Switch ON the main switch.
3. If the output is 1, then the led glows.

## Program:

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

Developed by : MOHAMMED PARVEZ S

Register Number : 23010483

Code : 

Half Subtractor :

![Exp4 hs code](https://github.com/MohammedParvez129/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/143175737/e8df54e8-e172-4051-b56b-962b44cffab2)

Full Subtractor :

![Exp4 fs code](https://github.com/MohammedParvez129/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/143175737/d9a041a8-cec5-4c61-9f86-fee233e5f8fb)

Truth Table :

Half Subtractor :

![267699989-78af586e-1adf-4892-9544-04c5bfe2d3ca](https://github.com/MohammedParvez129/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/143175737/be64f2e0-0e5c-47f8-99a4-4be4d0588245)

Full Subtractor :

![267700583-a9b18974-158f-4ff9-8fc8-4d568fbf95f9](https://github.com/MohammedParvez129/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/143175737/2c0d4cd3-c688-433f-9f14-4afea55203a8)

RTL realization :

Half Subtractor :

![Exp4 hs RTL diagram](https://github.com/MohammedParvez129/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/143175737/692c1eec-b0ae-46a5-ac75-af015d4284fe)

Full Subtractor :

![Exp4 fs RTL diagram](https://github.com/MohammedParvez129/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/143175737/acfd946b-0262-41fa-9b07-4a36cff84b05)

## Output:

Half Subtractor :

![267701235-9a4af079-d35e-43e5-8690-9d390d041fb6](https://github.com/MohammedParvez129/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/143175737/e2bdb2be-5ce4-4083-85fe-321c0161ce26)

Full Subtractor :

![267701298-5ea55e95-6c55-44f9-a5f8-938858e6876f](https://github.com/MohammedParvez129/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/143175737/d83182fb-00e3-460e-8a2c-bab818f5f219)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
