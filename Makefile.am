## $Id: Makefile.am 1.12 06/05/07 17:37:11+03:00 anttit@tcs.hut.fi $
## Process this file with automake to produce Makefile.in

AUTOMAKE_OPTIONS = gnu
EXTRA_DIST = BUGS INSTALL.kernel README.IPsec chkconf_kernel.sh \
	     extras/example-cmd.conf extras/example-mar.conf

if MISSING
LIBMISSING = libmissing
endif
SUBDIRS = $(LIBMISSING) libnetlink src man
