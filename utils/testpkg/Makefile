include $(TOPDIR)/rules.mk

PKG_NAME:=testpkg
PKG_VERSION:=1.1
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/testpkg
  SECTION:=utils
  CATEGORY:=Utilities
  TITLE:=Test package for CI
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/testpkg/install
	true
endef

$(eval $(call BuildPackage,testpkg))
