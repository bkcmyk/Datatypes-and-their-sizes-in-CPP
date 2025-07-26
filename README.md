# Use of Different Data Types in C++

## Program Overview

This program demonstrates how to input different types of data in C++ and displays both the value entered and the memory size (in bytes) occupied by each data type.

Each data type in C++ consumes a specific amount of memory depending on the system architecture and compiler. The `sizeof()` operator is used to determine this memory size.

Note:  
`sizeof(string)` returns the size of the string object, not the number of characters entered.

---

## Working

The program accepts input for the following data types:

- Integer  
- Float  
- Double  
- String  
- Character  
- Boolean  

It then prints:

- The value entered by the user  
- The memory size using the `sizeof()` operator
  ![Datatypes Chart](https://github.com/user-attachments/assets/fd5aec85-ccb5-4012-b0d9-6a44a383fd83)

---

## Sample Output

#### Sample Output 1
Enter any Integer: 5

Integer = 5 and its size is: 4 bytes

#### Sample Output 2
Enter a Decimal: 5

Decimal = 5 and its size is: 4 bytes

#### Sample Output 3
Enter a Bigger Decimal: 8.220

Double = 8.22 and its size is: 8 bytes

#### Sample Output 4
Enter a Word: Hello

The string is: Hello and its size (object size) is: 32 bytes

### Sample Output 5
Enter a Character: A

The character is: A and its size is: 1 bytes

#### Sample Output 6
Enter true (1) or false (0): 1

You entered 1 and its size is: 1 bytes

Note:  
If you enter `true` or `false` as text, C++ will interpret them as `0` because it doesn't accept text input directly for `bool`. Use `1` for `true` and `0` for `false`.

---

## Key Concepts Demonstrated

1. Data Types – Understanding of built-in types like `int`, `float`, `double`, `string`, `char`, and `bool`.
2. User Input – Using `cin` to get input from users for different types.
3. Memory Size – Using the `sizeof()` operator to display how much memory each data type occupies.
4. System Behavior – Shows how data size can vary based on the type and system.

---

## Learning Outcomes

- Learn how to declare and input different basic data types in C++  
- Understand how to measure memory usage of variables using `sizeof()`  
- Recognize how different types behave during input/output  
- Strengthen your foundation in C++ type systems and memory management

---




