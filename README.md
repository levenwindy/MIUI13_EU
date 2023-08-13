
提取步骤
1. simg2img
~~~~~~~~~~~~~~~~~~~
./simg2img 原版super.img super.raw

~~~~~~~~~~~~~~~~~~~

2. lpunpack 解压 super.raw
~~~~~~~~~~~~~~~~~~~
./lpunpack super.raw 
~~~~~~~~~~~~~~~~~~~

1.提取apk

MIpay.apk 

安装失败：（NextPay.apk TSMClient.apk UPTsmService.apk）

2.安装模块

MIUI EU 13（k30pro 安装成功）
https://github.com/mrchi/magisk-miui-eu-install-mipay ![下载](https://github.com/mrchi/magisk-miui-eu-install-mipay/releases/tag/v1.0.0)

3.安装apk、重启

4.隐藏root

magisk-设置(右上角)-Zygisk(✓)-遵守排除列表(✓)-配置排除列表（银行、公司等应用）
