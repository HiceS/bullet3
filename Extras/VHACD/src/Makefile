CC = g++
HEADER = ../inc/
PUBLIC = ../public/
CFLAGS = -c -Wall -I$(PUBLIC) -I$(HEADER)

all:
	$(CC) $(CFLAGS) $(HEADER) *.cpp
	ar rvs vhacd *.o
	
clean: 
	rm -rf *.o *.a vhacd ../inc/*.gch ../public/*.gch

