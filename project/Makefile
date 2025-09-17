# Compiler and flags

CC = gcc

CFLAGS = -Iinclude -Wall -Wextra
 
# Files

SRC = src/main.c

OBJ = $(SRC:.c=.o)

TARGET = myprogram
 
# Rules

all: $(TARGET)
 
$(TARGET): $(OBJ)

	$(CC) $(OBJ) -o $(TARGET)
 
%.o: %.c

	$(CC) $(CFLAGS) -c $< -o $@
 
clean:

	rm -f $(OBJ) $(TARGET)

 
