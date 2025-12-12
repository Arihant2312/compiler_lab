# compiler_lab
//LEX program consiists of lex file 

to compile it lex filename.l
gcc lex.yy.c -lfl
./a.out
do control D to get ouput


//YACC program compilation 
there ar two files .l and .y
yacc -d filename.y
lex filename.l
gcc y.tab.c lex.yy.c -o filename
./filename
