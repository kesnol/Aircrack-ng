#!/usr/bin/make
# Configure prefix here:
prefix=$(DESTDIR)/usr/local/
etcdir=$(DESTDIR)/usr/local/etc/
OSTYPE:=$(shell uname -s|cut -d_ -f1)
include Makefile-$(OSTYPE)
