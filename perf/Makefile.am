INCLUDES = -I$(top_builddir)/include \
           -I$(top_srcdir)/include

noinst_PROGRAMS = local_lat remote_lat local_thr remote_thr inproc_lat inproc_thr

local_lat_LDADD = $(top_builddir)/src/libxs.la
local_lat_SOURCES = local_lat.cpp

remote_lat_LDADD = $(top_builddir)/src/libxs.la
remote_lat_SOURCES = remote_lat.cpp

local_thr_LDADD = $(top_builddir)/src/libxs.la
local_thr_SOURCES = local_thr.cpp

remote_thr_LDADD = $(top_builddir)/src/libxs.la
remote_thr_SOURCES = remote_thr.cpp

inproc_lat_LDADD = $(top_builddir)/src/libxs.la
inproc_lat_SOURCES = inproc_lat.cpp

inproc_thr_LDADD = $(top_builddir)/src/libxs.la
inproc_thr_SOURCES = inproc_thr.cpp
