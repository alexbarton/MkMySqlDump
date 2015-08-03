#
# Makefile
#

include ../lib/Makefile.ax

install-local:
	install -d -o $(USER) -g $(GROUP) -m 755 \
	 $(DESTDIR)$(PREFIX)/sbin
	install -o $(USER) -g $(GROUP) -m 755 mkmysqldump \
	 $(DESTDIR)$(PREFIX)/sbin/mkmysqldump
	install -o $(USER) -g $(GROUP) -m 755 mkmysqlslave \
 	 $(DESTDIR)$(PREFIX)/sbin/mkmysqlslave
