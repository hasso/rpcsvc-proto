dnl Process this file with autoconf to produce a configure script.
AC_INIT(rpcsvc-proto, 1.4.1, kukuk@thkukuk.de)
AM_INIT_AUTOMAKE
AC_CONFIG_SRCDIR([rpcgen/rpc_main.c])
AM_CONFIG_HEADER(config.h)
AC_PREFIX_DEFAULT(/usr)

AC_SUBST(PACKAGE)
AC_SUBST(VERSION)

AC_PROG_CC
AC_GNU_SOURCE
AM_PROG_CC_C_O
AC_PROG_CPP
AC_ISC_POSIX
AC_PROG_INSTALL
AC_PROG_MAKE_SET

AM_GNU_GETTEXT([external])
AM_GNU_GETTEXT_VERSION([0.19.8])

AC_OUTPUT([Makefile rpcgen/Makefile rpcsvc/Makefile po/Makefile.in])
