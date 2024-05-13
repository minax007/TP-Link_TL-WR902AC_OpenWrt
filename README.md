[![Build OpenWrt](https://github.com/minax007/TP-Link_TL-WR902AC_OpenWrt/actions/workflows/openwrt_release_tl-wr902ac-v3.yml/badge.svg)](https://github.com/minax007/TP-Link_TL-WR902AC_OpenWrt/actions/workflows/openwrt_release_tl-wr902ac-v3.yml)
[![release](https://img.shields.io/github/v/release/minax007/TP-Link_TL-WR902AC_OpenWrt.svg)](https://github.com/minax007/TP-Link_TL-WR902AC_OpenWrt/releases)

# OpenWrt snapshot for TP-Link TL-WR902AC

This GitHub action is to build fresh images of latest OpenWrt snapshot for the TL-WR902AC using imagebuilder.

![grafik](https://github.com/minax007/TP-Link_TL-WR902AC_OpenWrt/assets/67478561/16b9a4ff-575e-436a-b760-83d0479f65b8)

Following packages are already installed, so that you do not need to install them via the command line afterwards: 

Added features | Package names
------------ | -------------
**LuCI GUI** | luci
**LuCI Material Theme** | luci-theme-material 
**LuCI Bandwidth Monitor** | luci-app-nlbwmon
**VPN** | OpenSSL VPN
__________________________________________________________________
**Official OpenWrt snapshot of TL-WR902AC build without LuCI:**

https://firmware-selector.openwrt.org/?version=SNAPSHOT&target=ramips%2Fmt76x8&id=tplink_tl-wr902ac-v3
__________________________________________________________________
**Official OpenWrt snapshot download directory for MT76x8 routers, which includes the imagebuilder used in this action script:**

https://downloads.openwrt.org/snapshots/targets/ramips/mt76x8/
