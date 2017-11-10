all: main.o hello.o
	g++ -o hello.exe main.o hello.o

main.o: main.cpp
	g++ -c main.cpp

hello.o: hello.cpp
	g++ -c hello.cpp

clean:
	rm -rf main.o hello.o hello.exe
