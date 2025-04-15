# TP0: Hello, world! 

Objetivos:

• Demostrar capacidad para editar, compilar, y ejecutar programas C mediante
el desarrollo de un programa simple.

• Tener un primer contacto con las herramientas necesarias para abordar la
resolución de los trabajos posteriores.

• Creación de repositorio personal git.

• Armado de equipo de trabajo.


## Consignas

Indique en el readme.md

A. El compilador seleccionado

B. La versión ese compilador

C. La versión de C que el compilador compila

## Resolución

A- Compilador: MinGW

B- Versión del compilador: (MinGW.org GCC-6.3.0-1) 6.3.0

C- Versión de C: C11

Como obtuve la versión de C:
#include <stdio.h>

int main ()
{
    printf ("Version del estandar de C: %id\n", __STDC_VERSION__);
}

Al buscar el número que imprime, obtuve que versión de C estaba compilando.
