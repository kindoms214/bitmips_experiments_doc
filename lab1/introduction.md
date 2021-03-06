# lab1 跑马灯 & 数码管

本实验是很简单的基础实验，大家可以选择性的来做。

## 实验要求
- 能够使用 Vivado 工具创建项目
- 能够编写简单的 Verilog 代码
- 能够看懂仿真文件，并尝试自己写仿真文件
- 能够创建管脚约束文件
- 能够将本实验中的两个小实验分别通过仿真测试
- 能够将本实验中的两个小实验分别下板至精工开发板并达到要求效果

## 实验内容
本实验包括两个部分。

### 跑马灯实验
本实验需要使用 Vivado 来创建一个工程，并且编写简单代码，实现一个跑马灯的效果，需要使用的板载资源是精工开发板上的 8 个 led 灯。如何实现跑马灯的效果？一个简单的思路就是每隔一段固定时间就让 8 个 led 灯逐个亮起来，每次只保证一个亮。依次循环往复。

[跑马灯实验流程指导](./led.md)

本系列实验只有跑马灯这一个实验工程需要手动创建，其他所有实验的工程都已创建好，请先将[实验代码](https://github.com/bit-mips/bitmips_experiments)克隆至本地。

### 数码管显示实验
本实验需要使用的板载资源是精工开发板上的 8 个 7 段数码管，数码管要求能够显示 0 ~ 9、a ~ f 即能够表示 16 进制中的16个字符。

[数码管显示实验流程指导](./num_led.md)

此实验不用再重新手动创建工程，只需使用 Vivado 打开 `lab1` 下的 `num_led` 工程即可，然后在其中填写代码。
