AC_PREREQ([2.69])
AC_INIT([main], [1.0], [https://github.com/Project-MAR])
AM_INIT_AUTOMAKE
AC_CONFIG_SRCDIR([src/main.c])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIRS([m4])

# Check for programs.
AC_PROG_CC


# Check for libraries.
LT_INIT
AC_ENABLE_SHARED
AC_DISABLE_STATIC

# Check for typedefs, structures and compiler characteristics.
AC_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_SIZE_T

# Output Makefile
AC_CONFIG_FILES([Makefile src/Makefile doc/Makefile examples/Makefile man/Makefile scripts/Makefile])
AC_OUTPUT
