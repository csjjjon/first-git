# Makefile.in generated by automake 1.14.1 from Makefile.am.
# extras/setup/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2013 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.







am__is_gnu_make = test -n '$(MAKEFILE_LIST)' && test -n '$(MAKELEVEL)'
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/scim
pkgincludedir = $(includedir)/scim
pkglibdir = $(libdir)/scim
pkglibexecdir = $(libexecdir)/scim
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = i586-pc-linux-gnu
host_triplet = i586-pc-linux-gnu
subdir = extras/setup
DIST_COMMON = $(srcdir)/Makefile.in $(srcdir)/Makefile.am \
	$(top_srcdir)/mkinstalldirs $(srcdir)/scim-setup.in \
	$(top_srcdir)/depcomp $(noinst_HEADERS)
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/m4/argz.m4 \
	$(top_srcdir)/m4/gettext.m4 $(top_srcdir)/m4/iconv.m4 \
	$(top_srcdir)/m4/lib-ld.m4 $(top_srcdir)/m4/lib-link.m4 \
	$(top_srcdir)/m4/lib-prefix.m4 $(top_srcdir)/m4/libtool.m4 \
	$(top_srcdir)/m4/ltdl.m4 $(top_srcdir)/m4/ltoptions.m4 \
	$(top_srcdir)/m4/ltsugar.m4 $(top_srcdir)/m4/ltversion.m4 \
	$(top_srcdir)/m4/lt~obsolete.m4 $(top_srcdir)/m4/nls.m4 \
	$(top_srcdir)/m4/po.m4 $(top_srcdir)/m4/progtest.m4 \
	$(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES = scim-setup
CONFIG_CLEAN_VPATH_FILES =
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__uninstall_files_from_dir = { \
  test -z "$$files" \
    || { test ! -d "$$dir" && test ! -f "$$dir" && test ! -r "$$dir"; } \
    || { echo " ( cd '$$dir' && rm -f" $$files ")"; \
         $(am__cd) "$$dir" && rm -f $$files; }; \
  }
am__installdirs = "$(DESTDIR)$(moduledir)" "$(DESTDIR)$(bindir)" \
	"$(DESTDIR)$(desktopdir)" "$(DESTDIR)$(gnomeccdir)"
LTLIBRARIES = $(module_LTLIBRARIES)
setup_la_DEPENDENCIES = $(top_builddir)/src/libscim-1.0.la
am_setup_la_OBJECTS = setup_la-scim_setup_ui.lo \
	setup_la-scim_setup_module.lo setup_la-scim_setup_helper.lo
setup_la_OBJECTS = $(am_setup_la_OBJECTS)
AM_V_lt = $(am__v_lt_$(V))
am__v_lt_ = $(am__v_lt_$(AM_DEFAULT_VERBOSITY))
am__v_lt_0 = --silent
am__v_lt_1 = 
setup_la_LINK = $(LIBTOOL) $(AM_V_lt) --tag=CXX $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CXXLD) $(setup_la_CXXFLAGS) \
	$(CXXFLAGS) $(setup_la_LDFLAGS) $(LDFLAGS) -o $@
am_setup_la_rpath = -rpath $(moduledir)
SCRIPTS = $(bin_SCRIPTS)
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
DEFAULT_INCLUDES = -I. -I$(top_builddir)
depcomp = $(SHELL) $(top_srcdir)/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
CXXCOMPILE = $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CXXFLAGS) $(CXXFLAGS)
LTCXXCOMPILE = $(LIBTOOL) $(AM_V_lt) --tag=CXX $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=compile $(CXX) $(DEFS) \
	$(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) \
	$(AM_CXXFLAGS) $(CXXFLAGS)
AM_V_CXX = $(am__v_CXX_$(V))
am__v_CXX_ = $(am__v_CXX_$(AM_DEFAULT_VERBOSITY))
am__v_CXX_0 = @echo "  CXX     " $@;
am__v_CXX_1 = 
CXXLD = $(CXX)
CXXLINK = $(LIBTOOL) $(AM_V_lt) --tag=CXX $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CXXLD) $(AM_CXXFLAGS) \
	$(CXXFLAGS) $(AM_LDFLAGS) $(LDFLAGS) -o $@
AM_V_CXXLD = $(am__v_CXXLD_$(V))
am__v_CXXLD_ = $(am__v_CXXLD_$(AM_DEFAULT_VERBOSITY))
am__v_CXXLD_0 = @echo "  CXXLD   " $@;
am__v_CXXLD_1 = 
SOURCES = $(setup_la_SOURCES)
DIST_SOURCES = $(setup_la_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
DATA = $(desktop_DATA) $(gnomecc_DATA)
HEADERS = $(noinst_HEADERS)
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
# Read a list of newline-separated strings from the standard input,
# and print each of them once, without duplicates.  Input order is
# *not* preserved.
am__uniquify_input = $(AWK) '\
  BEGIN { nonempty = 0; } \
  { items[$$0] = 1; nonempty = 1; } \
  END { if (nonempty) { for (i in items) print i; }; } \
'
# Make sure the list of sources is unique.  This is necessary because,
# e.g., the same source file might be shared among _SOURCES variables
# for different programs/libraries.
am__define_uniq_tagged_files = \
  list='$(am__tagged_files)'; \
  unique=`for i in $$list; do \
    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
  done | $(am__uniquify_input)`
ETAGS = etags
CTAGS = ctags
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/user/workspace/scim-jessie-version-important/scim/scim-1.4.15/missing aclocal-1.14
ALL_LINGUAS = as bn_IN ca cs de es fi fr gu hi it ja kn ko ml mr nl pa pt_BR ru sk sv ta te vi zh_CN zh_TW
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 1
AR = ar
ARGZ_H = 
AUTOCONF = ${SHELL} /home/user/workspace/scim-jessie-version-important/scim/scim-1.4.15/missing autoconf
AUTOHEADER = ${SHELL} /home/user/workspace/scim-jessie-version-important/scim/scim-1.4.15/missing autoheader
AUTOMAKE = ${SHELL} /home/user/workspace/scim-jessie-version-important/scim/scim-1.4.15/missing automake-1.14
AWK = gawk
CC = gcc
CCDEPMODE = depmode=none
CFLAGS = -g -O2 -fstack-protector-strong -Wformat -Werror=format-security
CLUTTERIMCONTEXT_CFLAGS = -pthread -I/usr/local/include -I/usr/include/clutter-imcontext-0.1 -I/usr/include/clutter-1.0 -I/usr/include/cogl -I/usr/include/atk-1.0 -I/usr/include/cogl -I/usr/include/libdrm -I/usr/include/json-glib-1.0 -I/usr/include/gtk-3.0 -I/usr/include/gio-unix-2.0/ -I/usr/include/cairo -I/usr/include/pango-1.0 -I/usr/include/harfbuzz -I/usr/include/pango-1.0 -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/libpng12 -I/usr/include/cairo -I/usr/include/pixman-1 -I/usr/include/freetype2 -I/usr/include/libpng12 -I/usr/include/glib-2.0 -I/usr/lib/i386-linux-gnu/glib-2.0/include 
CLUTTERIMCONTEXT_LIBS = -lclutter-imcontext-0.1 -lclutter-1.0 -lcogl-path -latk-1.0 -lcogl-pango -lcogl -lgmodule-2.0 -pthread -lwayland-egl -lgbm -ldrm -lEGL -lXrandr -ljson-glib-1.0 -lgio-2.0 -lgdk-3 -lpangocairo-1.0 -lpango-1.0 -lgdk_pixbuf-2.0 -lcairo-gobject -lcairo -lgobject-2.0 -lglib-2.0 -lwayland-cursor -lwayland-client -lxkbcommon -lwayland-server -lX11 -lXext -lXdamage -lXfixes -lXcomposite -lXi 
CLUTTER_CFLAGS = -pthread -I/usr/local/include -I/usr/include/clutter-1.0 -I/usr/include/cogl -I/usr/include/atk-1.0 -I/usr/include/cogl -I/usr/include/libdrm -I/usr/include/json-glib-1.0 -I/usr/include/gtk-3.0 -I/usr/include/gio-unix-2.0/ -I/usr/include/cairo -I/usr/include/pango-1.0 -I/usr/include/harfbuzz -I/usr/include/pango-1.0 -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/libpng12 -I/usr/include/cairo -I/usr/include/pixman-1 -I/usr/include/freetype2 -I/usr/include/libpng12 -I/usr/include/glib-2.0 -I/usr/lib/i386-linux-gnu/glib-2.0/include 
CLUTTER_IM_MODULEDIR = /usr/lib/i386-linux-gnu/clutter-imcontext/immodules
CLUTTER_LIBS = -lclutter-1.0 -lcogl-path -latk-1.0 -lcogl-pango -lcogl -lgmodule-2.0 -pthread -lwayland-egl -lgbm -ldrm -lEGL -lXrandr -ljson-glib-1.0 -lgio-2.0 -lgdk-3 -lpangocairo-1.0 -lpango-1.0 -lgdk_pixbuf-2.0 -lcairo-gobject -lcairo -lgobject-2.0 -lglib-2.0 -lwayland-cursor -lwayland-client -lxkbcommon -lwayland-server -lX11 -lXext -lXdamage -lXfixes -lXcomposite -lXi 
CPP = gcc -E
CPPFLAGS = -D_FORTIFY_SOURCE=2
CXX = g++
CXXCPP = g++ -E
CXXDEPMODE = depmode=none
CXXFLAGS = -g -O2 -fstack-protector-strong -Wformat -Werror=format-security
CYGPATH_W = echo
DATADIRNAME = share
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DLLTOOL = false
DOCBOOK_XSL = no
DOT = 
DOXYGEN = /usr/bin/doxygen
DSYMUTIL = 
DUMPBIN = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
EXEEXT = 
FGREP = /bin/grep -F
GETTEXT_PACKAGE = scim
GMSGFMT = /usr/bin/msgfmt
GREP = /bin/grep
GTHREAD2_CFLAGS = -pthread -I/usr/local/include -I/usr/include/glib-2.0 -I/usr/lib/i386-linux-gnu/glib-2.0/include 
GTHREAD2_LIBS = -lgthread-2.0 -pthread -lglib-2.0 
GTK2_CFLAGS = -pthread -I/usr/local/include -I/usr/include/gtk-2.0 -I/usr/lib/i386-linux-gnu/gtk-2.0/include -I/usr/include/gio-unix-2.0/ -I/usr/include/cairo -I/usr/include/pango-1.0 -I/usr/include/atk-1.0 -I/usr/include/cairo -I/usr/include/pixman-1 -I/usr/include/libpng12 -I/usr/include/pango-1.0 -I/usr/include/harfbuzz -I/usr/include/freetype2 -I/usr/include/pango-1.0 -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/libpng12 -I/usr/include/glib-2.0 -I/usr/lib/i386-linux-gnu/glib-2.0/include 
GTK2_IM_MODULEDIR = /usr/lib/i386-linux-gnu/gtk-2.0/2.10.0/immodules
GTK2_LIBS = -lgtk-x11-2.0 -lgdk-x11-2.0 -lpangocairo-1.0 -latk-1.0 -lcairo -lgio-2.0 -lpangoft2-1.0 -lfontconfig -lfreetype -lpango-1.0 -lgdk_pixbuf-2.0 -lgobject-2.0 -lglib-2.0 
GTK3_CFLAGS = -pthread -I/usr/local/include -I/usr/include/gtk-3.0 -I/usr/include/at-spi2-atk/2.0 -I/usr/include/at-spi-2.0 -I/usr/include/dbus-1.0 -I/usr/lib/i386-linux-gnu/dbus-1.0/include -I/usr/include/gtk-3.0 -I/usr/include/gio-unix-2.0/ -I/usr/include/cairo -I/usr/include/pango-1.0 -I/usr/include/harfbuzz -I/usr/include/pango-1.0 -I/usr/include/atk-1.0 -I/usr/include/cairo -I/usr/include/pixman-1 -I/usr/include/freetype2 -I/usr/include/libpng12 -I/usr/include/pango-1.0 -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/libpng12 -I/usr/include/glib-2.0 -I/usr/lib/i386-linux-gnu/glib-2.0/include 
GTK3_IM_MODULEDIR = /usr/lib/i386-linux-gnu/gtk-3.0/3.0.0/immodules
GTK3_LIBS = -lgtk-3 -lgdk-3 -lpangocairo-1.0 -latk-1.0 -lcairo-gobject -lcairo -lgio-2.0 -lpango-1.0 -lgdk_pixbuf-2.0 -lgobject-2.0 -lglib-2.0 
GTK_BINARY_VERSION = 3.0.0
GTK_CFLAGS = -pthread -I/usr/local/include -I/usr/include/gtk-3.0 -I/usr/include/at-spi2-atk/2.0 -I/usr/include/at-spi-2.0 -I/usr/include/dbus-1.0 -I/usr/lib/i386-linux-gnu/dbus-1.0/include -I/usr/include/gtk-3.0 -I/usr/include/gio-unix-2.0/ -I/usr/include/cairo -I/usr/include/pango-1.0 -I/usr/include/harfbuzz -I/usr/include/pango-1.0 -I/usr/include/atk-1.0 -I/usr/include/cairo -I/usr/include/pixman-1 -I/usr/include/freetype2 -I/usr/include/libpng12 -I/usr/include/pango-1.0 -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/libpng12 -I/usr/include/glib-2.0 -I/usr/lib/i386-linux-gnu/glib-2.0/include 
GTK_LIBDIR = /usr/lib/i386-linux-gnu
GTK_LIBS = -lgtk-3 -lgdk-3 -lpangocairo-1.0 -latk-1.0 -lcairo-gobject -lcairo -lgio-2.0 -lpango-1.0 -lgdk_pixbuf-2.0 -lgobject-2.0 -lglib-2.0 
GTK_MAJOR_VERSION = 3
GTK_VERSION = 3.0.0
HAVE_GRAPHVIZ = NO
INCLTDL = 
INCLUDE_STDINT = #include <stdint.h>
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
INTLLIBS = 
INTLTOOL_EXTRACT = /usr/bin/intltool-extract
INTLTOOL_MERGE = /usr/bin/intltool-merge
INTLTOOL_PERL = /usr/bin/perl
INTLTOOL_UPDATE = /usr/bin/intltool-update
INTLTOOL_V_MERGE = $(INTLTOOL__v_MERGE_$(V))
INTLTOOL_V_MERGE_OPTIONS = $(intltool__v_merge_options_$(V))
INTLTOOL__v_MERGE_ = $(INTLTOOL__v_MERGE_$(AM_DEFAULT_VERBOSITY))
INTLTOOL__v_MERGE_0 = @echo "  ITMRG " $@;
LD = /usr/bin/ld
LDFLAGS = -Wl,-z,relro
LIBADD_DL = -ldl 
LIBADD_DLD_LINK = 
LIBADD_DLOPEN = -ldl
LIBADD_SHL_LOAD = 
LIBICONV = 
LIBINTL = 
LIBLTDL = -lltdl
LIBOBJS = 
LIBS = -ldl 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIBTOOL_DEPS = ./ltmain.sh
LIBTOOL_EXPORT_OPTIONS = 
LIPO = 
LN_S = ln -s
LTDLDEPS = 
LTDLINCL = 
LTDLOPEN = libltdl
LTLIBICONV = 
LTLIBINTL = 
LTLIBOBJS = 
LT_CONFIG_H = config.h
LT_DLLOADERS =  libltdl/dlopen.la
LT_DLPREOPEN = -dlpreopen libltdl/dlopen.la 
MAKEINFO = ${SHELL} /home/user/workspace/scim-jessie-version-important/scim/scim-1.4.15/missing makeinfo
MANIFEST_TOOL = :
MKDIR_P = /bin/mkdir -p
MKINSTALLDIRS = $(top_builddir)/./mkinstalldirs
MSGFMT = /usr/bin/msgfmt
MSGMERGE = /usr/bin/msgmerge
NM = /usr/bin/nm -B
NMEDIT = 
OBJDUMP = objdump
OBJEXT = o
OTOOL = 
OTOOL64 = 
PACKAGE = scim
PACKAGE_BUGREPORT = https://github.com/scim-im/scim
PACKAGE_NAME = scim
PACKAGE_STRING = scim 1.4.15
PACKAGE_TARNAME = scim
PACKAGE_URL = 
PACKAGE_VERSION = 1.4.15
PATH_SEPARATOR = :
PERL = /usr/bin/perl
PKG_CONFIG = /usr/bin/pkg-config
PKG_CONFIG_LIBDIR = 
PKG_CONFIG_PATH = 
POSUB = po
QT3_CFLAGS = 
QT3_IM_MODULEDIR = 
QT3_LIBDIR = 
QT3_LIBS = 
QT3_MOC = 
QT3_PREFIX = 
QT4_CFLAGS = -DQT_SHARED -I/usr/include/qt4 -I/usr/include/qt4/QtGui -I/usr/include/qt4 -I/usr/include/qt4/QtCore 
QT4_IM_MODULEDIR = /usr/lib/i386-linux-gnu/qt4/plugins/inputmethods
QT4_LIBDIR = /usr/lib/i386-linux-gnu
QT4_LIBS = -lQtGui -lQtCore 
QT4_MOC = /usr/bin/moc
QT4_PREFIX = /usr
RANLIB = ranlib
SCIM_AGE = 2
SCIM_BINARY_VERSION = 1.4.0
SCIM_BRIDGE_MAJOR_VERSION = 1
SCIM_BRIDGE_MICRO_VERSION = 15
SCIM_BRIDGE_MINOR_VERSION = 4
SCIM_BRIDGE_VERSION = 1.4.15
SCIM_BUILD_CLUTTER_IMMODULE = 1
SCIM_BUILD_CONFIG_SIMPLE = 1
SCIM_BUILD_CONFIG_SOCKET = 1
SCIM_BUILD_DOCUMENTS = 
SCIM_BUILD_FILTER_SCTC = 1
SCIM_BUILD_FRONTEND_SOCKET = 1
SCIM_BUILD_FRONTEND_X11 = 1
SCIM_BUILD_GTK2_IMMODULE = 1
SCIM_BUILD_GTK3_IMMODULE = 1
SCIM_BUILD_GTK_UTILS = 1
SCIM_BUILD_IMENGINE_RAWCODE = 1
SCIM_BUILD_IMENGINE_SOCKET = 1
SCIM_BUILD_IMENGINE_TABLE = 
SCIM_BUILD_IMMODULE = 1
SCIM_BUILD_IM_AGENT = 1
SCIM_BUILD_ORIG_GTK2_IMMODULE = 0
SCIM_BUILD_ORIG_GTK3_IMMODULE = 0
SCIM_BUILD_PANEL_GTK = 1
SCIM_BUILD_QT3_IMMODULE = 0
SCIM_BUILD_QT4_IMMODULE = 1
SCIM_BUILD_SCIM_SETUP = 1
SCIM_BUILD_TESTS = 0
SCIM_BUILD_X11_UTILS = 1
SCIM_CURRENT = 10
SCIM_DATADIR = ${datarootdir}/scim
SCIM_EPOCH = -1.0
SCIM_ICONDIR = ${datarootdir}/scim/icons
SCIM_LIBDIR = ${prefix}/lib/i386-linux-gnu
SCIM_LIBEXECDIR = ${prefix}/lib/i386-linux-gnu/scim-1.0
SCIM_LOCALEDIR = ${datarootdir}/locale
SCIM_LTDLADVISE = 0
SCIM_MAJOR_VERSION = 1
SCIM_MICRO_VERSION = 15
SCIM_MINOR_VERSION = 4
SCIM_MODULE_PATH = ${prefix}/lib/i386-linux-gnu/scim-1.0
SCIM_PREFIX = /usr
SCIM_REVISION = 6
SCIM_SYSCONFDIR = /etc
SCIM_TEMPDIR = /tmp
SCIM_VERSION = 1.4.15
SED = /bin/sed
SET_MAKE = 
SHELL = /bin/bash
STRIP = strip
UINT16 = uint16_t
UINT32 = uint32_t
UINT64 = uint64_t
USE_NLS = yes
VERSION = 1.4.15
XGETTEXT = /usr/bin/xgettext
XMKMF = 
XSLTPROC = /usr/bin/xsltproc
X_CFLAGS = 
X_EXTRA_LIBS = 
X_LIBS =  -lX11
X_PRE_LIBS =  -lSM -lICE
abs_builddir = /home/user/workspace/scim-jessie-version-important/scim/scim-1.4.15/extras/setup
abs_srcdir = /home/user/workspace/scim-jessie-version-important/scim/scim-1.4.15/extras/setup
abs_top_builddir = /home/user/workspace/scim-jessie-version-important/scim/scim-1.4.15
abs_top_srcdir = /home/user/workspace/scim-jessie-version-important/scim/scim-1.4.15
ac_aux_dir = .
ac_ct_AR = ar
ac_ct_CC = gcc
ac_ct_CXX = g++
ac_ct_DUMPBIN = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build = i586-pc-linux-gnu
build_alias = i586-linux-gnu
build_cpu = i586
build_os = linux-gnu
build_vendor = pc
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = i586-pc-linux-gnu
host_alias = 
host_cpu = i586
host_os = linux-gnu
host_vendor = pc
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${prefix}/share/info
install_sh = ${SHELL} /home/user/workspace/scim-jessie-version-important/scim/scim-1.4.15/install-sh
intltool__v_merge_options_ = $(intltool__v_merge_options_$(AM_DEFAULT_VERBOSITY))
intltool__v_merge_options_0 = -q
libdir = ${prefix}/lib/i386-linux-gnu
libexecdir = ${prefix}/lib/i386-linux-gnu
localedir = ${datarootdir}/locale
localstatedir = /var
ltdl_LIBOBJS =  lt__strl.o
ltdl_LTLIBOBJS =  lt__strl.lo
mandir = ${prefix}/share/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
subdirs =  libltdl
sys_symbol_underscore = no
sysconfdir = /etc
target_alias = 
top_build_prefix = ../../
top_builddir = ../..
top_srcdir = ../..
MAINTAINERCLEANFILES = Makefile.in
CLEANFILES = *.bak scim-setup.desktop scim-setup
AM_CPPFLAGS = -I$(top_builddir) \
			  -I$(top_builddir)/src \
	    	  -I$(top_srcdir) \
			  -I$(top_srcdir)/src \
			  -I$(top_srcdir)/intl \
			  -DSCIM_DATADIR=\"${datarootdir}/scim\" \
			  -DSCIM_LOCALEDIR=\"${datarootdir}/locale\" \
			  -DSCIM_SYSCONFDIR=\"/etc\" \
			  -DSCIM_LIBEXECDIR=\"${prefix}/lib/i386-linux-gnu/scim-1.0\" \
			  -DSCIM_ICONDIR=\"${datarootdir}/scim/icons\" \
			  -DSCIM_MODULE_PATH=\"${prefix}/lib/i386-linux-gnu/scim-1.0\" \
			  -DSCIM_TEMPDIR=\"/tmp\"

noinst_HEADERS = scim_setup_module.h \
			  scim_setup_ui.h

CONFIG_SCIM_SETUP = scim-setup
CONFIG_SCIM_SETUP_HELPER = setup.la
bin_SCRIPTS = $(CONFIG_SCIM_SETUP)
moduledir = $(libdir)/scim-1.0/$(SCIM_BINARY_VERSION)/Helper
module_LTLIBRARIES = $(CONFIG_SCIM_SETUP_HELPER)
setup_la_SOURCES = scim_setup_ui.cpp \
			  scim_setup_module.cpp \
			  scim_setup_helper.cpp

setup_la_CXXFLAGS = -pthread -I/usr/local/include -I/usr/include/gtk-3.0 -I/usr/include/at-spi2-atk/2.0 -I/usr/include/at-spi-2.0 -I/usr/include/dbus-1.0 -I/usr/lib/i386-linux-gnu/dbus-1.0/include -I/usr/include/gtk-3.0 -I/usr/include/gio-unix-2.0/ -I/usr/include/cairo -I/usr/include/pango-1.0 -I/usr/include/harfbuzz -I/usr/include/pango-1.0 -I/usr/include/atk-1.0 -I/usr/include/cairo -I/usr/include/pixman-1 -I/usr/include/freetype2 -I/usr/include/libpng12 -I/usr/include/pango-1.0 -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/libpng12 -I/usr/include/glib-2.0 -I/usr/lib/i386-linux-gnu/glib-2.0/include 
setup_la_LDFLAGS = -avoid-version \
		     	  -rpath $(moduledir) \
			  -module \
			   \
			  -lgtk-3 -lgdk-3 -lpangocairo-1.0 -latk-1.0 -lcairo-gobject -lcairo -lgio-2.0 -lpango-1.0 -lgdk_pixbuf-2.0 -lgobject-2.0 -lglib-2.0  \
			  

setup_la_LIBADD = $(top_builddir)/src/libscim-1.0.la
desktopdir = $(datadir)/applications
desktop_in_files = scim-setup.desktop.in
desktop_DATA = $(desktop_in_files:.desktop.in=.desktop)
gnomeccdir = $(datadir)/control-center-2.0/capplets
gnomecc_DATA = $(desktop_in_files:.desktop.in=.desktop)
EXTRA_DIST = $(desktop_in_files) scim-setup.in
all: all-am

.SUFFIXES:
.SUFFIXES: .cpp .lo .o .obj
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --gnu extras/setup/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --gnu extras/setup/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure:  $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
scim-setup: $(top_builddir)/config.status $(srcdir)/scim-setup.in
	cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@

install-moduleLTLIBRARIES: $(module_LTLIBRARIES)
	@$(NORMAL_INSTALL)
	@list='$(module_LTLIBRARIES)'; test -n "$(moduledir)" || list=; \
	list2=; for p in $$list; do \
	  if test -f $$p; then \
	    list2="$$list2 $$p"; \
	  else :; fi; \
	done; \
	test -z "$$list2" || { \
	  echo " $(MKDIR_P) '$(DESTDIR)$(moduledir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(moduledir)" || exit 1; \
	  echo " $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL) $(INSTALL_STRIP_FLAG) $$list2 '$(DESTDIR)$(moduledir)'"; \
	  $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL) $(INSTALL_STRIP_FLAG) $$list2 "$(DESTDIR)$(moduledir)"; \
	}

uninstall-moduleLTLIBRARIES:
	@$(NORMAL_UNINSTALL)
	@list='$(module_LTLIBRARIES)'; test -n "$(moduledir)" || list=; \
	for p in $$list; do \
	  $(am__strip_dir) \
	  echo " $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=uninstall rm -f '$(DESTDIR)$(moduledir)/$$f'"; \
	  $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=uninstall rm -f "$(DESTDIR)$(moduledir)/$$f"; \
	done

clean-moduleLTLIBRARIES:
	-test -z "$(module_LTLIBRARIES)" || rm -f $(module_LTLIBRARIES)
	@list='$(module_LTLIBRARIES)'; \
	locs=`for p in $$list; do echo $$p; done | \
	      sed 's|^[^/]*$$|.|; s|/[^/]*$$||; s|$$|/so_locations|' | \
	      sort -u`; \
	test -z "$$locs" || { \
	  echo rm -f $${locs}; \
	  rm -f $${locs}; \
	}

setup.la: $(setup_la_OBJECTS) $(setup_la_DEPENDENCIES) $(EXTRA_setup_la_DEPENDENCIES) 
	$(AM_V_CXXLD)$(setup_la_LINK) $(am_setup_la_rpath) $(setup_la_OBJECTS) $(setup_la_LIBADD) $(LIBS)
install-binSCRIPTS: $(bin_SCRIPTS)
	@$(NORMAL_INSTALL)
	@list='$(bin_SCRIPTS)'; test -n "$(bindir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(bindir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(bindir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  if test -f "$$d$$p"; then echo "$$d$$p"; echo "$$p"; else :; fi; \
	done | \
	sed -e 'p;s,.*/,,;n' \
	    -e 'h;s|.*|.|' \
	    -e 'p;x;s,.*/,,;$(transform)' | sed 'N;N;N;s,\n, ,g' | \
	$(AWK) 'BEGIN { files["."] = ""; dirs["."] = 1; } \
	  { d=$$3; if (dirs[d] != 1) { print "d", d; dirs[d] = 1 } \
	    if ($$2 == $$4) { files[d] = files[d] " " $$1; \
	      if (++n[d] == $(am__install_max)) { \
		print "f", d, files[d]; n[d] = 0; files[d] = "" } } \
	    else { print "f", d "/" $$4, $$1 } } \
	  END { for (d in files) print "f", d, files[d] }' | \
	while read type dir files; do \
	     if test "$$dir" = .; then dir=; else dir=/$$dir; fi; \
	     test -z "$$files" || { \
	       echo " $(INSTALL_SCRIPT) $$files '$(DESTDIR)$(bindir)$$dir'"; \
	       $(INSTALL_SCRIPT) $$files "$(DESTDIR)$(bindir)$$dir" || exit $$?; \
	     } \
	; done

uninstall-binSCRIPTS:
	@$(NORMAL_UNINSTALL)
	@list='$(bin_SCRIPTS)'; test -n "$(bindir)" || exit 0; \
	files=`for p in $$list; do echo "$$p"; done | \
	       sed -e 's,.*/,,;$(transform)'`; \
	dir='$(DESTDIR)$(bindir)'; $(am__uninstall_files_from_dir)

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

#include ./$(DEPDIR)/setup_la-scim_setup_helper.Plo
#include ./$(DEPDIR)/setup_la-scim_setup_module.Plo
#include ./$(DEPDIR)/setup_la-scim_setup_ui.Plo

.cpp.o:
#	$(AM_V_CXX)$(CXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
#	$(AM_V_at)$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	$(AM_V_CXX)source='$<' object='$@' libtool=no 
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) 
	$(AM_V_CXX)$(CXXCOMPILE) -c -o $@ $<

.cpp.obj:
#	$(AM_V_CXX)$(CXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
#	$(AM_V_at)$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	$(AM_V_CXX)source='$<' object='$@' libtool=no 
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) 
	$(AM_V_CXX)$(CXXCOMPILE) -c -o $@ `$(CYGPATH_W) '$<'`

.cpp.lo:
#	$(AM_V_CXX)$(LTCXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
#	$(AM_V_at)$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Plo
#	$(AM_V_CXX)source='$<' object='$@' libtool=yes 
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) 
	$(AM_V_CXX)$(LTCXXCOMPILE) -c -o $@ $<

setup_la-scim_setup_ui.lo: scim_setup_ui.cpp
#	$(AM_V_CXX)$(LIBTOOL) $(AM_V_lt) --tag=CXX $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(setup_la_CXXFLAGS) $(CXXFLAGS) -MT setup_la-scim_setup_ui.lo -MD -MP -MF $(DEPDIR)/setup_la-scim_setup_ui.Tpo -c -o setup_la-scim_setup_ui.lo `test -f 'scim_setup_ui.cpp' || echo '$(srcdir)/'`scim_setup_ui.cpp
#	$(AM_V_at)$(am__mv) $(DEPDIR)/setup_la-scim_setup_ui.Tpo $(DEPDIR)/setup_la-scim_setup_ui.Plo
#	$(AM_V_CXX)source='scim_setup_ui.cpp' object='setup_la-scim_setup_ui.lo' libtool=yes 
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) 
	$(AM_V_CXX)$(LIBTOOL) $(AM_V_lt) --tag=CXX $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(setup_la_CXXFLAGS) $(CXXFLAGS) -c -o setup_la-scim_setup_ui.lo `test -f 'scim_setup_ui.cpp' || echo '$(srcdir)/'`scim_setup_ui.cpp

setup_la-scim_setup_module.lo: scim_setup_module.cpp
#	$(AM_V_CXX)$(LIBTOOL) $(AM_V_lt) --tag=CXX $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(setup_la_CXXFLAGS) $(CXXFLAGS) -MT setup_la-scim_setup_module.lo -MD -MP -MF $(DEPDIR)/setup_la-scim_setup_module.Tpo -c -o setup_la-scim_setup_module.lo `test -f 'scim_setup_module.cpp' || echo '$(srcdir)/'`scim_setup_module.cpp
#	$(AM_V_at)$(am__mv) $(DEPDIR)/setup_la-scim_setup_module.Tpo $(DEPDIR)/setup_la-scim_setup_module.Plo
#	$(AM_V_CXX)source='scim_setup_module.cpp' object='setup_la-scim_setup_module.lo' libtool=yes 
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) 
	$(AM_V_CXX)$(LIBTOOL) $(AM_V_lt) --tag=CXX $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(setup_la_CXXFLAGS) $(CXXFLAGS) -c -o setup_la-scim_setup_module.lo `test -f 'scim_setup_module.cpp' || echo '$(srcdir)/'`scim_setup_module.cpp

setup_la-scim_setup_helper.lo: scim_setup_helper.cpp
#	$(AM_V_CXX)$(LIBTOOL) $(AM_V_lt) --tag=CXX $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(setup_la_CXXFLAGS) $(CXXFLAGS) -MT setup_la-scim_setup_helper.lo -MD -MP -MF $(DEPDIR)/setup_la-scim_setup_helper.Tpo -c -o setup_la-scim_setup_helper.lo `test -f 'scim_setup_helper.cpp' || echo '$(srcdir)/'`scim_setup_helper.cpp
#	$(AM_V_at)$(am__mv) $(DEPDIR)/setup_la-scim_setup_helper.Tpo $(DEPDIR)/setup_la-scim_setup_helper.Plo
#	$(AM_V_CXX)source='scim_setup_helper.cpp' object='setup_la-scim_setup_helper.lo' libtool=yes 
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) 
	$(AM_V_CXX)$(LIBTOOL) $(AM_V_lt) --tag=CXX $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=compile $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(setup_la_CXXFLAGS) $(CXXFLAGS) -c -o setup_la-scim_setup_helper.lo `test -f 'scim_setup_helper.cpp' || echo '$(srcdir)/'`scim_setup_helper.cpp

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs
install-desktopDATA: $(desktop_DATA)
	@$(NORMAL_INSTALL)
	@list='$(desktop_DATA)'; test -n "$(desktopdir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(desktopdir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(desktopdir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(desktopdir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(desktopdir)" || exit $$?; \
	done

uninstall-desktopDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(desktop_DATA)'; test -n "$(desktopdir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(desktopdir)'; $(am__uninstall_files_from_dir)
install-gnomeccDATA: $(gnomecc_DATA)
	@$(NORMAL_INSTALL)
	@list='$(gnomecc_DATA)'; test -n "$(gnomeccdir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(gnomeccdir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(gnomeccdir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(gnomeccdir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(gnomeccdir)" || exit $$?; \
	done

uninstall-gnomeccDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(gnomecc_DATA)'; test -n "$(gnomeccdir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(gnomeccdir)'; $(am__uninstall_files_from_dir)

ID: $(am__tagged_files)
	$(am__define_uniq_tagged_files); mkid -fID $$unique
tags: tags-am
TAGS: tags

tags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	set x; \
	here=`pwd`; \
	$(am__define_uniq_tagged_files); \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: ctags-am

CTAGS: ctags
ctags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	$(am__define_uniq_tagged_files); \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"
cscopelist: cscopelist-am

cscopelist-am: $(am__tagged_files)
	list='$(am__tagged_files)'; \
	case "$(srcdir)" in \
	  [\\/]* | ?:[\\/]*) sdir="$(srcdir)" ;; \
	  *) sdir=$(subdir)/$(srcdir) ;; \
	esac; \
	for i in $$list; do \
	  if test -f "$$i"; then \
	    echo "$(subdir)/$$i"; \
	  else \
	    echo "$$sdir/$$i"; \
	  fi; \
	done >> $(top_builddir)/cscope.files

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(LTLIBRARIES) $(SCRIPTS) $(DATA) $(HEADERS)
installdirs:
	for dir in "$(DESTDIR)$(moduledir)" "$(DESTDIR)$(bindir)" "$(DESTDIR)$(desktopdir)" "$(DESTDIR)$(gnomeccdir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:
	-test -z "$(CLEANFILES)" || rm -f $(CLEANFILES)

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
	-test -z "$(MAINTAINERCLEANFILES)" || rm -f $(MAINTAINERCLEANFILES)
clean: clean-am

clean-am: clean-generic clean-libtool clean-moduleLTLIBRARIES \
	mostlyclean-am

distclean: distclean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am: install-desktopDATA install-gnomeccDATA \
	install-moduleLTLIBRARIES

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am: install-binSCRIPTS

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-binSCRIPTS uninstall-desktopDATA \
	uninstall-gnomeccDATA uninstall-moduleLTLIBRARIES

.MAKE: install-am install-strip

.PHONY: CTAGS GTAGS TAGS all all-am check check-am clean clean-generic \
	clean-libtool clean-moduleLTLIBRARIES cscopelist-am ctags \
	ctags-am distclean distclean-compile distclean-generic \
	distclean-libtool distclean-tags distdir dvi dvi-am html \
	html-am info info-am install install-am install-binSCRIPTS \
	install-data install-data-am install-desktopDATA install-dvi \
	install-dvi-am install-exec install-exec-am \
	install-gnomeccDATA install-html install-html-am install-info \
	install-info-am install-man install-moduleLTLIBRARIES \
	install-pdf install-pdf-am install-ps install-ps-am \
	install-strip installcheck installcheck-am installdirs \
	maintainer-clean maintainer-clean-generic mostlyclean \
	mostlyclean-compile mostlyclean-generic mostlyclean-libtool \
	pdf pdf-am ps ps-am tags tags-am uninstall uninstall-am \
	uninstall-binSCRIPTS uninstall-desktopDATA \
	uninstall-gnomeccDATA uninstall-moduleLTLIBRARIES


%.desktop:   %.desktop.in   $(INTLTOOL_MERGE) $(wildcard $(top_srcdir)/po/*.po) ; $(INTLTOOL_V_MERGE)LC_ALL=C $(INTLTOOL_MERGE) $(INTLTOOL_V_MERGE_OPTIONS) -d -u -c $(top_builddir)/po/.intltool-merge-cache $(top_srcdir)/po $< $@

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
