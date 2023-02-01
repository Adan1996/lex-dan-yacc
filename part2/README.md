## COMPILE
```
$ yacc -d calc.y
$ lex calc.l
$ gcc lex.yy.c calc.tab.c -o calc
```
## RUN PROGRAM
```
$ calc [enter]
$ a = 1 + 2;
$ print a;
$ Printing 3