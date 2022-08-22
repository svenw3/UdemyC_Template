DEBUG_FLAGS = -O0 -g3
RELEASE_FLAGS = -O3

FLAGS = $(RELEASE_FLAGS)

preprocess:
	gcc $(FLAGS) -E IfStatement.c > Temp.c

assemble:
	gcc $(FLAGS) -S IfStatement.c

compile:
	gcc $(FLAGS) -c IfStatement.c -o IfStatement.o

build:
	gcc $(FLAGS) IfStatement.o -o IfStatement
