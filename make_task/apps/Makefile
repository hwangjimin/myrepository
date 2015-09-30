CC = gcc
CFLAGS = -g -Wall
OUTPUT = main
LIBPATH = ../lib

main: main.o
	$(CC) -o $(OUTPUT) -L$(LIBPATH) main.o -lfuncs

main.o:
	$(CC) $(CFLAGS) -c -I../include main.c -o main.o
clean:
	rm -f $(OUTPUT) *.o
