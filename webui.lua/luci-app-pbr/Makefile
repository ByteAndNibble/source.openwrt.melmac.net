# Copyright 2017-2019 Stan Grishin (stangri@melmac.ca)
# This is free software, licensed under the GNU General Public License v3.

include $(TOPDIR)/rules.mk

PKG_LICENSE:=GPL-3.0-or-later
PKG_MAINTAINER:=Stan Grishin <stangri@melmac.ca>
PKG_VERSION:=0.9.9-2

LUCI_TITLE:=Policy Based Routing Service Web UI
LUCI_DESCRIPTION:=Provides Web UI for Policy Based Routing Service.
LUCI_DEPENDS:=+luci-compat +luci-base +pbr
LUCI_PKGARCH:=all

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
