CC=gcc
CFLAGS=-O3 -std=gnu99 -Wall
BIN=$(shell basename `pwd`)
LDLIBS=

all: $(BIN)

$(BIN):	$(BIN).c
	$(CC) $(CFLAGS) $^ -o $@ $(LDLIBS)

clean:
	$(RM) $(BIN)
