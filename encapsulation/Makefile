# Makefile is a binary file
main:shape.o main.o
	gcc -o main shape.o main.o

shape.o: shape.c
	gcc -c  shape.c

main.o:  main.c
	gcc -c main.c

clean:
	rm -f *.o main
