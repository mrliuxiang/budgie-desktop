PKG_CHECK_MODULES(SHOW_DESKTOP_PLUGIN,
    libwnck-3.0 >= 3.14.0,
    [have_wnck=yes], [have_wnck=no]
)

AM_CONDITIONAL(ENABLE_SHOW_DESKTOP_PLUGIN, test x$have_wnck = xyes)
AC_CONFIG_FILES([src/panel/applets/show-desktop/Makefile])
