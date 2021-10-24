# Hackintosh : ASRock Deskmini H310/COM



## 适用版本

macOS Big Sur 11.5.2  OpenCore 0.7.4


## 检查项

- [x] apple store 账号使用正常
- [x] 睡眠正常
- [x] 开关机正常
- [x] usb2.0 & 3.0 基本正常 已定制
- [x] DP输出2K显示正常 未测试HDMI
- [x] 蓝牙正常 必须接天线 信号才好
- [x] 无线正常 必须接天线 信号才好


## 主机配置

|                准系统 | ASRock Deskmini H310/COM  |
|                  CPU | I5-8400                   |
|                  显卡 | 核显 UHD 630              |
|                  内存 | 威刚 万紫千红 DDR4 2666 8G * 2       |
|             网卡&蓝牙  | BCM943602CS+NGFF A/E转接卡+IPX转SMA天线              |
|                  硬盘  | 西数 512G M.2固态         |
|                  散热器 | IS40X                   |


## 使用方法

1. 按照黑果小兵的介绍一步步安装

2. 安装完成，使用别的电脑挂载硬盘efi分区

3. 拷贝替换同名目录下文件即可

   ###  安装前BIOS 设置

   1. USB Configuration  XHCI Hand-off :  `Enabled`
   2. Onboard HD Audio : ` Enabled`
   3. Security boot : `Disabled`
   4. others :` Default`



## 特别感谢

### [leogitpro](https://github.com/leogitpro)/**[Hackintosh-DeskMini310](https://github.com/leogitpro/Hackintosh-DeskMini310)**

### [【黑果小兵】macOS Catalina 10.15 19A583 正式版 with Clover 5096原版镜像[双EFI双平台版]](https://blog.daliansky.net/macOS-Catalina-10.15-19A583-Release-version-with-Clover-5093-original-image-Double-EFI-Version.html)

### [解决安装黑苹果macOS Catalina 10.15 Beta1 USB3.0或USB3.1无法使用](https://osx.cx/fix-hackintosh-macos-catalina-10-15-beta1-usb3-0.html)









