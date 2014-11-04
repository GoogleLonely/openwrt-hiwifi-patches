openwrt-hiwifi-patches
======================

## 更新内容

* 此patch针对于openwrt 14.07稳定版本，在jaypei的patch基础上，修正了最右网口错误问题

## 使用方法

1. 在openwrt根目录下，执行
```
patch -p1 < openwrt-14.07-hiwifi-hc5661.patch
rm -rf tmp
```

2. 执行```make menuconfig```进行配置

3. 执行```make V=99```进行编译
