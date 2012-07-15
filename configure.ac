AC_INIT([OpenDPI], [1.3.0])
AC_CONFIG_SRCDIR([src/lib/ipq_protocols.h])

AM_INIT_AUTOMAKE([-Wall])
AC_CONFIG_MACRO_DIR([m4])
AC_PROG_LIBTOOL

AC_PROG_CC
AC_PROG_INSTALL

LT_INIT

AC_CHECK_HEADERS([netinet/in.h stdint.h stdlib.h string.h unistd.h])

AC_CONFIG_FILES([Makefile
		src/lib/Makefile
		src/include/Makefile
		src/examples/OpenDPI_demo/Makefile])
AC_OUTPUT
