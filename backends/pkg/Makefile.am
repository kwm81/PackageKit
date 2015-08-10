AM_CPPFLAGS = \
	-DG_LOG_DOMAIN=\"PackageKit-Pkg\"

plugindir = $(PK_PLUGIN_DIR)
plugin_LTLIBRARIES = libpk_backend_pkg.la

libpk_backend_pkg_la_SOURCES = \
			pk-backend-pkg.c
libpk_backend_pkg_la_CFLAGS = \
			$(PK_PLUGIN_CFLAGS) \
			$(WARNINGFLAGS_C) \
			$(LIBPKG_CFLAGS)
libpk_backend_pkg_la_LIBADD = \
			$(PK_PLUGIN_LIBS) \
			$(LIBPKG_LIBS)
libpk_backend_pkg_la_LDFLAGS = -module -avoid-version

-include $(top_srcdir)/git.mk
