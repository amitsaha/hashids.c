# http://www.gnu.org/software/automake/manual/html_node/Libtool-Libraries.html#Libtool-Libraries
# https://developer.gnome.org/anjuta-build-tutorial/stable/create-autotools.html.en

lib_LTLIBRARIES = libhashids.la
libhashids_la_SOURCES = hashids.c
include_HEADERS = hashids.h

bin_PROGRAMS = hashids
hashids_SOURCES = main.c
hashids_LDADD = libhashids.la
