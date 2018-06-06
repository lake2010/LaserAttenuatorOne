激光衰减器 一代 V1.2.0

License:
	All contributions by Chen.
	Copyright (c) 2018 Chen.
	All rights reserved.	

https://github.com/Chen-0810
Email:Chen.0810@outlook.com

更新日志： 
	V1.2.0	2018/06/06	优化代码，并发布于Github。

引脚说明：Silicon C8051
	P0.0：步进电机驱动 脉冲
	P0.1：步进电机驱动 方向（与V2.x硬件差异，故不可混用）
	P0.2：步进电机驱动 使能（与V2.x硬件差异，故不可混用）
	P0.4：Txd
	P0.5：Rxd
	P0.6：常输出 低电平 准双向I/O
	P0.7：常输出 低电平 准双向I/O
	
	P1.5：零点检测开关 低电平触发 准双向I/O
	
	P3.1：串口驱动芯片Rxd-Re
	P3.2：串口驱动芯片Txd-De
	P3.3：步进电机驱动 细分；常输出 低电平
	P3.4：步进电机驱动 细分；常输出 低电平

