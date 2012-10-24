CC=/usr/bin/gcc

test: forktest demoexec

forktest: forktest.c
	$(CC) -o forktest forktest.c
demoexec: demoexec.c
	$(CC) -o demoexec demoexec.c
clean:
	rm -f demoexec forktest
