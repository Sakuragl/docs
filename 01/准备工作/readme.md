>此次演示ROM为Dotos5.2
>其它ROM的刷入方式大同小异

## 解BootLoader锁

- 下载[ADB工具包](https://download.sakuragl.ml/Quark/7T/ADB%E5%B7%A5%E5%85%B7%E5%8C%85)- 装ADB驱动
- 打开CMD输入<u>adb.exe</u>的位置
- 输入<u>adb version</u>检查是否成功
- 键入**fastboot flashing unlock**选择确认即可成功解锁bl

## 刷入第三方Recovey
- 下载[twrp](https://download.sakuragl.ml/Quark/7T/rec/twrp-installer-3.6.2_11-0-hotdogv2.zip)
- 打开~~某某助手（bushi~~ 
- 打开ADB工具包输入fastboot flash **recovery**+<u>rec目录</u>
- 完成
