# SmartDNS

#### 说明

* 软件不定期同步[openwrt-smartdns](https://github.com/pymumu/openwrt-smartdns) & [luci-app-smartdns](https://github.com/pymumu/luci-app-smartdns)，适合一键下载到package目录下，用于openwrt编译

* pymumu原版luci-app-smartdns的lede版，编译文件中有luci-compat，删除后就可以正常编译了。

* 运行下面命令即可

* lede/package$下运行 或者openwrt/package$下运行

```bash
 svn co https://github.com/pirately/packages/trunk/smartdns package/smartdns
```