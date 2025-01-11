
## 简介


Super RP2350B 是一款紧凑型 RP2350 开发板，旨在嵌入空间有限的项目中。它包含运行强大的 RP2350B 芯片所需的组件（即晶体、调节器和必要的支持电路）、强大的8MB PSRAM和惊人的16MB 闪存。请注意，它没有 LED、按钮或 USB 连接器 - 您需要连接自己的 USB 连接器才能对其进行编程。

所有这些大幅修剪意味着您将获得一个 25.4 毫米见方的小空间和大量暴露的 RP2350 引脚。其中 48 个可用作通用 I/O（比 Raspberry Pi Pico 多 18 个 I/O！），8 个配备 ADC。我们甚至设法挤进了一些微小的引脚标签来帮助识别它们。




### 产品特点

- 采用 RP2350B（双 Arm Cortex M33，运行速度高达 150MHz，配备 520KB SRAM）
- 支持 XiP 的 16MB QSPI 闪存
- 8MB PSRAM（CS 通过可切割走线连接至 GP47）
- 晶体振荡器
- 板载 3V3 稳压器（最大稳压器电流输出 300mA）
- 64 个引脚，以 2.54 毫米 (0.1") 间距排列在引脚网格阵列中
- 48 个多功能通用 IO（8 个可用于 ADC）
- 6 GND 引脚
- 输入电压范围 3V - 5.5V（仅在 VB 引脚上）
- 尺寸：约 25.4 毫米 x 25.4 毫米 x 3.6 毫米（长 x 宽 x 高）
- 可使用 C/C++ 或 MicroPython 编程

### 引脚图

<img src="https://github.com/WMnologo/SuperRP2350B/blob/main/img/1.png"  />

<img src="https://github.com/WMnologo/SuperRP2350B/blob/main/img/2.png"  />

### 尺寸图

<img src="https://github.com/WMnologo/SuperRP2350B/blob/main/img/4.png"  />

### 原理图

<img src="https://github.com/WMnologo/SuperRP2350B/blob/main/img/3.png"  />

### PCB封装

[Super RP2350B PCB封装](https://github.com/WMnologo/SuperRP2350B/tree/main/hardware "")

### 3D模型

[Super RP2350B 3D模型](https://github.com/WMnologo/SuperRP2350B/tree/main/3DModel "")




