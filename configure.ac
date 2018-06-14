dnl Process this file with autoconf to produce a configure script.

AC_INIT([UC Berkeley Logic Optimization Espresso (1988)],
	    [1.2], [delp.gary@mayo.edu], [espresso88])

AM_INIT_AUTOMAKE([-Wall foreign std-options])autoconf
AM_CONFIG_HEADER([config.h])

dnl Checks for programs.
AC_PROG_CC

dnl Checks for libraries.

dnl Checks for header files.
AC_HEADER_STDC
AC_CHECK_HEADERS(limits.h sys/time.h unistd.h)

dnl Checks for typedefs, structures, and compiler characteristics.
AC_C_CONST
AC_TYPE_UID_T

dnl Checks for library functions.
AC_FUNC_MEMCMP
AC_CHECK_FUNCS(strcspn strerror strspn strstr)

AC_CONFIG_FILES([
	Makefile
	src/Makefile])
AC_OUTPUT
