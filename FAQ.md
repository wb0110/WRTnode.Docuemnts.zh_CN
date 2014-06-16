# 常见问题（FAQ）


## 如何连接 WRTnode 的无线

- 在无线中找到 WRTnodeXXXX 的无线信号，密码为 12345678。
- 访问 http://192.168.8.1/ 即可访问 WRTnode 的 OpenWRT WEB 界面。

## 如何编译 OpenWRT 固件（for WRTnode）

- 通过 OpenWRT WEB 界面设置 root 密码，通过 SSH 连接 WRTnode。
- 参考《[预览版SDK的固件编译](http://cn.wrtnode.com/?p=369 "预览版SDK的固件编译")》安装依赖库
- 参考《[OpenWRT固件编译](http://cn.wrtnode.com/?p=172 "OpenWRT固件编译")》构建固件编译环境，补充说明：
	- 必须有网络连接（大量下载源代码重新编译）
	- 使用非 root 账号
	- 漫长编译后，在 bin/ramips 目录下找到 WRTnode 所需要的固件文件
