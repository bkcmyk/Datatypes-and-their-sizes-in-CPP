This program demonstrates how to input different types of data in C++ and displays both the value entered and the memory size (in bytes) occupied by each data type.

Every data type in C++ consumes a specific amount of memory (in bytes) depending on the system architecture and compiler. The sizeof() operator is used to determine this memory size.

Data      Type	Description	            Typical Size

int    	  Integer numbers	              4 bytes
float	    Decimal numbers (single)	    4 bytes
double	  Larger decimal numbers	      8 bytes
string	  Sequence of characters	      Implementation-dependent (commonly 24–32 bytes)
char	    Single character            	1 byte
bool    	Boolean (true/false)	        1 byte

 sizeof(string) returns the size of the string object, not the number of characters.

Working:
1. This program accepts input of:
  Integer
  Float
  Double  
  String
  Character
  Boolean

2. Prints the entered value and the size of the corresponding data type using sizeof().

This program helps beginners understand:
1. How different data types are declared and used.
2. How input/output works with multiple types.
3. How to use sizeof() to determine the memory usage of each type.
   
It provides an essential foundation in memory management and type systems in C++.

