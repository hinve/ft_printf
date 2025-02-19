# Ft_printf -> Replica de la printf original <-

**Ft_printf** es un proyecto de las escuelas 42 que consiste en recrear la función original **printf** de stdio.h. El objetivo del proyecto es profundizar en el manejo de argumentos variables, trabajar con diferentes formatos de salida y obtener una mejor comprensión de **printf**.

## Características
- Soporte para los principales especificadores de formato: **c**, **s**, **p**, **d**, **u**, **x**, **X**, **%**.
- Manejo de argumentos variables con **va_list**.
- Conversión de enteros a diferentes bases numéricas como: decimal, hexadecimal, etc.
- Implementación de la impresión de punteros de memoria.

## Estructura del proyecto

```
ft_printf/
├── ft_*.c            # Arhcivos .c.
├── ft_printf.h       # Librería.
├── Makefile          # Scripts de compilación.
└── README.md         # Descripción del proyecto.
```
## Uso
Para usar **ft_printf** en tu propio proyecto:
1. Clona el repositorio en tu máquina local
   ```
   $ git clone https://github.com/hinve/ft_printf.git ft_printf
   $ cd ft_printf
   ```
2. Compila la librería
   ```
   $ make
   ```
3. Incluye la libreria en tu proyecto
   ```
   #include "ft_printf.h"

    int main(void)
    {
        ft_printf("Hola, %s!\n", "mundo");
        return 0;
    }
   ```
4. Compila tu proyecto con el mío
   ```
   $ gcc -L. -lftprintf -o your_program your_program.c
   ```
   
## Contribuciones
Este proyecto es principalmente para mi aprendizaje personal, pero si tienes sugerencias o mejoras, no dudes en contactarme sobre ello :).

