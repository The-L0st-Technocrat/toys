CC = gcc
CFLAGS_OSX = -lusb -framework CoreFoundation -framework IOKit -lreadline
CFLAGS_LNX = -lusb -lreadline
CFLAGS_OSX+=-I/opt/local/include

all:
		@echo 'make linux !or! make macosx'
	
macosx:
		$(CC) iRecovery.c -o iRecovery $(CFLAGS_OSX)

linux:
		$(CC) iRecovery.c -o iRecovery $(CFLAGS_LNX)
