all:
	g++ -c -O4 main.c
	g++ -o main main.o

clean:
	rm -f *.o *~ main

install: all
	cp main /usr/local/bin/u8-to-double

uninstall: all
	rm -f main /usr/local/bin/u8-to-double
