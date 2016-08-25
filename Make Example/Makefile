CC=gcc

hello: bar.o main.o
	$(CC) bar.o main.o -o hello
	
bar.o: bar.h bar.c
	$(CC) -c bar.c

main.o: main.c bar.h
	$(CC) -c main.c

clean:
	rm -f hello *.o
