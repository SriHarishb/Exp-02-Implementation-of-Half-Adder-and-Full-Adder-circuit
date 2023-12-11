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
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by : Sri Harish B
RegisterNumber:  23001744
## Code:
HALF ADDER:![Exp3 ha code](https://github.com/SriHarishb/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150308442/3fd5c5fe-5115-4870-911b-c5743bdff62a)

FULL ADDER:![Exp3 fa code](https://github.com/SriHarishb/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150308442/eba91a34-ab59-4e0d-8e57-3c789cdd186b)



### TRUTH TABLE:
HALF ADDER:![Exp3 truthtable (ha)](https://github.com/SriHarishb/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150308442/cd5e10a9-9dee-4aa6-9121-0b4c329db63b)

FULL ADDER:![Exp3 truthtable (fa)](https://github.com/SriHarishb/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150308442/a2334434-3633-43f5-871f-311108afa2cf)


## Output:
## RTL:
HALF ADDER:![Exp3 ha RTL diagram](https://github.com/SriHarishb/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150308442/37c2adfd-830d-419d-bba1-0ee7ba8dc7ac)

FULL ADDER:![Exp3 fa RTL diagram](https://github.com/SriHarishb/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150308442/904ed997-3471-4dde-9be9-52f764639f9c)


## TIMING DIAGRAM:
HALF ADDER:![exp3 ha wave](https://github.com/SriHarishb/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150308442/61a21f72-3c30-42c1-a942-e624185aa3ca)

FULL ADDER:![exp 3 fa wave](https://github.com/SriHarishb/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150308442/2e29b743-66d0-4f1a-8ad7-50b4c715e555)


## TRUTH TABLE:
HALF ADDER:![Exp3 truthtable (ha)](https://github.com/SriHarishb/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150308442/4cd47041-51a2-4cf8-9f95-50d145d8b0a4)

FULL ADDER:![Exp3 truthtable (fa)](https://github.com/SriHarishb/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150308442/68056405-27f0-44b0-a938-a521df95743e)


### Result:

Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
 programming.
