# STM32简单功能的手表
开发环境：Cubeide(HAL库)
芯片：STM32F407VET6

实现功能：
1. 实时显示时间，年月日，周期，且掉电后不重置
2. 可自定义修改主页时间
3. 有闹钟，秒表，倒计时功能
4. 可通过按键使设备进入待机模式，关闭不需要的外设，降低功耗，也可按键唤醒
5. 多级菜单系统控制OLED显示要调用的功能
6. 长按按键进入低功耗STOP模式

所使用的芯片外设：GPIO，SPI，RTC，Timer， 待机功能
外设模块：SPI通信协议的OLED屏幕，按键

未来改进方向：加个动画，加上9轴传感器，或者蓝牙，WIFI等，实现更多的智能功能
Commit 1 line
Commit 2 line
Commit 3 line
Commit 4 line
Commit 5 line
Commit 6 line
Commit 7 line
Commit 8 line
Commit 9 line
