ACLOCAL_AMFLAGS = -I m4
AM_CXXFLAGS = $(FW_INCLUDE) $(TSK_INCLUDE) -Wall
LDFLAGS="-lexif"

lib_LTLIBRARIES = libtskLibExifModule.la
libtskLibExifModule_la_SOURCES = LibExifModule.cpp
libtskLibExifModule_la_LIBADD = $(FW_LIBS)
