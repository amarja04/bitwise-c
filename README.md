# bitwise-c

In the arithmetic-logic unit (which is within the CPU), mathematical operations like: addition, subtraction, multiplication and division are done in bit-level. To perform bit-level operations in C programming, bitwise operators are used.

![bitwose-ope](https://user-images.githubusercontent.com/125913981/230799134-dc3fa04b-4564-42ad-9bc7-e42ae4585898.png)



[1]   Bitwise AND Operator &

The output of bitwise AND is 1 if the corresponding bits of two operands is 1. If either bit of an operand is 0, the result of corresponding bit is evaluated to 0.

In C Programming, the bitwise AND operator is denoted by &.

Let us suppose the bitwise AND operation of two integers 12 and 25.


12 = 00001100 (In Binary)

25 = 00011001 (In Binary)

Bit Operation of 12 and 25
  00001100
  
& 00011001

  ________
  00001000  = 8 (In decimal)
  
  
  
  
  
[2]    Bitwise OR Operator |
  
The output of bitwise OR is 1 if at least one corresponding bit of two operands is 1. In C Programming, bitwise OR operator is denoted by |.

12 = 00001100 (In Binary)

25 = 00011001 (In Binary)

Bitwise OR Operation of 12 and 25

  00001100
  
| 00011001
  ________
  00011101  = 29 (In decimal)




[3]      Bitwise XOR (exclusive OR) Operator ^

The result of bitwise XOR operator is 1 if the corresponding bits of two operands are opposite. It is denoted by ^.

12 = 00001100 (In Binary)

25 = 00011001 (In Binary)


Bitwise XOR Operation of 12 and 25

  00001100
  
^ 00011001
  ________
  
  00010101  = 21 (In decimal)
  
  
  
  
[4]     Right Shift Operator
  
Right shift operator shifts all bits towards right by certain number of specified bits. It is denoted by >>.


212 = 11010100 (In binary)

212 >> 2 = 00110101 (In binary) [Right shift by two bits]

212 >> 7 = 00000001 (In binary)

212 >> 8 = 00000000 

212 >> 0 = 11010100 (No Shift)





[5]    Left Shift Operator

Left shift operator shifts all bits towards left by a certain number of specified bits. The bit positions that have been vacated by the left shift operator are filled with 0. The symbol of the left shift operator is <<.

212 = 11010100 (In binary)

212<<1 = 110101000 (In binary) [Left shift by one bit]

212<<0 = 11010100 (Shift by 0)

212<<4 = 110101000000 (In binary) =3392(In decimal)


