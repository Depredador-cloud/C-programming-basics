# C-programming-basics
Introduction to C Programming Language
C is a powerful general-purpose programming language that is widely used in various fields such as system programming, embedded systems, and developing software applications. Here is a basic explanation of the C programming language, using information from "C Programming for Arduino" by Julien Bayle.

History of C
C was developed in the early 1970s by Dennis Ritchie at Bell Labs. It was designed as a system programming language for writing operating systems. Over the years, C has become one of the most widely used programming languages due to its efficiency and control over system resources.

Key Features of C
Simple and Efficient: C provides a simple and efficient way to write programs. Its syntax is straightforward, which makes it easy to learn and use.
Low-Level Access: C allows low-level access to memory through pointers, enabling direct manipulation of hardware and memory.
Portability: C programs can be easily ported to different types of computer systems.
Rich Library: C has a rich set of built-in functions and libraries that help in performing various operations.
Structured Programming: C supports structured programming, which helps in writing clear and maintainable code.
Basic Structure of a C Program
A typical C program consists of the following components:

Preprocessor Directives: These are commands that are processed before the actual compilation of the code begins. They usually start with a # symbol. For example, #include <stdio.h> includes the standard input-output library.
Main Function: The main function is the entry point of every C program. It is where the execution of the program begins.
Variables and Data Types: C supports various data types such as int (integer), float (floating-point), char (character), and more.
Statements and Expressions: These are the instructions that perform operations and compute values.
Functions: Functions in C are used to perform specific tasks and can be reused throughout the program.
Example of a Simple C Program

c
#include <stdio.h>

int main() {
    // Variable declaration
    int num;

    // Print a message to the console
    printf("Enter a number: ");

    // Read input from the user
    scanf("%d", &num);

    // Print the entered number
    printf("You entered: %d\n", num);

    return 0;
}
Explanation of the Example
#include <stdio.h>: This line includes the standard input-output library.
int main() { ... }: This is the main function where the program execution begins.
int num;: This line declares an integer variable named num.
printf("Enter a number: ");: This line prints a message to the console.
scanf("%d", &num);: This line reads an integer input from the user and stores it in the variable num.
printf("You entered: %d\n", num);: This line prints the value of num to the console.
return 0;: This line indicates that the program has ended successfully.
Common Data Types in C
int: Used to store integers.
float: Used to store floating-point numbers.
double: Used to store double-precision floating-point numbers.
char: Used to store single characters.
void: Represents the absence of type.
Control Structures
C supports various control structures for decision making and looping:

if, else if, else: Used for conditional branching.
switch: Used for multi-way branching.
for, while, do-while: Used for looping.
Example of Control Structures


c
#include <stdio.h>

int main() {
    int num = 10;

    // if-else statement
    if (num > 0) {
        printf("Number is positive\n");
    } else {
        printf("Number is not positive\n");
    }

    // for loop
    for (int i = 0; i < 5; i++) {
        printf("Iteration %d\n", i);
    }

    return 0;
}
Functions in C
Functions are blocks of code that perform specific tasks. They help in modularizing the code and making it reusable.

Example of a Function

c
#include <stdio.h>

// Function declaration
int add(int a, int b);

int main() {
    int result;

    // Function call
    result = add(5, 3);

    printf("The sum is: %d\n", result);

    return 0;
}

// Function definition
int add(int a, int b) {
    return a + b;
}
In this example, the add function takes two integers as arguments and returns their sum.

Conclusion
C is a powerful and versatile programming language that provides low-level access to memory and system resources. Its simplicity, efficiency, and rich set of libraries make it a popular choice for various applications, from system programming to embedded systems. By understanding the basic structure, data types, control structures, and functions in C, you can start writing your own programs and explore the vast possibilities that C programming offers.
