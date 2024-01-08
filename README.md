# proj-support-riscv-for-platformio

### 项目名称
为PlatformIO在RISC-V平台上提供支持

### 项目描述
PlatformIO是开源的物联网开发生态系统，提供了跨平台的代码构建器、集成开发环境。本项目的目标是实现PlatformIO可以在基于RISC-V平台的DC-ROMA笔记本上运行，并且能够成功构建MicroBlocks smallvm固件。

### 所属赛道
2024全国大学生操作系统比赛的“OS功能挑战”赛道

### 参赛要求
- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的学生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖 
- 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求 

### 项目导师
廖俊波
- github: https://github.com/DC-DeepComputing-Activity
- email: junbo.liao@deepcomputing.io

### 难度
较高

### 特征
- 了解单片机
- 了解RISC-V体系
- 全球首款RISC-V笔记本电脑DC-ROMA上进行开发构建

### 参考文档
- MicroBlocks smallvm固件源码: https://bitbucket.org/john_maloney/smallvm
- PlatformIO CLI源码: https://github.com/platformio/platformio-core
- PlatformIO对SiFive的支持(仅供参考): https://github.com/platformio/platform-sifive

### License
MIT license (LICENSE-MIT or http://opensource.org/licenses/MIT)

## 预期目标
第一题: 构建已支持型号的主板固件
1. 在DC-ROMA笔记本上，使PlatformIO CLI或者IDE可以正常运行。
2. 在DC-ROMA笔记本上，完成使用PlatformIO构建任意两个不同型号主板的MicroBlocks smallvm固件。

第二题: 构建未支持型号的主板固件 (附加题)
1. 完成PlatformIO对ESP32 C3/C6开发板的支持。
2. 完成smallvm对ESP32 C3/C6开发板的支持。
3. 在DC-ROMA笔记本上，使用PlatformIO能构建用于ESP32 C3/C6开发板的smallvm固件。
