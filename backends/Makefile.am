# SPDX-License-Identifier: GPL-3.0-or-later

AUTOMAKE_OPTIONS = subdir-objects
MAINTAINERCLEANFILES = $(srcdir)/Makefile.in

SUBDIRS = \
    graphite \
    json \
    opentsdb \
    prometheus \
	$(NULL)

dist_noinst_DATA = \
	README.md \
	$(NULL)

dist_noinst_SCRIPTS = \
	nc-backend.sh \
	$(NULL)
