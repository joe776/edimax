#
# Copyright (C) 2012-2013 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#
include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=mvebu
BOARDNAME:=Marvell Armada XP/370
FEATURES:=targz usb jffs2 pci pcie gpio
CFLAGS:=-Os -pipe -march=armv7-a -mfpu=vfpv3-d16 -mfloat-abi=softfp
MAINTAINER:=Florian Fainelli <florian@openwrt.org>

LINUX_VERSION:=3.8.12

include $(INCLUDE_DIR)/target.mk

KERNELNAME:="zImage dtbs"

DEFAULT_PACKAGES +=

$(eval $(call BuildTarget))
