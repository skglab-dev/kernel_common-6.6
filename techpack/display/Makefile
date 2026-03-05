# SPDX-License-Identifier: GPL-2.0-only

DISPLAY_ROOT=$(srctree)/techpack/display
KBUILD_OPTIONS := DISPLAY_ROOT=$(DISPLAY_ROOT)

ifeq ($(TARGET_SUPPORT),genericarmv8)
	KBUILD_OPTIONS += CONFIG_ARCH_SUN=y
endif

obj-m += msm/
