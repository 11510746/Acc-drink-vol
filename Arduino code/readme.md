1.  correct 文件夹下包含一个 arduino程序，对前 2000 个 mpu6050 数据求平均，用于校正 mpu6050 的六轴数据。
2.  mpu6050 文件下包含一个 arduino程序，从寄存器读取三轴加速度数据，并进行校正等处理，然后发送到串口和蓝牙设备。程序对 y 轴加速度设了阈值，仅当杯子被拿起，或桌面震动超过阈值时，才会发送数据。