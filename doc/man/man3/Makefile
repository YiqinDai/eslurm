# Makefile.in generated by automake 1.16.3 from Makefile.am.
# doc/man/man3/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2020 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.

MAKE=make

am__is_gnu_make = { \
  if test -z '$(MAKELEVEL)'; then \
    false; \
  elif test -n '$(MAKE_HOST)'; then \
    true; \
  elif test -n '$(MAKE_VERSION)' && test -n '$(CURDIR)'; then \
    true; \
  else \
    false; \
  fi; \
}
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
pkgdatadir = $(datadir)/slurm
pkgincludedir = $(includedir)/slurm
pkglibdir = $(libdir)/slurm
pkglibexecdir = $(libexecdir)/slurm
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
build_triplet = x86_64-pc-linux-gnu
host_triplet = x86_64-pc-linux-gnu
target_triplet = x86_64-pc-linux-gnu
subdir = doc/man/man3
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/auxdir/ax_check_compile_flag.m4 \
	$(top_srcdir)/auxdir/ax_check_zlib.m4 \
	$(top_srcdir)/auxdir/ax_gcc_builtin.m4 \
	$(top_srcdir)/auxdir/ax_lib_hdf5.m4 \
	$(top_srcdir)/auxdir/ax_pthread.m4 \
	$(top_srcdir)/auxdir/libtool.m4 \
	$(top_srcdir)/auxdir/ltoptions.m4 \
	$(top_srcdir)/auxdir/ltsugar.m4 \
	$(top_srcdir)/auxdir/ltversion.m4 \
	$(top_srcdir)/auxdir/lt~obsolete.m4 \
	$(top_srcdir)/auxdir/slurm.m4 \
	$(top_srcdir)/auxdir/slurmrestd.m4 \
	$(top_srcdir)/auxdir/x_ac_affinity.m4 \
	$(top_srcdir)/auxdir/x_ac_c99.m4 \
	$(top_srcdir)/auxdir/x_ac_cgroup.m4 \
	$(top_srcdir)/auxdir/x_ac_cray.m4 \
	$(top_srcdir)/auxdir/x_ac_curl.m4 \
	$(top_srcdir)/auxdir/x_ac_databases.m4 \
	$(top_srcdir)/auxdir/x_ac_debug.m4 \
	$(top_srcdir)/auxdir/x_ac_deprecated.m4 \
	$(top_srcdir)/auxdir/x_ac_dlfcn.m4 \
	$(top_srcdir)/auxdir/x_ac_env.m4 \
	$(top_srcdir)/auxdir/x_ac_freeipmi.m4 \
	$(top_srcdir)/auxdir/x_ac_http_parser.m4 \
	$(top_srcdir)/auxdir/x_ac_hwloc.m4 \
	$(top_srcdir)/auxdir/x_ac_json.m4 \
	$(top_srcdir)/auxdir/x_ac_jwt.m4 \
	$(top_srcdir)/auxdir/x_ac_lua.m4 \
	$(top_srcdir)/auxdir/x_ac_lz4.m4 \
	$(top_srcdir)/auxdir/x_ac_man2html.m4 \
	$(top_srcdir)/auxdir/x_ac_munge.m4 \
	$(top_srcdir)/auxdir/x_ac_netloc.m4 \
	$(top_srcdir)/auxdir/x_ac_nvml.m4 \
	$(top_srcdir)/auxdir/x_ac_ofed.m4 \
	$(top_srcdir)/auxdir/x_ac_pam.m4 \
	$(top_srcdir)/auxdir/x_ac_pmix.m4 \
	$(top_srcdir)/auxdir/x_ac_printf_null.m4 \
	$(top_srcdir)/auxdir/x_ac_ptrace.m4 \
	$(top_srcdir)/auxdir/x_ac_readline.m4 \
	$(top_srcdir)/auxdir/x_ac_rrdtool.m4 \
	$(top_srcdir)/auxdir/x_ac_rsmi.m4 \
	$(top_srcdir)/auxdir/x_ac_setproctitle.m4 \
	$(top_srcdir)/auxdir/x_ac_systemd.m4 \
	$(top_srcdir)/auxdir/x_ac_ucx.m4 \
	$(top_srcdir)/auxdir/x_ac_uid_gid_size.m4 \
	$(top_srcdir)/auxdir/x_ac_x11.m4 \
	$(top_srcdir)/auxdir/x_ac_yaml.m4 $(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
DIST_COMMON = $(srcdir)/Makefile.am
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/config.h $(top_builddir)/slurm/slurm.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
AM_V_P = $(am__v_P_1)
am__v_P_ = $(am__v_P_1)
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_1)
am__v_GEN_ = $(am__v_GEN_1)
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_1)
am__v_at_ = $(am__v_at_1)
am__v_at_0 = @
am__v_at_1 = 
SOURCES =
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
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
man3dir = $(mandir)/man3
am__installdirs = "$(DESTDIR)$(man3dir)"
NROFF = nroff
MANS = $(man3_MANS)
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
ACLOCAL = ${SHELL} '/home/daiyiqin1/Desktop/slurm-20.11.7/auxdir/missing' aclocal-1.16
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 1
AR = ar
AR_FLAGS = cr
AUTOCONF = ${SHELL} '/home/daiyiqin1/Desktop/slurm-20.11.7/auxdir/missing' autoconf
AUTOHEADER = ${SHELL} '/home/daiyiqin1/Desktop/slurm-20.11.7/auxdir/missing' autoheader
AUTOMAKE = ${SHELL} '/home/daiyiqin1/Desktop/slurm-20.11.7/auxdir/missing' automake-1.16
AWK = mawk
CC = gcc
CCDEPMODE = depmode=none
CFLAGS = -g -O2 -fno-omit-frame-pointer -pthread -ggdb3 -Wall -g -O1 -fno-strict-aliasing
CHECK_CFLAGS = 
CHECK_LIBS = 
CPP = gcc -E
CPPFLAGS = 
CRAY_JOB_CPPFLAGS = 
CRAY_JOB_LDFLAGS = 
CRAY_SELECT_CPPFLAGS = 
CRAY_SELECT_LDFLAGS = 
CRAY_SWITCH_CPPFLAGS = 
CRAY_SWITCH_LDFLAGS = 
CRAY_TASK_CPPFLAGS = 
CRAY_TASK_LDFLAGS = 
CXX = g++
CXXCPP = 
CXXDEPMODE = depmode=none
CXXFLAGS = 
CYGPATH_W = echo
DATAWARP_CPPFLAGS = 
DATAWARP_LDFLAGS = 
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DLLTOOL = false
DL_LIBS = -ldl
DSYMUTIL = 
DUMPBIN = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /usr/bin/grep -E
EXEEXT = 
FGREP = /usr/bin/grep -F
FREEIPMI_CPPFLAGS = 
FREEIPMI_LDFLAGS = 
FREEIPMI_LIBS = 
GLIB_CFLAGS = 
GLIB_COMPILE_RESOURCES = 
GLIB_GENMARSHAL = 
GLIB_LIBS = 
GLIB_MKENUMS = 
GOBJECT_QUERY = 
GREP = /usr/bin/grep
GTK_CFLAGS = 
GTK_LIBS = 
H5CC = 
H5FC = 
HAVEMYSQLCONFIG = no
HAVE_MAN2HTML = 
HDF5_CC = 
HDF5_CFLAGS = 
HDF5_CPPFLAGS = 
HDF5_FC = 
HDF5_FFLAGS = 
HDF5_FLIBS = 
HDF5_LDFLAGS = 
HDF5_LIBS = 
HDF5_TYPE = neither
HDF5_VERSION = 
HTTP_PARSER_CPPFLAGS = 
HTTP_PARSER_LDFLAGS = 
HWLOC_CPPFLAGS = 
HWLOC_LDFLAGS = 
HWLOC_LIBS = 
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
JSON_CPPFLAGS = 
JSON_LDFLAGS = 
JWT_CPPFLAGS = 
JWT_LDFLAGS = 
LD = /usr/bin/ld -m elf_x86_64
LDFLAGS =  
LIBCURL = 
LIBCURL_CPPFLAGS = 
LIBOBJS = 
LIBS =  -lm -lresolv 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIB_SLURM = -Wl,-rpath=${exec_prefix}/lib/slurm -L$(top_builddir)/src/api/.libs -lslurmfull
LIB_SLURM_BUILD = $(top_builddir)/src/api/full_version.map $(top_builddir)/src/api/libslurmfull.la
LIPO = 
LN_S = ln -s
LTLIBOBJS = 
LT_SYS_LIBRARY_PATH = 
LZ4_CPPFLAGS = 
LZ4_LDFLAGS = 
LZ4_LIBS = 
MAINT = #
MAKEINFO = ${SHELL} '/home/daiyiqin1/Desktop/slurm-20.11.7/auxdir/missing' makeinfo
MANIFEST_TOOL = :
MKDIR_P = /usr/bin/mkdir -p
MUNGE_CPPFLAGS = 
MUNGE_DIR = 
MUNGE_LDFLAGS = 
MUNGE_LIBS = 
MYSQL_CFLAGS = 
MYSQL_LIBS = 
NETLOC_CPPFLAGS = 
NETLOC_LDFLAGS = 
NETLOC_LIBS = 
NM = /usr/bin/nm -B
NMEDIT = 
NUMA_LIBS = 
NVML_CPPFLAGS = 
NVML_LIBS = 
OBJCOPY = objcopy
OBJDUMP = objdump
OBJEXT = o
OFED_CPPFLAGS = 
OFED_LDFLAGS = 
OFED_LIBS = 
OTOOL = 
OTOOL64 = 
PACKAGE = slurm
PACKAGE_BUGREPORT = 
PACKAGE_NAME = slurm
PACKAGE_STRING = slurm 20.11
PACKAGE_TARNAME = slurm
PACKAGE_URL = https://slurm.schedmd.com
PACKAGE_VERSION = 20.11
PAM_DIR = /lib/security
PAM_LIBS = 
PATH_SEPARATOR = :
PKG_CONFIG = /usr/bin/pkg-config
PKG_CONFIG_LIBDIR = 
PKG_CONFIG_PATH = 
PMIX_V1_CPPFLAGS = 
PMIX_V1_LDFLAGS = 
PMIX_V2_CPPFLAGS = 
PMIX_V2_LDFLAGS = 
PMIX_V3_CPPFLAGS = 
PMIX_V3_LDFLAGS = 
PMIX_V4_CPPFLAGS = 
PMIX_V4_LDFLAGS = 
PROJECT = slurm
PTHREAD_CC = gcc
PTHREAD_CFLAGS = -pthread
PTHREAD_LIBS = 
RANLIB = ranlib
READLINE_LIBS = 
RELEASE = 1
RRDTOOL_CPPFLAGS = 
RRDTOOL_LDFLAGS = 
RRDTOOL_LIBS = 
RSMI_CPPFLAGS = 
RSMI_LDFLAGS = 
RSMI_LIBS = 
SED = /usr/bin/sed
SET_MAKE = MAKE=make
SHELL = /bin/bash
SLEEP_CMD = /usr/bin/sleep
SLURMCTLD_PORT = 
SLURMCTLD_PORT_COUNT = 
SLURMDBD_PORT = 
SLURMD_PORT = 
SLURMRESTD_PORT = 6820
SLURM_API_AGE = 0
SLURM_API_CURRENT = 36
SLURM_API_MAJOR = 36
SLURM_API_REVISION = 0
SLURM_API_VERSION = 0x240000
SLURM_MAJOR = 20
SLURM_MICRO = 7
SLURM_MINOR = 11
SLURM_PREFIX = 
SLURM_VERSION_NUMBER = 0x140b07
SLURM_VERSION_STRING = 20.11.7
STRIP = strip
SUCMD = /usr/bin/su
SYSTEMD_TASKSMAX_OPTION = TasksMax=infinity
UCX_CPPFLAGS = 
UCX_LDFLAGS = 
UCX_LIBS = 
UTIL_LIBS = -lutil
VERSION = 20.11
YAML_CPPFLAGS = 
YAML_LDFLAGS = 
ZLIB_CPPFLAGS = 
ZLIB_LDFLAGS = 
ZLIB_LIBS = 
_libcurl_config = 
abs_builddir = /home/daiyiqin1/Desktop/slurm-20.11.7/doc/man/man3
abs_srcdir = /home/daiyiqin1/Desktop/slurm-20.11.7/doc/man/man3
abs_top_builddir = /home/daiyiqin1/Desktop/slurm-20.11.7
abs_top_srcdir = /home/daiyiqin1/Desktop/slurm-20.11.7
ac_ct_AR = ar
ac_ct_CC = gcc
ac_ct_CXX = 
ac_ct_DUMPBIN = 
ac_have_man2html = no
am__include = #
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
ax_pthread_config = 
bindir = ${exec_prefix}/bin
build = x86_64-pc-linux-gnu
build_alias = 
build_cpu = x86_64
build_os = linux-gnu
build_vendor = pc
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = x86_64-pc-linux-gnu
host_alias = 
host_cpu = x86_64
host_os = linux-gnu
host_vendor = pc
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/daiyiqin1/Desktop/slurm-20.11.7/auxdir/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
lua_CFLAGS = 
lua_LIBS = 
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local/slurm-plus
program_transform_name = s,x,x,
psdir = ${docdir}
runstatedir = ${localstatedir}/run
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = /usr/local/slurm-plus/etc
target = x86_64-pc-linux-gnu
target_alias = 
target_cpu = x86_64
target_os = linux-gnu
target_vendor = pc
top_build_prefix = ../../../
top_builddir = ../../..
top_srcdir = ../../..
man3_MANS = slurm_hostlist_create.3 \
	slurm_hostlist_destroy.3 \
	slurm_hostlist_shift.3 \
	slurm_allocate_het_job_blocking.3 \
	slurm_allocate_resources.3 \
	slurm_allocate_resources_blocking.3 \
	slurm_allocation_lookup.3 \
	slurm_allocation_msg_thr_create.3 \
	slurm_allocation_msg_thr_destroy.3 \
	slurm_api_version.3 \
	slurm_clear_trigger.3 \
	slurm_complete_job.3 \
	slurm_confirm_allocation.3 \
	slurm_create_partition.3 \
	slurm_create_reservation.3 \
	slurm_delete_partition.3 \
	slurm_delete_reservation.3 \
	slurm_free_ctl_conf.3 \
	slurm_free_front_end_info_msg.3 \
	slurm_free_job_info_msg.3 \
	slurm_free_job_alloc_info_response_msg.3 \
	slurm_free_job_array_resp.3 \
	slurm_free_job_step_create_response_msg.3 \
	slurm_free_job_step_info_response_msg.3 \
	slurm_free_node_info.3 \
	slurm_free_node_info_msg.3 \
	slurm_free_partition_info.3 \
	slurm_free_partition_info_msg.3 \
	slurm_free_reservation_info_msg.3 \
	slurm_free_resource_allocation_response_msg.3 \
	slurm_free_slurmd_status.3 \
	slurm_free_submit_response_response_msg.3 \
	slurm_free_trigger_msg.3 \
	slurm_get_end_time.3 \
	slurm_get_errno.3 \
	slurm_get_job_steps.3 \
	slurm_get_rem_time.3 \
	slurm_get_triggers.3 \
	slurm_init_update_front_end_msg.3 \
	slurm_init_job_desc_msg.3 \
	slurm_init_part_desc_msg.3 \
	slurm_init_resv_desc_msg.3 \
	slurm_init_trigger_msg.3 \
	slurm_init_update_node_msg.3 \
	slurm_init_update_step_msg.3 \
	slurm_job_cpus_allocated_on_node.3 \
	slurm_job_cpus_allocated_on_node_id.3 \
	slurm_job_step_create.3 \
	slurm_job_step_launch_t_init.3 \
	slurm_job_step_layout_get.3 \
	slurm_job_step_layout_free.3 \
	slurm_job_will_run.3 \
	slurm_job_will_run2.3 \
	slurm_jobinfo_ctx_get.3 \
	slurm_kill_job.3 \
	slurm_kill_job_step.3 \
	slurm_load_ctl_conf.3 \
	slurm_load_front_end.3 \
	slurm_load_job.3 \
	slurm_load_jobs.3 \
	slurm_load_job_user.3 \
	slurm_load_node.3 \
	slurm_load_node_single.3 \
	slurm_load_partitions.3 \
	slurm_load_reservations.3 \
	slurm_load_slurmd_status.3 \
	slurm_notify_job.3 \
	slurm_het_job_lookup.3 \
	slurm_het_job_will_run.3 \
	slurm_perror.3 \
	slurm_pid2jobid.3 \
	slurm_ping.3 \
	slurm_print_ctl_conf.3 \
	slurm_print_front_end_info_msg.3 \
	slurm_print_front_end_table.3 \
	slurm_print_job_info.3 \
	slurm_print_job_info_msg.3 \
	slurm_print_job_step_info.3 \
	slurm_print_job_step_info_msg.3 \
	slurm_print_node_info_msg.3 \
	slurm_print_node_table.3 \
	slurm_print_partition_info.3 \
	slurm_print_partition_info_msg.3 \
	slurm_print_reservation_info.3 \
	slurm_print_reservation_info_msg.3 \
	slurm_print_slurmd_status.3 \
	slurm_read_hostfile.3 \
	slurm_reconfigure.3 \
	slurm_resume.3 \
	slurm_resume2.3 \
	slurm_requeue.3 \
	slurm_requeue2.3 \
	slurm_set_debug_level.3 \
	slurm_set_trigger.3 \
	slurm_shutdown.3 \
	slurm_signal_job.3 \
	slurm_signal_job_step.3 \
	slurm_slurmd_status.3 \
	slurm_sprint_front_end_table.3 \
	slurm_sprint_job_info.3 \
	slurm_sprint_job_step_info.3 \
	slurm_sprint_node_table.3 \
	slurm_sprint_partition_info.3 \
	slurm_sprint_reservation_info.3 \
	slurm_step_ctx_create.3 \
	slurm_step_ctx_create_no_alloc.3 \
	slurm_step_ctx_daemon_per_node_hack.3 \
	slurm_step_ctx_destroy.3 \
	slurm_step_ctx_params_t_init.3 \
	slurm_step_ctx_get.3 \
	slurm_step_launch.3 \
	slurm_step_launch_fwd_signal.3 \
	slurm_step_launch_abort.3 \
	slurm_step_launch_wait_finish.3 \
	slurm_step_launch_wait_start.3 \
	slurm_strerror.3 \
	slurm_submit_batch_job.3 \
	slurm_suspend.3 \
	slurm_suspend2.3 \
	slurm_takeover.3 \
	slurm_terminate_job.3 \
	slurm_terminate_job_step.3 \
	slurm_update_front_end.3 \
	slurm_update_job.3 \
	slurm_update_job2.3 \
	slurm_update_node.3 \
	slurm_update_partition.3 \
	slurm_update_reservation.3 \
	slurm_update_step.3

all: all-am

.SUFFIXES:
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --gnu doc/man/man3/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --gnu doc/man/man3/Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__maybe_remake_depfiles)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__maybe_remake_depfiles);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure: # $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs
install-man3: $(man3_MANS)
	@$(NORMAL_INSTALL)
	@list1='$(man3_MANS)'; \
	list2=''; \
	test -n "$(man3dir)" \
	  && test -n "`echo $$list1$$list2`" \
	  || exit 0; \
	echo " $(MKDIR_P) '$(DESTDIR)$(man3dir)'"; \
	$(MKDIR_P) "$(DESTDIR)$(man3dir)" || exit 1; \
	{ for i in $$list1; do echo "$$i"; done;  \
	if test -n "$$list2"; then \
	  for i in $$list2; do echo "$$i"; done \
	    | sed -n '/\.3[a-z]*$$/p'; \
	fi; \
	} | while read p; do \
	  if test -f $$p; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; echo "$$p"; \
	done | \
	sed -e 'n;s,.*/,,;p;h;s,.*\.,,;s,^[^3][0-9a-z]*$$,3,;x' \
	      -e 's,\.[0-9a-z]*$$,,;$(transform);G;s,\n,.,' | \
	sed 'N;N;s,\n, ,g' | { \
	list=; while read file base inst; do \
	  if test "$$base" = "$$inst"; then list="$$list $$file"; else \
	    echo " $(INSTALL_DATA) '$$file' '$(DESTDIR)$(man3dir)/$$inst'"; \
	    $(INSTALL_DATA) "$$file" "$(DESTDIR)$(man3dir)/$$inst" || exit $$?; \
	  fi; \
	done; \
	for i in $$list; do echo "$$i"; done | $(am__base_list) | \
	while read files; do \
	  test -z "$$files" || { \
	    echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(man3dir)'"; \
	    $(INSTALL_DATA) $$files "$(DESTDIR)$(man3dir)" || exit $$?; }; \
	done; }

uninstall-man3:
	@$(NORMAL_UNINSTALL)
	@list='$(man3_MANS)'; test -n "$(man3dir)" || exit 0; \
	files=`{ for i in $$list; do echo "$$i"; done; \
	} | sed -e 's,.*/,,;h;s,.*\.,,;s,^[^3][0-9a-z]*$$,3,;x' \
	      -e 's,\.[0-9a-z]*$$,,;$(transform);G;s,\n,.,'`; \
	dir='$(DESTDIR)$(man3dir)'; $(am__uninstall_files_from_dir)
tags TAGS:

ctags CTAGS:

cscope cscopelist:

check-am: all-am
check: check-am
all-am: Makefile $(MANS)
installdirs:
	for dir in "$(DESTDIR)$(man3dir)"; do \
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

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic clean-libtool mostlyclean-am

distclean: distclean-am
	-rm -f Makefile
distclean-am: clean-am distclean-generic

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am: install-man

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am:

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man: install-man3

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-generic mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-man

uninstall-man: uninstall-man3

.MAKE: install-am install-strip

.PHONY: all all-am check check-am clean clean-generic clean-libtool \
	cscopelist-am ctags-am distclean distclean-generic \
	distclean-libtool dvi dvi-am html html-am info info-am install \
	install-am install-data install-data-am install-dvi \
	install-dvi-am install-exec install-exec-am install-html \
	install-html-am install-info install-info-am install-man \
	install-man3 install-pdf install-pdf-am install-ps \
	install-ps-am install-strip installcheck installcheck-am \
	installdirs maintainer-clean maintainer-clean-generic \
	mostlyclean mostlyclean-generic mostlyclean-libtool pdf pdf-am \
	ps ps-am tags-am uninstall uninstall-am uninstall-man \
	uninstall-man3

.PRECIOUS: Makefile


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
