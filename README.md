# CPP
C++ (pronounced "C plus plus") is a high-performance, general-purpose programming language developed by Bjarne Stroustrup in 1983. It is an extension of the C programming language with added features like object-oriented programming (OOP), making it more versatile and powerful.<br>

Why Use C++?
C++ is widely used for various reasons:
1. Performance:
    * C++ is a compiled language, meaning it is converted into machine code, making it extremely fast and efficient.
    * It is suitable for resource-constrained systems, like embedded systems or real-time applications.
2. Object-Oriented Programming (OOP):
    * C++ supports OOP principles such as encapsulation, inheritance, polymorphism, and abstraction, making code reusable, modular, and maintainable.
3. Low-Level Access:
    * C++ provides low-level access to memory (e.g., pointers) while still supporting high-level programming features.
    * This makes it suitable for system-level programming (e.g., operating systems, drivers).
4. Standard Template Library (STL):
    * STL offers pre-written classes and functions for common data structures (e.g., vectors, lists, maps) and algorithms (e.g., sorting, searching), boosting productivity.
5. Wide Application:
    * System Software: Used to create operating systems, browsers, and compilers.
    * Game Development: Known for high performance in game engines.
    * Embedded Systems: Preferred for hardware programming.
    * Financial Systems: Utilized in high-frequency trading due to its speed.
    * Scientific Computing: Used for simulations and computationally intensive tasks.
6. Cross-Platform Development:
    * C++ is portable, meaning code written on one platform can often be compiled and run on another with minimal changes.
7. Large Community and Legacy:
    * It has a massive user base and decades of development, making resources, libraries, and tools abundant.
8. Hybrid Features:
    * Combines procedural and object-oriented programming.
Offers flexibility in how you design and structure your programs.
9. Compatibility with C:
    * C++ is backward compatible with C, so you can use C code within C++ programs, making it easier to adopt and extend older projects.

## Hello World Program

```cpp
#include <iostream>

int main () {
  // this is a comment
  /*multi line comment*/
  std::cout << "Hello World" << std::endl ;
  std::cout << "Hello Myself" << "\n" ;
  std::cout << "Bye World" ;
  return 0;
}
```

1. iostream
    * This is a preprocessor directive that tells the compiler to include the header file <iostream>.
    * <iostream> is used for input and output operations, such as printing to the console or reading from the keyboard.
    * Specifically, it allows you to use std::cout for output.
2. main function
    * This defines the main function, which is the entry point of every C++ program.
    * Execution starts from the main() function.
3. cout, endl and \n
    * std::cout is used to output data to the console.
    * "Hello World" is a string literal, which will be displayed in the console.
    * << is the stream insertion operator used to pass data to std::cout.
    * std::endl inserts a newline character (\n) and flushes the output buffer, ensuring the text is displayed immediately.
    * "\n" adds a new line without flushing the output buffer, which can be more efficient for some applications.
4. return 0
    * Returning 0 from the main() function is a convention in C++ to signal successful execution to the operating system.