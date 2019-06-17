1、根据需要更新的内容把以下对应文件拷贝到SD卡：

 (1)、更新配置文件：mks_config.txt
 (2)、更新图片：    mks_pic
 (3)、更新字库：    mks_font
 (4)、更新TFT固件： mkstft35.bin
 (5)、更新Wifi固件：MksWifi.bin

2、使用SD卡更新配置文件时，需要把配置文件名修改为：mks_config.txt

3、可以参考Example文件夹中的例程。

4、TFT70_V1.0.2修改内容：
（1）、修复回零界面“关闭电机”不工作问题
（2）、修复网络打印有时不转发数据的问题
（3）、双喷头打印中“变速”后“返回”喷头挤出不对
（4）、添加bootloader翻转功能
（5）、修改读卡错误打印停止问题
（6）、修复5次rend重定行出错问题

//////////////////////////////////////////////////////////////

1,According to the content that needs to be updated, copy the following file to the SD card:

 (1)、update the config file：mks_config.txt
 (2)、update images：         mks_pic
 (3)、update font：           mks_font
 (4)、update TFT firmware：   mkstft35.bin
 (5)、update Wifi firmware：  MksWifi.bin

2,When using the SD card to update the configuration file, you need to change the configuration file name to: mks_config.txt

3, You can refer to the Example folder's routines.

4, The firmware of V_1.0.2 modified content :
(1)、Fix the bug that "zero" interface "turn off the motor" does not work.
(2)、Fix the bug that network printing does not transfer data sometimes.
(3)、Fix the bug that extrusion is error after change print speed and return in the double nozzle printing.
(4)、Added the ablity to display rotation of bootloader.
(5)、Fix the bug that print stop due to card reading error.
(6)、Fix the bug that define line number error after 5 times resend.


