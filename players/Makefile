##
# Makefile for Battleship Games Players
#
# April 1998, Nigel Ward, University of Tokyo
#
CC = gcc -g -Wall -I ../master/
IF = ../master/

#note that we just assume that client-side.o and util.o are up-to-date

all: ex1 ex2 ex3 ex4 ex5 player player2

ex1:    ex1.o 
	${CC} -o ex1 ex1.o ${IF}util.o ${IF}client-side.o
ex1.o:  ex1.c ${IF}redundant.h ${IF}util.o ${IF}client-side.o ${IF}public.h
	${CC} -c ex1.c

ex2:    ex2.o 
	${CC} -o ex2 ex2.o ${IF}util.o ${IF}client-side.o
ex2.o:  ex2.c ${IF}redundant.h ${IF}util.o ${IF}client-side.o ${IF}public.h
	${CC} -c ex2.c

ex3:    ex3.o 
	${CC} -o ex3 ex3.o ${IF}util.o ${IF}client-side.o
ex3.o:  ex3.c ${IF}redundant.h ${IF}util.o ${IF}client-side.o ${IF}public.h
	${CC} -c ex3.c

ex4:    ex4.o 
	${CC} -o ex4 ex4.o ${IF}util.o ${IF}client-side.o
ex4.o:  ex4.c ${IF}redundant.h ${IF}util.o ${IF}client-side.o ${IF}public.h
	${CC} -c ex4.c

ex5:    ex5.o 
	${CC} -o ex5 ex5.o ${IF}util.o ${IF}client-side.o
ex5.o:  ex5.c ${IF}redundant.h ${IF}util.o ${IF}client-side.o ${IF}public.h
	${CC} -c ex5.c

player: player.o 
	${CC} -o player player.o ${IF}util.o ${IF}client-side.o
player.o: player.c ${IF}redundant.h ${IF}util.o ${IF}client-side.o ${IF}public.h
	${CC} -c player.c

player2: player2.o 
	${CC} -o player2 player2.o ${IF}util.o ${IF}client-side.o
player2.o: player2.c ${IF}redundant.h ${IF}util.o ${IF}client-side.o ${IF}public.h
	${CC} -c player2.c

clean: 
	rm *.o ex1 ex2 ex3 ex4 ex5 player
