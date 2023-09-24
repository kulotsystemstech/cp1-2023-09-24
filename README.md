## CP1 | 2023-09-24
Introduction to Computer Programming 1


### Programming Language
- a set of instructions that people use to tell computers what to do
- how humans communicate tasks to computers, using specific instructions. It's the code that makes software and apps work.

Examples:
- C
- C++
- Java
- PHP
- Python
- JavaScript


### Problem Solving
- using computers to find solutions to real-world challenges. It involves breaking down complex problems into smaller, manageable steps that a computer can understand.


### ALGORITHM
- finite number of steps to be carried out in order to solve a specific problem

### VARIABLE
- identifier that stores a specific data

---

#### PROBLEM:
- create a program that asks the user to enter two numbers, then display the sum of those numbers.


#### ALGORITHM:
1. Ask the user to enter the first number, and save it to the variable called `num1`.

2. Ask the user to enter the second number, and save it to the variable called `num2`.

3. Calculate the sum of the `num1` and `num2` and store the result to the variable `sum`:
    ```
    sum = num1 + num2
    ```
4. Display the value of `sum` on the screen.


### Computer Program
- a set of instructions that tell a computer what to do.

##### INPUT
- information received.
##### PROCESS
- operations and calculations.
##### OUTPUT
- result or response.

### Dev C++
- tool for C++ programming

### compiling
- the process of turning source code into an executable program

##### .cpp
- file extension for C++ program source files
- example: main.cpp (for programmers)
- 
##### .exe
- file extension for executable programs in Windows
- example: main.exe (for computers running on Windows)

#### C++ Source File
```cpp
#include <iostream>
#include <cstdlib>

using namespace std;

int main()
{
   // declare variables
   int num1;
   int num2;
   int sum;
   
   // ask first number
   cout << "Enter the first number : ";
   cin  >> num1;
   
   // ask second number
   cout << "Enter the second number: ";
   cin  >> num2;
   
   // calculate the sum
   sum = num1 + num2;
   
   cout << endl;
   
   // display the value of sum
   cout << "The sum is " << sum << ".";
   
   cout << endl << endl;
   system("PAUSE");
   return 0;
}
```
