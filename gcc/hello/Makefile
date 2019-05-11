CC = gcc
CFLAGS = -Wall

objects = main.o hello_fn.o

all: main clean

main: $(objects)
	$(CC) $(objects) -o main
	./main

.PHONY: clean
clean:
	rm -f $(objects) main
