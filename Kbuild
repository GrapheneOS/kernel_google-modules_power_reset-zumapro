# SPDX-License-Identifier: GPL-2.0

subdir-ccflags-y += \
		-I$(KERNEL_SRC)/../private/google-modules/bms \

pixel-reboot-$(CONFIG_SOC_GS101) += pixel-gs101-reboot.o
pixel-reboot-$(CONFIG_SOC_GS201) += pixel-gs201-reboot.o
pixel-reboot-$(CONFIG_SOC_ZUMA) += pixel-zuma-reboot.o

obj-$(CONFIG_PIXEL_POWER_REBOOT) += pixel-reboot.o
