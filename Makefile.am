AUTOMAKE_OPTIONS = foreign
bin_PROGRAMS = helloworld
helloworld_SOURCES = hello_world.c hello_func.c
include_HEADERS = hello_make.h

# Cleans the directory and removes binary file from /usr/local/bin with 'make clean-all'
.PHONY: clean-all
clean-all:
	$(MAKE) distclean
	rm -rf autom4te.cache
	rm -rf _build _inst .deps
	rm -f configure configure.scan aclocal.m4 Makefile.in depcomp install-sh missing compile
	rm -f helloworld-0.1.tar.gz
	sudo rm /usr/local/bin/helloworld
