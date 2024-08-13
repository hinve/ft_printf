# Ft_printf ->Replicate the original printf<-
**Ft_printf** is a 42 schools project that involves recreating the original **printf** function from stdio.h. The goal of the project is to delve into hadling variable arguments, work with different output formats, and gain a better undestanding of **printf**.
## Features
- Support for the main format specifiers: **c**, **s**, **p**, **d**, **u**, **x**, **X**, **%**.
- Handling variable arguments with **va_list**.
- Conversion of integers to different numeric bases like: decimal, hexadecimal, etc.
- Implementation of memory pointer printing.
## Project structure
```
ft_printf/
├── ft_*.c            # Whole .c files.
├── ft_printf.h       # Library.
├── Makefile          # Compilation scripts.
└── README.md         # Project description.
```
## Usage
To use **ft_printf** on your own project:
1. Clone the repository on your local machine
   ```
   $ git clone https://github.com/hinve/ft_printf.git ft_printf
   $ cd ft_printf
   ```
2. Compile the library
   ```
   $ make
   ```
3. Include the library into your project
   ```
   #include "ft_printf.h"

    int main(void)
    {
        ft_printf("Hola, %s!\n", "mundo");
        return 0;
    }
   ```
4. Compile your project with mine
   ```
   $ gcc -L. -lftprintf -o your_program your_program.c
   ```
## Contributions
This project is mainly for my personal learning, but if you have any suggestions or improvements, feel free to contact me about it :).
