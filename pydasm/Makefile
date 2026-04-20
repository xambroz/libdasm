DESTDIR=/
BINDIR=/usr/local/bin
PYTHON ?= python

all:
	$(PYTHON) setup.py build

install:
	$(PYTHON) setup.py install --skip-build --root $(DESTDIR)
	install -m 755 -p -D das.py $(DESTDIR)$(BINDIR)/das.py
