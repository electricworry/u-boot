# SPDX-License-Identifier: GPL-2.0+
#
# (C) Copyright 2012 Henrik Nordstrom <henrik@henriknordstrom.net>
#
# Based on some other Makefile
# (C) Copyright 2000-2003
# Wolfgang Denk, DENX Software Engineering, wd@denx.de.

obj-$(CONFIG_MACH_SUN6I)	+= tzpc.o
obj-$(CONFIG_MACH_SUN8I_H3)	+= tzpc.o

obj-$(CONFIG_MACH_SUN6I)	+= sram.o
obj-$(CONFIG_MACH_SUN8I)	+= sram.o

ifndef CONFIG_XPL_BUILD
obj-$(CONFIG_ARMV7_PSCI)	+= psci.o
endif

ifdef CONFIG_XPL_BUILD
obj-y	+= fel_utils.o
endif
