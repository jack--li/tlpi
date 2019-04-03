cd lib
make
the we can #include "tlpi_hdr.h"
and 
gcc test.c -I./lib libtlpi.a

for module with libtlpi.a, we must include Makefile.inc
for module without libtlpi.a, we just just the default Makefile to generate the .o file.
