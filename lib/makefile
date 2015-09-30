OBJFILES = func1.o func2.o

libfuncs.a: $(OBJFILES)
	ar rv libfuncs.a $(OBJFILES)
%.o: %.c
	gcc -I../include -c $< -o $@
clean:
	rm *.o $(OUTPUT)
