AC_INIT([xrectsel], [0.3.1])
AC_CONFIG_AUX_DIR([build-aux])
AM_INIT_AUTOMAKE([foreign subdir-objects -Wall -Werror])
AC_PROG_CC
AC_SEARCH_LIBS([XOpenDisplay], [X11], , [AC_MSG_ERROR([libx11 is required])])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([Makefile])
AC_OUTPUT
