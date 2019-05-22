## Process this file with automake to produce Makefile.in

AM_CPPFLAGS = \
	-DPACKAGE_DATA_DIR=\""$(datadir)"\" \
	-DPACKAGE_LOCALE_DIR=\""$(prefix)/share/locale"\" \
	@PACKAGE_CFLAGS@

bin_PROGRAMS = gcolor2

gcolor2_SOURCES = \
	main.c \
	support.c support.h \
	interface.c interface.h \
	callbacks.c callbacks.h

gcolor2_LDADD = @PACKAGE_LIBS@ $(INTLLIBS)

