# Makefile is a binary file
main:shape.o rect.o circle.o main.o
	gcc -o main shape.o rect.o circle.o main.o

shape.o: shape.c
	gcc -c  shape.c

rect.o:  rect.c
	gcc -c rect.c

circle.o: circle.c
	gcc -c circle.c

main.o:  main.c
	gcc -c main.c

clean:
	rm -f *.o main
