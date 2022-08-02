dir = usr/share/desktop-base/tmaxgooroom-theme/grub

.PHONY: build install

build: $(files)

install:
	install -d $(DESTDIR)/$(dir)
	$(INSTALL_DATA) $(wildcard *.png *.sh) $(DESTDIR)/$(dir)

include ../../Makefile.inc
