APP=ex1


all: clean comp run

clean:
	rm -rf ${APP}.exe

comp:
	g++ -I/usr/local/include/eigen3 -Wall ${APP}.cpp -o ${APP}.exe


run:
	./${APP}.exe
