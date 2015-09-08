#
# Makefile
#

include ../lib/Makefile.ax

install-local:
	install -d -o $(USER) -g $(GROUP) -m 755 \
	 $(DESTDIR)$(PREFIX)/bin
	install -o $(USER) -g $(GROUP) -m 755 mkmysqldump \
	 $(DESTDIR)$(PREFIX)/bin/mkmysqldump
	install -o $(USER) -g $(GROUP) -m 755 mkmysqlslave \
 	 $(DESTDIR)$(PREFIX)/bin/mkmysqlslave
