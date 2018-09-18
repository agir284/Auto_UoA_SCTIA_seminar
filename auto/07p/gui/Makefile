#===> sun.makefile
#
#   Makefile written by Xianjun WANG in March 1994
#
#   This Makefile is used to compile the Graphic User Interface(GUI)
#   source code for Sun(Sparc) Station machines.
#
#   Type "make -f sun.makefile" to compile
#
.SUFFIXES: .c .o
#
CC   = gcc
#
CFLAGS =  -g -O2  -I../include -c
#SRC = auto97.c
OBJ  = auto97.o
PGM  = ../bin/auto97
RM   = rm -f
LIBS =   
#
.c.o:
	$(CC) $(CFLAGS) $*.c -o $@
#
$(PGM): $(OBJ)
	$(CC) $(OBJ) -o $@ $(LIBS)
#
clean:  
	$(RM) *.o *~

