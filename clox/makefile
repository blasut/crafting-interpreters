CC      = gcc
CFLAGS  = -g
RM      = rm -r

default: all

all: main

main: main.o
	$(CC) $(CFLAGS) compiler.c scanner.c vm.c value.c chunk.c memory.c debug.c main.c -o main.o

clean:
	$(RM) main.o main.o.*
