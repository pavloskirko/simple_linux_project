AUTOMAKE_OPTIONS = foreign
bin_PROGRAMS = nuke_mars
nuke_mars_SOURCES = main.c func.c 
include_HEADERS = header.h
includedir = include

clean-all : 
	ls -I "*.c" -I "*.h" -I "*.ac" -I "*.am" |xargs rm -rf
	rm -rf /usr/local/bin/$(bin_PROGRAMS)