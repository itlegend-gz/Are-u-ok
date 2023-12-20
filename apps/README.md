#### iStore .run 软件包

* 本页面所下载的软件包插件适用于aarch64_cortex-a53平台的机器(EasePi ARS2、小米AX3600、AX9000、红米AX6等)。

* 也兼容aarch64_generic平台，例如R2S、R4S、R5S、R68S等。

* 一系列软件包：

|插件名|功能|下载|
| :----: | :----: | :----: |
| ByPass | 科学上网 | [下载](https://raw.githubusercontent.com/bcseputetto/Are-u-ok/main/apps/all/ByPass_a53.run) |
| VSSR | 科学上网 | [下载](https://raw.githubusercontent.com/bcseputetto/Are-u-ok/main/apps/all/VSSR_a53.run) |
| AdGuardHome | luci-app-AdGuardHome(DNS+广告拦截) | [下载](https://raw.githubusercontent.com/bcseputetto/Are-u-ok/main/apps/all/AdGuardHome_a53.run) |
| ikoolproxy | koolproxy拦截广告(不适合高于5.4内核的固件) | [下载](https://raw.githubusercontent.com/bcseputetto/Are-u-ok/main/apps/all/ikoolproxy_a53.run) |
| Adblock | Adblock 拦截广告 | [下载](https://raw.githubusercontent.com/bcseputetto/Are-u-ok/main/apps/all/adblock.run) |
| Adbyby | 广告屏蔽大师 Plus+ | [下载](https://raw.githubusercontent.com/bcseputetto/Are-u-ok/main/apps/all/adbyby_a53.run) |
| UnblockNeteaseMusic | 解锁网易云灰色歌曲 | [下载](https://raw.githubusercontent.com/bcseputetto/Are-u-ok/main/apps/all/UnblockNeteaseMusic_a53.run) |
| OpenVPN | OpenVPN客户端 | [下载](https://raw.githubusercontent.com/bcseputetto/Are-u-ok/main/apps/all/OpenVPN_20211018.run) |
| OpenVPN-Server | OpenVPN服务端 | [下载](https://raw.githubusercontent.com/bcseputetto/Are-u-ok/main/apps/all/OpenVPN-Server_a53.run) |
| JD-dailybonus | 某东签到(扫码早就gg，手动填cookie) | [下载](https://raw.githubusercontent.com/bcseputetto/Are-u-ok/main/apps/all/JD-dailybonus_20211105.run) |
| KMS | KMS服务器 | [下载](https://raw.githubusercontent.com/bcseputetto/Are-u-ok/main/apps/all/KMS_a53.run) |
| NPS | Nps内网穿透 | [下载](https://raw.githubusercontent.com/bcseputetto/Are-u-ok/main/apps/all/NPS_a53.run) |
| MosDNS | DNS 转发/分流器 | [下载](https://raw.githubusercontent.com/bcseputetto/Are-u-ok/main/apps/all/MosDNS-New_a53.run) |

* 如何安装
下载后，来到iStore应用商店页面，点击手动安装，点击选择上传或者直接拖放文件
![png](https://cdn.jsdelivr.net/gh/bcseputetto/Are-u-ok@master/apps/install.png)

对于没有iStore应用商店的OpenWrt也可以使用以下方法。
将 .run 文件上传到路由器上，然后在终端环境执行
```console
sh 包名.run
```
例
```console
sh PassWall_4.71-2_aarch64_a53_all_sdk_22.03.5.run
```
如果文件不在当前路径记得填写路径，下例
```console
sh /tmp/upload/PassWall_4.71-2_aarch64_a53_all_sdk_22.03.5.run
