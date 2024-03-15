CC = gcc
CFLAGS = -g -Wall
LDFLAGS = -lpcap

all: test

test: test.o
	$(CC) $(CFLAGS) -o $@ $^ $(LDFLAGS)

test.o: test.c
	$(CC) $(CFLAGS) -c $< -o $@

clean:
	rm -f *.o test
