all: helloworld.asm helloworld

clean:
	rm -f helloworld helloworld.asm

helloworld.asm: helloworld.c
	gcc -Wall -S -o helloworld.asm helloworld.c

helloworld: helloworld.c
	gcc -Wall -o helloworld helloworld.c
