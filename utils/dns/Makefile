# DNS Utilities Makefile.
#
# $Id: Makefile,v 1.6 2000/04/21 15:22:57 logic Exp $
#
# $Log: Makefile,v $
# Revision 1.6  2000/04/21 15:22:57  logic
# Update to current cvs tree.
#
# Revision 1.1  1998/01/27 02:10:33  emarshal
# Added dump.c, a quick utility for dumping an RR (sort of);
# suitable for hexdumping.
#

# Linux/glibc, Solaris
#CC=cc
#CFLAGS=-O
#LDFLAGS=-s -lresolv

# Linux/libc5, NeXT
CC=cc
CFLAGS=-g -Wall
LDFLAGS=-s

all: dump

clean:
	-rm dump
