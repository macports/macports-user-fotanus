MACPORTS_ROOT=`dirname \`dirname \\\`which port \\\`\``
all:
	@echo $(MACPORTS_ROOT)
	gcc lib_dependency.c -I$(MACPORTS_ROOT)/include/ -L$(MACPORTS_ROOT)/lib/ -ldep -o lib_dependency
install:

