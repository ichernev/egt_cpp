all: task2

%.o: %.cpp
	g++ -Wall -c -o $@ $<

task2: task.o pugixml.o
	g++ -Wall -o $@ $+

clean:
	rm -rf *.o task2
