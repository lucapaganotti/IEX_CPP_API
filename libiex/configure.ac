dnl Process this file with autoconf to produce a configure script.

AC_PREREQ(2.59)
AC_INIT(libiex, 1.0.1, [info@radair.org], [libiex], [http://www.radair.org])
dnl AC_PROG_CC
AC_PROG_CXX

AC_CANONICAL_SYSTEM

AC_CONFIG_MACRO_DIR([m4])

dnl Initialize automake
AM_INIT_AUTOMAKE

dnl this allows us specify individual liking flags for each target
AM_PROG_CC_C_O 

dnl Initialize Libtool
LT_INIT

AC_CONFIG_FILES(Makefile
                exampleProgram/Makefile
                TestProgram/Makefile
                libiex/Makefile
                include/Makefile)
AC_OUTPUT