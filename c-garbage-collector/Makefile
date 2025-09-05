# Name of the output binary
OUTPUT = main

# compiler
CC = clang
# flags, you can add -g to enable debugging mode.
CFLAGS = -Wall

# Source files (throw all .c files in here)
SRC = main.c

# Default rule (what happens when you run 'make')
all: $(OUTPUT)

$(OUTPUT): $(SRC)
	$(CC) $(CFLAGS) $(SRC) -o $(OUTPUT)

run:
	./$(OUTPUT)

# Clean rule
clean:
	rm -f $(OUTPUT)
