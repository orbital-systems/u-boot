# (C) Copyright 2016 Digi International, Inc.
#
# SPDX-License-Identifier:	GPL-2.0+
#

obj-y  := oas.o ../../digi/ccimx6ul/ccimx6ul.o

extra-$(CONFIG_USE_PLUGIN) :=  ../../digi/ccimx6ul/plugin.bin
$(obj)/../../digi/ccimx6ul/plugin.bin: $(obj)/../../digi/ccimx6ul/plugin.o
	$(OBJCOPY) -O binary --gap-fill 0xff $< $@
