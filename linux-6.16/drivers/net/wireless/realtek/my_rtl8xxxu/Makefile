# SPDX-License-Identifier: GPL-2.0-only
obj-m	+= rtl8xxxu.o

rtl8xxxu-y	:= core.o 8192e.o 8723b.o \
		   8723a.o 8192c.o 8188f.o \
		   8188e.o 8710b.o 8192f.o



all:
	$(MAKE) -C /lib/modules/`uname -r`/build/ M=`pwd` modules

clean:
	$(MAKE) -C /lib/modules/`uname -r`/build/ M=`pwd` clean