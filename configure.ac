AC_PREREQ([2.60])
AC_INIT([dispad], [0.1])
AC_CONFIG_SRCDIR([Makefile.am])
AM_INIT_AUTOMAKE([foreign])
AM_MAINTAINER_MODE
AC_PROG_CC
AC_PROG_INSTALL
AC_CHECK_LIB([Xi], [XOpenDevice])
AC_CHECK_LIB([X11], [XOpenDisplay])
AC_CHECK_LIB([confuse], [cfg_init])
AC_CONFIG_FILES([Makefile src/Makefile])
AC_OUTPUT
