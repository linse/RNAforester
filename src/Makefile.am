## Process this file with automake to produce Makefile.in

bin_PROGRAMS = RNAforester 

# C++ preprocesspr flags 
AM_CPPFLAGS = -I${includedir}\
							-I${srcdir}/anchors\
							-I${srcdir}/frontend\
							-I${srcdir}/RNAlib\
							-I${srcdir}/TED\
							-I${srcdir}/utils\
							-I${srcdir}/wmatch
# C++ compiler flags 
AM_CXXFLAGS = -Wall #-fmudflap -funwind-tables 
# C++ linker flags
#AM_LDFLAGS = -lmudflap


BUILT_SOURCES = shape.h
AM_YFLAGS = -d
RNAforester_SOURCES = \
	algebra.h\
	aligner.h\
	aligner.cpp\
	alignment.h\
	alignment_tables.h\
	main.cpp\
	forestali.h\
	forest.h\
	forestbase.h\
	forestbase.cpp\
	parser.h\
	parser.cpp\
	progressive_align.h\
	progressive_align.cpp\
	rna_profile_alignment.h\
	rna_profile_alignment.cpp\
	rna_alignment.h\
	rna_alignment.cpp\
	rna_algebra.h\
	rna_algebra.cpp\
	rna_alphabet.h\
	rna_alphabet.cpp\
	rnaforest.h\
	rnaforest.cpp\
	rnafuncs.h\
	rnafuncs.cpp\
	anchors/bplex.lpp \
	anchors/shape.ypp \
	anchors/anchors.h \
	anchors/basepair.h \
	anchors/anchors.cpp \
	frontend/Arguments.h\
	frontend/Arguments.cpp\
	frontend/rnaforester_options.h\
	frontend/rnaforester_options.cpp\
	RNAlib/fold.h\
	RNAlib/fold_vars.h\
	RNAlib/part_func.h\
	TED/forestsz.h\
	TED/treeedit.h\
	TED/rnaforestsz.h\
	TED/rnaforestsz.cpp\
	utils/debug.h\
	utils/matrix.h\
	utils/misc.h\
	utils/utils.h\
	wmatch/glib.c\
	wmatch/graphtypes.h\
	wmatch/wmatch.h\
	wmatch/wmatch.c

#INCLUDES = -I${includedir}

EXTRA_DIST = \
	alignment.t.cpp\
	forest.t.cpp\
	TED/forestsz.t.cpp\
	TED/treeedit.t.cpp\
	utils/misc.t.cpp\
	wmatch/match.defs\
	wmatch/pairs.c\
	wmatch/pointer.c\
	wmatch/readgraph.c\
	wmatch/term.c\
	wmatch/unpairs.c

