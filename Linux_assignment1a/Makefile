OUTPUTNAME = test

.PHONY = out clean run

SRC = test.c\
bitmask.c\
myutils.c\
mystring.c

out: $(SRC)
	gcc $(SRC) -o $(OUTPUTNAME).out

run:
	./$(OUTPUTNAME).out

clean:
	rm *.out