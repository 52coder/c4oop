# Makefile is a binary file
main:shape.o rect.o main.o
	gcc -o main shape.o rect.o main.o

shape.o: shape.c
	gcc -c  shape.c

rect.o:  rect.c
	gcc -c rect.c

main.o:  main.c
	gcc -c main.c

clean:
	rm -f *.o main
