AUTOMAKE_OPTIONS = subdir-objects
lib_LTLIBRARIES = libmimetex.la
libmimetex_la_SOURCES = \
    src/mimetex.h \
    src/texfonts.h \
    src/utils.h \
    src/aa.c \
    src/bytemap.c \
    src/chardef.c \
    src/raster.c \
    src/render.c \
    src/tex.c \
    src/utils.c \
    src/mimetex.c

bin_PROGRAMS = mimetex gfuntype
mimetex_SOURCES = src/driver.c src/md5.c src/gifsave.c src/gifsave.h src/md5.h
mimetex_LDADD = libmimetex.la -lm
gfuntype_SOURCES = src/gfuntype.c
gfuntype_LDADD = libmimetex.la -lm

