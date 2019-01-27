CC = g++ -std=c++11

run: main.o
	$(CC) -o run main.o

main.o: main.cc main.h
	$(CC) -c -o main.o main.cc

clean:
	rm -r *~ *.o
