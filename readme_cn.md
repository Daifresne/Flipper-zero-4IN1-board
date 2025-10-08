# 该版本pcb已验证，为防止恶意申请专利以及倒卖现象，目前将不开源该项目相关源文件，仅开源足够复刻使用的相关文件。

# Flipper Zero ESP32 Marauder&NRF24&CC1101&L80-R 4 IN 1 board
[English Version](readme.md)

##  Flipper Zero ESP32 Marauder&NRF24&CC1101&L80-R 4 IN 1 board  设计文件

## 内容:
* /PCB - PCB gerber文件 - Daifresne （TSGP工作室）

* /bin - 烧录程序 - 别抱我幼辞 （万家科技）

* /STL - 外壳模型 - zjywlive



## 许可：
* 设计采用 GNU GENERAL PUBLIC LICENSE V3.0 - 许可。详情请查看 LICENSE 文件。

* 设计按原样提供，zjywlive、TSGP LAB以及万家科技不对使用这些设计可能引起的任何损害或伤害负责。

* 开源许可协议允许私人使用，TSGP LAB保留硬件-原理图&PCB设计专利的权利，万家科技保留-程序设计专利的权限，zjywlive保留硬件-外壳模型设计专利的权利。不允许将设计未经许可用于商业目的。如果你想将设计用于商业目的，请先与我们了解详情。



## 复刻指南：
1、请根据/pcb file/BOM_元件配单用——4in1 - TSGP LAB 内列举的元件进行购买，然后在pcb制造厂家的下单界面下单/pcb file/Gerber_4in1.zip 。然后您可以根据BOM中的元件位号配合pcb上的元件位号进行焊接。

2、在pcb的元件焊接完成后，你需要在/bin file 中找到你需要的固件版本，中文固件为“4OR1.bin”，英文固件为“4OR1_en.bin”,然后使用usb to ttl烧录器连接esp 01f模块上的ttl接口进行固件烧录。

3、如果您想使用外壳保护pcb，您可以在/STL FILE中下载外壳模型，并进行3d打印后安装。



## 使用指南：
在上述复刻指南内容都完成后，您可以通过esp32 s3附近的usb-c接口为它烧录你喜欢的固件来配合Flipper ZERO使用，此处不对esp32 s3固件进行列举。您可以通过oled屏幕旁边的按钮进行模块的开关以及切换。
