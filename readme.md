> 原项目仓库地址：[gtf35/BLESerial: Android 蓝牙串口 SPP 工具类 + Demo](https://github.com/gtf35/BLESerial)

电子系统设计课程设计配套应用程序，小车的蓝牙遥控器。

![Screenshot_20210915_190846_top.gtf35.bleserial](.\Screenshot_20210915_190846_top.gtf35.bleserial.jpg)

+ 使用：按住按钮维持运动状态，松开按钮停车，由于小车程序设置，底下三个按钮按下后只生效一次。

+ 发送命令数据如下：

+ | 命令     | 数据       |
  | -------- | ---------- |
  | 停车     | 0xFA, 0x00 |
  | 前进     | 0xFA, 0x01 |
  | 左转     | 0xFA, 0x02 |
  | 右转     | 0xFA, 0x03 |
  | 后退     | 0xFA, 0x04 |
  | 鸣笛     | 0xFA, 0x05 |
  | 切换模式 | 0xFA, 0x06 |
  | 上锁解锁 | 0xFA, 0x07 |
  | 调整速度 | 0xFA, 0x08 |

  
