CFLAGS=-c -Wall -O2 -D__LINUX__
LIBS = -lPNGdec -lm -lpthread

all: png2bmp

png2bmp: main.o
	$(CC) main.o $(LIBS) -o png2bmp

main.o: main.cpp
	$(CXX) $(CFLAGS) main.cpp

clean:
	rm *.o png2bmp
