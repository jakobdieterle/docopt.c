build:
	python ../docopt_c.py -o docopt.c example.docopt
	gcc -c docopt.c
	gcc -c example.c
	gcc -o example docopt.o example.o
	rm docopt.o example.o
