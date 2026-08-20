# C Programming

Welcome to the **C Programming** repository. This repository contains learning resources, lecture materials, practical programs, assignments, and problem-solving exercises for learning the C programming language.

## 📚 About the Course

C is a general-purpose, procedural programming language that provides a strong foundation for understanding programming concepts, algorithms, data structures, and system-level programming.

This repository is designed for beginners and students who want to develop strong programming and problem-solving skills using C.

## 🎯 Course Objectives

By completing this course, students will be able to:

* Understand the fundamentals of programming.
* Write, compile, and execute C programs.
* Use variables, constants, data types, and operators.
* Implement decision-making and looping statements.
* Work with arrays and strings.
* Create and use functions.
* Understand pointers and memory concepts.
* Work with structures and unions.
* Perform file handling operations.
* Develop algorithmic and problem-solving skills.
* Debug and test C programs.

## 🧠 Topics Covered

### Unit I – Introduction to C Programming

* Introduction to Programming
* Problem Solving Techniques
* Algorithms and Flowcharts
* Structure of a C Program
* Compilation and Execution
* Keywords and Identifiers
* Variables and Constants
* Data Types
* Input and Output Functions
* Type Conversion

### Unit II – Operators and Control Statements

* Arithmetic Operators
* Relational Operators
* Logical Operators
* Assignment Operators
* Increment and Decrement Operators
* Conditional Operator
* Bitwise Operators
* `if`, `if-else`
* Nested `if`
* `else-if` ladder
* `switch`
* `for` loop
* `while` loop
* `do-while` loop
* `break` and `continue`

### Unit III – Arrays, Strings and Functions

* One-Dimensional Arrays
* Two-Dimensional Arrays
* Multidimensional Arrays
* Character Arrays
* Strings
* String Handling Functions
* Function Declaration
* Function Definition
* Function Calling
* Function Arguments
* Return Values
* Recursion

### Unit IV – Pointers and User-Defined Data Types

* Introduction to Pointers
* Pointer Declaration
* Pointer Operators
* Pointer Arithmetic
* Pointers and Arrays
* Pointers and Functions
* Structures
* Nested Structures
* Arrays of Structures
* Unions
* Enumerations

### Unit V – File Handling and Advanced Concepts

* File Handling
* Opening and Closing Files
* Reading and Writing Files
* Text Files
* Binary Files
* Preprocessor Directives
* Macros
* Dynamic Memory Allocation
* `malloc()`
* `calloc()`
* `realloc()`
* `free()`

## 💻 Software Requirements

You can use any of the following environments:

* GCC Compiler
* Visual Studio Code
* Code::Blocks
* Dev-C++
* Ubuntu/Linux Terminal
* Windows Terminal

## 🚀 Running C Programs

### Using GCC

Create a C file:

```bash
nano hello.c
```

Write the program and save it.

Compile the program:

```bash
gcc hello.c -o hello
```

Run the program:

```bash
./hello
```

### Using GCC on Windows

Compile:

```bash
gcc hello.c -o hello.exe
```

Run:

```bash
hello.exe
```

## 📝 Sample C Program

```c
#include <stdio.h>

int main()
{
    printf("Hello, World!");

    return 0;
}
```

### Output

```text
Hello, World!
```

## 📂 Repository Structure

```text
C-Programming/
│
├── README.md
│
├── Unit-I/
│   ├── Introduction/
│   ├── Algorithms/
│   ├── Flowcharts/
│   └── Basic-Programs/
│
├── Unit-II/
│   ├── Operators/
│   ├── Decision-Making/
│   └── Loops/
│
├── Unit-III/
│   ├── Arrays/
│   ├── Strings/
│   └── Functions/
│
├── Unit-IV/
│   ├── Pointers/
│   ├── Structures/
│   └── Unions/
│
├── Unit-V/
│   ├── File-Handling/
│   ├── Preprocessor/
│   └── Dynamic-Memory/
│
├── Assignments/
│
├── Practical/
│
└── Programs/
```

## 🧪 Practical Programs

The practical section contains programs based on:

1. Basic Input/Output
2. Arithmetic Operations
3. Area and Perimeter Calculations
4. Conditional Statements
5. Looping Statements
6. Pattern Programs
7. Array Operations
8. Matrix Operations
9. String Operations
10. Functions
11. Recursion
12. Pointers
13. Structures
14. File Handling

## 📌 Example Programs

### Area of a Circle

```c
#include <stdio.h>

int main()
{
    float radius, area;

    printf("Enter radius: ");
    scanf("%f", &radius);

    area = 3.14159 * radius * radius;

    printf("Area = %.2f", area);

    return 0;
}
```

### Swap Two Numbers

```c
#include <stdio.h>

int main()
{
    int a, b, temp;

    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    temp = a;
    a = b;
    b = temp;

    printf("After swapping: %d %d", a, b);

    return 0;
}
```

## 🧩 Problem-Solving Approach

Students are encouraged to follow these steps for every programming problem:

```text
Problem
   ↓
Understand the Requirements
   ↓
Algorithm
   ↓
Flowchart / Pseudocode
   ↓
Write C Program
   ↓
Compile
   ↓
Run
   ↓
Test with Different Inputs
   ↓
Debug Errors
   ↓
Final Output
```

## 🐞 Common Errors

### 1. Missing Semicolon

Incorrect:

```c
printf("Hello")
```

Correct:

```c
printf("Hello");
```

### 2. Incorrect `scanf()`

Incorrect:

```c
scanf("%d", a);
```

Correct:

```c
scanf("%d", &a);
```

### 3. Missing Header File

```c
#include <stdio.h>
```

is required when using functions such as `printf()` and `scanf()`.

## 📖 Learning Resources

Students should practice programs regularly and focus on understanding the logic rather than memorizing programs.

Recommended practice:

* Write programs from scratch.
* Predict the output before execution.
* Test boundary and invalid inputs.
* Identify and fix compiler errors.
* Convert algorithms into C programs.
* Practice debugging.

## 🎓 Learning Outcomes

After completing this course, students should be able to:

* Develop basic C programs independently.
* Apply programming constructs to solve problems.
* Design algorithms and flowcharts.
* Use arrays, strings, functions, and pointers.
* Implement structured programs.
* Perform file operations.
* Debug and improve C programs.
* Develop logical and computational thinking skills.

## 📋 Repository Guidelines

Students should:

* Use meaningful variable names.
* Follow proper indentation.
* Add comments where necessary.
* Avoid unnecessary code repetition.
* Test every program before submission.
* Keep programs organized according to units.
* Do not copy programs without understanding them.

## 👨‍💻 Author

**Prof. Vikas Sadashiv More**
Assistant Professor
Department of Computer Science & Engineering

## 📜 License

This repository is intended for **educational and academic purposes**.

---

⭐ **If you find this repository useful for learning C Programming, consider giving it a star!**
