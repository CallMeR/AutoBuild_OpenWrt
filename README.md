# AutoBuild_OpenWrt_x86-64
[![x86_64](https://github.com/CallMeR/AutoBuild_OpenWrt/actions/workflows/x86_64.yml/badge.svg)](https://github.com/CallMeR/AutoBuild_OpenWrt/actions/workflows/x86_64.yml)  [![x86_64_enhanced](https://github.com/CallMeR/AutoBuild_OpenWrt/actions/workflows/x86_64_enhanced.yml/badge.svg)](https://github.com/CallMeR/AutoBuild_OpenWrt/actions/workflows/x86_64_enhanced.yml)

使用官方 [OpenWrt](https://github.com/openwrt/openwrt) 仓库进行x86-64版本编译

Hereby thank esirplayground for his amazing job: https://github.com/esirplayground/AutoBuild-OpenWrt  

**说明：**  
使用了官方 21.02 分支进行编译  
默认 LAN IP 地址：10.0.0.1  
强化了 CLI 使用的一些组件，比如 iper3 等  
增加了 vmxnet3 的驱动支持  
默认开启了 Qemu 的 qemu-qa，使用 ESXi 时需要手动调整
