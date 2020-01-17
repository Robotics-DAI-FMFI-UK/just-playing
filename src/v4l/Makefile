LIBS=-lpng

all: capturev4l2 find_red

capturev4l2:	capturev4l2.c pngwriter.c
	gcc -o capturev4l2 $^ $(LIBS)

find_red:	find_red.c pngwriter.c
	gcc -o find_red $^ $(LIBS)

clean:
	rm capturev4l2
