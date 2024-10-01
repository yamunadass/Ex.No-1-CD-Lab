Ex. No : 1

IMPLEMENTATION OF SYMBOL TABLE

Register Number :

Date :

AIM:

To write a C program to implement a symbol table.

ALGORITHM:

Start the program.
Get the input from the user with the terminating symbol ‘$’.
Allocate memory for the variable by dynamic memory allocation function.
If the next character of the symbol is an operator then only the memory is allocated.
While reading, the input symbol is inserted into symbol table along with its memory address.
The steps are repeated till ‘$’ is reached.
To reach a variable, enter the variable to be searched and symbol table has been checked for corresponding variable, the variable along with its address is displayed as result.
Stop the program.
PROGRAM:

OUTPUT:

RESULT:

The program to implement a symbol table is executed and the output is verified.



Ex-2-GENERATION OF LEXICAL TOKENS LEX FLEX TOOL
AIM
To write a lex program to implement lexical analyzer to recognize a few patterns.
ALGORITHM
Start the program.

Lex program consists of three parts.

a. Declaration %%

b. Translation rules %%

c. Auxilary procedure.

The declaration section includes declaration of variables, maintest, constants and regular definitions.

Translation rule of lex program are statements of the form

a. P1 {action}

b. P2 {action}

c. …

d. …

e. Pn {action}

Write a program in the vi editor and save it with .l extension.

Compile the lex program with lex compiler to produce output file as lex.yy.c. eg $ lex filename.l $ cc lex.yy.c

Compile that file with C compiler and verify the output.

INPUT
OUTPUT
RESULT
The lexical analyzer is implemented using lex and the output is verified.
