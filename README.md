# ex1-makefile

## Makefile
1. Write a makefile to compile main.c, which uses a function in bar.h.
2. Run the make command to produce the executable.
3. Run the executable and see if it prints out "Hello World!"

Help: https://www.cs.umd.edu/class/fall2002/cmsc214/Tutorial/makefile.html

## Library
1. Compile math_lib.c to get math_lib.o
2. Make a library from math_lib.o using the ar command. (should create .a file. Library name must start with lib and end with .a, for example "libmath.a" or "libutil.a")
3. Compile useLib.c to get useLib.o
4. Use useLib.o from step 3 to create an executable using the library you created in step 2. (make sure to use -L and -l options)
5. Run the executable and see if it prints out 7.

Help: http://docencia.ac.upc.edu/FIB/USO/Bibliografia/unix-c-libraries.html
