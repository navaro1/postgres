#-------------------------------------------------------------------------
#
# Makefile--
#    Makefile for access/hash
#
# IDENTIFICATION
#    src/backend/access/hash/Makefile
#
#-------------------------------------------------------------------------



#subdir = src/backend/access/sct
#top_builddir = ../../../..
#include $(top_builddir)/src/Makefile.global

EXTENSION = sct
MODULE_big = sct
PG_CONFIG = pg_config

OBJS = \
	hash.o \
	hash_xlog.o \
	hashfunc.o \
	hashinsert.o \
	hashovfl.o \
	hashpage.o \
	hashsearch.o \
	hashsort.o \
	hashutil.o \
	hashvalidate.o
PGXS := $(shell $(PG_CONFIG) --pgxs)
include $(PGXS)


#include $(top_srcdir)/src/backend/common.mk
