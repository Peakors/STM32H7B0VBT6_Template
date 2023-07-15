# STM32H7B0VBT6 Template

基于反客STM32H7B0VBT6核心板的CLion + CubeMX + CMake + OpenOCD的外部Flash下载算法模板

感谢群友`子衿`、`JasonGu`、`汪老二`的帮助

文档参考资料：www.armbbs.cn/forum.php?mod=viewthread&tid=116240

适配板子：`FK7B0M1-VBT6半孔版` & `FK7B0M2-VBT6直插版` & `FK7B0M1-VBT6板对板`

外置Flash下载算法使用1-1-1模式和Read Data(0x03)指令，参考W25Q64JV参考手册`8.1.2 Instruction Set Table 1 (Standard SPI Instructions)`

Debug时看到该提示表示成功进入Debug模式：

> Info : flash1 'win w25q64fv/jv' id = 0x1740ef size = 8192 KiB(((READY)))
> Info : Listening on port 4444 for telnet connections
> Info : accepting 'gdb' connection on tcp/3333
> Info : New GDB Connection: 1, Target STM32H7B0VBT6.cpu0, state:Debugger connected to tcp:localhost:3333
halted

