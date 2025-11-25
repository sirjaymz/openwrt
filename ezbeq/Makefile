## MIT LICENSE

include $(TOPDIR)/rules.mk

PKG_NAME:=ezbeq
PKG_VERSION:=2.3.0
PKG_RELEASE:=1

PKG_BUILD_DIR:=$(BUILD_DIR)/ezbeq-$(PKG_VERSION)-$(PKG_RELEASE)
PKG_SOURCE:=ezbeq-$(PKG_VERSION).tar.gz
PKG_SOURCE_URL:=https://codeload.github.com/3ll3dood/ezbeq/tar.gz/v$(PKG_VERSION)?
#PKG_HASH:=

PKG_MAINTAINER:=sirjaymz@gmail.com
PKG_LICENSE:=MIT
PKG_LICENSE_FILES:=LICENSE
PKG_URL:=https://github.com/sirjaymz/openwrt/ezbeq
PKG_BUILD_DEPENDS:=python3/host python3-venv/host python3-pip/host libyaml/host 
## PKG_BUILD_PARALLEL:=1

define Package/ezbeq
  CATEGORY:=Multimedia
  TITLE:=ezbeq
  DEPENDS:=+minidsp-rs 
  URL:=https://github.com/sirjaymz/openwrt/ezbeq
endef

define Package/ezbeq/description
  A simple web browser for beqcatalogue which integrates with minidsp-rs for local remote control of a minidsp or HTP-1.
endef
