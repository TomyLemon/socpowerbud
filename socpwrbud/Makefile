
CC=clang
CFLAGS=-fobjc-arc -funroll-loops -Ofast -mmacosx-version-min=11.0
LIBS=-lIOReport -framework Foundation -framework IOKit

PROGS= socpwrbud

all: $(PROGS)

socpwrbud: *.m
	$(CC) $(CFLAGS) -o $@ $^ ${LIBS}
	
clean:
	rm -rf ${PROGS} *.o
