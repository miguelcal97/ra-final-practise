# Ruta absoluta o relativa (cuidado con espacios en blanco al final del path!)
ARTOOLKITDIR = ../../ARToolKit
INC_DIR      = $(ARTOOLKITDIR)/include
LIB_DIR      = $(ARTOOLKITDIR)/lib

LIBS   =  -lARgsub -lARvideo -lARMulti -lAR -lGL -lGLU -lglut -lm 

NAMEEXEC     = ar_game

all: $(NAMEEXEC)

$(NAMEEXEC): $(NAMEEXEC).c 
	cc -I $(INC_DIR) -o $(NAMEEXEC) $(NAMEEXEC).c -L$(LIB_DIR) $(LIBS)
clean:
	rm -f *.o $(NAMEEXEC) *~ *.*~

