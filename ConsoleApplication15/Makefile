CC = g++
CFLAGS = -Wall -g
OBJ = User.o Message.o main.o

chat: $(OBJ)
 $(CC) $(CFLAGS) -o chat $(OBJ)

%.o: %.cpp %.h
 $(CC) $(CFLAGS) -c $<

clean:
 rm -f $(OBJ) chat

.PHONY: clean
