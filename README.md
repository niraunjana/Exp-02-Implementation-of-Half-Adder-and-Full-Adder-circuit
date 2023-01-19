# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design 
a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: NIRAUNJANA GAYATHRI G R 
RegisterNumber: 22008369 
*/
Logic symbol & Truthtable:


RTL realization

### Output:
![image](https://user-images.githubusercontent.com/119395610/212459234-70f3f073-5c1b-482e-b40c-925c410d279c.png)
![image](https://user-images.githubusercontent.com/119395610/212459254-8e4c2d08-f297-40d4-9223-249087b576ca.png)


### RTL:
![image](https://user-images.githubusercontent.com/119395610/212459278-c270a12e-a159-432d-bf87-4995e8105b5a.png)
![image](https://user-images.githubusercontent.com/119395610/212459282-5451c74c-3978-431c-994f-b458ff983028.png)


### TIMING DIAGRAM:
![image](https://user-images.githubusercontent.com/119395610/212459501-3e9184d9-dbd4-4ad1-b251-45cf1e929d40.png)![image](https://user-images.githubusercontent.com/119395610/212459529-8b91e6c9-fcd4-4d19-89e8-364eb863f7cc.png)






### TRUTH TABLE :
![truthtable half adder](https://user-images.githubusercontent.com/119395610/213471196-a490ebed-fc85-412f-9fde-2d0eccb92e83.png)



### Result:
Thus the Half Adder and Full Adder circuits are designed and the truth table is verified using the quartus software
