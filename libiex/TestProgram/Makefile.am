#######################################
# The list of executables we are building seperated by spaces
# the 'bin_' indicates that these build products will be installed
# in the $(bindir) directory. For example /usr/bin
#bin_PROGRAMS=exampleProgram

# Because a.out is only a sample program we don't want it to be installed.
# The 'noinst_' prefix indicates that the following targets are not to be
# installed.
noinst_PROGRAMS=TestProgram

#######################################
# Build information for each executable. The variable name is derived
# by use the name of the executable with each non alpha-numeric character is
# replaced by '_'. So a.out becomes a_out and the appropriate suffex added.
# '_SOURCES' for example.

ACLOCAL_AMFLAGS=-I ../m4

# Sources for the a.out 
TestProgram_SOURCES= examples.cpp

# Libraries for a.out
TestProgram_LDADD = $(top_srcdir)/libiex/libiex.la

# Linker options for a.out
TestProgram_LDFLAGS = -rpath `cd $(top_srcdir);pwd`/libiex/.libs -lm -lz -lcurl -lcurlpp -ljsoncpp

# Compiler options for a.out
TestProgram_CPPFLAGS = -I$(top_srcdir)/include