#######################################
# The list of libraries we are building seperated by spaces.
# The 'lib_' indicates that these build products will be installed
# in the $(libdir) directory. For example /usr/lib
lib_LTLIBRARIES = libiex.la

#######################################
# Build information for each library

# Sources for libiex
libiex_la_SOURCES = iex.cpp

# Linker options libTestProgram
libiex_la_LDFLAGS = -lm -lz -lcurl -lcurlpp -ljsoncpp

# Compiler options. Here we are adding the include directory
# to be searched for headers included in the source code.
libiex_la_CPPFLAGS = -I$(top_srcdir)/include

