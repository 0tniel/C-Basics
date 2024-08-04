# C-Basics

This repository is a collection of basic programming examples aimed at beginners. It includes simple implementations of the classic "Hello, World!" program and calculator.

<br>
<p align="center">
<strong>Experiment No 1A</strong>
</p>

## Aim

To print "Hello, World!" in C++.

## Software Used

- Dev C++

## Theory

C++ is a high-level, general-purpose programming language designed for system and application programming. It was developed by Bjarne Stroustrup at Bell Labs in 1983 as an extension of the C programming language. C++ is an object-oriented, multi-paradigm language that supports procedural, functional, and generic programming styles.
<br>
In the "Hello, World!" program, the cout function from the iostream library is used to print output to the console. The iostream library is part of the C++ Standard Library, providing essential functionalities for handling input and output operations. By including using namespace std;, the program avoids the necessity of prefixing standard library names with std::, thereby simplifying the code and enhancing readability.
<br>
## Algorithm
Step 1: Start
<br>
Step 2: Display Hello World
<br>
Step 3: Stop
<br>
## Program Code

```cpp
// HelloWorld.cpp
// Otniel Jhirad
// ENTC A3
// 23070123069

#include <iostream>
using namespace std;

int main() 
{
    cout << "Hello, World!" << endl; 
    return 0;
}
```
## Output
![Screenshot 2024-08-03 202918](https://github.com/user-attachments/assets/ee0014fc-b0c4-480e-a204-00baa2787b46)

<br>
<strong>Conclusion</strong>
<br>
Hence, we learned how to print text in C++ using the cout function.
<br>
<br>
<p align="center">
<strong>Experiment No 1B</strong>
</p>

## Aim

To make a basic calculator in C++.

## Software Used

- Dev C++

## Theory
The Calculator Program is a basic C++ application that performs four essential arithmetic operations: addition, subtraction, multiplication, and division. This program helps you understand how to use user input, perform calculations, and display results.
<br>
<strong align="left">Arithmetic Operations</strong>
Arithmetic Operators in C++ are used to perform arithmetic or mathematical operations on the operands. For example, ‘+’ is used for addition, ‘–‘ is used for subtraction,  ‘*’ is used for multiplication, etc. In simple terms, arithmetic operators are used to perform arithmetic operations on variables and data; they follow the same relationship between an operator and an operand.
<br>
<br>
## Algorithm
Step 1: Start
<br>
Step 2: Declare two variables: num1 and num2
<br>
Step 3: Read the first number (num1) from the user
<br>
Step 4: Read the second number (num2) from the user
<br>
Step 5: Display the value of the num1+num2
<br>
Step 6: Display the value of the num1-num2
<br>
Step 7: Display the value of the num1/num2
<br>
Step 8: Display the value of the num1*num2
<br>
Step 9: End
<br>
<br>
## Program Code
```cpp
// Name - Otniel Jhirad
// PRN - 23070123069

#include <iostream>
using namespace std;

int main() {
    float num1, num2;
    cout << "Please enter the first number: ";
    cin >> num1;
    cout << "Please enter the second number: ";
    cin >> num2;
    cout << "The sum of " << num1 << " and " << num2 << " is: " << num1 + num2 << "\n";
    cout << "The difference when subtracting " << num2 << " from " << num1 << " is: " << num1 - num2 << "\n";
    cout << "The result of dividing " << num1 << " by " << num2 << " is: " << num1 / num2 << "\n";
    cout << "The product of " << num1 << " and " << num2 << " is: " << num1 * num2 << "\n";

    return 0;
}
```

## Output
![Screenshot 2024-08-03 202801](https://github.com/user-attachments/assets/51bf855e-4402-466b-a412-8824fdc4d2ad)

<br>
<strong>Conclusion</strong>
<br>
Hence, we learned how to perform basic arithmetic operations in C++ using user input and output functions.
