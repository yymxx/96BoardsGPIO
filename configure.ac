AC_INIT([96BoardsGPIO], [0.1])

AC_CONFIG_SRCDIR([lib/gpio.c])
AC_CONFIG_MACRO_DIR([config/m4])
AC_CONFIG_AUX_DIR([config/autoconf])

AM_PATH_PYTHON(2.7)

AC_CANONICAL_SYSTEM
AC_PROG_CC
AM_INIT_AUTOMAKE()
AM_PROG_CC_C_O

LT_INIT

AC_SEARCH_LIBS([libsoc_board_init, libsoc_board_gpio_id],[soc], , AC_MSG_ERROR(["Could not find libsoc library: https://github.com/jackmitch/libsoc"]))

AC_CONFIG_FILES(Makefile lib/Makefile examples/Makefile 96BoardsGPIO.pc)
AC_OUTPUT
