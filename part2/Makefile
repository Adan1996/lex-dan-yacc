install:
	yacc -d calc.y
	lex calc.l
	gcc lex.yy.c calc.tab.c -o ./bin/calc