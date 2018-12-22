CC      = gcc
CFLAGS  = -g
RM      = rm -r

default: all

all: main

main: main.o
	$(CC) $(CFLAGS) value.c chunk.c memory.c debug.c main.c -o main.o

clean:
	$(RM) main.o main.o.*
