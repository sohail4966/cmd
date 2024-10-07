//lex

lex lex.l
gcc lex.yy.c
./a.out

//yacc

lex lex.l
yacc -d yacc.y
gcc lex.yy.c y.tab.c -ll
./a.out
