# Hackintosh-DeskMini310-i5-8400-OC




## 适用版本

macOS Big Sur 11.5.2 

OpenCore 0.7.4


## 检查项

- [x] apple store 账号使用正常
- [x] 睡眠正常
- [x] 开关机正常
- [x] usb2.0 & 3.0 基本正常 已定制
- [x] DP输出2K显示正常 未测试HDMI
- [x] 蓝牙正常 必须接天线 信号才好
- [x] 无线正常 必须接天线 信号才好


## 主机配置

|                配置 | 名称 |
| --------------------: | ------------------------ |
|                准系统 | ASRock Deskmini H310/COM  |
|                  CPU | I5-8400                   |
|                  显卡 | 核显 UHD 630              |
|                  内存 | 威刚笔记本内存 DDR4 2666 8G * 2       |
|             网卡&蓝牙  | BCM943602CS+NGFF A/E转接卡+IPX转SMA天线              |
|                  硬盘  | 西数 512G M.2固态         |
|                  散热器 | IS40X                   |


## 使用方法

1. 按照黑果小兵的介绍一步步安装

2. 安装完成，使用别的电脑挂载硬盘efi分区

3. 拷贝替换同名目录下文件即可，修改主机型号为 Macmini8,1

###  安装前BIOS 设置


> Load UEFI Defaults
>   * Advanced
>     - CPU Configuration
>       - CPU C States Support : Enable
>         - CFG LOCK : Disabled
>     * Chipset Configuration
>       * VT-d: Disabled
>       * Onboard HD Audio: Enabled
>     * USB Configuration
>       * XHCI Hand-off: Enabled
>     * Super IO Configuration
>       * Serial Port: Disabled
>   * Security
>    
>     * Secure Boot: Disabled(by default)
>   - Boot
>     * CSM disable
>



## 特别感谢(排名不分先后)

### [我的迷你主机之选-Asrock Deskmini 310](https://post.smzdm.com/p/aqnd99xp/)

### [【黑果小兵】【微信首发】macOS Big Sur 11.5.2 20G95 Installer for OpenCore 0.7.1 and CLOVER 5138 and PE 三 EFI 分区原版镜像](https://blog.daliansky.net/macOS-BigSur-11.5.2-20G95-Release-version-with-OC-0.7.1-and-Clover-5138-and-PE-original-image.html)

### [史上最全的黑苹果系统「MacOS」安装教程，小白也能秒掌握！](https://blog.csdn.net/easylife206/article/details/106088699)

### [DeskMini310_EF](https://github.com/cocobear/DeskMini310_EF)

### [Hackintosh-EFI-for-deskmini-310-dw1820](https://github.com/huangyanan/Hackintosh-EFI-for-deskmini-310-dw1820)

### [DeskMini H310 OC引导安装BigSur 11.0.1过程简单记录及EFI分享](https://bbs.pcbeta.com/viewthread-1877600-1-1.html)

### [asrock-Deskmini-h310-hackintosh-EFI](https://github.com/TWanGT/asrock-Deskmini-h310-hackintosh-EFI)




