# CPPDS_Basics
Introduction to C++ and its basic syntax
# C++ Basics: Hello World and Basic Operations

This repository contains examples and explanations of the basics of C++ programming, including printing "Hello, World!" and performing basic operations. This README provides an overview of how to get started with C++ programming.

## Table of Contents
- [C++ Basics](#c-basics)
  - [Hello, World!](#hello-world)
 

## C++ Basics

### Hello, World!

Printing "Hello, World!" is a common starting point in C++ programming. You can achieve this using the `cout` object from the `iostream` library:

```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```
### **BASICS**
1.#include <iostream>: This line includes the Input/Output Stream library, which provides functions like cout and endl for input and output operations.

2.int main() { ... }: This is the main function of your C++ program. It is the entry point of your program, and execution begins here.

3.std::cout: This is the standard C++ output stream, which is used to display output on the console.

4."Hello, World!": This is the text you want to print. It is enclosed in double quotation marks to represent a string.

5.<<: This is the output stream operator, used to insert the string "Hello, World!" into the std::cout stream.

6.std::endl: This is used to insert a newline character and flush the output buffer. It ensures that "Hello, World!" is displayed on a new line.

7.return 0;: This line indicates the successful completion of the main function. In C++, it's a convention to return 0 to indicate a successful execution of the program.

8. Compile and run this code, and it will print "Hello, World!" to the console.
   
