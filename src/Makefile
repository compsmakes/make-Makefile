FILES=mkmakefile
BINS= mkmakefile.x
TEMPLATE=mkmakefilemake
DESTDIR=/usr/local/bin/mkmakefile
TDESTDIR=/usr/local/bin

all:
		shc -r -f $(FILES)

help:
		@echo "make - compile sources"
		@echo "install - install binaries to DESTDIR"

install:
		cp $(BINS) $(DESTDIR)
		cp $(TEMPLATE) $(TDESTDIR)
		chmod +x $(DESTDIR)
