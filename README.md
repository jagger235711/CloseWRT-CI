# 自定义说明

只编译rax3000m（nand）、nx30pro固件

## 包含插件

CONFIG_PACKAGE_luci-app-diskman=y

CONFIG_PACKAGE_luci-app-autoreboot=y

CONFIG_PACKAGE_luci-app-passwall2=y

# CloseWRT-CI
云编译CloseWRT固件

HANWCKF源码：
https://github.com/hanwckf/immortalwrt-mt798x

PADAVANONLY源码：
https://github.com/padavanonly/immortalwrt-mt798x

# 固件简要说明：

固件每周一晚上8点开始自动编译。

固件信息里的时间为编译开始的时间，方便核对上游源码提交时间。

MEDIATEK系列，配套的UBOOT：
https://github.com/VIKINGYFY/UBOOT-CI/releases

# 目录简要说明：

Depends.txt——环境依赖列表

workflows——自定义CI配置

Scripts——自定义脚本

Config——自定义配置
