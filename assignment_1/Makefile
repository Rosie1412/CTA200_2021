CFLAGS=-std=c99

ave : main.o average.o
	cc $(CFLAGS) -o ave main.o average.o

main.o : main.c average.h
	cc $(CFLAGS) -c main.c 

average.o : average.c
	cc $(CFLAGS) -c average.c

clean :
	-rm *.o

