AUTOMAKE_OPTIONS = foreign
bindir = build
#Add libdir instead for adding library path for eg in /home/sfsf/sdwds/Desktop/
#Make an execuable
bin_PROGRAMS = helloworld


# PROGRAMS need to be built but scripts and data need not
# bin specifies that the file listed here namely helloworld 
# should be installed to the directory given by bindir


# Some ruby script you wanted to run , so specify rubydir and 
# ruby_DATA as the names of your programs

helloworld_SOURCES = main.c
helloworld_LDADD = /home/ishan/Desktop/libhello.so 
# or .a static library
# or so similar
# helloworld or the name of the program built


lib_LTLIBRARIES = libhelloworld.la
libhelloworld_la_SOURCES = main.c
libhelloworld_la_LDFLAGS = -version-info 0:0:0


#Why is .la for shared libs?
#-See README







# will make a .so file in /usr/local/lib
#usr/local/lib is libhelloworld.so        libhelloworld.so.0      libhelloworld.so.0.0.0





#For static library
#lib_LTLIBRARIES = libhelloworld.a
#libhelloworld_a_SOURCES = main.c
#libhelloworld_a_LDFLAGS = -version-info 0:0:0
