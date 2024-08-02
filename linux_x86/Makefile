CC  = gcc
CFLAGS = -fno-stack-protector -z execstack

BIN = my_level1

all: $(BIN)
$(all):
	$(CC) $(CFLAGS) -o $@ $<

my_level1:
	$(CC) $(CFLAGS) -o my_level1 my_level1.c
clean:
	rm -f $(BIN)