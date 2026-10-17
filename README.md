# Education

A simple C++ project for learning the basics of writing and running a program.

## Hello, World!

The program in `main.cpp` prints a greeting to the terminal.

### Build and run

Install a C++ compiler such as `g++` or `clang++`, then run:

```sh
g++ -std=c++17 -Wall -Wextra -pedantic main.cpp -o hello
./hello
```

Expected output:

```text
Hello, World!
```

`#include <iostream>` makes standard input and output available, `main` is where
the program starts, and `std::cout` writes the greeting to the terminal.
