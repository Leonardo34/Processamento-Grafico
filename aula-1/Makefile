all: run
run: link
	./hello
link: compile
	g++ -lglew -lglfw -framework Cocoa -framework OpenGL -framework IOKit -framework CoreVideo *.o -o hello
compile:
	g++ -Wall -c *.cpp
clean:
	rm hello
