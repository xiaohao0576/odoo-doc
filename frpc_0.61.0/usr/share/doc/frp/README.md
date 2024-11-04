## 说明
从https://github.com/fatedier/frp/releases 中下载最新的linux_amd64.tar.gz文件,
替换/usr/local/bin/frpc文件

## 更新DEBIAN/control的版本号
把DEBIAN/control文件中的版本号替换成最新的版本号

## 编译deb文件命
dpkg-deb --build frpc_1.0.0 frpc_1.0.0_amd64.deb
替换1.0.1为真正的版本号
