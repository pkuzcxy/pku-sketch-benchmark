CC=g++ -w
CFLAGS = -std=c++11
OBJS=main.cpp test.cpp factor.cpp

sketchList.h:
	sh genSketchList.sh

AAA.out: main.cpp test.cpp factor.cpp sketchList.h
	$(CC) $(CFLAGS) $(OBJS) -o $@
	rm ../sketch/sketchList.h
clean :
	rm -rf ../AAA.out *.o