# Roboard-Pro
> 无敌增强版Arduino开发板



# 对比原生的Arduino UNO 具备如下特性：

* 管脚和库100%兼容Arduino UNO

* 在UNO的基础上增加了两路电机驱动（L298P，最大4A电流输出，可开窗上锡进一步过载），自锁式电机线接口

* 在UNO的基础上增加了一个IMU（MPU6050）

* 在UNO的基础上增加了一块蓝牙模块（HC-05）

* 所有外设都是用跳线焊盘连接，可以自行选择断开或连接

* 使用Mega32U4芯片，自带两个串口，下载串口和蓝牙串口不冲突

* 修改了Bootloader解决Leonardo复位慢的问题

* 配套无线APP（可控Ctrl、颜艺Boy、迹 等，通过蓝牙连接）

* 更多细节优化

  ​

# 使用方法

* PCB文件可以直接打样，元器件选型原理图里都有标出
* 将software文件夹内的文件全部复制到Arduino IDE的 \hardware\arduino\avr 文件夹内，可以覆盖，不会删除原有的功能
* 重启IDE，选择板卡 - Roboard，即可正常使用



# 管脚分配（待补充）



> 个人主页：www.pengzhihui.xyz

