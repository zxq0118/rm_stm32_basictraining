#F103外接LED点灯实验

板卡：STM32F103C8T6,HSE=8MHZ,系统时钟=72MHZ

接线：PA13/SWDI0,PA14/SWCLK,GND/GND;独立3.3V电源

LED:PA0,低电平点亮

打开：rm_training/rm_f103_ledblink_HAL_Delay/MDK-ARM/rm_f103_ledblink_HAL_Delay.uvprojx

构建：Keil Build,下载后复位

现象：LED亮250ms,灭250ms
