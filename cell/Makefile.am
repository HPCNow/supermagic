###############################################################################
# Copyright (c) 2012      Los Alamos National Security, LLC.
#                         All rights reserved.
#
# This program was prepared by Los Alamos National Security, LLC at Los Alamos
# National Laboratory (LANL) under contract No. DE-AC52-06NA25396 with the U.S.
# Department of Energy (DOE). All rights in the program are reserved by the DOE
# and Los Alamos National Security, LLC. Permission is granted to the public to
# copy and use this software without charge, provided that this Notice and any
# statement of authorship are reproduced on all copies. Neither the U.S.
# Government nor LANS makes any warranty, express or implied, or assumes any
# liability or responsibility for the use of this software.
################################################################################

CC=gcc

lib_LTLIBRARIES =

if SMGC_BUILD_CELL
lib_LTLIBRARIES += libcell_check.la
endif

libcell_check_la_SOURCES = \
cell_check.c cell_check.h cell_check_internal.h cw_util.h cw_util.c cw_util.h

libcell_check_la_LDFLAGS = \
-L/usr/lib64/dacs/debug

libcell_check_la_LIBADD = \
-ldacs_hybrid

SUBDIRS = ppu
