# proj197-GDB-stub-on-OneOS
## 项目描述
OneOS是中移物联网发布的面向物联网领域的、可裁剪的实时操作系统。拥有比较丰富的调试手段，已通过GDB实现了系统和用户任务的调试，在调试链路上支持串口。
赛题的目标是在 OneOS 上实现一个 GDB stub，可以在没有硬件调试器的情况下，通过串口对部署 OneOS系统的软件进行源代码级调试。调试环境由宿主机 GDB 和目标机调试 stub 共同构成，两者通过串口连接，使用 GDB 远程串行协议 RSP 协同工作，实现对目标机上的系统内核和上层应用的监控和调试功能。
本项目可以帮助学生熟悉系统调试原理，了解调试协议。

## 源码
- [gdbstub](https://github.com/mborgerson/gdbstub.git)

## 项目导师
张猛
- github edward518
- email zhangmeng<zhangmeng@cmiot.chinamobile.com>

## 难度
中等

## 文档
- [OneOS文档中心](https://os.iot.10086.cn/v2/doc/homePage)

## License
Apache 2.0(https://www.apache.org/licenses/LICENSE-2.0.html)
预期目标
注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标
第一题：完成OneOS GDB stub 基本功能开发
- 在 OneOS提供的开发版上，完成 OneOS gdb stub 开发，能通过串口调试系统内核，实现单步、断点、读写内存。

**选择该赛题的支持**  
开发套件支持：提供给参赛队伍开发套件，此开发板万耦天工板载STM32 F103芯片:144引脚，512K FLASH，支持GSM/GPRS /LORA /WIFI/蓝牙、LCD、摄像头、温湿度等模块。并具有丰富的例程demo，OneOS学院提供手把手教学视频，方便同学们上手使用。  
获奖激励：公司对获奖同学提供入职绿色通道，获得全国总决赛二等奖、三等奖的同学可以免笔试，直接进入面试环节。获得全国总决赛一等奖的同学可以直接进入终面环节。  
技术答疑指导：针对OneOS操作系统及本赛题技术要点，资深研发工程师提供专业的技术支持、指导，全程辅导技术方案的实现。  
技术资料：提供相关技术资料和对应索引，指导赛题方向。  
