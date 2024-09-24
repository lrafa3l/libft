# Libft

Libft is a custom implementation of essential C standard library functions, developed as part of the 42 curriculum. The library includes basic string manipulation, memory management, and linked list functions, providing a solid foundation for building more complex projects in C.

## Description

Libft is a collection of functions designed to mimic the standard C library. The goal is to re-implement standard C functions from `stdlib.h`, `string.h`, `stdio.h`, and other common libraries to gain a deeper understanding of low-level operations in C.

## Features

- **Standard C library functions**: Reimplementations of common string, memory, and linked list functions.
- **Formatted output with `ft_printf`**: A function that mimics `printf`, allowing for formatted output.
- **File reading with `get_next_line`**: A function that reads a line from a file descriptor.

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/libft.git

## Usage
After compiling the library using make, you will get a static library file libft.a. This file can be linked with your C projects to use the functions you implemented. Here's how to use the library in your own C programs:

- **Include the Header File**

In your C files, include the `libft.h` header so that you can use the functions from your library:
``` C
#include "libft.h"
```
