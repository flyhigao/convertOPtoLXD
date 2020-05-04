# lxd-openwrt
convert my openwrt rom to lxd (for pve)

为了简略，做了一些功能去除
1.  从我的网站获取rootfs和sdk，去掉checksum的检查
2.  去掉rom upgrade
3.  去掉rom 新增加包的功能
仅仅运行build.sh即可，如果成功就会在/bin/目录下出现openwrt-19.07.2-x86-64-lxd.tar.gz

注意，rootfs和sdk的文件名是从https://myfile.net/releases/19.07.2/targets/x86/64/sha256sums文件中获得。
所有要把自己编译出的所有文件放过去即可。不必去改文件名

原始代码获得由：
https://github.com/mikma/lxd-openwrt

