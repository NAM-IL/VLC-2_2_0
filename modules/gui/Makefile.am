# modules/gui/Makefile.am automatically generated from modules/gui/Modules.am by modules/genmf
# DO NOT EDIT THIS FILE DIRECTLY! See Modules.am instead.

guidir = $(pluginsdir)/gui
gui_LTLIBRARIES =
EXTRA_LTLIBRARIES =

EXTRA_DIST = Modules.am

include $(top_srcdir)/modules/common.am
include $(srcdir)/Modules.am

if MAINTAINER_MODE
$(srcdir)/Makefile.am: $(srcdir)/Modules.am $(top_srcdir)/modules/genmf
	$(AM_V_GEN)cd \$(top_srcdir) && \$(SHELL) modules/genmf gui
endif

libncurses_plugin_la_SOURCES = $(SOURCES_ncurses)
libncurses_plugin_la_CPPFLAGS = $(AM_CPPFLAGS) $(CPPFLAGS_ncurses) 	-DMODULE_NAME_IS_ncurses
libncurses_plugin_la_CFLAGS = $(AM_CFLAGS) $(CFLAGS_ncurses)
libncurses_plugin_la_CXXFLAGS = $(AM_CXXFLAGS) $(CXXFLAGS_ncurses)
libncurses_plugin_la_OBJCFLAGS = $(AM_OBJCFLAGS) $(OBJCFLAGS_ncurses)
libncurses_plugin_la_LIBADD = $(LIBS_ncurses)
libncurses_plugin_la_LDFLAGS = $(AM_LDFLAGS) -rpath '$(guidir)' $(LDFLAGS_ncurses)
EXTRA_LTLIBRARIES += libncurses_plugin.la
gui_LTLIBRARIES += $(LTLIBncurses)
