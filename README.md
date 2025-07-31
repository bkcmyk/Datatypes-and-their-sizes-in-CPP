# Use of Different Data Types in C++

## Objective

To write a C++ program that demonstrates input, output, and memory size of basic data types.

---

## Apparatus

- Visual Studio Code (VS Code)  
- Any Online C++ Compiler (e.g., Replit, OnlineGDB, Programiz)

---

## Theory

Each variable in C++ has a **data type** that determines the type of value it can hold and the memory it occupies. C++ provides several built-in types including:

- **int**: Integer values
- **float**: Decimal values with single precision
- **double**: Decimal values with double precision
- **char**: Single character
- **bool**: Boolean values (true or false)
- **string**: Sequence of characters (from the Standard Library)

Memory for each data type is allocated differently, and we can determine this using the `sizeof()` operator.

> Note: `sizeof(string)` gives size of the string object, not the number of characters entered.

---

## Key Concepts Used

- Data Types: `int`, `float`, `double`, `char`, `bool`, `string`
- Input with `cin` and Output with `cout`
- Memory size detection using `sizeof()`

---

## Algorithms

### 1. Integer Input and Size
1. Declare an integer variable.
2. Use `cin` to take input.
3. Display value and `sizeof(int)`.

### 2. Float Input and Size
1. Declare a float variable.
2. Use `cin` to take input.
3. Display value and `sizeof(float)`.

### 3. Double Input and Size
1. Declare a double variable.
2. Use `cin` to take input.
3. Display value and `sizeof(double)`.

### 4. String Input and Size
1. Declare a `string` variable.
2. Use `cin` to take input.
3. Display value and `sizeof(string)`.

### 5. Character Input and Size
1. Declare a `char` variable.
2. Use `cin` to take input.
3. Display value and `sizeof(char)`.

### 6. Boolean Input and Size
1. Declare a `bool` variable.
2. Use `cin` to take input (use 1 for true, 0 for false).
3. Display value and `sizeof(bool)`.

---

## Learning Outcomes

- Learned how to declare and input basic data types in C++  
- Understood how to check memory usage with `sizeof()`  
- Gained familiarity with how C++ handles different types  
- Strengthened knowledge of fundamental programming concepts

