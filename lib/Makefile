.PHONY: clean

libfuncs.a: func1.o func2.o
	ar rv libfuncs.a func1.o func2.o

func1.o: func1.c 
	gcc -c func1.c -I../include 
func2.o: func2.c 
	gcc -c func2.c -I../include

clean:
	rm  libfuncs.a func1.o func2.o
