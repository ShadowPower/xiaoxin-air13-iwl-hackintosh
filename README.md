# Lenovo 小新 Air13 IWL 黑苹果EFI

驱动和配置文件来自于网络和其他 repo。除了指纹不能用，其余全部正常。

HDMI 和 DP (Type-C) 接口均可输出视频信号，支持热插拔。

安装 ALCPlugFix 之后，声卡支持耳机/扬声器切换，耳机/扬声器的音质表现和 Windows/Linux 下差异不大。

更换 DELL DW1820A (WiFi: 1028:075A) (BT: 0A5C:6414) 无线网卡，蓝牙、WiFi、AirDrop 可以正常使用。

需要在 BIOS 中关闭 MX150 独显以避免额外的耗电和发热。



注：不一定适用于所有的 Lenovo 小新 Air13 IWL，我并不能正常使用 daliansky 的配置。同型号机型可能会存在差异。



其他信息：

* 联想笔记本 DW1820A 屏蔽针脚：[https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html)

* 开启 HIDPI：[https://github.com/xzhih/one-key-hidpi](https://github.com/xzhih/one-key-hidpi)



## 详细配置

| 规格      | 详细信息                                                     |
| -------- | ------------------------------------------------------------ |
| 电脑型号  | Lenovo Xiaoxin Air13 IWL                        |
| 操作系统 | macOS Mojave 10.14.6 (18G1012)                            |
| 处理器   | Intel(R) Core(TM) i5-8265U CPU @ 1.80GHz                       |
| 内存     | 8 GB  LPDDR3 超频至 2133MHz                             |
| 硬盘     | WD BLACK SN750 1TB          |
| 显卡     | Intel UHD Graphics 620 (8086:3EA0 Whiskey Lake) platform-id:0x3e9b0000     |
| 显示器   | FHD 1920x1080 (13.3 英寸)                                        |
| 声卡     | ALC236 (layout-id:99)                                           |
| 网卡     | DELL DW1820A (WiFi: 1028:075A) (BT: 0A5C:6414) |
