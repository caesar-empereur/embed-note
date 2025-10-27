## 串口
```
arduino 里的 Serial 串口对象, 在 Arduino IDE 的串口监视器中显示信息，其实这个 Serial，
	就是在 HardwareSerial.h 头文件中定义好的，相当于 esp32 的 0 号串口, 这个 0 号串口没有引脚标注
	是 esp 32 内置的与 pc 连接的串口，用来下载固件，与pc 通信
	HardwareSerial 类是用于访问和控制硬件串口的主要类。你可以使用预定义好的
	HardwareSerial 对象（Serial、Serial1、Serial2 分别对应了 UART0、UART1 和 UART2。）
	与特定的硬件串口进行通信
```