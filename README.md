# Bitwise-operators- exp 4

Aim:
To understand and implement bitwise operators in C++ for performing operations directly on the binary representations of integers. This will include basic operations such as AND, OR, XOR, NOT, and bit shifts.

Theory:
Bitwise operators perform operations on the binary representations of integers, directly manipulating bits. The primary operators are:

AND (&): Sets each bit to 1 if both corresponding bits are 1.
OR (|): Sets each bit to 1 if at least one of the corresponding bits is 1.
XOR (^): Sets each bit to 1 if only one of the corresponding bits is 1.
NOT (~): Inverts all the bits (bitwise complement).
Left Shift (<<): Shifts the bits of the left operand to the left by the number of positions specified by the right operand.
Right Shift (>>): Shifts the bits of the left operand to the right by the number of positions specified by the right operand.
These operators are useful in tasks such as low-level programming, graphics, and systems programming where efficient manipulation of data at the bit level is crucial.

Procedure:
Include Required Headers:

cpp
Copy code
#include <iostream>
using namespace std;
Define Main Function:

cpp
Copy code
int main() {
    // Initialize variables
    unsigned int a = 12; // Binary: 00001100
    unsigned int b = 7;  // Binary: 00000111


Compile and Run:
Use a C++ compiler to compile and run the program to observe the results of the bitwise operations on the variables.

Conclusion:
Bitwise operators in C++ enable efficient manipulation of data at the bit level, providing powerful tools for low-level programming. They facilitate operations such as bitwise AND, OR, XOR, NOT, and bit shifts. Mastery of these operators is essential for performance optimization and system-level programming. The example illustrated their practical applications and effects clearly.
