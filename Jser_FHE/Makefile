#############################################################################
# Makefile for building: ser_FHE
# Generated by qmake (2.01a) (Qt 4.8.4) on: Fri Jan 16 04:45:40 2015
# Project:  ser_FHE.pro
# Template: app
# Command: /usr/local/bin/qmake -spec /usr/local/mkspecs/linux-g++ -o Makefile ser_FHE.pro
#############################################################################

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DQT_NO_DEBUG -DQT_GUI_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -pipe -O2 -Wall -W -D_REENTRANT $(DEFINES)
CXXFLAGS      = -pipe -O2 -Wall -W -D_REENTRANT $(DEFINES)
INCPATH       = -I/usr/local/mkspecs/linux-g++ -I. -I/usr/local/include/QtCore -I/usr/local/include/QtGui -I/usr/local/include -I/usr/local/fhe/include -I/usr/local/sw/include -I/usr/lib/mysql -I.
LINK          = g++
LFLAGS        = -Wl,-O1 -Wl,-rpath,/usr/local/lib
LIBS          = $(SUBLIBS)  -L/usr/local/lib -L/home/lhk/Desktop/FHE_HElib/ser_FHE/../../../../../usr/local/fhe/lib/ -lfhe -L/home/lhk/Desktop/FHE_HElib/ser_FHE/../../../../../usr/local/sw/lib/ -lntl -L/home/lhk/Desktop/FHE_HElib/ser_FHE/../../../../../usr/lib/mysql/ -lmysqlclient -lQtGui -L/usr/local/lib -L/usr/X11R6/lib -lQtCore -lpthread 
AR            = ar cqs
RANLIB        = 
QMAKE         = /usr/local/bin/qmake
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
STRIP         = strip
INSTALL_FILE  = install -m 644 -p
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = install -m 755 -p
DEL_FILE      = rm -f
SYMLINK       = ln -f -s
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = ./

####### Files

SOURCES       = ser_FHE.cpp 
OBJECTS       = ser_FHE.o
DIST          = /usr/local/mkspecs/common/unix.conf \
		/usr/local/mkspecs/common/linux.conf \
		/usr/local/mkspecs/common/gcc-base.conf \
		/usr/local/mkspecs/common/gcc-base-unix.conf \
		/usr/local/mkspecs/common/g++-base.conf \
		/usr/local/mkspecs/common/g++-unix.conf \
		/usr/local/mkspecs/qconfig.pri \
		/usr/local/mkspecs/features/qt_functions.prf \
		/usr/local/mkspecs/features/qt_config.prf \
		/usr/local/mkspecs/features/exclusive_builds.prf \
		/usr/local/mkspecs/features/default_pre.prf \
		/usr/local/mkspecs/features/release.prf \
		/usr/local/mkspecs/features/default_post.prf \
		/usr/local/mkspecs/features/unix/gdb_dwarf_index.prf \
		/usr/local/mkspecs/features/warn_on.prf \
		/usr/local/mkspecs/features/qt.prf \
		/usr/local/mkspecs/features/unix/thread.prf \
		/usr/local/mkspecs/features/moc.prf \
		/usr/local/mkspecs/features/resources.prf \
		/usr/local/mkspecs/features/uic.prf \
		/usr/local/mkspecs/features/yacc.prf \
		/usr/local/mkspecs/features/lex.prf \
		/usr/local/mkspecs/features/include_source_dir.prf \
		ser_FHE.pro
QMAKE_TARGET  = ser_FHE
DESTDIR       = 
TARGET        = ser_FHE

first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile $(TARGET)

$(TARGET): /home/lhk/Desktop/FHE_HElib/ser_FHE/../../../../../usr/local/fhe/lib/libfhe.a /home/lhk/Desktop/FHE_HElib/ser_FHE/../../../../../usr/local/sw/lib/libntl.a $(OBJECTS)  
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)

Makefile: ser_FHE.pro  /usr/local/mkspecs/linux-g++/qmake.conf /usr/local/mkspecs/common/unix.conf \
		/usr/local/mkspecs/common/linux.conf \
		/usr/local/mkspecs/common/gcc-base.conf \
		/usr/local/mkspecs/common/gcc-base-unix.conf \
		/usr/local/mkspecs/common/g++-base.conf \
		/usr/local/mkspecs/common/g++-unix.conf \
		/usr/local/mkspecs/qconfig.pri \
		/usr/local/mkspecs/features/qt_functions.prf \
		/usr/local/mkspecs/features/qt_config.prf \
		/usr/local/mkspecs/features/exclusive_builds.prf \
		/usr/local/mkspecs/features/default_pre.prf \
		/usr/local/mkspecs/features/release.prf \
		/usr/local/mkspecs/features/default_post.prf \
		/usr/local/mkspecs/features/unix/gdb_dwarf_index.prf \
		/usr/local/mkspecs/features/warn_on.prf \
		/usr/local/mkspecs/features/qt.prf \
		/usr/local/mkspecs/features/unix/thread.prf \
		/usr/local/mkspecs/features/moc.prf \
		/usr/local/mkspecs/features/resources.prf \
		/usr/local/mkspecs/features/uic.prf \
		/usr/local/mkspecs/features/yacc.prf \
		/usr/local/mkspecs/features/lex.prf \
		/usr/local/mkspecs/features/include_source_dir.prf \
		/usr/local/lib/libQtGui.prl \
		/usr/local/lib/libQtCore.prl
	$(QMAKE) -spec /usr/local/mkspecs/linux-g++ -o Makefile ser_FHE.pro
/usr/local/mkspecs/common/unix.conf:
/usr/local/mkspecs/common/linux.conf:
/usr/local/mkspecs/common/gcc-base.conf:
/usr/local/mkspecs/common/gcc-base-unix.conf:
/usr/local/mkspecs/common/g++-base.conf:
/usr/local/mkspecs/common/g++-unix.conf:
/usr/local/mkspecs/qconfig.pri:
/usr/local/mkspecs/features/qt_functions.prf:
/usr/local/mkspecs/features/qt_config.prf:
/usr/local/mkspecs/features/exclusive_builds.prf:
/usr/local/mkspecs/features/default_pre.prf:
/usr/local/mkspecs/features/release.prf:
/usr/local/mkspecs/features/default_post.prf:
/usr/local/mkspecs/features/unix/gdb_dwarf_index.prf:
/usr/local/mkspecs/features/warn_on.prf:
/usr/local/mkspecs/features/qt.prf:
/usr/local/mkspecs/features/unix/thread.prf:
/usr/local/mkspecs/features/moc.prf:
/usr/local/mkspecs/features/resources.prf:
/usr/local/mkspecs/features/uic.prf:
/usr/local/mkspecs/features/yacc.prf:
/usr/local/mkspecs/features/lex.prf:
/usr/local/mkspecs/features/include_source_dir.prf:
/usr/local/lib/libQtGui.prl:
/usr/local/lib/libQtCore.prl:
qmake:  FORCE
	@$(QMAKE) -spec /usr/local/mkspecs/linux-g++ -o Makefile ser_FHE.pro

dist: 
	@$(CHK_DIR_EXISTS) .tmp/ser_FHE1.0.0 || $(MKDIR) .tmp/ser_FHE1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) .tmp/ser_FHE1.0.0/ && $(COPY_FILE) --parents sock.h .tmp/ser_FHE1.0.0/ && $(COPY_FILE) --parents ser_FHE.cpp .tmp/ser_FHE1.0.0/ && (cd `dirname .tmp/ser_FHE1.0.0` && $(TAR) ser_FHE1.0.0.tar ser_FHE1.0.0 && $(COMPRESS) ser_FHE1.0.0.tar) && $(MOVE) `dirname .tmp/ser_FHE1.0.0`/ser_FHE1.0.0.tar.gz . && $(DEL_FILE) -r .tmp/ser_FHE1.0.0


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


check: first

mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all:
compiler_moc_header_clean:
compiler_rcc_make_all:
compiler_rcc_clean:
compiler_image_collection_make_all: qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all:
compiler_uic_clean:
compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: 

####### Compile

ser_FHE.o: ser_FHE.cpp /usr/local/fhe/include/FHE.h \
		/usr/local/fhe/include/DoubleCRT.h \
		/usr/local/fhe/include/NumbTh.h \
		/usr/local/sw/include/NTL/ZZ.h \
		/usr/local/sw/include/NTL/lip.h \
		/usr/local/sw/include/NTL/config.h \
		/usr/local/sw/include/NTL/mach_desc.h \
		/usr/local/sw/include/NTL/gmp_aux.h \
		/usr/local/sw/include/NTL/g_lip.h \
		/usr/local/sw/include/NTL/c_lip.h \
		/usr/local/sw/include/NTL/tools.h \
		/usr/local/sw/include/NTL/ctools.h \
		/usr/local/sw/include/NTL/vector.h \
		/usr/local/sw/include/NTL/SPMM_ASM.h \
		/usr/local/sw/include/NTL/ZZX.h \
		/usr/local/sw/include/NTL/vec_ZZ.h \
		/usr/local/sw/include/NTL/lzz_pX.h \
		/usr/local/sw/include/NTL/lzz_p.h \
		/usr/local/sw/include/NTL/FFT.h \
		/usr/local/sw/include/NTL/vec_long.h \
		/usr/local/sw/include/NTL/SmartPtr.h \
		/usr/local/sw/include/NTL/new.h \
		/usr/local/sw/include/NTL/thread.h \
		/usr/local/sw/include/NTL/LazyTable.h \
		/usr/local/sw/include/NTL/vec_lzz_p.h \
		/usr/local/sw/include/NTL/Lazy.h \
		/usr/local/sw/include/NTL/ZZ_pX.h \
		/usr/local/sw/include/NTL/ZZ_p.h \
		/usr/local/sw/include/NTL/ZZVec.h \
		/usr/local/sw/include/NTL/vec_ZZ_p.h \
		/usr/local/sw/include/NTL/xdouble.h \
		/usr/local/sw/include/NTL/mat_GF2.h \
		/usr/local/sw/include/NTL/matrix.h \
		/usr/local/sw/include/NTL/vec_vec_GF2.h \
		/usr/local/sw/include/NTL/vec_GF2.h \
		/usr/local/sw/include/NTL/WordVector.h \
		/usr/local/sw/include/NTL/GF2.h \
		/usr/local/sw/include/NTL/mat_GF2E.h \
		/usr/local/sw/include/NTL/vec_vec_GF2E.h \
		/usr/local/sw/include/NTL/vec_GF2E.h \
		/usr/local/sw/include/NTL/GF2E.h \
		/usr/local/sw/include/NTL/GF2X.h \
		/usr/local/sw/include/NTL/GF2XFactoring.h \
		/usr/local/sw/include/NTL/pair_GF2X_long.h \
		/usr/local/sw/include/NTL/pair.h \
		/usr/local/sw/include/NTL/mat_lzz_p.h \
		/usr/local/sw/include/NTL/vec_vec_lzz_p.h \
		/usr/local/sw/include/NTL/mat_lzz_pE.h \
		/usr/local/sw/include/NTL/vec_vec_lzz_pE.h \
		/usr/local/sw/include/NTL/vec_lzz_pE.h \
		/usr/local/sw/include/NTL/lzz_pE.h \
		/usr/local/sw/include/NTL/lzz_pXFactoring.h \
		/usr/local/sw/include/NTL/pair_lzz_pX_long.h \
		/usr/local/sw/include/NTL/GF2EX.h \
		/usr/local/sw/include/NTL/GF2XVec.h \
		/usr/local/sw/include/NTL/lzz_pEX.h \
		/usr/local/fhe/include/IndexMap.h \
		/usr/local/fhe/include/IndexSet.h \
		/usr/local/fhe/include/cloned_ptr.h \
		/usr/local/fhe/include/FHEContext.h \
		/usr/local/fhe/include/PAlgebra.h \
		/usr/local/fhe/include/CModulus.h \
		/usr/local/fhe/include/bluestein.h \
		/usr/local/fhe/include/recryption.h \
		/usr/local/fhe/include/AltCRT.h \
		/usr/local/fhe/include/Ctxt.h \
		/usr/local/fhe/include/EncryptedArray.h \
		/usr/local/fhe/include/timing.h \
		sock.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ser_FHE.o ser_FHE.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

