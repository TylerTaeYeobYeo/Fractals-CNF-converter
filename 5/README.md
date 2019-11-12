# CNF Converter

This program gives proper assignments for propostional logic, which is written in z3 form, in CNF FORM.

For Example:
```
 input: 
  (or a1 (not (or (not (or a2 a3)) a4)))
 output: 
  1 -4
  1 2 3
```

How To Use:

quick usage:
```
gcc 5.c
./a.out
//put input statement written in z3 form

or you can create a file (input) and store the statement.

./a.out < input

warning: beware that the file should not contain a line feed. If so, it will produce error message.
```

compile and run with standard input.
