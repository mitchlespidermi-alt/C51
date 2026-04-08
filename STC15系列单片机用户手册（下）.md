例如：假设读到�RAM区�F8单元的内容�为 $8 0 \mathrm { H }$ ，�F9单元的内容�为00�H，即内�部掉电唤醒定时器的时钟频率[WIRC_H,WIRC_L]为 $3 2 7 6 8 \mathrm { H z }$ ，则内�部掉电唤醒专用定时器最短��计数 时间(即�数一 次的时间)为： ${ \frac { 1 0 ^ { 6 } \mathrm { u S } } { 3 2 7 6 8 } } \mathrm { ~ x ~ } 1 6 \mathrm { ~ x ~ } 1 \approx 4 8 8 . 2 8 \mathrm { u S }$ 

内部掉电唤醒专用定时器最长计数 时间约为 $4 8 8 . 2 8 \mathrm { u s } \times 3 2 7 6 8 = 1 6 \mathrm { S }$ 

设定{WKTCH[6:0],WKTCL[7:0]}寄存器的值等于9 �� �的时钟频率[WIRC_H,WIRC_L]为32768Hz, 则从系统掉电到启动系统振荡 器，所需要等待的时间为 $4 8 8 . 2 8 \mathrm { u S \times 1 0 \approx 4 8 8 2 . 8 u S }$ 

设定{WKTCH[6:0],WKTCL[7:0]}寄存器的值等于32767(即最大��计数 $= 3 2 7 6 8 = 2 ^ { 1 5 } ,$ )内部掉电唤醒定时器的时钟频率[WIRC_H,WIRC_L]为32768Hz, 则从系统掉电到启动系统振荡 器，所需要等待的时间为 $4 8 8 . 2 8 \mathbf { u } \mathbf { S } \times 3 2 7 6 8 = 1 6 \mathbf { S }$ 

下面给出了在读到RAM区F8单元的内容为80H，F9单元的内容为00H，即内部掉电唤醒定时器的时钟频率[WIRC_H,WIRC_L]为32768Hz情况下， �掉电唤醒专用定时器的��时间

$$
\{\text {W K T C H} [ 6: 0 ], \text {W K T C L} [ 7: 0 ] \} = 0, \quad 4 8 8. 2 8 \mathrm {u S} \times 1 = 4 8 8. 2 8 \mathrm {u S}
$$

$$
\{\text {W K T C H} [ 6: 0 ], \text {W K T C L} [ 7: 0 ] \} = 9, \quad 4 8 8. 2 8 \mathrm {u S} \times 1 0 = 4. 8 8 2 8 \mathrm {m S}
$$

$$
\{W K T C H [ 6: 0 ], W K T C L [ 7: 0 ] \} = 9 9, \quad 4 8 8. 2 8 u S x 1 0 0 = 4 8. 8 2 8 m S
$$

$$
\{W K T C H [ 6: 0 ], W K T C L [ 7: 0 ] \} = 9 9 9, \quad 4 8 8. 2 8 u S x 1 0 0 0 = 4 8 8. 2 8 m S
$$

$$
\{W K T C H [ 6: 0 ], W K T C L [ 7: 0 ] \} = 4 0 9 5, \quad 4 8 8. 2 8 u S x 4 0 9 6 = 2. 0 S
$$

$$
\{\text {W K T C H} [ 6: 0 ], \text {W K T C L} [ 7: 0 ] \} = 3 2 7 6 7, \quad 4 8 8. 2 8 \mathrm {u S} \times 3 2 7 6 8 = 1 6 \mathrm {S}
$$

再假设读到RAM区F8单元的内容为7 9H，F9单元的内容为18H，即内部掉电唤醒定时器的时钟频率[WIRC_H,WIRC_L]为 $3 1 0 0 0 \mathrm { H z }$ ，则内�部掉电唤醒专用定时器最短��计数 时间(即���次的时间)为： ${ \frac { 1 0 ^ { 6 } \mathrm { u S } } { 3 1 0 0 0 } } \mathrm { ~ x ~ } 1 6 \mathrm { ~ x ~ } 1 \approx 5 1 6 . 1 3 \mathrm { ~ u S }$ 

内部掉电唤醒专用定时器最长计数 时间约为 $5 1 6 . 1 3 \mathrm { u s } \times 3 2 7 6 8 \approx 1 6 . 9 5$ 

设定{WKTCH[6:0],WKTCL[7:0]}寄存器的值等于9 �� �的时钟频率[WIRC_H,WIRC_L]为31000Hz, 则从系统掉电到启动系统振荡 器，所需要等待的时间为 $5 1 6 . 1 3 \mathrm { u S } \mathrm { ~ x ~ } 1 0 \approx 5 1 6 1 . 3 \mathrm { u S }$ 

下面给出了在读到RAM区F8单元的内容为7 9H，F9单元的内容为18H，即内部掉电唤醒定时器的时钟频率[WIRC_H,WIRC_L]为31000Hz情况下， �掉电唤醒专用定时器的��时间

$$
\{\text {W K T C H} [ 6: 0 ], \text {W K T C L} [ 7: 0 ] \} = 0, \quad 5 1 6. 1 3 \mathrm {u S} \times 1 \quad \approx 5 1 6. 1 3 \mathrm {u S}
$$

$$
\{W K T C H [ 6: 0 ], W K T C L [ 7: 0 ] \} = 9, \quad 5 1 6. 1 3 u S x 1 0 \approx 5. 1 6 1 3 m S
$$

$$
\{\text {W K T C H} [ 6: 0 ], \text {W K T C L} [ 7: 0 ] \} = 9 9, \quad 5 1 6. 1 3 \mathrm {u S} \times 1 0 0 \approx 5 1. 6 1 3 \mathrm {m S}
$$

$\{\mathrm{WKTCH}[6:0],\mathrm{WKTCL}[7:0]\} = 999,$ $516.13\mathrm{us}\times 1000\approx 516.13\mathrm{mS}$ $\{\mathrm{WKTCH}[6:0],\mathrm{WKTCL}[7:0]\} = 4095,$ $516.13\mathrm{us}\times 4096\approx 2.1\mathrm{S}$ $\{\mathrm{WKTCH}[6:0],\mathrm{WKTCL}[7:0]\} = 32767,$ $516.13\mathrm{us}\times 32768\approx 16.9\mathrm{S}$ 

又假设读到RAM区F8单元的内容为80H，F9单元的内容为E8H，即内部掉电唤醒定时器的时钟频率[WIRC_H,WIRC_L]为 $3 3 0 0 0 \mathrm { H z }$ ，则内�部掉电唤醒专用定时器最短��计数 时间(即���次的时间)为： $\frac { 1 0 ^ { 6 } \mathrm { u S } } { 3 3 0 0 0 } \mathrm { ~ x ~ } 1 6 \mathrm { ~ x ~ } 1 \approx 4 8 4 . 8 5 \mathrm { u S }$ 

内部掉电唤醒专用定时器最长计数 时间约为 $4 8 4 . 8 5 \mathrm { u s } \times 3 2 7 6 8 \approx 1 5 . 8 9 \mathrm { S }$ 

设定{WKTCH[6:0],WKTCL[7:0]}寄存器的值等于9 �� �的时钟频率[WIRC_H,WIRC_L]为33000Hz, 则从系统掉电到启动系统振荡 器，所需要等待的时间为 $4 8 4 . 8 5 \mathrm { u S \times 1 0 \approx 4 8 4 8 . 5 u S }$ 

下面给出了在读到RAM区F8单元的内容为80H，F9单元的内容为E8H，即内部掉电唤醒定时器的时钟频率[WIRC_H,WIRC_L]为33000Hz情况下， �掉电唤醒专用定时器的��时间

$\{\mathrm{WKTCH}[6:0],\mathrm{WKTCL}[7:0]\} = 0,$ 484.85uS x 1 $\approx 484.85\mathrm{uS}$ $\{\mathrm{WKTCH}[6:0],\mathrm{WKTCL}[7:0]\} = 9,$ 484.85uS x 10 $\approx 4.8485\mathrm{mS}$ $\{\mathrm{WKTCH}[6:0],\mathrm{WKTCL}[7:0]\} = 99,$ 484.85uS x 100 $\approx 48.485\mathrm{mS}$ $\{\mathrm{WKTCH}[6:0],\mathrm{WKTCL}[7:0]\} = 999,$ 484.85uS x 1000 $\approx 484.85\mathrm{mS}$ $\{\mathrm{WKTCH}[6:0],\mathrm{WKTCL}[7:0]\} = 4095,$ 484.85uS x 4096 $\approx 1.986\mathrm{S}$ $\{\mathrm{WKTCH}[6:0],\mathrm{WKTCL}[7:0]\} = 32767,$ 484.85uS x 32768\~15.89S 

如果 掉电唤醒定时器被允许（WKTEN=1），同时用户也将外部中断打开了。进入 掉地模式后，当外部中断提前将单片机从停机模式唤醒时，可以通过读WKTCL和WKTCH的内容(实际是读WKTCL_CNT和WKTCH_CNT中的内容)，可以读出单片机在停机模式/掉电模式等待的时间。

# /*利用内部专用掉电唤醒定时器来唤醒掉电模式的示例程序（C程序）

# 1. C程序：

/* -*/ 

/* --- STC MCU Limited. - --*/ 

/-/* --- 演示STC15F2K60S2 系列 掉电唤醒定时器举例--- -*/

/* --- 研发顾问QQ：800003751- *

/* --- Fax: 86-755-82905966 * 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果 要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果 要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可- *

/*- */ 

//假定测试芯片的工作 频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

//- 

sfr WKTCL $=$ 0xaa; //掉电唤醒定时器计时低字节

sfr WKTCH $=$ 0xab; //掉电唤醒定时器计时高字节

sbit P10 P1^0; 

void main() 

{ WKTCL $=$ 49; //设置唤醒周期为 $488\mathrm{us}^{*}(49 + 1) = 24.4\mathrm{ms}$ WKTCH $=$ 0x80; //使能掉电唤醒定时器

while(1) { $\mathrm{PCON} = 0\mathrm{x}02;$ //进入掉电模式 _nop_(); _nop_; P10 $= !$ P10; //掉电唤醒后，取反测试口 }

# 2. 汇编程序：

/*- -*/ 

/* --- STC MCU Limited. - -*/ 

/-/* --- 演示STC15F2K60S2 系列 掉电唤醒定时器举例-- -*/

/* --- 研发顾问QQ：800003751- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果 要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果 要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可- *

/* */ 

//假定测试芯片的工作 频率为18.432MHz

WKTCL DATA 0AAH //掉电唤醒定时器计时低字节

WKTCH DATA 0ABH //掉电唤醒定时器计时高字节

ORG 0000H 

LJMP MAIN 

//复位入口

ORG 0100H 

MAIN: MOV SP, #3FH 

MOV WKTCL, #49 //设置唤醒周期为488us*(49+1) = 24.4ms

MOV WKTCH,#80H //使能掉电唤醒定时器

LOOP: 

MOV PCON, #02H 

//进入 掉电模式

NOP 

NOP 

CPL P1.0 //掉电唤醒后,取反测试口

JMP LOOP 

SJMP $ 

END 

# 7.9 外部管脚T0/T1/T2/T3/T4如何唤醒掉电模式/停机模式

如果 定时器(T0/T1/T2/T3/T4)的中断在进入 掉电模式/停机模式前已经被允许，即ET0/ET1/ET2/ET3/ET4及EA在进入 掉电模式/停机模式前已经被置为1，则进入 掉电模式/停机模式后定时器仍继续工作 ，且定时器T0/T1/T2/T3/T4的外部管脚(T0/P3.4,T1/P3.5,T2/P3.1,T3/P0.7,T4/P0.5)如发生由高到低的变化可以将MCU从掉电模式/停机模式唤醒。当MCU由定时器T0/T1/T2/T3/T4的外部管脚由高到低的变化唤醒时，如果主 时钟使用的是内部系统时钟(� ��ISP烧录 程序时自行设置)，MCU�在等�待6��4个 时�钟后，����就认为此���时系统�时钟�从开始��起振�的不稳定状态已经过渡到稳定状态,�就将时���钟供给 C�PU������工作 ；如果主 时�钟使用的是外�部晶体或时�钟(�户在ISP烧录 程序时自行设置)，MCU�在等�待10���24个 时�钟后，����就认为此 时系�统时�钟从��开始 起�振的不稳定状态已经过渡到稳定状态,�就将时���钟供给 C�PU���工作 ；C�PU�获得时�钟后，程�序从上次片机进入 掉电模式语句 的下一条语句开始往 �执行 �� �

# 第8章 串行口通信

除STC15F101W系列无串行口功能外，其他STC15系列单片机都有串行口功能，其中STC-15W4K60S4系列单片机有4个 高速异步串行通信端口、STC15F2K60S2系列单片机有2个 高速异步串行通信端口、STC15W1K16S/STC15W408S/STC15W408AS/STC15W201S/STC15F408AD系列单片机有1个高速异步串行通信端口，如下 表所示：

下表总结了STC15系列单片机内置了高速异步串行通信端口的单片机型号：

<table><tr><td>高速异步串行通信端口单片机型号</td><td>串行口1</td><td>串行口2</td><td>串行口3</td><td>串行口4</td></tr><tr><td>STC15W4K60S4系列</td><td>✓</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td>STC15F2K60S2系列</td><td>✓</td><td>✓</td><td></td><td></td></tr><tr><td>STC15W1K16S系列</td><td>✓</td><td></td><td></td><td></td></tr><tr><td>STC15W408S系列</td><td>✓</td><td></td><td></td><td></td></tr><tr><td>STC15W408AS系列</td><td>✓</td><td></td><td></td><td></td></tr><tr><td>STC15W201S系列</td><td>✓</td><td></td><td></td><td></td></tr><tr><td>STC15F408AD系列</td><td>✓</td><td></td><td></td><td></td></tr><tr><td>STC15F101W系列</td><td></td><td></td><td></td><td></td></tr></table>


上表中√表示对应的系列有相应的串行口。


现以STC15W4K60S4系列单片机为例，介绍STC15系列单片机的串行通信端口。

STC15W4K60S4系列单片机具有4个 采用UART(Universal Asychronous Receiver/Transmitter)工作 方式的全双工 异步串行通信接口(串口1、串口2、串口3和串口4)。每个串行口由2个数 据缓冲器、一个 移位寄存器、一个 串行控制寄存器和一个 波特率发生器等组成。每个串行口的数据缓冲器由���2个互 相独立的接收、发�送缓冲器构成，可以同时发�送和接收�数据�。发�送缓冲器只能写入而不能读出，接收缓冲器只能读出而不能写入，因而两个缓冲器可以共用一个 地址码。串行口1的两个缓冲器共用的地址码是99��H；串行口2�的两个�缓冲器共用的地址码是 ��H3的两个缓冲器共用的地址码是ADH��；串行口�4的两�个缓冲器共用的地址码是 ��H个缓冲器统称串行通信特殊功能寄存器�SBU��F；串行口�2的两�个缓冲器�统称串行通信特殊功能寄存器��S2BUF��；串行口3的两�个缓冲器�统称串行通信特殊功能寄存器�S3BU��F；串行口�4的两�个缓冲器统称串行通信特殊功能寄存器��S4 �F

STC15W4K60S4系列单片机的串行口1有4种工作 方式，其中两种方式的波特率是可变的，另两种是固定的，以供不同应用场合选用。串行口2/串行口3/串行口4都只有两种工作 方式，这两种方式的波特率都是可变的。用户可用软件设置不同的波特率和选择不同的工作 方式。主 机可通过查询或中断方式对接收/发送进 行程序处理，使用十分灵活。

STC15W4K60S4系列单片机串行口1对应的硬件部分是TxD和RxD。串行口1可以在3组管

脚之间进行切换。通过设置特殊功能寄存器AUXR1/P_SW1中的位S1_S1/AUXR1.7和S1_S0/P_SW1.6，可以将串行口1从[RxD/P3.0,TxD/P3.1]切换到[RxD_2/P3.6,TxD_2/P3.7]，还可以切换到[RxD_3/P1.6/XTAL2,TxD_3/P1.7/XTAL1]。注意，当串行口1在[RxD_2/P1.6, TxD_2/P1.7]时，系统要使用内部时钟。 串口1建议放在[P3.6/RxD_2,P3.7/TxD_2]或[P1.6/RxD_3/XTAL2,P1.7/TxD_3/XTAL1]上。

STC15W4K60S4系列单片机串行口2对应的硬件部分是TxD2和RxD2。串行口2可以在2组管脚之间进行切换。通过设置特殊功能寄存器P_SW2中的位S2_S/P_SW2.0，可以将串行口2从[RxD2/P1.0,TxD2/P1.1]切换到[RxD2_2/P4.6,TxD2_2/P4.7]。

STC15W4K60S4系列单片机串行口3对应的硬件部分是TxD3和RxD3。串行口3可以在2组管脚之间进行切换。通过设置特殊功能寄存器P_SW2中的位S3_S/P_SW2.1，可以将串行口3从[RxD3/P0.0,TxD3/P0.1]切换到[RxD3_2/P5.0,TxD3_2/P5.1]。

STC15W4K60S4系列单片机串行口4对应的硬件部分是TxD4和RxD4。串行口4可以在2组管脚之间进行切换。通过设置特殊功能寄存器P_SW2中的位S4_S/P_SW2.2，可以将串行口4从[RxD4/P0.2,TxD4/P0.3]切换到[RxD4_2/P5.2,TxD4_2/P5.3]。

STC15W4K60S4系列单片机的串行通信口，除用于数据通信外，还可方便地构成一个 或多个并行I/O口，或作串—

# 8.1 串行口1的相关寄存器

<table><tr><td rowspan="2">符号</td><td rowspan="2">描述</td><td rowspan="2">地址</td><td colspan="9">位地址及符号</td><td rowspan="2">复位值</td></tr><tr><td colspan="6">MSB</td><td colspan="3">LSB</td></tr><tr><td>T2H</td><td>定时器2高8位寄存器</td><td>D6H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>T2L</td><td>定时器2低8位寄存器</td><td>D7H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>AUXR</td><td>辅助寄存器</td><td>8EH</td><td>T0x12</td><td>T1x12</td><td>UART_M0x6</td><td>T2R</td><td>T2_C/T</td><td>T2x12</td><td>EXTRAM</td><td colspan="2">S1ST2</td><td>0000 0001B</td></tr><tr><td>SCON</td><td>Serial Control</td><td>98H</td><td>SM0/FE</td><td>SM1</td><td>SM2</td><td>REN</td><td>TB8</td><td>RB8</td><td>TI</td><td colspan="2">RI</td><td>0000 0000B</td></tr><tr><td>SBUF</td><td>Serial Buffer</td><td>99H</td><td colspan="9"></td><td>xxxx xxxxxB</td></tr><tr><td>PCON</td><td>Power Control</td><td>87H</td><td>SMOD</td><td>SMOD0</td><td>LVDF</td><td>POF</td><td>GF1</td><td>GF0</td><td>PD</td><td colspan="2">IDL</td><td>0011 0000B</td></tr><tr><td>IE</td><td>Interrupt Enable</td><td>A8H</td><td>EA</td><td>ELVD</td><td>EADC</td><td>ES</td><td>ET1</td><td>EX1</td><td>ET0</td><td colspan="2">EX0</td><td>0000 0000B</td></tr><tr><td>IP</td><td>Interrupt Priority Low</td><td>B8H</td><td>PPCA</td><td>PLVD</td><td>PADC</td><td>PS</td><td>PT1</td><td>PX1</td><td>PT0</td><td colspan="2">PX0</td><td>0000 0000B</td></tr><tr><td>SADEN</td><td>Slave Address Mask</td><td>B9H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>SADDR</td><td>Slave Address</td><td>A9H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>AUXR1 P_SW1</td><td>辅助寄存器1</td><td>A2H</td><td>S1_S1</td><td>S1_S0</td><td>CCP_S1</td><td>CCP_S0</td><td>SPI_S1</td><td>SPI_S0</td><td>0</td><td colspan="2">DPS</td><td>0000 0000B</td></tr><tr><td>CLK_DIV PCON2</td><td>时钟分频寄存器</td><td>97H</td><td>MCKO_S1</td><td>MCKO_S1</td><td>ADRJ</td><td>Tx_Rx</td><td>MCLKO_2</td><td>CLKS2</td><td>CLKS1</td><td colspan="2">CLKS0</td><td>0000 0000B</td></tr></table>

# 1. 串行口1的控制寄存器SCON和PCON

STC15系列单片机的串行口1设有两个控制寄存器：串行控制寄存器SCON和波特率选择特殊功能寄存器PCON。

串行控制寄存器SCON用于选择串行通信的工作 方式和某些控制功能。其格式如下 ：

SCON : 串行控制寄存器 (可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>SCON</td><td>98H</td><td>name</td><td>SM0/FE</td><td>SM1</td><td>SM2</td><td>REN</td><td>TB8</td><td>RB8</td><td>TI</td><td>RI</td></tr></table>

SM0/FE：当PCON寄存器中的SMOD0/PCON.6位为1时，该位用于帧错误检测。当检测到一个无效停止位时，通过UART接收器设置该位。它必须由软件清零。

当PCON寄存器中的SMOD0/PCON.6位为0时，该位和SM1一起指定串行通信的工作方式，如下 表所示。

其中SM0、SM1按下列组合确定串行口1的工作 方式：

<table><tr><td>SM0</td><td>SM1</td><td>工作方式</td><td>功能说明</td><td>波特率</td></tr><tr><td>0</td><td>0</td><td>方式0</td><td>同步移位串行方式:移位寄存器</td><td>当UART_M0x6=0时,波特率是SYSclk/12,当UART_M0x6=1时,波特率是SYSclk/2</td></tr><tr><td>0</td><td>1</td><td>方式1</td><td>8位UART,波特率可变</td><td>串行口1用定时器1作为其波特率发生器且定时器1工作于模式0(16位自动重装载模式)或串行口用定时器2作为其波特率发生器时,波特率=(定时器1的溢出率或定时器T2的溢出率)/4.注意:此时波特率与SMOD无关。当串行口1用定时器1作为其波特率发生器且定时器1工作于模式2(8位自动重装模式)时,波特率=(2SMOD/32)×(定时器1的溢出率)</td></tr><tr><td>1</td><td>0</td><td>方式2</td><td>9位UART</td><td>(2SMOD/64)xSYSclk系统工作时钟频率</td></tr><tr><td>1</td><td>1</td><td>方式3</td><td>9位UART,波特率可变</td><td>当串行口1用定时器1作为其波特率发生器且定时器1工作于模式0(16位自动重装载模式)或串行口用定时器2作为其波特率发生器时,波特率=(定时器1的溢出率或定时器T2的溢出率)/4.注意:此时波特率与SMOD无关。当串行口1用定时器1作为其波特率发生器且定时器1工作干模式2(8位自动重装模式)时,波特率=(2SMOD/32)×(定时器1的溢出率)</td></tr><tr><td colspan="4">当定时器1工作于模式0(16位自动重装载模式)且AUXR.6/T1x12=0时,定时器1的溢出率=SYSclk/12/(65536-[RL_TH1,RL_TL1]);当定时器1工作于模式0(16位自动重装载模式)且AUXR.6/T1x12=1时,定时器1的溢出率=SYSclk/(65536-[RL_TH1,RL_TL1])当定时器1工作于模式2(8位自动重装模式)且T1x12=0时,定时器1的溢出率=SYSclk/12/(256-TH1);当定时器1工作于模式2(8位自动重装模式)且T1x12=1时,定时器1的溢出率=SYSclk/(256-TH1)当AUXR.2/T2x12=0时,定时器T2的溢出率=SYSclk/12/(65536-[RL_TH2,RL_TL2]);当AUXR.2/T2x12=1时,定时器T2的溢出率=SYSclk/(65536-[RL_TH2,RL_TL2]);</td><td></td></tr></table>

SM2：允许方式2或方式3多机通信控制位。

方式2或方式3时，如果 SM2位为1且REN位为1，则接收机处于地址帧筛选状态。此 时可以利用接收到的第9位(即RB8)来筛选地址帧：若RB8=1，说明该帧是地址帧，地址信息可以进入S BUF，并使RI为 1，进而在中断服务程序中再进行地址号比较；若RB8=0，说明该帧不是地址帧，应丢掉且保持RI=0。在 方式2或方式3中，如果 SM2位为0且REN位为1，接收收机处于地址帧筛选被禁止状态。不论收到的RB8为0或1，均可使接收到的信息进入S BUF,并使R $= 1$ ,此 时RB8通常为校验位.

方式1和方式0是非多机通信方式，在这两种方式时，要设置SM2 应为0。

REN：允许/禁止串行接收控制位。由 软件置位REN，即REN=1为允许串行接收状态，可启动串行接收器RxD，开始 接收信息。软件复位REN，即REN=0，则禁止接收。

TB8： 在方式2或方式3，它为要发送的第9位数据，按需要由软件置位或清0。例如，可用作数据的校验位或多机通信中表示地址帧/数据帧的标志位。在 方式0和方式1中，该位不用.

RB8： 在方式2或方式3，是接收到的第9位数据，作为 奇偶校验位或地址帧/数据帧的标志位。方式0中不用RB8(置SM2=0). 方式1中也不用RB8(置SM2=0, RB8是接收到的停止位)。

TI： 发送中断请求标志位。在 方式0，当串行发送数 据第8位结束时，由内部硬件自动置位，即 $\mathrm { T I } { = } 1$ ，向主机请求中断，响应中断后TI必须用软件清零，即 $\mathrm { T I } { = } 0$ 。在 其他方式中，则在停止位开始 发送时由内部硬件置位，即TI=1,响应中断后TI必须用软件清零。

RI： 接收中断请求标志位。在 方式0，当串行接收到第8位结束时由内部硬件自动置位RI=1，向主机请求中断，响应中断后RI必须用软件清零，即RI=0。在 其他方式中，串行接收到停止位的中间时刻由内部硬件置位，即RI=1,向CPU发中断申请，响应中断后RI必须由软件清零。

SCON的所有位可通过整机复位信号复位为全 0”�。SCON的字节地址为98H，可位寻址，各位地址为98H~~9FH，可用软件实现位设置。

串行通信的中断请求：当一帧发送完成，内部硬件自动置位TI，即TI=1，请求中断处理；当接收完一帧信息时，内部硬件自动置位RI，即RI=1，请求中断处理。由 于TI和RI以“辑”关系向主�机请求中断，所以主�机响应中断时事先并不知道��是TI还是RI请求的中断，必须在中断服务程序中查询TI和RI进行判别，然后分别处理。因此，两个中断请求标志位均不能由硬件自动置位，必须通过软件清0，否则将出现一次请求多次响应的错误。

电源控制寄存器PCON中的SMOD/PCON.7用于设置方式1、方式2、方式3的波特率是否加倍。

电源控制寄存器PCON格式如下 ：

PCON : 电源控制寄存器 (不可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>PCON</td><td>87H</td><td>name</td><td>SMOD</td><td>SMODO</td><td>LVDF</td><td>POF</td><td>GF1</td><td>GF0</td><td>PD</td><td>IDL</td></tr></table>

SMOD：波特率选择位。当用软件置位SMOD，即SMOD=1，则使串行通信方式1、2、3的波特率加倍；SMOD=0，则各工作 方式的波特率加倍。复位时SMOD=0。

SMOD0：帧错误检测有效控制位。当SMOD0=1，SCON寄存器中的SM0/FE位用于FE(帧错误检测)功能；当SMOD0=0，SCON寄存器中的SM0/FE位用于SM0功能,和SM1一起指定串行口的工作 方式。复位时SMOD0=0

PCON中的其他位都与串行口1无关，在此 不作介绍。

# 2.串行口数据缓冲寄存器SBUF

STC15系列单片机的串行口1缓冲寄存器(SBUF)的地址是99H，实际是2个 缓冲器，写SBUF的操作 完成待发送数 据的加载，读SBUF的操作 可获得已接收到的数据。两个操作 分别对应两个不同的寄存器，1个是只写寄存器，1个是只读寄存器。

串行通道内设有数据寄存器。在 所有的串行通信方式中，在写入SBUF信号(MOV SBUF,A)的控制下，把数据装入相同的9位移位寄存器，前面8位为数 据字节，其最低位为移位寄存器的输出位。根据不同的工作 方式会自动将 1” TB8的值装入移位寄存器的第9位,并进行发送.

串行通道的接收寄存器是一个 输入移位寄存器。在 方式0时它的字长为8位，其他方式时为9位。当一帧接收完毕，移位寄存器中的数据字节装入串行数据缓冲器SBUF中,其第9位则装入SCON寄存器中的RB8位。如果由 于SM2使得已接收到的数据无效时,RB8和SBUF中内容不变.

由于接收通道内设有输入移位寄存器和SBUF缓冲器，从而能使一帧接收完将数据由移位寄存器装入SBUF后，可立即开始 接收下一 帧信息，主机应在该帧接收结束前从SBUF缓冲器中将数据取走，否则前一帧数据将丢失。SBUF以并行方式送往 内部数 据总线。

# 3. 辅助寄存器AUXR

辅助寄存器AUXR的格式及各位含义如下 ：


AUXR : 辅助寄存器 (不可位寻址)


<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>AUXR</td><td>8EH</td><td>name</td><td>T0x12</td><td>T1x12</td><td>UART_M0x6</td><td>T2R</td><td>T2_C/T</td><td>T2x12</td><td>EXTRAM</td><td>S1ST2</td></tr></table>

T0x12: 定时器0速度控制位

0, 定时器0是传统8051速度，12分频；

1, 定时器0的速度是传统8051的12倍，不分频

T1x12: 定时器1速度控制位

0, 定时器1是传统8051速度，12分频；

1, 定时器1的速度是传统8051的12倍，不分频

如果 UART1/串口1用T1作为 波特率发生器，则由T1x12决定UART1/串口是12T还是1T

UART_M0x6: 串口模式0的通信速度设置位。

0, 串口1模式0的速度是传统8051单片机串口的速度，12分频；

1, 串口1模式0的速度是传统8051单片机串口速度的6倍，2分频

T2R: 定时器2允许控制位

0, 不允许定时器2运行；

1, 允许定时器2运行

T2_C/T: 控制定时器2用作定时器或计数 器。

0, 用作定时器(对内部系统时钟进 行计数 )；

1, 用作计数 器(对引脚T2/P3.1的外部脉冲进行计数 )

# T2x12: 定时器2速度控制位

0, 定时器2是传统8051速度，12分频；

1, 定时器2的速度是传统8051的12倍，不分频

如果 串口1或串口2用T2作为 波特率发生器，则由T2x12决定串口1或串口2是12T还是1T.

EXTRAM: 内部/外部RAM存取控制位

0, 允许使用逻辑上在片外、物理上在片内的扩展RAM；

1, 禁止使用逻辑上在片外、物理上在片内的扩展RAM

S1ST2: 串口1(UART1)选择定时器2作 波特率发生器的控制位

0, 选择定时器1作为 串口1(UART1)的波特率发生器；

1, 选择定时器2作为 串口1(UART1)的波特率发生器，此时定时器1得到释放，可以作为独立定时器使用

串口1可以选择定时器1做波特率发生器，也可以选择定时器���2作为���波特率发生器�当设置AUXR寄存器中的S1ST2位(串行 �1时，串行口1选择定时器���器,此 时定时器1可以释放出来作为 定时器/计数 器/时钟输出使用.

对于STC15系列单片机，串口2只能使用定时器2作为波特率发生器，不能够选择其他定时器作为 其波特率发生器；而串口1默认选择定时器2作为 其波特率发生器，也可以选择定时器1作为 其波特率发生器；串口3默认选择定时器2作为 其波特率发生器，也可以选择定时器3作为其波特率发生器；串口4默认选择定时器2作为 其波特率发生器，也可以选择定时器4作为 其波特率发生器。

# 4. 定时器2的寄存器T2H, T2L

定时器2寄存器T2H(地址为D6H，复位值为00H)及寄存器T2L(地址为D7H，复位值为00H)用于保存重装时间常数。

注意：对于STC15系列单片机，串口2只能使用定时器2作为波特率发生器，不能够选择其他定时器作为 其波特率发生器；而串口1默认选择定时器2作为 其波特率发生器，也可以选择定时器1作为 其波特率发生器；串口3默认选择定时器2作为 其波特率发生器，也可以选择定时器3作为其波特率发生器；串口4默认选择定时器2作为 其波特率发生器，也可以选择定时器4作为 其波特率发生器。

# 5. 从机地址控制寄存器SADEN和SADDR

为了方便多机通信，STC15系列单片机设置了从机地址控制寄存器SADEN和SADDR。其中SADEN是从机地址掩模寄存器(地址为B9H，复位值为00H)，SADDR是从机地址寄存器(地址为A9H，复位值为00H)。

# 6.与串行口1中断相关的寄存器位ES和PS

串行口中断允许位ES位于中断允许寄存器IE中，中断允许寄存器的格式如下 ：

IE : 中断允许寄存器 (可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IE</td><td>A8H</td><td>name</td><td>EA</td><td>ELVD</td><td>EADC</td><td>ES</td><td>ET1</td><td>EX1</td><td>ET0</td><td>EX0</td></tr></table>

EA : CPU的总中断允许控制位

EA=1，CPU开放中断，

EA=0，CPU屏蔽所有的中断申请。

EA的作用是使中断允许形成多级控制。即各中断源首先受EA控制;其次还受各中断源自己的中断允许控制位控制。

ES : 串行口中断允许位

$\mathbf { E S } { = } 1$ ，允许串行口中断，

$\mathrm { E S } { = } 0$ ，禁止串行口中断。

IP : 中断优先级控制寄存器低 (可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IP</td><td>B8H</td><td>name</td><td>PPCA</td><td>PLVD</td><td>PADC</td><td>PS</td><td>PT1</td><td>PX1</td><td>PT0</td><td>PX0</td></tr></table>

PS: 串行口1中断优先级控制位。

当PS=0时，串行口1中断为最低优先级中断(优先级0)

当PS=1时，串行口1中断为最高优先级中断(优先级1)

# 7. 将串口1进行切换的寄存器AUXR1(P_SW1)

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td><td>Reset Value</td></tr><tr><td>AUXR1</td><td rowspan="2">A2H</td><td rowspan="2">Auxiliary register 1</td><td rowspan="2">S1_S1</td><td rowspan="2">S1_S0</td><td rowspan="2">CCP_S1</td><td rowspan="2">CCP_S0</td><td rowspan="2">SPI_S1</td><td rowspan="2">SPI_S0</td><td rowspan="2">0</td><td rowspan="2">DPS</td><td rowspan="2">0000,0000</td></tr><tr><td>P_SW1</td></tr></table>

<table><tr><td colspan="3">串口1/S1可在3个地方切换,由 S1_S0 及 S1_S1 控制位来选择</td></tr><tr><td>S1_S1</td><td>S1_S0</td><td>串口1/S1可在P1/P3之间来回切换</td></tr><tr><td>0</td><td>0</td><td>串口1/S1在[P3.0/RxD,P3.1/TxD]</td></tr><tr><td>0</td><td>1</td><td>串口1/S1在[P3.6/RxD_2,P3.7/TxD_2]</td></tr><tr><td>1</td><td>0</td><td>串口1/S1在[P1.6/RxD_3/XTAL2,P1.7/TxD_3/XTAL1]串口1在P1口时要使用内部时钟</td></tr><tr><td>1</td><td>1</td><td>无效</td></tr></table>

串口1建议放在[P 3.6/RxD_2,P 3.7/TxD_2] 或[P1.6/RxD_3/XTAL2,P 1.7/TxD_3/XTAL1]上。

<table><tr><td colspan="3">CCP可在3个地方切换,由 CCP_S1 / CCP_S0 两个控制位来选择</td></tr><tr><td>CCP_S1</td><td>CCP_S0</td><td>CCP可在P1/P2/P3之间来回切换</td></tr><tr><td>0</td><td>0</td><td>CCP在[P1.2/ECI,P1.1/CCP0,P1.0/CCP1,P3.7/CCP2]</td></tr><tr><td>0</td><td>1</td><td>CCP在[P3.4/ECI_2,P3.5/CCP0_2,P3.6/CCP1_2,P3.7/CCP2_2]</td></tr><tr><td>1</td><td>0</td><td>CCP在[P2.4/ECI_3,P2.5/CCP0_3,P2.6/CCP1_3,P2.7/CCP2_3]</td></tr><tr><td>1</td><td>1</td><td>无效</td></tr></table>

<table><tr><td colspan="3">SPI可在3个地方切换,由 SPI_S1 / SPI_S0 两个控制位来选择</td></tr><tr><td>SPI_S1</td><td>SPI_S0</td><td>SPI可在P1/P2/P4之间来回切换</td></tr><tr><td>0</td><td>0</td><td>SPI在[P1.2/SS,P1.3/MOSI,P1.4/MISO,P1.5/SCLK]</td></tr><tr><td>0</td><td>1</td><td>SPI在[P2.4/SS_2,P2.3/MOSI_2,P2.2/MISO_2,P2.1/SCLK_2]</td></tr><tr><td>1</td><td>0</td><td>SPI在[P5.4/SS_3,P4.0/MOSI_3,P4.1/MISO_3,P4.3/SCLK_3]</td></tr><tr><td>1</td><td>1</td><td>无效</td></tr></table>

# 8.串口1的中继广播方式设置位— Tx_Rx/CLK_DIV.4

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td><td>Reset Value</td></tr><tr><td>CLK_DIV(PCON2)</td><td>97H</td><td>时钟分频寄存器</td><td>MCKO_S1</td><td>MCKO_S0</td><td>ADRJ</td><td>Tx_Rx</td><td>MCLKO_2</td><td>CLKS2</td><td>CLKS1</td><td>CLKS0</td><td>0000,0000</td></tr></table>

# Tx_Rx：串口1的中继广播方式设置

# 0：串口1为正常工作 方式

1：串口1为中继广播方式，即将RxD端口输入的电平状态实时输出在TxD外部管脚上，TxD外部管脚可以对RxD管脚的输入信号进行实时整形放大输出，TxD管脚的对外输出实时反映RxD端口输入的电平状态。

串口1的RxD管脚和TxD管脚可以在3组不同管脚之间进行切换：[RxD/P3.0, TxD/P3.1]；

[RxD_2/P3.6, TxD_2/P3.7]； 

[RxD_3/P1.6, TxD_3/P1.7]. 

# 8.2 串行口1工作模式

STC15系列单片机的串行通信接口有4种工作 模式，可通过软件编程对SCON中的SM0、SM1的设置进行选择。其中模式1、模式2和模式3为异步通信，每个发送和接收的字符都带有1个启动位和1个停止位。在 模式0中，串行口被作为 1个简单的移位寄存器使用。

# 8.2.1 串行口1工作模式0：同步移位寄存器(建议初学者不学)

在模式0状态，串行通信接口工作在 同步移位寄存器模式，当位UART_M0x6/AUXR.5 = 0时，其波特率固定为SYSclk/12。当串行口模式0的通信速度设置UART_M0x6/AUXR.5 = 1时，其波特率固定为SYSclk/2。串行口数据由RxD/P3.0端输入，同步移位脉冲（SHIFTCLOCK）由TxD/P3.1输出，发送、接收的是8位数据，低位在先。

模式0的发送过程：当主机执行将数据写入发送缓冲器SBUF指令时启动发送，串行口即将8位数据以SYSclk/12或SYSclk/2(由UART_M0x6/AUXR.5确定是12分频还是2分频)的波特率从RxD管脚输出(从低位到高位)，发送完中断标志TI置 $" 1 \prime $ ，TxD管脚输出同步移位脉冲（SHIFT-CLOCK）。波形如图8-1中“发送”所示。

当写信号有效后，相隔一个 时钟，发送控制端SEND有效(高电平)，允许RxD发送数 据，同时允许TxD输出同步移位脉冲。一 帧(8位)数据发送完毕时，各控制端均恢复原状态，只有TI保持高电平，呈中断申请状态。在 再次发送数 据前，必须用软件将TI清0。

模式0接收过程：模式0接收时，复位接收中断请求标志RI，即 $\mathrm { R I } { = } 0$ ，置位允许接收控制位REN=1时启动串行模式0接收过程。启动接收过程后，RxD为串行输入端，TxD为同步脉冲输出端。串行接收的波特率为SYSclk/12或SYSclk/2(由UART_M0x6/AUXR.5确定是12分频还是2分频)。其时序图如图8-1中“接收”所示。

当接收完成一帧数据(8位)后，控制信号复位，中断标志RI被置"1"，呈中断申请状态。当再次接收时，必须通过软件将RI清0

工作 于模式0时，必须清0多机通信控制位SM2，使不影响TB8位和RB8位。由 于波特率固定为SYSclk/12或SYSclk/2，无需定时器提供，直接由单片机的时钟作为 同步移位脉冲。

串行口工作 模式0的示意图如图8-1所示

由示意图中可见，由TX和RX控制单元分别产生中断请求信号并置位TI=1或RI =1，经“门”��送主 � TI还是RI请求中断，必须软件清0中断请求标志位TI或RI。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c29671381740b6b98b42d5138e944ce148cbab113eb5f9e1854ec0e21e4c74e3.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/35e95efea268c7d4ead77e08690497a73ef0617d0a5c9d3316a25c56a1582332.jpg)



图8-1 串行口1模式0功能结构及时序示意图


# 8.2.2 串行口1工作模式1：8位UART，波特率可变

当软件设置SCON的SM0、SM1为“01” 1工作。此 模式为8位UART格式，一帧信息为10位：1位起始位，8位数据位(低位在先)和1位停止位。波特率可变，即可根据需要进行设置。TxD/P3.1为发送信息，RxD/P3.0为接收端接收信息，串行口为全双工 接受/发送串行口。

图8-2为串行模式1的功能结构示意图及接收/发送时序图

模式1的发送过程：串行通信模式发送时，数据由串行发送端TxD输出。当主机执行一条写 SBUF“ � �，写 SBUF”信号还把 1” � �的第9位，并通知TX控制单元开始 发送。 发送各位的定时是由16分频计数 器同步。

移位寄存器将数据不断右移送TxD端口发送，在数 据的左边不断移入“0”�作 �数据的最高位移到移位寄存器的输出位置，紧跟其后的是第9位 1” � �“0” � � TX控制单元作最后一次移位输出，然后使允许发送信号 SEND”失效，完成一帧信息的发送，并置位中断请求位TI，即TI=1，向主机请求中断处理。

模式1的接收过程：当软件置位接收允许标志位REN，即REN=1时，接收器便以选定波特率的16分频的速率采样串行接收端口RxD，当检测到RxD端口从 1”�→ 0” �动接收器准备接收数据，并立即复位16分频计数 器，将1FFH植装入移位寄存器。复位16分频计数 器是使它与输入位时间同步。

16分频计数 器的16个状态是将1波特率（每位接收时间）均为16等份，在每位时间的7、8、9状态由检测器对RxD端口进行采样，所接收的值是这次采样直经“三中取二” 3次采样至少2次相同的值，以此消除干扰影响，提高可靠性。在 起始位，如果 接收到的值不为“0” �位无效，复位接收电路，并重新检测 $" 1 "  " 0 "$ ��� �的起始位有效，则将它输入移位寄存器，并接收本帧的其余信息。

接收的数据从接收移位寄存器的右边移入，已装入的1FFH向左边移出，当起始位 $" 0 ^ { \prime \prime }$ �移位寄存器的最左边时，使RX控制器作最后一次移位，完成一帧的接收。若同时满足以下两个条 件：

·RI=0； 

·SM2=0或接收到的停止位为1。

则接收到的数据有效，实现装载入SBUF，停止位进入 RB8，置位RI，即 $\mathrm { R I } { = } 1$ ，向主机请求中断，若上述两条件不能同时满足，则接收到的数据作废并丢失，无论条件满足与否，接收器重又检测RxD端口上的 $" 1 "  " 0 "$ 的跳变，继续下一��帧的接收。�接收有效，在�响应中断后，必须由软件清0，即 $\scriptstyle \mathrm { R I = 0 }$ 。通常情况下，串行通信工作 于模式1时，SM2设置为 $" 0 ^ { \prime \prime }$ 。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b35ce559092fac38ca29be0b6cd15462c87207e9a0ad38e8b7450279b99ab7ad.jpg)



图8-2 串行口模式1功能结构示意图及接收/发送时序图


串行通信模式1的波特率是可变的，可变的波特率由定时器/计数 器1或定时器2产生，优先选择定时器2产生波特率。

当串行口1用定时器2作为 其波特率发生器时，

STC创新设计，请不要抄

串行口1的波特率 $: =$ (定时器T�2的溢出率) �

袭，再抄袭就很无耻了

（注意：此时波特率也与S MOD无关。）

当T2工作在 1T模式(AUXR.2/T2x12=1)时 定时器�2 $=$ SYSclk / ( 65536 - [RL_TH2,RL_TL2] )；

即此时，串行口1的波特率=SYSclk / ( 65536 - [RL_TH2,RL_TL2]) / 4

当T2工作在 12T模式(AUXR.2/T2x12=0)时 定时器�2 =SYSclk /12/(65536 - [RL_TH2,RL_TL2])；

即此时，串行口1的波特率 $\displaystyle . =$ SYSclk / 12 / ( 65536 - RL_TH2,RL_TL2]) / 4

RL_TH2是T2H的自动重装载寄存器，RL_TL2是T2L的自动重装载寄存器。

当串行口1用定时器1作为 其波特率发生器且定时器1工作 于模式0(16位自动重装载模式)时，

串行口1的波特率=(定时器1的溢出率) �

（注意：此时波特率与S MOD无关。）

当 �� � T1x12 = 0时

定时器 $=$ SYSclk/12/( 65536 - [RL_TH1,RL_TL1]) ；

即此时，串行口1的波特率=SYSclk/12/( 65536 - [RL_TH1,RL_TL1]) / 4

当定时器1工作于模式0（16位自动重装载模式）且 $\mathrm { T } 1 \mathrm { x } 1 2 = 1$ 时,

定时器 $=$ SYSclk / (65536 - [RL_TH1,RL_TL1])

即此时，串行口1的波特率=SYSclk / ( 65536 - [RL_TH1,RL_TL1]) / 4

RL_TH1是TH1的自动重装载寄存器，RL_TL1是TL1的自动重装载寄存器。

当串行口1用定时器1作为 其波特率发生器且定时器1工作 于模式2(8位自动重装模式)时，

串行口1的波特率= $( 2 ^ { \mathrm { { S M O D } } } / 3 2 ) \times$ (定时器1的溢出率)

当定时器1��工作 于模式�2（8位�自动重装模式）且 $\mathrm { T } 1 \mathrm { x } 1 2 = 0$ 时

定时器 $= \mathrm { S Y S c l k } / 1 2 / ( 2 5 6 - \mathrm { T H 1 } )$ $=$ 

即此时，串行口1的波特率=( 2SMOD/32 )×SYSclk / 12 / ( 256 - TH1)

当定时器1��工作 于模式�2（8位�自动重装模式）且 $\mathrm { T } 1 \mathrm { x } 1 2 = 1$ 时,

定时器 $=$ SYSclk / ( 256 - TH1)

即此时，串行口1的波特率=( 2SMOD/32 )×SYSclk / ( 256 - TH1)

# 8.2.3 串行口1工作模式2：9位UART，波特率固定(建议不学习)

当SM0、SM1两位为10时，串行口1工作在 模式2。 串行口1工作 模式2为9位数据异步通信UART模式，其一帧的信息由11位组成：1位起始位，8位数据位(低位在先)，1位可编程位(第9位数据)和1位停止位。发送时可编程位(第9位数据)由SCON中的TB8提供，可软件设置为1或0，或者可将PSW中的奇/偶校验位P值装入TB8(TB8既可作为 多机通信中的地址数据标志位，又可作为数 据的奇偶校验位)。接收时第9位数据装入SCON的RB8。TxD/P3.1为发送端口，RxD/P3.0为接收端口，以全双工 模式进行接收/发送。

模式2的波特率为：

串行通信模式2波特率=2SMOD/64×(SYSclk系统工作 时钟频率)

上述波特率可通过软件对PCON中的SMOD位进行设置，当SMOD=1时，选择SYSclk/32；当SMOD $\scriptstyle 1 = 0$ 时，选择SYSclk/64，故而称SMOD为波特率加倍位。可见，模式2的波特率基本上是固定的。

图8-3为串行通信模式2的功能结构示意图及其接收/发送时序图。

由图8-3可知，模式2和模式1相比，除波特率发生源略有不同，发送时由TB8提供给 移位寄存器第9数据位不同外，其余功能结构均基本相同，其接收/发送操作 过程及时序也基本相同。

当接收器接收完一帧信息后必须同时满足下列条件：

·RI=0 

·SM2=0或者SM2=1，并且接收到的第9数据位RB8=1。

当上述两条件同时满足时，才将接收到的移位寄存器的数据装入SBUF和RB8中，并置位$\mathrm { R I } { = } 1$ ，向主机请求中断处理。如果 上述条件有一个 不满足，则刚接收到移位寄存器中的数据无效而丢失，也不置位RI。无论上述条件满足与否，接收器又重新开始 检测RxD输入端口的跳变信息，接收下一 帧的输入信息。

在模式2中，接收到的停止位与SBUF、RB8和RI无关。

通过软件对SCON中的SM2、TB8的设置以及通信协议的约定，为多机通信提供了方便。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b700b61c54f25bd276eaf44efb11e1223e172054ce8d95dea829397516a8c0c6.jpg)



图8-3 串行口模式2功能结构示意图及接收/发送时序图


# 8.2.4 串行口1工作模式3：9位UART，波特率可变

当SM0、SM1两位为11时，串行口1工作在 模式3。串行通信 3为9位数据异步通信UART模式， � �11位组成：1位起始位，8位数据位(低位在先)，1位可编程位(第9位数据)和1位停止位。发送时可编程位(第9位数据)由SCON中的TB8提供，可软件设置为1或0，或者可将PSW中的奇/偶校验位P值装入TB8(TB8既可作为 多机通信中的地址数据标志位，又可作为数 据的奇偶校验位)。接收时第9位数据装入SCON的RB8。TxD/P3.1为发送端口，RxD/P3.0为接收端口，以全双工 模式进行接收/发送。

图8-4为串行口工作 模式3的功能结构示意图及其接收/发送时序图。

由图8-4可知，模式3和模式1相比，除发送时由TB8提供给 移位寄存器第9数据位不同外，其余功能结构均基本相同，其接收‘发���送操作 过程及时�序也基本相同。

当接收器接收完一帧信息后必须同时满足下列条件：

·RI=0 

·SM2=0或者SM2=1，并且接收到的第9数据位RB8=1。

当上述两条件同时满足时，才将接收到的移位寄存器的数据装入SBUF和RB8中，并置位$\mathrm { R I } { = } 1$ ，向主机请求中断处理。如果 上述条件有一个 不满足，则刚接收到移位寄存器中的数据无效而丢失，也不置位RI。无论上述条件满足与否，接收器又重新开始 检测RxD输入端口的跳变信息，接收下一 帧的输入信息。

在模式3中，接收到的停止位与SBUF、RB8和RI无关。

通过软件对SCON中的SM2、TB8的设置以及通信协议的约定，为多机通信提供了方便。

串行通信模式3的波特率也是可变的，可变的波特由定时器/计数 器1或定时器2产生。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/fe14a837916dba0059305815caa0f2ac47ae1ea6b58f0d7d2f803f6e95869ec8.jpg)



图8-4 串行口模式3功能结构示意图及接收/发送时序图


模式3的波特率（优先选择定时器2产生波特率）为：

当串行口1用定时器2作为 其波特率发生器时，

串行口1的波特率=(定时器T�2的溢出率) �

STC创新设计，请不要抄

袭，再抄袭就很无耻了

（注意：此时波特率也与S MOD无关。）

当T2工作在 1T模式(AUXR.2/T2x12=1)时 定时器�2 $=$ SYSclk / ( 65536 - [RL_TH2,RL_TL2] )；

即此时，串行口1的波特率 $\displaystyle . =$ SYSclk / ( 65536 - [RL_TH2,RL_TL2]) / 4

当T2工作在 12T模式(AUXR.2/T2x12=0)时 定时器�2 =SYSclk /12/(65536 - [[RL_TH2,RL_TL2])；

即此时，串行口1的波特率 $\displaystyle . =$ SYSclk / 12 / ( 65536 - [RL_TH2,RL_TL2]) / 4

RL_TH2是T2H的自动重装载寄存器，RL_TL2是T2L的自动重装载寄存器。

当串行口1用定时器1作为 其波特率发生器且定时器1工作 于模式0(16位自动重装载模式)时，串行口1的波特率 $: =$ (定时器1的溢出率) �

（注意：此时波特率与S MOD无关。）

当 �� � T1x12 $=$ 0时

定时器 $=$ SYSclk/12/( 65536 - [RL_TH1,RL_TL1]) ；

即此时，串行口1的波特率=SYSclk/12/( 65536 - [RL_TH1, RL_TL1]) / 4

当定时器1工作于模式0（16位自动重装载模式）且 $\mathrm { T } 1 \mathrm { x } 1 2 = 1$ 时,

定时器 $=$ SYSclk / (65536 - [RL_TH1,RL_TL1])

即此时，串行口1的波特率=SYSclk / ( 65536 - [RL_TH1, RL_TL1]) / 4

RL_TH1是TH1的自动重装载寄存器，RL_TL1是TL1的自动重装载寄存器。

当串行口1用定时器1作为 其波特率发生器且定时器1工作 于模式2(8位自动重装模式)时，

串行口1的波特率=( $2 ^ { \mathrm { S M O D } } / 3 2 ) \times 1$ (定时器1的溢出率)

当定时器1��工作 于模式�2（8位�自动重装模式）且 $\mathrm { T } 1 \mathrm { x } 1 2 = 0$ 时

定时器 $= \mathrm { S Y S c l k } / 1 2 / ( 2 5 6 \cdot \mathrm { T H 1 } )$ $=$ ；

即此时，串行口1的波特率=( 2SMOD/32 )×SYSclk / 12 / ( 256 - TH1)

当定时器1��工作 于模式�2（8位�自动重装模式）且 $\mathrm { T } 1 \mathrm { x } 1 2 = 1$ 时,

定时器 $=$ SYSclk / ( 256 - TH1)

即此时，串行口1的波特率=( 2SMOD/32 )×SYSclk / ( 256 - TH1)

可见，模式3和模式1一样，其波特率可通过软件对定时器/计数 器1或定时器2的设置进行波特率的选择，是可变的。

# 8.3 串行口1的波特率设置

STC15W4K60S4系列单片机串行口1的波特率随所选工作 模式的不同而异，对于工作 模式0和模式2，其波特率与系统时钟频率SYSclk和PCON中的波特率选择位SMOD有关，而模式1和模式3的波特率除与SYSclk和PCON位有关外，还与定时器/计数 器1或定时器2设置有关。通过对定时器/计数 器1或定时器2的设置，可选择不同的波特率，所以这种波特率是可变的。建议用户优先选择定时器2作为 串行口1的波特率发生器。

串行通信模式0，其波特率与系统时钟频率SYSclk有关 。

当模式0的通信速度设置 UART_M0x6/AUXR.5 = 0时，其波特率 $= { \mathrm { S Y S c l k } } / { 1 2 }$ $=$ 。

当模式0的通信速度设置 UART_M0x6/AUXR.5 = 1时，其波特率 $= \mathrm { S Y S c l k } / 2$ $=$ 。

一旦 SYSclk选定且UART_M0x6/AUXR.5设置好，则串行通信工作 模式0的波特率固定不变。

串行通信工作 模式2，其波特率除与SYSclk有关外，还与SMOD位有关。

其基本表达式为：串行通信模式2波特率 ${ = } 2 ^ { \mathrm { S M O D } } / 6 4 \times$ (SYSclk系统工作 时钟频率)

当SMOD $\not { D } = 1$ 时，波特率=2/64(SYSclk)=1/32(SYSclk)；

当SMOD $\scriptstyle \longmapsto 0$ 时，波特率=1/64(SYSclk)。

当SYSclk选定后，通过软件设置PCON中的SMOD位，可选择两种波特率。所以，这种模式的波特率基本固定。

串行通信模式1和3，其波特率是可变的(建议用户优先选择定时器T2作为 串口1的波特率发生器)： STC创新设计，请不要抄

当串行口1用定时器2作为 其波特率发生器时，

STC创新设计，请不要抄袭，再抄袭就很无耻了

串行口1的波特率=(定时器T�2的溢出率) �

（注意：此时波特率也与S MOD无关。）

当T2工作在 1T模式(AUXR.2/T2x12=1)时 定时器�2 $=$ SYSclk / ( 65536 - [RL_TH2,RL_TL2] )；

即此时，串行口1的波特率=SYSclk / ( 65536 - [RL_TH2,RL_TL2]) / 4

当T2工作在 12T模式(AUXR.2/T2x12=0)时 定时器�2 =SYSclk /12/(65536 - [RL_TH2,RL_TL2])；

即此时，串行口1的波特率 $\displaystyle . =$ SYSclk / 12 / ( 65536 - [RL_TH2,RL_TL2]) / 4

当串行口1用定时器1作为 其波特率发生器且定时器1工作 于模式0(16位自动重装载模式)时，

串行口1的波特率 $: =$ (定时器1的溢出率) �

（注意：此时波特率与S MOD无关。）

当定时器1工作于模式0（16位自动重装载模式）且 $\mathrm { T } 1 \mathrm { x } 1 2 = 0$ 时

定时器 $=$ SYSclk/12/( 65536 - [RL_TH1,RL_TL1]) ；

即此时，串行口1的波特率=SYSclk/12/( 65536 - [RL_TH1,RL_TL1]) / 4

当定时器1工作于模式0（16位自动重装载模式）且 $\mathrm { T } 1 \mathrm { x } 1 2 = 1$ 时,

定时器 $=$ SYSclk / (65536 - [RL_TH1,RL_TL1])

即此时，串行口1的波特率=SYSclk / ( 65536 - [RL_TH1,RL_TL1]) / 4

当串行口1用定时器1作为 其波特率发生器且定时器1工作 于模式2(8位自动重装模式)时，

串行口1的波特率=( $2 ^ { \mathrm { S M O D } } / 3 2 ) \times 1$ (定时器1的溢出率)

当定时器1��工作 于模式�2（8位�自动重装模式）且 $\mathrm { T } 1 \mathrm { x } 1 2 = 0$ 时

定时器 $= \mathrm { S Y S c l k } / 1 2 / ( 2 5 6 - \mathrm { T H 1 } )$ $=$ ；

即此时，串行口1的波特率 $= ( 2 ^ { \mathrm { { S M O D } } } / 3 2 ) { \times } \mathrm { { S Y S c l k } } / 1 2 / ( 2 5 6 - \mathrm { { T H } } 1 )$ 

当定时器1��工作 于模式�2（8位�自动重装模式）且 $\mathrm { T } 1 \mathrm { x } 1 2 = 1$ 时,

定时器 $=$ SYSclk / ( 256 - TH1)

即此时，串行口1的波特率=( 2SMOD/32 )×SYSclk / ( 256 - TH1)

通过对定时器/计数 器1和T2定时器2的设置，可灵活地选择不同的波特率。在 实际应用中多半选用串行模式1或串行模式3。显然，为选择波特率，关键在于定时器/计数 器1和T2定时器2的溢出率的计算。SMOD的选择，只需根据需要执行下列指令就可实现SMOD=0或1；

MOV PCON，#00H ；使SMOD=0

MOV PCON，#80H ；使SMOD $\lvert = 1$ 

SMOD只占用电源控制寄存器PCON的最高一位，其他各位的具体设置应根据实际情况而定。

当用户选择定时器/计数 器1�作波特率发生器时，�为选择波特率，关键�在于定时器/计数 器1的溢出率。下 面介绍如何计算定时器/计数 器1的溢出率。

定时器/计数 器1的溢出率定义为：单位时间（秒）内定时器/计数 器1回0溢出的次数，即定时器/计数 器1的溢出率=定时器/计数 器1的溢出次数/秒。

STC15W4K60S4系列单片机设有3个定时器/计数 器，定时器/计数 器1具有4种工作 方式,而常选用定时器/计数 器1的工作 方式0（16位自动重装载模式）及工作 方式2（8位自动重装）作为波特率的溢出率。

以定时器/计数 器1工作 于定时模式的工作 方式2（8位自动重装）为例：设置定时器/计数器1工作 于定时模式的工作 方式2（8位自动重装），TL1的计数 输入来自于SYSclk经12分频或不分频(由T1x12/AUXR.6确定是12分频还是不分频)的脉冲。当T1x12/AUXR.6=0时，单片机工作在 12T模式，TL1的计数 输入来自于SYSclk经12分频的脉冲；当T1x12/AUXR. $6 { = } 1$ 时，单片机工作在 1T模式，TL1的计数 输入来自于SYSclk不经过分频的脉冲。可见，定时器/计数 器1的溢出率与SYSclk和自动重装值N有关，SYSclk越大，特别是N越大，溢出率也就越高。例如：当N=FFN，则每隔一个 时钟即溢出一次（极限情况）；若 $\scriptstyle \mathrm { N = } 0 0 \mathrm { H }$ ，则需每隔256个时钟才溢出一次；当SYSclk $\underline { { \underline { { \mathbf { \Pi } } } } }$ 6MHz且T1x12/AUXR.6=0时，一个 时钟为 $2 \mu \mathrm { s } .$ , 当SYSclk=6MHz且T1x12/AUXR.6=1时，一个 时钟约为 $0 . 1 6 7 \mu \mathrm { s }$ (快12倍)。SYSclk=12MHz且T1x12/AUXR.6=0时，则一个时钟为 1µs, 当SYSclk=6MHz且T1x12/AUXR.6=1时，一个 时钟约为 $0 . 0 8 3 \mu \mathrm { s }$ (快12倍)。对于一般情况下，

当T1x12/AUXR.6=0时，定时器/计数 器1溢出一次所需的时间为： $( 2 ^ { 8 } { - } \mathrm { N } ) \times 1 2$ 2时钟 $= ( 2 ^ { 8 } { \mathrm { - N } } ) \times 1 2 \times { \frac { 1 } { { \mathrm { S Y S c l k } } } }$ 

当T1x12/AUXR.6=1时，定时器/计数 器1溢出一次所需的时间为： $( 2 ^ { 8 } mathrm { - } \mathrm { { N } ) \times 1 }$ 时钟 $= ( 2 ^ { 8 } { \mathrm { - N } } ) \times \frac { 1 } { { \mathrm { S Y S c l k } } }$ 

于是得定时器/计数 器每秒溢出的次数，即

当T1x12/AUXR.6=0时，定时器/计数 器1的溢出率=SYSclk/12×(28 －N) (次/秒)

当T1x12/AUXR.6=1时，定时器/计数 器1的溢出率=SYSclk×(28 －N) (次/秒)

式中SYSclk为系统时钟频率，N为再装入时间常数。

显然，选用定时器/计数 器2作波特率的溢出率也一样。选用不同工作 方式所获得波特率的范围不同。因为不同方式的计数 位数不同，N取值范围不同，且计数 方式较复杂。

现以定时器/计数 器1工作 于方式2（8位自动重装模式）为例，

设： T1x12/AUXR. $6 { = } 0$ ,SYSclk 6MHz, N=FFH,

定时器/计数 器1工作 于方式2的溢出率为 $1 6 \times 1 0 ^ { 6 } / \{ 1 2 \times \ : \ : ( 2 5 6 - 2 5 5 ) \} \ : = 0 . 5 \times 1 0 ^ { 6 } \ : ( \mathcal { W } / \mathcal { X } / \bar { \mathcal { X } } ) \ : ;$ 

设： T1x12/AUXR. $6 { = } 0$ ,SYSclk=12MHz, N=FFH,

定时器/计数 器1工作 于方式2的溢出率 $= ~ 1 \times 1 0 ^ { 6 }$ （次/秒）；

设： T1x12/AUXR. $6 { = } 0$ ,SYSclk 12MHz, $\mathrm { { N = } 0 0 H }$ ,

定时器/计数 器1工作 于方式2的溢出率 $= 1 2 \times 1 0 ^ { 6 } / 1 2 \times 2 5 6 { \approx } 3 9 0 6$ $=$ （次/秒）

设： T1x12/AUXR. $6 { = } 1$ ,SYSclk $: =$ 6MHz, N=FFH,

定时器/计数 器1工作 于方式2的溢出率为6×106 /(256－255) = 6×106 (次/秒)；

设： T1x12/AUXR. $6 { = } 1$ ,SYSclk=12MHz, $\mathrm { \ N = 0 0 H }$ ,

定时器/计数 器1工作 于方式2的溢出率 $= 1 2 \times 1 0 ^ { 6 } / 2 5 6 = 4 6 8 7 5$ （次/秒）

下表给出各种常用波特率与定时器/计数 器1各参数之间的关系。


常用波特率与定时器/计数 器1各参数关系（T1x12/AUXR. $6 { = } 0$ )


<table><tr><td rowspan="2" colspan="2">常用波特率</td><td rowspan="2">系统时钟频率(MHz)</td><td rowspan="2">SMOD</td><td colspan="3">定时器1</td></tr><tr><td>C/T</td><td>方式</td><td>重新装入值</td></tr><tr><td colspan="2">方式0 MAX: 1M</td><td>12</td><td>×</td><td>×</td><td>×</td><td>×</td></tr><tr><td colspan="2">方式2 MAX: 375K</td><td>12</td><td>1</td><td>×</td><td>×</td><td>×</td></tr><tr><td rowspan="9">方式1和3</td><td>62.5K</td><td>12</td><td>1</td><td>0</td><td>2</td><td>FFH</td></tr><tr><td>19.2K</td><td>11.059</td><td>1</td><td>0</td><td>2</td><td>FDH</td></tr><tr><td>9.6K</td><td>11.059</td><td>0</td><td>0</td><td>2</td><td>FDH</td></tr><tr><td>4.8K</td><td>11.059</td><td>0</td><td>0</td><td>2</td><td>FAH</td></tr><tr><td>2.4K</td><td>11.059</td><td>0</td><td>0</td><td>2</td><td>F4H</td></tr><tr><td>1.2K</td><td>11.059</td><td>0</td><td>0</td><td>2</td><td>F8H</td></tr><tr><td>137.5</td><td>11.986</td><td>0</td><td>0</td><td>2</td><td>1DH</td></tr><tr><td>110</td><td>6</td><td>0</td><td>0</td><td>2</td><td>72H</td></tr><tr><td>110</td><td>12</td><td>0</td><td>0</td><td>1</td><td>FFFBH</td></tr></table>

设置波特率的初始化程序段如下 ：

```asm
MOV TMOD, #20H ; 设置定时器/计数器1定时、工作方式2  
MOV TH1, #xxH ; 设置定时常数N  
MOV TL1, #xxH ;  
SETB TR1 ; 启动定时器/计数器1  
MOV PCON, #80H ; 设置SMOD=1  
MOV SCON, #50H ; 设置串行通信方式1  
;
```

执行上述程序段后，即可完成对定时器/计数 器1的操作 方式及串行通信的工作 方式和波特率的设置。

由于用其他工作 方式设置波特率计算方法较复杂，一般应用较少，故不一一 论述。

当用户选择T2定时器2作 波特率发生器时，为选择波特率，关键在于定时器2的溢出率。当用户选择T2定时器2作 波特率发生器时，定时器/��计数 器 �� ��钟输出使用.�。

用户在 程序中如何具体使用串口1和定时器 �

1.设置串口1 的工作 模式，SCON 寄存器中的SM0 和SM1 两位决定了串口1 的4 种工作 模式。

2.设置串口1 的波特率,使用定时器�2寄存器 T��2H及T��

3.设置寄存器AUXR中的位T2x12/AUXR.2,确定定时器2速度是1T还是12T

4.启动定时器�2，�让T�2R位�为1，T��2H/T�2L 定时器�2 � �����

5.设置串口1的中断优先级，及打开中断相应的控制位是:

PS, ES,EA 

6.如要串口1接收，将REN置1即可

如要串口1发送，将数据送入S BUF即可，

接收完成标志RI,发送完成标志TI,要由软件清0。

当串口工作在 模式1和模式3时，�计算相应的波特率需要设置的重装载��数, 结���果送入 T��2H/T��2L寄存器

计算自动重装数 RELOAD:

1. 计算 RELOAD

计算公式： RELOAD = 65536 - INT(SYSclk/Baud0/4 + 0.5)

计算出的RELOAD 数直 接送T2H/T2L寄存器

式中: INT() 表示取整运算即舍去小数, 在式中加 0.5 可以达到四舍五入的目的

SYSclk $=$ 晶振频率

Baud0 $=$ 标准波特率

2. 设置AUXR. $2 / \mathrm { T } 2 \mathrm { x } 1 2 { = } 1$ �,定时器����2工作在 1T模式

3. 计算用 RELOAD 产生的波特率:

Baud $=$ SYSclk/(65536 - RELOAD)/4 

4. 计算误差

$$
\text {error} = (\text {Baud} - \text {Baud0}) / \text {Baud0} * 100 \%
$$

5. 如果 误差绝对值 > $3 \%$ 要更换波特率或者更换晶体频率, 重复步骤 1-4

例: SYSclk = 22.1184MHz, Baud0 = 57600

$$
\begin{array}{l} = 6 5 5 3 6 - \mathrm {I N T} (9 6. 5) \\ = 6 5 5 3 6 - 9 6 \\ = 6 5 4 4 0 \\ = O F F A O H \\ \end{array}
$$

2. 设置AUXR.2�/T�2x1�2=1�,定时器����2工作在 1T模式

3. Baud $=$ 22118400/(65536-65440)/4 

$$
= 5 7 6 0 0
$$

4. 误差等于零

例: SYSclk $=$ 12MHz, Baud0 = 57600

$$
\begin{array}{l} = 6 5 5 3 6 - \mathrm {I N T} (5 2. 0 8 3 3 + 0. 5) \\ = 6 5 5 3 6 - \text {I N T} (5 2. 5 8 3 3) \\ = 6 5 5 3 6 - 5 2 \\ = 6 5 4 8 4 \\ = O F F C C H \\ \end{array}
$$

2. 设置AUXR. $2 / \mathrm { T } 2 \mathrm { x } 1 2 { = } 1$ �,定时器����2工作在 1T模式

3. Baud $=$ 12000000/(66536-65484)/4 

$$
= 5 7 6 9 2
$$

4. error $=$ (57692 - 57600)/57600 * 100% 

$$
= 0.16\%
$$

# 8.4 串行口1的测试程序(C和汇编)

# 8.4.1 定时器2作串口1波特率发生器的测试程序(C和汇编)

# 1. C程序：

/* */ 

/* --- STC MCU Limited. - */ 

/* --- STC15F2K60S2 系列 定时器2用作串口1的波特率发生器举例-- */

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com */ 

/* 如果 要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果 要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可- *

/* - */ 

//假定测试芯片的工作 频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

#define FOSC 18432000L 

#define BAUD 115200 

#define NONE_PARITY 0 

#define ODD_PARITY 1 

#define EVEN_PARITY 2 

#define MARK_PARITY 3 

#define SPACE_PARITY 4 

//系统频率

//串口波特率

#define PARITYBIT EVEN_PARITY 

//无校验

//奇校验

sfr AUXR $=$ 0x8e; 

sfr T2H $=$ 0xd6; 

sfr T2L $=$ 0xd7; 

//偶校验

//标记校验

//空白校验

sbit P22 一 P2^2;

//定义校验位

//辅助寄存器

//定时器2高8位

//定时器2低8位

bit busy; 

void SendData(BYTE dat); 

void SendString(char *s); 

void main() 

{ #if (PARITYBIT $= =$ NONE_PARITY) SCON $= 0\mathrm{x}50$ //8位可变波特率 #elif (PARITYBIT $= =$ ODD_PARITY) $\parallel$ (PARITYBIT $= =$ EVEN_PARITY) $\parallel$ (PARITYBIT $= =$ MARK_PARITY) SCON $= 0\mathrm{xda}$ //9位可变波特率,校验位初始为1 #elif (PARITYBIT $= =$ SPACE_PARITY) SCON $= 0\mathrm{xd}2$ //9位可变波特率,校验位初始为0 #endif T2L $= (65536 - (\mathrm{FOSC} / 4 / \mathrm{BAUD}))$ //设置波特率重装值 T2H $= (65536 - (\mathrm{FOSC} / 4 / \mathrm{BAUD})) >> 8$ AUXR $= 0\mathrm{x}14$ //T2为1T模式,并启动定时器2 AUXR $| = 0\mathrm{x}01$ //选择定时器2为串口1的波特率发生器 ES $= 1$ //使能串口1中断 EA $= 1$ SendString("STC15F2K60S2\r\nUart Test !\r\n"); while(1); } /*___________ UART中断服务程序 ______*/ void Uart() interrupt 4 using 1 { if (RI) { RI $= 0$ //清除RI位 P0 $= \mathrm{SBUF}$ //P0显示串口数据 P22 $= \mathrm{RB8}$ //P2.2显示校验位 } if (TI) { TI $= 0$ //清除TI位 busy $= 0$ //清忙标志 } } /*___________ 发送串口数据 ______*/ void SendData(BYTE dat) { while (busy); //等待前面的数据发送完成 ACC $= \mathrm{dat}$ //获取校验位P(PSW.0) if (P) //根据P来设置校验位 { #if (PARITYBIT $= =$ ODD_PARITY) TB8 $= 0$ //设置校验位为0

```c
elif (PARITYBIT == EVEN_PARITY)  
TB8 = 1; //设置校验位为1  
#endif  
}  
else  
{  
#ifndef (PARITYBIT == ODD_PARITY)  
TB8 = 1; //设置校验位为1  
#elif (PARITYBIT == EVEN_PARITY)  
TB8 = 0; //设置校验位为0  
#endif  
}  
busy = 1;  
SBUF = ACC; //写数据到UART数据寄存器  
}  
/*___________发送字符串___________*/  
void SendString(char *s)  
{ while (*s) //检测字符串结束标志  
{ SendData(*s++); //发送当前字符  
}
```

# 2. 汇编程序：

/*- */ 

/* --- STC MCU Limited. - */ 

/* --- STC15F2K60S2 系列 定时器2用作串口1的波特率发生器举例- */

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果 要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果 要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可- *

/* */ 

//本示例在Keil开 发环境下请选择Intel的8052芯片型号进行编译

//假定测试芯片的工作 频率为18.432MHz

#define NONE_PARITY 0 //无校验

#define ODD_PARITY 1 //奇校验

#define EVEN_PARITY 2 //偶校验

#define MARK_PARITY 3 //标记校验

#define SPACE_PARITY 4 //空白校验

#define PARITYBIT EVEN_PARITY //定义校验位

AUXR EQU 08EH //辅助寄存器

T2H DATA 0D6H //定时器2高8位

T2L DATA 0D7H //定时器2低8位

/ 

BUSY BIT 20H.0 //忙标志位

//- 

ORG 0000H 

LJMP MAIN 

ORG 0023H 

LJMP UART_ISR 

//- 

ORG 0100H 

MAIN: 

CLR BUSY 

CLR EA 

MOV SP, #3FH 

#if (PARITYBIT $= =$ NONE_PARITY) 

MOV SCON, #50H 

#elif (PARITYBIT $= =$ ODD_PARITY) || (PARITYBIT $= =$ EVEN_PARITY) || (PARITYBIT $= =$ MARK_PARITY) 

<table><tr><td>MOV</td><td>SCON, #0DAH</td><td>//9位可变波特率,校验位初始为1</td></tr><tr><td colspan="3">#elif (PARITYBIT==SPACE_PARITY)</td></tr><tr><td>MOV</td><td>SCON, #0D2H</td><td>//9位可变波特率,校验位初始为0</td></tr><tr><td>#endif</td><td></td><td></td></tr><tr><td>MOV</td><td>T2L, #0D8H</td><td>//设置波特率重装值(65536-18432000/4/115200)</td></tr><tr><td>MOV</td><td>T2H, #0FFH</td><td></td></tr><tr><td>MOV</td><td>AUXR, #14H</td><td>//T2为1T模式,并启动定时器2</td></tr><tr><td>ORL</td><td>AUXR, #01H</td><td>//选择定时器2为串口1的波特率发生器</td></tr><tr><td>SETB</td><td>ES</td><td>//使能串口中断</td></tr><tr><td>SETB</td><td>EA</td><td></td></tr><tr><td>MOV</td><td>DPTR, #TESTSTR</td><td>//发送测试字符串</td></tr><tr><td>LCALL</td><td>SENDSTRING</td><td></td></tr><tr><td>SJMP $</td><td></td><td></td></tr><tr><td colspan="3">TESTSTR: 
DB &quot;STC15F2K60S2 Uart1 Test!&quot;,0DH,0AH,0</td></tr><tr><td colspan="3">};*--------</td></tr><tr><td colspan="3">;UART中断服务程序</td></tr><tr><td colspan="3">;--------*/</td></tr><tr><td>UART_ISR: 
PUSH</td><td>ACC</td><td></td></tr><tr><td>PUSH</td><td>PSW</td><td></td></tr><tr><td>JNB</td><td>RI, CHECKTI</td><td>//检测RI位</td></tr><tr><td>CLR</td><td>RI</td><td>//清除RI位</td></tr><tr><td>MOV</td><td>P0, SBUF</td><td>//P0显示串口数据</td></tr><tr><td>MOV</td><td>C, RB8</td><td></td></tr><tr><td>MOV</td><td>P2.2, C</td><td>//P2.2显示校验位</td></tr><tr><td>CHECKTI: 
JNB</td><td>TI, ISR_EXIT</td><td>//检测TI位</td></tr><tr><td>CLR</td><td>TI</td><td>//清除TI位</td></tr><tr><td>CLR</td><td>BUSY</td><td>//清忙标志</td></tr><tr><td>ISR_EXIT: 
POP</td><td>PSW</td><td></td></tr><tr><td>POP</td><td>ACC</td><td></td></tr><tr><td>RETI</td><td></td><td></td></tr><tr><td colspan="3">;/*--------</td></tr><tr><td colspan="3">;发送串口数据</td></tr><tr><td colspan="3">;--------*/</td></tr><tr><td>SENDDATA: 
JB</td><td>BUSY, $</td><td>//等待前面的数据发送完成</td></tr><tr><td>MOV</td><td>ACC, A</td><td>//获取校验位P(PSW.0)</td></tr><tr><td>JNB</td><td>P, EVEN1INACC</td><td>//根据P来设置校验位</td></tr></table>

# ODD1INACC:

#if (PARITYBIT $= =$ ODD_PARITY) 

CLR TB8 

//设置校验位为0

#elif (PARITYBIT $= =$ EVEN_PARITY) 

SETB TB8 

//设置校验位为1

#endif 

SJMP PARITYBITOK 

EVEN1INACC: 

#if (PARITYBIT $= =$ ODD_PARITY) 

SETB TB8 

//设置校验位为1

#elif (PARITYBIT $= =$ EVEN_PARITY) 

CLR TB8 

//设置校验位为0

#endif 

PARITYBITOK: 

//校验位设置完成

SETB BUSY 

MOV SBUF, A 

//写数据到UART数据寄存器

RET 

;发送字符串

*/ 

SENDSTRING: 

CLR A 

MOVC A, @A+DPTR 

//读取字符

JZ STRINGEND 

//检测字符串结束标志

INC DPTR 

//字符串地址+1

LCALL SENDDATA 

//发送当前字符

SJMP SENDSTRING 

STRINGEND: 

RET 

END 

# 8.4.2 定时器1模式0(16位自动重装载)作串口1波特率发生器程序(C和汇编)

# 1. C程序：

/*- */ 

/* --- STC MCU Limited. - */ 

/* --- STC15F2K60S2 系列 定时器1用作串口1的波特率发生器举例-- */

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果 要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果 要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可---- -*/

/*- */ 

//假定测试芯片的工作 频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

#define FOSC 18432000L 

#define BAUD 115200 

#define NONE_PARITY 0 

#define ODD_PARITY 

#define EVEN_PARITY 2 

#define MARK_PARITY 3 

#define SPACE_PARITY 4 

#define PARITYBIT EVEN_PARITY 

sfr AUXR $=$ 0x8e; 

sbit P22 P2^2; 

bit 

void SendData(BYTE dat); 

void SendString(char *s); 

void main() 

#if (PARITYBIT $= =$ NONE_PARITY) 

$\mathrm { S C O N } = 0 \mathrm { x } 5 0$ 

#elif (PARITYBIT $= =$ ODD_PARITY) || (PARITYBIT $= =$ EVEN_PARITY) || (PARITYBIT ARITY)| (PARITYBIT $= =$ MARK_PARITY) MARK_PARITY) 

$\mathrm { S C O N } = 0 \mathrm { x d a }$ 

#elif (PARITYBIT $= =$ SPACE_PARITY) 

$\mathrm { S C O N } = 0 \mathrm { x d } 2$ 

#endif 

//8位可变波特率

//9位可变波特率,校验位初始为 1

//9位可变波特率,校验位初始为 0

$\mathrm{AUXR} = 0\mathrm{x}40$ //定时器1为1T模式TMOD $= 0\mathrm{x}00$ //定时器1为模式0(16位自动重载)TL1 $=$ (65536-(FOSC/4/BAUD)); //设置波特率重装值TH1 $=$ (65536-(FOSC/4/BAUD))>>8;TR1 $= 1$ //定时器1开始启动ES $= 1$ //使能串口中断EA $= 1$ ：SendString("STC15F2K60S2\r\nUart Test !r\n");while(1); $\}$ /\*\*  
UART中断服务程序\*/  
void Uart() interrupt 4 using 1  
{if (RI){ $\mathrm{RI} = 0;$ //清除RI位P0 $\equiv$ SBUF; //P0显示串口数据P22 $\equiv$ RB8; //P2.2显示校验位}if(TI){TI $= 0$ //清除TI位busy $= 0$ //清忙标志}  
}  
/\*\*  
发送串口数据\*/  
void SendData(BYTE dat){while (busy); //等待前面的数据发送完成ACC $\equiv$ dat; //获取校验位P(PSW.0)if(P)#if(PARITYBIT $\equiv$ ODD_PARITY)TB8 $= 0$ //设置校验位为0#elif(PARITYBIT $\equiv$ EVEN_PARITY)TB8 $= 1$ //设置校验位为1endif}else{#if(PARITYBIT $\equiv$ ODD_PARITY)TB8 $= 1$ //设置校验位为1

```c
elif (PARITYBIT == EVEN_PARITY)  
TB8 = 0; //设置校验位为0  
#endif  
}  
busy = 1;  
SBUF = ACC; //写数据到UART数据寄存器  
}  
/*___________发送字符串________*/  
void SendString(char *s)  
{ while (*s) //检测字符串结束标志  
{ SendData(*s++)； //发送当前字符  
}
```

# 2. 汇编程序：

/* */ 

/* --- STC MCU Limited. - */ 

/* --- STC15F2K60S2 系列 定时器1用作串口1的波特率发生器举例- */

/* --- 研发顾问QQ：800003751- *

/* --- Fax: 86-755-82905966 - */ 

/* --- Tel: 86-755-82948412 -- */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果 要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果 要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可- *

/*- */ 


//假定测试芯片的工作 频率为18.432MHz


```c
define NONE_PARITY 0 //无校验  
#define ODD_PARITY 1 //奇校验  
#define EVEN_PARITY 2 //偶校验  
#define MARK_PARITY 3 //标记校验  
#define SPACE_PARITY 4 //空白校验  
#define PARITYBIT EVEN_PARITY //定义校验位  
{//  
AUXR EQU 08EH //辅助寄存器  
BUSY BIT 20H.0 //忙标志位
```

```txt
ORG 0000H LJMP MAIN ORG 0023H LJMP UART_ISR 
```

ORG 0100H 

MAIN: 

CLR BUSY 

CLR EA 

MOV SP, #3FH 

```cmake
if (PARITYBIT == NONE_PARITY) 
```

MOV SCON, #50H //8位可变波特率

```lisp
elif (PARITYBIT == ODD_PARITY) || (PARITYBIT == EVEN_PARITY) || (PARITYBIT == MARK_PARITY) 
```

MOV SCON, #0DAH //9位可变波特率,校验位初始为 1

```cmake
elif (PARITYBIT == SPACE_PARITY) 
```

MOV SCON, #0D2H //9位可变波特率,校验位初始为 0

#endif 

```txt
// 
```

MOV AUXR, #40H //定时器1为1T模式

MOV TMOD, #00H //定时器1为模式0(16位自动重载)

MOV TL1, #0D8H //设置波特率重装值(65536-18432000/4/115200)

MOV TH1, #0FFH 

SETB TR1 //定时器1开始 运行

SETB //使能串口中断

SETB EA 

MOV DPTR, #TESTSTR //发送测试字符串

LCALL SENDSTRING 

SJMP $ 

TESTSTR: 

DB "STC15F2K60S2 Uart1 Test !",0DH,0AH,0 

```txt
:/ 
```

;UART 中断服务程序

```txt
\* 
```

UART_ISR: 

PUSH ACC 

PUSH PSW 

JNB RI, CHECKTI //检测RI位

CLR RI //清除RI位

MOV P0, SBUF //P0显示串口数据

MOV C, RB8 

MOV P2.2, C //P2.2显示校验位

CHECKTI: 

JNB TI, 

ISR_EXIT 

//检测TI位

CLR TI 

//清除TI位

CLR BUSY 

//清忙标志

ISR_EXIT: 

POP PSW 

POP ACC 

RETI 

;/*-- 

;发送串口数据

-*/ 

SENDDATA: 

JB BUSY, $ 

//等待前面的数据发送完成

MOV ACC, A 

//获取校验位P (PSW.0)

JNB P, EVEN1INACC 

//根据P来设置校验位

ODD1INACC: 

#if (PARITYBIT $= =$ ODD_PARITY) 

CLR TB8 

//设置校验位为0

#elif (PARITYBIT $= =$ EVEN_PARITY) 

SETB TB8 

//设置校验位为1

#endif 

SJMP PARITYBITOK 

EVEN1INACC: 

#if (PARITYBIT $= =$ ODD_PARITY) 

SETB TB8 

//设置校验位为1

#elif (PARITYBIT $= =$ EVEN_PARITY) 

CLR TB8 

//设置校验位为0

#endif 

PARITYBITOK: 

//校验位设置完成

SETB BUSY 

MOV SBUF, A 

//写数据到UART数据寄存器

RET 

;/*- 

;发送字符串

-*/ 

SENDSTRING: 

CLR A 

MOVC A, @A+DPTR 

//读取字符

JZ STRINGEND 

//检测字符串结束标志

INC DPTR 

//字符串地址+1

LCALL SENDDATA 

//发送当前字符

SJMP SENDSTRING 

STRINGEND: 

RET 

//- 

END 

# 8.4.3 定时器1模式2(8位自动重装载)作串口1波特率发生器程序(建议不学)

# 1. C程序：

/* */ 

/* --- STC MCU Limited. - */ 

/* --- STC15F2K60S2 系列 定时器1用作串口1的波特率发生器举例-- */

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果 要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果 要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可- *

/* */ 

//假定测试芯片的工作 频率为18.432MHz#include "reg51.h"

#include "intrins.h" 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

#define FOSC 18432000L //系统频率

#define BAUD 115200 //串口波特率

#define NONE_PARITY 0 //无校验

#define ODD_PARITY //奇校验

#define EVEN_PARITY 2 //偶校验

#define MARK_PARITY 3 //标记校验

#define SPACE_PARITY 4 //空白校验

#define PARITYBIT EVEN_PARITY //定义校验位

sfr AUXR $=$ 0x8e; //辅助寄存器

sbit P22 P2^2; 

bit busy; 

void SendData(BYTE dat); 

void SendString(char $^ { * } \mathrm { { s } }$ ); 

void main() 

{ 

#if (PARITYBIT $= =$ NONE_PARITY) 

$\mathrm { S C O N } = 0 \mathrm { x } 5 0$ ; //8位可变波特率

#elif (PARITYBIT $= =$ ODD_PARITY) || (PARITYBIT $= =$ EVEN_PARITY) || (PARITYBIT $= =$ MARK_PARITY) 

$\mathrm { S C O N } = 0 \mathrm { x d a }$ ; //9位可变波特率,校验位初始为 1

```c
elif (PARITYBIT == SPACE_PARITY)  
SCON = 0xd2; //9位可变波特率,校验位初始为0  
#endif  
AUXR = 0x40; //定时器1为1T模式  
TMOD = 0x20; //定时器1为模式2(8位自动重载)  
TL1 = (256 - (FOSC/32/BAUD)); //设置波特率重装值  
TH1 = (256 - (FOSC/32/BAUD));  
TR1 = 1; //定时器1开始工作  
ES = 1; //使能串口中断  
EA = 1;  
SendString("STC15F2K60S2\r\nUart Test !\r\n");  
while(1);  
}  
/*___________*/  
UART中断服务程序________*/  
void Uart() interrupt 4 using 1  
{  
if (RI)  
{  
    RI = 0; //清除RI位  
    P0 = SBUF; //P0显示串口数据  
    P22 = RB8; //P2.2显示校验位  
}  
if (TI)  
{  
    TI = 0; //清除TI位  
    busy = 0; //清忙标志  
}  
}  
/*___________*/  
发送串口数据________*/  
void SendData(BYTE dat)  
{  
while (busy); //等待前面的数据发送完成  
ACC = dat; //获取校验位P(PSW.0)  
if (P) //根据P来设置校验位  
{  
if (PARITYBIT == ODD_PARITY)  
TB8 = 0; //设置校验位为0  
#elif (PARITYBIT == EVEN_PARITY)  
TB8 = 1; //设置校验位为1  
#endif  
}
```

else{#if (PARITYBIT $= =$ ODD_PARITY)TB8 $= 1$ //设置校验位为1#elif (PARITYBIT $= =$ EVEN_PARITY)TB8 $= 0$ //设置校验位为0endif}busy $= 1$ SBUF $\equiv$ ACC; //写数据到UART数据寄存器  
}/*-发送字符串\*/void SendString(char \*s)while $(^{*}\mathrm{s})$ //检测字符串结束标志{SendData $(^{*}\mathrm{s} + + )$ //发送当前字符}

# 2. 汇编程序：

/* */ 

/* --- STC MCU Limited. --- */ 

/* --- STC15F2K60S2 系列 定时器1用作串口1的波特率发生器举例- */

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 - */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com */ 

/* 如果 要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果 要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可- *

/* */ 

//假定测试芯片的工作 频率为18.432MHz

```c
define NONE_PARITY 0 //无校验  
#define ODD_PARITY 1 //奇校验  
#define EVEN_PARITY 2 //偶校验  
#define MARK_PARITY 3 //标记校验  
#define SPACE_PARITY 4 //空白校验  
#define PARITYBIT EVEN_PARITY //定义校验位
```

```txt
AUXR EQU 08EH //辅助寄存器  
BUSY BIT 20H.0 //忙标志位
```

```txt
// 
```

ORG 0000H 

LJMP MAIN 

ORG 0023H 

LJMP UART_ISR 

```txt
// 
```

ORG 0100H 

```txt
MAIN: 
```

CLR BUSY 

CLR EA 

MOV SP, #3FH 

```cmake
if (PARITYBIT == NONE_PARITY) 
```

MOV SCON, #50H //8位可变波特率

```lisp
elif (PARITYBIT == ODD_PARITY) || (PARITYBIT == EVEN_PARITY) || (PARITYBIT == MARK_PARITY) 
```

MOV SCON, #0DAH //9位可变波特率,校验位初始为 1

```cmake
elif (PARITYBIT == SPACE_PARITY) 
```

MOV SCON, #0D2H //9位可变波特率,校验位初始为 0

```txt
endif 
```

MOV AUXR, #40H //定时器1为1T模式

MOV TMOD, #20H //定时器1为模式2(8位自动重载)

MOV TL1, #0FBH //设置波特率重装值(256-18432000/32/115200)

MOV TH1, #0FBH 

SETB TR1 //定时器1开始 运行

SETB ES //使能串口中断

SETB EA 

MOV DPTR, #TESTSTR //发送测试字符串

LCALL SENDSTRING 

```txt
SJMP $ 
```

```txt
TESTSTR: 
```

DB "STC15F2K60S2 Uart1 Test !",0DH,0AH,0 

```txt
/水
```

```txt
;UART中断服务程序
```

```txt
\* 
```

```txt
UARTISR: 
```

PUSH ACC 

PUSH PSW 

JNB RI, CHECKTI //检测RI位

CLR RI //清除RI位

MOV P0, SBUF //P0显示串口数据

MOV C, RB8 

<table><tr><td>MOV</td><td>P2.2,</td><td>C</td><td>//P2.2显示校验位</td></tr><tr><td>CHECKTI:</td><td></td><td></td><td></td></tr><tr><td>JNB</td><td>TI,</td><td>ISR_EXIT</td><td>//检测TI位</td></tr><tr><td>CLR</td><td>TI</td><td></td><td>//清除TI位</td></tr><tr><td>CLR</td><td>BUSY</td><td></td><td>//清忙标志</td></tr><tr><td>ISR_EXIT:</td><td></td><td></td><td></td></tr><tr><td>POP</td><td>PSW</td><td></td><td></td></tr><tr><td>POP</td><td>ACC</td><td></td><td></td></tr><tr><td>RETI</td><td></td><td></td><td></td></tr><tr><td colspan="4">;/*--------*/</td></tr><tr><td colspan="4">;发送串口数据</td></tr><tr><td colspan="4">;--------*/</td></tr><tr><td>SENDDATA:</td><td></td><td></td><td></td></tr><tr><td>JB</td><td>BUSY,</td><td>$</td><td>//等待前面的数据发送完成</td></tr><tr><td>MOV</td><td>ACC,</td><td>A</td><td>//获取校验位P(PSW.0)</td></tr><tr><td>JNB</td><td>P,</td><td>EVEN1INACC</td><td>//根据P来设置校验位</td></tr><tr><td>ODD1INACC:</td><td></td><td></td><td></td></tr><tr><td colspan="4">#if (PARITYBIT==ODD_PARITY)</td></tr><tr><td>CLR</td><td>TB8</td><td></td><td>//设置校验位为0</td></tr><tr><td colspan="4">#elif (PARITYBIT==EVEN_PARITY)</td></tr><tr><td>SETB</td><td>TB8</td><td></td><td>//设置校验位为1</td></tr><tr><td colspan="4">#endif</td></tr><tr><td>SJMP</td><td>PARITYBITOK</td><td></td><td></td></tr><tr><td>EVEN1INACC:</td><td></td><td></td><td></td></tr><tr><td colspan="4">#if (PARITYBIT==ODD_PARITY)</td></tr><tr><td>SETB</td><td>TB8</td><td></td><td>//设置校验位为1</td></tr><tr><td colspan="4">#elif (PARITYBIT==EVEN_PARITY)</td></tr><tr><td>CLR</td><td>TB8</td><td></td><td>//设置校验位为0</td></tr><tr><td colspan="4">#endif</td></tr><tr><td>PARITYBITOK:</td><td></td><td></td><td>//校验位设置完成</td></tr><tr><td>SETB</td><td>BUSY</td><td></td><td></td></tr><tr><td>MOV</td><td>SBUF,</td><td>A</td><td>//写数据到UART数据寄存器</td></tr><tr><td>RET</td><td></td><td></td><td></td></tr><tr><td colspan="4">;/*--------*/</td></tr><tr><td colspan="4">;发送字符串</td></tr><tr><td colspan="4">;--------*/</td></tr><tr><td>SENDSTRING:</td><td></td><td></td><td></td></tr><tr><td>CLR</td><td>A</td><td></td><td></td></tr><tr><td>MOVC</td><td>A,</td><td>@A+DPTR</td><td>//读取字符</td></tr><tr><td>JZ</td><td>STRINGEND</td><td></td><td>//检测字符串结束标志</td></tr><tr><td>INC</td><td>DPTR</td><td></td><td>//字符串地址+1</td></tr><tr><td>LCALL</td><td>SENDDATA</td><td></td><td>//发送当前字符</td></tr><tr><td>SJMP</td><td>SENDSTRING</td><td></td><td></td></tr><tr><td>STRINGEND:</td><td></td><td></td><td></td></tr><tr><td>RET</td><td></td><td></td><td></td></tr><tr><td>END</td><td></td><td></td><td></td></tr></table>

# 8.5 串行口2的相关寄存器

<table><tr><td rowspan="2">符号</td><td rowspan="2">描述</td><td rowspan="2">地址</td><td colspan="9">位地址及符号</td><td rowspan="2">复位值</td></tr><tr><td colspan="6">MSB</td><td colspan="3">LSB</td></tr><tr><td>S2CON</td><td>Serial 2 Control register</td><td>9AH</td><td>S2SM0</td><td>-</td><td>S2SM2</td><td>S2REN</td><td>S2TB8</td><td>S2RB8</td><td>S2TI</td><td>S2RI</td><td>0000 0000B</td><td></td></tr><tr><td>S2BUF</td><td>Serial 2 Buffer</td><td>9BH</td><td colspan="9"></td><td>xxxx xxxxxB</td></tr><tr><td>T2H</td><td>定时器2高8位,装入重装数</td><td>D6H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>T2L</td><td>定时器2低8位,装入重装数</td><td>D7H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>AUXR</td><td>辅助寄存器</td><td>8EH</td><td>T0x12</td><td>T1x12</td><td>UART_M0x6</td><td>T2R</td><td>T2_C/T</td><td>T2x12</td><td>EXTRAM</td><td>S1ST2</td><td>0000 0001B</td><td></td></tr><tr><td>IE</td><td>Interrupt Enable</td><td>A8H</td><td>EA</td><td>ELVD</td><td>EADC</td><td>ES</td><td>ET1</td><td>EX1</td><td>ET0</td><td>EX0</td><td>0000 0000B</td><td></td></tr><tr><td>IE2</td><td>Interrupt Enable 2</td><td>AFH</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>ESPI</td><td>ES2</td><td>xxxx xx00B</td><td></td></tr><tr><td>IP2</td><td>Interrupt Priority 2 Low</td><td>B5H</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>PSPI</td><td>PS2</td><td>x000 0000B</td><td></td></tr><tr><td>P_SW2</td><td>外围设备功能切换控制寄存器</td><td>BAH</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>S4_S</td><td>S3_S</td><td>S2_S</td><td>xxxx x000B</td><td></td></tr></table>

# 1.串行口2的控制寄存器S2CON

串行口2控制寄存器S2CON用于确定串行口2的工作 方式和某些控制功能。其格式如下 ：

S2CON : 串行口2控制寄存器

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>S2CON</td><td>9AH</td><td>name</td><td>S2SM0</td><td>-</td><td>S2SM2</td><td>S2REN</td><td>S2TB8</td><td>S2RB8</td><td>S2TI</td><td>S2RI</td></tr></table>

S2SM0：指定串行口2的工作 方式，如下 表所示。

<table><tr><td>S2SM0</td><td>工作方式</td><td>功能说明</td><td>波特率</td></tr><tr><td>0</td><td>方式0</td><td>8位UART, 波特率可变</td><td>(定时器T2的溢出率)/4</td></tr><tr><td>1</td><td>方式1</td><td>9位UART, 波特率可变</td><td>(定时器T2的溢出率)/4</td></tr><tr><td colspan="4">当AUXR.2/T2x12=1时, 定时器T2的溢出率 = SYSclk / (65536 - [RL_TH2,RL_TL2]) 
当AUXR.2/T2x12=0时, 定时器T2的溢出率 = SYSclk / 12 / (65536 - [RL_TH2,RL_TL2]) 
式中RL_TH2是T2H的重装载寄存器, RL_TL2是T2L的重装载寄存器。</td></tr></table>

B6:保留，该位复位后为0.

S2SM2：允许方式1多机通信控制位。

方式1时，如果 S2SM2位为1且S2REN位为1，则接收机处于地址帧筛选状态。此 时可以利用接收到的第9位(即S2RB8)来筛选地址帧：若S2RB8=1，说明该帧是地址帧，地址信息可以进入S2 BUF，并使S2RI为 1，进而在中断服务程序中再进行地址号比较；若S2RB8=0，说明该帧不是地址帧，应丢掉且保持S2RI=0。在 方式1中，如果S2 SM2位为0且S2REN位为1，接收收机处于地址帧筛选被禁止状态。不论收到的S2RB8为0或1，均可使接收到的信息进入 S2BUF,并使S2RI=1,此 时S2RB8通常为校验位.

方式0是非多机通信方式，在这种方式时，要设置S2SM2 应为0。



S2REN：允许/禁止串行口2接收控制位。由 软件置位S2REN，即S2REN $[ = 1$ 为允许串行接收状态，可启动串行接收器RxD2，开始 接收信息。软件复位S2REN，即S2REN=0，则禁止接收。





S2TB8：在方式1，S2TB8为要发送的第9位数据，按需要由软件置位或清0。例如，可用作数 据的校验位或多机通信中表示地址帧/数据帧的标志位。在 方式0中，该位不用.





S2RB8：在方式1，S2RB8是接收到的第9位数据，作为 奇偶校验位或地址帧/数据帧的标志位。方式0中不用S2RB8(置S2SM2=0, S2RB8是接收到的停止位)。





S2TI：发送中断请求标志位。在 停止位开始 发送时由S2 TI内部硬件置位，即S2TI=1,响应中断后S2TI必须用软件清零。





S2RI：接收中断请求标志位。在 串行接收到停止位的中间时刻S2RI由 内部硬件置位，即S2RI=1,向CPU发中断申请，响应中断后S2RI必须由软件清零。





S2CON的所有位可通过整机复位信号复位为全 0”�。S2CON的字节地址为9AH，不可位寻址。串行通信的中断请求：当一帧发送完成，内部硬件自动置位S2TI，即S2TI=1，请求中断处理；当接收完一帧信息时，内部硬件自动置位S2RI，即S2RI=1，请求中断处理。由 于S2TI和S2RI以“或逻辑”关系向�主机请求中断，所以�主机响应中断时事先并不��知道 是S2TI还是S2RI请求的中断，必须在中断服务程序中查询S2TI和S2RI进行判别，然后分别处理。因此，两个中断请求标志位均不能由硬件自动置位，必须通过软件清0，否则将出现一次请求多次响应的错误。



# 2.串行口2的数据缓冲寄存器S2BUF

STC15系列单片机的串行口2数 据缓冲寄存器(S2BUF)的地址是9BH，实际是2个 缓冲器，写S2BUF的操作 完成待发送数 据的加载，读S2BUF的操作 可获得已接收到的数据。两个操作 分别对应两个不同的寄存器，1个是只写寄存器，1个是只读寄存器。

串行通道内设有数据寄存器。在 所有的串行通信方式中，在写入S2BUF信号（MOVS2BUF,A）的控制下，把数据装入相同的9位移位寄存器，前面8位为数 据字节，其最低位为移位寄存器的输出位。根据不同的工作 方式会自动将 1” S2TB8的值装入移位寄存器的第9位,并进行发送.

串行通道的接收寄存器是一个 输入移位寄存器。在 方式0和方式1时均为9位。当一帧接收完毕，移位寄存器中的数据字节装入串行数据缓冲器S2BUF中,其第9位则装入S2CON寄存器中的S2RB8位。如果由 于S2SM2使得已接收到的数据无效时,S2RB8和S2BUF中内容不变.

由于接收通道内设有输入移位寄存器和S2BUF缓冲器，从而能使一帧接收完将数据由移位寄存器装入S2BUF后，可立即开始 接收下一 帧信息，主机应在该帧接收结束前从S2BUF缓冲器中将数据取走，否则前一帧数据将丢失。S2BUF以并行方式送往 内部数 据总线。

# 3.串行口2只能选择定时器2作为其波特率发生器——定时器2的寄存器T2H, T2L

定时器2寄存器T2H(地址为D6H，复位值为00H)及寄存器T2L(地址为D7H，复位值为00H)用于保存重装时间常数。

注意：对于STC15系列单片机，串口2永远是使用定时器���2作为 波特率发生器�,串口�2不能够选择其他定时器�作其波特率发生器�串口1默认选择定时器2作为 其波特率发生器，也可以选择定时器1作为 其波特率发生器；串口3默认选择定时器2作为 其波特率发生器，也可以选择定时器3作为其波特率发生器；串口4默认选择定时器2作为 其波特率发生器，也可以选择定时器4作为 其波特率发生器。

# 4.定时器2的控制位— TR2、T2_C/T、T2x12

AUXR : 辅助寄存器 (不可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>AUXR</td><td>8EH</td><td>name</td><td>T0x12</td><td>T1x12</td><td>UART_M0x6</td><td>T2R</td><td>T2_C/T</td><td>T2x12</td><td>EXTRAM</td><td>S1ST2</td></tr></table>

T2R：定时器2运行控制位

0，不允许定时器�2

1，允许定时器�

T2_C/T: 控制定时器2用作定时器或计数 器。

0, 用作定时器(对内部系统时钟进 行计数 )；

1, 用作计数 器(对引脚T2/P3.1的外部脉冲进行计数 )

T2x12: 定时器2速度控制位

0, 定时器2是传统8051速度，12分频；

1, 定时器2的速度是传统8051的12倍，不分频

如果 串口1或串口2用T2作为 波特率发生器，则由T2x12决定串口1或串口2是12T还是1T.

对于STC15系列单片机，串口2只能使用定时器2作为波特率发生器，不能够选择其他定时器作为 其波特率发生器；而串口1默认选择定时器2作为 其波特率发生器，也可以选择定时器1作为 其波特率发生器；串口3默认选择定时器2作为 其波特率发生器，也可以选择定时器3作为其波特率发生器；串口4默认选择定时器2作为 其波特率发生器，也可以选择定时器4作为 其波特率发生器。

# 5.与串行口2中断相关的寄存器

串行口2中断允许位ES2位于中断允许寄存器IE2中，中断允许寄存器的格式如下 ：

IE2 : 中断允许寄存器2 (不可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IE2</td><td>AFH</td><td>name</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>ESPI</td><td>ES2</td></tr></table>

ES2 : 串行口2中断允许位，ES2=1，允许串行口2中断，ES2=0，禁止串行口2中断。

IE : 中断允许寄存器 (可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IE</td><td>A8H</td><td>name</td><td>EA</td><td>ELVD</td><td>EADC</td><td>ES</td><td>ET1</td><td>EX1</td><td>ET0</td><td>EX0</td></tr></table>

EA : CPU的总中断允许控制位，EA=1，CPU开放中断，EA=0，CPU屏蔽所有的中断申请。

EA的作用是使中断允许形成多级控制。即各中断源首先受EA控制;其次还受各中断源自己的中断允许控制位控制。

串行口2中断优先级控制位PS2 位位于中断优先级控制寄存器IP中，中断优先级控制寄存器的格式如下 ：

IP2 : 中断优先级控制寄存器 (不可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IP2</td><td>B5H</td><td>name</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>PSPI</td><td>PS2</td></tr></table>

PS2: 串行口2中断优先级控制位。

当PS2=0时，串行口2中断为最低优先级中断(优先级0)

当PS2=1时，串行口2中断为最高优先级中断(优先级1)

# 6.串行口2在2组管脚之间切换的控制位— S2_S/P_SW2.0

通过设置寄存器P_S W2中的S2_S 位，可以将串口2在2组 管脚之间任意切换，P_S W2寄存器的格式如下 ：

P_SW2: 外围设备功能切换控制寄存器2 (不可位寻址)

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td><td>Reset Value</td></tr><tr><td>P_SW2</td><td>BAH</td><td>外围设备功能切换控制寄存器2</td><td></td><td></td><td></td><td></td><td></td><td>S4_S</td><td>S3_S</td><td>S2_S</td><td>xxxx,x000</td></tr></table>

<table><tr><td colspan="2">串口2/S2可在2个地方切换,由 S2_S 控制位来选择</td></tr><tr><td>S2_S</td><td>S2可在P1/P4之间来回切换</td></tr><tr><td>0</td><td>串口2/S2在[P1.0/RxD2,P1.1/TxD2]</td></tr><tr><td>1</td><td>串口2/S2在[P4.6/RxD2_2,P4.7/TxD2_2]</td></tr></table>

<table><tr><td colspan="2">串口3/S3可在2个地方切换，由S3_S控制位来选择</td></tr><tr><td>S3_S</td><td>S3可在P0/P5之间来回切换</td></tr><tr><td>0</td><td>串口3/S3在[P0.0/RxD3, P0.1/TxD3]</td></tr><tr><td>1</td><td>串口3/S3在[P5.0/RxD3_2, P5.1/TxD3_2]</td></tr></table>

<table><tr><td colspan="2">串口4/S4可在2个地方切换，由S4_S控制位来选择</td></tr><tr><td>S4_S</td><td>S4可在P0/P5之间来回切换</td></tr><tr><td>0</td><td>串口4/S4在[P0.2/RxD4, P0.3/TxD4]</td></tr><tr><td>1</td><td>串口4/S4在[P5.2/RxD4_2, P5.3/TxD4_2]</td></tr></table>

# 8.6 串行口2工作模式

STC15W4K60S4系列单片机的串行口2有两种工作 模式，可通过软件编程对S2CON中的S2SM0的设置进行选择。其中模式0和模式1都为异步通信，每个发送和接收的字符都带有1个启动位和1个停止位。

# 8.6.1 串行口2的工作模式0----8位UART，波特率可变

10 � RxD2/P1.0(RxD2_2/P4.6)接收，通过TxD2/P1.1(TxD2_2/P4.7)发送。一 帧数据包含一个 起始位(0),�8��个数 据位和一个��停止位(1)�。 ��S2CON的S2RB8位。波特率由定时器T2的溢出率决定。

串口2在 模式0的 $=$ 定时器 � �

当T2工作在 1T模式(AUXR.2/T2x12=1)时 定时器�2 =SYSclk / ( 65536 - [RL_TH2, RL_TL2] )；

即此时，串行口2的波特率=SYSclk / ( 65536 - [RL_TH2, RL_TL2]) / 4

当T2工作在 12T模式(AUXR.2/T2x12=0)时 定时器�2 =SYSclk /12/(65536 - [RL_TH2, RL_TL2])；

即此时，串行口2的波特率=SYSclk / 12 / ( 65536 - [RL_TH2, RL_TL2]) / 4

上式中RL_TH2是T2H的重装载寄存器，RL_TL2是T2L的重装载寄存器。

# 8.6.2 串行口2的工作模式1----9位UART，波特率可变

11位数据通过RxD2/P1.0(RxD2_2/P4.6)发送，通过TxD2/P1.1(TxD2_2/P4.7)接收。一 帧�据包含一个 起始位(0)，8个数 据位，一个 可编程的第9位，和一个 停止位(1)。发送时，第9位数据位来自特殊功能寄存器S2CON的S2TB8位.接收时，第9位进入 特殊功能寄存器S2CON的S2RB8位。

串口2在 模式1的 $=$ T2 定时器�2 �

当T2工作在 1T模式(AUXR.2/T2x12=1)时 定时器�2 =SYSclk / ( 65536 - [RL_TH2, RL_TL2] )；

即此时，串行口2的波特率=SYSclk / ( 65536 - [RL_TH2, RL_TL2]) / 4

当T2工作在 12T模式(AUXR.2/T2x12=0)时 定时器�2 =SYSclk /12/(65536 - [RL_TH2, RL_TL2])；

即此时，串行口2的波特率=SYSclk / 12 / ( 65536 - [RL_TH2, RL_TL2]) / 4

上式中RL_TH2是T2H的重装载寄存器，RL_TL2是T2L的重装载寄存器。

可见，模式1和模式0一样，其波特率可通过软件对定时器2的设置进行波特率的选择，是可变的。

用户在 程序中如何具体使用串口2

1.设置串口2的工作 模式，S2CON寄存器中的S2SM0决定了串口2的2种工作 模式

2.设置串口2的波特率相应的寄存器：

定时器� T2H / T2L

3.启动定时器�2 �T2R位为1，定时器��2就 ����

4.设置AUXR.2�/T2�x1��2,确定定时器�2的速度

5.设置串口2的中断优先级，及打开中断相应的控制位是:

PS2, PS2H, ES2, EA 

6.如要串口2接收，将S2REN置1 即可

如要串口2发送，将数据送入 S2BUF即可，

接收完成标志S2RI,发送完成标志S2TI,要由软件清0。

# 8.7 串行口2的测试程序(C和汇编)

# 使用定时器2作串口2的波特率发生器

# 1. C程序：

/*- */ 

/* --- STC MCU Limited. - */ 

/* --- STC15F2K60S2 系列 定时器2用作串口2的波特率发生器举例- */

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果 要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果 要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- *

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可------------*/

/* ------------ */ 

//假定测试芯片的工作 频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

#define FOSC 18432000L //系统频率

#define BAUD 115200 //串口波特率

#define TM (65536 - (FOSC/4/BAUD)) 

#define NONE_PARITY 0 //无校验

#define ODD_PARITY 1 //奇校验

#define EVEN_PARITY 2 //偶校验

#define MARK_PARITY 3 //标记校验

#define SPACE_PARITY 4 //空白校验

#define PARITYBIT EVEN_PARITY //定义校验位

sfr AUXR $=$ 0x8e; //辅助寄存器

sfr S2CON $=$ 0x9a; //UART2 控制寄存器

sfr S2BUF $=$ 0x9b; //UART2 数据寄存器

sfr T2H $=$ 0xd6; //定时器2高8位

sfr T2L 0xd7; //定时器2低8位

sfr IE2 = 0xaf; //中断控制寄存器2

#define S2RI 0x01 //S2CON.0 

#define S2TI 0x02 //S2CON.1 

#define S2RB8 0x04 

//S2CON.2 

#define S2TB8 0x08 

//S2CON.3 

bit busy; 

void SendData(BYTE dat); 

void SendString(char $^ { * } \mathrm { { s } }$ 

void main() 

{ 

#if (PARITYBIT $= =$ NONE_PARITY) 

$\mathrm { S } 2 \mathrm { C O N } = \mathrm { 0 } \mathrm { x } \mathrm { 5 } 0$ 

//8位可变波特率

#elif (PARITYBIT $= =$ ODD_PARITY) $\parallel$ (PARITYBIT $= =$ EVEN_PARITY) || (PARITYBIT $= =$ MARK_PARITY) 

$\mathrm { S } 2 \mathrm { C O N } = \mathrm { 0 } \mathrm { x d a }$ 

//9位可变波特率,校验位初始为 1

#elif (PARITYBIT $= =$ SPACE_PARITY) 

$\mathrm { S } 2 \mathrm { C O N } = 0 \mathrm { x } \mathrm { d } 2$ 

//9位可变波特率,校验位初始为 0

#endif 

$\mathrm { T } 2 \mathrm { L } = \mathrm { T M }$ 

//设置波特率重装值

$\mathrm { T 2 H } = \mathrm { T M } > > 8$ 

//T2为1T模式, 并启动定时器2

$\mathbf { A U X R } = 0 \mathbf { x } 1 4$ ; 

//使能串口2中断

$\mathrm { I E } 2 = 0 \mathrm { x } 0 1$ 

$\mathrm { E A } = 1$ 

SendString("STC15F2K60S2\r\nUart2 Test !\r\n"); while(1); } 

/* 

UART2 中断服务程序

-*/ 

void Uart2() interrupt 8 using 1 

{if (S2CON & S2RI){S2CON &= ~S2RI; //清除S2RI位P0 = S2BUF; //P0显示串口数P2 = (S2CON & S2RB8); //P2.2显示校验}if (S2CON & S2TI){S2CON &= ~S2TI; //清除S2TI位busy ${ } = 0$ ; //清忙标志}

/* 


发送串口数据


void SendData(Byte dat)  
{ while (busy); //等待前面的数据发送完成 ACC $=$ dat; //获取校验位P(PSW.0) if(P) //根据P来设置校验位 { #if(PARITYBIT $\equiv$ ODD_PARITY) S2CON& $\equiv$ ~S2TB8; //设置校验位为0 #elif(PARITYBIT $\equiv$ EVEN_PARITY) S2CON $\mid =$ S2TB8; //设置校验位为1 #endif } else { #if(PARITYBIT $\equiv$ ODD_PARITY) S2CON $\mid =$ S2TB8; //设置校验位为1 #elif(PARITYBIT $\equiv$ EVEN_PARITY) S2CON& $\equiv$ ~S2TB8; //设置校验位为0 #endif } busy $= 1$ . S2BUF $=$ ACC; //写数据到UART2数据寄存器   
}   
/*   
发送字符串   
*/   
void SendString(char\*s)   
{ while (\*s) //检测字符串结束标志 { SendData\*(s++); //发送当前字符 }

# 2. 汇编程序：

/*- */ 

/* --- STC MCU Limited. - */ 

/* --- STC15F2K60S2 系列 定时器2用作串口2的波特率发生器举例-- */

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com */ 

/* 如果 要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果 要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可- *

/*- */ 

//假定测试芯片的工作 频率为18.432MHz

#define NONE_PARITY 0 

#define ODD_PARITY 1 

#define EVEN_PARITY 2 

#define MARK_PARITY 3 

#define SPACE_PARITY 4 

//无校验

//奇校验

//偶校验

//标记校验

//空白校验

#define PARITYBIT EVEN_PARITY 

//定义校验位

AUXR EQU 08EH 

S2CON EQU 09AH 

S2BUF EQU 09BH 

T2H DATA 0D6H 

T2L DATA 0D7H 

IE2 EQU 0AFH 

S2RI EQU 01H 

S2TI EQU 02H 

S2RB8 EQU 04H 

S2TB8 EQU 08H 

BUSY BIT 20H.0 

ORG 0000H 

LJMP MAIN 

ORG 0043H 

LJMP UART2_ISR 

//- 

ORG 0100H 

//辅助寄存器

//UART2 控制寄存器

//UART2 数据寄存器

//定时器2高8位

//定时器2低8位

//中断控制寄存器2

//S2CON.0 

//S2CON.1 

//S2CON.2 

//S2CON.3 

//忙标志位

MAIN: 

CLR BUSY 

CLR EA 

MOV SP, #3FH 

#if (PARITYBIT $= =$ NONE_PARITY) 

MOV S2CON, #50H 

//8位可变波特率

#elif (PARITYBIT $= =$ ODD_PARITY) || (PARITYBIT $= =$ EVEN_PARITY) || (PARITYBIT $= =$ MARK_PARITY) 

MOV S2CON, #0DAH 

//9位可变波特率,校验位初始为 1

#elif (PARITYBIT $= =$ SPACE_PARITY) 

MOV S2CON, #0D2H 

//9位可变波特率,校验位初始为 0

#endif 

//- 

MOV T2L, #0D8H 

//设置波特率重装值(65536-18432000/4/115200)

MOV T2H, #0FFH 

MOV AUXR, #14H 

//T2为1T模式, 并启动定时器2

ORL IE2, #01H 

//使能串口2中断

SETB EA 

MOV DPTR, #TESTSTR 

//发送测试字符串

LCALL SENDSTRING 

SJMP $ 

TESTSTR: 

DB "STC15F2K60S2 Uart2 Test !",0DH,0AH,0 

：/* 

;UART2 中断服务程序

-*/ 

UART2_ISR: 

PUSH ACC 

PUSH PSW 

MOV A, S2CON 

;读取UART2控制寄存器

JNB ACC.0, CHECKTI 

;检测S2RI位

ANL S2CON, #NOT S2RI 

;清除S2RI位

MOV P0, S2BUF 

;P0显示串口数据

ANL A, #S2RB8 

MOV P2, A 

;P2.2显示校验位

CHECKTI: 

MOV A, S2CON 

;读取UART2控制寄存器

JNB ACC.1, ISR_EXIT 

;检测S2TI位

ANL S2CON, #NOT S2TI 

;清除S2TI位

CLR BUSY 

;清忙标志

ISR_EXIT: 

POP PSW 

POP ACC 

RETI 

;/*-- 

;发送串口数据

-*/ 

SENDDATA: 

JB BUSY, $ 

//等待前面的数据发送完成

MOV ACC, A 

//获取校验位P (PSW.0)

JNB P, EVEN1INACC 

//根据P来设置校验位

ODD1INACC: 

#if (PARITYBIT $= =$ ODD_PARITY) 

ANL S2CON, #NOT S2TB8 

//设置校验位为0

#elif (PARITYBIT $= =$ EVEN_PARITY) 

ORL S2CON, #S2TB8 

//设置校验位为1

#endif 

SJMP PARITYBITOK 

EVEN1INACC: 

#if (PARITYBIT $= =$ ODD_PARITY) 

ORL S2CON, #S2TB8 

//设置校验位为1

#elif (PARITYBIT $= =$ EVEN_PARITY) 

ANL S2CON, #NOT S2TB8 

//设置校验位为0

#endif 

PARITYBITOK: 

SETB BUSY 

MOV S2BUF, A 

//写数据到UART2数据寄存器

RET 

;/*- 

;发送字符串

//- -*/ 

SENDSTRING: 

CLR A 

MOVC A, @A+DPTR 

//读取字符

JZ STRINGEND 

//检测字符串结束标志

INC DPTR 

//字符串地址+1

LCALL SENDDATA 

//发送当前字符

SJMP SENDSTRING 

STRINGEND: 

RET 

END 

# 8.8 串行口3的相关寄存器

<table><tr><td rowspan="2">符号</td><td rowspan="2">描述</td><td rowspan="2">地址</td><td colspan="9">位地址及符号</td><td rowspan="2">复位值</td></tr><tr><td colspan="6">MSB</td><td colspan="3">LSB</td></tr><tr><td>S3CON</td><td>串口3控制寄存器</td><td>ACH</td><td>S3SM0</td><td>S3ST3</td><td>S3SM2</td><td>S3REN</td><td>S3TB8</td><td>S3RB8</td><td>S3TI</td><td>S3RI</td><td></td><td>0000,0000</td></tr><tr><td>S3BUF</td><td>串口3数据缓冲器</td><td>ADH</td><td colspan="9"></td><td>xxxx,xxxx</td></tr><tr><td>T2H</td><td>定时器2高8位,装入重装数</td><td>D6H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>T2L</td><td>定时器2低8位,装入重装数</td><td>D7H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>AUXR</td><td>辅助寄存器</td><td>8EH</td><td>T0x12</td><td>T1x12</td><td>UART_M0x6</td><td>T2R</td><td>T2_C/T</td><td>T2x12</td><td>EXTRAM</td><td>S1ST2</td><td></td><td>0000 0001B</td></tr><tr><td>T3H</td><td>定时器3高8位寄存器</td><td>D4H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>T3L</td><td>定时器3低8位寄存器</td><td>D5H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>T4T3M</td><td>T4和T3的控制寄存器</td><td>D1H</td><td>T4R</td><td>T4_C/T</td><td>T4x12</td><td>T4CLKO</td><td>T3R</td><td>T3_C/T</td><td>T3x12</td><td>T3CLKO</td><td></td><td>0000 0000B</td></tr><tr><td>IE2</td><td>中断允许寄存器</td><td>AFH</td><td></td><td>ET4</td><td>ET3</td><td>ES4</td><td>ES3</td><td>ET2</td><td>ESPI</td><td>ES2</td><td></td><td>x000 0000B</td></tr><tr><td>P_SW2</td><td>外围设备功能切换控制寄存器</td><td>BAH</td><td colspan="9">- | - | - | - | - | S4_S | S3_S | S2_S</td><td>xxxx x000B</td></tr></table>

# 1.串行口3的控制寄存器S3CON

串行口3控制寄存器S3CON用于确定串行口3的工作 方式和某些控制功能。其格式如下 ：

S3CON : 串行口3控制寄存器

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>S3CON</td><td>ACH</td><td>name</td><td>S3SM0</td><td>S3ST3</td><td>S3SM2</td><td>S3REN</td><td>S3TB8</td><td>S3RB8</td><td>S3TI</td><td>S3RI</td></tr></table>

S3SM0：指定串行口3的工作 方式，如下 表所示。

<table><tr><td>S3SM0</td><td>工作方式</td><td>功能说明</td><td>波特率</td></tr><tr><td>0</td><td>方式0</td><td>8位UART, 波特率可变</td><td>(定时器T2的溢出率)/4 或 (定时器T3的溢出率)/4</td></tr><tr><td>1</td><td>方式1</td><td>9位UART, 波特率可变</td><td>(定时器T2的溢出率)/4 或 (定时器T3的溢出率)/4</td></tr><tr><td colspan="4">当AUXR.2/T2x12=1时, 定时器T2的溢出率 = SYSclk / (65536 - [RL_TH2,RL_TL2])当AUXR.2/T2x12=0时, 定时器T2的溢出率 = SYSclk / 12 / (65536 - [RL_TH2,RL_TL2])式中RL_TH2是T2H的重装载寄存器, RL_TL2是T2L的重装载寄存器。当T4T3M.1/T3x12=1时, 定时器T3的溢出率 = SYSclk / (65536 - [RL_TH3,RL_TL3])当T4T3M.1/T3x12=0时, 定时器T3的溢出率 = SYSclk / 12 / (65536 - [RL_TH3,RL_TL3])式中RL_TH3是T3H的重装载寄存器, RL_TL3是T3L的重装载寄存器。</td></tr></table>

S3ST3：串口3(UART3)选择定时器3作波特率发生器的控制位。

0，串行 ���2 其

1，串行口3 ��其

S3SM2：允许方式1多机通信控制位。

方式1时，如果 S3SM2位为1且S3REN位为1，则接收机处于地址帧筛选状态。此 时可以利用接收到的第9位(即S3RB8)来筛选地址帧：若 $\mathrm { S 3 R B 8 { = } 1 }$ ，说明该帧是地址帧，地址信息可以进入S 3BUF，并使S3RI为 1，进而在中断服务程序中再进行地址号比较；若S3RB8=0，说明该帧不是地址帧，应丢掉且保持 $\mathrm { S 3 R I { = } 0 }$ 。在 方式1中，如果S 3SM2位为0且S3REN位为1，接收收机处于地址帧筛选被禁止状态。不论收到的S3RB8为0或1，均可使接收到的信息进入S 3BUF,并使S3RI=1,此 时S3RB8通常为校验位.方式0是非多机通信方式，在这种方式时，要设置S3SM2 应为0。

S3REN：允许/禁止串行口3接收控制位。由 软件置位S3REN，即S3REN=1为允许串行接收状态，可启动串行接收器RxD3，开始 接收信息。软件复位S3REN，即S3REN=0，则禁止接收。

S3TB8：在方式1，S3TB8为要发送的第9位数据，按需要由软件置位或清0。例如，可用作数 据的校验位或多机通信中表示地址帧/数据帧的标志位。在 方式0中，该位不用.

S3RB8：在方式1，S3RB8是接收到的第9位数据，作为 奇偶校验位或地址帧/数据帧的标志位。方式0中不用S3RB8(置S3SM2=0, S3RB8是接收到的停止位)。

S3TI：发送中断请求标志位。在 停止位开始 发送时由S 3TI内部硬件置位，即S3TI=1,响应中断后S3TI必须用软件清零。

S3RI：接收中断请求标志位。在 串行接收到停止位的中间时刻S3RI由 内部硬件置位，即S3RI=1,向CPU发中断申请，响应中断后S3RI必须由软件清零。

S3CON的所有位可通过整机复位信号复位为全 0”�。S3CON的字节地址为ACH，不可位寻址。串行通信的中断请求：当一帧发送完成，内部硬件自动置位S3TI，即 ${ \bf S } 3 \mathrm { T I } { = } 1$ ，请求中断处理；当接收完一帧信息时，内部硬件自动置位S3RI，即S3RI=1，请求中断处理。由 于S3TI和S3RI以“或逻辑”关系向�主机请求中断，所以�主机响应中断时事先并不��知道 是S3TI还是S3RI请求的中断，必须在中断服务程序中查询S3TI和S3RI进行判别，然后分别处理。因此，两个中断请求标志位均不能由硬件自动置位，必须通过软件清0，否则将出现一次请求多次响应的错误。

# 2.串行口3的数据缓冲寄存器S3BUF

STC15W4K60S4系列单片机的串行口3数据缓冲寄存器(S3BUF)的地址是ADH，实际是2个 缓冲器，写S3BUF的操作 完成待发送数 据的加载，读S3BUF的操作 可获得已接收到的数据。两个操作分别对应两个不同的寄存器，1个是只写寄存器，1个是只读寄存器。

串行通道内设有数据寄存器。在 所有的串行通信方式中，在写入S3BUF信号（MOVS3BUF,A）的控制下，把数据装入相同的9位移位寄存器，前面8位为数 据字节，其最低位为移位寄存器的输出位。根据不同的工作 方式会自动将 1” S3TB8的值装入移位寄存器的第9位,并进行发送.

串行通道的接收寄存器是一个 输入移位寄存器。在 方式0和方式1时均为9位。当一帧接收完毕，移位寄存器中的数据字节装入串行数据缓冲器S3BUF中,其第9位则装入S3CON寄存器中的S3RB8位。如果由 于S3SM2使得已接收到的数据无效时,S3RB8和S3BUF中内容不变.

由于接收通道内设有输入移位寄存器和S3BUF缓冲器，从而能使一帧接收完将数据由移位寄存器装入S3BUF后，可立即开始 接收下一 帧信息，主机应在该帧接收结束前从S3BUF缓冲器中将数据取走，否则前一帧数据将丢失。S3BUF以并行方式送往 内部数 据总线。

# 3. 串行口3既能选择定时器2作为其波特率发生器，也能选择定时器3作为其波特率发生器— 定时器2的寄存器T2H, T2L和定时器3的寄存器T3H, T3L

定时器2寄存器T2H(地址为D6H，复位值为00H)及寄存器T2L(地址为D7H，复位值为00H)用于保存重装时间常数。

定时器3寄存器T3H(地址为D4H，复位值为00H)及寄存器T3L(地址为D5H，复位值为00H)用于保存重装时间常数。

注意：有串口2的单片机，串口2永远是使用定时器���2作为 波特率发生器�,串口�2不能够选择定时器1 做波特率发生器，串口1可以选择定时器1做波特率发生器，也可以选择定时器���率发生器�。而 �做波特率发生器，也可以选择定时器 ��器�。同样串口�4可以选择定时器�2做波特率发生器，也可以选择定时器���4作为 波特率发生器

# 4.定时器2的控制位— TR2、T2_C/T、T2x12

AUXR : 辅助寄存器 (不可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>AUXR</td><td>8EH</td><td>name</td><td>T0x12</td><td>T1x12</td><td>UART_M0x6</td><td>T2R</td><td>T2_C/T</td><td>T2x12</td><td>EXTRAM</td><td>S1ST2</td></tr></table>

T2R：定时器2运行控制位

0，不允许定时器�2

1，允许定时器�

T2_C/T: 控制定时器2用作定时器或计数 器。

0, 用作定时器(对内部系统时钟进 行计数 )；

1, 用作计数 器(对引脚T2/P3.1的外部脉冲进行计数 )

T2x12: 定时器2速度控制位

0, 定时器2是传统8051速度，12分频；

1, 定时器2的速度是传统8051的12倍，不分频

如果 串口1或串口2用T2作为 波特率发生器，则由T2x12决定串口1或串口2是12T还是1T.

# 5.定时器3的控制位— TR3、T3_C/T、T3x12

T4T3M(不可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>T4T3M</td><td>D1H</td><td>name</td><td>T4R</td><td>T4_C/T</td><td>T4x12</td><td>T4CLKO</td><td>T3R</td><td>T3_C/T</td><td>T3x12</td><td>T3CLKO</td></tr></table>

B3 - T3R：定时器3运行控制位。

0, 不允许定时器3运行；

1, 允许定时器3运行。

B2 - T3_C/T: 控制定时器3用作定时器或计数 器。

0, 用作定时器(对内部系统时钟进 行计数 )；

1, 用作计数 器(对引脚T3/P0.7的外部脉冲进行计数 )

B1 - T3x12：定时器3速度控制位。

0,定时器3速度是8051单片机定时器的速度，即12分频；

1,定时器3速度是8051单片机定时器速度的12倍，即不分频。

# 6.与串行口3中断相关的寄存器IE2

串行口3中断允许位ES3位于中断允许寄存器IE2中，中断允许寄存器的格式如下 ：

IE2 : 中断允许寄存器2 (不可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IE2</td><td>AFH</td><td>name</td><td>-</td><td>ET4</td><td>ET3</td><td>ES4</td><td>ES3</td><td>ET2</td><td>ESPI</td><td>ES2</td></tr></table>

ET4：定时器4的中断允许位。

1，允许定时器4产生中断；

0，禁止定时器4产生中断。

ET3：定时器3的中断允许位。

1，允许定时器3产生中断；

0，禁止定时器3产生中断。

ES4 : 串行口4中断允许位。

1，允许串行口4中断；

0，禁止串行口4中断

ES3 : 串行口3中断允许位。

1，允许串行口3中断；

0，禁止串行口3中断。

ET2：定时器2的中断允许位。

1，允许定时器2产生中断；

0，禁止定时器2产生中断。

ESPI：SPI中断允许位。

1，允许SPI中断；

0，禁止SPI 中断。

ES2 : 串行口2中断允许位。

1，允许串行口2中断；

0，禁止串行口2中断。

IE : 中断允许寄存器 (可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IE</td><td>A8H</td><td>name</td><td>EA</td><td>ELVD</td><td>EADC</td><td>ES</td><td>ET1</td><td>EX1</td><td>ET0</td><td>EX0</td></tr></table>

EA : CPU的总中断允许控制位

1，CPU开放中断，

0，CPU屏蔽所有的中断申请。

EA的作用是使中断允许形成多级控制。即各中断源首先受EA控制;其次还受各中断源自己的中断允许控制位控制。

# 7.串行口3在2组管脚之间切换的控制位— S3_S/P_SW2.1

通过设置寄存器P_S W2中的S3_S位，可以将串口3在2组 管脚之间任意切换，P_S W2寄存器的格式如下 ：

P_SW2 : 外围设备切换控制寄存器2 (不可位寻址)

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>7</td><td>6</td><td>5</td><td>4</td><td>3</td><td>2</td><td>1</td><td>0</td><td>Reset Value</td></tr><tr><td>P_SW2</td><td>BAH</td><td>外围设备功能切换控制寄存器2</td><td></td><td></td><td></td><td></td><td></td><td>S4_S</td><td>S3_S</td><td>S2_S</td><td>xxxx,x000</td></tr></table>

<table><tr><td colspan="2">串口2/S2可在2个地方切换，由S2_S控制位来选择</td></tr><tr><td>S2_S</td><td>S2可在P1/P4之间来回切换</td></tr><tr><td>0</td><td>串口2/S2在[P1.0/RxD2, P1.1/TxD2]</td></tr><tr><td>1</td><td>串口2/S2在[P4.6/RxD2_2, P4.7/TxD2_2]</td></tr></table>

<table><tr><td colspan="2">串口3/S3可在2个地方切换，由S3_S控制位来选择</td></tr><tr><td>S3_S</td><td>S3可在P0/P5之间来回切换</td></tr><tr><td>0</td><td>串口3/S3在[P0.0/RxD3, P0.1/TxD3]</td></tr><tr><td>1</td><td>串口3/S3在[P5.0/RxD3_2, P5.1/TxD3_2]</td></tr></table>

<table><tr><td colspan="2">串口4/S4可在2个地方切换，由S4_S控制位来选择</td></tr><tr><td>S4_S</td><td>S4可在P0/P5之间来回切换</td></tr><tr><td>0</td><td>串口4/S4在[P0.2/RxD4, P0.3/TxD4]</td></tr><tr><td>1</td><td>串口4/S4在[P5.2/RxD4_2, P5.3/TxD4_2]</td></tr></table>

# 8.9 串行口3工作模式

STC15W4K60S4系列单片机的串行口3有两种工作 模式，可通过软件编程对S3CON中的S3SM0的设置进行选择。其中模式0和模式1都为异步通信，每个发送和接收的字符都带有1个启动位和1个停止位。

# 8.9.1 串行口3的工作模式0----8位UART，波特率可变

10 � RxD3/P0.0(RxD3/P5.0)接收，通过TxD3/P0.1(TxD3/P5.1)发送。一 帧数据包含一个 起始位(0),�8��个数 据位和��一个 停止位(1)�。 �� S3CON的S3RB8位。串行口3既可以选择定时器2作 其波特率发生器，也可以选择定时器3作其波特率发生器。所以串行口3的波特率由定时器T2的溢出率或定时器T3的溢出率决定。

当串行口3选择定时器T2作为 其波特率发生器(即S3ST3/S3SCON.1=0)时：

串口3在模式0的 $=$ 定时器 � �

当T2工作在 1T模式(AUXR.2/T2x12=1)时 定时器�2 =SYSclk / ( 65536 - [RL_TH2, RL_TL2] )；

即此时，串行口3的波特率=SYSclk / ( 65536 - [RL_TH2, RL_TL2]) / 4

当T2工作在 12T模式(AUXR.2/T2x12=0)时 定时器�2 =SYSclk /12/(65536 - [RL_TH2, RL_TL2])；

即此时，串行口3的波特率=SYSclk / 12 / ( 65536 - [RL_TH2, RL_TL2]) / 4

上式中RL_TH2是T2H的重装载寄存器，RL_TL2是T2L的重装载寄存器。

当串行口3选择定时器T3作为 其波特率发生器(即S3ST3/S3SCON.1=1)时：

串口3波特率在模式 $0 =$ 定时器 �

当T3工作在 1T模式(T4T3M.1/T3x12=1)时 定时器 =SYSclk / ( 65536 - [RL_TH3, RL_TL3] )；

即此时，串行口3的波特率=SYSclk / ( 65536 - [RL_TH3, RL_TL3]) / 4

当T3工作在 12T模式(T4T3M.1/T3x12=0)时 定时器 $\Leftarrow$ SYSclk /12/(65536 - [RL_TH3, RL_TL3])；

即此时，串行口3的波特率=SYSclk / 12 / ( 65536 - [RL_TH3, RL_TL3]) / 4

上式中RL_TH3是T3H的重装载寄存器，RL_TL3是T3L的重装载寄存器。

# 8.9.2 串行口3的工作模式1----9位UART，波特率可变

11位数据通过TxD3/P0.1(TxD3/P5.1)发送，通过RxD3/P0.0(RxD3/P5.0)接收。一 帧�含一个 起始位(0)，8个数 据位，一个 可编程的第9位，和一个 停止位(1)。发送时，第9位数据位来自特殊功能寄存器S3CON的S3TB8位.接收时，第9位进入 特殊功能寄存器S3CON的S3RB8位。串行口3既可以选择定时器2作 其波特率发生器，也可以选择定时器3作其波特率发生器。所以串行口3的波特率由定时器T2的溢出率或定时器T3的溢出率决定。

当串行口3选择定时器T2作为 其波特率发生器(即S3ST3/S3SCON. $1 { = } 0$ )时：

串口3在模式1的 $=$ 定时器 � �

当T2工作在 1T模式(AUXR.2/T2x12=1)时 定时器�2 =SYSclk / ( 65536 - [RL_TH2, RL_TL2] )；

即此时，串行口3的波特率=SYSclk / ( 65536 - [RL_TH2, RL_TL2]) / 4

当T2工作在 12T模式(AUXR.2/T2x12=0)时 定时器�2 =SYSclk /12/(65536 - [RL_TH2, RL_TL2])；

即此时，串行口3的波特率=SYSclk / 12 / ( 65536 - [RL_TH2, RL_TL2]) / 4

上式中RL_TH2是T2H的重装载寄存器，RL_TL2是T2L的重装载寄存器。

当串行口3选择定时器T3作为 其波特率发生器(即S3ST3/S3SCON. $\overline { { \overline { { \mathbf { \Lambda } } } } } = 1$ )时：

串口3波特率在模式 $1 =$ 定时器T3的溢出率/4

当T3工作在 1T模式(T4T3M.1/T3x12=1)时 定时器 =SYSclk / ( 65536 - [RL_TH3, RL_TL3] )；

即此时，串行口3的波特率=SYSclk / ( 65536 - [RL_TH3, RL_TL3]) / 4

当T3工作在 12T模式(T4T3M.1/T3x12=0)时 定时器 $\underline { { \mathbf { \Pi } } }$ SYSclk /12/(65536 - [RL_TH3, RL_TL3])；

即此时，串行口3的波特率=SYSclk / 12 / ( 65536 - [RL_TH3, RL_TL3]) / 4

上式中RL_TH3是T3H的重装载寄存器，RL_TL3是T3L的重装载寄存器。

可见，模式1和模式0一样，其波特率可通过软件对定时器2或定时器3的设置进行波特率的选择，是可变的。

# 用户在 程序中如何具体使用串口3

1.设置串口3的工作 模式，S3CON寄存器中的S3SM0决定了串口3的2种工作 模式

2.设置串口3的波特率相应的寄存器：

定时器 T3H / T3L

3.启动定时器 �T3R位为1，定时器 � ����

4. T4T3M.1/T3x12,确定定时器3的速度

5.打开串口3中断，设置

ES3, EA 

6.如要串口3接收，将S3REN置1 即可

如要串口3发送，将数据送入 S3BUF即可，

接收完成标志S3RI,发送完成标志S3TI,要由软件清0。

# 8.10 串行口4的相关寄存器

<table><tr><td>符号</td><td>描述</td><td>地址</td><td colspan="9">位地址及符号MSBLSB</td><td>复位值</td></tr><tr><td>S4CON</td><td>串口4控制寄存器</td><td>84H</td><td>S4SM0</td><td>S4ST4</td><td>S4SM2</td><td>S4REN</td><td>S4TB8</td><td>S4RB8</td><td>S4TI</td><td>S4RI</td><td></td><td>0000,0000</td></tr><tr><td>S4BUF</td><td>串口4数据缓冲器</td><td>85H</td><td colspan="9"></td><td>xxxx,xxxx</td></tr><tr><td>T2H</td><td>定时器2高8位,装入重装数</td><td>D6H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>T2L</td><td>定时器2低8位,装入重装数</td><td>D7H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>AUXR</td><td>辅助寄存器</td><td>8EH</td><td>T0x12</td><td>T1x12</td><td>UART_M0x6</td><td>T2R</td><td>T2_C/T</td><td>T2x12</td><td>EXTRAM</td><td>S1ST2</td><td></td><td>0000 0001B</td></tr><tr><td>T4H</td><td>定时器4高8位寄存器</td><td>D2H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>T4L</td><td>定时器4低8位寄存器</td><td>D3H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>T4T3M</td><td>T4和T3的控制寄存器</td><td>D1H</td><td>T4R</td><td>T4_C/T</td><td>T4x12</td><td>T4CLKO</td><td>T3R</td><td>T3_C/T</td><td>T3x12</td><td>T3CLKO</td><td></td><td>0000 0000B</td></tr><tr><td>IE2</td><td>中断允许寄存器</td><td>AFH</td><td></td><td>ET4</td><td>ET3</td><td>ES4</td><td>ES3</td><td>ET2</td><td>ESPI</td><td>ES2</td><td></td><td>x000 0000B</td></tr><tr><td>P_SW2</td><td>外围设备功能切换控制寄存器</td><td>BAH</td><td colspan="9">- | - | - | - | - | S4_S | S3_S | S2_S</td><td>xxxx x000B</td></tr></table>

# 1.串行口4的控制寄存器S4CON

串行口4控制寄存器S4CON用于确定串行口4的工作 方式和某些控制功能。其格式如下 ：

S4CON : 串行口4控制寄存器

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>S4CON</td><td>84H</td><td>name</td><td>S4SM0</td><td>S4ST4</td><td>S4SM2</td><td>S4REN</td><td>S4TB8</td><td>S4RB8</td><td>S4TI</td><td>S4RI</td></tr></table>

S4SM0：指定串行口4的工作 方式，如下 表所示。

<table><tr><td>S4SM0</td><td>工作方式</td><td>功能说明</td><td>波特率</td></tr><tr><td>0</td><td>方式0</td><td>8位UART, 波特率可变</td><td>(定时器T4的溢出率)/4</td></tr><tr><td>1</td><td>方式1</td><td>9位UART, 波特率可变</td><td>(定时器T4的溢出率)/4</td></tr><tr><td colspan="4">当T4T3M.5/T4x12=1时, 定时器T4的溢出率 = SYSclk / (65536 - [RL_TH4, RL_TL4]) 
当T4T3M.5/T4x12=0时, 定时器T4的溢出率 = SYSclk / 12 / (65536 - [RL_TH4, RL_TL4]) 
式中RL_TH4是T4H的重装载寄存器, RL_TL4是T4L的重装载寄存器。</td></tr></table>

S4ST4：串口4(UART4)选择定时器4作 波特率发生器的控制位。

0，串行口�4选择定时器���2 其

1，串行 �4选择定时器���其

S4SM2：允许方式1多机通信控制位。

方式1时，如果 S4SM2位为1且S4REN位为1，则接收机处于地址帧筛选状态。此 时可以利用接收到的第9位(即S4RB8)来筛选地址帧：若S4RB8=1，说明该帧是地址帧，地址信息可以进入S4 BUF，并使S4RI为 1，进而在中断服务程序中再进行地址号比较；若S4RB8=0，说明该帧不是地址帧，应丢掉且保持S4RI=0。在 方式1中，如果S4 SM2位为0且S4REN位为1，接收收机处于地址帧筛选被禁止状态。不论收到的S4RB8为0或1，均可使接收到的信息进入S4 BUF,并使S4RI=1,此 时S4RB8通常为校验位.方式0是非多机通信方式，在这种方式时，要设置S4SM2 应为0。

S4REN：允许/禁止串行口4接收控制位。由 软件置位S4REN，即S4REN=1为允许串行接收状态，可启动串行接收器RxD4，开始 接收信息。软件复位S4REN，即S4REN=0，则禁止接收。

S4TB8：在方式1，S4TB8为要发送的第9位数据，按需要由软件置位或清0。例如，可用作数 据的校验位或多机通信中表示地址帧/数据帧的标志位。在 方式0中，该位不用.

S4RB8：在方式1，S4RB8是接收到的第9位数据，作为 奇偶校验位或地址帧/数据帧的标志位。方式0中不用S4RB8(置S4SM2=0, S4RB8是接收到的停止位)。

S4TI：发送中断请求标志位。在 停止位开始 发送时由S4 TI内部硬件置位，即S4TI=1,响应中断后S4TI必须用软件清零。

S4RI：接收中断请求标志位。在 串行接收到停止位的中间时刻S4RI由 内部硬件置位，即S4RI=1,向CPU发中断申请，响应中断后S4RI必须由软件清零。

S4CON的所有位可通过整机复位信号复位为全 0”�。S4CON的字节地址为84H，不可位寻址。串行通信的中断请求：当一帧发送完成，内部硬件自动置位S4TI，即S4TI=1，请求中断处理；当接收完一帧信息时，内部硬件自动置位S4RI，即S4RI=1，请求中断处理。由 于S4TI和S4RI以“或逻辑”关系向�主机请求中断，所以�主机响应中断时事先并不��知道 是S4TI还是S4RI请求的中断，必须在中断服务程序中查询S4TI和S4RI进行判别，然后分别处理。因此，两个中断请求标志位均不能由硬件自动置位，必须通过软件清0，否则将出现一次请求多次响应的错误。

# 2.串行口4的数据缓冲寄存器S4BUF

STC15W4K60S4系列单片机的串行口4数 据缓冲寄存器(S4BUF)的地址是85H，实际是2个 缓冲器，写S4BUF的操作 完成待发送数 据的加载，读S4BUF的操作 可获得已接收到的数据。两个操作分别对应两个不同的寄存器，1个是只写寄存器，1个是只读寄存器。

串行通道内设有数据寄存器。在 所有的串行通信方式中，在写入S4BUF信号（MOVS4BUF,A）的控制下，把数据装入相同的9位移位寄存器，前面8位为数 据字节，其最低位为移位寄存器的输出位。根据不同的工作 方式会自动将 1” S4TB8的值装入移位寄存器的第9位,并进行发送.

串行通道的接收寄存器是一个 输入移位寄存器。在 方式0和方式1时均为9位。当一帧接收完毕，移位寄存器中的数据字节装入串行数据缓冲器S4BUF中,其第9位则装入S4CON寄存器中的S4RB8位。如果由 于S4SM2使得已接收到的数据无效时,S4RB8和S4BUF中内容不变.

由于接收通道内设有输入移位寄存器和S4BUF缓冲器，从而能使一帧接收完将数据由移位寄存器装入S4BUF后，可立即开始 接收下一 帧信息，主机应在该帧接收结束前从S4BUF缓冲器中将数据取走，否则前一帧数据将丢失。S4BUF以并行方式送往 内部数 据总线。

# 3. 串行口4既能选择定时器2作为其波特率发生器，也能选择定时器4作为其波特率发生器— 定时器2的寄存器T2H, T2L和定时器4的寄存器T3H, T3L

定时器2寄存器T2H(地址为D6H，复位值为00H)及寄存器T2L(地址为D7H，复位值为00H)用于保存重装时间常数。

定时器4寄存器T4H(地址为D2H，复位值为00H)及寄存器T3L(地址为D3H，复位值为00H)用于保存重装时间常数。

# 4.定时器2的控制位— TR2、T2_C/T、T2x12

AUXR : 辅助寄存器 (不可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>AUXR</td><td>8EH</td><td>name</td><td>T0x12</td><td>T1x12</td><td>UART_M0x6</td><td>T2R</td><td>T2_C/T</td><td>T2x12</td><td>EXTRAM</td><td>S1ST2</td></tr></table>

T2R: 定时器2允许控制位

0, 不允许定时器2运行；

1, 允许定时器2运行

T2_C/T: 控制定时器2用作定时器或计数 器。

0, 用作定时器(对内部系统时钟进 行计数 )；

1, 用作计数 器(对引脚T2/P3.1的外部脉冲进行计数 )

T2x12: 定时器2速度控制位

0, 定时器2是传统8051速度，12分频；

1, 定时器2的速度是传统8051的12倍，不分频

如果 串口1或串口2用T2作为 波特率发生器，则由T2x12决定串口1或串口2是12T还是1T.

# 5.定时器4的控制位— TR4、T4_C/T、T4x12

T4T3M(不可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>T4T3M</td><td>D1H</td><td>name</td><td>T4R</td><td>T4_C/T</td><td>T4x12</td><td>T4CLKO</td><td>T3R</td><td>T3_C/T</td><td>T3x12</td><td>T3CLKO</td></tr></table>

B7 - T4R：定时器4运行控制位。

0,不允许定时器4运行；

1, 允许定时器4运行。

B6 - T4_C/T: 控制定时器4用作定时器或计数 器。

0, 用作定时器(对内部系统时钟进 行计数 )；

1, 用作计数 器(对引脚T4/P0.5的外部脉冲进行计数 )

B5 - T4x12：定时器4速度控制位。

0,定时器4速度是8051单片机定时器的速度，即12分频；

1,定时器4速度是8051单片机定时器速度的12倍，即不分频。

# 6.与串行口4中断相关的寄存器IE2

串行口4中断允许位ES4位于中断允许寄存器IE2中，中断允许寄存器的格式如下 ：

IE2 : 中断允许寄存器2 (不可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IE2</td><td>AFH</td><td>name</td><td>-</td><td>ET4</td><td>ET3</td><td>ES4</td><td>ES3</td><td>ET2</td><td>ESPI</td><td>ES2</td></tr></table>

ET4：定时器4的中断允许位。

1，允许定时器4产生中断；

0，禁止定时器4产生中断。

ET3：定时器3的中断允许位。

1，允许定时器3产生中断；

0，禁止定时器3产生中断。

ES4 : 串行口4中断允许位。

1，允许串行口4中断；

0，禁止串行口4中断

ES3 : 串行口3中断允许位。

1，允许串行口3中断；

0，禁止串行口3中断。

ET2：定时器2的中断允许位。

1，允许定时器2产生中断；

0，禁止定时器2产生中断。

ESPI：SPI中断允许位。

1，允许SPI中断；

0，禁止SPI 中断。

ES2 : 串行口2中断允许位。

1，允许串行口2中断；

0，禁止串行口2中断。

IE : 中断允许寄存器 (可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IE</td><td>A8H</td><td>name</td><td>EA</td><td>ELVD</td><td>EADC</td><td>ES</td><td>ET1</td><td>EX1</td><td>ET0</td><td>EX0</td></tr></table>

EA : CPU的总中断允许控制位

EA=1，CPU开放中断，

EA=0，CPU屏蔽所有的中断申请。

EA的作用是使中断允许形成多级控制。即各中断源首先受EA控制;其次还受各中断源自己的中断允许控制位控制。

# 7.串行口4在2组管脚之间切换的控制位— S4_S/P_SW2.2

通过设置寄存器P_S W2中的S4_S 位，可以将串口4在2组 管脚之间任意切换，P_S W2寄存器的格式如下 ：

P_SW2 : 外围设备切换控制寄存器2 (不可位寻址)

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>7</td><td>6</td><td>5</td><td>4</td><td>3</td><td>2</td><td>1</td><td>0</td><td>Reset Value</td></tr><tr><td>P_SW2</td><td>BAH</td><td>外围设备功能切换控制寄存器2</td><td></td><td></td><td></td><td></td><td></td><td>S4_S</td><td>S3_S</td><td>S2_S</td><td>xxxx,x000</td></tr></table>

<table><tr><td colspan="2">串口2/S2可在2个地方切换，由S2_S控制位来选择</td></tr><tr><td>S2_S</td><td>S2可在P1/P4之间来回切换</td></tr><tr><td>0</td><td>串口2/S2在[P1.0/RxD2, P1.1/TxD2]</td></tr><tr><td>1</td><td>串口2/S2在[P4.6/RxD2_2, P4.7/TxD2_2]</td></tr></table>

<table><tr><td colspan="2">串口3/S3可在2个地方切换，由S3_S控制位来选择</td></tr><tr><td>S3_S</td><td>S3可在P0/P5之间来回切换</td></tr><tr><td>0</td><td>串口3/S3在[P0.0/RxD3, P0.1/TxD3]</td></tr><tr><td>1</td><td>串口3/S3在[P5.0/RxD3_2, P5.1/TxD3_2]</td></tr></table>

<table><tr><td colspan="2">串口4/S4可在2个地方切换，由S4_S控制位来选择</td></tr><tr><td>S4_S</td><td>S4可在P0/P5之间来回切换</td></tr><tr><td>0</td><td>串口4/S4在[P0.2/RxD4, P0.3/TxD4]</td></tr><tr><td>1</td><td>串口4/S4在[P5.2/RxD4_2, P5.3/TxD4_2]</td></tr></table>

# 8.11 串行口4工作模式

STC15W4K60S4系列单片机的串行口4有两种工作 模式，可通过软件编程对S4CON中的S4SM0的设置进行选择。其中模式0和模式1都为异步通信，每个发送和接收的字符都带有1个启动位和1个停止位。

# 8.11.1 串行口4的工作模式0----8位UART，波特率可变

10 � RxD4/P0.2(RxD4_2/P5.2)接收，通过TxD4/P0.3(TxD4_2/P5.3)发送。一 帧数据包含一个 起始位(0),�8��个数 据位和一个��停止位(1)�。 ��S4CON的S4RB8位。串行口4既可以选择定时器2作 其波特率发生器，也可以选择定时器4作 其波特率发生器。所以串行口4的波特率由定时器T2的溢出率或定时器T4的溢出率决定。

当串行口4选择定时器T2作为 其波特率发生器(即S4S T4/S4S CON. $1 { = } 0$ )时：

串口4在 模式0的 $=$ 定时器 � �

当T2工作在 1T模式(AUXR.2/T2x12=1)时 定时器�2 =SYSclk / ( 65536 - [RL_TH2, RL_TL2] )；

即此时，串行口4的波特率=SYSclk / ( 65536 - [RL_TH2, RL_TL2]) / 4

当T2工作在 12T模式(AUXR.2/T2x12=0)时 定时器�2 =SYSclk /12/(65536 - [RL_TH2, RL_TL2])；

即此时，串行口4的波特率 $\displaystyle . =$ SYSclk / 12 / ( 65536 - [RL_TH2, RL_TL2]) / 4

上式中RL_TH2是T2H的重装载寄存器，RL_TL2是T2L的重装载寄存器。

当串行口4选择定时器T4作为 其波特率发生器(即S4S T4/S4S CON.1=1)时：

串口4在 模式0的 $=$ 定时器 � �

当T4工作在 1T模式(T4T3M.5/T4x12=1)时 定时器�4 =SYSclk / ( 65536 - [RL_TH4, RL_TL4] )；

即此时，串行口4的波特率=SYSclk / ( 65536 - [RL_TH4, RL_TL4]) / 4

当T4工作在 12T模式(T4T3M.5/T4x12=0)时 定时器�4 =SYSclk /12/(65536 - [RL_TH4, RL_TL4])；

即此时，串行口4的波特率=SYSclk / 12 / ( 65536 - [RL_TH4, RL_TL4]) / 4

上式中RL_TH4是T4H的重装载寄存器，RL_TL4是T4L的重装载寄存器。

# 8.11.2 串行口4的工作模式1----9位UART，波特率可变

11位数据通过TxD4/P0.3(TxD4_2/P5.3)发送，通过RxD4/P0.2(RxD4_2/P5.2)接收。一 帧�据包含一个 起始位(0)，8个数 据位，一个 可编程的第9位，和一个 停止位(1)。发送时，第9位数据位来自特殊功能寄存器S4CON的S4TB8位.接收时，第9位进入 特殊功能寄存器S4CON的S4RB8位。串行口4既可以选择定时器2作 其波特率发生器，也可以选择定时器4作 其波特率发生器。所以串行口4的波特率由定时器T2的溢出率或定时器T4的溢出率决定。

当串行口4选择定时器T2作为 其波特率发生器(即S4S T4/S4S CON. $1 { = } 0$ )时：

串口4在 模式1的 $=$ 定时器 � �

当T2工作在 1T模式(AUXR.2/T2x12=1)时 定时器�2 =SYSclk / ( 65536 - [RL_TH2, RL_TL2] )；

即此时，串行口4的波特率=SYSclk / ( 65536 - [RL_TH2, RL_TL2]) / 4

当T2工作在 12T模式(AUXR.2/T2x12=0)时 定时器�2 =SYSclk /12/(65536 - [RL_TH2, RL_TL2])；

即此时，串行口4的波特率=SYSclk / 12 / ( 65536 - [RL_TH2, RL_TL2]) / 4

上式中RL_TH2是T2H的重装载寄存器，RL_TL2是T2L的重装载寄存器。

当串行口4选择定时器T4作为 其波特率发生器(即S4S T4/S4S CON.1=1)时：

串口4在 模式1的 $=$ 定时器T4的溢出率/4

当T4工作在 1T模式(T4T3M.5/T4x12=1)时 定时器�4 =SYSclk / ( 65536 - [RL_TH4, RL_TL4] )；

即此时，串行口4的波特率=SYSclk / ( 65536 - [RL_TH4, RL_TL4]) / 4

当T4工作在 12T模式(T4T3M.5/T4x12=0)时 定时器�4 =SYSclk /12/(65536 - [RL_TH4, RL_TL4])；

即此时，串行口4的波特率 $\displaystyle . =$ SYSclk / 12 / ( 65536 - [RL_TH4, RL_TL4]) / 4

上式中RL_TH4是T4H的重装载寄存器，RL_TL4是T4L的重装载寄存器。

可见，模式1和模式0一样，其波特率可通过软件对定时器2的设置进行波特率的选择，是可变的。

# 用户在 程序中如何具体使用串口4

1.设置串口4的工作 模式，S4CON寄存器中的S4SM0决定了串口4的2种工作 模式

2.设置串口4的波特率相应的寄存器：

定时器� T4H / T4L

3.启动定时器�4 �T4R位为1，定时器��4就 ����

4. T4T3M.5/T4x12,确定定时器4的速度

5.打开串口4中断，设置

ES4, EA 

6.如要串口4接收，将S4REN置1 即可

如要串口4发送，将数据送入 S4BUF即可，

接收完成标志S4RI,发送完成标志S4TI,要由软件清0。

# 8.12 双机通信

STC15系列单片机的串行通信根据其应用可分为双 机通信和多机通信两种。下 面先介绍双机通信。

如果 两个8051应用系统相距很近，可将它们的串行端口直接相连（TXD—RXD，RXD—TXD，GND—GND—地），即可实现�双机通信��。为 了增加通信距离，减少通�道及电源干扰，可采用RS—232C或RS—422、RS—485标准进行双机通信，两通信系统之间采用光—术，以减少通道及电源的干扰，提高通信可靠性。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/6654486752c1577aed29ebf578ce991dfe6e45fb6602006f00d0f02980595dba.jpg)


为确保通信成功，通信双方必须在软件上有系列的约定通常称为软件通信“协议”�例简介双机异步通信软件“协议”��

通信双方均选用2400波特的传输速率，设系统的主频SYSclk=6MHz,甲机发送数 据，乙机接收数据。在双 机开始 通信时，先由甲机发送一个 呼叫信号（例如“06H”否可以接收数据；乙机接收到呼叫信号后，若同意接收数据，则发回 00H”��作为 �否则发 05H”表示暂不能接收数�据，；�甲机只有在�接收到�乙机的应答�信号 00H”存储在外部数 据存储器中的内容逐一发送给 乙机，否则继续向乙机发呼叫信号，直到 乙机同意接收。其发送数 据格式如下 ：

<table><tr><td>字节数n</td><td>数据1</td><td>数据2</td><td>数据3</td><td>...</td><td>数据n</td><td>累加校验和</td></tr></table>

字节数n：甲机向乙机发送的数据个数；

数据1~数据n：甲机将向乙机发送的n帧数据；

累加校验和：为字节数n、数据1、… � n,这(n+1)个字节内容的算术累加和.

乙机根据接收到的“校验和” � n个数 据是否正确。若接收正确,向甲机回发“0FH”信号,否则回发“F0H”信号。甲机只有在接收到乙机发回的 0FH” �务，返回被调用的程序，否则继续呼叫，重发数据。

不同的通信要求，软件“协议”内容也不�一样，有关需甲、乙�双方共同��遵守 的约定应尽量完善，以防止通信不能正确判别而失败。

STC15系列单片机的串行通信，可直接采用查询法，也可采用自动中断法。

# （1）查询方式双机通信软件举例

# $\textcircled{1}$ 甲机发送子程序段

下图为甲机发送子程序流程图。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/37c6906b4c05e4266b10d46b82cb51715847d0a9e597090633a3adcf7c8cb47e.jpg)


甲机发送程序设置：

(a) 波特率设置：选用定时器/��计数 器1定时模式、��工作 方式�2，��计数 常��数F3�H，�SMOD=1�特率为��00（位/

(b) 串行通信设置：异步通信方式1

(c) �部RAM ��

31H�和30�H单元存放发�送的�数据块首地址；

���2FH 单元存放发�送的�数据块��个数；��

R6�为 �

甲机发送子程序清单：

START: 

```txt
MOV TMOD，#20H ；设置定时器/计数器1定时、工作方式2  
MOV TH1， #0F3H ；设置定时计数常数  
MOV TL1， #0F3H ；  
MOV SCON，#50H ；串口初始化  
MOV PCON，#80H ；设置SMOD=1  
SETB TR1 ；启动定时
```

ST-RAM: 

```txt
MOV DPH, 31H ; 设置外部RAM数据指针  
MOV DPL, 30H ; DPTR初值  
MOV R7, 2FH ; 发送数据块数送R7  
MOV R6, #00H ; 累加和寄存器R6清0
```

TX-ACK： 

```txt
MOV A, #06H ; MOV SBUF, A 发送呼叫信号“06H”
```

WAIT1： 

```txt
JBC T1, RX-YES ；等待发送完呼叫信号 SJMP WAIT1 ；未发送完转WATI1
```

RX-YES： 

```txt
JBC RI， NEXT1 ；判断乙机回答信号 SJMP RX-YES ；未收到回答信号，则等待
```

NEXT1： 

```txt
MOV A, SBUF ；接收回答信号送A  
CJNE A, #00H, TX-ACK; 判断是否“00H”，否则重发呼叫信号
```

TX-BYT： 

```txt
MOV A, R7 ; 发送数据块数n  
MOV SBUF, A ;  
ADD A, R6  
MOV R6, A
```

WAIT2： 

```txt
JBC TI, TX-NES ；JMP WAIT2 等待发送完
```

TX-NES： 

```txt
MOVX A, @DPTR ; 从外部RAM取发送数据  
MOV SBUF, A ; 发送数据块  
ADD A, R6  
MOV R6, A  
INC DPTR ; DPTR指针加1
```

WAIT3： 

JBC TI, 

NEXT2 

；判断一数 据块发送完否

SJMP WAIT3 

；等待发送完

NEXT2： 

DJNZ R7, 

TX-NES 

；判断发送全部结束否

TX-SUM： 

MOV A, 

R6 

；发送累加和给乙机

MOV SBUF， A 

WAIT4： 

JBC TI, 

RX-0FH 

； 等待发送完

RX-0FH： 

SJMP WAIT4 

JBC RI, IF-0FH 

； 等待接收乙机回答信号

IF-0FH： 

SJMP RX-0FH 

MOV A, 

SBUF； 

ST-RAM 

； 判断传输是否正确，否则重新发送

CJNE A, 

RET 

；返回

乙机接收子程序段

接收程序段的设置：

（a） 波特率设置初�始化：同发�送程�序；

（b） 串行通信初�始化：同发�送程�序；

（c） 寄存器设置：

内部RAM 31H、30H单元存放接收数据缓冲区首地址。

R7——数据块个数 寄存器。

R6——累加和寄存器。

（d） 向甲机回� 0FH”为接收正确，“F0H”为传送出错，“00H”为同意接收数据，“05H”为暂不接收。

下图为双 机通信查询方式乙机接收子程序流程图。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c312ea421d77137e7a734b9cf655b09a07eaa09627f58c378050ff24e51d4efd.jpg)


接收子程序清单：

TART： 

MOV TMOD，#20H 

MOV TH1， #0F3H 

MOV TL1， #0F3H 

SETB TR1 

MOV SCON， #50H 

MOV PCON， #80H 

ST-RAM： 

MOV DPH， 31H 

MOV DPL， 30H 

MOV R6， #00H 

定时器/计数 器1设置

；启动定时器/计数 器1

；置串行通信方式1，允许接收SMOD置位；

； 设置DPTR首地址；

；校验和寄存器清0

RX-ACK： 

JBC RI， IF-06H 

；判断接收呼叫信号

SJMP RX-ACK 

；等待接收呼叫信号

IF-06H： 

MOV A， SBUF 

；呼叫信号送A

CJNEA #06H， TX-05H 

；判断呼叫信号正确否？

TX-00H： 

MOV A， #00H 

；； 向甲机发送“00H”，同意接收

MOV SBUF， A 

WAIT1： 

JBC TI， RX-BYS 

；等待应答信号发送完

SJMP WAIT1 

TX-05H： 

MOV A， #05H 

；向甲机发送“05H”呼叫

MOV SBUF， A 

；不正确信号

WAIT2： 

JBC TI， HAVE1 

；等待发送完

SJMP WAIT2 

HAVE1： 

LJMP RX-ACK 

；因呼叫错，返回重新接收呼叫

RX-BYS： 

JBC RI， HAVE2 

；等待接收数据块个数

SJMP RX-BYS 

； 

HAVE2： 

MOV A， SBUF 

； 

MOV R7， A 

；数 据块个数 帧送R7,R6

MOV R6， A 

； 

RX-NES： 

JBC RI， HAVE3 

； 接收数据帧

SJMP RX-NES 

HAVE3： 

MOV A， SBUF 

； 

MOVX ＠DPTR，A 

；接收到的数据存入外部RAM

INC DPTR 

； 

ADD A， R6 

；； 形 成累加和

MOV R6， A 

；判断数据是否接收完

DJNZ R7， RX-NES 


RX-SUM：


JBC RI, HAVE4 ;等待接收校验和SJMP RX-SUM ;  
HAVE4: MOV A, SBUF ;判断传输是否正确CJNE A, R6, TX-ERR ;  
TX-RIT: MOV A, #0FH ;向甲机发送接收正确信息MOV SBUF, A ;  
WAIT3: JBC TI, GOOD ;等待发送结束SJMP WAIT3 ;  
TX-ERR: MOV A, #0F0H ;向甲机发送传输有误信号MOV SBUF, A  
WAIT4: JBC TI, AGAIN ;等待发送完SJMP WAIT4  
AGAIN: LJMP ST-RAM ;返回重新开始接收  
GOOD: RET ;传输正确返回

# （2）中断方式双机通信软件举例

在很多应用场合，双机通信的双方或一方采用中断方式以提高通信效率。由 于STC15系列单片机的串行通信是双工 的，且中断系统只提供一个 中断矢量入口地址，所以实际上是中断和查询必须相结合，即接收/发送均可各自请求中断，响应中断时主机并不知道 是谁请求中断，统一 转入同一个 中断矢量入口，必须由中断服务程序查询确定并转入对应的服务程序进 行处理。

这里，任以上述协议为例，甲方（发送方）任以查询方式通信（从略），乙方（接收方）则改用中断— � �

在中断接收服务程序中，需设置三个标志位来判断所接收的信息是呼叫信号还是数据块个数，是数据还是校验和。增设寄存器：内部RAM32H单元为数 据块个数 寄存器，33H单元为校验和寄存器，位地址7FH、7EH、7DH为标志位。

# 乙机接收中断服务程序清单

采用中断方式时，应在主 程序中安排定时器/计数 器、串行通信等初始化程序。 通信接收的数据存放在外部RAM的首地址也需在主 程序中确定。

主程序：

```txt
ORG 0000H  
AJMP START ;转至主程序起始处  
ORG 0023H  
LIMP SERVE ;转中断服务程序处
```

START： 

```txt
MOV TMOD，#20H ；定义定时器/计数器1定时、工作方式  
MOV TH1， #0F3H 设置波特率为2400位/秒  
MOV TL1， #0F3H 设置串行通信方式1，允许接收  
MOV SCON，#50H 设置SMOD=1  
MOV PCON，#80H 设置SMOD=1  
SETB TR1 启动定时器  
SETB 7FH  
SETB 7EH 设置标志位为1  
SETB 7DH  
MOV 31H，#10H 规定接收的数据存储于外部RAM的起始地址1000H  
MOV 30H，#00H  
MOV 33H，#00H 累加和单元清0  
SETB EA 开中断  
SETB ES
```

中断服务程序：

SERVE： 

CLR EA 

；关中断

CLR RI 

；清除接收中断请求标志

PUSH DPH 

； 

PUSH DPL 

；现场保护

PUSH A 

； 

JB 7FH， RXACK 

；判断是否是呼叫信号

JB 7EH， RXBYS 

；判断是否是数据块数据

JB 7DH， RXDATA 

；判断是否是接收数据帧

RXSUM： 

MOV A， SBUF 

；接收到的校验和

CJNE A， 33H， TXERR 

：判断传输是否正确

TXRI： 

MOV A， #0FH 

向甲机发送接收正确信号“0FH”

MOV SBUF， A 

WAIT1： 

JNB TI， WAIT1 

；等待发送完毕

CLR TI 

；清除发送中断请求标志位

SJMP AGAIN 

；转结束处理

TXERR： 

MOV A， #0F0H 

； 向甲机发送接收出错信号“F0H”

MOV SBUF， A 

WAIT2： 

JNB TI， WAIT2 

；等待发送完毕

CLR TI 

；清除发送中断请求标志

SJMP AGAIN 

；转结束处理

RXACK： 

MOV A， SBUF 

；判断是否是呼叫信号“06H”

XRL A， #06H 

；异或逻辑处理

JZ TXREE 

；是呼叫，则转TXREE

TXNACK： 

MOV A， #05H 

；接收到的不是呼叫信号，则向甲机发送

MOV SBUF， A 

； “05H”，要求重发呼叫

WAIT3： 

JNB TI， WAIT3 ；等待发送结束

CLR TI 

SJMP RETURN ；转恢复现场处理

TXREE： 

MOV A， #00H ；接收到的是呼叫信号，发送“00H”

MOV SBUF， A ；接收到的是呼叫信号，发送“00H”

WAIT4： 

JNB TI， WAIT4 ；等待发送完毕

CLR TI ；清除TI标志

CLR 7FH ；清除呼叫标志

SJMP RETURN ；转恢复现场处理

RXBYS： 

MOV A， SBUF ；接收到数 据块数

MOV 32H， A ；存入32H单元

ADD A， 33H ； 

MOV 33H， A ； 形成累加和

CLR 7EH ；清除数据块数标志

SJMP RETURN ；转恢复现场处理

RXDATA： 

MOV DPH， 31H ； 

MOV DPL， 30H ； 设置存储

MOV A， SBUF ；读取数据帧

MOVX ＠DPTR, A ；将数据存外部RAM

INC DPTR ；地址指针加1

MOV 31H， DPH ； 

MOV 30H， DPL 保存地址指针值

ADD A， 33H ； 

MOV 33H， A 

DJNZ 32H， RETURN ；判断数据接收完否

CLR 7DH ；清数据接收完标志

SJMP RETURN ；转恢复现场处理

AGAIN： 

<table><tr><td>SETB</td><td>7FH</td><td></td><td>;</td></tr><tr><td>SETB</td><td>7EH</td><td></td><td>; 恢复标志位</td></tr><tr><td>SETB</td><td>7DH</td><td></td><td>;</td></tr><tr><td>MOV</td><td>33H,</td><td>#00H</td><td>; 累加和单元清0</td></tr><tr><td>MOV</td><td>31H,</td><td>#10H</td><td>; }恢复接收数据缓冲区首地址</td></tr><tr><td>MOV</td><td>30H,</td><td>#00H</td><td>;</td></tr><tr><td>N:</td><td></td><td></td><td></td></tr><tr><td>POP</td><td>A</td><td></td><td>;</td></tr><tr><td>POP</td><td>DPL</td><td></td><td>; 恢复现场</td></tr><tr><td>POP</td><td>DPH</td><td></td><td>;</td></tr><tr><td>SETB</td><td>EA</td><td></td><td>; 开中断</td></tr><tr><td>RET1</td><td></td><td></td><td>; 返回</td></tr></table>

上述程序清单中，ORG为程序段说明伪指令，在程序汇编时，它向汇编程序说明该程序段的起始地址。

在实际应用中情况多种多样，而且是两台独立的计算机之间进行信息传输。因此，应周密考虑通信协议，以保证通信的正确性和成功率

# 8.13 多机通信

在很多实际应用系统中，需要多台微计算机协调工作。 STC15系列单片机的串行通信方式2和方式3具有多机通信功能，可构成各种分布式通信系统。下 图为全双工主 从式多机通信系统的连接框图。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a5c1dcde874a13f13305cfba69ec6f5f4c1fe92c146cd288cf20752ed853af96.jpg)


上图为一 台主机和几台从机组成的全双工 多机通信系统。主 机可与任一台从机通信，而从机之间的通信必须通过知己转发。

# （1）多机通信的基本原理

在多机通信系统中，为保证主机（发送）与多台从机（接收）之间能可靠通信，串行通信必须具备识别能力。MC�-51系列单片机的串行通信控制寄存器�CONSM2�。当程�序设置 $\mathrm { S M 2 ^ { = } 1 }$ ，串行通信��工作 于方式�2或方式8 �端通过对TB8送的是地址帧（ $\mathrm { T B } 8 { = } 1$ ）还是�数据帧（ $\mathrm { T B } 8 { = } 0$ ），接收端通过对接收�到RB8�进行识别：当 $\mathbf { S M 2 { = } 1 }$ ，若接收到RB8=1，则被确��认为 呼叫地址帧，将该帧内容装��入SBU�F中，并置位 �=1，向 �U断，进行地址呼叫处理；若RB8=0��为数 据帧，将不�予理�睬，接收的信息被丢��弃。 若 $\mathbf { S } \mathbf { M } 2 { = } 0$ ，则无论是地址帧还是数据帧均接收，并置位R�I=1，向C�PU请求中断，将该帧内容装��入SBU��F �理，可实现多机通信。

对于上图的从机式多机通信系统，从机的地址为0，1，�2，…，n�。 �下：

$\textcircled{1}$ 置全部�从机的 $\mathrm { S M 2 } { = } 1$ ，处于只接收地址帧状态。

$\textcircled{2}$ 主�机首先发送�呼叫地址帧信息，将TB8设置�为1 �的是

$\textcircled{3}$ 所有从机接收�到呼叫地址帧后，各�自将接收�到的�主机呼叫的地址�与本机的地址相比较：若比较结果相等，则为被寻址从机，清除 $\mathrm { S M } 2 { = } 0$ ，准备接收从�主机发�送的�数据帧，��直至 全部数 据传输完；若比较不相等，则为非寻址从机，任维持 $\mathrm { S M 2 } { = } 1$ 不变，对其后发来的数据帧不予理睬，即接收到的数据帧内容不装入�SBU�F，不置位， $\mathtt { R I } { = } 0$ ，不会产生中断请求，直至被寻址为止。

$\textcircled{4}$ 主�机在�发送�完呼叫地址帧后，接着发送一连 ���串的数�据帧，其中的

$\mathrm { T B } 8 { = } 0$ ��据帧。

$\textcircled{5}$ 当主机改变从机通信时间则再发呼叫地址帧，寻呼其他从机，原先被寻址的从机经分析得知主 机在寻呼其他从机时，恢复其 $\mathrm { S M 2 } { = } 1$ ，对其后�主机发�送的�数据帧不�予理�睬。

上述过程均在软件控制下实现。

# （2）多机通信协议简述

由于串行通信是在二台或多台各自完全独立的系统之间进行信息传输这就需要根据时间通信要求制定某些约定，作为 通信规范遵照执行，协议要求严格、完善，不同的通信要求，协议的内容也不相同。在 多机通信系统中要考虑的问题较多，协议内容比较复杂。这里仅例举几条作一 说明。

上图的主从式多机通信系统，允许配置�255 �00H~FEH。

$\textcircled{1}$ 约定地址����FFH����为全�部从机的控制命令，命令各从机恢复�SM�2=1 �址呼叫。

$\textcircled{2}$ 主�机和从机的联络��过程约定：主�机首先发送�地址呼叫帧，被寻址的从机回送�本机地址机，经验证地址相符后主机再向被寻址的从机发送命令字，被寻址的从机根据命令字要求回送本机的状态，若主机判断状态正常，主机即开始 发送或接收数据帧，发或接收的第一帧为传输数据块长度。

$\textcircled{3}$ 约定主�机发送�的命令字为�：

00H：要求从机接收�

01H：要求从机发��

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a59f840747ab8e72b67a9043ef8a3f0063918c274ddf7575991fcdd2a7de75bf.jpg)


其他：非法命令。

$\textcircled{4}$ 从机的状态字格式约定�

<table><tr><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>ERR</td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td><td>TRDY</td><td>RRDY</td></tr></table>

定义： 若ER $: = 1$ ，从机接收到非法命令；

若 $\mathrm { T R D Y = 1 }$ � ��

若 $\mathbf { R R D Y = 1 }$ ，从机接收准备就绪；

$\textcircled{5}$ 其他：如传输出错措施等。

# （3） �

在实际应用中如传输波特率不太高，系统实时性有一定要求以及希望提高通信效率，则多半采用中断控制方式，但程序调试较困难，这就要求提高程序编制的正确性。采用查询方式，则程序调试较方便。这里仅以中断控制方式为例简单介绍主—从机之间�一对�一通信软件。

# $\textcircled{1}$ � � �

该主机要发送的数据存放在内部RAM中，�数据块的首地址�为51�H，�据块长度存放做 �H元中，有关发送前的初始化、参数设置等采用子程序格式，所有信息发送均由中断服务程序完成。当主机需要发送时，在完成发送子程序的调用之后，随即返回主程序继续执行。以后只需查询��PSW·5的�F0标志位的状态即可���知道数 据是否发�送完毕�。

要求主机向#5从机发��送数 据，中断服务程�序选用��工作 寄存存器区1的R0~R7。

主机发送程序清单：

```txt
ORG 0000H  
AJMP MAIN ;转主程序  
ORG 0023H ;发送中断服务程序入口  
LJMP SERVE ;转中断服务程序
```

MAIN： ；主 程序

```txt
ORG 1000H ；发送子程序入口
```

TXCALL： 

MOV TMOD，#20H ；设置定时器/计数 器1定时、方式2

MOV TH1， #0F3H ；设置波特率为2400位/秒

MOV TL1， #0F3H ；置位SMOD

MOV PCON， #80H 

SETB TR1 ；启动定时器/计数 器1

MOV SCON， #0D8H ；串行方式8，允许接收，TB8=1

SETB EA ；开 中断总控制位

CLR ES ；禁止串行通信中断

TXADDR： 

MOV SBUF， #05H ；发送呼叫从机地址

WAIT1： 

JNB TI， WAIT1 ；等待发送完毕

CLR TI ；复位发送中断请求标志

# RXADDR：

JNB RI， RXADDR 

；等待从机回答本机地址

CLR TI 

；复位接收中断请求标志

MOV A， SBUF 

；读取从机回答的本机地址

CJNE A， #05H， TXADDR 

；判断呼叫地址符否，否则重发

CLR TB8 

；地址相符，复位TB8=0，准备发数据

CLR PSW.5 

；复位F0=0标志位

MOV 08H， #50H 

；发送数 据地址指针送R0

MOV 0CH， 50H 

；数 据块长度送R4

INC 0CH 

；数 据块长度加1

SETB ES 

；允许串行通信中断

RET 

；返回主程序

# SERVE：

CLR TI 

；中断服务程序段，清中断请求标志TI

PUSH PSW 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/9d6465984cb1545d85205bc2e198f8b79295e3c9e7021bff2dd9709f9c5a6c23.jpg)


PUSH A 

CLR RS1 

SETB RS0 

# TXDATA：

MOV SBUF， ＠R0 

；发送数 据块长度及数据

# WAIT2：

JNB TI， WAIT2 

；等待发送完毕

CLR TI 

；复位TI=0

INC R0 

；地址指针加1

DJNZ R4， RETURN 

；数 据块未发送完，转返回

SETB PSW.5 

；已发送完毕置位F0=1

CLR ES 

；关闭串行中断

# RETURN：

POP A 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/6097ed1463cee97b0425701f2323941398d43e4b4f50c0e9f827dad6769895a2.jpg)


POP PSW 

；返回

RETI 

# $\textcircled{2}$ 从机接收程序

主机发送的地址呼叫帧，所有的从机均接收，若不是呼叫本机地址即从中断返回；若是本机地址，则回送本机地址给主 机作为 应答，并开始 接收主机发送来的数据块长度帧，并存放于内部RAM的60H单元中，紧接着接收的数据帧存放于61H为首地址的内部RAM单元中，程序中还选用20·0H、20·1H位作标志位，用来判断接收的是地址、数据块长度还是数据，选用了2FH、2EH两个字节单元用于存放数据字节数和存储数据指针。#5从机的接收程序如下 ，供参考。


#5从机接收程序清单：


```txt
ORG 0000H  
AJMP START ; 转主程序段  
ORG 0023H  
LJMP SERVE ; 从中断入口转中断服务程序  
ORG 0100H
```


START：


MOV TMOD，#20H ；主程序段：初始化程序，设置定时  
MOV TH1， #OF3H ；器/计数器1定时、工作方式2，设  
MOV TL1， #OF3H ；置波特率为2400位/秒的有关初值  
MOV PCON，#80H ；置位SMOD  
MOV SCON，#0F0H ；设置串行方式3，允许接收， $\mathrm{SM}2 = 1$ SETB TR1 ；启动定时器/计数器1  
SETB $20\cdot 0$ ； 置标志位为1  
SETB $20\cdot 1$ ：  
SETB EA ；开中断  
SETB ES


SERVE：


CLR RI ；清接收中断请求标志 $\mathrm{RI} = 0$ PUSH A 现场保护PUSH PSW CLR RS1 选择工作寄存器组1SETB RS0 JB $20\cdot 0\mathrm{H}$ ，ISADDR 判断是否是地址帧JB $20\cdot 1\mathrm{H}$ ，ISBYTE 判断是否是数据块长度帧

# ISDATA：

MOV R0， 2EH ；数 据指针送R0

MOV A， SBUF ；接收数据

MOV ＠R0， A 

INC 2EH ；数 据指针加1

DJNZ 2FH， RETURN ；判断数据接收完否？

SETB 20·0H 

SETB 20·1H ；恢复标志位

SETB SM2 

SJMP RETURN ；转入恢复现场，返回

# ISADDR：

MOV A， SBUF ； 是地址呼叫，判断与本机地址

CJNE A， #05H， RETURN 相符否，不符则转返回

MOV SBUF， #01H ；相符，发回答信号“01H”

# WAIT：

JNB TI， WAIT ；等待发送结束

CLR TI ；清0TI， $2 0 \cdot 0$ ，SM2

CLR 20·0H ；清0TI， $2 0 \cdot 0$ ，SM2

CLR SM2 ；清0TI， $2 0 \cdot 0$ ，SM2

SJMP RETURN ；转返回

# ISBYTES：

MOV A， SBUF ；接收数据块长度帧

MOV R0， #60H ； 

MOV $@ { \bf R } 0$ ， A ；将数据块长度存入内部RAM

MOV 2FH， A ；60H单元及2FH单元

MOV 2EH， #61H ；置首地址61H于2EH单元

CLR 20·1H ；清 $2 0 \cdot 1 \mathrm { H }$ 标志，表示以后接收的为数 据

# RETURN：

POP PSW ； 恢复现场POP A

RETI ；返回

多机通信方式可多种多样，上例仅以最简单的住一从式作了简单介绍，仅供参考。

对于串行通信工作 方式0的同步方式，常用于通过移位寄存器进行扩展并行I/O口，或配置某些串行通信接口的外部设备。例如，串行打印机、显示器等。这里就不一一 举例了。

# 8.14 串口1作为增强型串口使用时的自动地址识别功能

# 8.14.1 与串口1自动地址识别功能相关的特殊功能寄存器

<table><tr><td rowspan="2">符号</td><td rowspan="2">描述</td><td rowspan="2">地址</td><td colspan="9">位地址及符号</td><td rowspan="2">复位值</td></tr><tr><td colspan="6">MSB</td><td colspan="3">LSB</td></tr><tr><td>SCON</td><td>串口控制寄存器</td><td>98H</td><td>SM0/FE</td><td>SM1</td><td>SM2</td><td>REN</td><td>TB8</td><td>RB8</td><td>TI</td><td>RI</td><td>0000 0000B</td><td></td></tr><tr><td>SBUF</td><td>串口发送/接收数据缓冲器</td><td>99H</td><td colspan="8"></td><td>xxxx xxxxxB</td><td></td></tr><tr><td>SADEN</td><td>从机地址屏蔽位寄存器</td><td>B9H</td><td colspan="8"></td><td>0000 0000B</td><td></td></tr><tr><td>SADDR</td><td>从机地址寄存器</td><td>A9H</td><td colspan="8"></td><td>0000 0000B</td><td></td></tr></table>

# 1.串行口1的控制寄存器SCON

串行控制寄存器SCON用于选择串行通信的工作 方式和某些控制功能。其格式如下 ：

SCON : 串行控制寄存器 (可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>SCON</td><td>98H</td><td>name</td><td>SM0/FE</td><td>SM1</td><td>SM2</td><td>REN</td><td>TB8</td><td>RB8</td><td>TI</td><td>RI</td></tr></table>

SM0/FE：当PCON寄存器中的SMOD0/PCON.6位为1时，该位用于帧错误检测。当检测到一个无效停止位时，通过UART接收器设置该位。它必须由软件清零。

当PCON寄存器中的SMOD0/PCON.6位为0时，该位和SM1一起指定串行通信的工作方式，如下 表所示。

其中SM0、SM1按下列组合确定串行口1的工作 方式：

<table><tr><td>SM0</td><td>SM1</td><td>工作方式</td><td>功能说明</td><td>波特率</td></tr><tr><td>0</td><td>0</td><td>方式0</td><td>同步移位串行方式:移位寄存器</td><td>当UART_M0x6=0时,波特率是SYSclk/12,当UART_M0x6=1时,波特率是SYSclk/2</td></tr><tr><td>0</td><td>1</td><td>方式1</td><td>8位UART,波特率可变</td><td>串行口1用定时器1作为其波特率发生器且定时器1工作于模式0(16位自动重装载模式)或串行口用定时器2作为其波特率发生器时,波特率=(定时器1的溢出率或定时器T2的溢出率)/4.注意:此时波特率与SMOD无关。当串行口1用定时器1作为其波特率发生器且定时器1工作于模式2(8位自动重装模式)时,波特率=(2SMOD/32)×(定时器1的溢出率)</td></tr><tr><td>1</td><td>0</td><td>方式2</td><td>9位UART</td><td>(2SMOD/64)x SYSclk系统工作时钟频率</td></tr><tr><td>1</td><td>1</td><td>方式3</td><td>9位UART,波特率可变</td><td>当串行口1用定时器1作为其波特率发生器且定时器1工作于模式0(16位自动重装载模式)或串行口用定时器2作为其波特率发生器时,波特率=(定时器1的溢出率或定时器T2的溢出率)/4.注意:此时波特率与SMOD无关。当串行口1用定时器1作为其波特率发生器且定时器1工作干模式2(8位自动重装模式)时,波特率=(2SMOD/32)×(定时器1的溢出率)</td></tr></table>

SM2：允许方式2或方式3多机通信控制位。

方式2或方式3时，如果 SM2位为1且REN位为1，则接收机处于地址帧筛选状态。此 时可以利用接收到的第9位(即RB8)来筛选地址帧：若RB8=1，说明该帧是地址帧，地址信息可以进入S BUF，并使RI为 1，进而在中断服务程序中再进行地址号比较；若 $\mathrm { R B 8 = 0 }$ ，说明该帧不是地址帧，应丢掉且保持R $= 0$ 。在 方式2或方式3中，如果 SM2位为0且REN位为1，接收收机处于地址帧筛选被禁止状态。不论收到的RB8为0或1，均可使接收到的信息进入S BUF,并使R $= 1$ ,此 时RB8通常为校验位.

方式1和方式0是非多机通信方式，在这两种方式时，要设置SM2 应为0。

REN：允许/禁止串行接收控制位。由 软件置位REN，即REN=1为允许串行接收状态，可启动串行接收器RxD，开始 接收信息。软件复位REN，即REN=0，则禁止接收。

TB8： 在方式2或方式3，它为要发送的第9位数据，按需要由软件置位或清0。例如，可用作数据的校验位或多机通信中表示地址帧/数据帧的标志位。在 方式0和方式1中，该位不用.

RB8： 在方式2或方式3，是接收到的第9位数据，作为 奇偶校验位或地址帧/数据帧的标志位。方式0中不用RB8(置SM2=0). 方式1中也不用RB8(置SM2=0, RB8是接收到的停止位)。

TI： 发送中断请求标志位。在 方式0，当串行发送数 据第8位结束时，由内部硬件自动置位，即 $\mathrm { T I } { = } 1$ ，向主机请求中断，响应中断后TI必须用软件清零，即 $\mathrm { T I } { = } 0$ 。在 其他方式中，则在停止位开始 发送时由内部硬件置位，即TI=1,响应中断后TI必须用软件清零。

RI： 接收中断请求标志位。在 方式0，当串行接收到第8位结束时由内部硬件自动置位RI=1，向主机请求中断，响应中断后RI必须用软件清零，即RI=0。在 其他方式中，串行接收到停止位的中间时刻由内部硬件置位，即RI=1,向CPU发中断申请，响应中断后RI必须由软件清零。

SCON的所有位可通过整机复位信号复位为全 0”�。SCON的字节地址为98H，可位寻址，各位地址为98H~~9FH，可用软件实现位设置。

串行通信的中断请求：当一帧发送完成，内部硬件自动置位TI，即 $\mathrm { T I } { = } 1$ ，请求中断处理；当接收完一帧信息时，内部硬件自动置位RI，即 $\mathrm { R I } { = } 1$ ，请求中断处理。由 于TI和RI以“辑”关系向主�机请求中断，所以主�机响应中断时事先并不知道��是TI还是RI请求的中断，必须在中断服务程序中查询TI和RI进行判别，然后分别处理。因此，两个中断请求标志位均不能由硬件自动置位，必须通过软件清0，否则将出现一次请求多次响应的错误。

# 2.串行口数据缓冲寄存器SBUF

STC15系列单片机的串行口1缓冲寄存器(SBUF)的地址是99H，实际是2个 缓冲器，写SBUF的操作 完成待发送数 据的加载，读SBUF的操作 可获得已接收到的数据。两个操作 分别对应两个不同的寄存器，1个是只写寄存器，1个是只读寄存器。

串行通道内设有数据寄存器。在 所有的串行通信方式中，在写入SBUF信号(MOV SBUF,A)的控制下，把数据装入相同的9位移位寄存器，前面8位为数 据字节，其最低位为移位寄存器的输出位。根据不同的工作 方式会自动将 1” TB8的值装入移位寄存器的第9位,并进行发送.

串行通道的接收寄存器是一个 输入移位寄存器。在 方式0时它的字长为8位，其他方式时为9位。当一帧接收完毕，移位寄存器中的数据字节装入串行数据缓冲器SBUF中,其第9位则装入SCON寄存器中的RB8位。如果由 于SM2使得已接收到的数据无效时,RB8和SBUF中内容不变.

由于接收通道内设有输入移位寄存器和SBUF缓冲器，从而能使一帧接收完将数据由移位寄存器装入SBUF后，可立即开始 接收下一 帧信息，主机应在该帧接收结束前从SBUF缓冲器中将数据取走，否则前一帧数据将丢失。SBUF以并行方式送往 内部数 据总线。

# 3. 从机地址控制寄存器SADEN和SADDR

为了方便多机通信，STC15系列单片机设置了从机地址控制寄存器SADEN和SADDR。其中SADEN是从机地址掩模寄存器(地址为B9H，复位值为00H)，SADDR是从机地址寄存器(地址为A9H，复位值为00H)。

# 8.14.2 串口1自动地址识别功能的介绍

自动地址识别功能典型应用在多机通讯领域，其主要原理是从机系统通过硬件比较功能来识别来自于主机串口数据流中的地址信息，通过寄存器SADDR和SADEN设置的本机的从机地址，硬件自动对从机地址进行过滤，当来自于主机的从机地址信息与本机所设置的从机地址相匹配时，硬件产生串口中断；否则硬件自动丢弃串口数据，而不产生中断。当众多处于空闲模式的从机链接在一 起时，只有从机地址相匹配的从机才会从空闲模式唤醒，从而可以大大降低从机MCU的功耗，即使从机处于正常工作 状态也可避免不停地进入 串口中断而降低系统执行效率。

要使用串口的自动地址识别功能，首先需要将参与通讯的MCU的串口通讯模式设置为模式或者模式3（通常都选择波特率可变的模式3，因为模式2的波特率是固定的，不便于调节），并开启从机的SCON的SM2位。对于串口模式2或者模式3的9位数据位中，第9位数据（存放在RB8中）为地址/数据的标志位，当第9位数据为1时，表示前面的8位数据（存放在S BUF中）为地址信息。当 $\mathrm { S M 2 = 1 }$ 时，从机MCU会自动过滤掉非地址数据（第9位为0的数据），而对SBUF中的地址数据（第9位为1的数据）自动与S ADDR和SADEN所设置的本机地址进行比较，若地址相匹配，则会将RI置“1”，并产生中断，否则不予处理本次接收的串口数据。

从机地址的设置是通过SADDR和SADEN两个寄存器进行设置的。S ADDR为从机地址寄存器，里面存放本机的从机地址。S ADEN为从机地址屏蔽位寄存器，用于设置地址信息中的“don’tcare bit”（忽略位），设置方法如下 ：

例如

$$
\mathrm {S A D D R} = 1 1 0 0 1 0 1 0
$$

$$
\mathrm {S A D E N} = 1 0 0 0 0 0 0 1
$$

则匹配地址为 1xxxxxx0

即，只要主机送出的地址数据中的bit0为0且bit7为 1就可以和本机地址相匹配

再例如

$$
\mathrm {S A D D R} = 1 1 0 0 1 0 1 0
$$

$$
\mathrm {S A D E N} = 0 0 0 0 1 1 1 1
$$

则匹配地址为 xxxx1010

即，只要主机送出的地址数据中的低4位为1010就可以和本机地址相匹配，而高4为 被忽略，可以为任意值。

主机可以使用广播地址（FFH ）同时选中所有的从机来进行通讯。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/8cca3da3e8e77d1c91b527b8f0aad481b2f6d3fd60fc99c46d6ef7ac20b31c78.jpg)


示例代码的测试方法:

1、	�����首先将两个 MCU按照上图的链接方法与电脑相连接

2、	�将 �SLAVE定义为0(“#define SLAVER ” )，编译产生的HEX文件烧录到SLAVER-1的MCU中;然后将SLAVE定义为1（“#define SLAVER 1”），编译产生的HEX文件烧录到SLAVER-2的MCU中

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/91daddafc44a048fa7a485b4c40034481b615c440710747c614a84655bf64e6e.jpg)


注意校验位

3、	��������������� 在PC端,打开串口助手,将串口 ��

4、	��������在串口助手终端, 发�����������送0x55,则会选中从 机1����,此时从 机1��应答 的��数据 为��8个0x78 $0 \mathrm { x } 7 8$ 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/4aea7f2e1655ea2393e98d9ad5b5e350b973a8e1ea491bb5cf5989bf8d2a98d4.jpg)


5、	�������串口助手终端再 发�����������送0x5a,则会选中从 机2����,此时从 机2��应答 的��数据 为����8个0x 4�9，�如图

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/3b6d7e78d17da98bdf77309bfd1936ecf254b87f3780776196f9e4cef634fc6b.jpg)


# 8.14.3 串口1自动地址识别功能的测试程序(C和汇编)

1. C程序：

/* -*/ 

/* --- STC MCU Limited */ 

/* --- STC15F2K60S2 系列 串口 1地址自动识别举例举例- */

/* --- 研发顾问QQ：800003751--- -*/

/* --- Fax: 86-755-82905966 - -*/ 

/* --- Tel: 86-755-82948412 */ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序 */

/* 如果要在文章中应 用此代码,请在文章中注明使用了STC的资料及程序 */

/*---- 在 Keil C C 开发环境中选 择 Intel 8052编译，头文件包含<reg51.h>即可 */

/* -*/ 

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

/ 

#define SLAVER 0 //定义从机编号,0为从机1, 1为从机2

#if SLAVER == 0 

#define SAMASK 0x33 //从机1地址屏蔽位

<table><tr><td colspan="4">STC15F2K60S2系列单片机指南 官方网站:www.STCMCU.com 研发顾问QQ:800003751 STC-全球最大的8051单片机设计公司</td></tr><tr><td>#	define</td><td>SERADR</td><td>0x55</td><td>//从机1的地址为xx01,xx01</td></tr><tr><td>#	define</td><td>ACKTST</td><td>0x78</td><td>//从机1应答测试数据</td></tr><tr><td>#else</td><td></td><td></td><td></td></tr><tr><td>#	define</td><td>SAMASK</td><td>0x3C</td><td>//从机2地址屏蔽位</td></tr><tr><td>#	define</td><td>SERADR</td><td>0x5A</td><td>//从机2的地址为xx01,10xx</td></tr><tr><td>#	define</td><td>ACKTST</td><td>0x49</td><td>//从机2应答测试数据</td></tr><tr><td>#endif</td><td></td><td></td><td></td></tr><tr><td>#define</td><td>URMD 0</td><td></td><td>//0:使用定时器2作为波特率发生器
//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器
//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器</td></tr><tr><td>sfr</td><td>T2H =</td><td>0xd6;</td><td>//定时器2高8位</td></tr><tr><td>sfr</td><td>T2L =</td><td>0xd7;</td><td>//定时器2低8位</td></tr><tr><td>sfr</td><td>AUXR =</td><td>0x8e;</td><td>//辅助寄存器</td></tr><tr><td>sfr</td><td>SADDR =</td><td>0xA9;</td><td>//从机地址寄存器</td></tr><tr><td>sfr</td><td>SADEN =</td><td>0xB9;</td><td>//从机地址屏蔽寄存器</td></tr><tr><td>void InitUart();</td><td></td><td></td><td></td></tr><tr><td>char count;</td><td></td><td></td><td></td></tr><tr><td>void main()</td><td></td><td></td><td></td></tr><tr><td rowspan="4">{</td><td>InitUart();</td><td rowspan="4" colspan="2">//初始化串口</td></tr><tr><td>ES = 1;</td></tr><tr><td>EA = 1;</td></tr><tr><td>while (1);</td></tr><tr><td>}</td><td></td><td></td><td></td></tr><tr><td colspan="4">{/*}- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - }</td></tr><tr><td>void Uart() interrupt 4 using 1</td><td></td><td></td><td></td></tr><tr><td rowspan="9">{</td><td>if (TI)</td><td></td><td></td></tr><tr><td rowspan="4">{</td><td>TI = 0;</td><td>//清除TI位</td></tr><tr><td>if (count != 0)</td><td></td></tr><tr><td>{</td><td>count--;</td></tr><tr><td>SBUF = ACKTST;</td><td>//继续发送应答数据</td></tr><tr><td>else</td><td></td><td></td></tr><tr><td>{</td><td></td><td></td></tr><tr><td>SM2 = 1;</td><td colspan="2">//若发送完成,则重新开始地址检测</td></tr><tr><td>}</td><td></td><td></td></tr><tr><td>}</td><td></td><td></td><td></td></tr></table>

```c
if (RI)  
{ RI = 0; //清除RI位 SM2 = 0; //本机被选中后,进入数据接收状态 count = 7; SBUF = ACKTST; //并开发送应答数据 }  
}  
/*  
初始化串口 */  
void InitUart()  
{ SADDR = SERADR; SADEN = SAMASK; SCON = 0xf8; //设置串口为9位可变波特率,使能多机通讯检测, //将TB8设置为1,方便与PC直接通讯测试) #if URMD == 0 T2L = 0xd8; //设置波特率重装值 T2H = 0xff; //115200 bps(65536-18432000/4/115200) AUXR = 0x14; //T2为1T模式,并启动定时器2 AUXR |= 0x01; //选择定时器2为串口1的波特率发生器 #elif URMD == 1 AUXR = 0x40; //定时器1为1T模式 TMOD = 0x00; //定时器1为模式0(16位自动重载) TL1 = 0xd8; //设置波特率重装值 TH1 = 0xff; //115200 bps(65536-18432000/4/115200) TR1 = 1; //定时器1开始启动 #else TMOD = 0x20; //设置定时器1为8位自动重装载模式 AUXR = 0x40; //定时器1为1T模式 TH1 = TL1 = 0xfb; //115200 bps(256 - 18432000/32/115200) TR1 = 1;
```

# 2. 汇编程序：

/*- -*/ 

/* --- STC MCU Limited - -*/ 

/* --- STC15F2K60S2 系列 串口1地址自动识别举例举例-- */

/* --- 研发顾问QQ：800003751- -*/

/* --- Fax: 86-755-82905966 - -*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序 */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可 */

/* -*/ 

# //假定测试芯片的工作频率为18.432MHz

#define SLAVER 0 //定义从机编号,0为从机1, 1为从机2

#if SLAVER == 0 

#define SAMASK 0x33 //从机1地址屏蔽位

#define SERADR 0x55 //从机1的地址为xx01,xx01

#define ACKTST 0x78 //从机1应答测试数据

#else 

#define SAMASK 0x3C //从机2地址屏蔽位

#define SERADR 0x5A //从机2的地址为xx01,10xx

#define ACKTST 0x49 //从机2应答测试数据

#endif 

#define URMD 0 //0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

//定时器2高8位 //定时器2高8位

T2H DATA 0D6H 

T2L DATA 0D7H //定时器2低8位

AUXR DATA 08EH //辅助寄存器

SADDR DATA 0A9H //从机地址寄存器

SADEN DATA 0B9H //从机地址屏蔽寄存器

COUNT DATA 20H 

// 

ORG 0000H 

LJMP MAIN 

ORG 0023H 

LJMP UART_ISR 

//- 

ORG 0100H 

MAIN: 

MOV SP, #3FH 

LCALL INIT_UART //初始化串口

SETB ES 

SETB EA 

SJMP $ 

//串口中断服务程序

UART_ISR: 

PUSH PSW 

PUSH ACC 

JNB TI, CHK_RX 

CLR TI 

MOV A, COUNT //发送完成8个数据后,就不再发送

JZ RESTART 

DEC COUNT 

MOV SBUF, #ACKTST //发送应答测试数据

JMP UREXIT 

RESTART: 

SETB SM2 //若发送完成,则重新开始地址检测

JMP UREXIT 

CHK_RX: 

JNB RI, UREXIT 

CLR RI 

CLR SM2 //本机被选中后,进入数据接收状态

MOV SBUF, #ACKTST //并开发送应答数据

MOV COUNT, #7 

UREXIT: 

POP ACC 

POP PSW 

RETI 

/* 

初始化串口

-*/ 

INIT_UART: 

MOV SADDR, #SERADR 

MOV SADEN, #SAMASK 

MOV SCON, #0F8H 

//设置串口为9位可变波特率,使能多机通讯检测,//(将TB8设置为1,方便与PC直接通讯测试)

#if URMD 一 0

MOV T2L, #0D8H 

MOV T2H, #0FFH 

MOV AUXR, #14H 

ORL AUXR, #01H 

#elif URMD 

MOV AUXR, #40H 

MOV TMOD, #00H 

MOV TL1, #0D8H 

MOV TH1, #0FFH 

//设置波特率重装值(65536-18432000/4/115200)

//T2为1T模式, 并启动定时器2

//选择定时器2为串口1的波特率发生器

//;定时器1为1T模式

//定时器1为模式0(16位自动重载)

//设置波特率重装值(65536-18432000/4/115200)

<table><tr><td>SETB</td><td>TR1</td><td>//定时器1开始运行</td></tr><tr><td>MOV</td><td>TMOD, #20H</td><td>//设置定时器1为8位自动重装载模式</td></tr><tr><td>MOV</td><td>AUXR, #40H</td><td>//定时器1为1T模式</td></tr><tr><td>MOV</td><td>TL1, #0FBH</td><td>//115200 bps(256 - 18432000/32/115200)</td></tr><tr><td>MOV</td><td>TH1, #0FBH</td><td></td></tr><tr><td>SETB</td><td>TR1</td><td></td></tr><tr><td>#endif</td><td></td><td></td></tr><tr><td>RET</td><td></td><td></td></tr><tr><td colspan="3">//--------</td></tr><tr><td colspan="3">END</td></tr></table>

# 8.15 串行口1的中继广播方式

串行口1可在3组管脚间进行切换：[RxD/P3.0, TxD/P3.1]；[RxD_2/P3.6, TxD_2/P3.7]；[RxD_3/P1.6, TxD_3/P1.7].

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>7</td><td>BB6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td><td>Reset Value</td></tr><tr><td>CLK_DIV(PCON2)</td><td>97H</td><td>时钟分频寄存器</td><td>MCKO_S1</td><td>MCKO_S0</td><td>ADRJ</td><td>Tx_Rx</td><td>MCLKO_2</td><td>CLKS2</td><td>CLKS1</td><td>CLKS0</td><td>0000,0000</td></tr></table>

# Tx_Rx：串口1的中继广播方式设置

# 0：串口1为正常工作方式

1：串口1为中继广播方式，即将RxD端口输入的电平状态实时输出在TxD外部管脚上，TxD外部管脚可以对RxD管脚的输入信号进行实时整形放大输出，TxD管脚的对外输出实时反映RxD端口输入的电平状态。

串口1的RxD管脚和TxD管脚可以在3组不同管脚之间进行切换：[RxD/P3.0, TxD/P3.1]；

$$
[ \mathrm {R x D} _ {- 2} / \mathrm {P 3 . 6}, \mathrm {T x D} _ {- 2} / \mathrm {P 3 . 7} ];
$$

$$
[ \mathrm {R x D} _ {-} 3 / \mathrm {P} 1. 6, \mathrm {T x D} _ {-} 3 / \mathrm {P} 1. 7 ].
$$

串行口1的中继广播方式除可以在用户程序中设置Tx_Rx/CLK_DIV.4来选择外，还可以在STC-ISP下载编程软件中设置。

当单片机的工作电压低于上电复位门槛电压(POR，3V单片机在1.8V附近，5V单片机在3.2V附近)时，Tx_Rx默认为0，即串行口1默认为正常工作方式。当单片机的工作电压高于上电复位门槛电压(POR，3V单片机在1.8V附近，5V单片机在3.2V附近)时，单片机首先读取用户在STC-ISP下载编程软件中的设置，如果用户允许了“单片机TxD管脚的对外输出实时反映RxD端口输入的电平状态”即中继广播方式，则上电复位后P3.7/TxD_2管脚的对外输出可以实时反映P3.6/RxD_2端口输入的电平状态，如果用户未选择“单片机TxD管脚的对外输出实时反映RxD端口输入的电平状态”，则上电复位后串口1为正常工作方式，即P3.7/TxD_2管脚的对外输出不实时反映P3.6/RxD_2端口输入的电平状态。

串行口1的位置和中继广播方式除可以在STC-ISP下载编程软件中设置外，还可以在用户的用户程序中用设置。在STC-ISP下载编程软件中的设置是在单片机上电复位后就可以执行的，如果用户在用户程序中的设置与STC-ISP下载编程软件中的设置不一致时，当执行到相应的用户程序时就会覆盖原来STC-ISP下载编程软件中的设置。

# 8.16 软件模拟串行口的测试程序(C及汇编)

# 如串行口不够用或无串行口可用[P3.0, P3.1]结合定时器0软件模拟串行口

# 1. C程序：

/*- -*/ 

/* --- STC MCU Limited - -*/ 

/* --- STC15Fxx 系列 软件模拟串口举例--- -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/* --*/ 

//本示例在Keil开发环境下请选择Intel的8058芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

//- 

//define baudrate const 

//BAUD = 256 - FOSC/3/BAUDRATE/M (1T:M=1; 12T:M=12) 

//NOTE: (FOSC/3/BAUDRATE) must be greater then 98, (RECOMMEND GREATER THEN 110) 

//#define BAUD 0xF400 // 1200bps @ 11.0592MHz 

//#define BAUD 0xFA00 // 2400bps @ 11.0592MHz 

//#define BAUD 0xFD00 // 4800bps @ 11.0592MHz 

//#define BAUD 0xFE80 // 9600bps @ 11.0592MHz 

//#define BAUD 0xFF40 //19200bps @ 11.0592MHz 

//#define BAUD 0xFFA0 //38400bps @ 11.0592MHz 

//#define BAUD 0xEC00 // 1200bps @ 18.432MHz 

//#define BAUD 0xF600 // 2400bps @ 18.432MHz 

//#define BAUD 0xFB00 // 4800bps @ 18.432MHz 

//#define BAUD 0xFD80 // 9600bps @ 18.432MHz 

//#define BAUD 0xFEC0 //19200bps @ 18.432MHz 

#define BAUD 0xFF60 //38400bps @ 18.432MHz 

//#define BAUD 0xE800 // 1200bps @ 22.1184MHz 

//#define BAUD 0xF400 // 2400bps @ 22.1184MHz 

//#define BAUD 0xFA00 // 4800bps @ 22.1184MHz 

//#define BAUD 0xFD00 // 9600bps @ 22.1184MHz 

```txt
//define BAUD 0xFE80  
//define BAUD 0xFF40  
//define BAUD 0xFF80  
sfr AUXR = 0x8E;  
sbit RXB = P3^0;  
sbit TXB = P3^1; 
```

//19200bps @ 22.1184MHz 

//38400bps @ 22.1184MHz 

//57600bps @ 22.1184MHz 

//define UART TX/RX port 

```txt
typedef bit BOOL; typedef unsigned char BYTE; typedef unsigned int WORD; 
```

```sql
BYTE TBUF, RBUF;  
BYTE TDAT, RDAT;  
BYTE TCNT, RCNT;  
BYTE TBIT, RBIT;  
BOOL TING, RING;  
BOOL TEND, REND; 
```

```sql
void UART_INIT(); 
```

```txt
BYTE t, r;  
BYTE buf[16]; 
```

void main()   
{ TMOD $= 0\mathrm{x}00$ //timer0 in 16-bit auto reload mode AUXR $= 0\mathrm{x}80$ //timer0 working at 1T mode TL0 $\equiv$ BAUD; TH0 $=$ BAUD>>8; //initial timer0 and set reload value TR0 $= 1$ //tiemr0 start running ET0 $= 1$ //enable timer0 interrupt PT0 $= 1$ //improve timer0 interrupt priority EA $= 1$ //open global interrupt switch UART_INIT(); while (1) { //user's function if (REND) { REND $= 0$ .. $\mathrm{buf[r + + }$ & 0x0f] $=$ RBUF; } if (TEND) 

{ if $(\mathrm{t} != \mathrm{r})$ { TEND $= 0$ TBUF $=$ buf[t++&0x0f]; TING $= 1$ . }   
}   
}   
//Timer interrupt routine for UART   
void tm0() interrupt 1 using 1 if (RING) { if(-RCNT $= = 0$ ） { RCNT $= 3$ //reset send baudrate counter if(-RBIT $= = 0$ ） { RBUF $=$ RDAT; //save the data to RBUF RING $= 0$ //stop receive REND $= 1$ //set receive completed flag } else { RDAT $> = 1$ if(RXB)RDAT $| = 0x80$ //shift RX data to RX buffer } }   
} else if(!RXB) { RING $= 1$ //set start receive flag RCNT $= 4$ //initial receive baudrate counter RBIT $= 9$ //initial receive bit number (8 data bits + 1 stop bit)   
}   
if(-TCNT $= = 0$ ） { TCNT $= 3$ //reset send baudrate counter 

```lisp
if (TING) //judge whether sending  
{  
if (TBIT == 0)  
{  
TXB = 0; //send start bit  
TDAT = TBUF; //load data from TBUF to TDAT  
TBIT = 9; //initial send bit number (8 data bits + 1 stop bit)  
}  
else  
{  
TDAT >= 1; //shift data to CY  
if (--TBIT == 0)  
{  
TXB = 1;  
TING = 0; //stop send  
TEND = 1; //set send completed flag  
}  
else  
{  
TXB = CY; //write CY to TX port  
}  
}  
} 
```

# 2. 汇编程序：

/*- -*/ 

/* --- STC MCU Limited - -*/ 

/* --- STC15Fxx 系列 软件模拟串口举例-- -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 - -*/ 

/* --- Tel: 86-755-82948412 -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/* -*/ 

//本示例在Keil开发环境下请选择Intel的8058芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

;define baudrate const 

;BAUD $=$ 65536 - FOSC/3/BAUDRATE/M (1T:M=1; 12T:M=12) 

;NOTE: (FOSC/3/BAUDRATE) must be greater then 75, (RECOMMEND GREATER THEN 100) 

;BAUD EQU 0F400H ; 1200bps @ 11.0592MHz 

;BAUD EQU 0FA00H ; 2400bps @ 11.0592MHz 

;BAUD EQU 0FD00H ; 4800bps @ 11.0592MHz 

;BAUD EQU 0FE80H ; 9600bps @ 11.0592MHz 

;BAUD EQU 0FF40H ;19200bps @ 11.0592MHz 

;BAUD EQU 0FFA0H ;38400bps @ 11.0592MHz 

;BAUD EQU 0FFC0H ;57600bps @ 11.0592MHz 

;BAUD EQU 0EC00H ; 1200bps @ 18.432MHz 

;BAUD EQU 0F600H ; 2400bps @ 18.432MHz 

;BAUD EQU 0FB00H ; 4800bps @ 18.432MHz 

;BAUD EQU 0FD80H ; 9600bps @ 18.432MHz 

;BAUD EQU 0FEC0H ;19200bps @ 18.432MHz 

;BAUD EQU 0FF60H ;38400bps @ 18.432MHz 

BAUD EQU 0FF95H ;57600bps @ 18.432MHz 

;BAUD EQU 0E800H ; 1200bps @ 22.1184MHz 

;BAUD EQU 0F400H ; 2400bps @ 22.1184MHz 

;BAUD EQU 0FA00H ; 4800bps @ 22.1184MHz 

;BAUD EQU 0FD00H ; 9600bps @ 22.1184MHz 

;BAUD EQU 0FE80H ;19200bps @ 22.1184MHz 

;BAUD EQU 0FF40H ;38400bps @ 22.1184MHz 

;BAUD EQU 0FF80H ;57600bps @ 22.1184MHz 

;define UART TX/RX port 

RXB BIT P3.0 

TXB BIT P3.1 

;define SFR 

AUXR DATA 8EH 

;define UART module variable 

TBUF DATA 08H ;(R0) ready send data buffer (USER WRITE ONLY) 

RBUF DATA 09H ;(R1) received data buffer (UAER READ ONLY) 

TDAT DATA 0AH ;(R2) sending data buffer (RESERVED FOR UART MODULE) 

RDAT DATA 0BH ;(R3) receiving data buffer (RESERVED FOR UART MODULE) 

TCNT DATA 0CH ;(R4) send baudrate counter (RESERVED FOR UART MODULE) 

RCNT DATA 0DH ;(R5) receive baudrate counter (RESERVED FOR UART MODULE) 

TBIT DATA 0EH ;(R6) send bit counter (RESERVED FOR UART MODULE) 

RBIT DATA 0FH ;(R7) receive bit counter (RESERVED FOR UART MODULE) 

TING BIT 20H.0 ; sending flag (USER WRITE "1" TO TRIGGER SEND DATA, 

CLEAR BY MODULE) 

RING BIT 20H.1 ; receiving flag (RESERVED FOR UART MODULE) 

TEND BIT 20H.2 ; sent flag (SET BY MODULE AND SHOULD USER CLEAR) 

REND BIT 20H.3 ; received flag (SET BY MODULE AND SHOULD USER CLEAR) 

RPTR DATA 21H ;circular queue read pointer 

WPTR DATA 22H ;circular queue write pointer 

BUFFER DATA 23H ;circular queue buffer (16 bytes) 

ORG 0000H 

LJMP RESET 

;Timer0 interrupt routine for UART 

ORG 000BH 

PUSH ACC ;4 save ACC 

PUSH PSW ;4 save PSW 

<table><tr><td>MOV</td><td>PSW,</td><td>#08H</td><td>;3 using register group 1</td></tr><tr><td>L_UARTSTART:</td><td></td><td></td><td></td></tr><tr><td>JB</td><td>RING,</td><td>L_RING</td><td>;4 judge whether receiving</td></tr><tr><td>JB</td><td>RXB,</td><td>L_REND</td><td>; check start signal</td></tr><tr><td>L_RSTART:</td><td></td><td></td><td></td></tr><tr><td>SETB</td><td>RING</td><td></td><td>; set start receive flag</td></tr><tr><td>MOV</td><td>R5,</td><td>#4</td><td>; initial receive baudrate counter</td></tr><tr><td>MOV</td><td>R7,</td><td>#9</td><td>; initial receive bit number (8 data bits + 1 stop bit)</td></tr><tr><td>SJMP</td><td>L_REND</td><td></td><td>; end this time slice</td></tr><tr><td>L_RING:</td><td></td><td></td><td></td></tr><tr><td>DJNZ</td><td>R5,</td><td>L_REND</td><td>;4 judge whether sending</td></tr><tr><td>MOV</td><td>R5,</td><td>#3</td><td>;2 reset send baudrate counter</td></tr><tr><td>L_RBIT:</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>C,</td><td>RXB</td><td>;3 read RX port data</td></tr><tr><td>MOV</td><td>A,</td><td>R3</td><td>;1 and shift it to RX buffer</td></tr><tr><td>RRC</td><td>A</td><td></td><td>;1</td></tr><tr><td>MOV</td><td>R3,</td><td>A</td><td>;2</td></tr><tr><td>DJNZ</td><td>R7,</td><td>L_REND</td><td>;4 judge whether the data have receive completed</td></tr><tr><td>L_RSTOP:</td><td></td><td></td><td></td></tr><tr><td>RLC</td><td>A</td><td></td><td>; shift out stop bit</td></tr><tr><td>MOV</td><td>R1,</td><td>A</td><td>; save the data to RBUF</td></tr><tr><td>CLR</td><td>RING</td><td></td><td>; stop receive</td></tr><tr><td>SETB</td><td>REND</td><td></td><td>; set receive completed flag</td></tr><tr><td>L_REND:</td><td></td><td></td><td></td></tr><tr><td>;</td><td></td><td></td><td></td></tr><tr><td>L_TING:</td><td></td><td></td><td></td></tr><tr><td>DJNZ</td><td>R4,</td><td>L_TEND</td><td>;4 check send baudrate counter</td></tr><tr><td>MOV</td><td>R4,</td><td>#3</td><td>;2 reset it</td></tr><tr><td>JNB</td><td>TING,</td><td>L_TEND</td><td>;4 judge whether sending</td></tr><tr><td>MOV</td><td>A,</td><td>R6</td><td>;1 detect the sent bits</td></tr><tr><td>JNZ</td><td>L_TBIT</td><td></td><td>;3 &quot;0&quot; means start bit not sent</td></tr><tr><td>L_TSTART:</td><td></td><td></td><td></td></tr><tr><td>CLR</td><td>TXB</td><td></td><td>; send start bit</td></tr><tr><td>MOV</td><td>TDAT,</td><td>R0</td><td>; load data from TBUF to TDAT</td></tr><tr><td>MOV</td><td>R6,</td><td>#9</td><td>; initial send bit number (8 data bits + 1 stop bit)</td></tr><tr><td>JMP</td><td>L_TEND</td><td></td><td>; end this time slice</td></tr><tr><td>L_TBIT:</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>A,</td><td>R2</td><td>;1 read data in TDAT</td></tr><tr><td>SETB</td><td>C</td><td></td><td>;1 shift in stop bit</td></tr><tr><td>RRC</td><td>A</td><td></td><td>;1 shift data to CY</td></tr><tr><td>MOV</td><td>R2,</td><td>A</td><td>;2 update TDAT</td></tr><tr><td>MOV</td><td>TXB,</td><td>C</td><td>;4 write CY to TX port</td></tr><tr><td>DJNZ</td><td>R6,</td><td>L_TEND</td><td>;4 judge whether the data have send completed</td></tr></table>

# L_TSTOP:

CLR TING ; stop send 

SETB TEND ; set send completed flag 

# L_TEND:

# L_UARTEND:

POP PSW ;3 restore PSW 

POP ACC ;3 restore ACC 

RETI ;4 (69) 

;initial UART module variable 

# UART_INIT:

CLR TING 

CLR RING 

SETB TEND 

CLR REND 

CLR A 

MOV TCNT, A 

MOV RCNT, A 

RET 

;main program entry 

# RESET:

MOV R0, #7FH ;clear RAM 

CLR A 

MOV @R0, A 

DJNZ R0, $-1 

MOV SP, #7FH ;initial SP 

# ;system initial

MOV TMOD, #00H ;timer0 in 16-bit auto reload mode 

MOV AUXR, #80H ;timer0 working at 1T mode 

MOV TL0, #LOW BAUD ;initial timer0 and 

MOV TH0, #HIGH BAUD ;set reload value 

SETB TR0 ;tiemr0 start running 

SETB ET0 ;enable timer0 interrupt 

SETB PT0 ;improve timer0 interrupt priority 

SETB EA ;open global interrupt switch 

LCALL UART_INIT 

# MAIN:

JNB REND, CHECKREND ;if (REND) 

CLR REND ;{ MOV A, RPTR ; REND $= 0$ INC RPTR ; BUFFER[RPTR++&0xf] $\equiv$ RBUF; ANL A,#0FH ;ADD A,#BUFFER ;MOV R0,A ;MOV @R0,RBUF ;CHECKREND: JNB TEND, MAIN ;if (TEND) MOV A, RPTR ;XRL A, WPTR ; if (WPTR != REND) JZ MAIN ; CLR TEND ; TEND $= 0$ MOV A, WPTR ; TBUF $\equiv$ BUFFER[WPTR++&0xf]; INC WPTR ; TING $= 1$ ; ANL A,#0FH ; ADD A,#BUFFER ; MOV R0,A ; MOV TBUF, @R0 ; SETB TING ; SJMP MAIN 

# 第9章 STC15系列单片机EEPROM的应用

STC15系列单片机内部集成了大容量的EEPROM，其与程序空间是分开的。�利 �术可将内部Data Flash当EEPROM，擦写次数在10万次以上。EEPROM可分为若干个扇区，�每区包含512字节。使用时，建议同一次修改的数据放在同一个扇区，不是同一次修改的数据放在不同的扇区，不一定要用满。数据存储器的擦除操作是按扇区进行的。

EEPROM可用于保存一些需要在应用过程中修改并且掉电不丢失的参数数据。在用户程序中，可以对EEPROM进行字节读/字节编程/扇区擦除操作。在工作电压Vcc偏低时，建议不要进行EEPROM/IAP操作。

# 9.1 IAP及EEPROM新增特殊功能寄存器介绍

<table><tr><td>符号</td><td>描述</td><td>地址</td><td colspan="9">位地址及符号MSBLSB</td><td>复位值</td></tr><tr><td>IAP_DATA</td><td>ISP/IAP Flash Data Register</td><td>C2H</td><td colspan="9"></td><td>1111 1111B</td></tr><tr><td>IAP_ADDRH</td><td>ISP/IAP Flash Address High</td><td>C3H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>IAP_ADDRL</td><td>ISP/IAP Flash Address Low</td><td>C4H</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td rowspan="2">IAP_CMD</td><td rowspan="2">ISP/IAP Flash Command Register</td><td rowspan="2">C5H</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>MS1</td><td colspan="2">MS0</td><td rowspan="2">xxxx x000B</td></tr><tr><td colspan="9"></td></tr><tr><td>IAP_TRIG</td><td>ISP/IAP Flash Command Trigger</td><td>C6H</td><td colspan="9"></td><td>xxxx xxxxxB</td></tr><tr><td rowspan="2">IAP_CONTR</td><td rowspan="2">ISP/IAP Control Register</td><td rowspan="2">C7H</td><td>IAPEN</td><td>SWBS</td><td>SWRST</td><td>CMD_FAIL</td><td>-</td><td>WT2</td><td>WT1</td><td colspan="2">WT0</td><td rowspan="2">0000 x000B</td></tr><tr><td colspan="9"></td></tr><tr><td>PCON</td><td>Power Control</td><td>87H</td><td>SMOD</td><td>SMODO</td><td>LVDF</td><td>POF</td><td>GF1</td><td>GF0</td><td>PD</td><td colspan="2">IDL</td><td>0011 0000B</td></tr></table>

# 1. ISP/IAP数据寄存器IAP_DATA

IAP_DATA : ISP/IAP 操作时的数据寄存器。

ISP/IAP 从Flash读出的数据放在此处，向Flash写的数据也需放在此处

# 2. ISP/IAP地址寄存器IAP_ADDRH和IAP_ADDRL

IAP_ADDRH : ISP/IAP 操作时的地址寄存器高八位。

IAP_ADDRL : ISP/IAP 操作时的地址寄存器低八位。

# 3. ISP/IAP命令寄存器IAP_CMD

ISP/IAP命令寄存器IAP_CMD格式如下：

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IAP_CMD</td><td>C5H</td><td>name</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>MS1</td><td>MS0</td></tr></table>

<table><tr><td>MS1</td><td>MS0</td><td>命令 / 操作 模式选择</td></tr><tr><td>0</td><td>0</td><td>Standby 待机模式，无ISP操作</td></tr><tr><td>0</td><td>1</td><td>从用户的应用程序区对&quot;Data Flash/EEPROM区&quot;进行字节读</td></tr><tr><td>1</td><td>0</td><td>从用户的应用程序区对&quot;Data Flash/EEPROM区&quot;进行字节编程</td></tr><tr><td>1</td><td>1</td><td>从用户的应用程序区对&quot;Data Flash/EEPROM区&quot;进行扇区擦除</td></tr></table>

程序在用户应用程序区时，仅可以对数据Flash区(EEPROM)进行字节读/字节编程/扇区擦除IAP15系列 �P15系列可在用户应用程序区修改用户

特别声明：EEPROM也可以用MOVC指令读(MOVC访问的是程序存储器)，但起始地址不再是0000H,而是程序存储空间结束地址的下一个地址。

# 4. ISP/IAP命令触发寄存器IAP_TRIG

IAP_TRIG: ISP/IAP操作时的命令触发寄存器。

在IAPEN(IAP_CONTR.7) = 1 时,对IAP_TRIG先写入5Ah,再写入A5h,ISP/IAP命令才会生效。

ISP/IAP操作完成后，I�AP地址高八位寄存器I�AP_�ADDRH�、I�AP地址低八位寄存器I�AP_�ADDRL和I�AP命令寄存器IAP_CMD的内容不变。如果接下来要对下一个地址的数据进行ISP/IAP操作，需手动将该地址的高8位和低8位分别写入IAP_ADDRH和IAP_ADDRL寄存器。

每次IAP操作时，都要对IAP_TRIG先写入5AH，再写入A5H，ISP/IAP命令才会生效。

在每次触发前，需重新送字节读/字节编程/扇区擦除命令，在命令不改变时,不需重新送命令

# 5. ISP/IAP命令寄存器IAP_CONTR

ISP/IAP控制寄存器IAP_CONTR格式如下：

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IAP_CONTR</td><td>C7H</td><td>name</td><td>IAPEN</td><td>SWBS</td><td>SWRST</td><td>CMD_FAIL</td><td>-</td><td>WT2</td><td>WT2</td><td>WT0</td></tr></table>

IAPEN: ISP/IAP功能允许位。0：禁止IAP读/写/ Data Flash/EEPROM

1: 允许IAP读/写/ Data Flash/EEPROM

SWBS: 启动(送0) �ISP� 启动(送1)。要与SWRST直接配合才可以实现

SWRST: 0: 不操作； 1: �生复位，单片机自动复位

CMD_FAIL: 如果IAP地址(由IAP地址寄存器IAP_ADDRH和IAP_ADDRL的值决定)指向了非法地址或无效地址，且送了ISP/IAP命令,并对IAP_TRIG送5Ah/A5h触发失败，CMD_FAIL为1,需由软件清零

;在用户应用程序区(AP 区)软件复位并从用户应用程序区(AP 区)开始执行程序

MOV IAP_CONTR, #00100000B ;SWBS = 0(选择AP 区), SWRST = 1(软复位)

;在用户应用程序区(AP 区)软件复位并从系统ISP 监控程序区开始执行程序

MOV IAP_CONTR, #01100000B ;SWBS = 1(选择ISP 区), SWRST = 1(软复位)

;在系统ISP 监控程序区软件复位并从用户应用程序区(AP 区)开始执行程序

MOV IAP_CONTR, #00100000B ;SWBS = 0(选择AP 区), SWRST = 1(软复位)

;在系统ISP 监控程序区软件复位并从系统ISP 监控程序区开始执行程序

MOV IAP_CONTR, #01100000B ;SWBS = 1(选择ISP 区), SWRST = 1(软复位)

<table><tr><td colspan="3">设置等待时间</td><td colspan="4">CPU等待时间(多少个CPU工作时钟)</td></tr><tr><td>WT2</td><td>WT1</td><td>WT0</td><td>Read/读(2个时钟)</td><td>Program/编程(=55us)</td><td>Sector Erase扇区擦除(=21ms)</td><td>Recommended System Clock跟等待参数对应的推荐系统时钟</td></tr><tr><td>1</td><td>1</td><td>1</td><td>2个时钟</td><td>55个时钟</td><td>21012个时钟</td><td>≤ 1MHz</td></tr><tr><td>1</td><td>1</td><td>0</td><td>2个时钟</td><td>110个时钟</td><td>42024个时钟</td><td>≤ 2MHz</td></tr><tr><td>1</td><td>0</td><td>1</td><td>2个时钟</td><td>165个时钟</td><td>63036个时钟</td><td>≤ 3MHz</td></tr><tr><td>1</td><td>0</td><td>0</td><td>2个时钟</td><td>330个时钟</td><td>126072个时钟</td><td>≤ 6MHz</td></tr><tr><td>0</td><td>1</td><td>1</td><td>2个时钟</td><td>660个时钟</td><td>252144个时钟</td><td>≤ 12MHz</td></tr><tr><td>0</td><td>1</td><td>0</td><td>2个时钟</td><td>1100个时钟</td><td>420240个时钟</td><td>≤ 20MHz</td></tr><tr><td>0</td><td>0</td><td>1</td><td>2个时钟</td><td>1320个时钟</td><td>504288个时钟</td><td>≤ 24MHz</td></tr><tr><td>0</td><td>0</td><td>0</td><td>2个时钟</td><td>1760个时钟</td><td>672384个时钟</td><td>≤ 30MHz</td></tr></table>

# 6. 工作电压过低判断，此时不要进行EEPROM/IAP操作


PCON : 电源控制寄存器


<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>PCON</td><td>87H</td><td>name</td><td>SMOD</td><td>SMOD0</td><td>LVDF</td><td>POF</td><td>GF1</td><td>GF0</td><td>PD</td><td>IDL</td></tr></table>

LVDF: 低压检测标志位,当工作电压Vcc低于低压检测门槛电压时，该位置1。该位要由软件清0当低压检测电路发现工作电压Vcc偏低时，不要进行EEPROM/IAP操作。

5V单片机的低压检测门槛电压：

<table><tr><td>-40 °C</td><td>25 °C</td><td>85 °C</td></tr><tr><td>4.74</td><td>4.64</td><td>4.60</td></tr><tr><td>4.41</td><td>4.32</td><td>4.27</td></tr><tr><td>4.14</td><td>4.05</td><td>4.00</td></tr><tr><td>3.90</td><td>3.82</td><td>3.77</td></tr><tr><td>3.69</td><td>3.61</td><td>3.56</td></tr><tr><td>3.51</td><td>3.43</td><td>3.38</td></tr><tr><td>3.36</td><td>3.28</td><td>3.23</td></tr><tr><td>3.21</td><td>3.14</td><td>3.09</td></tr></table>

3.3V单片机的低压检测门槛电压：

<table><tr><td>-40 °C</td><td>25 °C</td><td>85 °C</td></tr><tr><td>3.11</td><td>3.08</td><td>3.09</td></tr><tr><td>2.85</td><td>2.82</td><td>2.83</td></tr><tr><td>2.63</td><td>2.61</td><td>2.61</td></tr><tr><td>2.44</td><td>2.42</td><td>2.43</td></tr><tr><td>2.29</td><td>2.26</td><td>2.26</td></tr><tr><td>2.14</td><td>2.12</td><td>2.12</td></tr><tr><td>2.01</td><td>2.00</td><td>2.00</td></tr><tr><td>1.90</td><td>1.89</td><td>1.89</td></tr></table>

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/6f0bb2216c52a3322730fda31d5dab8d88559e158c5737ea7ac090e6c3cec17f.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/cc45844ef0ee6bca905974e24d33aa06e04c69385bb58deb7ac12c8f1cb7b099.jpg)


建议在电压偏低时，不要操作EEPROM/IAP, 烧录时直接选择“低压禁止EEPROM操作”

# 9.2 STC15系列单片机EEPROM空间大小及地址

# 9.2.1 STC15W4K60S4系列单片机EEPROM空间大小及地址

<table><tr><td colspan="7">STC15W4K60S4系列单片机内部EEPROM选型一览表</td><td rowspan="2">STC15W4K60S4系列单片机内部EEPROM还可以用MOVC指令读,但此时首地址不再是0000H,而是程序存储空间结束地址的下一个地址</td></tr><tr><td>型号</td><td>EEPROM字节数</td><td>扇区数</td><td>用IAP字节读时EEPROM起始扇区首地址</td><td>用IAP字节读时EEPROM结束扇区末尾地址</td><td>用MOVC指令读时EEPROM起始扇区首地址</td><td>用MOVC指令读时EEPROM结束扇区末尾地址</td></tr><tr><td>STC15W4K08S4</td><td>53K</td><td>106</td><td>0000h</td><td>D3FFh</td><td>2000h</td><td>F3FFh</td><td rowspan="8">512字节为一个扇区</td></tr><tr><td>STC15W4K16S4</td><td>45K</td><td>90</td><td>0000h</td><td>B3FFh</td><td>4000h</td><td>F3FFh</td></tr><tr><td>STC15W4K24S4</td><td>37K</td><td>74</td><td>0000h</td><td>93FFh</td><td>6000h</td><td>F3FFh</td></tr><tr><td>STC15W4K32S4</td><td>29K</td><td>58</td><td>0000h</td><td>73FFh</td><td>8000h</td><td>F3FFh</td></tr><tr><td>STC15W4K40S4</td><td>21K</td><td>42</td><td>0000h</td><td>53FFh</td><td>A000h</td><td>F3FFh</td></tr><tr><td>STC15W4K48S4</td><td>13K</td><td>26</td><td>0000h</td><td>33FFh</td><td>C000h</td><td>F3FFh</td></tr><tr><td>STC15W4K56S4</td><td>5K</td><td>10</td><td>0000h</td><td>13FFh</td><td>E000h</td><td>F3FFh</td></tr><tr><td>STC15W4K60S4</td><td>1K</td><td>2</td><td>0000h</td><td>03FFh</td><td>F000h</td><td>F3FFh</td></tr><tr><td colspan="8">以下系列特殊,可在用户程序区直接修改程序,所有Flash空间均可作EEPROM修改</td></tr><tr><td>IAP15W4K61S4</td><td>-</td><td>122</td><td>0000h</td><td>F3FFh</td><td></td><td></td><td>没有专门的E - PROM,但可在用户程序区修改用户程序,使用时不要将自己的有效程序擦除。</td></tr></table>

# 9.2.2 STC15F2K60S2及STC15L2K60S2系列EEPROM空间大小及地址

<table><tr><td colspan="7">STC15F2K60S2系列单片机内部EEPROM选型一览表STC15L2K60S2系列单片机内部EEPROM选型一览表</td><td rowspan="18">STC15F2K60S2及STC15L2K60S2系列单片机内部EEPROM还可以用MOVC指令读,但此时首地址不再是0000H,而是程序存储空间结束地址的下一个地址512字节为一个扇区</td></tr><tr><td>型号</td><td>EEPROM字节数</td><td>扇区数</td><td>用IAP字节读时EEPROM起始扇区首地址</td><td>用IAP字节读时EEPROM结束扇区末尾地址</td><td>用MOVC指令读时EEPROM起始扇区首地址</td><td>用MOVC指令读时EEPROM结束扇区末尾地址</td></tr><tr><td>STC15F2K08S2</td><td rowspan="2">53K</td><td rowspan="2">106</td><td rowspan="2">0000h</td><td rowspan="2">D3FFh</td><td rowspan="2">2000h</td><td rowspan="2">F3FFh</td></tr><tr><td>STC15L2K08S2</td></tr><tr><td>STC15F2K16S2</td><td rowspan="2">45K</td><td rowspan="2">90</td><td rowspan="2">0000h</td><td rowspan="2">B3FFh</td><td rowspan="2">4000h</td><td rowspan="2">F3FFh</td></tr><tr><td>STC15L2K16S2</td></tr><tr><td>STC15F2K24S2</td><td rowspan="2">37K</td><td rowspan="2">74</td><td rowspan="2">0000h</td><td rowspan="2">93FFh</td><td rowspan="2">6000h</td><td rowspan="2">F3FFh</td></tr><tr><td>STC15L2K24S2</td></tr><tr><td>STC15F2K32S2</td><td rowspan="2">29K</td><td rowspan="2">58</td><td rowspan="2">0000h</td><td rowspan="2">73FFh</td><td rowspan="2">8000h</td><td rowspan="2">F3FFh</td></tr><tr><td>STC15L2K32S2</td></tr><tr><td>STC15F2K40S2</td><td rowspan="2">21K</td><td rowspan="2">42</td><td rowspan="2">0000h</td><td rowspan="2">53FFh</td><td rowspan="2">A000h</td><td rowspan="2">F3FFh</td></tr><tr><td>STC15L2K40S2</td></tr><tr><td>STC15F2K48S2</td><td rowspan="2">13K</td><td rowspan="2">26</td><td rowspan="2">0000h</td><td rowspan="2">33FFh</td><td rowspan="2">C000h</td><td rowspan="2">F3FFh</td></tr><tr><td>STC15L2K48S2</td></tr><tr><td>STC15F2K56S2</td><td rowspan="2">5K</td><td rowspan="2">10</td><td rowspan="2">0000h</td><td rowspan="2">13FFh</td><td rowspan="2">E000h</td><td rowspan="2">F3FFh</td></tr><tr><td>STC15L2K56S2</td></tr><tr><td>STC15F2K60S2</td><td rowspan="2">1K</td><td rowspan="2">2</td><td rowspan="2">0000h</td><td rowspan="2">03FFh</td><td rowspan="2">F000h</td><td rowspan="2">F3FFh</td></tr><tr><td>STC15L2K60S2</td></tr><tr><td colspan="8">以下系列特殊,可在用户程序区直接修改程序,所有Flash空间均可作EEPROM修改</td></tr><tr><td>IAP15F2K61S2</td><td rowspan="2">-</td><td rowspan="2">122</td><td rowspan="2">0000h</td><td rowspan="2">F3FFh</td><td rowspan="2"></td><td rowspan="2"></td><td rowspan="2">没有专门的EEPROM,但可在用户程序区修改用户程序,使用时不要将自己的有效程序擦除。</td></tr><tr><td>IAP15L2K61S2</td></tr></table>

# 9.2.3 STC15W1K16S系列单片机EEPROM空间大小及地址

<table><tr><td colspan="7">STC15W1K16S系列单片机内部EEPROM选型一览表</td><td rowspan="4">STC15W1K16S系列单片机内部EEPROM还可以用MOVC指令读,但此时首地址不再是0000H,而是程序存储空间结束地址的下一个地址512字节为一个扇区</td></tr><tr><td>型号</td><td>EEPROM字节数</td><td>扇区数</td><td>用IAP字节读时EEPROM起始扇区首地址</td><td>用IAP字节读时EEPROM结束扇区末尾地址</td><td>用MOVC指令读时EEPROM起始扇区首地址</td><td>用MOVC指令读时EEPROM结束扇区末尾地址</td></tr><tr><td>STC15W1K16S</td><td>13K</td><td>26</td><td>0000h</td><td>33FFh</td><td></td><td></td></tr><tr><td>STC15W1K24S</td><td>5K</td><td>10</td><td>0000h</td><td>13FFh</td><td></td><td></td></tr><tr><td colspan="8">以下系列特殊,可在用户程序区直接修改程序,所有Flash空间均可作EEPROM修改</td></tr><tr><td>IAP15W1K29S</td><td>-</td><td>58</td><td>0000h</td><td>73FFh</td><td></td><td></td><td>没有专门的EEPROM,但可在用户程序区修改用户程序,使用时不要将自己的有效程序擦除。</td></tr></table>

STC15W1K16S系列中以STC开头的单片机不能用MOVC读EEPROM。

# 9.2.4 STC15W408S系列单片机EEPROM空间大小及地址

<table><tr><td colspan="7">STC15W408S系列单片机内部EEPROM选型一览表</td><td rowspan="5">STC15W408S系列单片机内部EEPROM还可以用MOVC指令读,但此时首地址不再是0000H,而是程序存储空间结束地址的下一个地址512字节为一个扇区</td></tr><tr><td>型号</td><td>EEPROM字节数</td><td>扇区数</td><td>用IAP字节读时EEPROM起始扇区首地址</td><td>用IAP字节读时EEPROM结束扇区末尾地址</td><td>用MOVC指令读时EEPROM起始扇区首地址</td><td>用MOVC指令读时EEPROM结束扇区末尾地址</td></tr><tr><td>STC15W404S</td><td>9K</td><td>18</td><td>0000h</td><td>23FFh</td><td></td><td></td></tr><tr><td>STC15W408S</td><td>5K</td><td>10</td><td>0000h</td><td>13FFh</td><td></td><td></td></tr><tr><td>STC15W410S</td><td>3K</td><td>6</td><td>0000h</td><td>0BFFh</td><td></td><td></td></tr><tr><td colspan="8">以下系列特殊,可在用户程序区直接修改程序,所有Flash空间均可作EEPROM修改</td></tr><tr><td>IAP15W413S</td><td>-</td><td>26</td><td>0000h</td><td>33FFh</td><td></td><td></td><td>没有专门的EEPROM,但可在用户程序区修改用户程序,使用时不要将自己的有效程序擦除。</td></tr></table>

STC15W408S系列中以STC开头的单片机不能用MOVC读EEPROM。

# 9.2.5 STC15W408AS系列单片机EEPROM空间大小及地址

<table><tr><td colspan="7">STC15W408AS系列单片机内部EEPROM选型一览表</td><td rowspan="6">STC15W408AS系列单片机内部EEPROM还可以用MOVC指令读,但此时首地址不再是0000H,而是程序存储空间结束地址的下一个地址512字节为一个扇区</td></tr><tr><td>型号</td><td>EEPROM字节数</td><td>扇区数</td><td>用IAP字节读时EEPROM起始扇区首地址</td><td>用IAP字节读时EEPROM结束扇区末尾地址</td><td>用MOVC指令读时EEPROM起始扇区首地址</td><td>用MOVC指令读时EEPROM结束扇区末尾地址</td></tr><tr><td>STC15W404AS</td><td>9K</td><td>18</td><td>0000h</td><td>23FFh</td><td>1000h</td><td>33FFh</td></tr><tr><td>STC15W408AS</td><td>5K</td><td>10</td><td>0000h</td><td>13FFh</td><td>2000h</td><td>33FFh</td></tr><tr><td>STC15W410AD</td><td>3K</td><td>6</td><td>0000h</td><td>0BFFh</td><td>2800h</td><td>33FFh</td></tr><tr><td>STC15W412AD</td><td>1K</td><td>2</td><td>0000h</td><td>03FFh</td><td>3000h</td><td>33FFh</td></tr><tr><td colspan="8">以下系列特殊,可在用户程序区直接修改程序,所有Flash空间均可作EEPROM修改</td></tr><tr><td>IAP15W413AS</td><td>-</td><td>26</td><td>0000h</td><td>33FFh</td><td></td><td></td><td>没有专门的EEPROM,但可在用户程序区修改用户程序,使用时不要将自己的有效程序擦除。</td></tr></table>

# 9.2.6 STC15W201S系列单片机EEPROM空间大小及地址

<table><tr><td colspan="7">STC15W201S系列单片机内部EEPROM选型一览表</td><td rowspan="6">STC15W201S系列单片机内部EEPROM还可以用MOVC指令读,但此时首地址不再是0000H,而是程序存储空间结束地址的下一个地址512字节为一个扇区</td></tr><tr><td>型号</td><td>EEPROM字节数</td><td>扇区数</td><td>用IAP字节读时EEPROM起始扇区首地址</td><td>用IAP字节读时EEPROM结束扇区末尾地址</td><td>用MOVC指令读时EEPROM起始扇区首地址</td><td>用MOVC指令读时EEPROM结束扇区末尾地址</td></tr><tr><td>STC15W201S</td><td>4K</td><td>8</td><td>0000h</td><td>0FFFh</td><td></td><td></td></tr><tr><td>STC15W202S</td><td>3K</td><td>6</td><td>0000h</td><td>0BFFh</td><td></td><td></td></tr><tr><td>STC15W203S</td><td>2K</td><td>4</td><td>0000h</td><td>07FFh</td><td></td><td></td></tr><tr><td>STC15W204S</td><td>1K</td><td>2</td><td>0000h</td><td>03FFh</td><td></td><td></td></tr><tr><td colspan="8">以下系列特殊,可在用户程序区直接修改程序,所有Flash空间均可作EEPROM修改</td></tr><tr><td>IAP15W205S</td><td>-</td><td>10</td><td>0000h</td><td>13FFh</td><td></td><td></td><td>没有专门的EEPROM,但可在用户程序区修改用户程序,使用时不要将自己的有效程序擦除。</td></tr></table>

STC15W201S系列中以STC开头的单片机不能用MOVC读EEPROM。

# 9.2.7 STC15F408AD及STC15L408AD系列EEPROM空间大小及地址

<table><tr><td colspan="7">STC15F408AD系列单片机内部EEPROM选型一览表
STC15L408AD系列单片机内部EEPROM选型一览表</td><td rowspan="3">STC15F408AD及
STC15L408AD系列单片机内部EEPROM还可以用MOVC指令读，但此时首地址不再是0000H，而是程序存储空间结束地址的下一个地址
512字节为一个扇区</td></tr><tr><td>型号</td><td>EEPROM字节数</td><td>扇区数</td><td>用IAP字节读时EEPROM起始扇区首地址</td><td>用IAP字节读时EEPROM结束扇区末尾地址</td><td>用MOVC指令读时EEPROM起始扇区首地址</td><td>用MOVC指令读时EEPROM结束扇区末尾地址</td></tr><tr><td>STC15F408AD</td><td>5K</td><td>10</td><td>0000h</td><td>13FFh</td><td>2000h</td><td>33FFh</td></tr><tr><td colspan="8">以下系列特殊，可在用户程序区直接修改程序，所有Flash空间均可作EEPROM修改</td></tr><tr><td>IAP15F413AD</td><td rowspan="2">-</td><td rowspan="2">26</td><td rowspan="2">0000h</td><td rowspan="2">33FFh</td><td rowspan="2"></td><td rowspan="2"></td><td rowspan="2">没有专门的EEPROM,但可在用户程序区修改用户程序，使用时不要将自己的有效程序擦除。</td></tr><tr><td>IAP15L413AD</td></tr></table>

# 9.2.8 STC15F101W及STC15L101W系列EEPROM空间大小及地址

<table><tr><td colspan="7">STC15F101W系列单片机内部EEPROM选型一览表STC15L101W系列单片机内部EEPROM选型一览表</td><td colspan="2" rowspan="7">STC15F101W及STC15L101W系列单片机内部EEPROM还可以用MOVC指令读,但此时首地址不再是0000H,而是程序存储空间结束地址的下一个地址512字节为一个扇区</td></tr><tr><td>型号</td><td>EEPROM字节数</td><td>扇区数</td><td>用IAP字节读时EEPROM起始扇区首地址</td><td>用IAP字节读时EEPROM结束扇区末尾地址</td><td>用MOVC指令读时EEPROM起始扇区首地址</td><td colspan="2">用MOVC指令读时EEPROM结束扇区末尾地址</td></tr><tr><td>STC15F101W</td><td>4K</td><td>8</td><td>0000h</td><td>0FFFh</td><td>0400h</td><td colspan="2">13FFh</td></tr><tr><td>STC15F102W</td><td>3K</td><td>6</td><td>0000h</td><td>0BFFh</td><td>0800h</td><td colspan="2">13FFh</td></tr><tr><td>STC15F103W</td><td>2K</td><td>4</td><td>0000h</td><td>07FFh</td><td>0C00h</td><td colspan="2">13FFh</td></tr><tr><td>STC15F103W</td><td>2K</td><td>4</td><td>0000h</td><td>07FFh</td><td>0C00h</td><td colspan="2">13FFh</td></tr><tr><td>STC15F104W</td><td>1K</td><td>2</td><td>0000h</td><td>03FFh</td><td>1000h</td><td colspan="2">13FFh</td></tr><tr><td colspan="9">以下系列特殊,可在用户程序区直接修改程序,所有Flash空间均可作EEPROM修改</td></tr><tr><td>IAP15F105W</td><td rowspan="2">-</td><td rowspan="2">10</td><td rowspan="2">0000h</td><td rowspan="2">13FFh</td><td rowspan="2"></td><td rowspan="2"></td><td colspan="2" rowspan="2">没有专门的EEPROM,但可在用户程序区修改用户程序,使用时不要将自己的有效程序擦除。</td></tr><tr><td colspan="9">IAP15L105W</td></tr><tr><td colspan="9">STC15单片机的内部EEPROM地址表</td></tr><tr><td colspan="2">第一扇区</td><td colspan="2">第二扇区</td><td colspan="2">第三扇区</td><td colspan="2">第四扇区</td><td rowspan="42">每个扇区512字节建议同一次修改的数据放在同一扇区,不是同一次修改的数据放在不同的扇区,不 必用满,当然可全用</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>0000h</td><td>1FFh</td><td>200h</td><td>3FFh</td><td>400h</td><td>5FFh</td><td>600h</td><td>7FFh</td></tr><tr><td colspan="2">第五扇区</td><td colspan="2">第六扇区</td><td colspan="2">第七扇区</td><td colspan="2">第八扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>800h</td><td>9FFh</td><td>A00h</td><td>BFFh</td><td>C00h</td><td>DFFh</td><td>E00h</td><td>FFFh</td></tr><tr><td colspan="2">第九扇区</td><td colspan="2">第十扇区</td><td colspan="2">第十一扇区</td><td colspan="2">第十二扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>1000h</td><td>11FFh</td><td>1200h</td><td>13FFh</td><td>1400h</td><td>15FFh</td><td>1600h</td><td>17FFh</td></tr><tr><td colspan="2">第十三扇区</td><td colspan="2">第十四扇区</td><td colspan="2">第十五扇区</td><td colspan="2">第十六扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>1800h</td><td>19FFh</td><td>1A00h</td><td>1BFFh</td><td>1C00h</td><td>1DFFh</td><td>1E00h</td><td>1FFFh</td></tr><tr><td colspan="2">第十七扇区</td><td colspan="2">第十八扇区</td><td colspan="2">第十九扇区</td><td colspan="2">第二十扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>2000h</td><td>21FFh</td><td>2200h</td><td>23FFh</td><td>2400h</td><td>25FFh</td><td>2600h</td><td>27FFh</td></tr><tr><td colspan="2">第二十一扇区</td><td colspan="2">第二十二扇区</td><td colspan="2">第二十三扇区</td><td colspan="2">第二十四扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>2800h</td><td>29FFh</td><td>2A00h</td><td>2BFFh</td><td>2C00h</td><td>2DFFh</td><td>2E00h</td><td>2FFFH</td></tr><tr><td colspan="2">第二十五扇区</td><td colspan="2">第二十六扇区</td><td colspan="2">第二十七扇区</td><td colspan="2">第二十八扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>3000h</td><td>31FFh</td><td>3200h</td><td>33FFh</td><td>3400h</td><td>35FFh</td><td>3600h</td><td>37FFH</td></tr><tr><td colspan="2">第二十九扇区</td><td colspan="2">第三十扇区</td><td colspan="2">第三十一扇区</td><td colspan="2">第三十二扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>3800h</td><td>39FFh</td><td>3A00h</td><td>3BFFh</td><td>3C00h</td><td>3DFFh</td><td>3E00h</td><td>3FFFH</td></tr><tr><td colspan="2">第三十三扇区</td><td colspan="2">第三十四扇区</td><td colspan="2">第三十五扇区</td><td colspan="2">第三十六扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>4000h</td><td>41FFh</td><td>4200h</td><td>43FFh</td><td>4400h</td><td>45FFh</td><td>4600h</td><td>47FFH</td></tr><tr><td colspan="2">第三十七扇区</td><td colspan="2">第三十八扇区</td><td colspan="2">第三十九扇区</td><td colspan="2">第四十扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>4800h</td><td>49FFh</td><td>4A00h</td><td>4BFFh</td><td>4C00h</td><td>4DFFh</td><td>4E00h</td><td>4FFFH</td></tr><tr><td colspan="2">第四十一扇区</td><td colspan="2">第四十二扇区</td><td colspan="2">第四十三扇区</td><td colspan="2">第四十四扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>5000h</td><td>51FFh</td><td>5200h</td><td>53FFh</td><td>5400h</td><td>55FFh</td><td>5600h</td><td>57FFH</td></tr><tr><td colspan="2">第四十五扇区</td><td colspan="2">第四十六扇区</td><td colspan="2">第四十七扇区</td><td colspan="2">第四十八扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>5800h</td><td>59FFh</td><td>5A00h</td><td>5BFFh</td><td>5C00h</td><td>5DFFh</td><td>5E00h</td><td>5FFFH</td></tr><tr><td colspan="2">第四十九扇区</td><td colspan="2">第五十扇区</td><td colspan="2">第五十一扇区</td><td colspan="2">第五十二扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>6000h</td><td>61FFh</td><td>6200h</td><td>63FFh</td><td>6400h</td><td>65FFh</td><td>6600h</td><td>67FFH</td></tr><tr><td colspan="2">第五十三扇区</td><td colspan="2">第五十四扇区</td><td colspan="2">第五十五扇区</td><td colspan="2">第五十六扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>6800h</td><td>69FFh</td><td>6A00h</td><td>6BFFh</td><td>6C00h</td><td>6DFFh</td><td>6E00h</td><td>6FFFH</td></tr><tr><td colspan="2">第五十七扇区</td><td colspan="2">第五十八扇区</td><td colspan="2">第五十九扇区</td><td colspan="2">第六十扇区</td><td rowspan="42">每个扇区512字节建议同一次修改的数据放在同一扇区,不是同一次修改的数据放在不同的扇区,不 必用满,当然可全用</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>7000h</td><td>71FFh</td><td>7200h</td><td>73FFh</td><td>7400h</td><td>75FFh</td><td>7600h</td><td>77FFh</td></tr><tr><td colspan="2">第六十一扇区</td><td colspan="2">第六十二扇区</td><td colspan="2">第六十三扇区</td><td colspan="2">第六十四扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>7800h</td><td>79FFh</td><td>7A00h</td><td>7BFFh</td><td>7C00h</td><td>7DFFh</td><td>7E00h</td><td>7FFFh</td></tr><tr><td colspan="2">第六十五扇区</td><td colspan="2">第六十六扇区</td><td colspan="2">第六十七扇区</td><td colspan="2">第六十八扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>8000h</td><td>81FFh</td><td>8200h</td><td>83FFh</td><td>8400h</td><td>85FFh</td><td>8600h</td><td>87FFh</td></tr><tr><td colspan="2">第六十九扇区</td><td colspan="2">第七十扇区</td><td colspan="2">第七十一扇区</td><td colspan="2">第七十二扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>8800h</td><td>89FFh</td><td>8A00h</td><td>8BFFh</td><td>8C00h</td><td>8DFFh</td><td>8E00h</td><td>8FFFh</td></tr><tr><td colspan="2">第七十三扇区</td><td colspan="2">第七十四扇区</td><td colspan="2">第七十五扇区</td><td colspan="2">第七十六扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>9000h</td><td>91FFh</td><td>9200h</td><td>93FFh</td><td>9400h</td><td>95FFh</td><td>9600h</td><td>97FFh</td></tr><tr><td colspan="2">第七十七扇区</td><td colspan="2">第七十八扇区</td><td colspan="2">第七十九扇区</td><td colspan="2">第八十扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>9800h</td><td>99FFh</td><td>9A00h</td><td>9BFFh</td><td>9C00h</td><td>9DFFh</td><td>9E00h</td><td>9FFFH</td></tr><tr><td colspan="2">第八十一扇区</td><td colspan="2">第八十二扇区</td><td colspan="2">第八十三扇区</td><td colspan="2">第八十四扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>A000h</td><td>A1FFh</td><td>A200h</td><td>A3FFh</td><td>A400h</td><td>A5FFh</td><td>A600h</td><td>A7FFh</td></tr><tr><td colspan="2">第八十五扇区</td><td colspan="2">第八十六扇区</td><td colspan="2">第八十七扇区</td><td colspan="2">第八十八扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>A800h</td><td>A9FFh</td><td>AA00h</td><td>ABFFh</td><td>AC00h</td><td>ADFFh</td><td>AE00h</td><td>AFFFH</td></tr><tr><td colspan="2">第八十九扇区</td><td colspan="2">第九十扇区</td><td colspan="2">第九十一扇区</td><td colspan="2">第九十二扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>B000h</td><td>B1FFh</td><td>B200h</td><td>B3FFh</td><td>B400h</td><td>B5FFh</td><td>B600h</td><td>B7FFh</td></tr><tr><td colspan="2">第九十三扇区</td><td colspan="2">第九十四扇区</td><td colspan="2">第九十五扇区</td><td colspan="2">第九十六扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>B800h</td><td>B9FFh</td><td>BA00h</td><td>BBFFh</td><td>BC00h</td><td>BDFFh</td><td>BE00h</td><td>BFFFH</td></tr><tr><td colspan="2">第九十七扇区</td><td colspan="2">第九十八扇区</td><td colspan="2">第九十九扇区</td><td colspan="2">第一百扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>C000h</td><td>C1FFh</td><td>C200h</td><td>C3FFh</td><td>C400h</td><td>C5FFh</td><td>C600h</td><td>C7FFh</td></tr><tr><td colspan="2">第一百零一扇区</td><td colspan="2">第一百零二扇区</td><td colspan="2">第一百零三扇区</td><td colspan="2">第一百零四扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>C800h</td><td>C9FFh</td><td>CA00h</td><td>CBFFh</td><td>CC00h</td><td>CDFFh</td><td>CE00h</td><td>CFFFH</td></tr><tr><td colspan="2">第一百零五扇区</td><td colspan="2">第一百零六扇区</td><td colspan="2">第一百零七扇区</td><td colspan="2">第一百零八扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>D000h</td><td>D1FFh</td><td>D200h</td><td>D3FFh</td><td>D400h</td><td>D5FFh</td><td>D600h</td><td>D7FFh</td></tr><tr><td colspan="2">第一百零九扇区</td><td colspan="2">第一百一十扇区</td><td colspan="2">第一百一十一扇区</td><td colspan="2">第一百一十二扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>D800h</td><td>D9FFh</td><td>DA00h</td><td>DBFFh</td><td>DC00h</td><td>DDFFh</td><td>DE00h</td><td>DFFFH</td></tr><tr><td colspan="2">第一百一十三扇区</td><td colspan="2">第一百一十四扇区</td><td colspan="2">第一百一十五扇区</td><td colspan="2">第一百一十六扇区</td><td rowspan="9">每个扇区512字节建议同一次修改的数据放在同一扇区,不是同一次修改的数据放在不同的扇区,不必用满,当然可全用</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>E000h</td><td>E1FFh</td><td>E200h</td><td>E3FFh</td><td>E400h</td><td>E5FFh</td><td>E600h</td><td>E7FFh</td></tr><tr><td colspan="2">第一百一十七扇区</td><td colspan="2">第一百一十八扇区</td><td colspan="2">第一百一十九扇区</td><td colspan="2">第一百二十扇区</td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td></tr><tr><td>E800h</td><td>E9FFh</td><td>EA00h</td><td>EBFFh</td><td>EC00h</td><td>EDFFh</td><td>EE00h</td><td>EFFFH</td></tr><tr><td colspan="2">第一百二十一扇区</td><td colspan="2">第一百二十二扇区</td><td colspan="2"></td><td colspan="2"></td></tr><tr><td>起始地址</td><td>结束地址</td><td>起始地址</td><td>结束地址</td><td></td><td></td><td></td><td></td></tr><tr><td>F000h</td><td>F1FFh</td><td>F200h</td><td>F3FFh</td><td></td><td></td><td></td><td></td></tr></table>

# 9.3 IAP及EEPROM汇编简介

;用DATA还是EQU声明新增特殊功能寄存器地址要看你用的汇编器/编译器

<table><tr><td>IAP_DATA</td><td>DATA</td><td>0C2h;</td><td>或</td><td>IAP_DATA</td><td>EQU</td><td>0C2h</td></tr><tr><td>IAP_ADDRH</td><td>DATA</td><td>0C3h;</td><td>或</td><td>IAP_ADDRH</td><td>EQU</td><td>0C3h</td></tr><tr><td>IAP_ADDRL</td><td>DATA</td><td>0C4h;</td><td>或</td><td>IAP_ADDRL</td><td>EQU</td><td>0C4h</td></tr><tr><td>IAP_CMD</td><td>DATA</td><td>0C5h;</td><td>或</td><td>IAP_CMD</td><td>EQU</td><td>0C5h</td></tr><tr><td>IAP_TRIG</td><td>DATA</td><td>0C6h;</td><td>或</td><td>IAP_TRIG</td><td>EQU</td><td>0C6h</td></tr><tr><td>IAP_CONTR</td><td>DATA</td><td>0C7h;</td><td>或</td><td>IAP_CONTR</td><td>EQU</td><td>0C7h</td></tr></table>

;定义ISP/IAP命令及等待时间

<table><tr><td>ISP_IAP_BYTE_READ</td><td>EQU</td><td>1</td><td>;字节读</td></tr><tr><td>ISP_IAP_BYTEPROGRAM</td><td>EQU</td><td>2</td><td>;字节编程,前提是该字节是空,0FFh</td></tr><tr><td>ISP_IAP_SECTOR_ERASE</td><td>EQU</td><td>3</td><td>;扇区擦除,要某字节为空,要擦一扇区</td></tr><tr><td>WAIT_TIME</td><td>EQU</td><td>0</td><td>;设置等待时间,30MHz以下0,24M以下1,</td></tr></table>

;20MHz以下2,12M以下3,6M以下4,3M以下5,2M以下6,1M以下7,

;字节读,�也 � 程序存储空间结束地址的下一个地址

<table><tr><td>MOV</td><td>IAP_ADDRH,</td><td>#BYTE_ADDR_HIGH ;送地址高字节 地址需要改变时</td></tr><tr><td>MOV</td><td>IAP_ADDRL,</td><td>#BYTE_ADDR_LOW ;送地址低字节 才需重新送地址</td></tr><tr><td>MOV</td><td>IAP_CONTR,</td><td>#WAIT_TIME ;设置等待时间 此两句可以合成一句,</td></tr><tr><td>ORL</td><td>IAP_CONTR,</td><td>#10000000B ;允许ISP/IAP操作 并且只送一次就够了</td></tr><tr><td>MOV</td><td>IAP_CMD,</td><td>#ISP_IAP_BYTE_READ ;送字节读命令,现有A版本每次触发前需重新送命令。 ;在命令不需改变时,不需重新送命令</td></tr><tr><td>MOV</td><td>IAP_TRIG,</td><td>#5Ah ;先送5Ah,再送A5h到ISP/IAP触发寄存器,每次都需如此</td></tr><tr><td>MOV</td><td>IAP_TRIG,</td><td>#0A5h ;送完A5h后,ISP/IAP命令立即被触发起动</td></tr></table>

;CPU等待IAP动作完成后，才会继续执行程序。

<table><tr><td>NOP</td><td></td><td>;数据读出到IAP_DATA寄存器后，CPU继续执行程序</td></tr><tr><td>MOV</td><td>A,</td><td>;将读出的数据送往Acc</td></tr></table>

# ;以下语句可不用,只是出于安全考虑而已

MOV IAP_CONTR, #00000000B ;禁止ISP/IAP操作

MOV IAP_CMD, #00000000B ;去除ISP/IAP命令

;MOV IAP_TRIG, #00000000B ;防止ISP/IAP命令误触发

;MOV IAP_ADDRH, #0FFh ;送地址高字节单元为FF,指向非EEPROM区

;MOV IAP_ADDRL, #0FFh ;送地址低字节单元为FF,防止误操作

# ;字节编程，该字节为FFh/空时，可对其编程，否则不行,要先执行扇区擦除

MOV IAP_DATA, #ONE_DATA ;送字节编程数据到IAP_DATA,

;只有数据改变时才需重 新送

MOV IAP_ADDRH, #BYTE_ADDR_HIGH ;送地址高字节 地址需要改变时

MOV IAP_ADDRL, #BYTE_ADDR_LOW ;送地址低字节 才需重 新送地址

MOV IAP_CONTR, #WAIT_TIME ;设置等待时间 此两句可合成

ORL IAP_CONTR, #10000000B ;允许ISP/IAP操作 送一次就够了

MOV IAP_CMD, #ISP_IAP_BYTE_PROGRAM 

;送字节编程命令,现有A版本 每次触发前需重 新送命令。

;在命令不�需改�变时,不��需重 新送命令

MOV IAP_TRIG, #5Ah ;先送5Ah,再送A5h到ISP/IAP触发寄存器,每次都需如此

MOV IAP_TRIG, #0A5h ;送完A5h后，ISP/IAP命令立即被触发起动

# ;CPU等待IAP动作完成后，才会继续执行程序.

NOP ;字节编程成功后，CPU继续执行程序

# ;以下语句可不用,只是出于安全考虑而已

MOV IAP_CONTR, #00000000B ;禁止ISP/IAP操作

MOV IAP_CMD, #00000000B ;去除ISP/IAP命令

;MOV IAP_TRIG, #00000000B ;防止ISP/IAP命令误触发

;MOV IAP_ADDRH, #0FFh ;送地址高字节单元为FF,;指向非EEPROM区,防止误操作

;MOV IAP_ADDRL, #0FFh ;送地址低字节单元为FF,指向非EEPROM区,防止误操作

;扇区擦除，没有字节擦除，只有扇区擦除，512字节/扇区,每个扇区用得越少越方便

;如果要对某个扇区进行擦除，而其中有些字节的内容需要保留，则需将其先读到单片机

;内部的RAM中保存，再将该扇区擦除，然后将须保留的数据写回该扇区，所以每个扇区

;中用的字节数越少越好，操作起来越灵活方便

;扇区中任意一个字节的地址都是该扇区的地址,无需求出首地址.

MOV IAP_ADDRH, #SECTOR_FIRST_BYTE_ADDR_HIGH ;送扇区起始地址高字节

MOV IAP_ADDRL, #SECTOR_FIRST_BYTE_ADDR_LOW ;送扇区起始地址低字节

;地址需要改变时才需重 新送地址

MOV IAP_CONTR, #WAIT_TIME ;设置等待时间 此两句可以合

ORL IAP_CONTR, #10000000B ;允许ISP/IAP 送一次就够了

MOV IAP_CMD, #ISP_IAP_SECTOR_ERASE 

;送扇区擦除命令,�现有A��版本 每次�触发前��需重 新送命令。

;在命令不�需改�变时,不��需重 新送命令

MOV IAP_TRIG, #5Ah 

;先送5Ah,再送A5h到ISP/IAP触发寄存器,每次都需如此

MOV IAP_TRIG, #0A5h ;送完A5h后，ISP/IAP命令立即被触发起动

;CPU等待IAP动作完成后，才会继续执行程序.

NOP ;扇区擦除成功后，CPU继续执行程序

;以下语句可不用,只是出于安全考虑而已

MOV IAP_CONTR, #00000000B ;禁止ISP/IAP操作

MOV IAP_CMD, #00000000B ;去除ISP/IAP命令

;MOV IAP_TRIG, #00000000B ;防止ISP/IAP命令误触发

;MOV IAP_ADDRH, #0FFh ;送地址高字节单元为FF,指向非EEPROM区

;MOV IAP_ADDRL, #0FFh ;送地址低字节单元为FF,防止误操作

小常识： (STC单片机的Data Flash 当EEPROM功能使用)

3个基本命令----字节读，字节编程，扇区擦除

字节编程：将“1”写成“1”或 $^ { \dprime } { } ^ { \dprime } { } ^ { \dprime }$ ，将 $^ { \dag } 0 ^ { \dag }$ 写成 $^ { \dprime } { } ^ { \dprime } { } ^ { \dprime }$ 。如果某字节是FFH,才可进行字节编程。如果该字节不是F F H � �将“0”变为“1”。

扇区擦除：只有“扇区擦除”才可能将“0”擦除为“1”。

# 大建议：

1.同一次修改的数据放在同一扇区中，不是同一次修改的数据放在另外的扇区,就不须读出保护。

2.如果一个扇区只用一个字节，那就是真正的EEPROM,STC单片机的Data Flash比外部EEPROM要快很多，读一个字节/编程一个字节大概是2 �钟/55�

3.如果在一个扇区中存放了大量的数据，某次只需要修改其中的一个字节或一部分字节时，则另外的不需要修改的数据须先读出放在STC单片机的RAM中，然后擦除整个扇区，再将需要保留的数据和需修改的数据�按字节�逐字节写回该扇区中( �续字节写命令 �时每个扇区使用的字节数是使用的越少越方便(不需读出一大堆需保留数据)。

# 常问的问题：

1：IAP指令完成后，地址是否会自动“加1”或“减1”？

答：不会

2：送5A和A5触发后，下一次IAP命令是否还需要送5A和A5触发？

答：是，一定要。

# 9.4 EEPROM测试程序(C和汇编)

# 9.4.1 EEPROM测试程序(不用串口送出数据)(C和汇编)

# 1. C程序：

;STC15系列单片机EEPROM/IAP 功能测试程序演示

/*- -*/ 

/* --- STC MCU Limited. - -*/ 

/* --- 演示STC 15 系列单片机 EEPROM/IAP功能-- -*/

/* --- 研发顾问QQ：800003751- -*/

/* --- Fax: 86-755-82905966 - -*/ 

/* --- Tel: 86-755-82948412 --*/ 

/* --- Web: www.STCMCU.com -*/ 

/* 如果要在程序中使用或在文章中引用该程序， *

/* 请在程序中或文章中注明使用了STC的资料及程序 --*/

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可-----*/

/* ----*/ 

//假定测试芯片的工作频率为18.432MHz

void IapIdle(); 

BYTE IapReadByte(WORD addr); 

#include "reg51.h" 

#include "intrins.h" 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

//-- 

sfr IAP_DATA $\qquad = \quad 0 \mathbf { x } { \mathbf { C } } 2$ ; //IAP数据寄存器

sfr IAP_ADDRH $\qquad = \quad 0 \mathbf { x } { \mathbf { C } } 3$ ; //IAP地址寄存器高字节

sfr IAP_ADDRL $= \ \mathrm { 0 x C 4 }$ ; //IAP地址寄存器低字节

sfr IAP_CMD = 0xC5; //IAP命令寄存器

sfr IAP_TRIG = 0xC6; //IAP命令触发寄存器

sfr IAP_CONTR = 0xC7; //IAP控制寄存器

#define CMD_IDLE 0 //空闲模式

#define CMD_READ 1 //IAP字节读命令

#define CMD_PROGRAM 2 //IAP字节编程命令

#define CMD_ERASE 3 //IAP扇区擦除命令

//#define ENABLE_IAP 0x80 //if SYSCLK<30MHz 

//#define ENABLE_IAP 0x81 //if SYSCLK<24MHz 

#define ENABLE_IAP 0x82 //if SYSCLK<20MHz 

//#define ENABLE_IAP 0x83 //if SYSCLK<12MHz 

//#define ENABLE_IAP 0x84 //if SYSCLK<6MHz 

```txt
//define ENABLE_IAP 0x85 //if SYSCLK<3MHz  
//define ENABLE_IAP 0x86 //if SYSCLK<2MHz  
//define ENABLE_IAP 0x87 //if SYSCLK<1MHz 
```


//测试地址


```txt
define IAP_ADDRESS 0x0400 
```

```txt
void Delay(Byte n);  
void IapIdle();  
BYTE IapReadByte(WORD addr);  
void IapProgramByte(WORD addr, BYTE dat);  
void IapEraseSector(WORD addr); 
```

```c
void main()  
{  
    WORD i;  
    P1 = 0xffe; //1111,1110系统OK  
    Delay(10); //延时  
    IapEraseSector(IAP_ADDRESS); //扇区擦除  
    for (i=0; i<512; i++) {  
        if (IapReadByte(IAP_ADDRESS+i) != 0xff) {  
            goto Error; //如果出错，则退出  
        }  
        P1 = 0xfc; //1111,1100擦除成功  
        Delay(10); //延时  
        for (i=0; i<512; i++) {  
            IapProgramByte(IAP_ADDRESS+i, BYTE)i);  
        }  
        P1 = 0xf8; //1111,1000编程完成  
        Delay(10); //延时  
        for (i=0; i<512; i++) {  
            if (IapReadByte(IAP_ADDRESS+i) != (BYTE)i) {  
                goto Error; //如果校验错误，则退出  
            }  
        }  
        P1 = 0xf0; //1111,0000测试完成  
        while (1);  
    }  
}
```

void Delay(BYTE n)  
{WORD x;while (n--){ $\mathrm{x} = 0$ while $(++\mathrm{x})$ ：}  
1/\*关闭IAP\*/void IapIdle()IAP_CONTR $= 0$ //关闭IAP功能IAP_CMD $= 0$ //清除命令寄存器IAP_TRIG $= 0$ //清除触发寄存器IAP_ADDRH $= 0\mathrm{x}80$ //将地址设置到非IAP区域IAP_ADDRL $= 0$ ：  
1/\*从ISP/IAP/EEPROM区域读取一字节\*/BYTE IapReadByte(WORD addr)  
{BYTE dat; //数据缓冲区IAP_CONTR $=$ ENABLE_IAP; //使能IAPIAP_CMD $=$ CMD_READ; //设置IAP命令IAP_ADDRL $=$ addr; //设置IAP低地址IAP_ADDRH $=$ addr>>8; //设置IAP高地址IAP_TRIG $= 0\mathrm{x}5\mathrm{a}$ //写触发命令(0x5a)IAP_TRIG $= 0\mathrm{xa}5$ //写触发命令(0xa5)_nop_；dat $=$ IAP_DATA; //读ISP/IAP/EEPROM操作完成IapIdle(); //关闭IAP功能return dat; //返回

```txt
\*/ 
```

写一字节数据到ISP/IAP/EEPROM区域

```txt
\* 
```

```txt
void IapProgramByte(WORD addr, BYTE dat) { 
```

```txt
IAP_CONTR = ENABLE_IAP; 
```

```txt
//使能IAP
```

```txt
IAP_CMD = CMD-ProGRAM; 
```

```txt
//设置IAP命令
```

```txt
IAP_ADDRL = addr; 
```

```txt
//设置IAP低地址
```

```erb
IAP_ADDRH = addr >> 8; 
```

```txt
//设置IAP高地址
```

```txt
IAP_DATA = dat; 
```

```txt
//写ISP/IAP/EEPROM数据
```

IAP_TRIG $= 0\mathrm{x}5\mathrm{a}$ 

```javascript
//写触发命令(0x5a)
```

IAP_TRIG $= 0\mathrm{xa}5$ 

```txt
//写触发命令(0xa5)
```

```txt
\_nop\_(); 
```

```txt
//等待ISP/IAP/EEPROM操作完成
```

```javascript
IapIdle(); 
```

```txt
\*/ 
```

扇区擦除

```txt
\* 
```

```txt
void IapEraseSector(WORD addr) { 
```

```txt
IAP_CONTR = ENABLE_IAP; 
```

```txt
IAP_CMD = CMD_ERASE; 
```

```txt
IAP_ADDRL = addr; 
```

```erb
IAP_ADDRH = addr >> 8; 
```

```txt
IAP_TRIG = 0x5a; 
```

```txt
IAP_TRIG = 0xa5; 
```

```txt
\_nop\_; 
```

```javascript
IapIdle(); 
```

```txt
} 
```

```txt
//使能IAP
```

```txt
//设置IAP命令
```

```txt
//设置IAP低地址
```

```txt
//设置IAP高地址
```

```javascript
//写触发命令(0x5a)
```

```txt
//写触发命令(0xa5)
```

```txt
//等待ISP/IAP/EEPROM操作完成
```

# 2. 汇编程序：

;STC15系列单片机EEPROM/IAP 功能测试程序演示

/*- -*/ 

/* --- STC MCU Limited. - --*/ 

/* --- 演示STC 15 系列单片机 EEPROM/IAP功能-- --*/

/* --- 研发顾问QQ：800003751- -*/

/* --- Fax: 86-755-82905966 - --*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用或在文章中引用该程序， -*/

/* 请在程序中或文章中注明使用了STC的资料及程序 --*/

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可-----*/

/*- -*/ 

//假定测试芯片的工作频率为18.432MHz

IAP_DATA EQU 0C2H //IAP数据寄存器

IAP_ADDRH EQU 0C3H //IAP地址寄存器高字

IAP_ADDRL EQU 0C4H //IAP地址寄存器低字

IAP_CMD EQU 0C5H //IAP命令寄存器

IAP_TRIG EQU 0C6H //IAP命令触发寄存器

IAP_CONTR EQU 0C7H //IAP控制寄存器

CMD_IDLE EQU 0 //空闲模式

CMD_READ EQU 1 //IAP字节读命令

CMD_PROGRAM EQU 2 //IAP字节编程命令

CMD_ERASE EQU 3 //IAP扇区擦除命令

;ENABLE_IAP EQU 80H //if SYSCLK<30MHz 

;ENABLE_IAP EQU 81H //if SYSCLK<24MHz 

ENABLE_IAP EQU 82H //if SYSCLK<20MHz 

;ENABLE_IAP EQU 83H //if SYSCLK<12MHz 

;ENABLE_IAP EQU 84H //if SYSCLK<6MHz 

;ENABLE_IAP EQU 85H //if SYSCLK<3MHz 

;ENABLE_IAP EQU 86H //if SYSCLK<2MHz 

;ENABLE_IAP EQU 87H //if SYSCLK<1MHz 

//测试地址

IAP_ADDRESS EQU 0400H 

//- 

ORG 0000H 

LJMP MAIN 

ORG 0100H 

MAIN: 

MOV P1, #0FEH //1111,1110 系统OK

LCALL DELAY //延时

<table><tr><td>MOV</td><td>DPTR,</td><td>#IAP_ADDRESS</td><td>//设置ISP/IAP/EEPROM地址</td></tr><tr><td>LCALL</td><td>IAP_ERASE</td><td></td><td>//扇区擦除</td></tr><tr><td>MOV</td><td>DPTR,</td><td>#IAP_ADDRESS</td><td>//设置ISP/IAP/EEPROM地址</td></tr><tr><td>MOV</td><td>R0,</td><td>#0</td><td>//检测512字节</td></tr><tr><td>MOV</td><td>R1,</td><td>#2</td><td></td></tr><tr><td>CHECK1:</td><td></td><td></td><td>//检测是否擦除成功(全FF检测</td></tr><tr><td>LCALL</td><td>IAP_READ</td><td></td><td>//读IAP数据</td></tr><tr><td>CJNE</td><td>A,</td><td>#0FFH, ERROR</td><td>//如果出错,则退出</td></tr><tr><td>INC</td><td>DPTR</td><td></td><td>//IAP地址+1</td></tr><tr><td>DJNZ</td><td>R0,</td><td>CHECK1</td><td></td></tr><tr><td>DJNZ</td><td>R1,</td><td>CHECK1</td><td></td></tr><tr><td>MOV</td><td>P1,</td><td>#0FCH</td><td>//1111,1100擦除成功</td></tr><tr><td>LCALL</td><td>DELAY</td><td></td><td>//延时</td></tr><tr><td>MOV</td><td>DPTR,</td><td>#IAP_ADDRESS</td><td>//设置ISP/IAP/EEPROM地址</td></tr><tr><td>MOV</td><td>R0,</td><td>#0</td><td>//编程512字节</td></tr><tr><td>MOV</td><td>R1,</td><td>#2</td><td></td></tr><tr><td>MOV</td><td>R2,</td><td>#0</td><td></td></tr><tr><td>NEXT:</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>A,</td><td>R2</td><td>//准备数据</td></tr><tr><td>LCALL</td><td>IAP PROGRAM</td><td></td><td>//字节编程</td></tr><tr><td>INC</td><td>DPTR</td><td></td><td>//IAP地址+1</td></tr><tr><td>INC</td><td>R2</td><td></td><td>//修改测试数据</td></tr><tr><td>DJNZ</td><td>R0,</td><td>NEXT</td><td></td></tr><tr><td>DJNZ</td><td>R1,</td><td>NEXT</td><td></td></tr><tr><td>MOV</td><td>P1,</td><td>#0F8H</td><td>//1111,1000编程完成</td></tr><tr><td>LCALL</td><td>DELAY</td><td></td><td>//延时</td></tr><tr><td>MOV</td><td>DPTR,</td><td>#IAP_ADDRESS</td><td>//设置ISP/IAP/EEPROM地址</td></tr><tr><td>MOV</td><td>R0,</td><td>#0</td><td>//校验512字节</td></tr><tr><td>MOV</td><td>R1,</td><td>#2</td><td></td></tr><tr><td>MOV</td><td>R2,</td><td>#0</td><td></td></tr><tr><td>CHECK2:</td><td></td><td></td><td></td></tr><tr><td>LCALL</td><td>IAP_READ</td><td></td><td>//读IAP数据</td></tr><tr><td>CJNE</td><td>A,</td><td>2, ERROR</td><td>//如果出错,则退出</td></tr><tr><td>INC</td><td>DPTR</td><td></td><td>//IAP地址+1</td></tr><tr><td>INC</td><td>R2</td><td></td><td></td></tr><tr><td>DJNZ</td><td>R0,</td><td>CHECK2</td><td></td></tr><tr><td>DJNZ</td><td>R1,</td><td>CHECK2</td><td></td></tr><tr><td>MOV</td><td>P1,</td><td>#0F0H</td><td>//1111,0000测试完成</td></tr><tr><td>SJMP</td><td>$</td><td></td><td></td></tr></table>

# ERROR:

MOV P0, R0 

MOV P2, R1 

MOV P3, R2 

CLR P1.7 //0xxx,xxxx IAP 测试失败

SJMP $ 

/*- 

# 软件延时

-*/ 

# DELAY:

CLR A 

MOV R0, A 

MOV R1, A 

MOV R2, #20H 

# DELAY1:

DJNZ R0, DELAY1 

DJNZ R1, DELAY1 

DJNZ R2, DELAY1 

RET 

/* 

# 关闭IAP

--*/ 

# IAP_IDLE:

MOV IAP_CONTR, #0 //关闭IAP功能

MOV IAP_CMD, #0 //清除命令寄存器

MOV IAP_TRIG, #0 //清除触发寄存器

MOV IAP_ADDRH, #80H //将地址设置到非IAP区域

MOV IAP_ADDRL, #0 

RET 

/* 

# 从ISP/IAP/EEPROM区域读取一字节

* 

# IAP_READ:

MOV IAP_CONTR, #ENABLE_IAP //使能IAP

MOV IAP_CMD, #CMD_READ //设置IAP命令

MOV IAP_ADDRL,DPL //设置IAP低地址

MOV IAP_ADDRH, DPH //设置IAP高地址

MOV IAP_TRIG, #5AH //写触发命令(0x5a)

MOV IAP_TRIG, #0A5H //写触发命令(0xa5)

NOP //等待ISP/IAP/EEPR

MOV A, IAP_DATA //度IAP数据

LCALL IAP_IDLE 

RET 

//关闭IAP功能

/* 

写一字节数据到ISP/IAP/EEPROM区域

-*/ 

IAP_PROGRAM: 

MOV IAP_CONTR, 

#ENABLE_IAP 

//使能IAP

MOV IAP_CMD, 

#CMD_PROGRAM 

//设置IAP命令

MOV IAP_ADDRL, 

DPL 

//设置IAP低地址

MOV IAP_ADDRH, 

DPH 

//设置IAP高地址

MOV IAP_DATA, 

A 

//写IAP数据

MOV IAP_TRIG, 

#5AH 

//写触发命令(0x5a)

MOV IAP_TRIG, 

#0A5H 

//写触发命令(0xa5)

NOP 

//等待ISP/IAP/EEPROM操作完成

LCALL IAP_IDLE 

//关闭IAP功能

RET 

/* 

扇区擦除

-*/ 

IAP_ERASE: 

MOV IAP_CONTR, 

#ENABLE_IAP 

MOV IAP_CMD, 

#CMD_ERASE 

MOV IAP_ADDRL, 

DPL 

MOV IAP_ADDRH, 

DPH 

MOV IAP_TRIG, 

#5AH 

MOV IAP_TRIG, 

#0A5H 

NOP 

LCALL IAP_IDLE 

RET 

END 

//使能IAP

//设置IAP命令

//设置IAP低地址

//设置IAP高地址

//写触发命令(0x5a)

//写触发命令(0xa5)

//等待ISP/IAP/EEPROM操作完成

//关闭IAP功能

# 9.4.2 EEPROM测试程序(使用串口送出数据)(C和汇编)

# 1. C程序：

;STC15系列单片机EEPROM/IAP 功能测试程序演示

/* */ 

/* --- STC MCU Limited. - -*/ 

/* --- 演示STC 15 系列单片机 EEPROM/IAP功能-- --*/

/* --- 研发顾问QQ：800003751- -*/

/* --- Fax: 86-755-82905966 -- -*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用或在文章中引用该程序， */

/* 请在程序中或文章中注明使用了STC的资料及程序 -*/

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可-----*/

/* * 

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

//- 

sfr IAP_DATA $\qquad = \quad 0 \mathbf { x } { \mathbf { C } } 2$ ; //IAP数据寄存器

sfr IAP_ADDRH = 0xC3; //IAP地址寄存器高字节

sfr IAP_ADDRL = 0xC4; //IAP地址寄存器低字节

sfr IAP_CMD = 0xC5; //IAP命令寄存器

sfr IAP_TRIG = 0xC6; //IAP命令触发寄存器

sfr IAP_CONTR = 0xC7; //IAP控制寄存器

#define CMD_IDLE 0 //空闲模式

#define CMD_READ 1 //IAP字节读命令

#define CMD_PROGRAM 2 //IAP字节编程命令

#define CMD_ERASE 3 //IAP扇区擦除命令

#define URMD 0 //0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

sfr T2H 0xd6; //定时器2高8位

sfr T2L 0xd7; //定时器2低8位

sfr AUXR = 0x8e; //辅助寄存器

<table><tr><td>//#define ENABLE_IAP</td><td>0x80</td><td>//if SYSCLK&lt;30MHz</td></tr><tr><td>//#define ENABLE_IAP</td><td>0x81</td><td>//if SYSCLK&lt;24MHz</td></tr><tr><td>#define ENABLE_IAP</td><td>0x82</td><td>//if SYSCLK&lt;20MHz</td></tr><tr><td>//#define ENABLE_IAP</td><td>0x83</td><td>//if SYSCLK&lt;12MHz</td></tr><tr><td>//#define ENABLE_IAP</td><td>0x84</td><td>//if SYSCLK&lt;6MHz</td></tr><tr><td>//#define ENABLE_IAP</td><td>0x85</td><td>//if SYSCLK&lt;3MHz</td></tr><tr><td>//#define ENABLE_IAP</td><td>0x86</td><td>//if SYSCLK&lt;2MHz</td></tr><tr><td>//#define ENABLE_IAP</td><td>0x87</td><td>//if SYSCLK&lt;1MHz</td></tr></table>

//测试地址

#define IAP_ADDRESS 0x0400 

void Delay(BYTE n); 

void IapIdle(); 

BYTE IapReadByte(WORD addr); 

void IapProgramByte(WORD addr, BYTE dat); 

void IapEraseSector(WORD addr); 

void InitUart(); 

BYTE SendData(BYTE dat); 

void main()   
{ WORD i; P1 $= 0$ xfe; //1111,1110系统OK InitUart(); //初始化串口 Delay(10); //延时 IapEraseSector(IAP_ADDRESS); //扇区擦除 for $(\mathrm{i} = 0;\mathrm{i} <   512;\mathrm{i} + + )$ //检测是否擦除成功(全FF检测) { if (SendData(IapReadByte(IAP_ADDRESS+i)) != 0xff) goto Error; //如果出错，则退出 } P1 $= 0$ xfc; //1111,1100擦除成功 Delay(10); //延时 for $(\mathrm{i} = 0;\mathrm{i} <   512;\mathrm{i} + + )$ //编程512字节 { IapProgramByte(IAP_ADDRESS+i, (BYTE)i); } P1 $= 0$ xf8; //1111,1000编程完成 Delay(10); //延时 for $(\mathrm{i} = 0;\mathrm{i} <   512;\mathrm{i} + + )$ //校验512字节 { if (SendData(IapReadByte(IAP_ADDRESS+i)) != (BYTE)i) goto Error; //如果校验错误，则退出 } P1 $= 0$ xf0; //1111,0000测试完成 while (1);

Error: P1 $\& = 0\mathrm{x}7\mathrm{f};$ //0xxx,xxxxIAP操作失败 while(1);   
}   
/\*   
软件延时 /\*   
void Delay(BYTE n)   
{ WORD x; while (n--） { $\mathrm{x} = 0$ . while $(++\mathrm{x})$ ：   
}   
/\*   
关闭IAP /\*   
void IapIdle() { IAP_CONTR $= 0;$ //关闭IAP功能 IAP_CMD $= 0;$ //清除命令寄存器 IAP_TRIG $= 0;$ //清除触发寄存器 IAP_ADDRH $= 0\mathrm{x}80;$ //将地址设置到非IAP区域 IAP_ADDRL $= 0;$ }   
/\*   
从ISP/IAP/EEPROM区域读取一字节 /\*   
BYTE IapReadByte(WORD addr) { BYTE dat; //数据缓冲区 IAP_CONTR $\equiv$ ENABLE_IAP; //使能IAP IAP_CMD $\equiv$ CMD_READ; //设置IAP命令 IAP_ADDRL $\equiv$ addr; //设置IAP低地址 IAP_ADDRH $\equiv$ addr>>8; //设置IAP高地址 IAP_TRIG $\equiv$ 0x5a; //写触发命令(0x5a) IAP_TRIG $\equiv$ 0xa5; //写触发命令(0xa5) _nop_(); $\mathrm{dat} = \mathrm{IAP\_DATA};$ //等待ISP/IAP/EEPROM操作完成 IapIdle(); //关闭IAP功能 return dat; //返回

```txt
\* 
```

写一字节数据到ISP/IAP/EEPROM区域

```txt
\* 
```

```txt
void IapProgramByte(WORD addr, BYTE dat) { 
```

```txt
IAP_CONTR = ENABLE_IAP; 
```

```txt
IAP_CMD = CMD_PROGRAM; 
```

```txt
IAP_ADDRL = addr; 
```

```erb
IAP_ADDRH = addr >> 8; 
```

```txt
IAP_DATA = dat; 
```

```txt
IAP_TRIG = 0x5a; 
```

```txt
IAP_TRIG = 0xa5; 
```

```txt
\_nop\_(); 
```

```javascript
IapIdle(); 
```

```txt
} 
```

```txt
\* 
```

扇区擦除

```txt
\* 
```

```txt
void IapEraseSector(WORD addr) 
```

```txt
{ 
```

```txt
IAP_CONTR = ENABLE_IAP; 
```

```txt
IAP_CMD = CMD_ERASE; 
```

```txt
IAP_ADDRL = addr; 
```

```erb
IAP_ADDRH = addr >> 8; 
```

```txt
IAP_TRIG = 0x5a; 
```

```txt
IAP_TRIG = 0xa5; 
```

```txt
_nop_(); 
```

```javascript
IapIdle(); 
```

```txt
} 
```

```txt
/* 
```

初始化串口

```txt
\* 
```

```txt
void InitUart() 
```

```txt
{ 
```

```txt
SCON 0x5a; 
```

if URMD $= =$ 0 

```txt
T2L 0xd8; 
```

```txt
T2H 0xff; 
```

```txt
AUXR 0x14; 
```

AUXR $| =$ 0x01; 

```txt
elif URMD 1 
```

```txt
AUXR 0x40; 
```

```txt
TMOD 0x00; 
```

```txt
TL1 0xd8; 
```

```txt
TH1 0xff; 
```

```txt
TR1 1; 
```

```txt
//使能IAP
```

```txt
//设置IAP命令
```

```txt
//设置IAP低地址
```

```txt
//设置IAP高地址
```

```txt
//写ISP/IAP/EEPROM数据
```

```javascript
//写触发命令(0x5a)
```

```txt
//写触发命令(0xa5)
```

```txt
//等待ISP/IAP/EEPROM操作完成
```

```txt
//使能IAP
```

```txt
//设置IAP命令
```

```txt
//设置IAP低地址
```

```txt
//设置IAP高地址
```

```javascript
//写触发命令(0x5a)
```

```txt
//写触发命令(0xa5)
```

```txt
//等待ISP/IAP/EEPROM操作完成
```

```txt
//设置串口为8位可变波特率
```

```txt
//设置波特率重装值
```

```txt
//115200 bps(65536-18432000/4/115200) 
```

```txt
//T2为1T模式，并启动定时器2
```

```txt
//选择定时器2为串口1的波特率发生器
```

```txt
//定时器1为1T模式
```

```txt
//定时器1为模式0(16位自动重载)
```

```txt
//设置波特率重装值
```

```txt
//115200 bps(65536-18432000/4/115200) 
```

```txt
//定时器1开始启动
```

#else 

TMOD $=$ 0x20; 

//设置定时器1为8位自动重装载模式

AUXR = 0x40; 

//定时器1为1T模式

TH1 = TL1 = 0xfb; 

//115200 bps(256 - 18432000/32/115200) 

TR1 1; 

#endif 

} 

/*-- 

发送串口数据

-*/ 

BYTE SendData(BYTE dat) 

{ 

while (!TI); 

//等待前一个数据发送完成

$\mathrm { T I } = 0$ ; 

//清除发送标志

SBUF = dat; 

//发送当前数据

return dat; } 

# 2. 汇编程序：

;STC15系列单片机EEPROM/IAP 功能测试程序演示

/* */ 

/* --- STC MCU Limited. ---- -*/ 

/* --- 演示STC 15 系列单片机 EEPROM/IAP功能- *

/* --- 研发顾问QQ：800003751- */

/* --- Fax: 86-755-82905966 -- -*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用或在文章中引用该程序， *

/* 请在程序中或文章中注明使用了STC的资料及程序 -*/

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可-----*/

/*- -*/ 

//假定测试芯片的工作频率为18.432MHz

#define URMD 0 

//0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

T2H DATA 0 

//定时器2高8位

T2L DATA 0 

//定时器2低8位

AUXR DATA 08 

//辅助寄存器

IAP_DATA 

EQU 

0C2H 

//IAP数据寄存器

IAP_ADDRH 

EQU 

0C3H 

//IAP地址寄存器高字

<table><tr><td>IAP_ADDRL</td><td>EQU</td><td>0C4H</td><td>//IAP地址寄存器低字</td></tr><tr><td>IAP_CMD</td><td>EQU</td><td>0C5H</td><td>//IAP命令寄存器</td></tr><tr><td>IAP_TRIG</td><td>EQU</td><td>0C6H</td><td>//IAP命令触发寄存器</td></tr><tr><td>IAP_CONTR</td><td>EQU</td><td>0C7H</td><td>//IAP控制寄存器</td></tr><tr><td>CMD_IDLE</td><td>EQU</td><td>0</td><td>//空闲模式</td></tr><tr><td>CMD_READ</td><td>EQU</td><td>1</td><td>//IAP字节读命令</td></tr><tr><td>CMD-ProGRAM</td><td>EQU</td><td>2</td><td>//IAP字节编程命令</td></tr><tr><td>CMD_ERASE</td><td>EQU</td><td>3</td><td>//IAP扇区擦除命令</td></tr><tr><td>;ENABLE_IAP</td><td>EQU</td><td>80H</td><td>//if SYSCLK&lt;30MHz</td></tr><tr><td>;ENABLE_IAP</td><td>EQU</td><td>81H</td><td>//if SYSCLK&lt;24MHz</td></tr><tr><td>ENABLE_IAP</td><td>EQU</td><td>82H</td><td>//if SYSCLK&lt;20MHz</td></tr><tr><td>;ENABLE_IAP</td><td>EQU</td><td>83H</td><td>//if SYSCLK&lt;12MHz</td></tr><tr><td>;ENABLE_IAP</td><td>EQU</td><td>84H</td><td>//if SYSCLK&lt;6MHz</td></tr><tr><td>;ENABLE_IAP</td><td>EQU</td><td>85H</td><td>//if SYSCLK&lt;3MHz</td></tr><tr><td>;ENABLE_IAP</td><td>EQU</td><td>86H</td><td>//if SYSCLK&lt;2MHz</td></tr><tr><td>;ENABLE_IAP</td><td>EQU</td><td>87H</td><td>//if SYSCLK&lt;1MHz</td></tr></table>

# //测试地址

IAP_ADDRESS EQU 0400H 

ORG 0000H 

LJMP MAIN 

ORG 0100H 

MAIN: 

<table><tr><td>LCALL</td><td>INIT_UART</td><td>//初始化串口</td></tr><tr><td>MOV</td><td>P1, #0FEH</td><td>//1111,1110 系统OK</td></tr><tr><td>LCALL</td><td>DELAY</td><td>//延时</td></tr></table>

<table><tr><td>MOV</td><td>DPTR, #IAP_ADDRESS</td><td>//设置ISP/IAP/EEPROM地址</td></tr><tr><td>LCALL</td><td>IAP_ERASE</td><td>//扇区擦除</td></tr></table>

<table><tr><td>MOV</td><td>DPTR,</td><td>#IAP_ADDRESS</td><td>//设置ISP/IAP/EEPROM地址</td></tr><tr><td>MOV</td><td>R0,</td><td>#0</td><td>//检测512字节</td></tr></table>

CHECK1: 

LCALL IAP_READ //读IAP数据

LCALL SEND_DATA 

<table><tr><td>CJNE</td><td>A,</td><td>#0FFH,ERROR</td><td>//如果出错,则退出</td></tr><tr><td>INC</td><td>DPTR</td><td></td><td>//IAP地址+1</td></tr></table>

DJNZ R0, CHECK1 

DJNZ R1, CHECK1 

MOV P1, LCALL DELA 

<table><tr><td>MOV</td><td>DPTR,</td><td>#IAP_ADDRESS</td><td>//设置ISP/IAP/EEPROM地址</td></tr></table>

<table><tr><td>MOV</td><td>R0,</td><td>#0</td><td>//编程512字节</td></tr><tr><td>MOV</td><td>R1,</td><td>#2</td><td></td></tr><tr><td>MOV</td><td>R2,</td><td>#0</td><td></td></tr><tr><td>NEXT:</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>A,R2</td><td></td><td>//准备数据</td></tr><tr><td>LCALL</td><td>IAP PROGRAM</td><td></td><td>//字节编程</td></tr><tr><td>INC</td><td>DPTR</td><td></td><td>//IAP地址+1</td></tr><tr><td>INC</td><td>R2</td><td></td><td>//修改测试数据</td></tr><tr><td>DJNZ</td><td>R0,</td><td>NEXT</td><td></td></tr><tr><td>DJNZ</td><td>R1,</td><td>NEXT</td><td></td></tr><tr><td>;</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>P1,</td><td>#0F8H</td><td>//1111,1000编程完成</td></tr><tr><td>LCALL</td><td>DELAY</td><td></td><td>//延时</td></tr><tr><td>;</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>DPTR,</td><td>#IAP_ADDRESS</td><td>//设置ISP/IAP/EEPROM地址</td></tr><tr><td>MOV</td><td>R0,</td><td>#0</td><td>//校验512字节</td></tr><tr><td>MOV</td><td>R1,</td><td>#2</td><td></td></tr><tr><td>MOV</td><td>R2,</td><td>#0</td><td></td></tr><tr><td>CHECK2:</td><td></td><td></td><td></td></tr><tr><td>LCALL</td><td>IAP_READ</td><td></td><td>//读IAP数据</td></tr><tr><td>LCALL</td><td>SEND_DATA</td><td></td><td></td></tr><tr><td>CJNE</td><td>A,</td><td>2,</td><td>ERROR //如果出错,则退出</td></tr><tr><td>INC</td><td>DPTR</td><td></td><td>//IAP地址+1</td></tr><tr><td>INC</td><td>R2</td><td></td><td></td></tr><tr><td>DJNZ</td><td>R0,</td><td>CHECK2</td><td></td></tr><tr><td>DJNZ</td><td>R1,</td><td>CHECK2</td><td></td></tr><tr><td>;</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>P1,</td><td>#0F0H</td><td>//1111,0000测试完成</td></tr><tr><td>SJMP</td><td>$</td><td></td><td></td></tr><tr><td>;</td><td></td><td></td><td></td></tr><tr><td>ERROR:</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>P0,</td><td>R0</td><td></td></tr><tr><td>MOV</td><td>P2,</td><td>R1</td><td></td></tr><tr><td>MOV</td><td>P3,</td><td>R2</td><td></td></tr><tr><td>CLR</td><td>P1.7</td><td></td><td>//0xxx,xxxx IAP 测试失败</td></tr><tr><td>SJMP</td><td>$</td><td></td><td></td></tr><tr><td>/*</td><td></td><td></td><td></td></tr><tr><td>软件延时</td><td></td><td></td><td></td></tr><tr><td>*</td><td></td><td></td><td></td></tr><tr><td>DELAY:</td><td></td><td></td><td></td></tr><tr><td>CLR</td><td>A</td><td></td><td></td></tr><tr><td>MOV</td><td>R0,</td><td>A</td><td></td></tr><tr><td>MOV</td><td>R1,</td><td>A</td><td></td></tr><tr><td>MOV</td><td>R2,</td><td>#20H</td><td></td></tr><tr><td>DELAY1:</td><td></td><td></td><td></td></tr><tr><td>DJNZ</td><td>R0,</td><td>DELAY1</td><td></td></tr><tr><td>DJNZ</td><td>R1,</td><td>DELAY1</td><td></td></tr><tr><td>DJNZ</td><td>R2,</td><td>DELAY1</td><td></td></tr><tr><td>RET</td><td></td><td></td><td></td></tr></table>

/*-- 

关闭IAP

-*/ 

IAP_IDLE: 

MOV IAP_CONTR, #0 

MOV IAP_CMD, #0 

MOV IAP_TRIG, #0 

MOV IAP_ADDRH, #80H 

MOV IAP_ADDRL, #0 

RET 

//关闭IAP功能

//清除命令寄存器

//清除触发寄存器

//将地址设置到非IAP区域

/* 

从ISP/IAP/EEPROM区域读取一字节

-*/ 

IAP_READ: 

MOV IAP_CONTR, #ENABLE_IAP 

MOV IAP_CMD, #CMD_READ 

MOV IAP_ADDRL, DPL 

MOV IAP_ADDRH, DPH 

MOV IAP_TRIG, #5AH 

MOV IAP_TRIG, #0A5H 

NOP 

MOV A, IAP_DATA 

LCALL IAP_IDLE 

RET 

//使能IAP

//设置IAP命令

//设置IAP低地址

//设置IAP高地址

//写触发命令(0x5a)

//写触发命令(0xa5)

//等待ISP/IAP/EEPROM操作完成

//度IAP数据

//关闭IAP功能

/* 

写一字节数据到ISP/IAP/EEPROM区域

-*/ 

IAP_PROGRAM: 

MOV IAP_CONTR, #ENABLE_IAP 

MOV IAP_CMD, #CMD_PROGRAM 

MOV IAP_ADDRL, DPL 

MOV IAP_ADDRH, DPH 

MOV IAP_DATA, A 

MOV IAP_TRIG, #5AH 

MOV IAP_TRIG, #0A5H 

NOP 

LCALL IAP_IDLE 

RET 

//使能IAP

//设置IAP命令

//设置IAP低地址

//设置IAP高地址

//写IAP数据

//写触发命令(0x5a)

//写触发命令(0xa5)

//等待ISP/IAP/EEPROM操作完成

//关闭IAP功能

/* 

扇区擦除

*/ 

IAP_ERASE: 

MOV IAP_CONTR, #ENABLE_IAP 

MOV IAP_CMD, #CMD_ERASE 

MOV IAP_ADDRL, DPL 

MOV IAP_ADDRH, DPH 

//使能IAP

//设置IAP命令

//设置IAP低地址

//设置IAP高地址

<table><tr><td>MOV</td><td>IAP_TRIG,</td><td>#5AH</td><td>//写触发命令(0x5a)</td></tr><tr><td>MOV</td><td>IAP_TRIG,</td><td>#0A5H</td><td>//写触发命令(0xa5)</td></tr><tr><td>NOP</td><td></td><td></td><td>//等待ISP/IAP/EEPROM操作完成</td></tr><tr><td>LCALL</td><td>IAP_IDLE</td><td></td><td>//关闭IAP功能</td></tr><tr><td>RET</td><td></td><td></td><td></td></tr><tr><td colspan="4">{/*- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - }}</td></tr><tr><td>;初始化串口</td><td></td><td></td><td></td></tr><tr><td colspan="4">}; - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - } /</td></tr><tr><td>INIT_UART:</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>SCON,</td><td>#5AH</td><td>;设置串口为8位可变波特率</td></tr><tr><td>#if URMD == 0</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>T2L,</td><td>#0D8H</td><td>;设置波特率重装值(65536-18432000/4/115200)</td></tr><tr><td>MOV</td><td>T2H,</td><td>#0FFH</td><td></td></tr><tr><td>MOV</td><td>AUXR,</td><td>#14H</td><td>;T2为1T模式,并启动定时器2</td></tr><tr><td>ORL</td><td>AUXR,</td><td>#01H</td><td>;选择定时器2为串口1的波特率发生器</td></tr><tr><td>#elif URMD == 1</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>AUXR,</td><td>#40H</td><td>;定时器1为1T模式</td></tr><tr><td>MOV</td><td>TMOD,</td><td>#00H</td><td>;定时器1为模式0(16位自动重载)</td></tr><tr><td>MOV</td><td>TL1,</td><td>#0D8H</td><td>;设置波特率重装值(65536-18432000/4/115200)</td></tr><tr><td>MOV</td><td>TH1,</td><td>#0FFH</td><td></td></tr><tr><td>SETB</td><td>TR1</td><td></td><td>;定时器1开始运行</td></tr><tr><td>#else</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>TMOD,</td><td>#20H</td><td>;设置定时器1为8位自动重装载模式</td></tr><tr><td>MOV</td><td>AUXR,</td><td>#40H</td><td>;定时器1为1T模式</td></tr><tr><td>MOV</td><td>TL1,</td><td>#0FBH</td><td>;115200 bps(256-18432000/32/115200)</td></tr><tr><td>MOV</td><td>TH1,</td><td>#0FBH</td><td></td></tr><tr><td>SETB</td><td>TR1</td><td></td><td></td></tr><tr><td>#endif</td><td></td><td></td><td></td></tr><tr><td>RET</td><td></td><td></td><td></td></tr><tr><td colspan="4">{/*- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - } /</td></tr><tr><td>;发送串口数据</td><td></td><td></td><td></td></tr><tr><td colspan="4">; - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -</td></tr><tr><td>SEND_DATA:</td><td></td><td></td><td></td></tr><tr><td>JNB</td><td>TI,</td><td>$</td><td>;等待前一个数据发送完成</td></tr><tr><td>CLR</td><td>TI</td><td></td><td>;清除发送标志</td></tr><tr><td>MOV</td><td>SBUF,</td><td>A</td><td>;发送当前数据</td></tr><tr><td>RET</td><td></td><td></td><td></td></tr><tr><td>END</td><td></td><td></td><td></td></tr></table>

# 9.5 比较器作外部掉电检测的参考电路

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/fc2de83ea6d9a21c4c41d62d0a3ab2473975c3118043e0b4c8d43f89c7a6a83a.jpg)


上图中， �R1和R2对稳压块7805的 �端电压进行分压，分压后的电压作为P5.5/CMP+的外部输入与内部BandGap参考 (1.27V附近)进行比较。

如交流电在220V时，稳压块7805前端的直流电是11V，当交流电压� 160V时，稳压块7805前端的直流电是8.5V， �R1和R2就将 �输入电压分压 CMP+端(比较器正极输入端)，此时CMP+端输入电压 BandGap参考 (1.27V附近)，可产生比较器中断，这样掉电检测时就有充足的时间将数据保存到EEPROM中。 7805前端的直流电压高于8.5V以上时 CMP+端输入电压 BandGap参考 (1.27V附近)，CPU可继续正常工作

# 第10章 STC15系列单片机的A/D转换器

下表总结了STC15系列单片机内部集成了8路10位高速A/D转换器的单片机型号：

<table><tr><td>特殊外围设备
单片机型号</td><td>8路10位高速
A/D转换器</td><td>CCP/PCA/PWM功能</td><td>1组高速同步串行口SPI</td></tr><tr><td>STC15W4K60S4系列</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td>STC15F2K60S2系列</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td>STC15W1K16S系列</td><td></td><td></td><td>✓</td></tr><tr><td>STC15W408S系列</td><td></td><td></td><td>✓</td></tr><tr><td>STC15W408AS系列</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td>STC15W201S系列</td><td></td><td></td><td></td></tr><tr><td>STC15F408AD系列</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td>STC15F101W系列</td><td></td><td></td><td></td></tr></table>


上表中 $\surd$ 表示对应的系列有相应的功能。


# 10.1 A/D转换器的结构

STC15系列单片机ADC(A/D转换器)的结构如下图所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/6bcddf178bfd24ab9b7d588f894951cc535c3ce0addedd99591fb517e3f5858c.jpg)


当CLK_DIV.5(PCON2.5)/ADRJ ${ } = 0$ 时，A/D转换结果寄存器格式如下：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7ea8d9c01f14c4abe730baaa4450340eda3a3d2f0efc57b0b985cb3c4e93282e.jpg)


当CLK_DIV.5(PCON2.5)/ADRJ $= 1$ 时，A/D转换结果寄存器格式如下：


ADC_RES[1:0]


<table><tr><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>ADC_B9</td><td>ADC_B8</td></tr></table>

<table><tr><td>ADC_B7</td><td>ADC_B6</td><td>ADC_B5</td><td>ADC_B4</td><td>ADC_B3</td><td>ADC_B2</td><td>ADC_B1</td><td>ADC_B0</td><td>ADC_RESL[7:0]</td></tr></table>

STC15系列单片机ADC由多路选择开关、比较器、逐次比较寄存器、10位DAC、转换结果寄存器(ADC_RES和ADC_RESL)以及ADC_CONTR构成。

STC15系列单片机的ADC是逐次比较型ADC。逐次比较型ADC由一个比较器和D/A转换器构成，通过逐次比较逻辑，从最高位(MSB)开始，顺序地对每一输入电压与内置D/A转换器输出进行比较，经过多次比较，使转换所得的数字量逐次逼近输入模拟量对应值。逐次比较型A/D转换器具有速度高，功耗低等优点。

从上图可以看出，通过模拟多路开关，将通过ADC0~7的模拟量输入送给比较器。用数/模转换器(DAC)转换的模拟量与输入的模拟量通过比较器进行比较，将比较结果保存到逐次比较寄存器，并通过逐次比较寄存器输出转换结果。A/D转换结束后，最终的转换结果保存到ADC转换结果寄存器ADC_RES和ADC_RESL，同时，置位ADC控制寄存器ADC_CONTR中的A/D转换结束标志位ADC_FLAG,以供程序查询或发出中断申请。模拟通道的选择控制由ADC控制寄存器ADC_CONTR中的CHS2~CHS0确定。ADC的转换速度由ADC控制寄存器中的SPEED1和SPEED0确定。在使用ADC之前，应先给ADC上电，也就是置位ADC控制寄存器中的ADC_POWER位。

当ADRJ=0时，如果取10位结果，则按下面公式计算:

$$
1 0 - \text {b i t A / D C o n v e r s i o n R e s} \left(\mathrm {A D C} _ {-} \mathrm {R E S} [ 7: 0 ], \mathrm {A D C} _ {-} \mathrm {R E S L} [ 1: 0 ]\right) = 1 0 2 4 \times \frac {\mathrm {V i n}}{\mathrm {V c c}}
$$

当ADRJ=0时，如果取8位结果，按下面公式计算:

$$
8 - \text {b i t} A / D \text {C o n v e n s i o n R e s u l t : (A D C \_ R E S [ 7 : 0 ]) = 2 5 6 x} \frac {\mathrm {V i n}}{\mathrm {V c c}}
$$

当ADRJ $\stackrel { \cdot } { = } 1$ 时，如果取10位结果，则按下面公式计算:

$$
1 0 - \text {b i t A / D C o n v e r s i o n R e s} \left(\mathrm {A D C} _ {-} \mathrm {R E S} [ 1: 0 ], \mathrm {A D C} _ {-} \mathrm {R E S L} [ 7: 0 ]\right) = 1 0 2 4 \times \frac {\mathrm {V i n}}{\mathrm {V c c}}
$$

式中，Vin为模拟输入通道输入电压，Vcc为单片机实际工作电压，用单片机工作电压作为模拟参考电压。

# 10.2 与A/D转换相关的寄存器

与STC15系列单片机A/D转换相关的寄存器列于下表所示。

<table><tr><td rowspan="2">符号</td><td rowspan="2">描述</td><td rowspan="2">地址</td><td rowspan="2" colspan="9">位地址及其符号MSB</td><td rowspan="2">复位值</td></tr><tr></tr><tr><td>P1ASF</td><td>P1 Analog Function Configure register</td><td>9DH</td><td colspan="9">P17ASF|P16ASF|P15ASF|P14ASF|P13ASF|P12ASF|P11ASF|P10ASF</td><td>0000 0000B</td></tr><tr><td>ADC_CONTR</td><td>ADC Control Register</td><td>BCH</td><td>ADC_POWER</td><td>SPEED1</td><td>SPEED0</td><td>ADC_FLAG</td><td>ADC_START</td><td>CHS2</td><td>CHS1</td><td>CHS0</td><td></td><td>0000 0000B</td></tr><tr><td>ADC_RES</td><td>ADC Result high</td><td>BDH</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td>ADC_RESL</td><td>ADC Result low</td><td>BEH</td><td colspan="9"></td><td>0000 0000B</td></tr><tr><td rowspan="2">CLK_DIVPCON2</td><td rowspan="2">时钟分频寄存器</td><td rowspan="2">97H</td><td>MCKO_S1</td><td>MCKO_S0</td><td>ADRJ</td><td>Tx_Rx</td><td>MCLKO_2</td><td>CLKS2</td><td>CLKS1</td><td>CLKS0</td><td></td><td rowspan="2">0000 0000B</td></tr><tr><td colspan="9"></td></tr><tr><td>IE</td><td>Interrupt Enable</td><td>A8H</td><td>EA</td><td>ELVD</td><td>EADC</td><td>ES</td><td>ET1</td><td>EX1</td><td>ET0</td><td>EX0</td><td></td><td>0000 0000B</td></tr><tr><td rowspan="2">IP</td><td rowspan="2">Interrupt PriorityLow</td><td rowspan="2">B8H</td><td>PPCA</td><td>PLVD</td><td>PADC</td><td>PS</td><td>PT1</td><td>PX1</td><td>PT0</td><td>PX0</td><td></td><td rowspan="2">0000 0000B</td></tr><tr><td colspan="9"></td></tr></table>

# 1.P1口模拟功能控制寄存器P1ASF

STC15系列单片机的A/D转换口在P1口(P1,7-P1.0)，有8路10位高速A/D转换器,速度可达到300KHz(30万次/秒)。8路电压输入型A/D，可做温度检测、电池电压检测、按键扫描、频谱检测等。上电复位后P1口为弱上拉型I/O口，用户可以通过软件设置将8路中的任何一路设置为A/D转换，不需作为A/D使用的P1口可继续作为I/O口使用(建议只作为输入 �口需先将P1ASF特殊功能寄存器中的相应位置为‘1’，将相应的口设置为模拟功能。存器的格式如下：

P1ASF : P1口模拟功能控制寄存器(该寄存器是只写寄存器,读无效

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>P1ASF</td><td>9DH</td><td>name</td><td>P17ASF</td><td>P16ASF</td><td>P15ASF</td><td>P14ASF</td><td>P13ASF</td><td>P12ASF</td><td>P11ASF</td><td>P10ASF</td></tr></table>

<table><tr><td>P1ASF[7:0]</td><td>P1.x的功能</td><td>其中P1ASF寄存器地址为：[9DH](不能够进行位寻址)</td></tr><tr><td>P1ASF.0 = 1</td><td>P1.0口作为模拟功能A/D使用</td><td></td></tr><tr><td>P1ASF.1 = 1</td><td>P1.1口作为模拟功能A/D使用</td><td></td></tr><tr><td>P1ASF.2 = 1</td><td>P1.2口作为模拟功能A/D使用</td><td></td></tr><tr><td>P1ASF.3 = 1</td><td>P1.3口作为模拟功能A/D使用</td><td></td></tr><tr><td>P1ASF.4 = 1</td><td>P1.4口作为模拟功能A/D使用</td><td></td></tr><tr><td>P1ASF.5 = 1</td><td>P1.5口作为模拟功能A/D使用</td><td></td></tr><tr><td>P1ASF.6 = 1</td><td>P1.6口作为模拟功能A/D使用</td><td></td></tr><tr><td>P1ASF.7 = 1</td><td>P1.7口作为模拟功能A/D使用</td><td></td></tr></table>

# 2. ADC控制寄存器ADC_CONTR

ADC_CONTR寄存器的格式如下：

ADC_CONTR : ADC控制寄存器

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>ADC_CONTR</td><td>BCH</td><td>name</td><td>ADC_POWER</td><td>SPEED1</td><td>SPEED0</td><td>ADC_FLAG</td><td>ADC_START</td><td>CHS2</td><td>CHS1</td><td>CHS0</td></tr></table>

对ADC_CONTR寄存器进行操作，建议直接用MOV赋值语句，不要用‘与’和‘或’语句

ADC_POWER: ADC 电源控制位。

0：关闭ADC 电源；

1：打开A/D转换器电源.

建议进入空闲模式和掉电模式前，将ADC电源关闭，即ADC_POWER =0 �低功耗。动A/D转换前一定要确认A/D电源已打开，A/D转换结束后关闭A/D电源可降低功耗，也可不关闭。初次打开内部A/D转换模拟电源，需适当延时，等内部模拟电源稳定后，再启动A/D转换

建议启动A/D转换后，在A/D转换结束之前，不改变任何I/O口的状态，有利于高精度A/D转换,如能将定时器/串行口/中断系统关闭更好。

SPEED1，SPEED0：模数转换器转换速度控制位

<table><tr><td>SPEED1</td><td>SPEED0</td><td>A/D转换所需时间</td></tr><tr><td>1</td><td>1</td><td>90个时钟周期转换一次，CPU工作频率21MHz时，A/D转换速度约300KHz</td></tr><tr><td>1</td><td>0</td><td>180个时钟周期转换一次</td></tr><tr><td>0</td><td>1</td><td>360个时钟周期转换一次</td></tr><tr><td>0</td><td>0</td><td>540个时钟周期转换一次</td></tr></table>

ADC_FLAG: 模数转换器转换结束标志位,当A/D转换完成后，ADC_FLAG = 1，要由软件清0。不管是A/D 转换完成后由该位申请产生中断，还是由软件查询该标志位A/D转换是否结束,当A/D转换完成后，ADC_FLAG = 1，一定要软件清0。

ADC_START:模数转换器(ADC)转换启动控制位，设置为“1”时，开始转换,转换结束后为0。

CHS2/CHS1/CHS0：模拟输入通道选择，CHS2/CHS1/CHS0

<table><tr><td>CHS2</td><td>CHS1</td><td>CHS0</td><td>Analog Channel Select (模拟输入通道选择)</td></tr><tr><td>0</td><td>0</td><td>0</td><td>选择 P1.0 作为A/D输入来用</td></tr><tr><td>0</td><td>0</td><td>1</td><td>选择 P1.1 作为A/D输入来用</td></tr><tr><td>0</td><td>1</td><td>0</td><td>选择 P1.2 作为A/D输入来用</td></tr><tr><td>0</td><td>1</td><td>1</td><td>选择 P1.3 作为A/D输入来用</td></tr><tr><td>1</td><td>0</td><td>0</td><td>选择 P1.4 作为A/D输入来用</td></tr><tr><td>1</td><td>0</td><td>1</td><td>选择 P1.5 作为A/D输入来用</td></tr><tr><td>1</td><td>1</td><td>0</td><td>选择 P1.6 作为A/D输入来用</td></tr><tr><td>1</td><td>1</td><td>1</td><td>选择 P1.7 作为A/D输入来用</td></tr></table>

# 3.ADC转换结果调整寄存器位— ADRJ

ADC转换结果调整寄存器位——ADRJ位于寄存器CLK_DIV/PCON中，用于控制ADC转换结果存放的位置。

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td><td>Reset Value</td></tr><tr><td>CLK_DIV(PCON2)</td><td>97H</td><td>时钟分频寄存器</td><td>MCKO_S1</td><td>MCKO_S0</td><td>ADRJ</td><td>Tx_Rx</td><td>Tx2_Rx2</td><td>CLKS2</td><td>CLKS1</td><td>CLKS0</td><td>0000,x000</td></tr></table>

ADRJ：ADC转换结果调整

0：ADC_RES[7:0]存放高8位ADC结果，ADC_RESL[1:0]存放低2位ADC结果

1：ADC_RES[1:0]存放高2位ADC结果，ADC_RESL[7:0]存放低8位ADC结果

# 4. A/D转换结果寄存器ADC_RES、ADC_RESL

特殊功能寄存器ADC_RES和ADC_RESL寄存器用于保存A/D转换结果，其格式如下：

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>ADC_RES</td><td>BDh</td><td>A/D转换结果寄存器高</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>ADC_RESL</td><td>BEh</td><td>A/D转换结果寄存器低</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>CLK_DIV(PCON2)</td><td>97H</td><td>时钟分频寄存器</td><td>MCKO_S1</td><td>MCKO_S0</td><td>ADRJ</td><td>Tx_Rx</td><td>Tx2_Rx2</td><td>CLKS2</td><td>CLKS1</td><td>CLKS0</td></tr></table>

AUXR1寄存器的ADRJ位是A/D转换结果寄存器(ADC_RES,ADC_RESL)的数据格式调整控制位.当ADRJ=0时，10位A/D转换结果的高8位存放在ADC_RES中，低2位存放在ADC_RESL的低2位中

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>ADC_RES</td><td>BDh</td><td>A/D转换结果寄存器高8位</td><td>ADC_RES9</td><td>ADC_RES8</td><td>ADC_RES7</td><td>ADC_RES6</td><td>ADC_RES5</td><td>ADC_RES4</td><td>ADC_RES3</td><td>ADC_RES2</td></tr><tr><td>ADC_RESL</td><td>BEh</td><td>A/D转换结果寄存器低2位</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>ADC_RES1</td><td>ADC_RES0</td></tr><tr><td>CLK_DIV(PCON2)</td><td>97H</td><td>时钟分频寄存器</td><td></td><td></td><td>ADRJ = 0</td><td></td><td></td><td></td><td></td><td></td></tr></table>

此时，如果用户需取完整10位结果，按下面公式计算:

$$
1 0 - \text {b i t A / D C o n v e r s i o n R e s u l t : (A D C _ {\_} R E S [ 7 : 0 ] , A D C _ {\_} R E S L [ 1 : 0 ]) = 1 0 2 4 x \frac {V i n}{V c c}}
$$

如果用户只需取8位结果，按下面公式计算:

$$
8 - \text {b i t} A / D \text {C o n v e r s i o n R e s u l t : (A D C _ {-} R E S [ 7 : 0 ]) = 2 5 6 x} \frac {\text {V i n}}{\text {V c c}}
$$

式中，Vin为模拟输入通道输入电压，Vcc为单片机实际工作电压，用单片机工作电压作为模拟参考电压。

当ADRJ $\stackrel { \cdot } { = } 1$ 时，10位A/D转换结果的高2位存放在ADC_RES的低2位中，低8位存放在ADC_RESL中

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>ADC_RES</td><td>BDh</td><td>A/D转换结果寄存器高2位</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>ADC_RES9</td><td>ADC_RES8</td></tr><tr><td>ADC_RESL</td><td>BEh</td><td>A/D转换结果寄存器低8位</td><td>ADC_RES7</td><td>ADC_RES6</td><td>ADC_RES5</td><td>ADC_RES4</td><td>ADC_RES3</td><td>ADC_RES2</td><td>ADC_RES1</td><td>ADC_RES0</td></tr><tr><td>CLK_DIV(PCON2)</td><td>97H</td><td>时钟分频寄存器</td><td></td><td></td><td>ADRJ = 1</td><td></td><td></td><td></td><td></td><td></td></tr></table>

此时，如果用户需取完整10位结果，按下面公式计算:

$$
1 0 - \text {b i t A / D C o n v e r s i o n R e s} \left(\mathrm {A D C} _ {-} \mathrm {R E S} [ 1: 0 ], \mathrm {A D C} _ {-} \mathrm {R E S L} [ 7: 0 ]\right) = 1 0 2 4 \times \frac {\mathrm {V i n}}{\mathrm {V c c}}
$$

式中，Vin为模拟输入通道输入电压，Vcc为单片机实际工作电压，用单片机工作电压作为模拟参考电压。

# 5.中断允许寄存器IE

IE : 中断允许寄存器 (可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IE</td><td>A8H</td><td>name</td><td>EA</td><td>ELVD</td><td>EADC</td><td>ES</td><td>ET1</td><td>EX1</td><td>ET0</td><td>EX0</td></tr></table>

EA : CPU的中断开放标志

EA=1，CPU开放中断，

EA=0，CPU屏蔽所有的中断申请。

EA的作用是使中断允许形成多级控制。即各中断源首先受EA控制;其次还受各中断源自己的中断允许控制位控制。

EADC : A/D转换中断允许位

EADC=1，允许A/D转换中断，

EADC $\scriptstyle \sum 0$ ，禁止A/D转换中断。

# 6.中断优先级控制寄存器IP

IP : 中断优先级控制寄存器 (可位寻址)

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IP</td><td>B8H</td><td>name</td><td>PPCA</td><td>PLVD</td><td>PADC</td><td>PS</td><td>PT1</td><td>PX1</td><td>PT0</td><td>PX0</td></tr></table>

PADC: A/D转换中断优先级控制位。

当PADC $\scriptstyle \sum 0$ 时，A/D转换中断为最低优先级中断(优先级0)

当PADC $: = 1$ 时，A/D转换中断为最高优先级中断(优先级1)

# 10.3 A/D转换典型应用线路

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/63aedcc14f10fae23410b92122dbb2e96ca6c468d271f1e8cf88277dbc965efc.jpg)



基准参考电压源TL431B


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/816c53f8ddab071ba8ff9d55208b61026e336f6cffbf4d720b6900a5cfbbe9b7.jpg)



SOT23-3封装，RMB￥0.15~0.3


如应用简单，可无需基准参考电压源，直接与Vcc比较即可。

A/D转换通道在P1口。P1.x/ADCx是指P1.x管脚可作为A/D转换通道使用。


基准参考电压源TL431B的符号


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5c4ff96ee958aecea8d3cecaac46e16594ab7558c0d4a9d7e051c0b3cd453408.jpg)


# 10.4 A/D作按键扫描应用线路图

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/376c64f258540d0bb816e3eb6e2d95a1ea954310ad137c31da801d47fd9932e7.jpg)


# 读ADC键的方法：

每隔10ms左右读一次ADC值，并且保存最后3次的读数，其变化比较小时再判断键。判断键有效时，允许一定的偏差，比如 $\lvert \pm 1 6 $ 个字的偏差。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/9f96bf465eb8d47392a272bbf0f0e82e3345389f9bff9936b93ea012cdcc1422.jpg)


# 10.5 A/D转换模块的参考电压源

STC15系列单片机的参考电压源是输入工作电压Vcc，所以一般不用外接参考电压源。如7805的输出电压是5V，但实际电压可能是4.88V到4.96V，用户需要精度比较高的话，可在出厂时将实际测出的工作电压值记录在单片机内部的EEPROM里面，以供计算。

如果有些用户的Vcc不固定，如电池供电，电池电压在5.3V-4.2V之间漂移，则Vcc不固定，就需要在8路A/D转换的一个通道外接一个稳定的参考电压源，来计算出此时的工作电压Vcc，再计算出其他几路A/D转换通道的电压。如下图所示，可在ADC转换通道的第二一个1.25V(或1�V，或���．．．���)的基准参考电压源，由此求出此时的工作电压�Vcc，再计算出其�它几路A/D转换通道的电压(���理论依 据是�短时间之内，�Vcc不�变)

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/2d410890ea7cba17b5e54469a8d7da260063dd2572a3dd9cb67e8667f7009ac5.jpg)



SOT23-3封装，RMB￥0.15~0.3


如应用简单，可无需基准参考电压源，直接与Vcc比较即可。


基准参考电压源TL431B的符号


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/55f5118befc185affe0f0b3a962c148e0a0e07941c4df591cf0bcb53e9e2f7bf.jpg)


# 10.6 A/D转换的测试程序(C和汇编)

# 10.6.1 A/D转换的测试程序(ADC中断方式)

# 1. C程序：

/* -*/ 

/* --- STC MCU Limited. - -*/ 

/* --- STC15F2K60S2 系列 A/D转换中断方式举例--- -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序 */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可-----*/

/*- 火

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

#define FOSC 18432000L 

#define BAUD 9600 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

#define URMD 0 //0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

sfr T2H 0xd6; //定时器2高8位

sfr T2L $=$ 0xd7; //定时器2低8位

sfr AUXR $=$ 0x8e; //辅助寄存器

sfr ADC_CONT 一 0xBC; //ADC控制寄存器

sfr ADC_RES 0xBD; //ADC高8位结果

sfr ADC_LOW2 0xBE; //ADC低2位结果

sfr P1ASF 一 0x9D; //P1口第2功能控制寄存器

#define ADC_POWER 0x80 //ADC电源控制位

#define ADC_FLAG 0x10 //ADC完成标志

#define ADC_START 0x08 //ADC起始控制位

```c
define ADC_SPEEDLL 0x00 //540个时钟  
#define ADC_SPEEDL 0x20 //360个时钟  
#define ADC_SPEEDH 0x40 //180个时钟  
#define ADC_SPEEDHH 0x60 //90个时钟
```

```txt
void InitUart();  
void SendData(ByteDat);  
void Delay(Word n);  
void InitADC(); 
```

```txt
BYTE ch = 0; //ADC通道号  
void main()  
{ InitUart(); //初始化串口 InitADC(); //初始化ADC IE = 0xa0; //使能ADC中 while (1); //开始AD转换 }
```

```c
ADC中断服务程序  
\(\text{一} \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_
void adc_isr() interrupt 5 using 1
{
    ADC_CONTR &= !ADC_FLAG; //清除ADC中断标志
    SendData(ch); //显示通道号
    SendData(ADC_RES); //读取高8位结果并发送到串口
```

// SendData(ADC_LOW2); //显示低2位结果 if $(++\mathrm{ch} > 7)\mathrm{ch} = 0$ //切换到下一个通道 ADC_CONTR $=$ ADC_POWER|ADC_SPEEDLL|ADC_START|ch; }

```txt
初始化ADC
```

```txt
void InitADC()  
{ P1ASF = 0xff; //设置P1口为AD口 ADC_RES = 0; //清除结果寄存器 ADC_CONTR = ADC_POWER | ADC_SPEEDLL | ADC_START | ch; Delay(2); //ADC上电并延时}
```


初始化串口


```lisp
void InitUart()  
{ SCON = 0x5a; //设置串口为8位可变波特率  
#if URMD == 0  
T2L = 0xd8; //设置波特率重装值  
T2H = 0xff; //115200 bps(65536-18432000/4/115200)  
AUXR = 0x14; //T2为1T模式,并启动定时器2  
AUXR |= 0x01; //选择定时器2为串口1的波特率发生器  
URMD = 1  
AUXR = 0x40; //定时器1为1T模式  
TMOD = 0x00; //定时器1为模式0(16位自动重载)  
TL1 = 0xd8; //设置波特率重装值  
TH1 = 0xff; //115200 bps(65536-18432000/4/115200)  
TR1 = 1; //定时器1开始启动  
TMOD = 0x20; //设置定时器1为8位自动重装载模式  
AUXR = 0x40; //定时器1为1T模式  
TH1 = TL1 = 0xfb; //115200 bps(256-18432000/32/115200)  
TR1 = 1;  
#endif  
}  
/*__________发送串口数据*/  
void SendData(BYTE dat)  
{ while (!TI); //等待前一个数据发送完成  
TI = 0; //清除发送标志  
SBUF = dat; //发送当前数据  
}  
/*__________软件延时________*/  
void Delay(WORD n)  
{ WORD x; while (n--); { x = 5000; while (x--); }
```

# 2. 汇编程序：

/* -*/ 

/* --- STC MCU Limited. - -*/ 

/* --- STC15F2K60S2 系列 A/D转换中断方式举例-- -*

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 -*/ 

/* --- Web: www.STCMCU.com -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序 */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可--------*/

/* -*/ 

//本示例在Keil开发环境下请选择Intel的8052芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

#define URMD 0 //0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

T2H DATA 0D6H //定时器2高8位

T2L DATA 0D7H //定时器2低8位

AUXR DATA 08EH ;辅助寄存器

ADC_CONTR EQU 0BCH ;ADC控制寄存器

ADC_RES EQU 0BDH ;ADC高8位结果

ADC_LOW2 EQU 0BEH ;ADC低2位结果

P1ASF EQU 09DH ;P1口第2功能控制寄存器

ADC_POWER EQU 80H ;ADC电源控制位

ADC_FLAG EQU 10H ;ADC完成标志

ADC_START EQU 08H ;ADC起始控制位

ADC_SPEEDLL EQU 00H ;540个时钟

ADC_SPEEDL EQU 20H ;360个时钟

ADC_SPEEDH EQU 40H ;180个时钟

ADC_SPEEDHH EQU 60H ;90个时钟

ADCCH DATA 20H ;ADC通道号

ORG 0000H 

LJMP MAIN 

ORG 002BH 

LJMP ADC_ISR 

ORG 0100H 

MAIN: 

MOV SP, #3FH 

MOV ADCCH, #0 

LCALL INIT_UART 

LCALL INIT_ADC 

MOV IE, #0A0H 

SJMP $ 

;初始化串口

;初始化ADC

;使能ADC中断

;/*-- 

;ADC中断服务程序

-*/ 

ADC_ISR: 

PUSH ACC 

PUSH PSW 

ANL ADC_CONTR, #NOT ADC_FLAG ;清除ADC中断标志

MOV A, ADCCH 

LCALL SEND_DATA ;Send channel NO. 

MOV A, ADC_ RES ;Get ADC high 8-bit result 

LCALL SEND_DATA ;Send to UART 

MOV A, ADC_LOW2 ;Get ADC low 2-bit result 

LCALL SEND_DATA ;Send to UART 

INC ADCCH 

MOV A, ADCCH 

ANL A, #07H 

MOV ADCCH, A 

ORL A, #ADC_POWER | ADC_SPEEDLL | ADC_START 

MOV ADC_CONTR, A ;AD\开始AD转换

POP PSW 

POP ACC 

RETI 

;/*- 

;初始化ADC

-*/ 

INIT_ADC: 

MOV P1ASF, #0FFH ;设置P1口为AD口

MOV ADC_RES, #0 ;清除结果寄存器

MOV A, ADCCH 

ORL A, #ADC_POWER | ADC_SPEEDLL | ADC_START 

MOV ADC_CONTR, A ;ADC上电并延时

MOV A, #2 

LCALL DELAY 

RET 

;/*- 

;初始化串口

-*/ 

INIT_UART: 

<table><tr><td rowspan="6">#if</td><td>MOV</td><td>SCON,</td><td>#5AH</td><td>;设置串口为8位可变波特率</td></tr><tr><td>URMD</td><td>==</td><td>0</td><td></td></tr><tr><td>MOV</td><td>T2L,</td><td>#0D8H</td><td>;设置波特率重装值(65536-18432000/4/115200)</td></tr><tr><td>MOV</td><td>T2H,</td><td>#0FFH</td><td></td></tr><tr><td>MOV</td><td>AUXR,</td><td>#14H</td><td>;T2为1T模式,并启动定时器2</td></tr><tr><td>ORL</td><td>AUXR,</td><td>#01H</td><td>;选择定时器2为串口1的波特率发生器</td></tr><tr><td colspan="5">#elif URMD==1</td></tr><tr><td></td><td>MOV</td><td>AUXR,</td><td>#40H</td><td>;定时器1为1T模式</td></tr><tr><td></td><td>MOV</td><td>TMOD,</td><td>#00H</td><td>;定时器1为模式0(16位自动重载)</td></tr><tr><td></td><td>MOV</td><td>TL1,</td><td>#0D8H</td><td>;设置波特率重装值(65536-18432000/4/115200)</td></tr><tr><td></td><td>MOV</td><td>TH1,</td><td>#0FFH</td><td></td></tr><tr><td></td><td>SETB</td><td>TR1</td><td></td><td>;定时器1开始运行</td></tr><tr><td colspan="5">#else</td></tr><tr><td></td><td>MOV</td><td>TMOD,</td><td>#20H</td><td>;设置定时器1为8位自动重装载模式</td></tr><tr><td></td><td>MOV</td><td>AUXR,</td><td>#40H</td><td>;定时器1为1T模式</td></tr><tr><td></td><td>MOV</td><td>TL1,</td><td>#0FBH</td><td>;115200 bps(256 - 18432000/32/115200)</td></tr><tr><td></td><td>MOV</td><td>TH1,</td><td>#0FBH</td><td></td></tr><tr><td></td><td>SETB</td><td>TR1</td><td></td><td></td></tr><tr><td colspan="5">#endif</td></tr><tr><td></td><td>RET</td><td></td><td></td><td></td></tr><tr><td colspan="5">;/*--------*/</td></tr><tr><td colspan="5">;发送串口数据</td></tr><tr><td colspan="5">;--------*/</td></tr><tr><td colspan="5">SEND_DATA:</td></tr><tr><td></td><td>JNB</td><td>TI,</td><td>$</td><td>;等待前一个数据发送完成</td></tr><tr><td></td><td>CLR</td><td>TI</td><td></td><td>;清除发送标志</td></tr><tr><td></td><td>MOV</td><td>SBUF,</td><td>A</td><td>;发送当前数据</td></tr><tr><td></td><td>RET</td><td></td><td></td><td></td></tr><tr><td colspan="5">;/*--------*/</td></tr><tr><td colspan="5">;软件延时</td></tr><tr><td colspan="5">;--------*/</td></tr><tr><td colspan="5">DELAY:</td></tr><tr><td></td><td>MOV</td><td>R2,</td><td>A</td><td></td></tr><tr><td></td><td>CLR</td><td>A</td><td></td><td></td></tr><tr><td></td><td>MOV</td><td>R0,</td><td>A</td><td></td></tr><tr><td></td><td>MOV</td><td>R1,</td><td>A</td><td></td></tr><tr><td colspan="5">DELAY1:</td></tr><tr><td></td><td>DJNZ</td><td>R0,</td><td>DELAY1</td><td></td></tr><tr><td></td><td>DJNZ</td><td>R1,</td><td>DELAY1</td><td></td></tr><tr><td></td><td>DJNZ</td><td>R2,</td><td>DELAY1</td><td></td></tr><tr><td></td><td>RET</td><td></td><td></td><td></td></tr><tr><td></td><td>END</td><td></td><td></td><td></td></tr></table>

# 10.6.2 A/D转换的测试程序(ADC查询方式)

# 1. C程序：

/* */ 

/* --- STC MCU Limited. - */ 

/* --- STC15F2K60S2 系列 A/D转换查询方式举例- -*/

/* --- 研发顾问QQ：800003751- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - * 

/* --- Web: www.STCMCU.com - */ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可--------*/

/* */ 

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

#define FOSC 18432000L 

#define BAUD 9600 

typedef unsigned char BYTE; typedef unsigned int WORD; 

#define URMD 0 

//0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

sfr T2H 0xd6; //定时器2高8位

sfr T2L $=$ 0xd7; //定时器2低8位

sfr AUXR $=$ 0x8e; 

sfr ADC_CONTR $\begin{array} { r l } { = } & { { } 0 \mathrm { x B C } } \end{array}$ ; //ADC控制寄存器

sfr ADC_RES = 0xBD; //ADC高8位结果

sfr ADC_LOW2 = 0xBE; //ADC低2位结果

sfr P1ASF $\begin{array} { r l r } { \mathrm { ~  ~ \omega ~ } } & { { } = } & { 0 { \bf x } 9 { \bf D } } \end{array}$ ; /P1口第2功能控制寄存器

#define ADC_POWER 0x80 //ADC电源控制位

#define ADC_FLAG 0x10 //ADC完成标志

#define ADC_START 0x08 //ADC起始控制位

#define ADC_SPEEDLL 0x00 //540个时钟

#define ADC_SPEEDL 0x20 //360个时钟

#define ADC_SPEEDH 0x40 //180个时钟

#define ADC_SPEEDHH 0x60 //90个时钟

void InitUart(); 

```c
void InitADC();  
void SendData(BYTE dat);  
BYTE GetADCResult(BYTE ch);  
void Delay(WORD n);  
void ShowResult(BYTE ch);  
void main()  
{ InitUart(); //初始化串口 InitADC(); //初始化ADC while (1) { ShowResult(0); //显示通道0 ShowResult(1); //显示通道1 ShowResult(2); //显示通道2 ShowResult(3); //显示通道3 ShowResult(4); //显示通道4 ShowResult(5); //显示通道5 ShowResult(6); //显示通道6 ShowResult(7); //显示通道7 }  
}  
/*  
发送ADC结果到PC */  
void ShowResult(BYTE ch) { SendData(ch); //显示通道号 SendData(GetADCResult(ch)); //显示ADC高8位结果  
// SendData(ADC_LOW2); //显示低2位结果  
}  
/*  
读取ADC结果 */  
BYTE GetADCResult(BYTE ch) { ADC_CONTR = ADC_POWER | ADC_SPEEDDLL | ch | ADC_START; _nop(); //等待4个NOP _nop(); _nop(); _nop(); _nop(); while (!ADC_CONTR & ADC_FLAG); //等待ADC转换完成 ADC_CONTR &= ~ADC_FLAG; //Close ADC return ADC_RES; //返回ADC结果
```

```txt
初始化串口
```

```javascript
void InitUart() { 
```

```txt
SCON = 0x5a; //设置串口为8位可变波特率  
URMD == 0  
T2L = 0xd8; //设置波特率重装值  
T2H = 0xff; //115200 bps(65536-18432000/4/115200)  
AUXR = 0x14; //T2为1T模式,并启动定时器2  
AUXR |= 0x01; //选择定时器2为串口1的波特率发生器  
URMD == 1  
AUXR = 0x40; //定时器1为1T模式  
TMOD = 0x00; //定时器1为模式0(16位自动重载)  
TL1 = 0xd8; //设置波特率重装值  
TH1 = 0xff; //115200 bps(65536-18432000/4/115200)  
TR1 = 1; //定时器1开始启动  
TMOD = 0x20; //设置定时器1为8位自动重装载模式  
AUXR = 0x40; //定时器1为1T模式  
TH1 = TL1 = 0xfb; //115200 bps(256 - 18432000/32/115200)  
TR1 = 1;
```

```c
endif  
}  
/*  
初始化ADC*/  
void InitADC()  
{P1ASF = 0xff; //设置P1口为AD口ADC_RES = 0; //清除结果寄存器ADC_CONTR = ADC_POWER | ADC_SPEEDLL;Delay(2); //ADC上电并延时}
```

```txt
发送串口数据  
void SendData(BYTE dat)  
{ while(!TI); TI = 0; SBUF = dat; }
```

```txt
/*  
软件延时  
*/  
void Delay(WORD n)  
{  
    WORD x;  
    while (n--);  
    {  
        x = 5000;  
        while (x--);  
    }  
}
```

# 2. 汇编程序：

/* */ 

/* --- STC MCU Limited. - */ 

/* --- STC15F2K60S2 系列 A/D转换查询方式举例--------- *

/* --- 研发顾问QQ：800003751- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 */ 

/* --- Web: www.STCMCU.com -- */ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序- */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可--------*/

/* * 


//假定测试芯片的工作频率为18.432MHz


```txt
define URMD 0 //0:使用定时器2作为波特率发生器 //1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器 //2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器  
T2H DATA 0D6H //定时器2高8位  
T2L DATA 0D7H //定时器2低8位  
AUXR DATA 08EH ;辅助寄存器  
ADC_CONTR EQU 0BCH ;ADC控制寄存器  
ADC_RES EQU 0BDH ;ADC高8位结果  
ADC_LOW2 EQU 0BEH ;ADC低2位结果  
P1ASF EQU 09DH ;P1口第2功能控制寄存器  
ADC_POWER EQU 80H ;ADC电源控制位  
ADC_FLAG EQU 10H ;ADC完成标志  
ADC_START EQU 08H ;ADC起始控制位  
ADC_SPEEDDLL EQU 00H ;540个时钟
```

ADC_SPEEDL 

EQU 

20H 

;360个时钟

ADC_SPEEDH 

EQU 

40H 

;180个时钟

ADC_SPEEDHH 

EQU 

60H 

;90个时钟

ORG 0000H 

LJMP MAIN 

ORG 0100H 

MAIN: 

LCALL INIT_UART 

;初始化串口

LCALL INIT_ADC 

;初始化ADC

NEXT: 

MOV A, #0 

LCALL SHOW_RESULT 

;显示通道0的结果

MOV A, #1 

LCALL SHOW_RESULT 

;显示通道1的结果

MOV A, #2 

LCALL SHOW_RESULT 

;显示通道2的结果

MOV A, #3 

LCALL SHOW_RESULT 

;显示通道3的结果

MOV A, #4 

LCALL SHOW_RESULT 

;显示通道4的结果

MOV A, #5 

LCALL SHOW_RESULT 

;显示通道5的结果

MOV A, #6 

LCALL SHOW_RESULT 

;显示通道6的结果

MOV A, #7 

LCALL SHOW_RESULT 

;显示通道7的结果

SJMP NEXT 

：/* 

;发送ADC结果到PC

*/ 

SHOW_RESULT: 

LCALL SEND_DATA 

;显示通道号

LCALL GET_ADC_RESULT 

;读取高8位结果

LCALL SEND_DATA 

;显示结果

MOV A, ADC_LOW2 

;读取低2位结果

LCALL SEND_DATA 

;显示结果

RET 

;/*-- 

;读取ADC结果

_*/ 

GET_ADC_RESULT: 

ORL A, #ADC_POWER | ADC_SPEEDLL | ADC_START 

MOV ADC_CONTR, A ;开始AD转换

NOP ;等待4个NOP

NOP 

NOP 

NOP 

WAIT: 

MOV A, ADC_CONTR ;等待ADC转换完成

JNB ACC.4, WAIT ;ADC_FLAG(ADC_CONTR.4) 

ANL ADC_CONTR, #NOT ADC_FLAG ;清ADC标志

MOV A, ADC_RES ;返回ADC结果

RET 

;/*- 

;初始化ADC

*/ 

INIT_ADC: 

MOV P1ASF, #0FFH ;设置P1口为AD口

MOV ADC_RES, #0 

MOV ADC_CONTR, #ADC_POWER | ADC_SPEEDLL 

MOV A, #2 ;ADC上电并延时

LCALL DELAY 

RET 

;/*- 

;初始化串口

* 

INIT_UART: 

MOV SCON, #5AH ;设置串口为8位可变波特率

#if URMD $\scriptstyle = = 0$ 

MOV T2L, #0D8H ;设置波特率重装值(65536-18432000/4/115200)

MOV T2H, #0FFH 

MOV AUXR, #14H ;T2为1T模式, 并启动定时器2

ORL AUXR, #01H ;选择定时器2为串口1的波特率发生器

#elif URMD $= = 1$ 

MOV AUXR, #40H ;定时器1为1T模式

MOV TMOD, #00H ;定时器1为模式0(16位自动重载)

MOV TL1, #0D8H ;设置波特率重装值(65536-18432000/4/115200)

MOV TH1, #0FFH 

SETB TR1 

#else 

MOV TMOD, #20H ;设置定时器1为8位自动重装载模式

MOV AUXR, #40H ;定时器1为1T模式

MOV TL1, #0FBH ;115200 bps(256 - 18432000/32/115200) 

MOV TH1, #0FBH 

SETB TR1 

#endif 

RET 

;/*-- 

;发送串口数据

* 

SEND_DATA: 

JNB TI, $ 

CLR TI 

MOV SBUF, A 

RET 

;等待前一个数据发送完成

;清除发送标志

;发送当前数据

;/*-- 

;软件延时

-*/ 

DELAY: 

MOV R2, A 

CLR A 

MOV R0, A 

MOV R1, A 

DELAY1: 

DJNZ R0, DELAY1 

DJNZ R1, DELAY1 

DJNZ R2, DELAY1 

RET 

END 

# 10.7 利用新增的ADC第9通道测量内部参考电压的测试程序

# 所测量的内部参考电压BandGap电压用来计算工作电压Vcc

ADC的第9通道是用来测试内部BandGap参考电压的，由于内部BandGap参考电压很稳定，不会随芯片的工作电压的改变而变化，所以可以通过测量内部BandGap参考电压，然后通过ADC的值便可反推出VCC的电压，从而用户可以实现自己的低压检测功能。

ADC的第9通道的测量方法：首先将P1ASF初始化为0，即关闭所有P1口的模拟功能然后通过正常的ADC转换的方法读取第0通道的值，即可通过ADC的第9通道读取当前内部BandGap参考电压值。

用户实现自己的低压检测功能的实现方法：首先用户需要在VCC很精准的情况下(比如5.0V)，测量出内部BandGap参考电压的ADC转换值(比如为BGV5)，并将这个值保存到EEPROM中，然后在低压检测的代码中，在实际VCC变化后，测量出的内部BandGap参考电压的ADC转换值(比如为BGVx)，最后通过计算公式: 实际VCC $=$ 5.0V * BGV5 / BGVx，即可计算出实际的VCC电压值，需要注意的是,第一步的BGV5的基准测量一定要精确。

# 1. C程序：

/* ---------------- -*/ 

/* --- STC MCU Limited ------- */ 

/* --- STC15W4K60S4 系列 ADC第9通道应用举例- -*/

/* --- 研发顾问QQ：800003751---- */

/* --- Fax: 86-755-82905966 - * 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/* -*/ 

//本示例在Keil开发环境下请选择Intel的8058芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

# //说明:

// ADC的第9通道是用来测试内部BandGap参考电压的，由于内部BandGap参考电压很稳定，不会随芯

// 片的工作电压的改变而变化，所以可以通过测量内部BandGap参考电压，然后通过ADC的值便可反推

// 出VCC的电压，从而用户可以实现自己的低压检测功能.

// ADC的第9通道的测量方法：首先将P1ASF初始化为0，即关闭所有P1口的模拟功能然后通过正常的

// ADC转换的方法读取第0通道的值，即可通过ADC的第9通道读取当前内部BandGap参考电压值.

// 用户实现自己的低压检测功能的实现方法：首先用户需要在VCC很精准的情况下(比如5.0V)，测量

// 出内部BandGap参考电压的ADC转换值(比如为BGV5)，并将这个值保存到EEPROM中，然后在低压检

// 测的代码中，在实际VCC变化后，测量出的内部BandGap参考电压的ADC转换值(比如为BGVx)，最后

// 通过计算公式: 实际 $\mathrm { V C C } = 5 . 0 \mathrm { V } \ast \mathrm { B G V } 5 / \mathrm { B G V x } .$ ，即可计算出实际的VCC电压值.

// 需要注意的是,第一步的BGV5的基准测量一定要精确.

#include "reg51.h" 

#include "intrins.h" 

#define FOSC 18432000L 

#define BAUD 115200 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

#define URMD 0 //0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

sfr T2H 0xd6; //定时器2高8位

sfr T2L 0xd7; //定时器2低8位

sfr AUXR 0x8e; //辅助寄存器

sfr ADC_CONTR = 0xBC; //ADC控制寄存器

sfr ADC_RES 0xBD; //ADC高8位结果

sfr ADC_LOW2 0xBE; //ADC低2位结果

sfr P1ASF = 0x9D; //P1口第2功能控制寄存器

#define ADC_POWER 0x80 //ADC电源控制位

#define ADC_FLAG 0x10 //ADC完成标志

#define ADC_START 0x08 //ADC起始控制位

#define ADC_SPEEDLL 0x00 //540个时钟

#define ADC_SPEEDL 0x20 //360个时钟

#define ADC_SPEEDH 0x40 //180个时钟

#define ADC_SPEEDHH 0x60 //90个时钟

void InitUart(); 

void InitADC(); 

void SendData(BYTE dat); 

BYTE GetADCResult(); 

void Delay(WORD n); 

void ShowResult(); 

```txt
void main()  
{ InitUart(); //初始化串口 InitADC(); //初始化ADC while (1) { ShowResult(); //显示ADC结果 }
```

```txt
/* 
```

发送ADC结果到PC

```txt
\* 
```

```txt
void ShowResult() 
```

```txt
{ SendData(GetADCResult()); //显示ADC高8位结果 // SendData(ADC_LOW2); //显示低2位结果 }
```

```txt
/* 
```

读取ADC结果

```txt
\* 
```

```txt
BYTE GetADCRsult() 
```

```txt
ADC_CONTR = ADC_POWER | ADC_SPEEDDLL | 0 | ADC_START; 
```

```txt
_nop_(); //等待4个NOP
```

```txt
\_nop\_(); 
```

```txt
\_nop\_(); 
```

```txt
\_nop\_(); 
```

```javascript
while(!ADC_CONTR&ADC_FLAG);//等待ADC转换完成
```

ADC_CONTR $\& =$ ~ADC_FLAG; //Close ADC 

$\mathrm{P2 = ADC\_RES}$ 

```txt
return ADC_RES; //返回ADC结果
```

```txt
\*/ 
```

初始化串口

```txt
\* 
```

```txt
void InitUart() 
```

{ SCON $= \quad 0\mathrm{x}5\mathrm{a};$ //设置串口为8位可变波特率

```txt
if URMD 0 
```

```txt
T2L 0xd8; //设置波特率重装值
```

```txt
T2H 0xff; //115200 bps(65536-18432000/4/115200) 
```

```javascript
AUXR = 0x14; //T2为1T模式, 并启动定时器2
```

AUXR $| =$ 0x01; //选择定时器2为串口1的波特率发生器

```txt
elif URMD 1 
```

```txt
AUXR = 0x40; //定时器1为1T模式
```

TMOD $= \quad 0\mathrm{x}00;$ //定时器1为模式0(16位自动重载)

```txt
TL1 0xd8; //设置波特率重装值
```

```txt
TH1 = 0xff; //115200 bps(65536-18432000/4/115200) 
```

```txt
TR1 1; //定时器1开始启动
```


#else


TMOD $=$ 0x20; //设置定时器1为8位自动重装载模式  
AUXR $=$ 0x40; //定时器1为1T模式  
TH1 $=$ TL1 $=$ 0xffb; //115200 bps(256-18432000/32/115200)  
TR1 $= 1$ ：  
endif  
}  
/*  
初始化ADC*/  
void InitADC()  
{P1ASF $= 0\mathrm{x}00$ ADC_RES $= 0$ ADC_CONTR $\equiv$ ADC_POWER|ADC_SPEEDLL;Delay(2); //ADC上电并延时  
}  
/*  
发送串口数据*/  
void SendData(BYTE dat)  
{while(!TI); //等待前一个数据发送完成TI $= 0$ ： //清除发送标志SBUF $\equiv$ dat; //发送当前数据  
}  
/*  
软件延时*/  
void Delay(WORD n)  
{WORD x;while(n--）{x $= 5000$ while(x--);}

# 2. 汇编程序：

/*- -*/ 

/* --- STC MCU Limited - -*/ 

/* --- STC15W4K60S4 系列 ADC第9通道应用举例- -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com --*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/* -*/ 

//本示例在Keil开发环境下请选择Intel的8058芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

# //说明:

// ADC的第9通道是用来测试内部BandGap参考电压的，由于内部BandGap参考电压很稳定，不会随芯// 片的工作电压的改变而变化，所以可以通过测量内部BandGap参考电压，然后通过ADC的值便可反推// 出VCC的电压，从而用户可以实现自己的低压检测功能.

// ADC的第9通道的测量方法：首先将P1ASF初始化为0，即关闭所有P1口的模拟功能然后通过正常的// ADC转换的方法读取第0通道的值，即可通过ADC的第9通道读取当前内部BandGap参考电压值.

// 用户实现自己的低压检测功能的实现方法：首先用户需要在VCC很精准的情况下(比如5.0V)，测量// 出内部BandGap参考电压的ADC转换值(比如为BGV5)，并将这个值保存到EEPROM中，然后在低压检// 测的代码中，在实际VCC变化后，测量出的内部BandGap参考电压的ADC转换值(比如为BGVx)，最后// 通过计算公式: 实际 $\mathrm { V C C } = 5 . 0 \mathrm { V } * \mathrm { B G V } 5 / \mathrm { B G V x }$ ，即可计算出实际的VCC电压值.

// 需要注意的是,第一步的BGV5的基准测量一定要精确.

#define URMD 0 

//0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

T2H DATA 0D6H 

;定时器2高8位

T2L DATA 0D7H 

;定时器2低8位

AUXR DATA 08EH 

;辅助寄存器

ADC_CONTR EQU 0BCH 

;ADC控制寄存器

ADC_RES EQU 0BDH 

;ADC高8位结果

ADC_LOW2 EQU 0BEH 

;ADC低2位结果

P1ASF EQU 09DH 

;P1口第2功能控制寄存器

ADC_POWER EQU 80H 

;ADC电源控制位

ADC_FLAG EQU 10H 

;ADC完成标志

ADC_START EQU 08H 

;ADC起始控制位

ADC_SPEEDLL EQU 00H 

;540个时钟

```txt
ADC_SPEEDL EQU 20H ;360个时钟 ADC_SPEEDH EQU 40H ;180个时钟 ADC_SPEEDHH EQU 60H ;90个时钟
```

ORG 0000H 

LJMP MAIN 

ORG 0100H 

```txt
MAIN: LCALL INIT_UART ;初始化串口 LCALLINIT_ADC ;初始化ADC
```

```txt
NEXT: LCALL SHOW_result ;显示通道0的结果 SJMP NEXT
```

```txt
/ 
```

```txt
;发送ADC结果到PCMCU
```

```txt
SHOW.Result:  
LCALL GET_ADC.Result ;读取高8位结果  
LCALL SEND_DATA ;显示结果  
; MOV A, ADC_LOW2 ;读取低2位结果  
LCALL SEND_DATA ;显示结果  
RET
```

```lisp
;  
;读取ADC结果  
:
```

```txt
GET_ADC_result:  
MOV A, #ADC_POWER | ADC_SPEEDLL | 0 | ADC_START  
MOV ADC_CONTR, A;开始AD转换  
NOP ;等待4个NOP  
NOP
```

```csv
WAIT: MOV A, ADC_CONTR ;等待ADC转换完成  
JNB ACC.4, WAIT ;ADC_FLAG(ADC_CONTR.4)  
ANL ADC_CONTR, #NOT ADC_FLAG ;清ADC标志
```

MOV A, ADC_RES 

;返回ADC结果

RET 

;/*- 

;初始化ADC

-*/ 

INIT_ADC: 

MOV P1ASF, #00H 

;不设置P1口为模拟口

MOV ADC_RES, #0 

;清除结果寄存器

MOV ADC_CONTR, #ADC_POWER | ADC_SPEEDLL 

;ADC上电并延时

MOV A, #2 

LCALL DELAY 

RET 

;/*-- 

;初始化串口

-*/ 

INIT_UART: 

MOV SCON, #5AH 

;设置串口为8位可变波特率

#if URMD $\qquad = = \quad 0$ 

;设置波特率重装值(65536-18432000/4/115200)

MOV T2L, #0D8H 

MOV T2H, #0FFH 

MOV AUXR, #14H 

;T2为1T模式, 并启动定时器2

ORL AUXR, #01H 

;选择定时器2为串口1的波特率发生器

#elif URMD $= = 1$ 

MOV AUXR, #40H 

;定时器1为1T模式

MOV TMOD, #00H 

;定时器1为模式0(16位自动重载)

MOV TL1, #0D8H 

;设置波特率重装值(65536-18432000/4/115200)

MOV TH1, #0FFH 

;定时器1开始运行

SETB TR1 

#else 

MOV TMOD, #20H 

;设置定时器1为8位自动重装载模式

MOV AUXR, #40H 

;定时器1为1T模式

MOV TL1, #0FBH 

;115200 bps(256 - 18432000/32/115200) 

MOV TH1, #0FBH 

SETB TR1 

#endif RET 

;/*- 

;发送串口数据

*/ 

SEND_DATA: 

JNB TI, $ 

;等待前一个数据发送完成

CLR TI 

;清除发送标志

MOV SBUF, A 

;发送当前数据

RET 

;/*-- 

;软件延时

-*/ 

DELAY: 

MOV R2, A 

CLR A 

MOV R0, A 

MOV R1, A 

DELAY1: 

DJNZ R0, DELAY1 

DJNZ R1, DELAY1 

DJNZ R2, DELAY1 

RET 

END 

# 10.8 利用新增的ADC第9通道测量外部电压或外部电池电压利用内部参考电压BandGap电压测量

ADC的第9通道是用来测试内部BandGap参考电压的，由于内部BandGap参考电压很稳定，约为1.27V，不会随芯片的工作电压的改变而变化，所以可以通过测量内部BandGap参考电压，然后通过ADC的值便可反推出外部电压或外部电池电压，从而用户可以测量外部电压或外部电池电压。

ADC的第9通道的测量方法：首先将P1ASF初始化为0，即关闭所有P1口的模拟功能然后通过正常的ADC转换的方法读取第0通道的值，即可通过ADC的第9通道读取当前内部BandGap参考电压值，约为1.27V。

测量外部电压或外部电池电压的方法：首先用户需要在外部电压或外部电池电压很精准的情况下(比如5.0V)，测量出内部BandGap参考电压的ADC转换值(比如为BGV5)，并将这个值保存到EEPROM中，然后在实际的外部电压或外部电池电压变化后，测量出的内部BandGap参考电压的ADC转换值(比如为BGVx)，最后通过计算公式: 实际外部电压或外部电池电压 $= 5 . 0 \mathrm { V } \ ^ { * }$ BGV5 / BGVx，即可计算出实际的外部电压或外部电池电压值，需要注意的是,第一步的BGV5的基准测量一定要精确。

# 10.9 利用BandGap电压精确测量外部输入电压值及测试程序

ADC的第9通道是用来测试内部BandGap参考电压的，由于内部BandGap参考电压很稳定，不会随芯片的工作电压的改变而变化，所以可以通过两次测量和一次计算便可得到外部的精确电压，公式如下：

$$
\begin{array}{l} \frac {\mathrm {A D C} _ {\mathrm {b g}}}{\mathrm {V} _ {\mathrm {b g}}} = \frac {1 0 2 3}{\mathrm {V c c}} \\ \frac {\mathrm {A D C x}}{\mathrm {V x}} = \frac {1 0 2 3}{\mathrm {V c c}} \\ \end{array}
$$

由于两次测量的时间间隔很短,Vcc的电压在此期间的波动可忽略不计从而可推出：

$$
\frac {\mathrm {A D C} _ {\mathrm {b g}}}{\mathrm {V} _ {\mathrm {b g}}} = \frac {\mathrm {A D C x}}{\mathrm {V} _ {\mathrm {X}}}, \text {进 一 步 得 出} \mathrm {V} _ {\mathrm {X}} = \frac {\mathrm {V} _ {\mathrm {b g}} * \mathrm {A D C x}}{\mathrm {A D C} _ {\mathrm {b g}}}
$$

其中： $\mathrm { \Delta A D C _ { \mathrm { b g } } }$ 为Bandgap电压的ADC测量值

$\mathrm { V _ { b g } }$ 为实际Bandgap的电压值,在单片机进行CP测试时记录的参数,单位为毫伏(mV)

ADCx为外部输入电压的ADC测量值

Vx外部输入电压的实际电压值,单位为毫伏(mV)

具体的测试方法：首先将P1ASF初始化为0,即关闭所有P1口的模拟功能然后通过正常的ADC转换的方法读取第0通道的值,即可通过ADC的第9通道读取当前内部BandGap参考电压值$\mathrm { \Delta A D C _ { \mathrm { b g } } }$ ,然后测量有外部电压输入的ADC通道,测量出外部输入电压的ADC测量值ADCx,接下来$\mathrm { V x } = \frac { \mathrm { V _ { \mathrm { b g } } * A D C x } } { \mathrm { A D C _ { \mathrm { b g } } } } \mathrm { , }$ Vbg从RAM区或者ROM区读取实际Bandgap的电压值Vbg,最后通过公式 ,即可计ADCbg算出外部输入电压的实际电压值Vx。

利用BandGap电压精确测量外部输入电压值的测试程序如下：

/* -*/ 

/* --- STC MCU Limited - -*/ 

/* --- STC15W4K60S4 系列 通过BandGap电压精确测量外部输入电压值举例-----*/

/* --- Mobile: (86)13922805190 - -*/ 

/* --- Fax: 86-755-82905966 - -*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/* */ 

//本示例在Keil开发环境下请选择Intel的8058芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

//说明:

// ADC的第9通道是用来测试内部BandGap参考电压的,由于内部BandGap参考电

//压很稳定,不会随芯片的工作电压的改变而变化,所以可以通过两次测量和一次计算

//便可得到外部的精确电压.公式如下:

//ADCbg / ${ \mathrm { V b g } } = 1 0 2 3 { \mathrm { ~ , ~ } }$ / VCC 

//ADCx / Vx = 1023 / VCC 

//由于两次测量的时间间隔很短,VCC的电压在此期间的波动可忽略不计

//从而可推出 $\mathrm { A D C b g } / \mathrm { V b g } = \mathrm { A D C x } / \mathrm { V x }$ $=$ 

//进一步得出 Vx = Vbg * ADCx / ADCbg

//其中:ADCbg为Bandgap电压的ADC测量值

// Vbg为实际Bandgap的电压值,在单片机进行CP测试时记录的参数,单位为毫伏(mV)

// ADCx为外部输入电压的ADC测量值

// $\mathrm { V x }$ 外部输入电压的实际电压值,单位为毫伏(mV)

// 

//具体的测试方法:首先将P1ASF初始化为0,即关闭所有P1口的模拟功能

//然后通过正常的ADC转换的方法读取第0通道的值,即可通过ADC的第9通道读取当前

//内部BandGap参考电压值ADCbg,然后测量有外部电压输入的ADC通道,测量出

//外部输入电压的ADC测量值ADCx,接下来从RAM区或者ROM区读取实际Bandgap的电压值Vbg,

//最后通过公式Vx = Vbg * ADCx / ADCbg,即可计算出外部输入电压的实际电压值Vx

//- 

WORD idata Vbg_RAM _at_ 0xef; //对于只有256字节RAM的MCU存放地址为0EFH

//WORD idata Vbg_RAM _at_ 0x6f; //对于只有128字节RAM的MCU存放地址为06FH

//注意:需要在下载代码时选择"在ID号前添加重要测试参数"选项,才可在程序中获取此参数

//WORD code Vbg_ROM _at_ 0x03f7; //1K程序空间的MCU

//WORD code Vbg_ROM _at_ 0x07f7; //2K程序空间的MCU

//WORD code Vbg_ROM _at_ 0x0bf7; //3K程序空间的MCU

//WORD code Vbg_ROM _at_ 0x0ff7; //4K程序空间的MCU

//WORD code Vbg_ROM _at_ 0x13f7; //5K程序空间的MCU

//WORD code Vbg_ROM _at_ 0x1ff7; //8K程序空间的MCU

//WORD code Vbg_ROM _at_ 0x27f7; //10K程序空间的MCU

//WORD code Vbg_ROM _at_ 0x2ff7; //12K程序空间的MCU

//WORD code Vbg_ROM _at_ 0x3ff7; //16K程序空间的MCU

```c
//WORD code Vbg-ROM_at_0x4ff7; //20K程序空间的MCU  
//WORD code Vbg-ROM_at_0x5ff7; //24K程序空间的MCU  
//WORD code Vbg-ROM_at_0x6ff7; //28K程序空间的MCU  
//WORD code Vbg-ROM_at_0x7ff7; //32K程序空间的MCU  
//WORD code Vbg-ROM_at_0x9ff7; //40K程序空间的MCU  
//WORD code Vbg-ROM_at_0xbff7; //48K程序空间的MCU  
//WORD code Vbg-ROM_at_0xcff7; //52K程序空间的MCU  
//WORD code Vbg-ROM_at_0xdff7; //56K程序空间的MCU  
WORD code Vbg-ROM_at_0xeff7; //60K程序空间的MCU
```

```c
sfr ADC_CONTR = 0xBC; //ADC控制寄存器  
sfr ADC_RES = 0xCD; //ADC高8位结果  
sfr ADC_LOW2 = 0xBE; //ADC低2位结果  
sfr P1ASF = 0x9D; //P1口第2功能控制寄存器  
#define ADC_POWER 0x80 //ADC电源控制位  
#define ADC_FLAG 0x10 //ADC完成标志  
#define ADC_START 0x08 //ADC起始控制位  
#define ADC_SPEEDLL 0x00 //540个时钟  
#define ADC_SPEEDL 0x20 //360个时钟  
#define ADC_SPEEDH 0x40 //180个时钟  
#define ADC_SPEEDHH 0x60 //90个时钟
```

/*_ 

软件延时

* 

void Delay(WORD n)   
{ WORD x; while (n--） { $\mathrm{x} = 5000$ · while $(\mathbf{x} - - )$ 1 }   
void main() { BYTE ADCbg; BYTE ADCx; WORD Vx; 


//第一步:通过ADC的第9通道测试Bandgap电压的ADC测量值


```c
ADC_RES = 0; //清除结果寄存器  
P1ASF = 0x00; //不设置P1ASF,即可从ADC的第9通道读取内部Bandgap电压的ADC测量值  
ADC_CONTR = ADC_POWER | ADC_SPEEDLL;  
Delay(2); //ADC上电并延时  
ADC_CONTR = ADC_POWER | ADC_SPEEDDLL | 0 | ADC_START;  
_nop(); //等待4个NOP  
_nop();  
_nop();  
_nop();  
_nop();  
while (!ADC_CONTR & ADC_FLAG); //等待ADC转换完成  
ADC_CONTR &= ~ADC_FLAG; //清除ADC标志  
ADCbg = ADC_RES;
```


//第二步:通过ADC的第2通道测试外部输入电压的ADC测量值


```c
ADC_RES = 0; //清除结果寄存器  
P1ASF = 0x02; //设置P1.1口为模拟通道  
ADC_CONTR = ADC_POWER | ADC_SPEEDDLL;  
Delay(2); //ADC上电并延时  
ADC_CONTR = ADC_POWER | ADC_SPEEDDLL | 1 | ADC_START;  
_nop(); //等待4个NOP  
_nop();  
_nop();  
_nop();  
while (!ADC_CONTR & ADC_FLAG); //等待ADC转换完成  
ADC_CONTR &= ~ADC_FLAG; //清除ADC标志  
ADCx = ADC_RES;
```


//第三步:通过公式计算外部输入的实际电压值


$\mathrm{Vx} = \mathrm{Vbg\_RAM}*\mathrm{ADCx} / \mathrm{ADCbg};$ //使用RAM中的Bandgap电压参数进行计算//Vx $=$ Vbg_ROM\*ADCx/ADCbg; //使用ROM中的Bandgap电压参数进行计算while(1);

# 10.10 利用SPI接口扩展12位ADC(TLC2543)的应用线路图

TLC2参考

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7b3a923540678a113451fd9c77f566804fe3798a038bb8675a90794d9b9dc312.jpg)


# 第11章 STC15系列CCP/PAC/PWM/DAC应用

STC15系列部分单片机集成了3路可编程计数器阵列(CCP/PCA)模块，可用于软件定时器、外部脉冲的捕捉、高速脉冲输出以及脉宽调制(PWM)输出。

下表总结了STC15系列单片机内部集成了CCP/PCA/PWM功能的单片机型号：

<table><tr><td>特殊外围设备
单片机型号</td><td>8路10位高速
A/D转换器</td><td>CCP/PCA/PWM功能</td><td>1组高速同步串行口SPI</td></tr><tr><td>STC15W4K60S4系列</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td>STC15F2K60S2系列</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td>STC15W1K16S系列</td><td></td><td></td><td>✓</td></tr><tr><td>STC15W408S系列</td><td></td><td></td><td>✓</td></tr><tr><td>STC15W408AS系列</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td>STC15W201S系列</td><td></td><td></td><td></td></tr><tr><td>STC15F408AD系列</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td>STC15F101W系列</td><td></td><td></td><td></td></tr></table>

上表中 $\surd$ 表示对应的系列有相应的功能。

STC15W4K60S4系列、STC15F2K60S2系列和STC15F408AD系列单片机的CCP/PWM/PCA均可以在3组不同管脚之间进行切换：

$$
[ \mathrm {C C P 0 / P 1 . 1}, \mathrm {C C P 1 / P 1 . 0}, \mathrm {C C P 2 / C C P 2 \_ 2 / P 3 . 7} ];
$$

$$
[ \mathrm {C C P 0} _ {-} 2 / \mathrm {P} 3. 5, \mathrm {C C P 1} _ {-} 2 / \mathrm {P} 3. 6, \mathrm {C C P 2} / \mathrm {C C P 2} _ {-} 2 / \mathrm {P} 3. 7 ];
$$

$$
[ \mathrm {C C P 0} _ {-} 3 / \mathrm {P} 2. 5, \mathrm {C C P 1} _ {-} 3 / \mathrm {P} 2. 6, \mathrm {C C P 2} _ {-} 3 / \mathrm {P} 2. 7 ] 。
$$

STC15W408AS系列单片机的CCP/PWM/PCA可以在2组不同管脚之间进行切换：

$$
[ \mathrm {C C P 0 / P 1 . 1}, \mathrm {C C P 1 / P 1 . 0}, \mathrm {C C P 2 / C C P 2 \_ 2 / P 3 . 7} ];
$$

$$
[ \mathrm {C C P 0} _ {-} 2 / \mathrm {P} 3. 5, \mathrm {C C P 1} _ {-} 2 / \mathrm {P} 3. 6, \mathrm {C C P 2} / \mathrm {C C P 2} _ {-} 2 / \mathrm {P} 3. 7 ] 。
$$

STC15W1K16S系列、STC15W408S系列、STC15W201S系列和STC15F101W单片机没有CCP/PWM/PCA功能。

# 11.1 与CCP/PWM/PCA应用有关的特殊功能寄存器

STC15系列 1T 8051单片机 CCP/PCA/PWM特殊功能寄存器表 CCP/PCA/PWM SFRs

<table><tr><td rowspan="2">符号</td><td rowspan="2">描述</td><td rowspan="2">地址</td><td colspan="8">位地址及其符号</td><td rowspan="2">复位值</td></tr><tr><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>CCON</td><td>PCA Control Register</td><td>D8H</td><td>CF</td><td>CR</td><td>-</td><td>-</td><td>-</td><td>CCF2</td><td>CCF1</td><td>CCF0</td><td>00xx.xx00</td></tr><tr><td>CMOD</td><td>PCA Mode Register</td><td>D9H</td><td>CIDL</td><td>-</td><td>-</td><td>-</td><td>CPS2</td><td>CPS1</td><td>CPS0</td><td>ECF</td><td>0xxx,0000</td></tr><tr><td>CCAPM0</td><td>PCA Module 0 Mode Register</td><td>DAH</td><td>-</td><td>ECOM0</td><td>CAPP0</td><td>CAPN0</td><td>MAT0</td><td>TOG0</td><td>PWM0</td><td>ECCF0</td><td>x000,0000</td></tr><tr><td>CCAPM1</td><td>PCA Module 1 Mode Register</td><td>DBH</td><td>-</td><td>ECOM1</td><td>CAPP1</td><td>CAPN1</td><td>MAT1</td><td>TOG1</td><td>PWM1</td><td>ECCF1</td><td>x000,0000</td></tr><tr><td>CCAPM2</td><td>PCA Module 2 Mode Register</td><td>DCH</td><td>-</td><td>ECOM2</td><td>CAPP2</td><td>CAPN2</td><td>MAT2</td><td>TOG2</td><td>PWM2</td><td>ECCF2</td><td>x000,0000</td></tr><tr><td>CL</td><td>PCA Base Timer Low</td><td>E9H</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0000,0000</td></tr><tr><td>CH</td><td>PCA Base Timer High</td><td>F9H</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0000,0000</td></tr><tr><td>CCAP0L</td><td>PCA Module-0 Capture Register Low</td><td>EAH</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0000,0000</td></tr><tr><td>CCAP0H</td><td>PCA Module-0 Capture Register High</td><td>FAH</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0000,0000</td></tr><tr><td>CCAP1L</td><td>PCA Module-1 Capture Register Low</td><td>EBH</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0000,0000</td></tr><tr><td>CCAP1H</td><td>PCA Module-1 Capture Register High</td><td>FBH</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0000,0000</td></tr><tr><td>CCAP2L</td><td>PCA Module-2 Capture Register Low</td><td>ECH</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0000,0000</td></tr><tr><td>CCAP2H</td><td>PCA Module-2 Capture Register High</td><td>FCH</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0000,0000</td></tr><tr><td>PCA_PWM0</td><td>PCA PWM Mode Auxiliary Register 0</td><td>F2H</td><td>EBS0_1</td><td>EBS0_0</td><td>-</td><td>-</td><td>-</td><td>-</td><td>EPC0H</td><td>EPC0L</td><td>00xx.xx00</td></tr><tr><td>PCA_PWM1</td><td>PCA PWM Mode Auxiliary Register 1</td><td>F3H</td><td>EBS1_1</td><td>EBS1_0</td><td>-</td><td>-</td><td>-</td><td>-</td><td>EPC1H</td><td>EPC1L</td><td>00xx.xx00</td></tr><tr><td>PCA_PWM2</td><td>PCA PWM Mode Auxiliary Register 2</td><td>F4H</td><td>EBS2_1</td><td>EBS2_0</td><td>-</td><td>-</td><td>-</td><td>-</td><td>EPC2H</td><td>EPC2L</td><td>00xx.xx00</td></tr><tr><td>AUXR1 P_SW1</td><td>Auxiliary Register 1</td><td>A2H</td><td>S1_S1</td><td>S1_S0</td><td>CCP_S1</td><td>CCP_S0</td><td>SPI_S1</td><td>SPI_S0</td><td>-</td><td>DPS</td><td>0000,0000</td></tr></table>

# 1. PCA工作模式寄存器CMOD

PCA工作模式寄存器的格式如下：


CMOD : PCA工作模式寄存器


<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>CMOD</td><td>D9H</td><td>name</td><td>CIDL</td><td>-</td><td>-</td><td>-</td><td>CPS2</td><td>CPS1</td><td>CPS0</td><td>ECF</td></tr></table>

CIDL：空闲模式下是否停止PCA计数的控制位。

当CIDL ${ } _ { , = 0 }$ 时， PCA计数器继续工作

当CIDL $_ { , = 1 }$ 时， PCA计数器停止工作。

CPS2、CPS1、CPS0：PCA计数脉冲源选择控制位。PCA计数脉冲选择如下表所示。

<table><tr><td>CPS2</td><td>CPS1</td><td>CPS0</td><td>选择CCP/PCA/PWM时钟源输入</td></tr><tr><td>0</td><td>0</td><td>0</td><td>0,系统时钟,SYSclk/12</td></tr><tr><td>0</td><td>0</td><td>1</td><td>1,系统时钟,SYSclk/2</td></tr><tr><td>0</td><td>1</td><td>0</td><td>2,定时器0的溢出脉冲。由于定时器0可以工作在1T模式,所以可以达到计一个时钟就溢出,从而达到最高频率CPU工作时钟SYSclk。通过改变定时器0的溢出率,可以实现可调频率的PWM输出</td></tr><tr><td>0</td><td>1</td><td>1</td><td>3, ECI/P1.2(或P3.4或P2.4)脚输入的外部时钟(最大速率=SYSclk/2)</td></tr><tr><td>1</td><td>0</td><td>0</td><td>4,系统时钟,SYSclk</td></tr><tr><td>1</td><td>0</td><td>1</td><td>5,系统时钟/4,SYSclk/4</td></tr><tr><td>1</td><td>1</td><td>0</td><td>6,系统时钟/6,SYSclk/6</td></tr><tr><td>1</td><td>1</td><td>1</td><td>7,系统时钟/8,SYSclk/8</td></tr></table>

例如，CPS2/CPS1/CPS0 = 1/0/0时，CCP/PCA/PWM的时钟源是SYSclk，不用定时器0PWM的频率为SYSclk/256

如果要用 �/3来作为PCA的时钟源, �时 �T0工作在1T模式,计 3个脉冲即产生溢出 用T0的溢出可对系统时钟进行1 ~ 65536级分频(T0 �装载模式)

ECF：PCA计数溢出中断使能 。

当 $\mathrm { E C F } = 0$ $= 0$ 时，禁止寄存器CCON中CF位的中断；

当 $\mathrm { E C F } = 1$ $= 1$ 时，允许寄存器CCON中CF位的中断

# 2. PCA控制寄存器CCON

PCA控制寄存器的格式如下：

CCON : PCA控制控制寄存器

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>CCON</td><td>D8H</td><td>name</td><td>CF</td><td>CR</td><td>-</td><td>-</td><td>-</td><td>CCF2</td><td>CCF1</td><td>CCF0</td></tr></table>

CF：PCA计数器阵列溢出标志位。当PCA计数器溢出时 CF由硬件置位。如果CMOD寄存器的ECF位置位， CF标志可用来产生中断。CF位可通过硬件或软件置位， 但只可通过软件清零。

CR：PCA计数器阵列运行控制位。该位通过软件置位， 用来起动PCA计数器阵列计数。该位通过软件清零， 用来关闭PCA计数器。

CCF2：PCA模块2中断标志。当出现匹配或捕获时该位由硬件置位。该位必须通过软件清零。

CCF1：PCA模块1中断标志。当出现匹配或捕获时该位由硬件置位。该位必须通过软件清零。

CCF0：PCA模块0中断标志。当出现匹配或捕获时该位由硬件置位。该位必须通过软件清零。

# 3. PCA比较/捕获寄存器CCAPM0、CCAPM1和CCAPM2

PCA模块0的比较/捕获寄存器的格式如下：

CCAPM0 : PCA模块0的比较/捕获寄存器

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>CCAPM0</td><td>DAH</td><td>name</td><td>-</td><td>ECOM0</td><td>CAPP0</td><td>CAPN0</td><td>MAT0</td><td>TOGO</td><td>PWM0</td><td>ECCF0</td></tr></table>

B7：保留为将来之用。

ECOM0：允许比较器功能控制位

当ECOM0＝1时，允许

CAPP0： 正捕获控制位

当CAPP0 $= 1$ 时，允许 ��

CAPN0：负捕获控制位

当CAPN0 $= 1$ 时 ��降

MAT0： 匹配控制位

当MAT0＝1时，PCA计数值与模块的比较/捕获寄存器的值的匹配将置位CCON寄存器的中断标志位CCF0。

TOG0： 翻转控制位

当 $\mathrm { T O G 0 } { = } 1$ 时，工作在PCA高速脉冲输出 PCA计数器的值与模块的比较/捕获寄存器的值的匹配将使CCP0脚翻转。

(CCP0/PCA0/PWM0/P1.1或CCP0_2/PCA0/PWM0/P3.5或CCP0_3/PCA0/PWM0/P2.5)

PWM0： 脉宽调节模式。

当PWM0＝1时， CCP0脚用作脉宽调节输出。

(CCP0/PCA0/PWM0/P1.1或CCP0_2/PCA0/PWM0/P3.5或CCP0_3/PCA0/PWM0/P2.5)

ECCF0： 使能CCF0中断。使能寄存器CCON的比较/捕获标志CCF0， 用来产生中断。

PCA模块1的比较/捕获寄存器的格式如下：

CCAPM1 : PCA模块1的比较/捕获寄存器

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>CCAPM1</td><td>DBH</td><td>name</td><td>-</td><td>ECOM1</td><td>CAPP1</td><td>CAPN1</td><td>MAT1</td><td>TOG1</td><td>PWM1</td><td>ECCF1</td></tr></table>

B7：保留为将来之用。

ECOM1：允许比较器功能控制位

当ECOM1 $= 1$ 时，允许

CAPP1： 正捕获控制位

当CAPP1 $= 1$ 时，允许 ��

CAPN1：负捕获控制位

当CAPN1 $= 1$ 时 ��降

MAT1： 匹配控制位

当MAT1 $= 1$ 时，PCA计数值与模块的比较/捕获寄存器的值的匹配将置位CCON寄存器的中断标志位CCF1。

TOG1： 翻转控制位

当TOG1 $=$ 1时，工作在PCA高速脉冲输出 PCA计数器的值与模块的比较/捕获寄存器的值的匹配将使CCP1脚翻转。

(CCP1/PCA1/PWM1/P1.0或CCP1_2/PCA1/PWM1/P3.6或CCP1_3/PCA1/PWM1/P2.6)

PWM1： 脉宽调节模式。

当PWM1 $=$ 1时， CCP1脚用作脉宽调节输出。

(CCP1/PCA1/PWM1/P1.0或CCP1_2/PCA1/PWM1/P3.6或CCP1_3/PCA1/PWM1/P2.6)

ECCF1： 使能CCF1中断。使能寄存器CCON的比较/捕获标志CCF1， 用来产生中断。

PCA模块2的比较/捕获寄存器的格式如下：

CCAPM2 : PCA模块2的比较/捕获寄存器

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>CCAPM2</td><td>DCH</td><td>name</td><td>-</td><td>ECOM2</td><td>CAPP2</td><td>CAPN2</td><td>MAT2</td><td>TOG2</td><td>PWM2</td><td>ECCF2</td></tr></table>

B7：保留为将来之用。

ECOM2：允许比较器功能控制位

当ECOM2＝2时，允许

CAPP2： 正捕获控制位

当CAPP2 $= 1$ 时，允许 ��

CAPN2：负捕获控制位

当CAPN2 $= 1$ 时 ��降

MAT2： 匹配控制位

当MAT2 $= 1$ 时，PCA计数值与模块的比较/捕获寄存器的值的匹配将置位CCON寄存器的中断标志位CCF2。

TOG2： 翻转控制位

当TOG2＝1时，工作在PCA高速脉冲输出 PCA计数器的值与模块的比较/捕获寄存器的值的匹配将使CCP2脚翻转。

(CCP2/PCA2/PWM2/P3.7或CCP2/PCA2/PWM2/P2.7)

PWM2： 脉宽调节模式。

当PWM2 $= 1$ 时， CCP2脚用作脉宽调节输出。

(CCP2/PCA2/PWM2/P3.7或CCP2/PCA2/PWM2/P2.7)

ECCF2： 使能CCF2中断。使能寄存器CCON的比较/捕获标志CCF2， 用来产生中断。

# 4. PCA的16位计数器 — 低8位CL和高8位CH

CL和CH地址分别为E9H和F9H，复位值均为00H，用于保存PCA的装载值。

# 5. PCA捕捉/比较寄存器 — CCAPnL(低位字节)和CCAPnH(高位字节)

当PCA模块用于捕获或比较时，它们用于保存各个模块的16位捕捉计数值；当PCA模块用于PWM模式时，它们用来控制输出的占空比。其中， $\mathrm { n } { = } 0$ 、1、2，分别对应模块0、模块1和模块2。复位值均为00H。它们对应的地址分别为：

CCAP0L — EAH、CCAP0H — FAH：模块0的捕捉/比较寄存器。

CCAP1L — EBH、CCAP1H — FBH：模块1的捕捉/比较寄存器。

CCAP2L — ECH、CCAP2H — FCH：模块2的捕捉/比较寄存器。

# 6. PCA模块PWM寄存器PCA_PWM0、PCA_PWM1和PCA_PWM2

PCA模块0的PWM寄存器的格式如下：

PCA_PWM0 : PCA模块0的PWM寄存器

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>PCA_PWM0</td><td>F2H</td><td>name</td><td>EBS0_1</td><td>EBS0_0</td><td>-</td><td>-</td><td>-</td><td>-</td><td>EPC0H</td><td>EPC0L</td></tr></table>

EBS0_1 , EBS0_0：当PCA模块0工作于PWM模式时的功能选择位。

0 , 0 : PCA模块0工作于8位PWM功能；

0 , 1 : PCA模块0工作于7位PWM功能；

1 ， 0 ：PCA模块0工作于6位PWM功能；

1 ， 1 ：无效，PCA模块0仍工作于8位PWM模式.

EPC0H：在PWM模式下，与CCAP0H组成9位数。

EPC0L：在PWM模式下，与CCAP0L组成9位数。

PCA模块1的PWM寄存器的格式如下：

PCA_PWM1 : PCA模块1的PWM寄存器

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>PCA_PWM1</td><td>F3H</td><td>name</td><td>EBS1_1</td><td>EBS1_0</td><td>-</td><td>-</td><td>-</td><td>-</td><td>EPC1H</td><td>EPC1L</td></tr></table>

EBS1_1 , EBS1_0：当PCA模块1工作于PWM模式时的功能选择位。

0 , 0 : PCA模块1工作于8位PWM功能；

0 , 1 : PCA模块1工作于7位PWM功能；

1 ， 0 ：PCA模块1工作于6位PWM功能；

1 ， 1 ：无效，PCA模块1仍工作于8位PWM.

EPC1H：在PWM模式下，与CCAP1H组成9位数。

EPC1L：在PWM模式下，与CCAP1L组成9位数。

PCA模块2的PWM寄存器的格式如下：

PCA_PWM2 : PCA模块2的PWM寄存器

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>PCA_PWM2</td><td>F4H</td><td>name</td><td>EBS2_1</td><td>EBS2_0</td><td>-</td><td>-</td><td>-</td><td>-</td><td>EPC2H</td><td>EPC2L</td></tr></table>

EBS2_1 , EBS2_0：当PCA模块2工作于PWM模式时的功能选择位。

0 , 0 : PCA模块2工作于8位PWM模式；

0 , 1 : PCA模块2工作于7位PWM模式；

1 ， 0 ：PCA模块2工作于6位PWM模式；

1 ， 1 ：无效，PCA模块2仍工作于8位PWM.

EPC2H：在PWM模式下，与CCAP2H组成9位数。

EPC2L：在PWM模式下，与CCAP2L组成9位数。

PCA模块的工作模式设定表如下表所列：


PCA模块工作模式设定�CCAPMn寄存器， ${ \mathtt { n } } = 0 , 1 , 2$ ）


<table><tr><td>EBSn_1</td><td>EBSn_0</td><td>-</td><td>ECOMn</td><td>CAPPn</td><td>CAPNn</td><td>MATn</td><td>TOGn</td><td>PWMn</td><td>ECCFn</td><td>模块功能</td></tr><tr><td>X</td><td>X</td><td></td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td><td>无此操作</td></tr><tr><td>0</td><td>0</td><td></td><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td><td>1</td><td>0</td><td>8位PWM,无中断</td></tr><tr><td>0</td><td>1</td><td></td><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td><td>1</td><td>0</td><td>7位PWM,无中断</td></tr><tr><td>1</td><td>0</td><td></td><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td><td>1</td><td>0</td><td>6位PWM,无中断</td></tr><tr><td>1</td><td>1</td><td></td><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td><td>1</td><td>0</td><td>8位PWM,无中断</td></tr><tr><td>0</td><td>0</td><td></td><td>1</td><td>1</td><td>0</td><td>0</td><td>0</td><td>1</td><td>1</td><td>8位PWM输出,由低变高可产生中断</td></tr><tr><td>0</td><td>1</td><td></td><td>1</td><td>1</td><td>0</td><td>0</td><td>0</td><td>1</td><td>1</td><td>7位PWM输出,由低变高可产生中断</td></tr><tr><td>1</td><td>0</td><td></td><td>1</td><td>1</td><td>0</td><td>0</td><td>0</td><td>1</td><td>1</td><td>6位PWM输出,由低变高可产生中断</td></tr><tr><td>1</td><td>1</td><td></td><td>1</td><td>1</td><td>0</td><td>0</td><td>0</td><td>1</td><td>1</td><td>8位PWM输出,由低变高可产生中断</td></tr><tr><td>0</td><td>0</td><td></td><td>1</td><td>0</td><td>1</td><td>0</td><td>0</td><td>1</td><td>1</td><td>8位PWM输出,由高变低可产生中断</td></tr><tr><td>0</td><td>1</td><td></td><td>1</td><td>0</td><td>1</td><td>0</td><td>0</td><td>1</td><td>1</td><td>7位PWM输出,由高变低可产生中断</td></tr><tr><td>1</td><td>0</td><td></td><td>1</td><td>0</td><td>1</td><td>0</td><td>0</td><td>1</td><td>1</td><td>6位PWM输出,由高变低可产生中断</td></tr><tr><td>1</td><td>1</td><td></td><td>1</td><td>0</td><td>1</td><td>0</td><td>0</td><td>1</td><td>1</td><td>8位PWM输出,由高变低可产生中断</td></tr><tr><td>0</td><td>0</td><td></td><td>1</td><td>1</td><td>1</td><td>0</td><td>0</td><td>1</td><td>1</td><td>8位PWM输出,由低变高或者由高变低均可产生中断</td></tr><tr><td>0</td><td>1</td><td></td><td>1</td><td>1</td><td>1</td><td>0</td><td>0</td><td>1</td><td>1</td><td>7位PWM输出,由低变高或者由高变低均可产生中断</td></tr><tr><td>1</td><td>0</td><td></td><td>1</td><td>1</td><td>1</td><td>0</td><td>0</td><td>1</td><td>1</td><td>6位PWM输出,由低变高或者由高变低均可产生中断</td></tr><tr><td>1</td><td>1</td><td></td><td>1</td><td>1</td><td>1</td><td>0</td><td>0</td><td>1</td><td>1</td><td>8位PWM输出,由低变高或者由高变低均可产生中断</td></tr><tr><td>X</td><td>X</td><td></td><td>X</td><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td><td>X</td><td>16位捕获模式,由CCPn/PCAn的上升沿触发</td></tr><tr><td>X</td><td>X</td><td></td><td>X</td><td>0</td><td>1</td><td>0</td><td>0</td><td>0</td><td>X</td><td>16位捕获模式,由CCPn/PCAn的下降沿触发</td></tr><tr><td>X</td><td>X</td><td></td><td>X</td><td>1</td><td>1</td><td>0</td><td>0</td><td>0</td><td>X</td><td>16位捕获模式 由CCPn/PCAn的跳变触发</td></tr><tr><td>X</td><td>X</td><td></td><td>1</td><td>0</td><td>0</td><td>1</td><td>0</td><td>0</td><td>X</td><td>16位软件定时器</td></tr><tr><td>X</td><td>X</td><td></td><td>1</td><td>0</td><td>0</td><td>1</td><td>1</td><td>0</td><td>X</td><td>16位高速脉冲输出</td></tr></table>

# 7. 将单片机的CCP/PWM/PCA功能在3组管脚之间切换的寄存器AUXR1(P_SW1)

辅助寄存器1的格式如下：

AUXR1/P_SW1 : 外围设备切换控制寄存器 (不可位寻址)

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>7</td><td>6</td><td>5</td><td>4</td><td>3</td><td>2</td><td>1</td><td>0</td><td>Reset Value</td></tr><tr><td>AUXR1
P_SW1</td><td>A2H</td><td>Auxiliary
register 1</td><td>S1_S1</td><td>S1_S0</td><td>CCP_S1</td><td>CCP_S0</td><td>SPI_S1</td><td>SPI_S0</td><td>0</td><td>DPS</td><td>0000,0000</td></tr></table>

<table><tr><td colspan="3">CCP可在3个地方切换,由 CCP_S1 / CCP_S0 两个控制位来选择</td></tr><tr><td>CCP_S1</td><td>CCP_S0</td><td>CCP可在P1/P2/P3之间来回切换</td></tr><tr><td>0</td><td>0</td><td>CCP在[P1.2/ECI,P1.1/CCP0,P1.0/CCP1,P3.7/CCP2]</td></tr><tr><td>0</td><td>1</td><td>CCP在[P3.4/ECI_2,P3.5/CCP0_2,P3.6/CCP1_2,P3.7/CCP2_2]</td></tr><tr><td>1</td><td>0</td><td>CCP在[P2.4/ECI_3,P2.5/CCP0_3,P2.6/CCP1_3,P2.7/CCP2_3]</td></tr><tr><td>1</td><td>1</td><td>无效</td></tr></table>

<table><tr><td colspan="3">串口1/S1可在3个地方切换,由 S1_S0 及 S1_S1 控制位来选择</td></tr><tr><td>S1_S1</td><td>S1_S0</td><td>串口1/S1可在P1/P3之间来回切换</td></tr><tr><td>0</td><td>0</td><td>串口1/S1在[P3.0/RxD,P3.1/TxD]</td></tr><tr><td>0</td><td>1</td><td>串口1/S1在[P3.6/RxD_2,P3.7/TxD_2]</td></tr><tr><td>1</td><td>0</td><td>串口1/S1在[P1.6/RxD_3/XTAL2,P1.7/TxD_3/XTAL1]串口1在P1口时要使用内部时钟</td></tr><tr><td>1</td><td>1</td><td>无效</td></tr></table>

<table><tr><td colspan="3">SPI可在3个地方切换,由 SPI_S1 / SPI_S0 两个控制位来选择</td></tr><tr><td>SPI_S1</td><td>SPI_S0</td><td>SPI可在P1/P2/P4之间来回切换</td></tr><tr><td>0</td><td>0</td><td>SPI在[P1.2/SS,P1.3/MOSI,P1.4/MISO,P1.5/SCLK]</td></tr><tr><td>0</td><td>1</td><td>SPI在[P2.4/SS_2,P2.3/MOSI_2,P2.2/MISO_2,P2.1/SCLK_2]</td></tr><tr><td>1</td><td>0</td><td>SPI在[P5.4/SS_3,P4.0/MOSI_3,P4.1/MISO_3,P4.3/SCLK_3]</td></tr><tr><td>1</td><td>1</td><td>无效</td></tr></table>

DPS：DPTR �re��giste�rs select ��bit. DPTR 寄存器选择位

0: DPTR0 is selected 

DPTR0被选择

1: DPTR1 is selected 

DPTR1被选择

# 11.2 CCP/PWM/PCA模块的结构

STC15系列部分 � 通过AUXR1/P_SW1设置CCP/PCA/PWM从P1口切换到P2口切换到P3口

PCA含有一个特殊的16位定时器，有3个16位的捕获/比较模块与之相连，如下图所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/024b086ba9225a4ea7b667f76999f7e0f7d46b3c4f99dbcb3269e525e80c91f3.jpg)



PCA模块结构


每个模块可编程工作在4种模式下：上升/下降沿 捕获、软件定时器、高速脉冲输出制脉冲输出。

STC15F2K60S2系列： � P1.1/CCP0 或 P3.5/CCP0_2 或 P2.5/CCP0_3；

模块1连接到P1.0/CCP1 或 P3.6/CCP1_2 或 P2.6/CCP1_3；

模块2连接到P3.7/CCP2 或 P3.7/CCP2_2 或 P2.7/CCP2_3。

16位PCA定时器/计数器是3个模块的公共时间基准，其结构如下图所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b598b3ac9a56319a46c2d75eb08c3cb81fbdae91c93b618172830d9f99d4288d.jpg)



PCA 定时器/计数器结构


寄存器CH和CL的内容是正在自由递增计数的16位PCA定时器的值。PCA定时器是3个模块的公共时间基准，可通过编程工作在：1/12系统时钟�、1/8 �钟、1/6 �钟、1/4钟、1/2系统时�钟、 �钟 �STC15W4K60S4系列在P1.2或P3.4口）。定时器的计数源由CMOD特殊功能寄存器中 ��特殊功能寄存器说明）。

CMOD特殊功能寄存器还有2个位与PCA �们分别是：CIDLPCA；ECF，置位时，使能PCA中断，当PCA定时器溢出将PCA计数溢出标志CF�（CCON.7

CCON特殊功能寄存器包含PCA �（CR）和PCA �（CF标志（CCF2/CCF1/CCF0）。通过软件置位CR （�CCON.6）来运行PCA。CR位被清零时PCA当PCA计数器溢出时，CF �（CCON.7）置位,如果CMOD寄存器的ECF位置位,就产生中断。CF只可通过软件清除。CCON寄存器的位 $0 { \sim } 2$ 是PCA �位0对应模块0，位11，位2对应模块2），当发生匹配或比较时由硬件置位。这些标志也只能通过软件清除。所有模块共用一个中断向量。PCA

PCA �们分别是：模块0对应CCAPM0，模块1CCAPM1，模块2对应CCAPM2

当模块发生匹配或比较时，ECCFn �（CCAPMn.0， $\mathtt { n } { } = { } 0$ ，1，2由工作的模块决定）使能CCON 特殊功能寄存器的CCFn

PWM�（CCAPMn.1 

当PCA计数值与模块的捕获/比较寄存器的值相匹配时，如果TOG （�CCAPMn.2块的CCPn

当PCA计数值与模块的捕获/比较寄存器的值相匹配时，如果匹配位MATn�（CCAPMn.3位，CCON寄存器的CCFn

CAPNn�（CCAPMn.4）和CAPPn�（CCAPMn.5 �。CAPNn �沿有效，CAPPn位使能上升沿有效。如果两位都置位，则两种跳变沿都被使能，捕获可在两种跳变沿 产生。

通过置位CCAPMn寄存器的ECOMn �（CCAPMn.6

每个PCA模块还对应另外两个寄存器，CCAPnH和CCAPnL � �保存16位的计数值。当PCA模块用在PWM �们用来控制输出的占空比。

# 11.3 CCP/PCA模块的工作模式

# 11.3.1 捕获模式

PCA模块工作于捕获模式的结构图如下图所示。要使一个PCACCAPMn �（CAPNn和CAPPn）或其中任何一位必须置1。PCA的外部CCPn �CCP0/P1.1,CCP1/P1.0, CCP2/P3.7）的跳变进行采样。当采样到有效跳变时，PCA硬件就将PCA计数器�阵列寄存器�（CH和CL �（CCAPnLCCAPnH

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d37ab84ece7eacb6f6f1d757d48f1809ce82cd9a6e1f77510a55aee630166af4.jpg)



PCA Capture Mode (PCA捕获模式图)


如果CCON特殊功能寄存器中的位CCFn和CCAPMn特殊功能寄存器中产生中断。可在中断服务程序中判断哪一个模块产生了中断，并注意中断标志位的软件清零问题。

# 11.3.2 16位软件定时器模式

16位软件定时器模式结构图如下图所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/4410ebb92671cc688f3114d98db508b170dceaeb372b39c73be9cfed69312345.jpg)



PCA Software Timer Mode / PCA模块的16位软件定时器模式/PCA比较模式


通过置位CCAPMn寄存器的ECOM和MAT位，可使PCA模块用作软件定时器（上图）。PCA定时器的值与模块捕获寄存器的值相比较，当两者相等时，如果位CCFn(在CCON特殊功能寄存器中)和位ECCFn（在CCAPMn特殊功能寄存器中）都置位，将产生中断。

[CH,CL]每隔一定的时间自动加1，时间间隔取决于选择的时钟源。例如，当选择的时钟源为SYSclk/12，每12个时钟周期[CH,CL]加1。当[CH,CL]增加到等于[CCAPnH, CCAPnL]时，CCFn=1，产生中断请求。如果每次PCA模块中断后，在中断服务程序中断给[CCAPnH,CCAPnL]增加一个相同的数值，那么下次中断来临的间隔时间T也是相同的，从而实现了定时功能。定时时间的长短取决于时钟源的选择以及PCA计数器计数值的设置。下面举例说明PCA计数器计数值的计算方法。

假设，系统时钟频率 $\mathrm { S Y S c l k } = 1 8 . 4 3 2 \mathrm { M H z }$ ,选择的时钟源为SYSclk/12,定时时间T为5ms,则PCA计数器计数值为：

PCA计数器的计数值 = T / (( 1 / SYSclk )×12 ) = 0.005 / (( 1 / 18432000)×12 ) = 7680 (10进制数)$= 1 \mathrm { E 0 0 H }$ (16进制数)

也就是说，PCA计数器计数1E00H次，定时时间才是 $5 \mathrm { m s }$ ，这也 就是每次给[CCAPnH,CCAPnL]增加的数值(步长)。

# 11.3.3 高速脉冲输出模式

该模式中(下图)，当PCA计数器的计数值与模块捕获寄存器的值相匹配时,PCA模块的CCPn输出将发生翻转。要激活高速脉冲输出模式,CCAPMn寄存器

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/fd05734a374bcd38199e3e45cae962d99159704610d37f89d07940b063c3eeeb.jpg)



PCA High-Speed Output Mode / PCA 高速脉冲输出模式


CCAPnL的值决定了PCA模块n的输出脉冲频率。当PCA时钟源是SYSclk/2时，输出脉冲的频率F为：

$$
\mathrm {f} = \mathrm {S Y S c l k} / (4 \times \mathrm {C C A P n L})
$$

其中，SYSclk为系统时钟频率。由此，可以得到CCAPnL的值CCAPnL = SYSclk / ( 4×f ).

如果计算出的结果不是整数，则进行四舍五入取整，即

$$
\mathrm {C C A P n L} = \mathrm {I N T} (\mathrm {S Y S c l k} / (4 \times \mathrm {f}) + 0. 5)
$$

其中，INT( )为取整运算，直接去掉小数。例如，假设SYSclk = 20MHz，要求PCA高速脉冲输出125kHz的方波，则CCAPnL中的值应为：

$$
\mathrm {C C A P n L} = \mathrm {I N T} (2 0 0 0 0 0 0 0 / (4 \times 1 2 5 0 0 0) + 0. 5) = \mathrm {I N T} (4 0 + 0. 5) = 4 0 = 2 8 \mathrm {H}
$$

# 11.3.4 脉宽调节模式(PWM)

脉宽调制(PWM，Pulse Width Modulation)是一种使用程序来控制波形占空比、周期、相位波形的技术，在三相电机驱动、D/A转换等场合有广泛的应用。

STC15系列单片机的PCA模块可以通过设定各自的寄存器PCA_PWMn $\scriptstyle \mathbf { n = 0 , 1 , 2 . }$ .下同)中的位EBSn_1/PCA_PWMn.7及EBSn_0/PCA_PWMn.6，使其工作于8位PWM或7位PWM或6位PWM模式。

# 11.3.4.1 8位脉宽调节模式(PWM)

当[EBSn_1,EBSn_0]=[0,0]或[1,1]时，PCA模块n工作于8位PWM模式，此时将{0,CL[7:0]}与捕获寄存器[EPCnL,CCAPnL[7:0]]进行比较。PWM模式的结构如下图所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/fb6cad29224d0a79f485ced9ee0575a632af911a2e0097dde1c44a28a1e4ed62.jpg)



PCA PWM mode / 可调制脉冲宽度输出模式结构图(PCA


当PCA模块工作于8位PWM模式时， � PCA定时器，所有它们的输出频率相同。各个模块的输出占空比是独立变化的，与使用的捕获寄存器{EPCnL,CCAPnL[7:0]}有关。当{0,CL[7:0]}的值小于{EPCnL,CCAPnL[7:0]}时，输出为低； {0,CL[7:0]}的值等于或大于{EPCnL,CCAPnL[7:0]}时，输出为高。当CL的值由FF变为00溢出时，{EPCnH,CCAPnH[7:0]}的内容装载到{EPCnL,CCAPnL[7:0]}中。这样就可实现无干扰地更新PWM。要使能PWM模式，模块CCAPMn寄存器的PWMn和ECOMn位必须置位。

PCA时钟输入源频率当PWM是8位的 PWM的频率 $\underline { { \underline { { \mathbf { \Pi } } } } }$ 256

PCA时钟输入源可以从以下8种中选择一种：SYSclk， SYSclk/2， SYSclk/4，SYSclk/6，SYSclk/8，SYSclk/12,定时器0的溢出，ECI/P1.2输入

举例： PCA模块工作于8位PWM模式。 PWM输出频率为38KHz，选SYSclk为PCA/PWM时钟输入源，求出SYSclk的值

由计算公式38000=SYSclk/256 ，得到外部时钟频率SYSclk=38000 x 256 x 1=9,728,000

如果要实现可调频率的PWM输出,可选择定时器0的溢出率或者ECI脚的输入作为PCA/PWM的时钟输入源

当 $\mathrm { E P C n L } = 0$ $= 0$ 及CCAPnL $= 0 0 \mathrm { H }$ 时,PWM固定输出高

当EPCnL $= 1$ 及CCAPnL $=$ FFH时,PWM固定输出低

当某个I/O口作为PWM使用时,该口的状态

<table><tr><td>PWM之前口的状态</td><td>PWM输出时口的状态</td></tr><tr><td>弱上拉/准双向</td><td>强推挽输出/强上拉输出，要加输出限流电阻1K-10K</td></tr><tr><td>强推挽输出/强上拉输出</td><td>强推挽输出/强上拉输出，要加输出限流电阻1K-10K</td></tr><tr><td>仅为输入/高阻</td><td>PWM无效</td></tr><tr><td>开漏</td><td>开漏</td></tr></table>

限流电阻用10K到1K

普通I/O口 冈 接负载

# 11.3.4.2 7位脉宽调节模式(PWM)(STC创新设计，请不要抄袭)

当[EBSn_1,EBSn_0]=[0,1]时，PCA模块n工作于7位PWM模式，此时将{0,CL[6:0]}与捕获寄存器[EPCnL,CCAPnL[6:0]]进行比较。PWM模式的结构如下图所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/86937c7d54bcdbe9199a5ac7b73be5fd216fcb10f75f7cdffcb90683a51c32c8.jpg)



PCA PWM mode / 可调制脉冲宽度输出模式结构图(PCA


当PCA模块工作于7位PWM模式时， � PCA定时器，所有它们的输出频率相同。各个模块的输出占空比是独立变化的，与使用的捕获寄存器{EPCnL,CCAPnL[6:0]}有关。当{0,CL[6:0]}的值小于{EPCnL,CCAPnL[6:0]}时，输出为低； {0,CL[6:0]}的值等于或大于{EPCnL,CCAPnL[6:0]}时，输出为高。当CL的值由7F变为00溢出时，{EPCnH,CCAPnH[6:0]}的内容装载到{EPCnL,CCAPnL[6:0]}中。这样就可实现无干扰地更新PWM。要使能PWM模式，模块CCAPMn寄存器的PWMn和ECOMn位必须置位。

PCA时钟输入源频率当PWM是7位的 PWM的频率=128

PCA时钟输入源可以从以下8种中选择一种：SYSclk， SYSclk/2， SYSclk/4，SYSclk/6，SYSclk/8，SYSclk/12,定时器0的溢出，ECI/P1.2输入

举例： PCA模块工作于7位PWM模式。 PWM输出频率为38KHz，选SYSclk为PCA/PWM时钟输入源，求出SYSclk的值

由计算公式38000=SYSclk/128 ，得到外部时钟频率SYSclk=38000 x 128 x 1=4,864,000

如果要实现可调频率的PWM输出,可选择定时器0的溢出率或者ECI脚的输入作为PCA/PWM的时钟输入源

当EPCnL $= 0$ 及CCAPnL = 80H时,PWM固定输出高

当EPCnL $= 1$ 及CCAPnL $=$ 0FFH时,PWM固定输出低

# 11.3.4.3 6位脉宽调节模式(PWM)(STC创新设计，请不要抄袭)

当[EBSn_1,EBSn_0]=[1,0]时，PCA模块n工作于6位PWM模式，此时将{0,CL[5:0]}与捕获寄存器[EPCnL,CCAPnL[5:0]]进行比较。PWM模式的结构如下图所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d0c538f45576995610bac82fcc849d810a98d890042e2e72f1c1376c518e1cdf.jpg)



PCA PWM mode / 可调制脉冲宽度输出模式结构图(PCA


当PCA模块工作于6位PWM模式时， � PCA定时器，所有它们的输出频率相同。各个模块的输出占空比是独立变化的，与使用的捕获寄存器{EPCnL,CCAPnL[5:0]}有关。当{0,CL[5:0]}的值小于{EPCnL,CCAPnL[5:0]}时，输出为低； {0,CL[5:0]}的值等于或大于{EPCnL,CCAPnL[5:0]}时，输出为高。当CL的值由3F变为00溢出时，{EPCnH,CCAPnH[5:0]}的内容装载到{EPCnL,CCAPnL[5:0]}中。这样就可实现无干扰地更新PWM。要使能PWM模式，模块CCAPMn寄存器的PWMn和ECOMn位必须置位。

PCA时钟输入源频率当PWM是6位的 PWM的频率 $\underline { { \underline { { \mathbf { \Pi } } } } }$ 64

PCA时钟输入源可以从以下8种中选择一种：SYSclk， SYSclk/2， SYSclk/4，SYSclk/6，SYSclk/8，SYSclk/12,定时器0的溢出，ECI/P1.2输入

举例： PCA模块工作于6位PWM模式。 PWM输出频率为38KHz， 选SYSclk为PCA/PWM时钟输入源，求出SYSclk的值

由计算公式38000=SYSclk/64 ，得到外部时钟频率SYSclk=38000 x 64 x 1=2,432,000

如果要实现可调频率的PWM输出,可选择定时器0的溢出率或者ECI脚的输入作为PCA/PWM的时钟输入源

当EPCnL $= 0$ 及CCAPnL $=$ 0C0H时,PWM固定输出高

当EPCnL $= 1$ 及CCAPnL $=$ 0FFH时,PWM固定输出低

# 11.4 用CCP/PCA功能扩展外部中断的测试程序(C和汇编)

# 1. C程序：

/* -*/ 

/* --- STC MCU Limited. - -*/ 

/* --- 演示 STC 1T 系列单片机 用PCA功能扩展外部中断 -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 * 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用或在文章中引用该程序， -*/

/* 请在程序中或文章中注明使用了STC的资料及程序 - -*/

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可--------*/

/*- -*/ 

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

sfr P_SW1 = 0xA2; //外设功能切换寄存器1

#define CCP_S0 0x10 //P_SW1.4 

#define CCP_S1 0x20 //P_SW1.5 

sfr CCON $=$ 0xD8; //PCA控制寄存器

sbit CCF0 $=$ CCON^0; //PCA模块0中断标志

sbit CCF1 CCON^1; //PCA模块1中断标志

sbit CR CCON^6; //PCA定时器运行控制位

sbit CF CCON^7; //PCA定时器溢出标志

sfr CMOD = 0xD9; //PCA模式寄存器

sfr CL 一 0xE9; //PCA定时器低字节

sfr CH = 0xF9; //PCA定时器高字节

sfr CCAPM0 = 0xDA; //PCA模块0模式寄存器

sfr CCAP0L = 0xEA; //PCA模块0捕获寄存器 LOW

sfr CCAP0H = 0xFA; //PCA模块0捕获寄存器 HIGH

sfr CCAPM1 = 0xDB; //PCA模块1模式寄存器

sfr CCAP1L = 0xEB; //PCA模块1捕获寄存器 LOW

sfr CCAP1H = 0xFB; //PCA模块1捕获寄存器 HIGH

sfr PCAPWM0 = 0xf2; 

sfr PCAPWM1 $= 0\mathrm{xf3}$ sbit PCA_LED $\equiv$ P1^0; //PCA测试LED  
void PCA_isr() interrupt 7 using 1  
{CCF0 = 0; //清中断标志PCA_LED $=$ !PCA_LED; //测试LED取反  
}  
void main()  
{ACC $=$ P_SW1;ACC $\& =$ \~CCP_S0 | CCP_S1); //CCP_S0=0 CCP_S1=0P_SW1 $=$ ACC; //P1.2/ECI, P1.1/CCP0, P1.0/CCP1, P3.7/CCP2)  
// ACC $=$ P_SW1;  
// ACC $\& =$ \~CCP_S0 | CCP_S1); //CCP_S0=1 CCP_S1=0  
// ACC |= CCP_S0; //P3.4/ECI_2, P3.5/CCP0_2, P3.6/CCP1_2, P3.7/CCP2_2)  
// P_SW1 $=$ ACC;  
// ACC $=$ P_SW1;  
// ACC $\& =$ \~CCP_S0 | CCP_S1); //CCP_S0=0 CCP_S1=1  
// ACC |= CCP_S1; //P2.4/ECI_3, P2.5/CCP0_3, P2.6/CCP1_3, P2.7/CCP2_3)  
// P_SW1 $=$ ACC;  
CCON $= 0$ //初始化PCA控制寄存器//PCA定时器停止//清除CF标志//清除模块中断标志  
CL $= 0$ //复位PCA寄存器CH $= 0$ CMOD $= 0\mathrm{x}00$ //设置PCA时钟源//禁止PCA定时器溢出中断CCAPM0 $= 0\mathrm{x}11$ //PCA模块0为下降沿触发CCAPM0 $= 0\mathrm{x}21$ //PCA模块0为上升沿沿触发CCAPM0 $= 0\mathrm{x}31$ //PCA模块0为上升沿/下降沿触发CR $= 1$ //PCA定时器开始工作EA $= 1$ while (1);

# 2. 汇编程序：

/*- -*/ 

/* --- STC MCU Limited. -*/ 

/* --- 演示 STC 1T 系列单片机 用PCA功能扩展外部中断 -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用或在文章中引用该程序， -*/

/* 请在程序中或文章中注明使用了STC的资料及程序 -*/

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可--------*/

/* -*/ 

//假定测试芯片的工作频率为18.432MHz

P_SW1 EQU 0A2H ;外设功能切换寄存器1

CCP_S0 EQU 10H ;P_SW1.4 

CCP_S1 EQU 20H ;P_SW1.5 

CCON EQU 0D8H ;PCA控制寄存器

CCF0 BIT CCON.0 ;PCA模块0中断标志

CCF1 BIT CCON.1 ;PCA模块1中断标志

CR BIT CCON.6 ;PCA定时器运行控制位

CF BIT CCON.7 ;PCA定时器溢出标志

CMOD EQU 0D9H ;PCA模式寄存器

CL EQU 0E9H ;PCA定时器低字节

CH EQU 0F9H ;PCA定时器高字节

CCAPM0 EQU 0DAH ;PCA模块0模式寄存器

CCAP0L EQU 0EAH ;PCA模块0捕获寄存器 LOW

CCAP0H EQU 0FAH ;PCA模块0捕获寄存器 HIGH

CCAPM1 EQU 0DBH ;PCA模块1模式寄存器

CCAP1L EQU 0EBH ;PCA模块1捕获寄存器 LOW

CCAP1H EQU 0FBH ;PCA模块1捕获寄存器 HIGH

PCA_LED BIT P1.0 ;PCA测试LED

ORG 0000H 

LJMP MAIN 

ORG 003BH 

PCA_ISR: 

CLR CCF0 ;清中断标志

CPL PCA_LED ;测试LED取反

RETI 

<table><tr><td rowspan="4">MAIN:</td><td>ORG</td><td>0100H</td><td></td></tr><tr><td>MOV</td><td>A, P_SW1</td><td></td></tr><tr><td>ANL</td><td>A, #0CFH</td><td>//CCP_S0=0 CCP_S1=0</td></tr><tr><td>MOV</td><td>P_SW1, A</td><td>// (P1.2/ECI, P1.1/CCP0, P1.0/CCP1, P3.7/CCP2)</td></tr><tr><td>//</td><td>MOV</td><td>A, P_SW1</td><td></td></tr><tr><td>//</td><td>ANL</td><td>A, #0CFH</td><td>//CCP_S0=1 CCP_S1=0</td></tr><tr><td>//</td><td>ORL</td><td>A, #CCP_S0</td><td>// (P3.4/ECI_2, P3.5/CCP0_2, P3.6/CCP1_2, P3.7/CCP2_2)</td></tr><tr><td>//</td><td>MOV</td><td>P_SW1, A</td><td></td></tr><tr><td>//</td><td>MOV</td><td>A, P_SW1</td><td></td></tr><tr><td>//</td><td>ANL</td><td>A, #0CFH</td><td>//CCP_S0=0 CCP_S1=1</td></tr><tr><td>//</td><td>ORL</td><td>A, #CCP_S1</td><td>// (P2.4/ECI_3, P2.5/CCP0_3, P2.6/CCP1_3, P2.7/CCP2_3)</td></tr><tr><td>//</td><td>MOV</td><td>P_SW1, A</td><td></td></tr><tr><td></td><td>MOV</td><td>CCON, #0</td><td>;初始化PCA控制寄存器</td></tr><tr><td></td><td></td><td></td><td>;PCA定时器停止</td></tr><tr><td></td><td></td><td></td><td>;清除CF标志</td></tr><tr><td></td><td></td><td></td><td>;清除模块中断标志</td></tr><tr><td></td><td>CLR</td><td>A</td><td>;</td></tr><tr><td></td><td>MOV</td><td>CL, A</td><td>;复位PCA寄存器</td></tr><tr><td></td><td>MOV</td><td>CH, A</td><td>;</td></tr><tr><td></td><td>MOV</td><td>CMOD, #00H</td><td>;设置PCA时钟源</td></tr><tr><td></td><td></td><td></td><td>;禁止PCA定时器溢出中断</td></tr><tr><td></td><td>MOV</td><td>CCAPM0, #11H</td><td>;PCA模块0捕获CCP0(P1.3)的下降沿</td></tr><tr><td>;</td><td>MOV</td><td>CCAPM0, #21H</td><td>;PCA模块0捕获CCP0(P1.3)的上升沿</td></tr><tr><td>;</td><td>MOV</td><td>CCAPM0, #31H</td><td>;PCA模块0捕获CCP0(P1.3)的上升沿/下降沿</td></tr><tr><td>;</td><td>SETB</td><td>CR</td><td>;PCA定时器开始工作</td></tr><tr><td></td><td>SETB</td><td>EA</td><td></td></tr><tr><td></td><td>SJMP</td><td>$</td><td></td></tr><tr><td>;</td><td>END</td><td></td><td></td></tr></table>

# 11.5 用CCP/PCA功能实现16位定时器的测试程序(C和汇编)

# 1. C程序：

/* -*/ 

/* --- STC MCU Limited. - -*/ 

/* --- 演示 STC 1T 系列单片机 用PCA功能实现16位定时器 -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用或在文章中引用该程序， -*/

/* 请在程序中或文章中注明使用了STC的资料及程序 - -*/

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可--------*/

/*_ -*/ 

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

#define FOSC 18432000L 

#define T100Hz (FOSC / 12 / 100) 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

sfr P_SW1 $=$ 0xA2; //外设功能切换寄存器1

#define CCP_S0 0x10 //P_SW1.4 

#define CCP_S1 0x20 //P_SW1.5 

sfr CCON $=$ 0xD8; //PCA控制寄存器

sbit CCF0 $=$ CCON^0; //PCA模块0中断标志

sbit CCF1 CCON^1; //PCA模块1中断标志

sbit CR CCON^6; //PCA定时器运行控制位

sbit CF CCON^7; //PCA定时器溢出标志

sfr CMOD 0xD9; //PCA模式寄存器

sfr CL 0xE9; //PCA定时器低字节

sfr CH 0xF9; //PCA定时器高字节

sfr CCAPM0 一 0xDA; //PCA模块0模式寄存器

sfr CCAP0L 0xEA; //PCA模块0捕获寄存器 LOW

sfr CCAP0H = 0xFA; //PCA模块0捕获寄存器 HIGH

sfr CCAPM1 = 0xDB; //PCA模块1模式寄存器

sfr CCAP1L = 0xEB; //PCA模块1捕获寄存器 LOW

sfr CCAP1H = 0xFB; //PCA模块1捕获寄存器 HIGH

sfr PCAPWM0 = 0xf2; 

sfr PCAPWM1 一 0xf3;

sbit PCA_LED P1^0; //PCA测试LED

BYTE cnt; 

WORD value; 

```txt
void PCA_isr() interrupt 7 using 1  
{  
    CCF0 = 0; //清中断标志  
    CCAPOL = value;  
    CCAPOH = value >> 8; //更新比较值  
    value += T100Hz;  
    if (cnt-- == 0)  
    {  
        cnt = 100; //记数100次  
        PCA_LED = !PCA_LED; //每秒闪烁一次  
    }  
}  
void main()  
{  
    ACC = P_SW1;  
    ACC &= ~CCP_S0 | CCP_S1; //CCP_S0=0 CCP_S1=0  
    P_SW1 = ACC; //P1.2/ECI, P1.1/CCP0, P1.0/CCP1, P3.7/CCP2)  
    ACC = P_SW1;  
    ACC &= ~CCP_S0 | CCP_S1; //CCP_S0=1 CCP_S1=0  
    ACC |= CCP_S0; //P3.4/ECI_2, P3.5/CCP0_2, P3.6/CCP1_2, P3.7/CCP2_2)  
    P_SW1 = ACC;  
    ACC = P_SW1;  
    ACC &= ~CCP_S0 | CCP_S1; //CCP_S0=0 CCP_S1=1  
    ACC |= CCP_S1; //P2.4/ECI_3, P2.5/CCP0_3, P2.6/CCP1_3, P2.7/CCP2_3)  
    P_SW1 = ACC;  
    CCON = 0; //初始化PCA控制寄存器  
    //PCA定时器停止  
    //清除CF标志  
    //清除模块中断标志  
    CL = 0; //复位PCA寄存器  
    CH = 0;  
    CMOD = 0x00; //设置PCA时钟源  
    //禁止PCA定时器溢出中断  
    value = T100Hz;  
    CCAPOL = value;  
    CCAPOH = value >> 8; //初始化PCA模块0  
    value += T100Hz;  
    CCAPM0 = 0x49; //PCA模块0为16位定时器模式  
    CR = 1; //PCA定时器开始工作  
    EA = 1;  
    cnt = 0;  
    while (1);
```

# 2. 汇编程序：

/*- -*/ 

/* --- STC MCU Limited. * 

/* --- 演示 STC 1T 系列单片机 用PCA功能实现16位定时器 -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 -*/ 

/* --- Web: www.STCMCU.com -*/ 

/* 如果要在程序中使用或在文章中引用该程序， -*/

/* 请在程序中或文章中注明使用了STC的资料及程序 *

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可--------*/

/*-- -*/ 

//假定测试芯片的工作频率为18.432MHz

T100Hz EQU 3C00H ;(18432000 / 12 / 100) 

P_SW1 EQU 0A2H ;外设功能切换寄存器1

CCP_S0 EQU 10H ;P_SW1.4 

CCP_S1 EQU 20H ;P_SW1.5 

CCON EQU 0D8H ;PCA控制寄存器

CCF0 BIT CCON.0 ;PCA模块0中断标志

CCF1 BIT CCON.1 ;PCA模块1中断标志

CR BIT CCON.6 ;PCA定时器运行控制位

CF BIT CCON.7 ;PCA定时器溢出标志

CMOD EQU 0D9H ;PCA模式寄存器

CL EQU 0E9H ;PCA定时器低字节

CH EQU 0F9H ;PCA定时器高字节

CCAPM0 EQU 0DAH ;PCA模块0模式寄存器

CCAP0L EQU 0EAH ;PCA模块0捕获寄存器 LOW

CCAP0H EQU 0FAH ;PCA模块0捕获寄存器 HIGH

CCAPM1 EQU 0DBH ;PCA模块1模式寄存器

CCAP1L EQU 0EBH ;PCA模块1捕获寄存器 LOW

CCAP1H EQU 0FBH ;PCA模块1捕获寄存器 HIGH

PCA_LED BIT P1.0 ;PCA测试LED

CNT EQU 20H 

ORG 0000H 

LJMP MAIN 

ORG 003BH 

LJMP PCA_ISR 

ORG 0100H 

MAIN: 

MOV SP, #3FH 

MOV A, P_SW1 

ANL A, #0CFH //CCP_S0=0 CCP_S1=0 

MOV P_SW1, A //(P1.2/ECI, P1.1/CCP0, P1.0/CCP1, P3.7/CCP2) 

```asm
// MOV A, P_SW1  
// ANL A, #0CFH //CCP_S0=1 CCP_S1=0  
// ORL A, #CCP_S0 // (P3.4/ECI_2, P3.5/CCP0_2, P3.6/CCP1_2, P3.7/CCP2_2)  
// MOV P_SW1, A  
// MOV A, P_SW1  
// ANL A, #0CFH //CCP_S0=0 CCP_S1=1  
// ORL A, #CCP_S1 // (P2.4/ECI_3, P2.5/CCP0_3, P2.6/CCP1_3, P2.7/CCP2_3)  
// MOV P_SW1, A  
MOV CCON, #0 ;初始化PCA控制寄存器;PCA定时器停止;清除CF标志;清除模块中断标志CLR A;  
MOV CL, A;复位PCA寄存器MOV CH, A;  
MOV CMOD, #00H ;设置PCA时钟源;禁止PCA定时器溢出中断  
MOV CCAP0L, #LOW T100Hz;  
MOV CCAP0H, #HIGH T100Hz;初始化PCA模块0MOV CCAPM0, #49H;PCA模块0为16位定时器模式  
SETB CR;PCA定时器开始工作  
SETB EA;  
MOV CNT, #100  
SJMP $  
PCA_ISR:  
PUSH PSW  
PUSH ACC  
CLR CCF0;清中断标志MOV A, CCAP0L  
ADD A, #LOW T100Hz;更新比较值MOV CCAP0L,A  
MOV A, CCAP0H  
ADDC A, #HIGH T100Hz  
MOV CCAP0H, A  
DJNZ CNT, PCA_ISR_EXIT;记数100次MOV CNT, #100  
CPL PCA_LED;每秒闪烁一次  
PCA_ISR_EXIT:  
POP ACC  
POP PSW  
RETI
```

# 11.6 CCP/PCA输出高速脉冲的测试程序(C和汇编)

# 1. C程序：

/* -*/ 

/* --- STC MCU Limited. -*/ 

/* ---演示 STC 1T 系列单片机 PCA输出高速脉冲 -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com -*/ 

/* 如果要在程序中使用或在文章中引用该程序， -*/

/* 请在程序中或文章中注明使用了STC的资料及程序 -*/

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可--------*/

/*_ */ 

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

#define FOSC 18432000L 

#define T100KHz (FOSC / 4 / 100000) 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

sfr P_SW1 = 0xA2; //外设功能切换寄存器1

#define CCP_S0 0x10 //P_SW1.4 

#define CCP_S1 0x20 //P_SW1.5 

sfr CCON 0xD8; //PCA控制寄存器

sbit CCF0 CCON^0; //PCA模块0中断标志

sbit CCF1 CCON^1; //PCA模块1中断标志

sbit CR CCON^6; //PCA定时器运行控制位

sbit CF CCON^7; //PCA定时器溢出标志

sfr CMOD 0xD9; //PCA模式寄存器

sfr CL 0xE9; //PCA定时器低字节

sfr CH 0xF9; //PCA定时器高字节

sfr CCAPM0 = 0xDA; //PCA模块0模式寄存器

sfr CCAP0L 0xEA; //PCA模块0捕获寄存器 LOW

sfr CCAP0H = 0xFA; //PCA模块0捕获寄存器 HIGH

sfr CCAPM1 = 0xDB; //PCA模块1模式寄存器

sfr CCAP1L 0xEB; //PCA模块1捕获寄存器 LOW

sfr CCAP1H = 0xFB; //PCA模块1捕获寄存器 HIGH

sfr PCAPWM0 = 0xf2; 

sfr PCAPWM1 = 0xf3; 

```c
sbit PCA_LED = P1^0; //PCA测试LED  
BYTE cnt;  
WORD value;  
void PCA_isr() interrupt 7 using 1  
{  
    CCF0 = 0; //清中断标志  
    CCAPOL = value;  
    CCAPOH = value >> 8; //更新比较值  
    value += T100KHz;  
}  
void main()  
{  
    ACC = P_SW1;  
    ACC &= ~CCP_S0 | CCP_S1; //CCP_S0=0 CCP_S1=0  
    P_SW1 = ACC; //(P1.2/ECI, P1.1/CCP0, P1.0/CCP1, P3.7/CCP2)  
    // ACC = P_SW1;  
    ACC &= ~CCP_S0 | CCP_S1; //CCP_S0=1 CCP_S1=0  
    ACC |= CCP_S0; //(P3.4/ECI_2, P3.5/CCP0_2, P3.6/CCP1_2, P3.7/CCP2_2)  
    // P_SW1 = ACC;  
    // ACC = P_SW1;  
    ACC &= ~CCP_S0 | CCP_S1; //CCP_S0=0 CCP_S1=1  
    ACC |= CCP_S1; //(P2.4/ECI_3, P2.5/CCP0_3, P2.6/CCP1_3, P2.7/CCP2_3)  
    P_SW1 = ACC;  
    CCON = 0; //初始化PCA控制寄存器  
    //PCA定时器停止  
    //清除CF标志  
    //清除模块中断标志  
    CL = 0; //复位PCA寄存器  
    CH = 0;  
    CMOD = 0x02; //设置PCA时钟源  
    //禁止PCA定时器溢出中断  
    value = T100KHz;  
    CCAPOL = value; //P1.1输出100KHz方波  
    CCAPOH = value >> 8; //初始化PCA模块0  
    value += T100KHz;  
    CCAPM0 = 0x4d; //PCA模块0为16位定时器模式,同时反转CCP0(P1.1)口  
    CR = 1; //PCA定时器开始工作  
    EA = 1;  
    cnt = 0;  
    while (1);
```

# 2. 汇编程序：

/*- -*/ 

/* --- STC MCU Limited. -*/ 

/* ---演示 STC 1T 系列单片机 PCA输出高速脉冲 -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 - -*/ 

/* --- Tel: 86-755-82948412 - * 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用或在文章中引用该程序， -*/

/* 请在程序中或文章中注明使用了STC的资料及程序 - -*/

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可--------*/

/*-- -*/ 

//假定测试芯片的工作频率为18.432MHz

T100KHz EQU 2EH ;(18432000 / 4 / 100000) 

P_SW1 EQU 0A2H ;外设功能切换寄存器1

CCP_S0 EQU 10H ;P_SW1.4 

CCP_S1 EQU 20H ;P_SW1.5 

CCON EQU 0D8H ;PCA控制寄存器

CCF0 BIT CCON.0 ;PCA模块0中断标志

CCF1 BIT CCON.1 ;PCA模块1中断标志

CR BIT CCON.6 ;PCA定时器运行控制位

CF BIT CCON.7 ;PCA定时器溢出标志

CMOD EQU 0D9H ;PCA模式寄存器

CL EQU 0E9H ;PCA定时器低字节

CH EQU 0F9H ;PCA定时器高字节

CCAPM0 EQU 0DAH ;PCA模块0模式寄存器

CCAP0L EQU 0EAH ;PCA模块0捕获寄存器 LOW

CCAP0H EQU 0FAH ;PCA模块0捕获寄存器 HIGH

CCAPM1 EQU 0DBH ;PCA模块1模式寄存器

CCAP1L EQU 0EBH ;PCA模块1捕获寄存器 LOW

CCAP1H EQU 0FBH ;PCA模块1捕获寄存器 HIGH

ORG 0000H LJMP MAIN 

ORG 003BH 

PCA_ISR: 

PUSH PSW 

PUSH ACC 

CLR CCF0 

MOV A, CCAP0L 

ADD A, #T100KHz 

MOV CCAP0L, A 

;清中断标志

```asm
CLR A
ADDC A, CCAP0H
MOV CCAP0H, A
PCA_ISR_EXIT:
POP ACC
POP PSW
RETI
ORG 0100H
MAIN:
MOV A, P_SW1
ANL A, #0CFH //CCP_S0=0 CCP_S1=0
MOV P_SW1, A // (P1.2/ECI, P1.1/CCP0, P1.0/CCP1, P3.7/CCP2)
// MOV A, P_SW1
// ANL A, #0CFH //CCP_S0=1 CCP_S1=0
ORL A, #CCP_S0 // (P3.4/ECI_2, P3.5/CCP0_2, P3.6/CCP1_2, P3.7/CCP2_2)
// MOV P_SW1, A
// MOV A, P_SW1
// ANL A, #0CFH //CCP_S0=0 CCP_S1=1
ORL A, #CCP_S1 // (P2.4/ECI_3, P2.5/CCP0_3, P2.6/CCP1_3, P2.7/CCP2_3)
// MOV P_SW1, A
MOV CCON, #0 ;初始化PCA控制寄存器
STC ;PCA定时器停止
CLR A ;清除CF标志
MOV CL, A ;复位PCA寄存器
MOV CH, A ;设置PCA时钟源
MOV CMOD, #02H ;禁止PCA定时器溢出中断
MOV CCAPOL, #T100KHz ;P1.3输出100KHz方波
MOV CCAPOH, #0 ;初始化PCA模块0
MOV CCAPM0, #4dH ;PCA模块0为16位定时模式并使能PCA中断
SETB CR ;PCA定时器开始工作
SETB EA
SJMP $
END
```

# 11.7 CCP/PCA输出PWM(6位 $+ 7$ 位 $\mathbf { + 8 }$ 位)的测试程序(C和汇编)

# 1. C程序：

/* -*/ 

/* --- STC MCU Limited. - * 

/* ---STC15F2K60S2 系列 PCA输出6/7/8位PWM举例-- -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用或在文章中引用该程序， -*/

/* 请在程序中或文章中注明使用了STC的资料及程序 -*/

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可--------*/

/* */ 

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

#define FOSC 18432000L #define FOSC 18432000L 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

sfr P_SW1 = 0xA2; //外设功能切换寄存器1

#define CCP_S0 0x10 //P_SW1.4 

#define CCP_S1 0x20 //P_SW1.5 

sfr CCON = 0xD8; //PCA控制寄存器

sbit CCF0 = CCON^0; //PCA模块0中断标志

sbit CCF1 = CCON^1; //PCA模块1中断标志

sbit CR CCON^6; //PCA定时器运行控制位

sbit CF 一 CCON^7; //PCA定时器溢出标志

sfr CMOD = 0xD9; //PCA模式寄存器

sfr CL = 0xE9; //PCA定时器低字节

sfr CH = 0xF9; //PCA定时器高字节

sfr CCAPM0= 0xDA; //PCA模块0模式寄存器

sfr CCAP0L = 0xEA; //PCA模块0捕获寄存器 LOW

sfr CCAP0H = 0xFA; //PCA模块0捕获寄存器 HIGH

sfr CCAPM1= 0xDB; //PCA模块1模式寄存器

sfr CCAP1L = 0xEB; //PCA模块1捕获寄存器 LOW

sfr CCAP1H = 0xFB; //PCA模块1捕获寄存器 HIGH

```txt
sfr CCAPM2 = 0xD; //PCA模块2模式寄存器  
sfr CCAP2L = 0xEF; //PCA模块2捕获寄存器LOW  
sfr CCAP2H = 0xFC; //PCA模块2捕获寄存器HIGH  
sfr PCA_PWM0 = 0xf2; //PCA模块0的PWM寄存器  
sfr PCA_PWM1 = 0xf3; //PCA模块1的PWM寄存器  
sfr PCA_PWM2 = 0xf4; //PCA模块2的PWM寄存器  
void main()  
{ACC = P_SW1;ACC &= \~CCP_S0 | CCP_S1); //CCP_S0=0 CCP_S1=0P_SW1 = ACC; //P1.2/ECI, P1.1/CCP0, P1.0/CCP1, P3.7/CCP2)  
// ACC = P_SW1;ACC &= \~CCP_S0 | CCP_S1); //CCP_S0=1 CCP_S1=0ACC |= CCP_S0; //P3.4/ECI_2, P3.5/CCP0_2, P3.6/CCP1_2, P3.7/CCP2_2)  
// P_SW1 = ACC;  
// ACC = P_SW1;ACC &= \~CCP_S0 | CCP_S1); //CCP_S0=0 CCP_S1=1ACC |= CCP_S1; //P2.4/ECI_3, P2.5/CCP0_3, P2.6/CCP1_3, P2.7/CCP2_3)  
// P_SW1 = ACC;  
CCON = 0; //初始化PCA控制寄存器//PCA定时器停止//清除CF标志//清除模块中断标志CL = 0; //复位PCA寄存器CH = 0;  
CMOD = 0x02; //设置PCA时钟源//禁止PCA定时器溢出中断PCA_PWM0 = 0x00; //PCA模块0工作于8位PWMCCAP0H = CCAPOL = 0x20; //PWM0的占空比为87.5% ((100H-20H)/100H)CCAPM0 = 0x42; //PCA模块0为8位PWM模式  
PCA_PWM1 = 0x40;  
CCAP1H = CCAP1L = 0x20; //PWM1的占空比为75% ((80H-20H)/80H)CCAPM1 = 0x42; //PCA模块1为7位PWM模式  
PCA_PWM2 = 0x80; //PCA模块2工作于6位PWMCCAP2H = CCAP2L = 0x20; //PWM2的占空比为50% ((40H-20H)/40H)CCAPM2 = 0x42; //PCA模块2为6位PWM模式CR = 1; //PCA定时器开始工作while (1);
```

# 2. 汇编程序：

/* -*/ 

/* --- STC MCU Limited. -- -*/ 

/* ---STC15F2K60S2 系列 PCA输出6/7/8位PWM举例-- -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com -*/ 

/* 如果要在程序中使用或在文章中引用该程序， -*/

/* 请在程序中或文章中注明使用了STC的资料及程序 *

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可--------*/

/* */ 

//假定测试芯片的工作频率为18.432MHz

P_SW1 EQU 0A2H ;外设功能切换寄存器1

CCP_S0 EQU 10H ;P_SW1.4 

CCP_S1 EQU 20H ;P_SW1.5 

CCON EQU 0D8H ;PCA控制寄存器

CCF0 BIT CCON.0 ;PCA模块0中断标志

CCF1 BIT CCON.1 ;PCA模块1中断标志

CR BIT CCON.6 ;PCA定时器运行控制位

CF BIT CCON.7 ;PCA定时器溢出标志

CMOD EQU 0D9H ;PCA模式寄存器

CL EQU 0E9H ;PCA定时器低字节

CH EQU 0F9H ;PCA定时器高字节

CCAPM0 EQU 0DAH ;PCA模块0模式寄存器

CCAP0L EQU 0EAH ;PCA模块0捕获寄存器 LOW

CCAP0H EQU 0FAH ;PCA模块0捕获寄存器 HIGH

CCAPM1 EQU 0DBH ;PCA模块1模式寄存器

CCAP1L EQU 0EBH ;PCA模块1捕获寄存器 LOW

CCAP1H EQU 0FBH ;PCA模块1捕获寄存器 HIGH

CCAPM2 EQU 0DCH ;PCA模块2模式寄存器

CCAP2L EQU 0ECH ;PCA模块2捕获寄存器 LOW

CCAP2H EQU 0FCH ;PCA模块2捕获寄存器 HIGH

PCA_PWM0 EQU 0F2H ;PCA模块0的PWM寄存器

PCA_PWM1 EQU 0F3H ;PCA模块1的PWM寄存器

PCA_PWM2 EQU 0F4H ;PCA模块2的PWM寄存器

ORG 0000H LJMP MAIN 

ORG 0100H 

MAIN: 

MOV A, P_SW1 

ANL A, #0CFH //CCP_S0=0 CCP_S1=0 

<table><tr><td>MOV</td><td>P_SW1, A</td><td>// (P1.2/ECI, P1.1/CCP0, P1.0/CCP1, P3.7/CCP2)</td></tr><tr><td>MOV</td><td>A, P_SW1</td><td></td></tr><tr><td>ANL</td><td>A, #0CFH</td><td>//CCP_S0=1 CCP_S1=0</td></tr><tr><td>ORL</td><td>A, #CCP_S0</td><td>// (P3.4/ECI_2, P3.5/CCP0_2, P3.6/CCP1_2, P3.7/CCP2_2)</td></tr><tr><td>MOV</td><td>P_SW1, A</td><td></td></tr><tr><td>MOV</td><td>A, P_SW1</td><td></td></tr><tr><td>ANL</td><td>A, #0CFH</td><td>//CCP_S0=0 CCP_S1=1</td></tr><tr><td>ORL</td><td>A, #CCP_S1</td><td>// (P2.4/ECI_3, P2.5/CCP0_3, P2.6/CCP1_3, P2.7/CCP2_3)</td></tr><tr><td>MOV</td><td>P_SW1, A</td><td></td></tr><tr><td rowspan="4">MOV</td><td rowspan="4">CCON, #0</td><td>;初始化PCA控制寄存器</td></tr><tr><td>;PCA定时器停止</td></tr><tr><td>;清除CF标志</td></tr><tr><td>;清除模块中断标志</td></tr><tr><td>CLR</td><td>A</td><td>;</td></tr><tr><td>MOV</td><td>CL, A</td><td>;复位PCA计数器</td></tr><tr><td>MOV</td><td>CH, A</td><td>;</td></tr><tr><td rowspan="2">MOV</td><td rowspan="2">CMOD, #02H</td><td>;设置PCA时钟源</td></tr><tr><td>;禁止PCA定时器溢出中断</td></tr><tr><td>MOV</td><td>PCA_PWM0, #00H</td><td>;PCA模块0工作于8位PWM</td></tr><tr><td>MOV</td><td>A, #020H</td><td>;</td></tr><tr><td>MOV</td><td>CCAP0H, A</td><td>;PWM0的占空比为87.5% ((100H-20H)/100H)</td></tr><tr><td>MOV</td><td>CCAP0L, A</td><td>;</td></tr><tr><td>MOV</td><td>CCAPM0, #42H</td><td>;PCA模块0为8位PWM模式</td></tr><tr><td>MOV</td><td>PCA_PWM1, #40H</td><td>;PCA模块1工作于7位PWM</td></tr><tr><td>MOV</td><td>A, #020H</td><td>;</td></tr><tr><td>MOV</td><td>CCAP1H, A</td><td>;PWM1的占空比为75% ((80H-20H)/80H)</td></tr><tr><td>MOV</td><td>CCAP1L, A</td><td>;</td></tr><tr><td>MOV</td><td>CCAPM1, #42H</td><td>;PCA模块1为7位PWM模式</td></tr><tr><td>MOV</td><td>PCA_PWM2, #80H</td><td>;PCA模块2工作于6位PWM</td></tr><tr><td>MOV</td><td>A, #020H</td><td>;</td></tr><tr><td>MOV</td><td>CCAP2H, A</td><td>;PWM2的占空比为50% ((40H-20H)/40H)</td></tr><tr><td>MOV</td><td>CCAP2L, A</td><td>;</td></tr><tr><td>MOV</td><td>CCAPM2, #42H</td><td>;PCA模块2为6位PWM模式</td></tr><tr><td>SETB</td><td>CR</td><td>;PCA定时器开始工作</td></tr><tr><td>SJMP</td><td>$</td><td></td></tr><tr><td>END</td><td></td><td></td></tr></table>

# 11.8 用CCP/PCA软硬结合实现 9~16 位PWM输出的程序

//下列程序已在STC12C5Axx/STC12C52xx系列单片机上测试通过。

/*- -*/ 

/* --- STC MCU International Limited - -*/ 

/* --- STC 1T Series MCU Programme Demo - -*/ 

/* --- Fax: 86-755-82944243 -*/ 

/* --- Tel: 86-755-82948412 -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* If you want to use the program or the program referenced in the */ 

/* article, please specify in which data and procedures from STC */ 

/* -*/ 

/* 本程序经过测试完全正常, 不提供电话技术支持, 如不能理解, 请自行补充相关基础. */

/************* 本程序功能说明 **************

用PCA实现n位PWM

**********************************************/ 

#include "PWMn.h" 

// 文件: PWMn_main.c

// 功能: 测试模拟PWM的应用程序。

// 版本 : VER1.0

// 日期: 2011-4-11

// 备注:

/************* 

功能说明

************** 

在PWMn.h中选择是STC12C5201AD系列还是STC12C5A60S2系列。

用PCA模拟的9~16bit的PWM。

STC12C5201AD系列从PCA0的P3.7输出PWM。

STC12C5A60S2系列从PCA0的P1.3输出PWM。

本示例程序使用Fosc=24.576MHZ. 输出6000HZ的12bit PWM。

****************************************** 

/************ 工程文件

PWMn.c 

PWMn_main.c 

***************** 

/************* 

本地常量声明

************** 

/************* 

本地变量声明

*************** 

unsigned int 

pwm; 

//定义用户操作的PWM变量

/************* 

本地函数声明

**************/ 

void delay_ms(unsigned char ms); 

/**************** 外部函数声明和外部变量声明 *****************/

extern unsigned int PWM_high; 

//PWM空比寄存器，即PWM输出高电平的PCA时

钟脉冲个数（占空比写入变量）。

void PWMn_SetHighReg(unsigned int high); 

void PWMn_init(unsigned int high); 

/******************** 主函数 **************************/

// 函数: void main(void)

// 描述: 不断更新PWM值，用示波器观察占空比变化。

// 参数: 无。

// 返回: 无。

// 版本 : VER1.0

// 日期: 2011-4-11

// 备注:

void main(void) 

$\mathrm{pwm} = 1000;$ //pwm初值 $\mathrm{pwm} = \mathrm{PWM\_HIGH\_MIN};$ //pwm初值 $\mathrm{PWMn\_init(pwm)}$ //初始化pwm while(1） { delay_ms(10); //延时 $\mathrm{pwm} += 10;$ if(pwm $> =$ PWM_HIGH_MAX) $\mathrm{pwm} = \mathrm{PWM}$ $\mathrm{PWMn\_SetHighReg(pwm)}$ //更新PWM的 }

/**********************************************/ 

// 函数: void delay_ms(unsigned char ms)

// 描述: 延时函数。

// 参数: ms,要延时的ms数.

// 返回: none.

// 版本 : VER1.0

// 日期: 2010-12-15

// 备注:

//= 

```c
void delay_ms(unsigned char ms)  
{  
    unsigned int i;  
    do  
    {  
        i = MAIN_Fosc / 14000L; //1T  
        while(--i);  
    } while(--ms);  
} 
```

// 文件: PWMn.c

// 功能: 使用STC内带的PCA做9~16位的PWM。在PWMn.h中选择是STC12C5201AD系列还是//STC12C5A60S2系列。

// 版本 : VER1.0

// 日期: 2009-12-30

// 备注:

//= ============= /* 

原理说明：

本示例程序介绍在一些应用中所需要的高于8位分辨率的9~16位PWM，而8位的PWM可以直接使用STC的硬件PWM，请参考有关的的(Datasheet)。

本应用所需要资源：PCA可编程计数器阵列，捕获寄存器，匹配中断向量。

程序用到两个16位变量:

PWM_high 保存PWM输出高电平的PCA时钟数。

PWM_low 保存PWM输出低电平的PCA时钟数。

PWM的周期 = PWM_HIGH + PWM_LOW。

PCA时钟源有8种选择。

PCA模块被配置为16位高速输出方式，当PCA计数值与捕获寄存器数值匹配时，将CCP0输出取反，同时发生比较匹配中断。

比较匹配中断里判断高速输出的电平，如果是高电平，则向捕获寄存器装入高电平的PCA时钟数。如果是低电平，则装入低电平的PCA时钟数。

由于中断处理需 要一点时间，所以输出的占空比不能到0%或100%，所以对PWM_high有最小和最大值，中断处理绝对时间大约为100个SYSCLK。

本示例程序的测试是基于如下假设：

PCA时基信号为系统时钟Fosc，PCA中断优先级为最高。

提示：其它中断服务开销很长时间时，有可能会影响本程序的正常运行。

本示例程序用户可以在"用户配置宏"中选择以下参数：

PCA_IDLE_DISABLE 在IDLE模式是否禁止PCA工作，选择1: MCU在IDLE模式时禁止PCA工作，选择0: MCU在IDLE模式时允许PCA工作。

PCA_SOURCE_SELECT 选择PCA的基准时钟源，本示例使用系统时钟Fosc做PCA时钟源。

PWM_DUTY 定义PWM的周期，数值为PCA所选择的时钟脉冲个数，用户只需要装载PWM_high，PWM_low是根据这个周期计算出来的。

PWM_HIGH_MAX 限制PWM输出的最大占空比，原因如前所述。如果装载PWM_high大于此数值，将返回错误。

PWM_HIGH_MIN 限制PWM输出的最小占空比，原因如前所述。如果装载PWM_high小于此数值，将返回错误。*/

unsigned int PWM_high; //定义PWM占空比寄存器，即PWM输出高电平的PCA时钟脉冲个数//（占空比写入变量）。

unsigned int PWM_low; //定义PWM输出低电平的PCA时钟脉冲个数。unsigned int CCAP0_tmp; //定义CCAP0重装载影射寄存器。

// 函数: void PWMn_SetHighReg(unsigned int high)

// 描述: 写入占空比数据。

// 参数: high: 占空比数据，即PWM输出高电平的PCA时钟脉冲个数。

// 返回: 无

// 版本 : VER1.0

// 日期: 2009-12-30

// 备注:

```c
voidPWMn_SetHighReg(unsigned int high)  
{if(high > PWM_HIGH_MAX)high = PWM_HIGH_MAX; //如果写入大于最大占空比数据，强制为最大占空比。if(high < PWM_HIGH_MIN)high = PWM_HIGH_MIN; //如果写入小于最小占空比数据，则返回错误代码2。CR = 0; //停止PCA。PWM_high = high; //数据在正确范围，则装入占空比寄存器。PWM_low = PWM_DUTY - high; //计算并保存PWM输出低电平的PCA时钟脉冲个数。CR = 1; //启动PCA。}
```

// 函数: void PWMn_init(unsigned int high)

// 描述: 初始化程序。

// 参数: high: 初始化占空比数据，即PWM输出高电平的PCA时钟脉冲个数。

// 返回: 无

// 版本 : VER1.0

// 日期: 2009-12-30

// 备注:

```c
voidPWMn_init(unsigned int high)  
{  
    #ifdef STC12C5201AD  
        P3M1 &= ~0x80, P3M0 |= 0x80; //CCAP0使用PUSH-PULL输出模式，//STC12C5201AD系列，P3.7。  
    #else  
        P1M1 &= ~0x08, P1M0 |= 0x08; //CCAP0使用PUSH-PULL输出模式，//STC12C5A60S2系列，P1.3。  
    #endif  
    CCON = 0; //清除CF、CR、CCF0、CCF1  
    IPH |= 0x80; //PCA中断使用最高优先级  
    PPCA = 1;
```

CMOD $=$ (PCA_IDLE_DISABLE $\ll 7$ )|(PCA_SOURCE_SELECT $\ll 1$ //初始化PCA模式寄存器，这两项在PWMn.h中选择。CCAPM0 $= 0\mathrm{x}4\mathrm{D}$ //高速输出模式，允许比较匹配中断(ECCF0=1)。CL $= 0$ //清空PCA基本计数器。CH $= 0$ CCAP0_tmp $= 0$ //清空CCAP0重装载影射寄存器。PWMn_SetHighReg(high); //初始化占空比数据。CR $= 1$ //启动PCA。EA $= 1$ //允许总中断

// 函数: void PCA_interrupt (void) interrupt 7

// 描述: PCA中断服务程序。

// 参数: 无。

// 返回: 无。

// 版本 : VER1.0

// 日期: 2009-12-30

// 备注:

```c
void PCA_interrupt(void) interrupt 7  
{ if(CCF0 == 1) //PCA模块0中断  
{ CCF0 = 0; //清PCA模块0中断标志  
if(CCP0 == 1) CCAP0_tmp += PWM_high; //输出为高电平，则给影射寄存器装载高电平时间长度 else CCAP0_tmp += PWM_low; //输出为低电平，则给影射寄存器装载低电平时间长度 CCAPOL = (unsigned char)CCAP0_tmp; //将影射寄存器写入捕获寄存器，先写CCAPOL CCAPOH = (unsigned char)(CCAP0_tmp >> 8); //后写CCAPOH}  
/* else if(CCF1 == 1) //PCA模块1中断  
{ CCF1 = 0; //清PCA模块1中断标志  
} else if(CF == 1) //PCA溢出中断  
{ CF = 0; //清PCA溢出中断标志  
}  
*/ }
```

# 11.9 用CCP/PCA的16位捕获模式测脉冲宽度的程序(C和汇编)

# 1. C程序：

/* */ 

/* --- STC MCU Limited. - */ 

/* --- STC15F2K60S2 系列 PCA实现16位捕获举例- */

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可- *

/*- */ 

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

#define FOSC 18432000L 

typedef unsigned char 

BYTE; 

typedef unsigned int 

WORD; 

typedef unsigned long 

DWORD; 

sfr P_SW1 = 0xA2; //外设功能切换寄存器1

#define CCP_S0 0x10 //P_SW1.4 

#define CCP_S1 0x20 //P_SW1.5 

sfr CCON $=$ 0xD8; //PCA控制寄存器

sbit CCF0 CCON^0; //PCA模块0中断标志

sbit CCF1 $=$ CCON^1; //PCA模块1中断标志

sbit CR 一 CCON^6; //PCA定时器运行控制位

sbit CF = CCON^7; //PCA定时器溢出标志

sfr CMOD 0xD9; //PCA模式寄存器

sfr CL 0xE9; //PCA定时器低字节

sfr CH 0xF9; //PCA定时器高字节

sfr CCAPM0 一 0xDA; //PCA模块0模式寄存器

sfr CCAP0L 0xEA; //PCA模块0捕获寄存器 LOW

sfr CCAP0H = 0xFA; //PCA模块0捕获寄存器 HIGH

sfr CCAPM1 = 0xDB; //PCA模块1模式寄存器

sfr CCAP1L 0xEB; //PCA模块1捕获寄存器 LOW

sfr CCAP1H = 0xFB; //PCA模块1捕获寄存器 HIGH

sfr CCAPM2 一 0xDC; //PCA模块2模式寄存器

sfr CCAP2L 0xEC; //PCA模块2捕获寄存器 LOW

sfr CCAP2H = 0xFC; //PCA模块2捕获寄存器 HIGH

sfr PCA_PWM0 = 0xf2; //PCA模块0的PWM寄存器

sfr PCA_PWM1 = 0xf3; //PCA模块1的PWM寄存器

sfr PCA_PWM2 = 0xf4; //PCA模块2的PWM寄存器

BYTE cnt; //存储PCA计时溢出次数

DWORD count0; //记录上一次的捕获值

DWORD count1; //记录本次的捕获值

DWORD length; //存储信号的时间长度(count1 - count0)

void main() 

{ 

ACC P_SW1; 

ACC &= ~(CCP_S0 | CCP_S1); //CCP_S0=0 CCP_S1=0 

P_SW1 $=$ ACC; //(P1.2/ECI, P1.1/CCP0, P1.0/CCP1, P3.7/CCP2) 

// ACC = P_SW1; 

// ACC &= ~(CCP_S0 | CCP_S1); //CCP_S0=1 CCP_S1=0 

// ACC |= CCP_S0; //(P3.4/ECI_2, P3.5/CCP0_2, P3.6/CCP1_2, P3.7/CCP2_2) 

// P_SW1 = ACC; 

// 

// ACC = P_SW1; 

// ACC &= ~(CCP_S0 | CCP_S1); //CCP_S0=0 CCP_S1=1 

// ACC |= CCP_S1; //(P2.4/ECI_3, P2.5/CCP0_3, P2.6/CCP1_3, P2.7/CCP2_3) 

// P_SW1 = ACC; 

CCON = 0; //初始化PCA控制寄存器

//PCA定时器停止

//清除CF标志

//清除模块中断标志

CL 0; //复位PCA寄存器

CH 一 0;

CCAP0L = 0; 

CCAP0H = 0; 

CMOD = 0x09; //设置PCA时钟源为系统时钟,且使能PCA计时溢出中断

CCAPM0= 0x21; //PCA模块0为16位捕获模式(上升沿 捕获,

//可测从高电平开始的整个周期),且产生捕获中断

// CCAPM0= 0x11; //PCA模块0为16位捕获模式(下降沿 捕获,

//可测从低电平开始的整个周期),且产生捕获中断

// CCAPM0= 0x31; //PCA模块0为16位捕获模式(上升沿 /下降沿 捕获,

//可测高电平或者低电平宽度),且产生捕获中断

CR 1; //PCA定时器开始工作

EA 1; 

cnt 0; 

count0 $=$ 0; 

count1 $=$ 0; 

while(1);   
}   
void PCA_isr() interrupt 7 using 1   
{ if(CF) { $\mathrm{CF} = 0;$ cnt++; //PCA计时溢出次数 $+1$ } if(CCF0) { $\mathrm{CCF0} = 0;$ count0=count1; //备份上一次的捕获值 ((BYTE*)&count1)[3] $\equiv$ CCAPOL; //保存本次的捕获值 ((BYTE*)&count1)[2] $\equiv$ CCAPOH; ((BYTE*)&count1)[1] $\equiv$ cnt; ((BYTE*)&count1)[0] $\equiv 0$ length $\equiv$ count1 - count0; //计算两次捕获的差值，即得到时间长度 }

# 2. 汇编程序：

/*- */ 

/* --- STC MCU Limited. - */ 

/* --- STC15F2K60S2 系列 PCA实现16位捕获举例- */

/* --- 研发顾问QQ：800003751- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可- *

/* */ 

//假定测试芯片的工作频率为18.432MHz

P_SW1 EQU 0A2H ;外设功能切换寄存器1

CCP_S0 EQU 10H ;P_SW1.4 

CCP_S1 EQU 20H ;P_SW1.5 

CCON EQU 0D8H ;PCA控制寄存器

CCF0 BIT CCON.0 ;PCA模块0中断标志

CCF1 BIT CCON.1 ;PCA模块1中断标志

CR BIT CCON.6 ;PCA定时器运行控制位

CF BIT CCON.7 ;PCA定时器溢出标志

CMOD EQU 0D9H ;PCA模式寄存器

CL EQU 0E9H ;PCA定时器低字节

CH EQU 0F9H ;PCA定时器高字节

CCAPM0 EQU 0DAH ;PCA模块0模式寄存器

CCAP0L EQU 0EAH ;PCA模块0捕获寄存器 LOW

CCAP0H EQU 0FAH ;PCA模块0捕获寄存器 HIGH

CCAPM1 EQU 0DBH ;PCA模块1模式寄存器

CCAP1L EQU 0EBH ;PCA模块1捕获寄存器 LOW

CCAP1H EQU 0FBH ;PCA模块1捕获寄存器 HIGH

CCAPM2 EQU 0DCH ;PCA模块2模式寄存器

CCAP2L EQU 0ECH ;PCA模块2捕获寄存器 LOW

CCAP2H EQU 0FCH ;PCA模块2捕获寄存器 HIGH

PCA_PWM0 EQU 0F2H ;PCA模块0的PWM寄存器

PCA_PWM1 EQU 0F3H ;PCA模块1的PWM寄存器

PCA_PWM2 EQU 0F4H ;PCA模块2的PWM寄存器

CNT EQU 30H ;存储PCA计时溢出次数

COUNT0 EQU 31H ;记录上一次的捕获值,3字节

COUNT1 EQU 34H ;记录本次的捕获值,3字节

LENGTH EQU 37H ;存储信号的时间长度,3字节(count1 - count0)

ORG 0000H 

LJMP MAIN 

ORG 003BH 

PCA_ISR: 

PUSH PSW 

PUSH ACC 

JNB CF, CKECK_CCF0 ;判断是否为PCA计时溢出中断

CLR CF 

INC CNT ;PCA计时溢出次数+1

CKECK_CCF0: 

JNB CCF0, PCA_ISR_EXIT ;判断是否为捕获中断

CLR CCF0 

MOV COUNT0, COUNT1 ;备份上一次的捕获值

MOV COUNT0+1, COUNT1+1 

MOV COUNT0+2, COUNT1+2 

MOV COUNT1, CNT ;保存本次的捕获值

MOV COUNT1+1, CCAP0H 

MOV COUNT1+2, CCAP0L 

CLR C ;计算两次捕获的差值

MOV A, COUNT1+2 

SUBB A, COUNT0+2 

MOV LENGTH+2, A 

MOV A, COUNT1+1 

SUBB A, COUNT0+1 

MOV LENGTH+1, A 

MOV A, COUNT1 

SUBB A, COUNT0 

MOV LENGTH, A ;LENGTH存放的即为时间长度

PCA_ISR_EXIT: 

POP ACC 

POP PSW 

RETI 

ORG 0100H 

MAIN: 

MOV SP, #5FH 

MOV A, P_SW1 

ANL A, #0CFH //CCP_S0=0 CCP_S1=0 

MOV P_SW1, A //(P1.2/ECI, P1.1/CCP0, P1.0/CCP1, P3.7/CCP2) 

// MOV A, P_SW1 

// ANL A, #0CFH //CCP_S0=1 CCP_S1=0 

// ORL A, #CCP_S0 //(P3.4/ECI_2, P3.5/CCP0_2, P3.6/CCP1_2, P3.7/CCP2_2) 

// MOV P_SW1, A 

// // MOV A, P_SW1 

```txt
// ANL A, #0CFH //CCP_S0=0 CCP_S1=1  
// ORL A, #CCP_S1 // (P2.4/ECI_3, P2.5/CCP0_3, P2.6/CCP1_3, P2.7/CCP2_3)  
// MOV P_SW1, A 
```

```txt
MOV CCON, #0 
```

;初始化PCA控制寄存器

;PCA定时器停止

;清除CF标志

;清除模块中断标志

CLR A 

;复位PCA计时器

MOV CL, A 

MOV CH, A 

MOV CCAP0L, A 

MOV CCAP0H, A 

MOV CMOD, #09H 

;设置PCA时钟源为系统时钟

;使能PCA定时器溢出中断

MOV CCAPM0, #21H 

;PCA模块0为16位捕获模式(上升沿 捕获,

;可测从高电平开始的整个周期),且产生捕获中断

;PCA模块0为16位捕获模式(下降沿 捕获,

;可测从低电平开始的整个周期),且产生捕获中断

MOV CCAPM0, #11H 

;PCA模块0为16位捕获模式(上升沿 /下降沿 捕获,

;可测高电平或者低电平宽度),且产生捕获中断

MOV CCAPM0, #31H 

SETB CR 

;PCA定时器开始工作

SETB EA 

CLR A 

;初始化变量

MOV CNT, A 

MOV COUNT0, A 

MOV COUNT0+1, A 

MOV COUNT0+2, A 

MOV COUNT1, A 

MOV COUNT1+1, A 

MOV COUNT1+2, A 

MOV LENGTH, A 

MOV LENGTH+1, A 

MOV LENGTH+2, A 

SJMP $ 

END 

# 11.10 用T0软硬结合模拟10位/16位PWM输出的程序(C及汇编)利用定时器T0的16位自动重装载模式来模拟

# 1. C程序：

$$
\begin{array}{l} / * \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_ \_
\] \\ / * - - S T C M C U L i m i t e d. \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \cdot / \\ /* - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - \\ / ^ {*} - - - \text {研 发 顾 问} Q Q: 8 0 0 0 0 3 7 5 1 - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - \\ /* - - - F a x: 8 6 - 7 5 5 - 8 2 9 0 5 9 6 6 * / \\ / ^ {*} - \text {T e l : 8 6 - 7 5 5 - 8 2 9 4 8 4 1 2} \quad * / \\ /* - - - \text {W e b : w w w . S T C M C U . c o m} - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - \\ /* \text {如 果 要 在 程 序 中 使 用 此 代 码} \text {, 请 在 程 序 中 注 明 使 用 了 S T C 的 资 料 及 程 序} - - - - * / \\ / * \text {如 果 要 在 文 章 中 应 用 此 代 码 , 请 在 文 章 中 注 明 使 用 了 S T C 的 资 料 及 程 序} - - - / * \\ /* - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - \\ / * \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \ast / \\ \end{array}
$$


//假定测试芯片的工作频率为18.432MHz


include"reg51.h"   
//definePWM6BIT 64 //6-bitPWM周期数 #definePWM8BIT 256 //8-bitPWM周期数   
//#definePWM10BIT 1024 //10-bitPWM周期数   
//#definePWM16BIT 65536 //16-bitPWM周期数   
#defineHIGHDUTY 64 //高电平周期数(占空比 $64 / 256 = 25\%$ #defineLOWDUTY (PWM8BIT-HIGHDUTY) //低电平周期数   
sfr AUXR $=$ 0x8e; //辅助寄存器 sfr INT_CLKO $=$ 0x8f; //时钟输出控制寄存器 sbit T0CLKO $=$ P3^5; //定时器0的时钟输出口   
bit flag;   
//定时器0中断服务程序   
void tm0() interrupt 1   
{ flag $=$ !flag; //反转PWM的输出标志 if (flag) { TL0=(65536-HIGHDUTY); //准备高电平的重载值 TH0=(65536-HIGHDUTY) $\ggg$ 8; } else { TL0=(65536-LOWDUTY); //准备低电平的重载值 TH0=(65536-LOWDUTY) $\ggg$ 8; }

```c
void main()  
{  
    AUXR = 0x80; //定时器0为1T模式  
    INT_CLKO = 0x01; //使能定时器0的时钟输出功能  
    TMOD &= 0xf0; //设置定时器0为模式0(16位自动重装载)  
    TL0 = (65536-LOWDUTY); //初始化定时器初值和重装值  
    TH0 = (65536-LOWDUTY) >> 8;  
    TOCLKO = 1; //初始化时钟输出脚(软PWM口)  
    flag = 0; //初始化标志位  
    TR0 = 1; //定时器0开始计时  
    ET0 = 1; //使能定时器0中断  
    EA = 1;  
    while (1);  
}
```

# 2. 汇编程序：

/* */ 

/* --- STC MCU Limited. - */ 

/* --- STC15F2K60S2 系列 定时器软件模拟PWM举例------ */

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com -- */ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序---- */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序---- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可- *

/*- */ 

//假定测试芯片的工作频率为18.432MHz

;PWM6BIT EQU 64 ;6-bit PWM周期数

PWM8BIT EQU 256 ;8-bit PWM周期数

;PWM10BIT EQU 1024 ;10-bit PWM周期数

;PWM16BIT EQU 65536 ;16-bit PWM周期数

HIGHDUTY EQU 64 ;高电平周期数(占空比64/256=25%)

LOWDUTY EQU (PWM8BIT-HIGHDUTY) ;低电平周期数

AUXR DATA 08EH ;辅助寄存器

INT_CLKO DATA 08FH ;时钟输出控制寄存器

T0CLKO BIT P3.5 ;定时器0的时钟输出口

FLAG BIT 20H.0 

ORG 0000H 

LJMP MAIN 

ORG 000BH 

LJMP TM0_ISR 

# MAIN:

MOV AUXR, #80H 

MOV INT_CLKO, #01H 

ANL TMOD, #0F0H 

MOV TL0, #LOW (65536-LOWDUTY) 

MOV TH0, #HIGH (65536-LOWDUTY) 

SETB T0CLKO 

CLR FLAG 

SETB TR0 

SETB ET0 

SETB EA 

SJMP $ 

;定时器0为1T模式

;使能定时器0的时钟输出功能

;设置定时器0为模式0(16位自动重装载)

;初始化定时器初值和重装值

;初始化时钟输出脚(软PWM口)

;初始化标志位

;定时器0开始计时

;使能定时器0中断

;定时器0中断服务程序

TM0_ISR: 

CPL FLAG 

JNB FLAG, READYLOW 

READYHIGH: 

MOV TL0, #LOW (65536-HIGHDUTY) 

MOV TH0, #HIGH (65536-HIGHDUTY) 

JMP TM0ISR_EXIT 

READYLOW: 

MOV TL0, #LOW (65536-LOWDUTY) 

MOV TH0, #HIGH (65536-LOWDUTY) 

TM0ISR_EXIT: 

RETI 

;反转PWM的输出标志

;准备高电平的重载值

;准备低电平的重载值

END 

# 11.11 比利用CCP/PCA模块实现8~16位DAC的参考线路图

CCP：是英文单词的缩写

Capture(捕获),Compare(比较),PWM(脉宽调制)

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c46b891c0f66c9549fa9df75e20755aa9f8cd06a185c6fdaa19513cf27c7badf.jpg)


如应用简单，可无需基准参考电压源，直接与Vcc比较即可。

利用CCP/PCA模块的高速脉冲输出功能实现9~16位PWM来实现9~16位DAC，或用本身的硬件8位PWM来实现8位DAC，单片机本身也有10位ADC。

# 提示：

（1）PWM频率越高，输出波形越平滑。

（2）如果工作电压为5V，需输出1V电压，则设置高电平为1/5，低电平为4/5，则PWM输出电压就为1V。

（3）如果要输出高精准电压，建议用A/D检测输出的电压值，然后根据A/D检测的电压值逐步调整到所需要的电压。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/9948bf4ee46f448e051dc5bb1cb9269d00b466ae0152cf4567f32f8b7a1a69b0.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/23f5b082a9a7635e2f64ce0bb51171587178ad82b307119b9e9a32075d63070e.jpg)


如应用简单，可无需基准参考电压源，直接与Vcc比较即可。

# 第12章 STC15W系列的比较器

STC15W系列单片机(如STC15W408AS系列、STC15W201S系列、STC15W408S系列、STC15W1K16S系列及STC15W4K60S4系列)内置比较器功能。其中STC15W201S系列、STC15W408S系列及STC15W1K16S系列的比较器内部规划如下图所示:

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/bf055054a0ca59371e25d7faab2e899f8c0ff0c5973f95fdfffa3d85d63d04d6.jpg)


其中，有ADC的单片机STC15W408AS系列及STC15W4K60S4系列的比较器内部规划如下图所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7b646dfbb4a8bda46ff10f69d56433b7e9b6d5b7d55d72116043da4ed44be9fd.jpg)


STC15W系列与比较器相关的��特殊 (STC15W SFRs associated with comparator)

<table><tr><td rowspan="2">符号</td><td rowspan="2">描述</td><td rowspan="2">地址</td><td colspan="8">位地址及其符号</td><td rowspan="2">复位值</td></tr><tr><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>CMPCR1</td><td>比较器控制寄存器1</td><td>E6H</td><td>CMPEN</td><td>CMPIF</td><td>PIE</td><td>NIE</td><td>PIS</td><td>NIS</td><td>CMPOE</td><td>CMPRES</td><td>0000,0000</td></tr><tr><td>CMPCR2</td><td>比较器控制寄存器2</td><td>E7H</td><td>INVCMPO</td><td>DISFLT</td><td colspan="6">LCDTY[5:0]</td><td>0000,1001</td></tr></table>

# 1. 比较器控制寄存器1：CMPCR1

比较器控制寄存器1的格式如下：

CMPCR1 : 比较器控制寄存器1

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>CMPCR1</td><td>E6H</td><td>name</td><td>CMPEN</td><td>CMPIF</td><td>PIE</td><td>NIE</td><td>PIS</td><td>NIS</td><td>CMPOE</td><td>CMPRES</td></tr></table>

CMPEN：比较器模块使能位

CMPEN=1，使能比较器模块；

CMPEN=0，禁用比较器模块, 比较器的电源关闭。

CMPIF： ��� (Interrupt Flag) 

在 CMPEN为1的情况下：

当比较器的比较结果由LOW变成HIGH时, 若是PIE被设置成1, 那么内建的某一个叫做CMPIF_p的寄存器会被设置成1；

当比较器的比较结果由HIGH变成LOW时, 若是NIE被设置成1, 那么内建的某一个叫做CMPIF_n的寄存器会被设置成1；

当CPU 去读取 CMPIF 的数值时, 会读到 (CMPIF_p || CMPIF_n);

当CPU对CMPIF写0后, CMPIF_p 以及 CMPIF_n 都会被清除为0 .

而中断产生的条件是 [ $( \mathrm { E A } { = } { = } 1$ ) && (((PIE $\scriptstyle - = 1$ )&&(CMPIF_p $\scriptstyle 1 = = 1$ )) || ((NIE $\scriptstyle = = 1$ )&&(CMPIF_n==1))) ]

CPU接受中断后, 并不会自动清除此CMPIF标志 , 用户必须用软件写”0”去清除它。

PIE： 比较器上升沿中断使能位( Pos-edge Interrupt Enabling)

$\mathrm { P I E } = 1$ ， LOW变HIGH的事件 设定CMPIF_p/产生中断；

$\mathrm { P I E } = 0$ ， LOW变HIGH的事件 设定CMPIF_p/产生中断。

NIE： 比较器下降沿中断使能位 ( Neg-edge Interrupt Enabling)

$\mathrm { N E } = 1$ ， HIGH变LOW的事件 设定CMPIF_n/产生中断；

$\mathrm { N E } = 0$ ， HIGH变LOW的事件 设定CMPIF_n/产生中断。

PIS： 比较器正极选择位

$\mathrm { P I S } = 1$ ， ADCIS[2:0] 所选择到的 ADCIN 做为比较器的正极输入源

$\mathrm { P I S } = 0$ ，选择�外 P5.5为比较器的正极输入源

NIS：比较器负极选择位

$\mathrm { N I S } = 1$ ， � ��P5.4为比较器的负极输入源

${ \mathrm { N I S } } = 0$ ，选择 BandGap电压BGV为比较器的负极输入源

CMPOE：比较结果输出控制位

$\mathbf { C M P O E } = 1$ $= 1$ ，使能比较器的比较结果输出到P1.2；

CMPOE $= 0$ ， �比较器的比较结果输出

CMPRES：比较器比较结果 (Comparator Result)标志 位

CMPRES $= 1$ ，CMP+的电平高于CMP-的电平(或内部BandGap参考电压的电平)；

CMPRES $= 0$ ， ${ \mathrm { C M P } } +$ 的电平低于CMP-的电平

此 bit 是一个”只读(read-only)”的bit ; 软件对它做写入的动作没有任何意义。软件所读到的结果是“经过ENLCCTL控制后的结果”, 而非Analog比较器的直接输出结果.

# 2. 比较器控制寄存器2：CMPCR2

比较器控制寄存器2的格式如下：

CMPCR2 : 比较器控制寄存器2

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>CMPCR2</td><td>E7H</td><td>name</td><td>INVCMPO</td><td>DISFLT</td><td colspan="6">LCDTY[5:0]</td></tr></table>

INVCMPO：比较器输出取反控制位 (Inverse Comparator Output)

INVCMPO $= 1$ ，比较器取反后再输出到P1.2；

INVCMPO $= 0$ ，比较器正常输出。

比较器的输出, 采用“经过ENLCCTL控制后的结果”, 而非Analog比较器的直接输出结果.

DISFLT：去除比较器输出的 0.1uS Filter

DISFLT $= 1$ ， � 0.1uS Filter (可以让比较器速度有少许提升)；

DISFLT $= 0$ ， 0.1uS 的 Filter。

LCDTY[5:0]：比较器输出端 Level-Change control的 filter 长度(Duty)选择

bbbbbb： $=$ 

当比较器由LOW变HIGH, 必须侦测到该后来的HIGH持续至少bbbbbb个时钟, 此芯片线路才认定比较器的输出是由LOW转成HIGH; 如果在bbbbbb个时钟内, Analog比较器的输出又回复到LOW, 此芯片线路认为甚么都没发生, 视同比较器的输出一直维持在LOW；

当比较器由HIGH变LOW, 必须侦测到该后来的LOW持续至少bbbbbb个时钟, 此芯片线路才认定比较器的输出是由HIGH转成LOW; 如果在bbbbbb个时钟内, Analog比较器的输出又回复到HIGH, 此芯片线路认为甚么都没发生, 视同比较器的输出一直维持在HIGH.

若是设定成 000000, 代表没有 Level-Change Control.

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a4038e4f66b73affd09c50171f5a55956fd299fbd44d366052a5851deb7ca43a.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/295432a308ef28c9f47a0ebb58df590b9ad739f8bebb618dd49fdb4e84356e2e.jpg)


# 12.1 比较器中断方式程序举例(C及汇编)

# 1.C语言程序

/* -*/ 

/* --- STC MCU Limited * 

/* --- STC15W4K60S4 系列 比较器中断方式举例--- -*/

/* --- 研发顾问QQ：800003751- -*/

/* --- Fax: 86-755-82905966 --- --*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/*-- -*/ 

//本示例在Keil开发环境下请选择Intel的8052芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

sfr CMPCR1 = 0xE6; //比较器控制寄存器1

#define CMPEN 0x80 //CMPCR1.7 : 比较器模块使能位

<table><tr><td>#define</td><td>CMPIF</td><td>0x40</td><td>//CMPCR1.6:比较器中断标志位</td></tr><tr><td>#define</td><td>PIE</td><td>0x20</td><td>//CMPCR1.5:比较器上升沿中断使能位</td></tr><tr><td>#define</td><td>NIE</td><td>0x10</td><td>//CMPCR1.4:比较器下降沿中断使能位</td></tr><tr><td>#define</td><td>PIS</td><td>0x08</td><td>//CMPCR1.3:比较器正极选择位</td></tr><tr><td>#define</td><td>NIS</td><td>0x04</td><td>//CMPCR1.2:比较器负极选择位</td></tr><tr><td>#define</td><td>CMPOE</td><td>0x02</td><td>//CMPCR1.1:比较结果输出控制位</td></tr><tr><td>#define</td><td>CMPRES</td><td>0x01</td><td>//CMPCR1.0:比较器比较结果标志位</td></tr><tr><td>sfr</td><td colspan="2">CMPCR2 = 0xE7;</td><td>//比较器控制寄存器2</td></tr><tr><td>#define</td><td>INVCMPO</td><td>0x80</td><td>//CMPCR2.7:比较结果反向输出控制位</td></tr><tr><td>#define</td><td>DISFLT</td><td>0x40</td><td>//CMPCR2.6:比较器输出端虑波使能控制位</td></tr><tr><td>#define</td><td>LCDTY</td><td>0x3F</td><td>//CMPCR2.[5:0]:比较器输出的区抖时间控制</td></tr><tr><td>sbit</td><td colspan="2">LED = P1^1;</td><td>//测试脚</td></tr><tr><td colspan="3">void cmp_isr() interrupt 21 using 1</td><td>//比较器中断向量入口</td></tr><tr><td>{</td><td colspan="2">CMPCR1 &amp;= ~CMPIF;</td><td>//清除完成标志</td></tr><tr><td colspan="3">LED = !!(CMPCR1 &amp; CMPRES);</td><td>//将比较器结果CMPRES输出到测试口显示</td></tr><tr><td colspan="4">}</td></tr><tr><td colspan="4">void main()</td></tr><tr><td rowspan="2">{</td><td>CMPCR1 = 0;</td><td colspan="2">//初始化比较器控制寄存器1</td></tr><tr><td>CMPCR2 = 0;</td><td colspan="2">//初始化比较器控制寄存器2</td></tr><tr><td rowspan="2">//</td><td>CMPCR1 &amp;= ~PIS;</td><td colspan="2">//选择外部管脚P5.5（CMP+）为比较器的正极输入源</td></tr><tr><td>CMPCR1 |= PIS;</td><td colspan="2">//选择ADCIS[2:0]所选的ADCIN为比较器的正极输入源</td></tr><tr><td rowspan="2">//</td><td>CMPCR1 &amp;= ~NIS;</td><td colspan="2">//选择内部BandGap电压BGV为比较器的负极输入源</td></tr><tr><td>CMPCR1 |= NIS;</td><td colspan="2">//选择外部管脚P5.4（CMP-）为比较器的负极输入源</td></tr><tr><td rowspan="2">//</td><td>CMPCR1 &amp;= ~CMPOE;</td><td colspan="2">//禁用比较器的比较结果输出</td></tr><tr><td>CMPCR1 |= CMPOE;</td><td colspan="2">//使能比较器的比较结果输出到P1.2</td></tr><tr><td rowspan="2">//</td><td>CMPCR2 &amp;= ~INVCMPO;</td><td colspan="2">//比较器的比较结果正常输出到P1.2</td></tr><tr><td>CMPCR2 |= INVCMPO;</td><td colspan="2">//比较器的比较结果取反后输出到P1.2</td></tr><tr><td rowspan="2">//</td><td>CMPCR2 &amp;= ~DISFLT;</td><td colspan="2">//不禁用(使能)比较器输出端的0.1uS虚波电路</td></tr><tr><td>CMPCR2 |= DISFLT;</td><td colspan="2">//禁用比较器输出端的0.1uS虚波电路</td></tr><tr><td rowspan="2">//</td><td>CMPCR2 &amp;= ~LCDTY;</td><td colspan="2">//比较器结果不去抖动,直接输出</td></tr><tr><td>CMPCR2 |= (DISFLT &amp; 0x10);</td><td colspan="2">//比较器结果在经过16个时钟后再输出</td></tr></table>

CMPCR1 $\vDash$ PIE; //使能比较器的上升沿中断  
// CMPCR1 $\vDash$ NIE; //使能比较器的下降沿中断  
CMPCR1 $\vDash$ CMPEN; //使能比较器  
EA = 1;  
while (1);

# 2.汇编程序

/*- -*/ 

/* --- STC MCU Limited - ----*/ 

/* --- STC15W4K60S4 系列 比较器中断方式举例--- ---------*/

/* --- 研发顾问QQ：800003751-- -------------*/

/* --- Fax: 86-755-82905966 - */ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com * 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/* * 

//本示例在Keil开发环境下请选择Intel的8052芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

```asm
CMPCR1 DATA 0E6H ;比较器控制寄存器1  
CMPEN EQU 080H ;CMPCR1.7: 比较器模块使能位  
CMPIF EQU 040H ;CMPCR1.6: 比较器中断标志位  
PIE EQU 020H ;CMPCR1.5: 比较器上升沿中断使能位  
NIE EQU 010H ;CMPCR1.4: 比较器下降沿中断使能位  
PIS EQU 008H ;CMPCR1.3: 比较器正极选择位  
NIS EQU 004H ;CMPCR1.2: 比较器负极选择位  
CMPOE EQU 002H ;CMPCR1.1: 比较结果输出控制位  
CMPRES EQU 001H ;CMPCR1.0: 比较器比较结果标志位  
CMPCR2 DATA 0E7H ;比较器控制寄存器2  
INVCMPO EQU 080H ;CMPCR2.7: 比较结果反向输出控制位  
DISFLT EQU 040H ;CMPCR2.6: 比较器输出端虑波使能控制位  
LCDTY EQU 03FH ;CMPCR2.[5:0]: 比较器输出的区抖时间控制  
LED BIT P1.1 ;测试脚
```

<table><tr><td>ORG</td><td>0000H</td><td></td></tr><tr><td>LJMP</td><td>MAIN</td><td></td></tr><tr><td>ORG</td><td>00ABH</td><td></td></tr><tr><td>LJMP</td><td>CMP_ISR</td><td>;比较器中断向量入口</td></tr><tr><td>ORG</td><td>0100H</td><td></td></tr><tr><td>MAIN:</td><td></td><td></td></tr><tr><td>MOV</td><td>CMPCR1,</td><td>#0 ;初始化比较器控制寄存器</td></tr><tr><td>MOV</td><td>CMPCR2,</td><td>#0 ;初始化比较器控制寄存器</td></tr><tr><td>ANL</td><td>CMPCR1,</td><td>#NOT PIS</td></tr><tr><td>ORL</td><td>CMPCR1,</td><td>;选择外部管脚P5.5（CMP+）为比较器的正极输入源</td></tr><tr><td>ANL</td><td>CMPCR1,</td><td>#PIS ;选择ADCIS[2:0]所选的ADCIN为比较器的正极输入源</td></tr><tr><td>ORL</td><td>CMPCR1,</td><td>#NOT NIS</td></tr><tr><td>ORL</td><td>CMPCR1,</td><td>;选择内部BandGap电压BGV为比较器的负极输入源</td></tr><tr><td>ANL</td><td>CMPCR1,</td><td>#NIS ;选择外部管脚P5.4（CMP-）为比较器的负极输入源</td></tr><tr><td>ORL</td><td>CMPCR1,</td><td>#NOT CMPOE</td></tr><tr><td>ANL</td><td>CMPCR2,</td><td>;禁用比较器的比较结果输出</td></tr><tr><td>ORL</td><td>CMPCR2,</td><td>#CMPOE</td></tr><tr><td>ANL</td><td>CMPCR2,</td><td>;使能比较器的比较结果输出到P1.2</td></tr><tr><td>ORL</td><td>CMPCR2,</td><td>#NOT INVCMPO</td></tr><tr><td>ANL</td><td>CMPCR2,</td><td>;比较器的比较结果正常输出到P1.2</td></tr><tr><td>ORL</td><td>CMPCR2,</td><td>#INVCMPO</td></tr><tr><td>ANL</td><td>CMPCR2,</td><td>;比较器的比较结果取反后输出到P1.2</td></tr><tr><td>ORL</td><td>CMPCR2,</td><td>#NOT DISFLT</td></tr><tr><td>ANL</td><td>CMPCR2,</td><td>;不禁用(使能)比较器输出端的0.1uS虑波电路</td></tr><tr><td>ORL</td><td>CMPCR2,</td><td>#DISFLT</td></tr><tr><td>ANL</td><td>CMPCR2,</td><td>;禁用比较器输出端的0.1uS虑波电路</td></tr><tr><td>ORL</td><td>CMPCR2,</td><td>#NOT LCDTY</td></tr><tr><td>ORL</td><td>CMPCR2,</td><td>;(DISFLT AND 0x10)</td></tr><tr><td>ORL</td><td>CMPCR2,</td><td>;比较器结果在经过16个时钟后再输出</td></tr><tr><td>ORL</td><td>CMPCR1,</td><td>#PIE</td></tr><tr><td>ORL</td><td>CMPCR1,</td><td>#NIE</td></tr></table>

ORL CMPCR1, #CMPEN ;使能比较器

SETB EA 

SJMP $ 

CMP_ISR: 

PUSH PSW 

PUSH ACC 

ANL CMPCR1, #NOT CMPIF ;清除完成标志

MOV A, CMPCR1 

MOV C, ACC.0 ;将比较器结果CMPRES输出到测试口显示

MOV LED, C 

POP ACC 

POP PSW 

RETI 

END 

# 12.2 比较器查询方式程序举例(C及汇编)

# 1.C语言程序

/*- -*/ 

/* --- STC MCU Limited - */ 

/* --- STC15W4K60S4 系列 比较器查询方式举例- */

/* --- 研发顾问QQ：800003751-- --*/

/* --- Fax: 86-755-82905966 - -*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/*- -*/ 

//本示例在Keil开发环境下请选择Intel的8052芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#include "intrins.h" 

sfr CMPCR1= 0xE6; //比较器控制寄存器1

#define CMPEN 0x80 //CMPCR1.7 : 比较器模块使能位

#define CMPIF 0x40 //CMPCR1.6 : 比较器中断标志位

#define PIE 0x20 //CMPCR1.5 : 比较器上升沿中断使能位

#define NIE 0x10 //CMPCR1.4 : 比较器下降沿中断使能位

#define PIS 0x08 //CMPCR1.3 : 比较器正极选择位

#define NIS 0x04 //CMPCR1.2 : 比较器负极选择位

#define CMPOE 0x02 //CMPCR1.1 : 比较结果输出控制位

#define CMPRES 0x01 //CMPCR1.0 : 比较器比较结果标志位

sfr CMPCR2 = 0xE7; //比较器控制寄存器2

#define INVCMPO 0x80 //CMPCR2.7 : 比较结果反向输出控制位

#define DISFLT 0x40 //CMPCR2.6 : 比较器输出端0.1us虑波控制位

#define LCDTY 0x3F //CMPCR2.[5:0] : 比较器输出的区抖时间控制

sbit LED = P1^1; //测试脚

void main() 

{$\mathbf { C M P C R 1 } = 0$ ; //初始化比较器控制寄存器1

CMPCR2 = 0; //初始化比较器控制寄存器2

CMPCR1 &= ~PIS; //选择外部管脚P5.5（CMP+）为比较器的正极输入源

// CMPCR1 |= PIS; //选择ADCIS[2:0]所选的ADCIN为比较器的正极输入源

CMPCR1 &= ~NIS; //选择内部BandGap电压BGV为比较器的负极输入源

// CMPCR1 |= NIS; //选择外部管脚P5.4（CMP-）为比较器的负极输入源

```txt
CMPCR1 &=~CMPOE; //禁用比较器的比较结果输出  
CMPCR1 |= CMPOE; //使能比较器的比较结果输出到P1.2  
CMPCR2 &=~INVCMPO; //比较器的比较结果正常输出到P1.2  
CMPCR2 |= INVCMPO; //比较器的比较结果取反后输出到P1.2  
CMPCR2 &=~DISFLT; //不禁用(使能)比较器输出端的0.1uS虑波电路  
CMPCR2 |= DISFLT; //禁用比较器输出端的0.1uS虑波电路  
CMPCR2 &=~LCDTY; //比较器结果不去抖动,直接输出  
CMPCR2 |= (DISFLT & 0x10); //比较器结果在经过16个时钟后再输出  
CMPCR1 |= CMPEN; //使能比较器  
while (!(CMPCR1 & CMPIF)); //查询比较完成标志  
CMPCR1 &=~CMPIF; //清除完成标志  
LED = !!(CMPCR1 & CMPRES); //将比较器结果CMPRES输出到测试口显示  
while (1);
```

# 2.汇编程序

/* * 

/* --- STC MCU Limited ----------- */ 

/* --- STC15W4K60S4 系列 比较器查询方式举例- -*/

/* --- 研发顾问QQ：800003751- -*/

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/* * 

//本示例在Keil开发环境下请选择Intel的8052芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

<table><tr><td>CMPCR1</td><td>DATA</td><td>0E6H</td><td>;比较器控制寄存器1</td></tr><tr><td>CMPEN</td><td>EQU</td><td>080H</td><td>;CMPCR1.7:比较器模块使能位</td></tr><tr><td>CMPIF</td><td>EQU</td><td>040H</td><td>;CMPCR1.6:比较器中断标志位</td></tr><tr><td>PIE</td><td>EQU</td><td>020H</td><td>;CMPCR1.5:比较器上升沿中断使能位</td></tr><tr><td>NIE</td><td>EQU</td><td>010H</td><td>;CMPCR1.4:比较器下降沿中断使能位</td></tr><tr><td>PIS</td><td>EQU</td><td>008H</td><td>;CMPCR1.3:比较器正极选择位</td></tr><tr><td>NIS</td><td>EQU</td><td>004H</td><td>;CMPCR1.2:比较器负极选择位</td></tr><tr><td>CMPOE</td><td>EQU</td><td>002H</td><td>;CMPCR1.1:比较结果输出控制位</td></tr><tr><td>CMPRES</td><td>EQU</td><td>001H</td><td>;CMPCR1.0:比较器比较结果标志位</td></tr></table>

<table><tr><td>CMPCR2</td><td>DATA</td><td>0E7H</td><td>;比较器控制寄存器2</td></tr><tr><td>INVCMPO</td><td>EQU</td><td>080H</td><td>;CMPCR2.7:比较结果反向输出控制位</td></tr><tr><td>DISFLT</td><td>EQU</td><td>040H</td><td>;CMPCR2.6:比较器输出端虑波使能控制位</td></tr><tr><td>LCDTY</td><td>EQU</td><td>03FH</td><td>;CMPCR2.[5:0]:比较器输出的区抖时间控制</td></tr><tr><td>LED</td><td>BIT</td><td>P1.1</td><td>;测试脚</td></tr><tr><td>ORG</td><td>0000H</td><td></td><td></td></tr><tr><td>LJMP</td><td>MAIN</td><td></td><td></td></tr><tr><td>ORG</td><td>0100H</td><td></td><td></td></tr><tr><td>MOV</td><td>CMPCR1,</td><td>#0</td><td>;初始化比较器控制寄存器</td></tr><tr><td>MOV</td><td>CMPCR2,</td><td>#0</td><td>;初始化比较器控制寄存器</td></tr><tr><td>ANL</td><td>CMPCR1,</td><td colspan="2">#NOT PIS;选择外部管脚P5.5(CMP+)为比较器的正极输入源</td></tr><tr><td>ORL</td><td>CMPCR1,</td><td colspan="2">#PIS;选择ADCIS[2:0]所选的ADCIN为比较器的正极输入源</td></tr><tr><td>ANL</td><td>CMPCR1,</td><td colspan="2">#NOT NIS;选择内部BandGap电压BGV为比较器的负极输入源</td></tr><tr><td>ORL</td><td>CMPCR1,</td><td colspan="2">#NIS;选择外部管脚P5.4(CMP-)为比较器的负极输入源</td></tr><tr><td>ANL</td><td>CMPCR1,</td><td colspan="2">#NOT CMPOE;禁用比较器的比较结果输出</td></tr><tr><td>ORL</td><td>CMPCR1,</td><td colspan="2">#CMPOE;使能比较器的比较结果输出到P1.2</td></tr><tr><td>ANL</td><td>CMPCR2,</td><td colspan="2">#NOT INVCMPO;比较器的比较结果正常输出到P1.2</td></tr><tr><td>ORL</td><td>CMPCR2,</td><td colspan="2">#INVCMPO;比较器的比较结果取反后输出到P1.2</td></tr><tr><td>ANL</td><td>CMPCR2,</td><td colspan="2">#NOT DISFLT;不禁用(使能)比较器输出端的0.1uS虑波电路</td></tr><tr><td>ORL</td><td>CMPCR2,</td><td colspan="2">#DISFLT;禁用比较器输出端的0.1uS虑波电路</td></tr><tr><td>ANL</td><td>CMPCR2,</td><td colspan="2">#NOT LCDTY;比较器结果不去抖动,直接输出</td></tr><tr><td>ORL</td><td>CMPCR2,</td><td colspan="2">#(DISFLT AND 0x10);比较器结果在经过16个时钟后再输出</td></tr><tr><td>ORL</td><td>CMPCR1,</td><td colspan="2">#CMPEN;使能比较器</td></tr><tr><td>WAIT:</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>A,</td><td colspan="2">CMPCR1;查询比较完成标志</td></tr><tr><td>ANL</td><td>A,</td><td colspan="2">#CMPIF</td></tr><tr><td>JZ</td><td>WAIT</td><td></td><td></td></tr><tr><td>ANL</td><td>CMPCR1,</td><td colspan="2">#NOT CMPIF;清除完成标志</td></tr><tr><td>MOV</td><td>A,</td><td colspan="2">CMPCR1</td></tr><tr><td>MOV</td><td>C,</td><td colspan="2">ACC.0;将比较器结果CMPRES输出到测试口显示</td></tr><tr><td>MOV</td><td>LED,</td><td colspan="2">C</td></tr><tr><td>SJMP</td><td>$</td><td></td><td></td></tr><tr><td>END</td><td></td><td></td><td></td></tr></table>

# 12.3 比较器作外部掉电检测的参考电路

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ed215e930f9d95c82d61ed6be3c2724ed977b554a87f15a739a2392a3a772cb8.jpg)


上图中�， �R1和R2对稳压块7805的�前端电压进行�分压��压后的电压作为P5.5/CMP+的外部输入与内部BandGap参考 (1.27V附近)进行比较。

一般当��交流 220V时，稳压块7805前端的直流电压�11V，但 ��电压 160V时，稳压块7805前端的直流电压�8.5V。当稳压 7805前端的直流电压�����低于 8.5V时��，该前端输入的直流电压被 �R1和R2分压 CMP+端(比较器正极输入端)，CMP $^ +$ 端输入电压�低于内部BandGap参考 (1.27V附近)，此时可产生比较器中断，这样在掉电检测时就有充足的时间将数据保存到EEPROM中。 7805前端的直流电压高于8.5V时���，该前 �电压被 �R1和R2分压 CMP+端(比较器正极输入端)，CMP+端输入电压 � BandGap参考 (1.27V附近)，此时CPU可继续正常工作

内部BandGap参考电压� 1.27V附近���，具体 数值�要通过读�取内部BandGap电压在内部RAM区或ROM区所占用的地址的值获得。对于具 有128字节RAM空间的单片机（如STC15F104W系列单片机），其 BandGap参考电压� 06FH-070H，在ROM区占用的地址为程序空间 �8字节和第9字节（如STC15F104W型号单片机具有4K程序空间，则其BandGap参考电压� 0FF7H-0FF8H），用户只需通过读取RAM区06FH-070H地址的值或 ROM区0FF7H-0FF8H地址的值即可获得STC15F104W型号单片机的 BandGap参考电压�(毫伏,高字节在前)。对于具 有256及其以上字节RAM空间的单片机（如STC15F2K60S2系列单片机），其 BandGap参考电压� 0EFH-0F0H，在ROM区占用的地址为程序空间 �8字节和第9字节（如STC15F2K60S2型号单片机具有60K程序空间，则其内部BandGap参考电压� EFF7H-EFF8H），用户只需通过读取RAM区0EFH-0F0H地址的值或 ROM区EFF7H-EFF8H地址的值即可获得STC15F2K60S2型号单片机的BandGap参考电压�(毫伏,高字节在前)。

# 12.4 STC15W系列比较器作ADC的程序举例(C语言)

/*-- -*/ 

/* --- STC MCU Limited - -*/ 

/* --- STC15W4K60S4 系列 比较器作ADC的程序举例---- -*/

/* --- 研发顾问QQ：800003751-- --*/

/* --- Fax: 86-755-82905966 - -*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/*- -*/ 

//本示例在Keil开发环境下请选择Intel的8052芯片型号进行编译

//假定测试芯片的工作频率为22.1184MHz

//使用MCU自带的比较器进行ADC转换, 并经过模拟串口输出结果.

/**************************** 

使用比较器做ADC, 原理图如下.

做ADC的原理是基于电荷平衡的计数式ADC.

电压从Vin输入, 通过 $1 0 0 \mathrm { K } { + } 1 0 4$ 滤波, 进入比较器的P5.5正输入端, 经过比较器的比较, 将结果输出到P1.5再通过 $1 0 0 \mathrm { K } { + } 1 0 4$ 滤波后送比较器P5.4负输入端,跟输入电压平衡.

设置两个变量: 计数周期(量程)adc_duty 和比较结果高电平的计数值 adc, adc严格比例于输入电压.

ADC的基准就是P1.5的高电平. 如果高电平准确,比较器的放大倍数足够大,则ADC结果会很准确.

当比较结果为高电平,则P1.5输出1, 并且adc+1.

当比较结果为低电平,则P1.5输出0.

每一次比较都判断计数周期是否完成,完成则adc里的值就是ADC结果.

电荷平衡计数式ADC的性能类似数字万用表用的双积分ADC, 当计数周期为20ms的倍数时,具有很强的抗工频干扰能力,很好的线性和精度.

原理可以参考ADD3501(3 1/2位数字万用表)或ADD3701(3 3/4位数字万用表), 也可以参考AD7740 VFC电路.

例: 比较一次的时间间隔为10us, 量程为10000, 则做1次ADC的时间为100ms. 比较器的响应时间越短, 则完成ADC就越快.

由于要求每次比较时间间隔都要相等,所以用C编程最好在定时器中断里进行, 定时器设置为自动重装, 高优先级中断, 其它中断均低优先级.

用汇编的话, 保证比较输出电平处理的时间要相等.

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/79e49d75530ef5a4852c60fc30a280ac190a345de07208ac03d3c810d82493cd.jpg)


```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

#include "reg51.h" 

#include "intrins.h" 

typedef unsigned char u8; 

typedef unsigned int 

typedef unsigned long u32; 

#define MAIN_Fosc 22118400L //定义主时钟

sfr P1M1 一 0x91; //P1M1.n,P1M0.n = 00--->Standard, 01--->push-pull,实际上1T的都一样

sfr P1M0 = 

sfr AUXR $=$ 0x8E; 

sfr CMPCR1 = 0xE6; //比较器控制寄存器1

#define CMPEN 0x80 //CMPCR1.7 : 比较器模块使能位

#define CMPIF 0x40 //CMPCR1.6 : 比较器中断标志位

#define PIE 0x20 //CMPCR1.5 : 比较器上升沿中断使能位

#define NIE 0x10 //CMPCR1.4 : 比较器下降沿中断使能位

#define PIS 0x08 //CMPCR1.3 : 比较器正极选择位

#define NIS 0x04 //CMPCR1.2 : 比较器负极选择位

#define CMPOE 0x02 //CMPCR1.1 : 比较结果输出控制位

#define CMPRES 0x01 //CMPCR1.0 : 比较器比较结果标志位

sfr CMPCR2 = 0xE7; //比较器控制寄存器2

#define INVCMPO 0x80 //CMPCR2.7 : 比较结果反向输出控制位

#define DISFLT 0x40 //CMPCR2.6 : 比较器输出端0.1us虑波控制位

#define LCDTY 0x3F //CMPCR2.[5:0] : 比较器输出的区抖时间控制

sbit LED = P1^1; //测试脚

#define ADC_SCALE 50000 //ADC满量程, 根据需要设置

sbit P_ADC $=$ P1^5; //P1.2 比较器输出端

unsigned int adc; //ADC中间值, 用户层不可见

```c
unsigned int adc_duty; //ADC计数周期,用户层不可见  
unsigned int adc_value; //ADC值，用户层使用  
bit adc.ok; //ADC结束标志，为1则adc_value的值可用. //此标志给用户层查询，并且清0  
sbit P_TXD = P3^1; //定义模拟串口发送端，可以是任意IO  
void TxSend(u8 dat);  
void PrintString(unsigned char code *puts);  
void main()  
{u8 i;  
u8 tmp[5];  
CMPCR1 = 0; //初始化比较器控制寄存器1  
CMPCR2 = 0; //初始化比较器控制寄存器2  
CMPCR1 &= ~PIS; //选择外部管脚P5.5（CMP+）为比较器的正极输入源  
// CMPCR1 |= PIS; //选择ADCIS[2:0]所选的ADCIN为比较器的正极输入源  
// CMPCR1 &= ~NIS; //选择内部BandGap电压BGV为比较器的负极输入源  
CMPCR1 |= NIS; //选择外部管脚P5.4（CMP-）为比较器的负极输入源  
CMPCR1 &= ~CMPOE; //禁用比较器的比较结果输出  
CMPCR1 |= CMPOE; //使能比较器的比较结果输出到P1.2  
CMPCR2 &= ~INVCMPO; //比较器的比较结果正常输出到P1.2  
CMPCR2 |= INVCMPO; //比较器的比较结果取反后输出到P1.2  
CMPCR2 &= ~DISFLT; //使能比较器输出端的0.1uS虑波电路  
CMPCR2 |= DISFLT; //禁用比较器输出端的0.1uS虑波电路  
CMPCR2 &= ~LCDTY; //比较器结果不去抖动，直接输出  
CMPCR2 |= (DISFLT & 0x10); //比较器结果在经过16个时钟后再输出  
CMPCR1 |= CMPEN; //使能比较器  
while (!(CMPCR1 & CMPIF)); //查询比较完成标志  
CMPCR1 &= ~CMPIF; //清除完成标志  
LED = !!(CMPCR1 & CMPRES); //将比较器结果CMPRES输出到测试口显示  
ET0 = 1; //允许中断  
PT0 = 1; //高优先级中断  
TMOD &= ~0x03; //工作模式,0:16位自动重装,1:16位定时/计数, //2:8位自动重装,3:16位自动重装，不可屏蔽中断
```

AUXR $\equiv$ 0x80; //1TTH0=(u8)((-(MAIN_Fosc*10)/1000000) $\ggg$ 8); //10usTL0=(u8)(-(MAIN_Fosc*10)/1000000);P1M1& $\coloneqq$ \~(1<<5); //P1.5设置为push pull输出P1M0 $| =$ (1<<5);adc_duty $\equiv$ ADC_SCALE; //周期计数赋初值adc=0;TR0=1; //开始运行EA=1;PrintString("\r\n使用比较器做ADC例子\r\n");while(1){if adc.ok){adc.ok $= 0$ ; //清除ADC已结束标志PrintString("ADC=");//转十进制tmp[O]=adc_value/10000+0;tmp[1]=adc_value%10000/1000+0;tmp[2]=adc_value%1000/100+0;tmp[3]=adc_value%100/10+0;tmp[4]=adc_value%10+0;for(i=0;i<4;i++) //消无效o{if(tmp[i]！= 'O') break;tmp[i] $\equiv$ "；}for(i=0;i<5;i++) TxSend(tmp[i]); //发串口PrintString("\r\n");}）}  
/Timer0中断函数*********/  
void timer0_int(void) interrupt 1{if(CMPCR1 & CMPRES) //比较器输出高电平{P_ADC=1; //P_ADC输出高电平，给负输入端做反馈. $\mathrm{adc + + }$ ：//ADC计数 $+1$ 

else P_ADC $= 0$ //P_ADC输出低电平，给负输入端做反馈 if(--adc_duty $= = 0$ //ADC周期-1，到0则ADC结束 { adc_duty $\equiv$ ADC_SCALE; //周期计数赋初值 adc_value $\equiv$ adc; //保存ADC值 adc $= 0$ //清除ADC值 adc.ok $= 1$ //标志ADC已结束 }   
}   
//函数：void BitTime(void)   
//描述：位时间函数。   
//参数：none.   
//返回：none.   
//版本：VER1.0   
//日期：2013-4-1   
//备注：   
void BitTime(void) u16i; i $\equiv$ ((MAIN_Fosc/100)*104)/130000L-1; //根据主时钟来计算位时间 while(-i); STC   
//函数：void TxSend(uchar dat)   
//描述：模拟串口发送一个字节。9600，N，8，1   
//参数：dat:要发送的数据字节.   
//返回：none.   
//版本：VER1.0   
//日期：2013-4-1   
//备注：   
void TxSend(u8 dat) { u8 i; EA $= 0$ . P_TXD $= 0$ ; BitTime(); for(i=0;i<8;i++) { ifDAT&1) P_TXD $= 1$ else P_TXD $= 0$ 

dat $>> = 1$ ：   
BitTime();   
}   
P_TXD $= 1$ EA $= 1$ BitTime();   
BitTime();   
}   
//  
//函数：void PrintString(unsigned char code *puts)   
//描述：模拟串口发送一串字符串。9600，N，8，1   
//参数：*puts:要发送的字符指针.   
//返回：none.   
//版本：VER1.0   
//日期：2013-4-1   
//备注：   
//  
void PrintString(unsigned char code *puts)   
{ for(；\*puts $! = 0$ ； puts++) TxSend(\*puts);   
}

# 12.5 在比较器负端产生不同的电压由比较器正端进行比较

对于无ADC功能的单片机，如要进行电流检测或检测外部电池电压等， 可以利用CCP/PWM内部产生一个电压输入到比较器负端(CPM-)，然后由比较器的正端(CMP+)将其与外部电压进行比较，从而达到检测外部电压的目的。具体 实现的参考电路图如下：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b5f00868268d04b28d011add799932f5935064f86e83fba434db10e3fd0ffc85.jpg)


PWM功能可以利用T0/T1软件模拟10位/12位/16位PWM来实现，具体 实现方法请参照“用T0软硬结合模拟10位/16位PWM输出的程序”这一节；还可以利用CCP/PCA软硬结合实现9~16位PWM来实现，具体 实现方法参照“用CCP/PCA软硬结合实现9~16位PWM输出的程序”

# 12.6 现供货的STC15W201S系列A版本的比较器下降沿中断不响应将在STC15W201S系列B版本中修正

STC15W201S系列的A版本芯片正大批量现货供应中，当仅允许该版本的比较器下降沿中断时，该 比较器的下降沿中断暂不能使用。但是，该 版本的比较器下降沿中断不是绝对不能使用，用户可以通过以下两种办法解决这一问题：一、STC15W201S系列A版本的比较器上升沿中断是可正常使用的，且当用户将其比较器上升沿中断和下降沿中断都允许后，该 比较器上升沿中断和下降沿中断都可以正常使用。由于比较器比较结果标志位CMPRES(CMPCR1.0)是正确的，因此在比较器中断服务程序中查询比较器比较结果标志位CMPRES(CMPCR1.0)的值可判断单片机进入的是比较器上升沿中断还是比较器下降沿中断，如果CMPRES/CMPCR1.0=1，即CMP+的电平高于CMP-的电平(或内部BandGap参考电压的电平)，则表示单片机进入的是比较器上升沿中断；反之，如果CMPRES(CMPCR1.0)=0，即CMP+的电平低于 CMP-的电平(或内部BandGap参考电压的电平)，则表示单片机进入的是比较器下降沿中断，此时比较器下降沿中断是可正常使用的，这是解决办法之一；二、STC15W201S系列A版本的比较器比较结果标志位(CMPRES)是正确的，因此用户还可用软件查询方式解决该这一问题。

对于上述问题，敬请广大客户留意！对于给各位客户带来的不便，我们深表歉意，请各位客户谅解！我们将在STC15W201S系列的下一版本，即STC15W201S系列B版本中修正这一BUG。

# 第13章 使用STC15系列单片机的ADC做电容感应触摸按键

按键是电路最常用的零件之一，是 人机界面重要的输入方式，我们最熟悉的是机械式按键，但是机械按键有一个缺点（特别是便宜的按键），触点有寿命，很容易出现接触不良而失效。而非接触的按键则没有机械触点，寿命常，使用方便。

非接触的按键有多种方案，而电容感应按键则是低 成本的方案，多年前一般是使用专门的IC来实现，随着MCU功能的加强，以及广大用户的实践经验，直接使用MCU来做电容感应按键的技术已经成熟，其中最典型最可靠的是使用ADC做的方案。

本文档详述使用STC带ADC的系列MCU做的方案，可以使用任何带ADC功能的MCU来实现。

下面前3个图是用得最多的方式，原理都一样，本文使用第2个图。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/675f08119e7c675c1a2478ae240ec82c798e07d430461ea31b3bcda06084c957.jpg)



图1


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c532fc6ef1b24c86392a1c0b4dfa9e726b21452fe08e1e6ab3d76c2d20b88aae.jpg)



图2


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d04cfefd3dec427d39548e12bd1e5337e0b41c1e1b4d3052b233e28ea10d3e87.jpg)



Key_n


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/8b3af5c8e89296fa05aa88ea05ea06eb59c65e281d5623b33d60dfa15aca20e2.jpg)



图4 加了感应弹簧



图3



电容感应按键取样电路


一般实际应用时，都使用图4所示的感应弹簧来加大手指按下的面积。感应弹簧等效一块对地的金属板，对地有一个电容CP，而手指按下后，则再并联一个对地的电容CF，如下图所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/07cc9d12fe0a4eaf6120881c19518a611d717e5c75133bb10b6a36c465220dac.jpg)


下面为电路图的说明，CP为金属板和分布电容，CF为手指电容，并联在一起与C1对输入的300KHZ方波进行分压，经过D1整流，R2、C2滤波后送ADC，当手指压上去后，送去ADC的电压降低，程序就可以检测出按键动作。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/f1304cc10627c79bf280a61c33a427d8d2e8ec5103b15314e622b25dbc4ef2fd.jpg)


具

# 1、C语言程序

/*- -*/ 

/* --- STC MCU Limited - -*/ 

/* --- STC15W4K60S4 系列 ADC做电容触摸按键程序举例-- -*

/* --- Mobile: (86)13922805190 -*/ 

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 * 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/*- -*/ 

/************* 功能说明 **************

测试使用STC15W408AS的ADC做的电容感应触摸键.

假定测试芯片的工作频率为24MHz

****************************************** 

#include <reg51.h> 

#include <intrins.h> 

#define MAIN_Fosc 24000000UL //定义主时钟

typedef unsigned char u8; 

typedef unsigned int u16; 

typedef unsigned long u32; 

#define Timer0_Reload (65536UL -(MAIN_Fosc / 600000)) //Timer 0 重装值，对应300KHZ

sfr P1ASF $= 0 \mathrm { x } 9 \mathrm { D }$ ; //只写，模拟输入选择

sfr ADC_CONTR = 0xBC; //带AD系列

sfr ADC_RES $= 0 \mathrm { x B D }$ ; //带AD系列

sfr ADC_RESL = 0xBE; //带AD系列

sfr AUXR $= 0 \mathrm { x } 8 \mathrm { E }$ 

sfr AUXR2 $= 0 \mathrm { x } 8 \mathrm { F }$ 

/************* 本地常量声明 **************/

#define TOUCH_CHANNEL 8 //ADC通道数

#define ADC_90T $( 3 < < 5 )$ ) //ADC时间 90T

#define ADC_180T $2 { < } { < } 5 )$ ) //ADC时间 180T

#define ADC_360T $1 { < } { < } 5 )$ ) //ADC时间 360T

#define ADC_540T0 //ADC时间 540T

#define ADC_FLAG $1 { < } { < } 4$ ) //软件清0

#define ADC_START ( $1 { < } { < } 3$ ) //自动清0

/************* 本地变量声明 ***************

sbit $\mathrm { P } \bot \mathrm { E D } 7 = \mathrm { P } 2 \AA 7$ ; 

sbit P_LED6 = P2^6; 

```txt
sbit P_LED5 = P2^5;  
sbit P_LED4 = P2^4;  
sbit P_LED3 = P2^3;  
sbit P_LED2 = P2^2;  
sbit P_LED1 = P2^1;  
sbit P_LED0 = P2^0; 
```

```txt
u16 data adc[TOUCH_CHANNEL]; //当前ADC值  
u16 data adc prevail[TOUCH_CHANNEL]; //上一个ADC值  
u16 data TouchZero[TOUCH_CHANNEL]; //0点ADC值  
u8 data TouchZeroCnt[TOUCH_CHANNEL]; //0点自动跟踪计数  
u8 cnt_250ms;
```

```c
本地函数声明  
void delay_ms(u8 ms);  
void ADC_init(void);  
u16 Get_ADC10bitResult(u8 channel);  
void AutoZero(void);  
u8 check adc(u8 index);  
void ShowLED(void);
```


/******************** 主函数 **************************/


void main(void)  
{u8 i;delay_ms(50); $\mathrm{ET0} = 0$ //初始化Timer0输出一个300KHZ时钟TR0=0;AUXR|=0x80; //Timer0 set as 1T modeAUXR2|=0x01; //允许输出时钟TMOD $= 0$ //Timer0 set as Timer,16 bits Auto Reload.THO=(u8)(Timer0_Reload>>8);TL0=(u8)Timer0_Reload;TR0=1;ADC_init();//ADC初始化delay_ms(50);//延时50msfor(i=0;i<TOUCH_CHANNEL;i++)//初始化0点和上一个值和0点自动跟踪计数{adc prevail[i] $= 1023$ TouchZero[i] $= 1023$ 

```c
TouchZeroCnt[i] = 0;  
}  
cnt_250ms = 0;  
while (1)  
{ delay_ms(50); //每隔50ms处理一次按键 ShowLED(); if(++cnt_250ms >= 5) { cnt_250ms = 0; AutoZero(); //每隔250ms处理一次0点自动跟踪 }  
}  
//**********  
//函数:void delay_ms(unsigned char ms) //描述:延时函数。 //参数:ms,要延时的ms数,这里只支持1~255ms.自动适应主时钟. //返回:none. //版本:VER1.0 //日期:2013-4-1 //备注:  
void delay_ms(u8 ms) { unsigned int i; do { i = MAIN_Fosc / 13000; while(--i); }while(--ms);  
}  
//********** ADC初始化函数**********/  
void ADC_init(void)  
{ P1ASF = 0xff; //8路ADC ADC_CONTR = 0x80; //允许ADC }
```

// 函数: u16 Get_ADC10bitResult(u8 channel)

// 描述: 查询法读一次ADC结果.

// 参数: channel: 选择要转换的ADC.

// 返回: 10位ADC结果.

// 版本: V1.0, 2012-10-22

```c
u16 Get_ADC10bitResult(u8 channel) //channel = 0~7  
{ ADC_RES = 0; ADC_RESL = 0; ADC_CONTR = 0x80 | ADC_90T | ADC_START | channel; //触发ADC _nop(); _nop(); _nop(); _nop(); _nop(); while((ADC_CONTR & ADC_FLAG) == 0); //等待ADC转换结束 ADC_CONTR = 0x80; return((u16)ADC_RES << 2) | ((u16)ADC_RESL & 3)); //返回ADC结果
```

/********************* 自动0点跟踪函数 *************************/

```javascript
void AutoZero(void) //250ms调用一次这是使用相邻2个采样的差的绝对值之和来检测。  
{u8 i;u16 j,k;for(i=0;i<TOUCH_CHANNEL;i++) //处理8个通道j=adc[i];k=j-adc prevail[i];//减前一个读数F0=0; //按下if(k&0x8000) F0=1, k=0-k; //释放 求出两次采样的差值if(k>=20) //变化比较大{TouchZeroCnt[i]=0; //如果变化比较大，则清0计数器if(F0) TouchZero[i]=j; //如果是释放，并且变化比较大，则直接替代}else //变化比较小，则蠕动，自动0点跟踪{if(++TouchZeroCnt[i] >= 20) //连续检测到小变化20次/4=5秒.{//继续检测到小变化20次/4=5秒.}TouchZeroCnt[i]=0;TouchZero[i]=adc prevail[i]; //变化缓慢的值作为0点
```

} } adc prevail $\mathbf{\dot{[i]}} = \mathbf{j};$ //保存这一次的采样值 1


/********************* 获取触摸信息函数 50ms调用1次 *************************/


```c
u8 check adc(u8 index) //判断键按下或释放,有回差控制  
{ u16 delta; adc[index] = 1023 - Get_ADC10bitResult(index); //获取ADC值,转成按下键,ADC值增加 if(adc[index] < TouchZero[index]) return 0; //比0点还小的值,则认为是键释放 delta = adc[index] - TouchZero[index]; if(delay >= 40) return 1; //键按下 if(delay <= 20) return 0; //键释放 return 2; //保持原状态
```


/********************* 键处理 50ms调用1次 *************************/


```txt
void ShowLED(void)  
{ u8 i; i = check_adc(0); if(i == 0) P_LED0 = 1; //指示灯灭 if(i == 1) P_LED0 = 0; //指示灯亮 i = check_adc(1); if(i == 0) P_LED1 = 1; //指示灯灭 if(i == 1) P_LED1 = 0; //指示灯亮 i = check_adc(2); if(i == 0) P_LED2 = 1; //指示灯灭 if(i == 1) P_LED2 = 0; //指示灯亮 i = check_adc(3); if(i == 0) P_LED3 = 1; //指示灯灭 if(i == 1) P_LED3 = 0; //指示灯亮 i = check_adc(4); if(i == 0) P_LED4 = 1; //指示灯灭 if(i == 1) P_LED4 = 0; //指示灯亮
```

$\mathrm{i} =$ check adc(5); if(i $\equiv$ 0) P_LED5 $= 1$ //指示灯灭 if(i $\equiv$ 1) P_LED5 $= 0$ //指示灯亮 $\mathrm{i} =$ check adc(6); if(i $\equiv$ 0) P_LED6 $= 1$ //指示灯灭 if(i $\equiv$ 1) P_LED6 $= 0$ //指示灯亮 $\mathrm{i} =$ check adc(7); if(i $\equiv$ 0) P_LED7 $= 1$ //指示灯灭 if(i $\equiv$ 1) P_LED7 $= 0$ //指示灯亮

# 2、汇编程序

/* -*/ 

/* --- STC MCU Limited ---*/ 

/* --- STC15W4K60S4 系列 ADC做电容触摸按键程序举例- -*/

/* --- Mobile: (86)13922805190 - -*/ 

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/*_ * 

·/************* 功能说明 **************

;测试使用STC15W408AS的ADC做的电容感应触摸键.

;假定测试芯片的工作频率为24MHz

;******************************************/ 

;/****************************** 用户定义宏 ***********************************/

Fosc_KHZ EQU 24000 ;定义主时钟 KHZ

STACK_POIRTER EQU 0D0H ;堆栈开始地址

Timer0_Reload EQU (65536 - Fosc_KHZ/600) ;Timer 0 重装值， 对应300KHZ

******************************************************************* 

******************************************************************** 

P1ASF DATA 0x9D; //只写，模拟输入选择

ADC_CONTR DATA 0xBC; //带AD系列

ADC_RES DATA 0xBD; //带AD系列

ADC_RESL DATA 0xBE; //带AD系列

AUXR DATA 0x8E; 

AUXR2 DATA 0x8F; 

本地变量声明 **************;

/************* 本地常量声明 **************

TOUCH_CHANNEL EQU 8 ;ADC通道数

<table><tr><td>ADC_90T</td><td>EQU (3 SHL 5)</td><td>;ADC时间90T</td></tr><tr><td>ADC_180T</td><td>EQU (2 SHL 5)</td><td>;ADC时间180T</td></tr><tr><td>ADC_360T</td><td>EQU (1 SHL 5)</td><td>;ADC时间360T</td></tr><tr><td>ADC_540T</td><td>EQU 0</td><td>;ADC时间540T</td></tr><tr><td>ADC_FLAG</td><td>EQU (1 SHL 4)</td><td>;软件清0</td></tr><tr><td>ADC_START</td><td>EQU (1 SHL 3)</td><td>;自动清0</td></tr></table>

/************* 本地变量声明 **************/

<table><tr><td>P_LED7 BIT</td><td>P2.7;</td></tr><tr><td>P_LED6 BIT</td><td>P2.6;</td></tr><tr><td>P_LED5 BIT</td><td>P2.5;</td></tr><tr><td>P_LED4 BIT</td><td>P2.4;</td></tr><tr><td>P_LED3 BIT</td><td>P2.3;</td></tr><tr><td>P_LED2 BIT</td><td>P2.2;</td></tr><tr><td>P_LED1 BIT</td><td>P2.1;</td></tr><tr><td>P_LED0 BIT</td><td>P2.0;</td></tr></table>

<table><tr><td>adc</td><td>EQU</td><td>30H</td><td>;</td><td>当前ADC值</td><td>30H~3FH, 两字节一个值</td></tr><tr><td>adc prevail</td><td>EQU</td><td>40H</td><td>;</td><td>上一个ADC值</td><td>40H~4FH, 两字节一个值</td></tr><tr><td>TouchZero</td><td>EQU</td><td>50H</td><td>;</td><td>0点ADC值</td><td>50H~5FH, 两字节一个值</td></tr><tr><td>TouchZeroCnt</td><td>EQU</td><td>60H</td><td>;</td><td>0点自动跟踪计数</td><td>60H~67H</td></tr></table>

cnt_250ms DATA 68H 

******************************************************************** 

******************************************************************** 

<table><tr><td>ORG</td><td>00H</td><td>;reset</td></tr><tr><td>LJMP</td><td>F(Main</td><td></td></tr></table>

<table><tr><td>ORG</td><td>03H</td><td>;0 INT0 interrupt</td></tr><tr><td>RETI</td><td></td><td></td></tr><tr><td>LJMP</td><td>F_INT0_Interrupt</td><td></td></tr></table>

<table><tr><td>ORG</td><td>0BH</td><td>;1 Timer0 interrupt</td></tr><tr><td>LJMP</td><td>F_Timer0_Interrupt</td><td></td></tr></table>

<table><tr><td>ORG</td><td>13H</td><td>;2 INT1 interrupt</td></tr><tr><td>LJMP</td><td>F_INT1_Interrupt</td><td></td></tr></table>

<table><tr><td>ORG</td><td>1BH</td><td>;3 Timer1 interrupt</td></tr><tr><td>LJMP</td><td>F_Timer1_Interrupt</td><td></td></tr></table>

<table><tr><td>ORG</td><td>23H</td><td>;4 UART1 interrupt</td></tr><tr><td>LJMP</td><td>F_UART1Interrupt</td><td></td></tr></table>

ORG 2BH 

;5 ADC and SPI interrupt 

LJMP F_ADC_Interrupt 

ORG 33H 

;6 Low Voltage Detect interrupt 

LJMP F_LVD_Interrupt 

ORG 3BH 

;7 PCA interrupt 

LJMP F_PCA_Interrupt 

ORG 43H 

;8 UART2 interrupt 

LJMP F_UART2_Interrupt 

ORG 4BH 

;9 SPI interrupt 

LJMP F_SPI_Interrupt 

ORG 53H 

;10 INT2 interrupt 

LJMP F_INT2_Interrupt 

ORG 5BH 

;11 INT3 interrupt 

LJMP F_INT3_Interrupt 

ORG 63H 

;12 Timer2 interrupt 

LJMP F_Timer2_Interrupt 

ORG 83H 

;16 INT4 interrupt 

LJMP F_INT4_Interrupt 

;******************** 主程序 **************************/

F_Main: 

MOV R0, #1 

L_ClearRamLoop: 

;清除RAM

MOV @R0, #0 

INC R0 

MOV A, R0 

CJNE A, #0FFH, L_ClearRamLoop 

MOV SP, #STACK_POIRTER 

MOV PSW, #0 

USING 0 

;选择第0组R0~R7

用户初始化程序

MOV R7, #50 

LCALL F_delay_ms 

CLR ET0 

; 初始化Timer0输出一个300KHZ时钟

CLR TR0 

ORL AUXR, #080H 

; Timer0 set as 1T mode 

ORL AUXR2, #01H 

; 允许输出时钟

MOV TMOD, #0 

; Timer0 set as Timer, 16 bits Auto Reload. 

MOV TH0, #HIGH Timer0_Reload 

MOV TL0, #LOW Timer0_Reload 

SETB TR0 

LCALL F_ADC_init 

MOV R7, #50 

LCALL F_delay_ms 

MOV R0, #adc_prev 

; 初始化上一个ADC值

L_Init_Loop1: 

MOV @R0, #03H 

INC R0 

MOV @R0, #0FFH 

INC R0 

MOV A, R0 

CJNE A, #(adc_prev + TOUCH_CHANNEL * 2), L_Init_Loop1 

MOV R0, #TouchZero 

; 初始化0点ADC值

L_Init_Loop2: 

MOV @R0, #03H 

INC R0 

MOV @R0, #0FFH 

INC R0 

MOV A, R0 

CJNE A, #(TouchZero $^ +$ TOUCH_CHANNEL * 2), L_Init_Loop2 

MOV R0, #TouchZeroCnt; 初始化自动跟踪计数值

L_Init_Loop3: 

MOV @R0, #0 

INC R0 

MOV A, R0 

CJNE A, #(TouchZeroCnt $^ +$ TOUCH_CHANNEL), L_Init_Loop3 

MOV cnt_250ms, #5 

= 主循环

L_MainLoop: 

MOV R7, #50 ;延时50ms

LCALL F_delay_ms 

LCALL F_ShowLED ; 处理一次触摸键值

DJNZ cnt_250ms, L_MainLoop 

MOV cnt_250ms, #5 ;250ms处理一次0点自动跟踪

LCALL F_AutoZero ;自动跟踪零点

SJMP L_MainLoop 

= 主程序结束

; /************* ADC初始化函数 *****************/

F_ADC_init: 

MOV P1ASF,#0FFH ;8路ADC

MOV ADC_CONTR,#080H ;允许ADC

RET 

; END OF ADC_init 

; //= 

; // 函数: F_Get_ADC10bitResult

; // 描述: 查询法读一次ADC结果.

; // 参数: R7: 选择要转换的ADC.

; // 返回: $\mathrm { R 6 } \mathrm { R 7 } = = 1 0$ 位ADC结果.

; // 版本: V1.0, 2014-3-25

; //= 

F_Get_ADC10bitResult: 

USING 0 ;选择第0组R0~R7

MOV ADC_RES, #0 

MOV ADC_RESL,#0 

MOV A, R7 

ORL A, #0E8H ;(0x80 OR ADC_90T OR ADC_START) ;触发ADC

MOV ADC_CONTR, A 

NOP 

NOP 

NOP 

NOP 

L_10bitADC_Loop1: 

MOV A, ADC_CONTR 

JNB ACC.4, L_10bitADC_Loop1 ;等待ADC转换结束

MOV ADC_CONTR,#080H //清除标志

MOV A,ADC_RES 

MOV B,#04H 

MUL AB 

MOV R7,A 

MOV R6,B 

MOV A, ADC_RESL 

ANL A, #03H 

ORL A,R7 

MOV R7,A 

RET 

; END OF _Get_ADC10bitResult 

; /********************* 自动0点跟踪函数 *************************/

F_AutoZero: ;250ms调用一次这是使用相邻2个采样的差的绝对值之和来检测。

USING 0 ;选择第0组R0~R7

CLR A 

MOV R5,A 

L_AutoZero_Loop: 

$$
; [ R 6 \quad R 7 ] = a d c [ i ], (j = a d c [ i ])
$$

MOV A,R5 

ADD A,ACC 

ADD A,#LOW (adc) 

MOV R0,A 

MOV A,@R0 

MOV R6,A 

INC R0 

MOV A,@R0 

MOV R7,A 

; 计算差值 $[ { \bf R } 2 { \bf R } 3 ] =$ $=$ adc[i] - adc_prev[i], $\mathbf { k } = \mathbf { j }$ - adc_prev[i];) //减前一个读数

MOV A,R5 

ADD A,ACC 

ADD A,#LOW (adc_prev+01H) 

MOV R0,A 

CLR C 

MOV A,R7 

SUBB A,@R0 

MOV R3,A 

MOV A,R6 

DEC R0 

SUBB A,@R0 

MOV R2,A 

; 求差值的绝对值 [R2 R3], if(k & 0x8000) F0 = 1, k = 0 - k; //释放 求出两次采样的差值

CLR F0 ;按下

JNB ACC.7, L_AutoZero_1 

SETB F0 

CLR C 

CLR A 

SUBB A, R3 

MOV R3, A 

MOV A,R3 

CLR A 

SUBB A, R2 

MOV R2, A 

L_AutoZero_1: 

CLR C ;计算 [R2 R3] - #20, if(k >= 20) //变化比较大

MOV A,R3 

SUBB A,#20 

MOV A,R2 

SUBB A,#00H 

JC L_AutoZero_2 ;[R2 R3] , 20, 转

MOV A,#LOW (TouchZeroCnt) ;如果变化比较大，则清0计数器 TouchZeroCnt[i] ${ } = 0$ 

ADD A,R5 

MOV R0,A 

MOV @R0, #0 

if(F0) TouchZero[i] $=$ j; //如果是释放，并且变化比较大，则直接替代

JNB F0,L_AutoZero_3 

MOV A,R5 

ADD A,ACC 

ADD A,#LOW (TouchZero) 

MOV R0,A 

MOV @R0,AR6 

INC R0 

MOV @R0,AR7 

SJMP L_AutoZero_3 

L_AutoZero_2: ;变化比较小，则蠕动，自动0点跟踪

if $^ { + + }$ TouchZeroCnt[i] $> = 2 0$ ) //连续检测到小变化20次 $/ 4 = 5$ 秒.

```asm
MOV A,#LOW (TouchZeroCnt)  
ADD A,R5  
MOV R0,A  
INC @R0  
MOV A,@R0  
CLR C  
SUBB A,#20  
JC L_AutoZero_3 ;if(TouchZeroCnt[i] < 20), 转  
MOV @R0,#0 ;TouchZeroCnt[i] = 0;  
MOV A,R5 ;TouchZero[i] = adc prevail; //变化缓慢的值作为0点  
ADD A,ACC  
ADD A,#LOW (adc prevail)  
MOV R0,A  
MOV A,@R0  
MOV R2,A  
INC R0  
MOV A,@R0  
MOV R3,A  
MOV A,R5  
ADD A,ACC  
ADD A,#LOW (TouchZero)  
MOV R0,A  
MOV @R0,AR2  
INC R0  
MOV @R0,AR3  
L_AutoZero_3:  
    ; 保存采样值 adc prevail[i] = j;  
MOV A,R5  
ADD A,ACC  
ADD A,#LOW (adc prevail)  
MOV R0,A  
MOV @R0,AR6  
INC R0  
MOV @R0,AR7  
INC R5  
MOV A,R5  
XRL A,#08H  
JZ $+5H  
LJMP L_AutoZero_Loop  
RET
```

; END OF AutoZero 

; /********************* 获取触摸信息函数 50ms调用1次 *************************/

F_check_adc: ;判断键按下或释放,有回差控制

USING 0 ;选择第0组R0~R7

MOV R4, AR7 

; adc[index] $= 1 0 2 3$ - Get_ADC10bitResult(index); //获取ADC值, 转成按下键, ADC值增加

LCALL F_Get_ADC10bitResult ;返回的ADC值在 [R6 R7]

CLR C 

MOV A,#0FFH ;1023 - [R6 R7] 

SUBB A,R7 

MOV R7,A 

MOV A,#03H 

SUBB A,R6 

MOV R6,A 

MOV A,R4 ;保存 adc[index]

ADD A,ACC 

ADD A,#LOW (adc) 

MOV R0,A 

MOV @R0,AR6 

INC R0 

MOV @R0,AR7 

; if(adc[index] $<$ TouchZero[index]) return 0; //比0点还小的值，则认为是键释放

MOV A,R4 

ADD A,ACC 

ADD A,#LOW (TouchZero+01H) 

MOV R1,A 

MOV A,R4 

ADD A,ACC 

ADD A,#LOW (adc) 

MOV R0,A 

MOV A,@R0 

MOV R6,A 

INC R0 

MOV A,@R0 

CLR C 

SUBB A,@R1 ;计算 adc[index] - TouchZero[index]

MOV A,R6 

DEC R1 

SUBB A,@R1 

```asm
JNC L_check adc_1 ;if(adc[index] >= TouchZero[index]), 转  
MOV R7,#00H ;if(adc[index] < TouchZero[index]), 比0点还小的值，; 则认为是键释放, 返回0  
RET  
L_check adc_1: ;计算差值 [R6 R7] = delta = adc(index) - TouchZero[index];  
MOV A,R4  
ADD A,ACC  
ADD A,#LOW (TouchZero+01H)  
MOV R1,A  
MOV A,R4  
ADD A,ACC  
ADD A,#LOW (adc+01H)  
MOV R0,A  
CLR C  
MOV A,@R0  
SUBB A,@R1  
MOV R7,A  
DEC R0  
MOV A,@R0  
DEC R1  
SUBB A,@R1  
MOV R6,A  
CLRC Variable 'delta' assigned to Register 'R6/R7' ----  
CLR C  
MOV A,R7  
SUBB A,#40  
MOV A,R6  
SUBB A,#00H  
JC L_check adc_2 ;if(delta < 40), 转  
MOV R7,#1 ;if(delta >= 40) return 1; //键按下返回1  
RET  
L_check adc_2:  
SETB C  
MOV A,R7  
SUBB A,#20  
MOV A,R6  
SUBB A,#00H  
JNC L_check adc_3  
MOV R7,#0 ;if(delta <= 20) return 0; //键释放返回0  
RET
```

L_check_adc_3: 

MOV R7,#2 

;if((delta $> 2 0 $ ) && (delta $< 4 0 $ )) 

保持原状态 返回2

RET 

; END OF _check_adc 

/********************* 键处理 50ms调用1次 *************************/

F_ShowLED: 

USING 0 

;选择第0组R0~R7

MOV R7, #0 

LCALL F_check_adc 

MOV A,R7 

ANL A, #0FEH 

JNZ L_QuitCheck0 

MOV A, R7 

MOV C, ACC.0 

CPL C 

MOV P_LED0, C 

;if $( \mathrm { i } = = 0 ) ,$ ) 指示灯灭, if( $. = = 1 \AA$ ) 指示灯亮

L_QuitCheck0: 

MOV R7, #1 

LCALL F_check_adc 

MOV A,R7 

ANL A, #0FEH 

JNZ L_QuitCheck1 

MOV A, R7 

MOV C, ACC.0 

CPL C 

MOV P_LED1, C 

;if $( \mathrm { i } = = 0 ) ,$ ) 指示灯灭, $\operatorname { i f } ( \mathrm { i } = = 1 )$ ) 指示灯亮

L_QuitCheck1: 

MOV R7, #2 

LCALL F_check_adc 

MOV A,R7 

ANL A, #0FEH 

JNZ L_QuitCheck2 

MOV A, R7 

MOV C, ACC.0 

CPL C 

MOV P_LED2, C 

;if $( \mathrm { i } = = 0 )$ ) 指示灯灭, $\operatorname { i f } ( \mathrm { i } = = 1 )$ ) 指示灯亮

L_QuitCheck2: 

MOV R7, #3 

LCALL F_check_adc 

```txt
MOV A,R7  
ANL A, #0FEH  
JNZ L quitsCheck3  
MOV A, R7  
MOV C, ACC.0  
CPL C  
MOV P_LED3, C ;if(i == 0)指示灯灭, if(i == 1)指示灯亮  
L_QuitCheck3:  
MOV R7, #4  
LCALL F_check_adc  
MOV A,R7  
ANL A, #0FEH  
JNZ L quitsCheck4  
MOV A, R7  
MOV C, ACC.0  
CPL C  
MOV P_LED4, C ;if(i == 0)指示灯灭, if(i == 1)指示灯亮  
L_QuitCheck4:  
MOV R7, #5  
LCALL F_check_adc  
MOV A,R7  
ANL A, #0FEH  
JNZ L quitsCheck5  
MOV A, R7  
MOV C, ACC.0  
CPL C  
MOV P_LED5, C ;if(i == 0)指示灯灭, if(i == 1)指示灯亮  
L_QuitCheck5:  
MOV R7, #6  
LCALL F_check_adc  
MOV A,R7  
ANL A, #0FEH  
JNZ L quitsCheck6  
MOV A, R7  
MOV C, ACC.0  
CPL C  
MOV P_LED6, C ;if(i == 0)指示灯灭, if(i == 1)指示灯亮  
L_QuitCheck6:  
MOV R7, #7  
LCALL F_check_adc
```

MOV A,R7 

ANL A, #0FEH 

JNZ L_QuitCheck7 

MOV A, R7 

MOV C, ACC.0 

CPL C 

MOV P_LED7, C ;if $( \mathrm { i } = = 0 )$ ) 指示灯灭, $\mathrm { i f } ( \mathrm { i } = = 1 )$ ) 指示灯亮

```txt
L_QuitCheck7: 
```

RET 

```txt
; END OF ShowLED 
```

;//= 

;// 函数: F_delay_ms

;// 描述: 延时子程序。

;// 参数: R7: 延时ms数.

;// 返回: none.

;// 版本: VER1.0

;// 日期: 2013-4-1

;// 备注: 除了ACCC和PSW外, 所用到的通用寄存器都入栈

;//= 

```txt
F_delay_ms: 
```

PUSH AR3 

;入栈R3

PUSH AR4 

;入栈R4

```python
L_delay_ms_1: 
```

MOV R3, #HIGH (Fosc_KHZ / 13) 

MOV R4, #LOW (Fosc_KHZ / 13) 

```python
L_delay_ms_2: 
```

MOV A, R4 

;1T 

DEC R4 

;2T 

JNZ L_delay_ms_3 

;4T 

DEC R3 

```python
L_delay_ms_3: 
```

DEC A 

;1T 

ORL A, R3 

;1T 

JNZ L_delay_ms_2 

;4T 

DJNZ R7, L_delay_ms_1 

POP AR4 

;出栈R2

POP AR3 

;出栈R3

RET 

******************************************************************** 

;**************** 中断函数 ***************************************************

F_Timer0_Interrupt: RETI 

F_Timer1_Interrupt: RETI 

F_Timer2_Interrupt: RETI 

F_INT0_Interrupt: RETI 

F_INT1_Interrupt: RETI 

F_INT2_Interrupt: RETI 

F_INT3_Interrupt: RETI 

F_INT4_Interrupt: RETI 

F_UART1_Interrupt: RETI 

F_UART2_Interrupt: RETI 

F_ADC_Interrupt: RETI 

F_LVD_Interrupt: RETI 

F_PCA_Interrupt: RETI 

F_SPI_Interrupt: RETI END 

# 第14章 同步串行外围接口(SPI接口)

STC15系列单片机还提供另���一种高速串行�����通信接口� —— SPI接口。SPI是一种全双工、高速、同步的通信总线，有两种操作模式：主模式和从模式。在主模式中支持高达3 Mbps的速率(工作频率为12MHz时,如果CPU主频采用20MHz到36MHz,则可更高，从模式时速度无法太快，SYSclk/4以内较好),还具有传输完成标志和写冲突标志保护。

下表总结了STC15系列单片机内部集成了SPI功能的单片机型号：

<table><tr><td>特殊外围设备
单片机型号</td><td>8路10位高速
A/D转换器</td><td>CCP/PCA/PWM功能</td><td>1组高速同步串行口SPI</td></tr><tr><td>STC15W4K60S4系列</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td>STC15F2K60S2系列</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td>STC15W1K16S系列</td><td></td><td></td><td>✓</td></tr><tr><td>STC15W408S系列</td><td></td><td></td><td>✓</td></tr><tr><td>STC15W408AS系列</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td>STC15W201S系列</td><td></td><td></td><td></td></tr><tr><td>STC15F408AD系列</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td>STC15F101W系列</td><td></td><td></td><td></td></tr></table>

上表中 $\surd$ 表示对应的系列有相应的功能。

STC15W4K60S4系列、STC15F2K60S2系列、STC15W1K16S系列和STC15W408S系列单片机的SPI可以在3组不同管脚之间进行切换：

[SS/P1.2, MOSI/P1.3, MISO/P1.4, SCLK/P1.5]； 

[SS_2/P2.4, MOSI_2/P2.3, MISO_2/P2.2, SCLK_2/P2.1]； 

[SS_3/P5.4, MOSI_3/P4.0, MISO_3/P4.1, SCLK_3/P4.3]。 

注意：现STC15F2K60S2及STC15L2K60S2系列C版本的SPI工作于主模式时正常，但工作于从模式时有问题，建议不要使用该版本的SPI从模式。

STC15F408AD系列和STC15W408AS系列单片机的SPI可以在2组不同管脚之间进行切换：

[SS/P1.2, MOSI/P1.3, MISO/P1.4, SCLK/P1.5]； 

[SS_2/P2.4, MOSI_2/P2.3, MISO_2/P2.2, SCLK_2/P2.1]。 

注意：现STC15F408AD及STC15L408AD系列C版本的SPI工作于主模式时正常，但工作于从模式时有问题，建议不要使用该版本的SPI从模式。

STC15W201S系列和STC15F101W系列单片机没有SPI功能。

特别声明：以15F和15L开头且有SPI功能的芯片,只支持"SPI主机模式",不支持"SPI从机模式"；以15W开头且有SPI功能的芯片，SPI主/从机模式均支持

# 14.1 与SPI功能模块相关的特殊功能寄存器

STC15系列 1T 8051单片机SPI功能模块特殊功能寄存器 SPI Management SFRs

<table><tr><td rowspan="2">符号</td><td rowspan="2">描述</td><td rowspan="2">地址</td><td colspan="9">位地址及其符号</td><td rowspan="2">复位值</td></tr><tr><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td colspan="2">B0</td></tr><tr><td>SPCTL</td><td>SPI Control Register</td><td>CEH</td><td>SSIG</td><td>SPEN</td><td>DORD</td><td>MSTR</td><td>CPOL</td><td>CPHA</td><td>SPR1</td><td>SPRO</td><td>0000,0100</td><td></td></tr><tr><td>SPSTAT</td><td>SPI Status Register</td><td>CDH</td><td>SPIF</td><td>WCOL</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>00xx,xxxx</td><td></td></tr><tr><td>SPDAT</td><td>SPI Data Register</td><td>CFH</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0000,0000</td><td></td></tr><tr><td>IE</td><td>Interrupt Enable</td><td>A8H</td><td>EA</td><td>ELVD</td><td>EADC</td><td>ES</td><td>ET1</td><td>EX1</td><td>ET0</td><td>EX0</td><td>0000,0000</td><td></td></tr><tr><td>IE2</td><td>Interrupt Enable 2</td><td>AFH</td><td>-</td><td>ET4</td><td>ET3</td><td>ES4</td><td>ES3</td><td>ET2</td><td>ESPI</td><td>ES2</td><td>x000,0000</td><td></td></tr><tr><td>IP2</td><td>Interrupt Priority</td><td>B5H</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>PSPI</td><td>PS2</td><td>xxxx,xx00</td><td></td></tr><tr><td>AUXR1 P_SW1</td><td>Auxiliary Register 1</td><td>A2H</td><td>S1_S1</td><td>S1_S0</td><td>CCP_S1</td><td>CCP_S0</td><td>SPI_S1</td><td>SPI_S0</td><td>-</td><td>DPS</td><td>0000,0000</td><td></td></tr></table>

# 1. SPI控制寄存器SPCTL

SPI控制寄存器的格式如下：

SPCTL : SPI控制寄存器

<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>SPCTL</td><td>CEH</td><td>name</td><td>SSIG</td><td>SPEN</td><td>DORD</td><td>MSTR</td><td>CPOL</td><td>CPHA</td><td>SPR1</td><td>SPRO</td></tr></table>

SSIG：SS引脚忽略控制位。

SSIG=1，MSTR（位4）确定器件为主机还是从机

SSIG=0，SS脚用于确定器件为主机还是从机.SS脚可作为I/O口使用(�SPI主从选择表

SPEN：SPI使能位。

SPEN=1，SPI使能；

SPEN=0，SPI被禁止，所有SPI引脚都作为I/O口使用。

DORD：设定SPI数据发�送和接�收的位�顺序

DORD $\lvert = 1$ ， � LSB(最低位)最先发送；

DORD $\scriptstyle  = 0$ ， � MSB(最高位)最先发送。

MSTR：主/从模式选择位 �SPI主从选择表）。

CPOL：SPI时钟极性

CPOL $_ { , = 1 }$ ，SCLK空闲时为高电平。SCLK的前时钟沿为下降沿而后沿为上升沿

CPOL ${ } _ { , = 0 }$ ，SCLK空闲时为低电平。SCLK的前时钟沿为上升沿而后沿为下降沿

CPHA：SPI时钟相位选择。

CPHA $_ { \cdot = 1 }$ ， � SCLK的前时钟沿驱动，并在后时钟沿采样

CPHA=0， � SS为低（ ${ \mathrm { S S I G } } { = } 0 $ ）时被驱动，在SCLK的后时钟沿被改变，并在前时钟沿被采样。（注： $\mathrm { S S I G } = 1$ $= 1$ 时的操作未定义）

SPR1、SPR0：SPI时钟速率选择控制位。SPI时钟选择如下表所列。


SPI时钟频率的选择


<table><tr><td>SPR1</td><td>SPRO</td><td>时钟(SCLK)</td></tr><tr><td>0</td><td>0</td><td>CPU_CLK/4</td></tr><tr><td>0</td><td>1</td><td>CPU_CLK/16</td></tr><tr><td>1</td><td>0</td><td>CPU_CLK/64</td></tr><tr><td>1</td><td>1</td><td>CPU_CLK/128</td></tr></table>

其中，CPU_CLK是CPU时钟。

# 2. SPI状态寄存器SPSTAT

SPI状态寄存器的格式如下：


SPSTAT: SPI状态寄存器


<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>SPSTAT</td><td>CDH</td><td>name</td><td>SPIF</td><td>WCOL</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td></tr></table>

SPIF：SPI传输完成标志。

当一次串行 传输完成时，SPIF置位 SPI中断被打开(即ESPI (IE2.1) 和EA(IE.7) 都置位)，则��产生 SPI处于主模式且SSIG $\scriptstyle 1 = 0$ 时，如果SS为输入并被驱动为低电平，SPIF也将置位 � �” SPIF标志通过软件向其写入 1"

WCOL：SPI写冲突标志。

在数据传输的过程中如果对SPI 数据寄存器SPDAT执行写操作，WCOL将置位。WCOL标志通过软件向其写入 1"

# 3. SPI数据寄存器SPDAT

SPI数据寄存器的格式如下：


SPDAT: SPI数据寄存器


<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>SPDAT</td><td>CFH</td><td>name</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr></table>

SPDAT.7 - SPDAT.0: 传输的数据位Bit7～Bit0

# 4.中断允许寄存器IE及IE2


IE : 中断允许寄存器 (可位寻址)


<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IE</td><td>A8H</td><td>name</td><td>EA</td><td>ELVD</td><td>EADC</td><td>ES</td><td>ET1</td><td>EX1</td><td>ET0</td><td>EX0</td></tr></table>

EA : CPU的中断开放标志

EA=1，CPU开放中断，

EA=0，CPU屏蔽所有的中断申请。

EA的作用是使中断允许形成多级控制。即各中断源首先受EA控制;其次还受各中断源自己的中断允许控制位控制。


IE2 : 中断允许寄存器2


<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IE2</td><td>AFH</td><td>name</td><td>-</td><td>ET4</td><td>ET3</td><td>ES4</td><td>ES3</td><td>ET2</td><td>ESPI</td><td>ES2</td></tr></table>

ESPI : SPI中断允许位

ESPI=1，允许SPI中断，

ESPI=0，禁止SPI中断。

# 5.中断优先级控制寄存器IP2


IP2 : 中断优先级控制寄存器2


<table><tr><td>SFR name</td><td>Address</td><td>bit</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td></tr><tr><td>IP2</td><td>B5H</td><td>name</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>PSPI</td><td>PS2</td></tr></table>

PSPI: SPI中断优先级控制位。

当PSPI=0时，SPI中断为最低优先级中断(优先级0)

当PSP $[ = 1$ 时，SPI中断为最高优先级中断(优先级1)

# 6. 控制SPI功能切换的寄存器AUXR1(P_SW1)

外围设备切换控制寄存器1的格式如下：

AUXR1/P_SW1 : 外围设备切换控制寄存器1 (不可位寻址)

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>B7</td><td>B6</td><td>B5</td><td>B4</td><td>B3</td><td>B2</td><td>B1</td><td>B0</td><td>Reset Value</td></tr><tr><td>AUXR1
P_SW1</td><td>A2H</td><td>Auxiliary
register 1</td><td>S1_S1</td><td>S1_S0</td><td>CCP_S1</td><td>CCP_S0</td><td>SPI_S1</td><td>SPI_S0</td><td>0</td><td>DPS</td><td>0000,0000</td></tr></table>

<table><tr><td colspan="3">SPI可在3个地方切换,由 SPI_S1 / SPI_S0 两个控制位来选择</td></tr><tr><td>SPI_S1</td><td>SPI_S0</td><td>SPI可在P1/P2/P4之间来回切换</td></tr><tr><td>0</td><td>0</td><td>SPI在[P1.2/SS,P1.3/MOSI,P1.4/MISO,P1.5/SCLK]</td></tr><tr><td>0</td><td>1</td><td>SPI在[P2.4/SS_2,P2.3/MOSI_2,P2.2/MISO_2,P2.1/SCLK_2]</td></tr><tr><td>1</td><td>0</td><td>SPI在[P5.4/SS_3,P4.0/MOSI_3,P4.1/MISO_3,P4.3/SCLK_3]</td></tr><tr><td>1</td><td>1</td><td>无效</td></tr></table>

<table><tr><td colspan="3">CCP可在3个地方切换,由 CCP_S1 / CCP_S0 两个控制位来选择</td></tr><tr><td>CCP_S1</td><td>CCP_S0</td><td>CCP可在P1/P2/P3之间来回切换</td></tr><tr><td>0</td><td>0</td><td>CCP在[P1.2/ECI,P1.1/CCP0,P1.0/CCP1,P3.7/CCP2]</td></tr><tr><td>0</td><td>1</td><td>CCP在[P3.4/ECI_2,P3.5/CCP0_2,P3.6/CCP1_2,P3.7/CCP2_2]</td></tr><tr><td>1</td><td>0</td><td>CCP在[P2.4/ECI_3,P2.5/CCP0_3,P2.6/CCP1_3,P2.7/CCP2_3]</td></tr><tr><td>1</td><td>1</td><td>无效</td></tr></table>

<table><tr><td colspan="3">串口1/S1可在3个地方切换,由 S1_S0 及 S1_S1 控制位来选择</td></tr><tr><td>S1_S1</td><td>S1_S0</td><td>串口1/S1可在P1/P3之间来回切换</td></tr><tr><td>0</td><td>0</td><td>串口1/S1在[P3.0/RxD,P3.1/TxD]</td></tr><tr><td>0</td><td>1</td><td>串口1/S1在[P3.6/RxD_2,P3.7/TxD_2]</td></tr><tr><td>1</td><td>0</td><td>串口1/S1在[P1.6/RxD_3/XTAL2,P1.7/TxD_3/XTAL1]串口1在P1口时要使用内部时钟</td></tr><tr><td>1</td><td>1</td><td>无效</td></tr></table>

DPS：DPTR registers select bit�������� ����� ��� DPTR 寄存器选择位

0, 使用缺省数据指针DPTR0

1，使用另一个数据指针DPTR1

# 14.2 SPI接口的结构

STC15系列单片机的SPI功能方框图如下图所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a3b9106b672886ce4c7296e6679013da4fe6479d616e6c48fe013f1813b17d39.jpg)



SPI 功能方框图


SPI的核心是一个8位移位寄存器和数据缓冲器，数据可以同时发送和接收。在SPI数据的传输过程中，发送和接收的数据都存储在数据缓冲器中。

对于主模式，若要发送一字节数据，只需将这个数据写到SPDAT寄存器中。主模式下SS信号不是必需的；但是在从模式下，必须在SS信号变为有效并接收到合适的时钟信号后，方可进行数据传输。在从模式下，如果一个字节传输完成后，SS信号变为高电平，这个字节立即被硬件逻辑标志为接收完成，SPI接口准备接收下一个数据。

# 14.3 SPI接口的数据通信

SPI接口有4个管脚 SCLK, MISO, MOSI和SS，可在3组管脚之间进行切换 SCLK/P1.5,MISO/P1.4, MOSI/P1.3和SS/P1.2 ]； SCLK_2/P2.1, MISO_2/P2.2, MOSI_2/P2.3和SS_2/P2.4][SCLK_3/P4.3, MISO_3/P4.1, MOSI_3/P4.0和SS_3/P5.4]

MOSI ( Master Out Slave In，主出从入)：主器件的输出和从器件的输入，用于主器件到从器件的串行 数据传输。当SPI作为主器件时，该信号是输出；当SPI作为从器件时，该信号是输入。数据传输时最高位在先，低位在后 根据SPI规范，多个从机可以共享一根MOSI信号线。在时钟边界的前半周期，主机将数据放在MOSI信号线上，从机在该边界处获取该数据。

MISO ( Master In Slave Out，主入从出)：从器件的输出和主器件的输入，用于实现从器件到主器件的数据传输。当SPI作为主器件时，该信号是输入；当SPI作为从器件时，该信号是输出。数据传输时最高位在先，低位在后 SPI规范中，一个主机可连接多个从机，因此，主机的MISO信号线会连接到多个从机上，或者说，多个从机共享一根MISO信号线。当主机与一个从机通信时，其他从机应将其MISO引脚驱动置为高阻状态。

SCLK ( SPI Clock，串行 时钟信号)：串行 时钟信号是主器件的输出和从器件的输入，用于同步主器件和从器件之间在MOSI和MISO线上的串行 数据传输。当主器件启动一次数据传输时，自动产生 8个SCLK时钟周期信号给从机。在SCLK的每个跳变处(上升沿或下降沿)移出一位数据。所以，一次数据传输可以传输一个字节的数据。

SCLK、MOSI和MISO通常和两个或更多SPI器件连接在一起。数据通过MOSI由主机传送到从机，通过MISO由从机传送到主机。SCLK信号在主模式时为输出，在从模式时为输入。如果SPI系统被禁止，即SPEN(SPCTL.6)=0(复位值)，这些管脚都可作为I/O口使用。

SS( Slave Select，从机选择信号)：这是一个输入信号，主器件用它来选择处于从模式的SPI模块。 SS的使用方法不同。在主模式下，SPI接口只能有一个主机，不存在主机选择问题，该模式下SS不是必需的。主模式下通常将主机的SS管脚通过10KΩ的电阻上拉高电平。每一个从机的SS接主机的I/O口，由主机控制电平高低，以便主机选择从机。在从模式下，不管发送还是接收，SS信号必须有效。因此在一次数据传输开始之前必须将SS为低电平。SPI主机可以使用I/O口选择一个SPI器件作为当前的从机。

SPI从器件通过其SS脚确定是否被选择。如果满足下面的条件之一，SS就被忽略：

如果SPI系统被禁止，即SPEN(SPCTL.6)= 0(复位值)•

如果SPI配置为主机，即MSTR(SPCTL.4)=1,并且P1.2/SS配置为输出（ P1M0.2和•P1M1.2）

如果SS脚被忽略，即SSIG(SPCTL.7)＝ 1，该脚配置用于I/O口功能。•

注：即使SPI被配置为主机（ $\mathbf { \Delta M S T R } = 1 \mathbf { \Delta }$ ），它仍然可以通过拉低SS脚配置为从机（如果P1.2/SS配置为输入且SSIG=0）。要使能该特性，应当置位SPIF(SPSTAT.7)。

# 14.3.1 SPI接口的数据通信方式

STC15系列单片机的SPI接口的数据通信方式有3种 ：单主机—从机方式、双器件方式(器件可互为主机和从机)和单主机—多从机方式。

单主机—单从机方式的连接图如下SPI图1所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e24a313153e98d12482f16d6b3c9e70668fe4eff08c9007c6fcf5052a869dc91.jpg)



SPI图1 SPI单主机—单从机 配置


在上图SPI图1中，从机的SSIG(SPCTL.7)为0，SS用于选择从机。SPI主机可使用任何端口（包括P1.2/SS）来驱动SS脚。位寄存器。当主机程序向SPDAT寄存器写入一个字节时，立即启动一个连续的8位移位通信过程：主机的SCLK引脚向从机的SCLK引脚发出一串脉冲，在这串脉冲的驱动下，主机SPI的8位移位寄存器中的数据移动到了从机SPI的8移位寄存器中。与此同时，从机SPI的8位移位寄存器中的数据移动到了主机SPI的8位移位寄存器中。由此，主机既可向从机发送数据，又可读从机中的数据。

双器件方式(器件可互为主机和从机)的连接图如下SPI图2所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/19aa62324198ff19a016d5370c827bd176af5569092044ce9933703c65430da6.jpg)



SPI图2 SPI双器件配置(器件可互为主从)


上图SPI图2所示为两个器件互为主从的情况。当没有发生SPI操作时，两个器件都可配置为主机(MSTR=1)，将SSIG清零并将P1.2(SS)配置为准双向模式。当其中一个器件启动传输时，它可将P1.2/SS配置为输出并驱动为低电平，这样就强制另一个器件变为从机。

双方初始化时将自己设置成忽略SS脚的SPI从模式。当一方要主动发送数据时，先检测SS脚的电平，如果SS脚是高电平，就将自己设置成忽略SS脚的主模式。通信双方平时将SPI设置成没有被选中的从模式。在该模式下，MISO、MOSI、SCLK均为输入，当多个MCU的SPI接口以此模式并联时不会发生总线冲突。这种特性在互为主/从、一主多从等应用中很有用。

注意：互为主/从模式时，双方的SPI速率必须相同。如果使用外部晶体振荡器，双方的晶体频率也要相同。

双器件方式(器件可互为主机和从机)的连接图如下SPI图3所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ef0d927f59dafb87262e113c3538e1430b6b79d1e9b504056ea51e6bf2a58d27.jpg)



SPI图3 SPI 单主机-多从机 配置


在上图SPI图3 中，从机的SSIG(SPCTL.7)为0，从机通过对应的SS信号被选中。SPI主机可使用任何端口(包括P1.2/SS )来驱动SS脚

# 14.3.2 对SPI进行配置

STC15系列单片机进行SPI通信时，主机和从机的选择由SPEN、SSIG、SS引脚(P1.2)和MSTR联合控制。下表所示为主/从模式的配置以及模式的使用和传输方向。


SPI 主从模式选择


<table><tr><td>SPEN</td><td>SSIG</td><td>\(\overline{SS}\)脚P1.2</td><td>MSTR</td><td>主或从模式</td><td>MISO P1.4</td><td>MOSIP1.3</td><td>SCLK P1.5</td><td>备注</td></tr><tr><td>0</td><td>X</td><td>P1.2/ SS</td><td>X</td><td>SPI功能禁止</td><td>P1.4/ MISO</td><td>P1.3/ MOSI</td><td>P1.5/ SCLK</td><td>SPI禁止。P1.2/SS, P1.3/MOSI, P1.4/MISO和P1.5/SCLK作为普通I/O口使用</td></tr><tr><td>1</td><td>0</td><td>0</td><td>0</td><td>从机模式</td><td>输出</td><td>输入</td><td>输入</td><td>选择作为从机</td></tr><tr><td>1</td><td>0</td><td>1</td><td>0</td><td>从机模式未被选中</td><td>高阻</td><td>输入</td><td>输入</td><td>未被选中。MISO为高阻状态,以避免总线冲突</td></tr><tr><td>1</td><td>0</td><td>0</td><td>1-&gt;0</td><td>从机模式</td><td>输出</td><td>输入</td><td>输入</td><td>P1.2/SS配置为输入或准双向口。SSIG为0。如果选择SS被驱动为低电平,则被选择作为从机。当SS变为低电平时,MSTR将清零。注:当SS处于输入模式时,如被驱动为低电平且SSIG=0时,MSTR位自动清零。</td></tr><tr><td rowspan="2">1</td><td rowspan="2">0</td><td rowspan="2">1</td><td rowspan="2">1</td><td>主(空闲)</td><td rowspan="2">输入</td><td>高阻</td><td>高阻</td><td>当主机空闲时MOSI和SCLK为高阻态以避免总线冲突。用户必须将SCLK上拉或下拉(根据CPOL/SPCTL.3的取值)以避免SCLK出现悬浮状态。</td></tr><tr><td>主(激活)</td><td>输出</td><td>输出</td><td>作为主机激活时,MOSI和SCLK为推挽输出</td></tr><tr><td>1</td><td>1</td><td>P1.2/ SS</td><td>0</td><td>从</td><td>输出</td><td>输入</td><td>输入</td><td></td></tr><tr><td>1</td><td>1</td><td>P1.2/ SS</td><td>1</td><td>主</td><td>输入</td><td>输出</td><td>输出</td><td></td></tr></table>

# 14.3.3 作为主机/从机时的额外注意事项

# 作为从机时的额外注意事项

当CPHA ${ } = 0$ 时，SSIG必须为0（也就是不能忽略SS脚），SS脚必须置低并且在每个连续的串行 字节发送完后须重新设置为高电平。如果SPDAT寄存器在SS有效（低电平）时执行写操作，那么将导致一个写冲突错误。CPHA $_ { . = 0 }$ 且SSIG $\scriptstyle { \frac { 1 } { \sqrt { \frac { 1 } { 2 } } } } = 0$ 时的操作未定义。

当CPHA $= 1$ 时，SSIG可以置1（即可以忽略SS脚）。如果SSIG $= 0$ ，SS脚可在连续传输之间保持低有效（即一直固定为低电平）。这种方式有时适用于具有单固定主机和单从机驱动MISO数据线的系统。

# 作为主机时的额外注意事项

在SPI中，传输总是由主机启动的。如果SPI使能（SPEN=1）并选择作为主机，主机对SPI数据寄存器的写操作将启动SPI时钟发生器和数据的传输。在数据写入SPDAT之后的半个到一个SPI位时间后，数据将出现在MOSI脚。

需要注意的是，主机可以通过将对应器件的SS脚驱动为低电平实现与之通信。写入主机SPDAT寄存器的数�据从MOSI �到从机的MOSI脚。同时从机SPDAT �从MISO移出发送到主机的MISO

传输完一个字节后，SPI时钟发�生器�停止，传输完成标志（SPIF ��（如果SPI中断使能）。主机和从机CPU �作是一个16器。当数据从主机移位传送到从机的同时，数据也以相反的方向移入。这意味着在一个移位周期中，主机和从机的数据相互交换。

# 14.3.4 通过SS改变模式

如果SPEN=1, SSIG=0且MSTR $^ { - 1 }$ ，SPI使能为主机模式。SS脚可配置为输入([P2M1.2,P2M0.2]=[1,0])或准双向模式([P2M1.2, P2M0.2]=[0,0])。这种情况下，另外一个主机可将该SS脚驱动为低电平，从而将该器件选择为SPI从机并向其发送数据。

为了避免争夺总线，SPI系统执行以下动作:

1) MSTR清零并且CPU变成从机。这样SPI就变成从机。MOSI和SCLK强制变为输入模式，而MISO则变为输出模式。

2) SPSTAT 的SPIF标志位置位。如果SPI中断已被使能，则产生 SPI中断。

用户软件必须一直对MSTR位进行检测，如果该位被一个从机选择所清零而用户想继续将SPI作为主机，这时就必须重新置位MSTR，否则就进入从机模式。

# 14.3.5 写冲突

SPI在发送时为单缓冲，在接收时为双缓冲。这样在前一次发送尚未完成之前，不能将新的数据写入移位寄存器。当发送过程中对数据寄存器进行写操作时，WCOL位(SPSTAT.6)将置位以指示数据冲突。在这种情况下，当前发送的数据继续发送，而新写入的数据将丢失。

当对主机或从机进行写冲突检测时，主机发生写冲突的情况是很罕见的，因为主机拥有数据传输的完全控制权。但从机有可能发生写冲突，因为当主机启动传输时，从机无法进行控制。

接收数据时，接收到的数据传送到一个并行读数据缓冲区，这样将释放移位寄存器以进行下一个数据的接收。但必须在下个字符完全移入之前从数据寄存器中读出接收到的数据，否则，前一个接收数据将丢失。

WCOL可通过软件向其写入“1”清零。

# 14.3.6 数据模式

时钟相位位 �A) �的时钟边沿。时钟极性位CPOL置时钟极性。

SPI图4～图7 所示为时钟相位位 �A

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/bb639db86ef8256ece59a5c50f346150000447986ab76f086b7ffc0102dc16f4.jpg)



SPI图4 SPI 从机传输格式（CPHA=0）


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/2f5b33045f1916a613a0c24aa829dbf9d596571a7280587d632fdbd5425dd0de.jpg)



SPI图5 SPI从机传输格式（CPHA=1）


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/0fd6c278964c5de15ade81601f8abba3d54d0f84f785671311263b3cdd0106cc.jpg)



SPI图6 SPI主机传输格式（CPHA=0）


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5de361292241108502bb4c40154e2dedd76eefa905187442c741823678c00200.jpg)



SPI图7 SPI主机传输格式（CPHA=1）


SPI接口的时钟信号线SCLK有Idle和Active两种状态：Idle状态时指在不进行数据传输的时候(或数据传输完成后)SCLK所处的状态；Active是与Idle相对的一种状态。

时钟相位位(CPHA)允许用户设置采样和改变数据的时钟边沿。时钟极性CPOL允许用户设置时钟极性。

如果CPOL=0,Idle状态 $: =$ 低电平，Active状态 $\cong$ 高电平；

如果CPOL=1,Idle状态 高电平，Active状态=低电平。

主机总是在SCLK=Idle状态时，将下一位要发送的数据置于数据线MOSI上。

从Idle状态到Active状态的转变，称为SCLK前沿；从Active状态到Idle状态的转变，称为SCLK后沿。一个SCLK前沿和后沿构成一个SCLK时钟周期，一个SCLK时钟周期传输一位数据。

# SPI时钟预分频器选择

SPI时钟预分频器选择是通过SPCTL寄存器中的SPR1-SPR0位实现的


SPI时钟频率的选择


<table><tr><td>SPR1</td><td>SPRO</td><td>时钟(SCLK)</td></tr><tr><td>0</td><td>0</td><td>CPU_CLK/4</td></tr><tr><td>0</td><td>1</td><td>CPU_CLK/16</td></tr><tr><td>1</td><td>0</td><td>CPU_CLK/64</td></tr><tr><td>1</td><td>1</td><td>CPU_CLK/128</td></tr></table>

其中，CPU_CLK是CPU时钟。

# 14.4 适用单主单从系统的SPI功能测试程序(C和汇编)

# 14.4.1 中断方式

# 1. C程序

/* -*/ 

/* --- STC MCU Limited. - */ 

/* --- 演示STC 1T 系列单片机 SPI功能(适用单主单从，中断方式)- *

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序- */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可-------- *

/* * 

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

//#define MASTER //define:master undefine:slave 

#define FOSC 18432000L 

#define BAUD (256 - FOSC / 32 / 115200) 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

typedef unsigned long DWORD; 

#define URMD 0 //0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

sfr T2H 0xd6; //定时器2高8位

sfr T2L 0xd7; //定时器2低8位

sfr AUXR $=$ 0x8e; //辅助寄存器

sfr SPSTAT $=$ 0xcd; //SPI状态寄存器

#define SPIF 0x80 //SPSTAT.7 

#define WCOL 0x40 //SPSTAT.6 

sfr SPCTL = 0xce; //SPI控制寄存器

#define SSIG 0x80 //SPCTL.7 

#define SPEN 0x40 //SPCTL.6 

#define DORD 0x20 //SPCTL.5 

#define MSTR 0x10 //SPCTL.4 

#define CPOL 0x08 //SPCTL.3 

```c
define CPHA 0x04 //SPCTL.2  
#define SPDHH 0x00 //CPU_CLK/4  
#define SPDH 0x01 //CPU_CLK/16  
#define SPDL 0x02 //CPU_CLK/64  
#define SPDLL 0x03 //CPU_CLK/128  
sfr SPDAT = 0xfc; //SPI数据寄存器  
sbit SPISS = P1^1; //SPI从机选择口，连接到其它MCU的SS口//当SPI为一主多从模式时，//请使用主机的普通IO口连接到从机的SS口  
sfr IE2 = 0xEF; //中断控制寄存器2  
#define ESPI 0x02 //IE2.1  
void InitUart();  
void InitSPI();  
void SendUart(BYTE dat); //发送数据到PC  
BYTERecvUart(); //从PC接收数据  
} //Limited  
void main()  
{ InitUart(); //初始化串口InitSPI(); //初始化SPI  
IE2 |= ESPI;  
EA = 1;  
while (1) { #ifdef MASTER //对于主机(接收串口数据并发送给从机,同时//从即接收SPI数据并回传给PC)ACC =RecvUart(); //拉低从机的SSSPDAT = ACC; //触发SPI发送数据#endif}  
}  
}  
void spiISR() interrupt 9 using 1 //SPI中断服务程序9(004BH)  
{ SPSTAT = SPIF | WCOL; //清除SPI状态位ifdef MASTER  
SPISS = 1; //拉高从机的SSSendUart(SPDAT); //返回SPI数据  
#else //对于从机(从主机接收SPI数据,同时SPDAT = SPDAT; //发送前一个SPI数据给主机)  
#endif}
```

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////  
void InitUart()  
{SCON = 0x5a; //设置串口为8位可变波特率URMD == 0T2L = 0xd8; //设置波特率重装值T2H = 0xff; //115200 bps(65536-18432000/4/115200)AUXR = 0x14; //T2为1T模式,并启动定时器2AUXR |= 0x01; //选择定时器2为串口1的波特率发生器#elif URMD == 1AUXR = 0x40; //定时器1为1T模式TMOD = 0x00; //定时器1为模式0(16位自动重载)TL1 = 0xd8; //设置波特率重装值TH1 = 0xff; //115200 bps(65536-18432000/4/115200)TR1 = 1; //定时器1开始启动  
#elseTMOD = 0x20; //设置定时器1为8位自动重装载模式AUXR = 0x40; //定时器1为1T模式TH1 = TL1 = 0xfb; //115200 bps(256 - 18432000/32/115200)TR1 = 1;  
#endif}  
//////////////////////////void InitSPI()  
{SPDAT = 0; //初始化SPI数据SPSTAT $=$ SPIF | WCOL; //清除SPI状态位ifdef MASTERSPCTL $=$ SPEN | MSTR; //主机模式  
#elseSPCTL $=$ SPEN; //从机模式  
}  
//////////////////////////void SendUart(BYTE dat)  
{while (!TI); //等待发送完成TI = 0; //清除发送标志SBUF $=$ dat; //发送串口数据}  
//////////////////////////BYTERecvUart()  
{while (!RI); //等待串口数据接收完成RI = 0; //清除接收标志return SBUF; //返回串口数据}

# 2. 汇编程序

/* -*/ 

/* --- STC MCU Limited. - -*/ 

/* --- 演示STC 1T 系列单片机 SPI功能(适用单主单从，中断方式)- */

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 - */ 

/* --- Tel: 86-755-82948412 - - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序- */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可- -*

/*- */ 


//假定测试芯片的工作频率为18.432MHz


<table><tr><td>#define</td><td colspan="2">MASTER</td><td>//define:master undefine:slave</td></tr><tr><td>#define</td><td>URMD</td><td>0</td><td>//0:使用定时器2作为波特率发生器
//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器
//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器</td></tr><tr><td>T2H</td><td>DATA</td><td>0D6H</td><td>//定时器2高8位</td></tr><tr><td>T2L</td><td>DATA</td><td>0D7H</td><td>//定时器2低8位</td></tr><tr><td>AUXR</td><td>DATA</td><td>08EH</td><td>;辅助寄存器</td></tr><tr><td>SPSTAT</td><td>DATA</td><td>0CDH</td><td>;SPI状态寄存器</td></tr><tr><td>SPIF</td><td>EQU</td><td>080H</td><td>;SPSTAT.7</td></tr><tr><td>WCOL</td><td>EQU</td><td>040H</td><td>;SPSTAT.6</td></tr><tr><td>SPCTL</td><td>DATA</td><td>0CEH</td><td>;SPI控制寄存器</td></tr><tr><td>SSIG</td><td>EQU</td><td>080H</td><td>;SPCTL.7</td></tr><tr><td>SPEN</td><td>EQU</td><td>040H</td><td>;SPCTL.6</td></tr><tr><td>DORD</td><td>EQU</td><td>020H</td><td>;SPCTL.5</td></tr><tr><td>MSTR</td><td>EQU</td><td>010H</td><td>;SPCTL.4</td></tr><tr><td>CPOL</td><td>EQU</td><td>008H</td><td>;SPCTL.3</td></tr><tr><td>CPHA</td><td>EQU</td><td>004H</td><td>;SPCTL.2</td></tr><tr><td>SPDHH</td><td>EQU</td><td>000H</td><td>;CPU_CLK/4</td></tr><tr><td>SPDH</td><td>EQU</td><td>001H</td><td>;CPU_CLK/16</td></tr><tr><td>SPDL</td><td>EQU</td><td>002H</td><td>;CPU_CLK/64</td></tr><tr><td>SPDLL</td><td>EQU</td><td>003H</td><td>;CPU_CLK/128</td></tr><tr><td>SPDAT</td><td>DATA</td><td>0CFH</td><td>;SPI数据寄存器</td></tr><tr><td>SPISS</td><td>BIT</td><td>P1.1</td><td>;SPI从机选择口,连接到其它MCU的SS口
;当SPI为一主多从模式时,请使用主机的普通IO口连接到从机的SS口</td></tr><tr><td>IE2</td><td>EQU</td><td>0AFH</td><td>;中断控制寄存器2</td></tr><tr><td>ESPI</td><td>EQU</td><td>02H</td><td>;IE2.1</td></tr></table>

;////////////////////////////////////////////////////////// 

<table><tr><td>ORG</td><td>0000H</td><td></td></tr><tr><td>LJMP</td><td>RESET</td><td></td></tr><tr><td>ORG</td><td>004BH</td><td>;SPI中断服务程序</td></tr><tr><td>SPI_ISR:</td><td></td><td></td></tr><tr><td>PUSH</td><td>ACC</td><td></td></tr><tr><td>PUSH</td><td>PSW</td><td></td></tr><tr><td>MOV</td><td>SPSTAT, #SPIF | WCOL</td><td>;清除SPI状态位</td></tr><tr><td>#ifdef MASTER</td><td></td><td></td></tr><tr><td>SETB</td><td>SPISS</td><td>;拉高从机的SS</td></tr><tr><td>MOV</td><td>A, SPDAT</td><td>;返回SPI数据</td></tr><tr><td>LCALL</td><td>SEND_UART</td><td></td></tr><tr><td>#else</td><td></td><td>//对于从机(从主机接收SPI数据,同时</td></tr><tr><td>MOV</td><td>SPDAT, SPDAT</td><td>;发送前一个SPI数据给主机)</td></tr><tr><td>#endif</td><td></td><td></td></tr><tr><td>POP</td><td>PSW</td><td></td></tr><tr><td>POP</td><td>ACC</td><td></td></tr><tr><td>RETI</td><td></td><td></td></tr><tr><td colspan="2">;**********</td><td></td></tr><tr><td>ORG</td><td>0100H</td><td></td></tr><tr><td>RESET:</td><td></td><td></td></tr><tr><td>LCALL</td><td>INIT_UART</td><td>;初始化串口</td></tr><tr><td>LCALL</td><td>INIT_SPI</td><td>;初始化SPI</td></tr><tr><td>ORL</td><td>IE2, #ESPI</td><td></td></tr><tr><td>SETB</td><td>EA</td><td></td></tr><tr><td>MAIN:</td><td></td><td></td></tr><tr><td>#ifndef MASTER</td><td></td><td>//对于主机(接收串口数据并发送给从机,同时</td></tr><tr><td>LCALL</td><td>RECV_UART</td><td>;从从即接收SPI数据并回传给PC)</td></tr><tr><td>CLR</td><td>SPISS</td><td>;拉低从机的SS</td></tr><tr><td>MOV</td><td>SPDAT, A</td><td>;触发SPI发送数据</td></tr><tr><td>#endif</td><td></td><td></td></tr><tr><td>SJMP</td><td>MAIN</td><td></td></tr><tr><td colspan="2">;**********</td><td></td></tr><tr><td>INIT_UART:</td><td></td><td></td></tr><tr><td>MOV</td><td>SCON, #5AH</td><td>;设置串口为8位可变波特率</td></tr><tr><td>#if URMD==0</td><td></td><td></td></tr><tr><td>MOV</td><td>T2L, #0D8H</td><td>;设置波特率重装值(65536-18432000/4/115200)</td></tr><tr><td>MOV</td><td>T2H, #0FFH</td><td></td></tr><tr><td>MOV</td><td>AUXR, #14H</td><td>;T2为1T模式,并启动定时器2</td></tr><tr><td>ORL</td><td>AUXR, #01H</td><td>;选择定时器2为串口1的波特率发生器</td></tr><tr><td>#elif URMD==1</td><td></td><td></td></tr><tr><td>MOV</td><td>AUXR, #40H</td><td>;定时器1为1T模式</td></tr><tr><td>MOV</td><td>TMOD, #00H</td><td>;定时器1为模式0(16位自动重载)</td></tr><tr><td>MOV</td><td>TL1, #0D8H</td><td>;设置波特率重装值(65536-18432000/4/115200)</td></tr><tr><td>MOV</td><td>TH1, #0FFH</td><td></td></tr><tr><td>SETB</td><td>TR1</td><td>;定时器1开始运行</td></tr></table>

#else 

MOV TMOD, #20H 

;设置定时器1为8位自动重装载模式

MOV AUXR, #40H 

;定时器1为1T模式

MOV TL1, #0FBH 

;115200 bps(256 - 18432000/32/115200) 

MOV TH1, #0FBH 

SETB TR1 

#endif 

RET 

;////////////////////////////////////////////////////////// 

INIT_SPI: 

MOV SPDAT, #0 

;初始化SPI数据

MOV SPSTAT, #SPIF | WCOL 

;清除SPI状态位

#ifdef MASTER 

MOV SPCTL, #SPEN | MSTR 

;主机模式

#else 

MOV SPCTL, #SPEN 

;从机模式

#endif 

RET 

;////////////////////////////////////////////////////////// 

SEND_UART: 

JNB TI, $ 

;等待发送完成

CLR TI 

;清除发送标志

MOV SBUF, A 

;发送串口 数据

RET 

;////////////////////////////////////////////////////////// 

RECV_UART: 

JNB RI, $ 

;等待串口 数据接收完成

CLR RI 

;清除接收标志

MOV A, SBUF 

;返回串口 数据

RET 

RET 

;////////////////////////////////////////////////////////// 

END 

# 14.4.2 查询方式

# 1. C程序

/* -*/ 

/* --- STC MCU Limited. -*/ 

/* --- 演示STC 1T 系列单片机 SPI功能(适用单主单从，查询方式) -*/

/* --- 研发顾问QQ：800003751- */

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序- */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可------------*/

/*- */ 

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

//#define MASTER //define:master undefine:slave 

#define FOSC 18432000L 

#define BAUD (256 - FOSC / 32 / 115200) 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

typedef unsigned long DWORD; 

#define URMD 0 //0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

sfr T2H = 0xd6; //定时器2高8位

sfr T2L = 0xd7; //定时器2低8位

sfr AUXR = 0x8e; //辅助寄存器

sfr SPSTAT $=$ 0xcd; //SPI状态寄存器

#define SPIF 0x80 //SPSTAT.7 

#define WCOL 0x40 //SPSTAT.6 

sfr SPCTL = 0xce; //SPI控制寄存器

#define SSIG 0x80 //SPCTL.7 

#define SPEN 0x40 //SPCTL.6 

#define DORD 0x20 //SPCTL.5 

#define MSTR 0x10 //SPCTL.4 

#define CPOL 0x08 //SPCTL.3 

#define CPHA 0x04 //SPCTL.2 

#define SPDHH 0x00 //CPU_CLK/4 

#define SPDH 0x01 //CPU_CLK/16 

#define SPDL 0x02 //CPU_CLK/64 

<table><tr><td colspan="4">STC15F2K60S2系列单片机指南 官方网站:www.STCMCU.com 研发顾问QQ:80003751 STC-全球最大的8051单片机设计公司</td></tr><tr><td>#	define</td><td>SPDLL</td><td>0x03</td><td>//CPU_CLK/128</td></tr><tr><td>sfr</td><td>SPDAT =</td><td>0xfc;</td><td>//SPI数据寄存器</td></tr><tr><td>sbit</td><td>SPISS =</td><td>P1^1;</td><td>//SPI从机选择口,连接到其它MCU的SS口
//当SPI为一主多从模式时,
//请使用主机的普通IO口连接到从机的SS口</td></tr><tr><td>void InitUart();</td><td></td><td></td><td></td></tr><tr><td>void InitSPI();</td><td></td><td></td><td></td></tr><tr><td>void SendUart(BYTE dat);</td><td></td><td></td><td>//发送数据到PC</td></tr><tr><td>BYTERecvUart();</td><td></td><td></td><td>//从PC接收数据</td></tr><tr><td>BYTE SPISwap(BYTE dat);</td><td></td><td></td><td>//主机与从机之间交换数据</td></tr><tr><td>void main()</td><td></td><td></td><td></td></tr><tr><td>{</td><td>InitUart();</td><td>//初始化串口</td><td></td></tr><tr><td></td><td>InitSPI();</td><td>//初始化SPI</td><td></td></tr><tr><td></td><td>while (1)</td><td></td><td></td></tr><tr><td></td><td>{</td><td></td><td></td></tr><tr><td></td><td>#ifdef MASTER</td><td colspan="2">//对于主机(接收串口数据并发送给从机,同时
//从即接收SPI数据并回传给PC)</td></tr><tr><td></td><td>SendUart(SPISwap(RecvUart()));</td><td></td><td></td></tr><tr><td></td><td>#else</td><td colspan="2">//对于从机(从主机接收SPI数据,同时
//发送前一个SPI数据给主机)</td></tr><tr><td></td><td>ACC = SPISwap(ACC);</td><td></td><td></td></tr><tr><td></td><td>#endif</td><td></td><td></td></tr><tr><td>}</td><td></td><td></td><td></td></tr><tr><td>void InitUart()</td><td></td><td></td><td></td></tr><tr><td>{</td><td>SCON =</td><td>0x5a;</td><td>//设置串口为8位可变波特率</td></tr><tr><td>#if</td><td>URMD ==</td><td>0</td><td></td></tr><tr><td></td><td>T2L =</td><td>0xd8;</td><td>//设置波特率重装值</td></tr><tr><td></td><td>T2H =</td><td>0xff;</td><td>//115200 bps(65536-18432000/4/115200)</td></tr><tr><td></td><td>AUXR =</td><td>0x14;</td><td>//T2为1T模式,并启动定时器2</td></tr><tr><td></td><td>AUXR |=</td><td>0x01;</td><td>//选择定时器2为串口1的波特率发生器</td></tr><tr><td>#elif</td><td>URMD ==</td><td>1</td><td></td></tr><tr><td></td><td>AUXR =</td><td>0x40;</td><td>//定时器1为1T模式</td></tr><tr><td></td><td>TMOD =</td><td>0x00;</td><td>//定时器1为模式0(16位自动重载)</td></tr><tr><td></td><td>TL1 =</td><td>0xd8;</td><td>//设置波特率重装值</td></tr><tr><td></td><td>TH1 =</td><td>0xff;</td><td>//115200 bps(65536-18432000/4/115200)</td></tr><tr><td></td><td>TR1 =</td><td>1;</td><td>//定时器1开始启动</td></tr><tr><td>#else</td><td></td><td></td><td></td></tr><tr><td></td><td>TMOD =</td><td>0x20;</td><td>//设置定时器1为8位自动重装载模式</td></tr><tr><td></td><td>AUXR =</td><td>0x40;</td><td>//定时器1为1T模式</td></tr><tr><td></td><td>TH1 =</td><td>TL1 = 0xfb;</td><td>//115200 bps(256 - 18432000/32/115200)</td></tr><tr><td></td><td>TR1 =</td><td>1;</td><td></td></tr><tr><td>#endif</td><td></td><td></td><td></td></tr><tr><td>}</td><td></td><td></td><td></td></tr></table>

```txt
// // // // // // // // // // // // // // // // // // // // // // // // 
```

void InitSPI()  
{SPDAT $= 0$ //初始化SPI数据SPSTAT $\equiv$ SPI|WCOL; //清除SPI状态位#ifdef MASTERSPCTL $=$ SPEN|MSTR; //主机模式#elseSPCTL $=$ SPEN; //从机模式endif}  
//  
void SendUart(BYTE dat)  
{while(!TI); //等待发送完成TI $= 0$ //清除发送标志SBUF $\equiv$ dat; //发送串口数据}  
//  
BYTERecvUart()  
{while(!RI); //等待串口数据接RI $= 0$ //清除接收标志return SBUF; //返回串口数据}  
//  
BYTE SPISwap(BYTE dat)  
{#ifdef MASTERSPISS $= 0$ //拉低从机的SS#endifSPDAT $\equiv$ dat; //触发SPI发送数while(!(SPSTAT&SPI))；//等待发送完成SPSTAT $\equiv$ SPI|WCOL; //清除SPI状态位#ifdef MASTERSPISS $= 1$ //拉高从机的SS#endifreturn SPDAT; //返回SPI数据}

# 2. 汇编程序

/*- -*/ 

/* --- STC MCU Limited. -*/ 

/* --- 演示STC 1T 系列单片机 SPI功能(适用单主单从，查询方式) -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序- */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可--- 

/*- */ 

//假定测试芯片的工作频率为18.432MHz

//#define MASTER 

//define:master undefine:slave 

#define URMD 0 

//0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

T2H DATA 0D6H 

//定时器2高8位

T2L DATA 0D7H 

//定时器2低8位

AUXR DATA 08EH 

;Auxiliary register 

SPSTAT DATA 0CDH 

;SPI status register 

SPIF EQU 080H 

;SPSTAT.7 

WCOL EQU 040H 

;SPSTAT.6 

SPCTL DATA 0CEH 

;SPI control register 

SSIG EQU 080H 

;SPCTL.7 

SPEN EQU 040H 

;SPCTL.6 

DORD EQU 020H 

;SPCTL.5 

MSTR EQU 010H 

;SPCTL.4 

CPOL EQU 008H 

;SPCTL.3 

CPHA EQU 004H 

;SPCTL.2 

SPDHH EQU 000H 

;CPU_CLK/4 

SPDH EQU 001H 

;CPU_CLK/16 

SPDL EQU 002H 

;CPU_CLK/64 

SPDLL EQU 003H 

;CPU_CLK/128 

SPDAT DATA 0CFH 

;SPI data register 

SPISS BIT P1.1 

;SPI从机选择口, 连接到其它MCU的SS口

;当SPI为一主多从模式时,

;请使用主机的普通IO口连接到从机的SS口

;////////////////////////////////////////////////////////// 

ORG 0000H 

LJMP RESET 

ORG 0100H 

RESET: 

LCALL INIT_UART 

;初始化串口

LCALL INIT_SPI 

;初始化SPI

MAIN: 

#ifdef MASTER 

//对于主机(接收串口 数据并发送给从机,同时

LCALL RECV_UART 

从从即接收SPI数据并回传给PC)

LCALL SPI_SWAP 

LCALL SEND_UART 

#else 

//对于从机(从主机接收SPI数据,同时

LCALL SPI_SWAP 

发送前一个SPI数据给主机)

#endif 

SJMP MAIN 

;//////////////////////// /////////////////////// 

INIT_UART: 

MOV SCON, #5AH 

;设置串口 为8位可变波特率

#if URMD $\Longrightarrow = 0$ 

;设置波特率重装值(65536-18432000/4/115200)

MOV T2L, #0D8H 

;T2为1T模式, 并启动定时器2

MOV T2H, #0FFH 

;选择定时器2为串口 1的波特率发生器

MOV AUXR, #14H 

ORL AUXR, #01H 

#elif URMD $= = 1$ 

;定时器1为1T模式

MOV AUXR, #40H 

;定时器1为模式0(16位自动重载)

MOV TMOD, #00H 

;设置波特率重装值(65536-18432000/4/115200)

MOV TL1, #0D8H 

;定时器1开始运行

MOV TH1, #0FFH 

SETB TR1 

#else 

;设置定时器1为8位自动重装载模式

MOV TMOD, #20H 

;定时器1为1T模式

MOV AUXR, #40H 

;115200 bps(256 - 18432000/32/115200) 

MOV TL1, #0FBH 

MOV TH1, #0FBH 

SETB TR1 

#endif 

RET 

;////////////////////////////////////////////////////////// 

INIT_SPI: 

MOV SPDAT, #0 

;初始化SPI数据

MOV SPSTAT, #SPIF | WCOL 

;清除SPI状态位

#ifdef MASTER 

MOV SPCTL, #SPEN | MSTR 

;主机模式

#else 

```txt
MOV SPCTL, #SPEN ;从机模式  
endif RET
```

```txt
// 
```

```txt
SEND_UART:  
JNB TI, $ ;等待发送完成  
CLR TI ;清除发送标志  
MOV SBUF, A ;发送串口数据  
RET
```

```txt
// // // // // // // // // // // // // // // // // // // // 
```

```txt
RECV_UART: JNB RI, \\( ;等待串口数据接收完成 CLR RI ;清除接收标志 MOV A, SBUF ;返回串口数据 RET RET
```

```javascript
//111111111111111111111111 
```

```txt
SPI_SWAP: #ifdef MASTER CLR SPISS ;拉低从机的SS #endif MOV SPDAT, A ;触发SPI发送数据 WAIT: MOV A, SPSTAT JNB ACC.7, WAIT ;等待发送完成 MOV SPSTAT, #SPIF | WCOL #ifdef MASTER SETB SPISS ;拉高从机的SS #endif MOV A, SPDAT ;返回SPI数据 RET
```

```javascript
//111111111111111111111111 
```

END 

# 14.5 适用互为主从系统的SPI功能测试程序(C和汇编)

# 14.5.1 中断方式

# 1. C程序

/*- -*/ 

/* --- STC MCU Limited. - -*/ 

/* --- 演示STC 1T 系列单片机 SPI功能(适用互为主从系统，中断方式) -*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 - */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序- */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可-- -*

/*- - */ 

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#define FOSC 18432000L 

#define BAUD (256 - FOSC / 32 / 115200) 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

typedef unsigned long DWORD; 

#define URMD 0 //0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

sfr T2H 0xd6; //定时器2高8位

sfr T2L $=$ 0xd7; //定时器2低8位

sfr AUXR $=$ = 0x8e; //辅助寄存器

sfr SPSTAT $=$ 0xcd; //SPI状态寄存器

#define SPIF 0x80 //SPSTAT.7 

#define WCOL 0x40 //SPSTAT.6 

sfr SPCTL = 0xce; //SPI控制寄存器

#define SSIG 0x80 //SPCTL.7 

#define SPEN 0x40 //SPCTL.6 

#define DORD 0x20 //SPCTL.5 

#define MSTR 0x10 //SPCTL.4 

#define CPOL 0x08 //SPCTL.3 

#define CPHA 0x04 //SPCTL.2 

#define SPDHH 0x00 //CPU_CLK/4 

<table><tr><td colspan="2">STC15F2K60S2系列单片机指南</td><td>官方网站:www.STCMCU.com</td><td>研发顾问QQ:80003751</td><td>STC—全球最大的8051单片机设计公司</td></tr><tr><td>#	define</td><td>SPDH</td><td>0x01</td><td>//CPU_CLK/16</td><td></td></tr><tr><td>#	define</td><td>SPDL</td><td>0x02</td><td>//CPU_CLK/64</td><td></td></tr><tr><td>#	define</td><td>SPDLL</td><td>0x03</td><td>//CPU_CLK/128</td><td></td></tr><tr><td>sfr</td><td>SPDAT =</td><td>0xfc;</td><td>//SPI数据寄存器</td><td></td></tr><tr><td rowspan="2">sbit</td><td rowspan="2">SPISS =</td><td rowspan="2">P1^1;</td><td>//SPI从机选择口,连接到其它MCU的SS口</td><td>//当SPI为一主多从模式时,</td></tr><tr><td>//请使用主机的普通IO口连接到从机的SS口</td><td></td></tr><tr><td>sfr</td><td>IE2 =</td><td>0xAF;</td><td>//中断控制寄存器2</td><td></td></tr><tr><td>#	define</td><td>ESPI</td><td>0x02</td><td>//IE2.1</td><td></td></tr><tr><td>void InitUart();</td><td></td><td></td><td></td><td></td></tr><tr><td>void InitSPI();</td><td></td><td></td><td></td><td></td></tr><tr><td>void SendUart(BYTE dat);</td><td></td><td></td><td>//发送数据到PC</td><td></td></tr><tr><td>BYTERecvUart();</td><td></td><td></td><td>//从PC接收数据</td><td></td></tr><tr><td>bit</td><td>MSSEL;</td><td></td><td>//1: master 0:slave</td><td></td></tr><tr><td>//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////</td><td></td><td></td><td></td><td></td></tr><tr><td>void main()</td><td></td><td></td><td></td><td></td></tr><tr><td>{</td><td>InitUart();</td><td>//初始化串口</td><td></td><td></td></tr><tr><td></td><td>InitSPI();</td><td>//初始化SPI</td><td></td><td></td></tr><tr><td></td><td>IE2 |= ESPI;</td><td></td><td></td><td></td></tr><tr><td></td><td>EA = 1;</td><td></td><td></td><td></td></tr><tr><td></td><td>while (1)</td><td></td><td></td><td></td></tr><tr><td></td><td>{</td><td>if (RI)</td><td></td><td></td></tr><tr><td></td><td></td><td>SPCTL = SPEN | MSTR;</td><td>//设置为主机模式</td><td></td></tr><tr><td></td><td></td><td>MSSEL = 1;</td><td></td><td></td></tr><tr><td></td><td></td><td>ACC = RecvUart();</td><td></td><td></td></tr><tr><td></td><td></td><td>SPISS = 0;</td><td>//拉低从机的SS</td><td></td></tr><tr><td></td><td></td><td>SPDAT = ACC;</td><td>//触发SPI发送数据</td><td></td></tr><tr><td></td><td></td><td>}</td><td></td><td></td></tr><tr><td></td><td>}</td><td></td><td></td><td></td></tr><tr><td>}</td><td></td><td></td><td></td><td></td></tr><tr><td>/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////</td><td></td><td></td><td></td><td></td></tr><tr><td colspan="3">void spi_isr() interrupt 9 using 1</td><td>//SPI中断服务程序9(004BH)</td><td></td></tr><tr><td>{</td><td>SPSTAT = SPIF | WCOL;</td><td>//清除SPI状态位</td><td></td><td></td></tr><tr><td>if (MSSEL)</td><td></td><td></td><td></td><td></td></tr><tr><td>{</td><td>SPCTL = SPEN;</td><td>//重置为从机模式</td><td></td><td></td></tr><tr><td></td><td>MSSEL = 0;</td><td></td><td></td><td></td></tr></table>

SPISS = 1; //拉高从机的SS SendUart(SPDAT); //返回SPI数据   
} else { SPDAT $=$ SPDAT; //发送前一个SPI数据给主机)   
}   
//**********//**********void InitUart()   
{ SCON $=$ 0x5a; //设置串口为8位可变波特率 URMD $= =$ 0 T2L $=$ 0xd8; //设置波特率重装值 T2H $=$ 0xff; //115200 bps(65536-18432000/4/115200) AUXR $=$ 0x14; //T2为1T模式,并启动定时器2 AUXR $\models =$ 0x01; //选择定时器2为串口1的波特率发生器 URMD $= =$ 1 AUXR $=$ 0x40; //定时器1为1T模式 TMOD $=$ 0x00; //定时器1为模式0(16位自动重载) TL1 $=$ 0xd8; //设置波特率重装值 TH1 $=$ 0xff; //115200 bps(65536-18432000/4/115200) TR1 $=$ 1; //定时器1开始启动 #else TMOD $=$ 0x20; //设置定时器1为8位自动重装载模式 AUXR $=$ 0x40; //定时器1为1T模式 TH1 $=$ TL1 $=$ 0xfb; //115200 bps(256 - 18432000/32/115200) TR1 $=$ 1;   
#endif   
}   
//**********//**********void InitSPI()   
{ SPDAT $= 0$ ; //初始化SPI数据 SPSTAT $=$ SPI|WCOL; //清除SPI状态位 SPCTL $=$ SPEN; //从机模式   
}   
//**********//**********void SendUart(BYTE dat)   
{ while (!TI); //等待发送完成 TI $= 0$ ; //清除发送标志 SBUF $=$ dat; //发送串口数据

```txt
11111111111111111111111111111 
```

```txt
BYTERecvUart()  
{ while(!RI); //等待串口数据接收完成 RI=0; //清除接收标志 return SBUF; //返回串口数据
```

# 2. 汇编程序

```txt
/* 
```

```javascript
/\*---STC MCU Limited. \*/ 
```

```txt
/*---演示STC1T系列单片机SPI功能(适用互为主从系统，中断方式)--------*/
```

```txt
/* -- 研发顾问QQ: 800003751
```

```txt
/* -- Fax: 86-755-82905966 
```

```txt
/\*---Tel:86-755-82948412 
```

```txt
/* -- Web: www.STCMCU.com 
```

```txt
/*如果要在程序中使用此代码，请在程序中注明使用了STC的资料及程序******/
```

```txt
/*如果要在文章中应用此代码，请在文章中注明使用了STC的资料及程序******/
```

```javascript
/*----在Keil C开发环境中选择Intel8052编译，头文件包含<reg51.h>即可*/
```

```txt
\* 
```

```txt
//假定测试芯片的工作频率为18.432MHz
```

```txt
define URMD 0 
```

```txt
//0:使用定时器2作为波特率发生器
```

```javascript
//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器
```

```txt
//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器
```

```txt
T2H DATA 0D6H 
```

```txt
//定时器2高8位
```

```txt
T2L DATA 0D7H 
```

```txt
//定时器2低8位
```

```txt
AUXR DATA 08EH 
```

```txt
;辅助寄存器
```

```txt
SPSTAT DATA 0CDH 
```

```txt
;SPI状态寄存器
```

```txt
SPIF EQU 080H 
```

```csv
,SPSTAT.7 
```

```txt
WCOL EQU 040H 
```

```txt
;SPSTAT.6 
```

```txt
SPCTL DATA OCEH 
```

```txt
;SPI控制寄存器
```

```txt
SSIG EQU 080H 
```

```txt
;SPCTL.7 
```

```txt
SPEN EQU 040H 
```

```txt
;SPCTL.6 
```

```txt
DORD EQU 020H 
```

```txt
;SPCTL.5 
```

```txt
MSTR EQU 010H 
```

```txt
;SPCTL.4 
```

```txt
CPOL EQU 008H 
```

```txt
;SPCTL.3 
```

```txt
CPHA EQU 004H 
```

```txt
;SPCTL.2 
```

```txt
SPDHHEQU 000H 
```

```txt
:CPU_CLK/4 
```

```txt
SPDH EQU 001H 
```

```txt
;CPU_CLK/16 
```

```txt
SPDL EQU 002H 
```

```txt
;CPU_CLK/64 
```

```txt
SPDLL EQU 003H 
```

```csv
;CPU_CLK/128 
```

```txt
SPDAT DATA 0CFH 
```

```txt
,SPI数据寄存器
```

```txt
SPISS BIT P1.1 
```

```csv
;SPI从机选择口,连接到其它MCU的SS口
```

```txt
;当SPI为一主多从模式时,请使用主机的普通IO口连接到从机的SS口
```

IE2 EQU 0AFH 

;中断控制寄存器2

ESPI EQU 02H 

;IE2.1 

MSSEL BIT 20H.0 

;1: master 0:slave 

;////////////////////////////////////////////////////////// 

ORG 0000H 

LJMP RESET 

ORG 004BH 

;SPI中断服务程序

SPI_ISR: 

PUSH ACC 

PUSH PSW 

MOV SPSTAT, #SPIF | WCOL 

;清除SPI状态位

JBC MSSEL, MASTER_SEND 

SLAVE_RECV: 

;对于从机(从主机接收SPI数据,同时

MOV SPDAT, SPDAT 

发送前一个SPI数据给主机)

JMP SPI_EXIT 

MASTER_SEND: 

SETB SPISS 

;拉高从机的SS

MOV SPCTL, #SPEN 

;重置为从机模式

MOV A, SPDAT 

;返回SPI数据

LCALL SEND_UART 

SPI_EXIT: 

POP PSW 

POP ACC 

RETI 

;////////////////////////////////////////////////////////// 

ORG 0100H 

RESET: 

MOV SP, #3FH 

LCALL INIT_UART 

;初始化串口

LCALL INIT_SPI 

;初始化SPI

ORL IE2, #ESPI 

SETB EA 

MAIN: 

JNB RI, $ 

;等待串口 数据

MOV SPCTL, #SPEN | MSTR 

; ;设置为主机模式

SETB MSSEL 

LCALL RECV_UART 

;接收串口 数据

CLR SPISS 

;拉低从机的SS

MOV SPDAT, A 

;触发SPI发送数据

SJMP MAIN 

```txt
// 
```

INIT_UART: 

<table><tr><td>MOV</td><td>SCON,</td><td>#5AH</td><td>;设置串口为8位可变波特率</td></tr><tr><td>#if URMD==0</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>T2L,</td><td>#0D8H</td><td>;设置波特率重装值(65536-18432000/4/115200)</td></tr><tr><td>MOV</td><td>T2H,</td><td>#0FFH</td><td></td></tr><tr><td>MOV</td><td>AUXR,</td><td>#14H</td><td>;T2为1T模式,并启动定时器2</td></tr><tr><td>ORL</td><td>AUXR,</td><td>#01H</td><td>;选择定时器2为串口1的波特率发生器</td></tr><tr><td>#elif URMD==1</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>AUXR,</td><td>#40H</td><td>;定时器1为1T模式</td></tr><tr><td>MOV</td><td>TMOD,</td><td>#00H</td><td>;定时器1为模式0(16位自动重载)</td></tr><tr><td>MOV</td><td>TL1,</td><td>#0D8H</td><td>;设置波特率重装值(65536-18432000/4/115200)</td></tr><tr><td>MOV</td><td>TH1,</td><td>#0FFH</td><td></td></tr><tr><td>SETB</td><td>TR1</td><td></td><td>;定时器1开始运行</td></tr><tr><td>#else</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>TMOD,</td><td>#20H</td><td>;设置定时器1为8位自动重装载模式</td></tr><tr><td>MOV</td><td>AUXR,</td><td>#40H</td><td>;定时器1为1T模式</td></tr><tr><td>MOV</td><td>TL1,</td><td>#0FBH</td><td>;115200 bps(256-18432000/32/115200)</td></tr><tr><td>MOV</td><td>TH1,</td><td>#0FBH</td><td></td></tr><tr><td>SETB</td><td>TR1</td><td></td><td></td></tr><tr><td>#endif</td><td></td><td></td><td></td></tr><tr><td>RET</td><td></td><td></td><td></td></tr></table>

INIT_SPI: 

<table><tr><td>MOV</td><td>SPDAT, #0</td><td>;初始化SPI数据</td></tr><tr><td>MOV</td><td>SPSTAT, #SPI | WCOL</td><td>;清除SPI状态位</td></tr><tr><td>MOV</td><td>SPCTL, #SPEN</td><td>;从机模式</td></tr><tr><td>RET</td><td></td><td></td></tr></table>

SEND_UART: 

<table><tr><td>JNB</td><td>TI,</td><td>$</td><td>;等待发送完成</td></tr><tr><td>CLR</td><td>TI</td><td></td><td>;清除发送标志</td></tr><tr><td>MOV</td><td>SBUF,</td><td>A</td><td>;发送串口数据</td></tr><tr><td>RET</td><td></td><td></td><td></td></tr></table>

```txt
/ 
```

RECV_UART: 

<table><tr><td>JNB</td><td>RI,</td><td>$</td><td>;等待串口数据接收完成</td></tr><tr><td>CLR</td><td>RI</td><td></td><td>;清除接收标志</td></tr><tr><td>MOV</td><td>A,</td><td>SBUF</td><td>;返回串口数据</td></tr><tr><td>RET</td><td></td><td></td><td></td></tr><tr><td>RET</td><td></td><td></td><td></td></tr></table>

```txt
;END 
```

# 14.5.2 查询方式

# 1. C程序

/* -*/ 

/* --- STC MCU Limited. - -*/ 

/* --- 演示STC 1T 系列单片机 SPI功能(适用互为主从系统，查询方式)- --*/

/* --- 研发顾问QQ：800003751-- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com */ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序- */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可----

/* */ 

//假定测试芯片的工作频率为18.432MHz

#include "reg51.h" 

#define FOSC 18432000L 

#define BAUD (256 - FOSC / 32 / 115200) 

typedef unsigned char BYTE; 

typedef unsigned int WORD; 

typedef unsigned long DWORD; 

#define URMD 0 //0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

sfr T2H 0xd6; //定时器2高8位

sfr T2L $=$ 0xd7; //定时器2低8位

sfr AUXR $=$ 0x8e; //辅助寄存器

sfr SPSTAT $=$ 0xcd; //SPI状态寄存器

#define SPIF 0x80 //SPSTAT.7 

#define WCOL 0x40 //SPSTAT.6 

sfr SPCTL = 0xce; //SPI控制寄存器

#define SSIG 0x80 //SPCTL.7 

#define SPEN 0x40 //SPCTL.6 

#define DORD 0x20 //SPCTL.5 

#define MSTR 0x10 //SPCTL.4 

#define CPOL 0x08 //SPCTL.3 

#define CPHA 0x04 //SPCTL.2 

#define SPDHH 0x00 //CPU_CLK/4 

#define SPDH 0x01 //CPU_CLK/16 

#define SPDL 0x02 //CPU_CLK/64 

#define SPDLL 0x03 //CPU_CLK/128 

<table><tr><td>sfr</td><td>SPDAT =</td><td>0xfc;</td><td>//SPI数据寄存器</td></tr><tr><td>sbit</td><td>SPISS =</td><td>P1^1;</td><td>//SPI从机选择口,连接到其它MCU的SS口
//当SPI为一主多从模式时,
//请使用主机的普通IO口连接到从机的SS口</td></tr><tr><td>void InitUart();</td><td></td><td></td><td></td></tr><tr><td>void InitSPI();</td><td></td><td></td><td></td></tr><tr><td>void SendUart(BYTE dat);</td><td></td><td></td><td>//发送数据到PC</td></tr><tr><td>BYTERecvUart();</td><td></td><td></td><td>//从PC接收数据</td></tr><tr><td>BYTE SPISwap(BYTE dat);</td><td></td><td></td><td>//主机与从机之间交换数据</td></tr><tr><td>|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
\{</td><td></td><td></td><td></td></tr><tr><td>InitUart();</td><td></td><td></td><td>//初始化串口</td></tr><tr><td>InitSPI();</td><td></td><td></td><td>//初始化SPI</td></tr><tr><td>while (1)</td><td></td><td></td><td></td></tr><tr><td>if (RI)</td><td></td><td></td><td></td></tr><tr><td>{</td><td></td><td></td><td></td></tr><tr><td colspan="3">SPCTL = SPEN | MSTR;</td><td>//设置为主机模式</td></tr><tr><td colspan="3">SendUart(SPISwap(RecvUart()));</td><td></td></tr><tr><td colspan="3">SPCTL = SPEN;</td><td>//重置为从机模式</td></tr><tr><td>}</td><td></td><td></td><td></td></tr><tr><td>if (SPSTAT &amp; SPIF)</td><td></td><td></td><td></td></tr><tr><td>{</td><td></td><td></td><td></td></tr><tr><td colspan="3">SPSTAT = SPIF | WCOL;</td><td>//清除SPI状态位</td></tr><tr><td colspan="3">SPDAT = SPDAT;</td><td>//数据从接收缓冲区移到发送缓冲区</td></tr><tr><td>}</td><td></td><td></td><td></td></tr><tr><td>}</td><td></td><td></td><td></td></tr><tr><td>}</td><td></td><td></td><td></td></tr><tr><td>}</td><td></td><td></td><td></td></tr><tr><td>}</td><td></td><td></td><td></td></tr><tr><td>void InitUart()</td><td></td><td></td><td></td></tr><tr><td>{</td><td></td><td></td><td></td></tr><tr><td>SCON =</td><td colspan="2">0x5a;</td><td>//设置串口为8位可变波特率</td></tr><tr><td>URMD ==</td><td colspan="2">0</td><td></td></tr><tr><td>T2L =</td><td colspan="2">0xd8;</td><td>//设置波特率重装值</td></tr><tr><td>T2H =</td><td colspan="2">0xff;</td><td>//115200 bps(65536-18432000/4/115200)</td></tr><tr><td>AUXR =</td><td colspan="2">0x14;</td><td>//T2为1T模式,并启动定时器2</td></tr><tr><td>AUXR |=</td><td colspan="2">0x01;</td><td>//选择定时器2为串口1的波特率发生器</td></tr><tr><td>URMD ==</td><td colspan="2">1</td><td></td></tr><tr><td>AUXR =</td><td colspan="2">0x40;</td><td>//定时器1为1T模式</td></tr><tr><td>TMOD =</td><td colspan="2">0x00;</td><td>//定时器1为模式0(16位自动重载)</td></tr><tr><td>TL1 =</td><td colspan="2">0xd8;</td><td>//设置波特率重装值</td></tr><tr><td>TH1 =</td><td colspan="2">0xff;</td><td>//115200 bps(65536-18432000/4/115200)</td></tr></table>

```c
TR1 = 1; //定时器1开始启动  
#else  
TMOD = 0x20; //设置定时器1为8位自动重装载模式  
AUXR = 0x40; //定时器1为1T模式  
TH1 = TL1 = 0xfb; //115200 bps(256 - 18432000/32/115200)  
TR1 = 1;  
#endif  
}  
//**********  
void InitSPI()  
{SPDAT = 0; //初始化SPI数据SPSTAT = SPIF | WCOL; //清除SPI状态位SPCTL = SPEN; //从机模式  
}  
//**********  
void SendUart(BYTE dat)  
{while (!TI); //等待发送完成TI = 0; //清除发送标志SBUF = dat; //发送串口数据  
}  
//**********  
BYTE RecvUart()  
{while (!RI); //等待串口数据接收完成RI = 0; //清除接收标志return SBUF; //返回串口数据  
}  
//**********  
BYTE SPISwap(BYTE dat)  
{SPISS = 0; //拉低从机的SSSPDAT = dat; //触发SPI发送数据while (!SPSTAT & SPIF); //等待发送完成SPSTAT = SPIF | WCOL; //清除SPI状态位SPISS = 1; //拉高从机的SSreturn SPDAT; //返回SPI数据
```

# 2. 汇编程序

/*- -*/ 

/* --- STC MCU Limited. - -*/ 

/* --- 演示STC 1T 系列单片机 SPI功能(适用互为主从系统，查询方式)- --*/

/* --- 研发顾问QQ：800003751- -*/

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - */ 

/* --- Web: www.STCMCU.com - */ 

/* 如果要在程序中使用此代码,请在程序中注明使用了STC的资料及程序- */

/* 如果要在文章中应用此代码,请在文章中注明使用了STC的资料及程序- */

/*---- 在 Keil C C 开发环境中选择 Intel 8052编译，头文件包含<reg51.h>即可- *

/*- */ 

# //假定测试芯片的工作频率为18.432MHz

#define URMD 0 

//0:使用定时器2作为波特率发生器

//1:使用定时器1的模式0(16位自动重载模式)作为波特率发生器

//2:使用定时器1的模式2(8位自动重载模式)作为波特率发生器

//定时器2高8位

T2H DATA 0D6H 

//定时器2低8位

T2L DATA 0D7H 

;辅助寄存器

AUXR DATA 08EH 

;SPI状态寄存器

SPSTAT DATA 0CDH 

;SPSTAT.7 

SPIF EQU 080H 

;SPSTAT.6 

WCOL EQU 040H 

SPCTL DATA 0CEH 

;SPI控制寄存器

SSIG EQU 080H 

;SPCTL.7 

SPEN EQU 040H 

;SPCTL.6 

DORD EQU 020H 

;SPCTL.5 

MSTR EQU 010H 

;SPCTL.4 

CPOL EQU 008H 

;SPCTL.3 

CPHA EQU 004H 

;SPCTL.2 

SPDHH EQU 000H 

;CPU_CLK/4 

SPDH EQU 001H 

;CPU_CLK/16 

SPDL EQU 002H 

;CPU_CLK/64 

SPDLL EQU 003H 

;CPU_CLK/128 

SPDAT DATA 0CFH 

;SPI数据寄存器

SPISS BIT P1.1 

;SPI从机选择口, 连接到其它MCU的SS口

;当SPI为一主多从模式时,请使用主机的普通IO口连接到从机的SS口

;////////////////////////////////////////////////////////// 

ORG 0000H 

LJMP RESET 

ORG 0100H 

RESET: 

LCALL INIT_UART ;初始化串口

LCALL INIT_SPI 

;初始化SPI

MAIN: 

JB RI, MASTER_MODE 

SLAVE_MODE: 

MOV A, SPSTAT 

JNB ACC.7, MAIN 

MOV SPSTAT, #SPIF | WCOL 

MOV SPDAT, SPDAT 

SJMP MAIN 

;清除SPI状态位

;返回SPI数据

MASTER_MODE: 

MOV SPCTL, #SPEN | MSTR 

LCALL RECV_UART 

LCALL SPI_SWAP 

LCALL SEND_UART 

MOV SPCTL, #SPEN; 

SJMP MAIN 

;设置为主机模式

;接收串口 数据

;发送串口 数据给从机,同时从从机接收SPI数据

;发送SPI数据到PC

;重置为从机模式

;////////////////////////////////////////////////////////// 

INIT_UART: 

MOV SCON, #5AH 

#if URMD $\Longrightarrow = 0$ 

MOV T2L, #0D8H 

MOV T2H, #0FFH 

MOV AUXR, #14H 

ORL AUXR, #01H 

;设置串口 为8位可变波特率

;设置波特率重装值(65536-18432000/4/115200)

;T2为1T模式, 并启动定时器2

;选择定时器2为串口 1的波特率发生器

#elif URMD $= = 1$ 

MOV AUXR, #40H 

MOV TMOD, #00H 

MOV TL1, #0D8H 

MOV TH1, #0FFH 

SETB TR1 

;定时器1为1T模式

;定时器1为模式0(16位自动重载)

;设置波特率重装值(65536-18432000/4/115200)

#else 

MOV TMOD, #20H 

MOV AUXR, #40H 

MOV TL1, #0FBH 

MOV TH1, #0FBH 

SETB TR1 

;定时器1开始运行

#endif 

RET 

;设置定时器1为8位自动重装载模式

;定时器1为1T模式

;115200 bps(256 - 18432000/32/115200) 

;////////////////////////////////////////////////////////// 

INIT_SPI: 

MOV SPDAT, #0 

MOV SPSTAT, #SPIF | WCOL 

MOV SPCTL, #SPEN 

RET 

;初始化SPI数据

;清除SPI状态位

;从机模式

```txt
// 
```

SEND_UART: 

JNB TI, $ 

;等待发送完成

CLR TI 

;清除发送标志

MOV SBUF, A 

;发送串口 数据

RET 

```javascript
//111111111111111111111111111 
```

RECV_UART: 

JNB RI, $ 

;等待串口 数据接收完成

CLR RI 

;清除接收标志

MOV A, SBUF 

;返回串口 数据

RET 

RET 

```javascript
//11111111111111111111111111 
```

SPI_SWAP: 

CLR SPISS 

;拉低从机的SS

MOV SPDAT, A 

;触发SPI发送数据

WAIT: 

MOV A, SPSTAT 

JNB ACC.7, WAIT 

;等待发送完成

MOV SPSTAT, #SPIF | WCOL 

;清除SPI状态位

SETB SPISS 

;拉高从机的SS

MOV A, SPDAT 

;返回SPI数据

RET 

```javascript
//11111111111111111111111111 
```

END 

# 14.6 利用SPI控制74HC595驱动8位数码管及测试程序(C和汇编)

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/541114fc2bf1c1ed967c6611dbfc30748971c1ae3377b28e07ea701687003ef4.jpg)


下面是用STC的MCU的SPI方式控制74HC595驱动8位数码管(串口 扩展，3根线)的测试程序：

# 1. C程序

/*- -*/ 

/* --- STC MCU International Limited - -*/ 

/* --- STC 1T Series MCU Programme Demo - -*/ 

/* --- Fax: 86-755-82944243 -*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com - --*/ 

/* If you want to use the program or the program referenced in the */ 

/* article, please specify in which data and procedures from STC */ 

/*- -*/ 

/* 本程序经过测试完全正常, 不提供 电话技术支持, 如不能理解, 请自行补充相关基础. */

/************* 本程序功能说明 **************

用STC的MCU的SPI方式控制74HC595驱动8位数码管。

用户可以修改宏来选择时钟频率, 可以修改寄存器定义是STC12C5A60S2系列 还是 STC12C5628ADSTC12C5410AD STC12C4052AD系列.

用户可以在显示函数里修改成共阴或共阳.推荐尽量使用共阴数码管.

显示效果为: 8个数码管循环显示0,1,2...,A,B..F,消隐.

******************************************* 

#include "reg52.h" 

/****************************** 用户定义宏 ***********************************/

#define MAIN_Fosc 11059200UL //定义主时钟

//#define MAIN_Fosc 22118400UL //定义时钟

/*****************************************************************************/ 

sfr SPSTAT $=$ 0xCD; //STC12C5A60S2系列

sfr SPCTL $=$ 0xCE; //STC12C5A60S2系列

sfr SPDAT $=$ 0xCF; //STC12C5A60S2系列

/* 

sfr SPSTAT = 0x84; //STC12C5628AD STC12C5410AD STC12C4052AD系列

sfr SPCTL = 0x85; //STC12C5628AD STC12C5410AD STC12C4052AD系列

sfr SPDAT = 0x86; //STC12C5628AD STC12C5410AD STC12C4052AD系列

*/ 

/******************** 下面的宏自动生成, 用户不可修改 **************************/

#define Timer0_Reload (MAIN_Fosc / 12000) 

/*****************************************************************************/ 

```c
//SPCTL SPI控制寄存器  
//7 6 5 4 3 2 1 0 Reset Value  
//SSIG SPEN DORD MSTR CPOL CPHA SPR1 SPR0 0x00  
#define SSIG 1 //1:忽略SS脚，由MSTR位决定主机还是从机  
//0:SS脚用于决定主从机。  
#define SPEN 1 //1:允许SPI，  
//0:禁止SPI，所有SPI管脚均为普通IO  
#define DORD 0 //1:LSB先发，  
//0:MSB先发  
#define MSTR 1 //1:设为主机  
//0:设为从机  
#define CPOL 1 //1:空闲时SCLK为高电平，  
//0:空闲时SCLK为低电平  
#define CPHA 1 //  
#define SPR1 0 //SPR1,SPRO 00:fosc/4，01:fosc/16  
#define SPR0 0 //10:fosc/64，11:fosc/128  
#define SPEED_4 0 //fosc/4  
#define SPEED_16 1 //fosc/16  
#define SPEED_64 2 //fosc/64  
#define SPEED_128 3 //fosc/128
```

//SPSTATSPI状态寄存器

```c
//7 6 5 4 3 2 1 0 Reset Value  
// SPIF WCOL - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
#define SPIF 0x80 //SPI传输完成标志。写入1清0。  
#define WCOL 0x40 //SPI写冲突标志。写入1清0。
```

```c
********** 本地常量声明  
unsigned char code_t_display[] = {  
// 0 1 2 3 4 5 6 7 8 9 A B C D E F 消隐  
0x3F,0x06,0x5B,0x4F,0x66,0x6D,0x7D,0x07,0x7F,0x6F,0x77,0x7C,0x39,0x5E,0x79,0x71,0x00};  
//段码
```

unsigned char code T_COM[]={0x01,0x02,0x04,0x08,0x10,0x20,0x40,0x80}; //位码

```c
/******本地变量声明**********  
sbit SPI_SCL = P1^5; //SPI同步时钟 P_HC595_SRCLK pin 11 SRCLK Shift data clock  
//sbit SPI_MISO = P1^6; //SPI同步数据输入 本例不用  
sbit SPI_MOSI = P1^3; //SPI同步数据输出 P_HC595_SER pin 14 SER data input  
sbit P_HC595_RCLK = P4^1; //SPI片选(任意IO) pin 12 RCLk store (latch) clock  
unsigned char LED8[8]; //显示缓冲  
unsigned char display_index; //显示位索引  
bit B_1ms; //1ms标志
```

void main(void) //主函数  
{ unsigned char i,k; unsigned int j; SPCTL $=$ (SSIG<<7)+(SPEN<<6)+(DORD<<5)+(MSTR<<4)+(CPOL<<3)+(CPHA<<2) +SPEED_4; //配置SPI TMOD 0x01; TH0 (65536-Timer0_Reload)/256; TL0 (65536-Timer0_Reload)%256; ET0 1; TR0 1; EA 1; for(i=0;i<8;i++) LED8[i] = 0x10; j = 0; k = 0; while(1) { while(!B_1ms); //等待1ms到 B_1ms = 0; if(+j >= 500) //500ms到 { j = 0; for(i=0;i<8;i++) LED8[i] = k; if(+k > 0x10) k = 0; //8个数码管循环显示0,1,2...A,B..F,消隐. } }   
}   
/**********/   
/**********/   
void SPI_SendByte(unsigned char dat) //SPI发送一个字节 { SPSTAT = SPIF + WCOL; //清0SPIF和WCOL标志 SPDAT = dat; //发送一个字节 while((SPSTAT & SPIF) == 0); //等待发送完成 SPSTAT = SPIF + WCOL; //清0SPIF和WCOL标志 }   
}   
/**********/   
void DisplayScan(void) //显示扫描函数 { SPI_SendByte(~T_COM(display_index); //共阴 输出位码 SPI_SendByte(t_display[LED8[display_index]); //共阴 输出段码 SPI_SendByte(T_COM(display_index); //共阳 输出位码

SPI_SendByte(~t_display[LED8(display_index]); //共阳 输出段码P_HC595_RCLK = 1;P_HC595_RCLK = 0; //锁存输出数据if( $^+$ display_index $\geqslant$ 8) display_index $= 0$ //8位结束回0  
}  
**********  
void timer0(void) interrupt 1 //Timer0 1ms中断函数THO $=$ (65536-Timer0_Reload)/256; //重装定时值TL0 $=$ (65536-Timer0_Reload)%256;DisplayScan(); //1ms扫描显示一位B_1ms $= 1$ //1ms标志

# 2. 汇编程序

;/*- -*/ 

;/* --- STC MCU International Limited - -*/ 

;/* --- STC 1T Series MCU Programme Demo --*/ 

;/* --- Fax: 86-755-82944243 - -*/ 

;/* --- Tel: 86-755-82948412 -*/ 

;/* --- Web: www.STCMCU.com - -*/ 

;/* If you want to use the program or the program referenced in the */ 

;/* article, please specify in which data and procedures from STC */ 

;/*- -*/ 

;/* 本程序经过测试完全正常, 不提供 电话技术支持, 如不能理解, 请自行补充相关基础. */

·/************* 本程序功能说明 **************

;用STC的MCU的SPI方式控制74HC595驱动8位数码管。

;用户可以修改宏来选择时钟频率, 可以修改寄存器定义是STC12C5A60S2系列 还是 STC12C5628ADSTC12C5410AD STC12C4052AD系列.

;用户可以在显示函数里修改成共阴或共阳.推荐尽量使用共阴数码管.

;显示效果为: 8个数码管循环显示0,1,2...,A,B..F,消隐.

;******************************************/ 

;定义Timer0 1ms重装值

D_Timer0_Reload EQU (0-921) ;1ms for 11.0592MHZ 

;D_Timer0_Reload EQU (0-1832) ;1ms for 22.1184MHZ 

SPSTAT DATA 0CDH ;STC12C5A60S2系列

SPCTL DATA 0CEH ;STC12C5A60S2系列

SPDAT DATA 0CFH ;STC12C5A60S2系列

;SPSTAT DATA 084H ;STC12C5628AD STC12C5410AD STC12C4052AD系列

;SPCTL DATA 085H ;STC12C5628AD STC12C5410AD STC12C4052AD系列

;SPDAT DATA 086H ;STC12C5628AD STC12C5410AD STC12C4052AD系列

·/************* 本地变量声明 **************/

SPI_SCL BIT P1^5 ;SPI同步时钟 P_HC595_SRCLK pin11 SRCLK Shift data clock

;SPI_MISO BIT P1^6 ;SPI同步数据输入 本例不用

SPI_MOSI BIT P1^3 ;SPI同步数据输出 P_HC595_SER pin 14 SER data input

P_HC595_RCLK BIT P4^1 ;SPI片选(任意IO) pin 12 RCLk store (latch) clock

LED8 EQU 030H 

display_index DATA 038H 

FLAG0 DATA 20H 

B_1ms BIT FLAG0.0 

<table><tr><td colspan="2">;SPCTL</td><td colspan="6">SPI控制寄存器</td></tr><tr><td>;</td><td>7 6 5</td><td colspan="3">4 3 2 1 0</td><td colspan="3">Reset Value</td></tr><tr><td>;</td><td>SSIG</td><td>SPEN</td><td>DORD</td><td>MSTR</td><td>CPOL</td><td>CPHA</td><td>SPR1 SPR0 0x00</td></tr><tr><td rowspan="2">SSIG</td><td rowspan="2">EQU</td><td rowspan="2">1</td><td rowspan="2"></td><td rowspan="2"></td><td colspan="3">;1:忽略SS脚,由MSTR位决定主机还是从机</td></tr><tr><td colspan="3">;0:SS脚用于决定主从机。</td></tr><tr><td rowspan="2">SPEN</td><td rowspan="2">EQU</td><td rowspan="2">1</td><td rowspan="2"></td><td rowspan="2"></td><td colspan="3">;1:允许SPI,</td></tr><tr><td colspan="3">;0:禁止SPI,所有SPI管脚均为普通IO</td></tr><tr><td rowspan="2">DORD</td><td rowspan="2">EQU</td><td rowspan="2">0</td><td rowspan="2"></td><td rowspan="2"></td><td colspan="3">;1:LSB先发,</td></tr><tr><td colspan="3">;0:MSB先发</td></tr><tr><td rowspan="2">MSTR</td><td rowspan="2">EQU</td><td rowspan="2">1</td><td rowspan="2"></td><td rowspan="2"></td><td colspan="3">;1:设为主机</td></tr><tr><td colspan="3">;0:设为从机</td></tr><tr><td rowspan="2">CPOL</td><td rowspan="2">EQU</td><td rowspan="2">1</td><td rowspan="2"></td><td rowspan="2"></td><td colspan="3">;1:空闲时SCLK为高电平,</td></tr><tr><td colspan="3">;0:空闲时SCLK为低电平</td></tr><tr><td>CPHA</td><td>EQU</td><td>1</td><td></td><td></td><td colspan="3">;</td></tr><tr><td>SPR1</td><td>EQU</td><td>0</td><td></td><td></td><td colspan="3">;SPR1,SPRO 00:fosc/4, 01:fosc/16</td></tr><tr><td>SPRO</td><td>EQU</td><td>0</td><td></td><td></td><td colspan="3">; 10:fosc/64, 11:fosc/128</td></tr><tr><td colspan="2">SPEED_4</td><td>EQU</td><td>0</td><td></td><td colspan="3">;fosc/4</td></tr><tr><td colspan="2">SPEED_16</td><td>EQU</td><td>1</td><td></td><td colspan="3">;fosc/16</td></tr><tr><td colspan="2">SPEED_64</td><td>EQU</td><td>2</td><td></td><td colspan="3">;fosc/64</td></tr><tr><td colspan="2">SPEED_128</td><td>EQU</td><td>3</td><td></td><td colspan="3">;fosc/128</td></tr><tr><td colspan="2">;SPSTAT</td><td colspan="6">SPI状态寄存器</td></tr><tr><td>;</td><td>7 6 5 4</td><td colspan="2">3 2 1 0</td><td colspan="4">Reset Value</td></tr><tr><td>;</td><td>SPIF</td><td>WCOL</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td></tr><tr><td>SPIF</td><td>EQU</td><td>80H</td><td></td><td></td><td colspan="3">;SPI传输完成标志。写入1清0。</td></tr><tr><td>WCOL</td><td>EQU</td><td>40H</td><td></td><td></td><td colspan="3">;SPI写冲突标志。写入1清0。</td></tr></table>

******************************************************************** 

******************************************************************** 

<table><tr><td></td><td>ORG</td><td>00H</td><td>;reset</td></tr><tr><td></td><td>LJMP</td><td>F_MAINFUNC</td><td></td></tr><tr><td></td><td>ORG</td><td>03H</td><td>;INT0 interrupt</td></tr><tr><td>;</td><td>LJMP</td><td>F_INT0_interrupt</td><td></td></tr><tr><td></td><td>RETI</td><td></td><td></td></tr><tr><td></td><td>ORG</td><td>0BH</td><td>;Timer0 interrupt</td></tr><tr><td></td><td>LJMP</td><td>F_Timer0_interrupt</td><td></td></tr><tr><td></td><td>RETI</td><td></td><td></td></tr><tr><td></td><td>ORG</td><td>13H</td><td>;INT1 interrupt</td></tr><tr><td>;</td><td>LJMP</td><td>F_INT1_interrupt</td><td></td></tr><tr><td></td><td>ORG</td><td>1BH</td><td>;Timer1 interrupt</td></tr><tr><td>;</td><td>LJMP</td><td>F_Timer1_interrupt</td><td></td></tr><tr><td></td><td>RETI</td><td></td><td></td></tr></table>

******************************************************************** 

******************************************************************* 

```javascript
\*/\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```


F_MAIN_FUNC:


```asm
MOV SP, #50H  
MOV SPCTL, #(SSIG SHL 7) + (SPEN SHL 6) + (DORD SHL 5) + (MSTR SHL 4) + (CPOL SHL 3) + (CPHA SHL 2) + SPEED_4; //配置SPI
```

```txt
MOV TMOD, #01H ;Timer 0 config as 16bit timer, 12T  
MOV TH0, #HIGH D_Timer0_Reload ;1ms 
```

```txt
MOV TL0, #LOW D_Timer0_Reload 
```

```txt
SETB ETO 
```

```txt
SETB TR0 
```

```txt
SETB EA 
```

```asm
MOV R0, #LED8 
```


L_InitLoop1:


```txt
MOV @R0, #10H ;上电消隐
```

```txt
INC R0 
```

```txt
MOV A, R0 
```

```txt
CJNE A, #(LED8+8), L_InitLoop1 
```

```asm
MOV R2, #HIGH 500 ;500ms 
```

```txt
MOV R3, #LOW 500 
```

```asm
MOV R4, #0 
```


L_MainLoop:


```txt
JNB B_1ms, $ ;等待1ms到
```

```txt
CLR B_1ms ;清1ms标志
```

```txt
MOV A, R3 
```

```txt
CLR C 
```

```txt
SUBB A, #1 
```

```txt
MOV R3, A 
```

```txt
MOV A, R2 
```

```txt
SUBB A, #0 
```

```txt
MOV R2, A 
```

```txt
ORL A, R3 
```

```txt
JNZ L(MainLoop 
```

```asm
MOV R2, #HIGH 500 ;500ms 
```

```txt
MOV R3, #LOW 500 
```

```txt
MOV R0, #LED8 ;刷新显示
```


L_OptionLoop1:


```txt
MOV A, R4 
```

```txt
MOV @R0, A ; 
```

```txt
INC R0 
```

```txt
MOV A, R0 
```

```txt
CJNE A, #(LED8+8), LOPTIONLoop1 
```

```txt
INC R4 
```

MOV A, R4 

CJNE A, #11H,L_MainLoop 

MOV R4, #0 

SJMP L_MainLoop 

;8个数码管循环显示0,1,2...,A,B..F,消隐.

;/**********************************************/ 

t_display: 

;0 1 2 3 4 5 6 7 8 9 A B C D E F 消隐

DB 03FH,006H,05BH,04FH,066H,06DH,07DH,007H,07FH,06FH,077H,07CH,039H,05EH,079H,071H,000H;段码

T_COM: 

DB 01H,02H,04H,08H,10H,20H,40H,80H 

;位码

;/**********************************************/ 

F_SPI_SendByte: 

MOV SPSTAT, #(SPIF + WCOL) 

MOV SPDAT, A 

;SPI发送一个字节

;清0 SPIF和WCOL标志

L_SPI_SendByteWait: 

MOV A, SPSTAT 

ANL A, #SPIF 

JZ L_SPI_SendByteWait 

MOV SPSTAT, #(SPIF $^ +$ WCOL) 

RET 

;清0 SPIF和WCOL标志

·/**********************************************/ 

F_DisplayScan: 

MOV DPTR, #T_COM 

MOV A, display_index 

MOVC A, @A+DPTR 

CPL A 

LCALL F_SPI_SendByte 

;显示扫描函数

;共阴 共阳时注释掉本句

MOV DPTR, #t_display 

MOV A, #LED8 

ADD A, display_index 

MOV R0, A 

MOV A, @R0 

MOVC A, @A+DPTR 

CPL A 

LCALL F_SPI_SendByte 

SETB P_HC595_RCLK 

CLR P_HC595_RCLK 

INC display_index 

MOV A, display_index 

CJNE A, #8,L_QuitDisplayScan 

MOV display_index, #0 

L_QuitDisplayScan: 

RET 

;共阳 共阴时注释掉本句

;输出段码

;锁存输出数据

;8位结束回0

******************************************************************** 

******************************************************************** 

F_Timer0_interrupt: 

PUSH PSW 

PUSH ACC 

MOV A, R0 

PUSH ACC 

PUSH DPH 

PUSH DPL 

MOV TH0, #HIGH D_Timer0_Reload 

MOV TL0, #LOW D_Timer0_Reload 

LCALL F_DisplayScan 

SETB B_1ms 

L_QuitT0Interrupt: 

POP DPL 

POP DPH 

POP ACC 

MOV R0, A 

POP ACC 

POP PSW 

RETI 

END 

;Timer0 1ms中断函数

;现场保护

;1ms 重装定时值

;1ms扫描显示一位

;1ms标志

;现场恢复

# 14.7 利用SPI接口扩展12位ADC(TLC2543)的应用线路图

TLC2543是 精度19 转挽器参考

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5e5e23143b8d36c6d07a96104d10dbfea545c9de27ae737bd61a451dada4ca3e.jpg)


# 14.8 利用STC15系列单片机SPI的主模式读写外部串行Flash

# 14.8.1 利用STC15系列SPI的主模式读写外部串行Flash的参考电路图


Flash控制部分参考电路图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/1470cf709c9432c27913aa749dbdab30cea720b55b9221be5ee2e2a586f240df.jpg)


# 14.8.2 利用STC15系列SPI的主模式读写外部串行Flash的测试程序

# 14.8.2.1 通过中断方式利用SPI的主模式读写外部串行Flash的测试程序(C和汇编)

# 1、C语言程序

/*- -*/ 

/* --- STC MCU Limited -*/ 

/* --- STC15W4K60S4 系列 SPI的主模式读写外部串行 Flash举例(中断方式)-------*/

/* --- Mobile: (86)13922805190 --- */ 

/* --- Fax: 86-755-82905966 ---------- -*/ 

/* --- Tel: 86-755-82948412 */ 

/* --- Web: www.STCMCU.com -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/*- -*/ 

//本示例在Keil开发环境下请选择Intel的8058芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

//本示例所读写的目标Flash为PM25LV040,本代码已使用U7编程器测试通过

#include "reg51.h" 

typedef bit BOOL; 

typedef unsigned char BYTE; 

typedef unsigned short WORD; 

typedef unsigned long DWORD; 

#define FOSC 18432000L 

#define BAUD (65536 - FOSC / 4 / 115200) 

#define NULL 0 

#define FALSE 0 

#define TRUE 1 

sfr AUXR = 0x8e; //辅助寄存器

sfr P_SW1 = 0xa2; //外设功能切换寄存器1

#define SPI_S0 0x04 

#define SPI_S1 0x08 

sfr SPSTAT = 0xcd; //SPI状态寄存器

#define SPIF 0x80 //SPSTAT.7 

#define WCOL 0x40 //SPSTAT.6 

sfr SPCTL = 0xce; //SPI控制寄存器

#define SSIG 0x80 //SPCTL.7 

#define SPEN 0x40 //SPCTL.6 

#define DORD 0x20 //SPCTL.5 

#define MSTR 0x10 //SPCTL.4 

#define CPOL 0x08 //SPCTL.3 

#define CPHA 0x04 //SPCTL.2 

#define SPDHH 0x00 //CPU_CLK/4 

#define SPDH 0x01 //CPU_CLK/16 

#define SPDL 0x02 //CPU_CLK/64 

#define SPDLL 0x03 //CPU_CLK/128 

sfr SPDAT = 0xcf; //SPI数据寄存器

sbit SS = P2^4; //SPI的SS脚,连接到Flash的CE

sfr IE2 0xAF; //中断控制寄存器2

#define ESPI 0x02 //IE2.1 

#define SFC_WREN 0x06 //串行 Flash命令集

#define SFC_WRDI 0x04 

#define SFC_RDSR 0x05 

#define SFC_WRSR 0x01 

#define SFC_READ 0x03 

#define SFC_FASTREAD 0x0B 

#define SFC_RDID 0xAB 

#define SFC_PAGEPROG 0x02 

#define SFC_RDCR 0xA1 

#define SFC_WRCR 0xF1 

#define SFC_SECTORER 0xD7 

#define SFC_BLOCKER 0xD8 

#define SFC_CHIPER 0xC7 

void InitUart(); 

void SendUart(BYTE dat); 

void InitSpi(); 

BYTE SpiShift(BYTE dat); 

BOOL FlashCheckID(); 

BOOL IsFlashBusy(); 

void FlashWriteEnable(); 

void FlashErase(); 

void FlashRead(DWORD addr, DWORD size, BYTE *buffer); 

void FlashWrite(DWORD addr, DWORD size, BYTE *buffer); 

#define BUFFER_SIZE 1024 

#define TEST_ADDR 0 

//缓冲区大小

//Flash测试地址

BYTE xdata g_Buffer[BUFFER_SIZE]; 

BOOL g_fFlashOK; 

BOOL g_fSpiBusy; 

//Flash读写缓冲区

//Flash状态

//SPI的工作状态

void main() 

{ int i; 

//初始化Flash状态

g_fFlashOK $=$ FALSE; 

g_fSpiBusy $=$ FALSE; 

//初始化串口 和SPI

InitUart(); 

InitSpi(); 

//使能SPI传输中断

IE2 $| =$ ESPI; 

$\mathrm { E A } = 1$ 

//检测Flash状态

FlashCheckID(); 

//擦除Flash

FlashErase(); 

//读取测试地址的数据

FlashRead(TEST_ADDR, BUFFER_SIZE, g_Buffer); 

//发送到串口

for (i=0; i<BUFFER_SIZE; i++) SendUart(g_Buffer[i]); 

//修改置缓冲区for $(\mathrm{i} = 0$ ;i<BUFFER_SIZE; $\mathrm{i + + )}$ g_Buffer[i] $= \mathrm{i} > > 2$ //将缓冲区的数据写到Flash中FlashWrite(TEST_ADDR,BUFFER_SIZE,g_Buffer);//读取测试地址的数据FlashRead(TEST_ADDR, BUFFER_SIZE,g_Buffer);//发送到串口for $(\mathrm{i} = 0$ ;i<BUFFER_SIZE; $\mathrm{i + + )}$ SendUart(g_Buffer[i]);FlashErase();//读取测试地址的数据FlashRead(TEST_ADDR,BUFFER_SIZE,g_Buffer);//发送到串口for $(\mathrm{i} = 0$ ;i<BUFFER_SIZE; $\mathrm{i + + )}$ SendUart(g_Buffer[i]);//修改置缓冲区for $(\mathrm{i} = 0$ ;i<BUFFER_SIZE; $\mathrm{i + + )}$ g_Buffer[i]=255-(i>>2);//将缓冲区的数据写到Flash中FlashWrite(TEST_ADDR,BUFFER_SIZE,g_Buffer);//读取测试地址的数据FlashRead(TEST_ADDR,BUFFER_SIZE,g_Buffer);//发送到串口for $(\mathrm{i} = 0$ ;i<BUFFER_SIZE; $\mathrm{i + + )}$ SendUart(g_Buffer[i]);while (1);  
}  
/**********  
SPI中断服务程序  
**********  
void spi_isr() interrupt 9 using 1{SPSTAT $=$ SPI|WCOL; //清除SPI状态位g_fSpiBusy $=$ FALSE;  
}  
/**********  
串口初始化  
入口参数：无  
出口参数：无  
**********  
void InitUart()

{ AUXR $= 0\mathrm{x}40$ //设置定时器1为1T模式 TMOD $= 0\mathrm{x}00$ //定时器1为16位重载模式 TH1 $\equiv$ BAUD>>8; //设置波特率 TL1 $\equiv$ BAUD; TR1 $= 1$ SCON $= 0\mathrm{x}5\mathrm{a}$ //设置串口为8位数据位，波特率可变模式

```txt
/***** 
```

发送数据到串口

入口参数:

dat : 准备发送的数据

出口参数: 无

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

void SendUart(BYTE dat)  
{ while(!TI); //等待上一个数据发送完成 $\mathrm{TI} = 0$ //清除发送完成标志 SBUF $=$ dat; //触发本次的数据发送

```txt
/****** 
```

SPI初始化

入口参数: 无

出口参数: 无

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

void InitSpi()   
{ ACC $=$ P_SW1; //切换到第一组SPI ACC $\& =$ \~(SPI_S0|SPI_S1); //SPI_S0=0 SPI_S1=0 P_SW1 $=$ ACC; //P1.2/SS,P1.3/MOSI,P1.4/MISO,P1.5/SCLK) ACC $=$ P_SW1; //可用于测试U7,U7使用的是第二组SPI控制Flash ACC $\& =$ \~(SPI_S0|SPI_S1); //SPI_S0=1 SPI_S1=0 ACC $|\equiv$ SPI_S0; //P2.4/SS_2,P2.3/MOSI_2,P2.2/MISO_2,P2.1/SCLK_2) P_SW1 $=$ ACC;   
// ACC $=$ P_SW1; //切换到第三组SPI ACC $\& =$ \~(SPI_S0|SPI_S1); //SPI_S0=0 SPI_S1=1 ACC $|\equiv$ SPI_S1; //P5.4/SS_3,P4.0/MOSI_3,P4.1/MISO_3,P4.3/SCLK_3) P_SW1 $=$ ACC;

SPSTAT $=$ SPIF|WCOL; //清除SPI状态

$\mathrm{SS} = 1$ $\mathrm{SPCTL} = \mathrm{SSIG}|\mathrm{SPEN}|\mathrm{MSTR};$ //设置SPI为主模式

```txt
/****** 
```

使用SPI方式与Flash进行数据交换

入口参数:

dat : 准备写入的数据

出口参数:

从Flash中读出的数据

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

```txt
BYTE SpiShift(BYTE dat)  
{  
    g_fSpiBusy = TRUE;  
    SPDAT = dat; //触发SPI发送  
    while (g_fSpiBusy); //等待SPI数据传输完成  
    return SPDAT;
```

```txt
/***** 
```

检测Flash是否准备就绪

入口参数: 无

出口参数:

0 : 没有检测到正确的Flash

1 : Flash准备就绪

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

```txt
BOOL FlashCheckID()
{
BYTE dat1, dat2;
SS = 0;
SpiShift(SFC_RDID); //发送读取ID命令
SpiShift(0x00); //空读3个字节
SpiShift(0x00);
SpiShift(0x00);
dat1 = SpiShift(0x00); //读取制造商ID1
SpiShift(0x00); //读取设备ID
dat2 = SpiShift(0x00); //读取制造商ID2
SS = 1;
```

```txt
//检测是否为PM25LVxx系列的Flash  
g_fFlashOK = ((dat1 == 0x9d) && (dat2 == 0x7f));  
return g_fFlashOK;
```

```txt
/***** 
```

检测Flash的忙状态

入口参数: 无

出口参数:

0 : Flash处于空闲状态

1 : Flash处于忙状态

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

```c
BOOL IsFlashBusy()  
{  
    BYTE dat;  
    SS = 0;  
    SpiShift(SFC_RDSR); //发送读取状态命令  
    dat = SpiShift(0); //读取状态  
    SS = 1;  
    return (dat & 0x01); //状态值的Bit0即为忙标志  
}
```

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

使能Flash写命令

入口参数: 无

出口参数: 无

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

```txt
voidFlashWriteEnable()  
{ while(IsFlashBusy())； //Flash忙检测SS=0; SpiShift(SFC_WREN); //发送写使能命令SS=1;   
}
```

```txt
/***** 
```

擦除整片Flash

入口参数: 无

出口参数: 无

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

```txt
void FlashErase()  
{ if (g_fFlashOK) { FlashWriteEnable(); //使能Flash写命令 SS = 0;
```

$\begin{array}{rl} & {\mathrm{SpiShift(SFC_CHIPER);}}\\ & {\mathrm{SS = 1};}\\ & \end{array}$ //发送片擦除命令  
1  
1  
/******  
从Flash中读取数据  
入口参数：addr：地址参数size：数据块大小buffer：缓冲从Flash中读取的数据  
出口参数：无  
**********  
void FlashRead(DWORD addr, DWORD size, BYTE *buffer)  
{if(g_fFlashOK)while(IsFlashBusy();//Flash忙检测SS=0;SpiShift(SFC_FASTREAD);//使用快速读取命令SpiShift((BYTE*)&addr)[1]);//设置起始地址SpiShift((BYTE*)&addr)[2]);SpiShift((BYTE*)&addr)[3]);SpiShift(0);//需要空读一个字节while(size){\*buffer $=$ SpiShift(0);//自动连续读取并保存addr++;buffer++;size--;1SS=1;1

************************************************* 

写数据到Flash中

入口参数:

addr : 地址参数

size : 数据块大小

buffer : 缓冲需要写入Flash的数据

出口参数: 无

************************************************* 

```txt
void FlashWrite(DWORD addr, DWORD size, BYTE *buffer)  
{ if (g_fFlashOK) while (size) { FlashWriteEnable(); //使能Flash写命令 SS = 0; SpiShift(SFC_PAGEPROG); //发送页编程命令 SpiShift((BYTE *)&addr)[1]); //设置起始地址 SpiShift((BYTE *)&addr)[2]); SpiShift((BYTE *)&addr)[3]); while (size) { SpiShift(*buffer); //连续页内写 addr++; buffer++; size--; if ((addr & 0xff) == 0) break; } SS = 1; }
```

# 2、汇编程序

/*- -*/ 

/* --- STC MCU Limited - -*/ 

/* --- STC15W4K60S4 系列 SPI的主模式读写外部串行 Flash举例(中断方式)-------*/

/* --- Mobile: (86)13922805190 -*/ 

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com - --*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/*- -*/ 

//本示例在Keil开发环境下请选择Intel的8058芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

//本示例所读写的目标Flash为PM25LV040,本代码已使用U7编程器测试通过

//BAUD EQU 0FFE8H //(65536 - 11059200 / 4 / 115200) 

BAUD EQU 0FFD8H //(65536 - 18432000 / 4 / 115200) 

//BAUD EQU 0FFD0H //(65536 - 22118400 / 4 / 115200) 

AUXR DATA 08EH //辅助寄存器

P_SW1 DATA 0A2H //外设功能切换寄存器1

SPI_S0 EQU 04H 

SPI_S1 EQU 08H 

SPSTAT DATA 0CDH //SPI状态寄存器

SPIF EQU 080H //SPSTAT.7 

WCOL EQU 040H //SPSTAT.6 

SPCTL DATA 0CEH //SPI控制寄存器

SSIG EQU 080H //SPCTL.7 

SPEN EQU 040H //SPCTL.6 

DORD EQU 020H //SPCTL.5 

MSTR EQU 010H //SPCTL.4 

CPOL EQU 008H //SPCTL.3 

CPHA EQU 004H //SPCTL.2 

SPDHH EQU 000H //CPU_CLK/4 

SPDH EQU 001H //CPU_CLK/16 

SPDL EQU 002H //CPU_CLK/64 

SPDLL EQU 003H //CPU_CLK/128 

SPDAT DATA 0CFH //SPI数据寄存器

SS BIT P2.4 //SPI的SS脚,连接到Flash的CE

IE2 DATA 0AFH //中断控制寄存器2

<table><tr><td>ESPI</td><td>EQU</td><td>002H</td><td>//IE2.1</td></tr><tr><td>SFC_WREN</td><td>EQU</td><td>0x06</td><td>//串行Flash命令集</td></tr><tr><td>SFC_WRDI</td><td>EQU</td><td>0x04</td><td></td></tr><tr><td>SFC_RDSR</td><td>EQU</td><td>0x05</td><td></td></tr><tr><td>SFC_WRSR</td><td>EQU</td><td>0x01</td><td></td></tr><tr><td>SFC_READ</td><td>EQU</td><td>0x03</td><td></td></tr><tr><td>SFC_FASTREAD</td><td>EQU</td><td>0x0B</td><td></td></tr><tr><td>SFC_RDID</td><td>EQU</td><td>0xAB</td><td></td></tr><tr><td>SFC_PAGEPROG</td><td>EQU</td><td>0x02</td><td></td></tr><tr><td>SFC_RDCR</td><td>EQU</td><td>0xA1</td><td></td></tr><tr><td>SFC_WRCR</td><td>EQU</td><td>0xF1</td><td></td></tr><tr><td>SFC_SECTORER</td><td>EQU</td><td>0xD7</td><td></td></tr><tr><td>SFC_BLOCKER</td><td>EQU</td><td>0xD8</td><td></td></tr><tr><td>SFC_CHIPER</td><td>EQU</td><td>0xC7</td><td></td></tr><tr><td>BUFFER_SIZE</td><td>EQU</td><td>1024</td><td>//缓冲区大小</td></tr><tr><td>TEST_ADDR</td><td>EQU</td><td>0</td><td>//Flash测试地址</td></tr><tr><td>G BUFFER</td><td>XDATA</td><td>0</td><td>//Flash读写缓冲区</td></tr><tr><td>G_FLASHOK</td><td>BIT</td><td>20H.0</td><td>//Flash状态</td></tr><tr><td>G_SPIBUSY</td><td>BIT</td><td>20H.1</td><td>//SPI的工作状态</td></tr><tr><td>ADDR</td><td>DATA</td><td>21H</td><td>//地址变量,3字节</td></tr><tr><td>SIZE</td><td>DATA</td><td>24H</td><td>//大小变量,3字节</td></tr><tr><td>ORG</td><td>0000H</td><td></td><td></td></tr><tr><td>LJMP</td><td>MAIN</td><td></td><td></td></tr><tr><td>ORG</td><td>004BH</td><td></td><td></td></tr><tr><td>LJMP</td><td>SPI_ISR</td><td></td><td></td></tr><tr><td>ORG</td><td>0100H</td><td></td><td></td></tr><tr><td>MAIN:</td><td></td><td></td><td></td></tr><tr><td>MOV</td><td>SP, #3FH</td><td></td><td></td></tr><tr><td>CLR</td><td>G_FLASHOK</td><td></td><td>//初始化Flash状态</td></tr><tr><td>CLR</td><td>G_SPIBUSY</td><td></td><td></td></tr><tr><td>LCALL</td><td>INITUART</td><td></td><td>//初始化串口和SPI</td></tr><tr><td>LCALL</td><td>INITSPI</td><td></td><td></td></tr><tr><td>ORL</td><td>IE2, #ESPI</td><td></td><td>//使能SPI中断</td></tr><tr><td>SETB</td><td>EA</td><td></td><td></td></tr></table>

<table><tr><td>LCALL</td><td>FLASHCHECKID</td><td></td><td>//检测Flash状态</td><td></td></tr><tr><td>LCALL</td><td>FLASHERASE</td><td></td><td>//擦除Flash</td><td></td></tr><tr><td>MOV</td><td>ADDR+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>ADDR+1,</td><td>#HIGH TEST_ADDR</td><td></td><td></td></tr><tr><td>MOV</td><td>ADDR+0,</td><td>#LOW TEST_ADDR</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+1,</td><td>#HIGH BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+0,</td><td>#LOW BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>DPTR,</td><td>#G_BUFFER</td><td></td><td></td></tr><tr><td>LCALL</td><td>FLASHREAD</td><td></td><td>//读取测试地址的数据</td><td></td></tr><tr><td>MOV</td><td>SIZE+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+1,</td><td>#HIGH BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+0,</td><td>#LOW BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>DPTR,</td><td>#G_BUFFER</td><td></td><td></td></tr><tr><td>LCALL</td><td>SENDUARTBLOCK</td><td></td><td>//发送到串口</td><td></td></tr><tr><td>MOV</td><td>SIZE+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+1,</td><td>#HIGH BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+0,</td><td>#LOW BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>DPTR,</td><td>#G_BUFFER</td><td></td><td></td></tr><tr><td>MOV</td><td>B,#55H</td><td></td><td></td><td></td></tr><tr><td>LCALL</td><td>XMEMSET</td><td></td><td>//修改置缓冲区</td><td></td></tr><tr><td>MOV</td><td>ADDR+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>ADDR+1,</td><td>#HIGH TEST_ADDR</td><td></td><td></td></tr><tr><td>MOV</td><td>ADDR+0,</td><td>#LOW TEST_ADDR</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+1,</td><td>#HIGH BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+0,</td><td>#LOW BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>DPTR,</td><td>#G_BUFFER</td><td></td><td></td></tr><tr><td>LCALL</td><td>FLASHWRITE</td><td></td><td>//将缓冲区的数据写到Flash中</td><td></td></tr><tr><td>MOV</td><td>ADDR+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>ADDR+1,</td><td>#HIGH TEST_ADDR</td><td></td><td></td></tr><tr><td>MOV</td><td>ADDR+0,</td><td>#LOW TEST_ADDR</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+1,</td><td>#HIGH BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+0,</td><td>#LOW BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>DPTR,</td><td>#G_BUFFER</td><td rowspan="2"></td><td>//读取测试地址的数据</td></tr><tr><td>LCALL</td><td>FLASHREAD</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+1,</td><td>#HIGH BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+0,</td><td>#LOW BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>DPTR,</td><td>#G_BUFFER</td><td></td><td></td></tr></table>

<table><tr><td>LCALL</td><td colspan="2">SENDUARTBLOCK</td><td>//发送到串口</td><td></td></tr><tr><td>LCALL</td><td colspan="2">FLASHERASE</td><td>//擦除Flash</td><td></td></tr><tr><td>MOV</td><td>ADDR+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>ADDR+1,</td><td>#HIGH TEST_ADDR</td><td></td><td></td></tr><tr><td>MOV</td><td>ADDR+0,</td><td>#LOW TEST_ADDR</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+1,</td><td>#HIGH BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+0,</td><td>#LOW BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>DPTR,</td><td>#G_BUFFER</td><td></td><td></td></tr><tr><td>LCALL</td><td colspan="2">FLASHREAD</td><td>//读取测试地址的数据</td><td></td></tr><tr><td>MOV</td><td>SIZE+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+1,</td><td>#HIGH BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+0,</td><td>#LOW BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>DPTR,</td><td>#G_BUFFER</td><td></td><td></td></tr><tr><td>LCALL</td><td colspan="2">SENDUARTBLOCK</td><td>//发送到串口</td><td></td></tr><tr><td>MOV</td><td>SIZE+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+1,</td><td>#HIGH BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+0,</td><td>#LOW BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>DPTR,</td><td>#G_BUFFER</td><td></td><td></td></tr><tr><td>MOV</td><td>B,</td><td>#0AAH</td><td></td><td></td></tr><tr><td>LCALL</td><td colspan="2">XMEMSET</td><td>//修改置缓冲区</td><td></td></tr><tr><td>MOV</td><td>ADDR+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>ADDR+1,</td><td>#HIGH TEST_ADDR</td><td></td><td></td></tr><tr><td>MOV</td><td>ADDR+0,</td><td>#LOW TEST_ADDR</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+1,</td><td>#HIGH BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+0,</td><td>#LOW BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>DPTR,</td><td>#G_BUFFER</td><td></td><td>//将缓冲区的数据写到Flash中</td></tr><tr><td>LCALL</td><td colspan="2">FLASHWRITE</td><td></td><td></td></tr><tr><td>MOV</td><td>ADDR+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>ADDR+1,</td><td>#HIGH TEST_ADDR</td><td></td><td></td></tr><tr><td>MOV</td><td>ADDR+0,</td><td>#LOW TEST_ADDR</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+1,</td><td>#HIGH BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+0,</td><td>#LOW BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>DPTR,</td><td>#G_BUFFER</td><td></td><td></td></tr><tr><td>LCALL</td><td colspan="2">FLASHREAD</td><td>//读取测试地址的数据</td><td></td></tr><tr><td>MOV</td><td>SIZE+2,</td><td>#0</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+1,</td><td>#HIGH BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>SIZE+0,</td><td>#LOW BUFFER_SIZE</td><td></td><td></td></tr><tr><td>MOV</td><td>DPTR,</td><td>#G_BUFFER</td><td></td><td></td></tr><tr><td>LCALL</td><td colspan="2">SENDUARTBLOCK</td><td>//发送到串口</td><td></td></tr></table>

SJMP $ 

/************************************************ 

SPI中断服务程序

************************************************ 

SPI_ISR: 

MOV SPSTAT,#SPIF | WCOL 

//清除SPI状态位

CLR G_SPIBUSY 

RETI 

/************************************************ 

发送数据到串口

入口参数:

SIZE : 数据块大小

DPTR : 数据缓冲区

B : 设置的值

出口参数: 无

************************************************ 

XMEMSET: 

MOV A,SIZE 

ORL A,SIZE+1 

ORL A,SIZE+2 

JZ XMSEND 

MOV A,B 

MOVX @DPTR,A 

INC DPTR 

CLR C 

MOV A,SIZE+0 

SUBB A,#1 

MOV SIZE+0,A 

MOV A,SIZE+1 

SUBB A,#0 

MOV SIZE+1,A 

MOV A,SIZE+2 

SUBB A,#0 

MOV SIZE+2,A 

LJMP XMEMSET 

XMSEND: 

RET 

************************************************* 

串口 初始化

入口参数: 无

出口参数: 无

************************************************ 

# INITUART:

MOV AUXR, #40H 

//设置定时器1为1T模式

MOV TMOD, #00H 

//定时器1为16位重载模式

MOV TH1, #HIGH BAUD 

//设置波特率

MOV TL1, 

SETB TR1 

MOV SCON, #5AH 

//设置串口 为8位数据位,波特率可变模式

RET 

************************************************ 

发送数据到串口

入口参数:

ACC : 准备发送的数据

出口参数: 无

************************************************ 

# SENDUART:

JNB TI,$ 

//等待上一个数据发送完成

CLR TI 

//清除发送完成标志

MOV SBUF,A 

//触发本次的数据发送

RET 

/************************************************ 

发送数据块到串口

入口参数:

SIZE : 数据块大小

DPTR : 数据缓冲区

出口参数: 无

************************************************* 

# SENDUARTBLOCK:

MOV A,SIZE 

ORL A,SIZE+1 

ORL A,SIZE+2 

JZ SUBEND 

MOVX A,@DPTR 

LCALL SENDUART 

INC DPTR 

CLR C 

MOV A,SIZE+0 

SUBB A,#1 

MOV SIZE+0,A 

MOV A,SIZE+1 

SUBB A,#0 

MOV SIZE+1,A 

MOV A,SIZE+2 

//自动连续发送串口 数据

SUBB A,#0 

MOV SIZE+2,A 

LJMP SENDUARTBLOCK 

SUBEND: 

RET 

```txt
/***** 
```

SPI初始化

入口参数: 无

出口参数: 无

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```


INITSPI:


```csv
// MOV A,P_SW1 //切换到第一组SPI  
// ANL A,#NOT (SPI_S0 | SPI_S1) //SPI_S0=0 SPI_S1=0  
// MOV P_SW1,A //P1.2/SS, P1.3/MOSI, P1.4/MISO, P1.5/SCLK)  
MOV A,P_SW1 //可用于测试U7,U7使用的是第二组SPI控制Flash  
ANL A,#NOT (SPI_S0 | SPI_S1) //SPI_S0=1 SPI_S1=0  
ORL A,#SPI_S0 //P2.4/SS_2, P2.3/MOSI_2, P2.2/MISO_2, P2.1/SCLK_2)  
MOV P_SW1,A  
// MOV A,P_SW1 //切换到第三组SPI  
// ANL A,#NOT (SPI_S0 | SPI_S1) //SPI_S0=0 SPI_S1=1  
ORL A,#SPI_S1 //P5.4/SS_3, P4.0/MOSI_3, P4.1/MISO_3, P4.3/SCLK_3)  
MOV P_SW1,A  
MOV SPSTAT,#SPIF | WCOL //清除SPI状态  
SETB SS  
MOV SPCTL,#SSIG | SPEN | MSTR //设置SPI为主模式  
RET
```

```txt
/***** 
```

使用SPI方式与Flash进行数据交换

入口参数:

ACC : 准备写入的数据

出口参数:

ACC : 从Flash中读出的数据

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```


SPISHIFT:


SETB G_SPIBUSY 

MOV SPDAT,A 

JB G_SPIBUSY,$ 

MOV A,SPDAT 

RET 

//触发SPI发送

//等待SPI数据传输完成

************************************************ 

检测Flash是否准备就绪

入口参数: 无

出口参数: CY

0 : 没有检测到正确的Flash

1 : Flash准备就绪

************************************************/ 

FLASHCHECKID: 

CLR SS 

MOV A,#SFC_RDID //发送读取ID命令

LCALL SPISHIFT 

LCALL SPISHIFT //空读3个字节

LCALL SPISHIFT 

LCALL SPISHIFT 

LCALL SPISHIFT //读取制造商ID1

MOV R7,A 

LCALL SPISHIFT //读取设备ID

LCALL SPISHIFT //读取制造商ID2

MOV R6,A 

SETB SS 

CLR G_FLASHOK 

CJNE R7,#9DH,$ //检测是否为PM25LVxx系列的Flash

CJNE R6,#7FH,$ 

SETB G_FLASHOK 

FLASHERROR: 

MOV C,G_FLASHOK 

RET 

************************************************* 

检测Flash的忙状态

入口参数: 无

出口参数: CY

0 : Flash处于空闲状态

1 : Flash处于忙状态

************************************************* 

ISFLASHBUSY: 

CLR SS 

MOV A,#SFC_RDSR //发送读取状态命令

LCALL SPISHIFT 

LCALL SPISHIFT //读取状态

SETB SS 

MOV C,ACC.0 //状态值的Bit0即为忙标志

RET 

************************************************ 

使能Flash写命令

入口参数: 无

出口参数: 无

************************************************ 

FALSHWRITEENABLE: 

LCALL ISFLASHBUSY 

JC $-3 

//Flash忙检测

CLR SS 

MOV A,#SFC_WREN 

//发送写使能命令

LCALL SPISHIFT 

SETB SS 

RET 

/************************************************ 

擦除整片Flash

入口参数: 无

出口参数: 无

************************************************/ 

FLASHERASE: 

JNB G_FLASHOK,FEREXIT 

//使能Flash写命令

LCALL FALSHWRITEENABLE 

CLR SS 

MOV A,#SFC_CHIPER 

//发送片擦除命令

LCALL SPISHIFT 

SETB SS 

FEREXIT: 

RET 

************************************************* 

从Flash中读取数据

入口参数:

ADDR : FALSH地址参数

SIZE : 数据块大小

DPTR : 缓冲区首地址

出口参数:

无

************************************************* 

FLASHREAD: 

JNB G_FLASHOK,FRDEXIT 

LCALL ISFLASHBUSY 

JC $-3 

//Flash忙检测

CLR SS 

<table><tr><td>MOV</td><td>A,#SFC_FASTREAD</td><td>//使用快速读取命令</td></tr><tr><td>LCALL</td><td>SPISHIFT</td><td></td></tr><tr><td>MOV</td><td>A,ADDR+2</td><td>//设置起始地址</td></tr><tr><td>LCALL</td><td>SPISHIFT</td><td></td></tr><tr><td>MOV</td><td>A,ADDR+1</td><td></td></tr><tr><td>LCALL</td><td>SPISHIFT</td><td></td></tr><tr><td>MOV</td><td>A,ADDR+0</td><td></td></tr><tr><td>LCALL</td><td>SPISHIFT</td><td></td></tr><tr><td>LCALL</td><td>SPISHIFT</td><td>//需要空读一个字节</td></tr><tr><td>FRDNEXTBYTE:</td><td></td><td></td></tr><tr><td>MOV</td><td>A,SIZE</td><td></td></tr><tr><td>ORL</td><td>A,SIZE+1</td><td></td></tr><tr><td>ORL</td><td>A,SIZE+2</td><td></td></tr><tr><td>JZ</td><td>FRDEND</td><td></td></tr><tr><td>LCALL</td><td>SPISHIFT</td><td>//自动连续读取并保存</td></tr><tr><td>MOVX</td><td>@DPTR,A</td><td></td></tr><tr><td>INC</td><td>DPTR</td><td></td></tr><tr><td>MOV</td><td>A,ADDR+0</td><td></td></tr><tr><td>ADD</td><td>A,#1</td><td></td></tr><tr><td>MOV</td><td>ADDR+0,A</td><td></td></tr><tr><td>MOV</td><td>A,ADDR+1</td><td></td></tr><tr><td>ADDC</td><td>A,#0</td><td></td></tr><tr><td>MOV</td><td>ADDR+1,A</td><td></td></tr><tr><td>MOV</td><td>A,ADDR+2</td><td></td></tr><tr><td>ADDC</td><td>A,#0</td><td></td></tr><tr><td>MOV</td><td>ADDR+2,A</td><td></td></tr><tr><td>CLR</td><td>C</td><td></td></tr><tr><td>MOV</td><td>A,SIZE+0</td><td></td></tr><tr><td>SUBB</td><td>A,#1</td><td></td></tr><tr><td>MOV</td><td>SIZE+0,A</td><td></td></tr><tr><td>MOV</td><td>A,SIZE+1</td><td></td></tr><tr><td>SUBB</td><td>A,#0</td><td></td></tr><tr><td>MOV</td><td>SIZE+1,A</td><td></td></tr><tr><td>MOV</td><td>A,SIZE+2</td><td></td></tr><tr><td>SUBB</td><td>A,#0</td><td></td></tr><tr><td>MOV</td><td>SIZE+2,A</td><td></td></tr><tr><td>LJMP</td><td>FRDNEXTBYTE</td><td></td></tr><tr><td>FRDEND:</td><td></td><td></td></tr><tr><td>SETB</td><td>SS</td><td></td></tr><tr><td>FRDEXIT:</td><td></td><td></td></tr><tr><td>RET</td><td></td><td></td></tr></table>

************************************************ 

写数据到Flash中

入口参数:

ADDR : 地址参数

SIZE : 数据块大小

DPTR : 缓冲需要写入Flash的数据

出口参数: 无

************************************************ 

FLASHWRITE: 

JNB G_FLASHOK,FWREXIT 

FWRNEXTPAGE: 

MOV A,SIZE 

ORL A,SIZE+1 

ORL A,SIZE+2 

JZ FWREXIT 

LCALL FALSHWRITEENABLE //使能Flash写命令

CLR SS 

MOV A,#SFC_PAGEPROG //发送页编程命令

LCALL SPISHIFT 

MOV A,ADDR+2 //设置起始地址

LCALL SPISHIFT 

MOV A,ADDR+1 

LCALL SPISHIFT 

MOV A,ADDR+0 

LCALL SPISHIFT 

FWRNEXTBYTE: 

MOV A,SIZE 

ORL A,SIZE+1 

ORL A,SIZE+2 

JZ FRDEND 

MOVX A,@DPTR 

LCALL SPISHIFT //连续页内写

INC DPTR 

MOV A,ADDR+0 

ADD A,#1 

MOV ADDR+0,A 

MOV A,ADDR+1 

ADDC A,#0 

MOV ADDR+1,A 

MOV A,ADDR+2 

ADDC A,#0 

<table><tr><td>MOV</td><td>ADDR+2,A</td></tr><tr><td>CLR</td><td>C</td></tr><tr><td>MOV</td><td>A,SIZE+0</td></tr><tr><td>SUBB</td><td>A,#1</td></tr><tr><td>MOV</td><td>SIZE+0,A</td></tr><tr><td>MOV</td><td>A,SIZE+1</td></tr><tr><td>SUBB</td><td>A,#0</td></tr><tr><td>MOV</td><td>SIZE+1,A</td></tr><tr><td>MOV</td><td>A,SIZE+2</td></tr><tr><td>SUBB</td><td>A,#0</td></tr><tr><td>MOV</td><td>SIZE+2,A</td></tr><tr><td>MOV</td><td>A,ADDR+0</td></tr><tr><td>JZ</td><td>FWREND</td></tr><tr><td>LJMP</td><td>FWRNEXTBYTE</td></tr><tr><td>FWREND:</td><td></td></tr><tr><td>SETB</td><td>SS</td></tr><tr><td>LJMP</td><td>FWRNXTPAGE</td></tr><tr><td>FWREXT:</td><td></td></tr><tr><td>RET</td><td></td></tr><tr><td>END</td><td></td></tr></table>

# 14.8.2.2 通过查询方式利用SPI的主模式读写外部串行Flash的测试程序(C和汇编)

# 1、C语言程序

/*- -*/ 

/* --- STC MCU Limited - ---*/ 

/* --- STC15W4K60S4 系列 SPI的主模式读写外部串行 Flash举例(查询方式)--------*/

/* --- Mobile: (86)13922805190 - --*/ 

/* --- Fax: 86-755-82905966 */ 

/* --- Tel: 86-755-82948412 - -*/ 

/* --- Web: www.STCMCU.com - --*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/*- -*/ 

//本示例在Keil开发环境下请选择Intel的8058芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

//本示例所读写的目标Flash为PM25LV040,本代码已使用U7编程器测试通过

#include "reg51.h" 

typedef bit BOOL; 

typedef unsigned char BYTE; 

typedef unsigned short WORD; 

typedef unsigned long DWORD; 

#define FOSC 18432000L 

#define BAUD (65536 - FOSC / 4 / 115200) 

#define NULL 0 

#define FALSE 0 

#define TRUE 1 

sfr AUXR 0x8e; //辅助寄存器

sfr P_SW1 $=$ 0xa2; //外设功能切换寄存器1

#define SPI_S0 0x04 

#define SPI_S1 0x08 

sfr SPSTAT = 0xcd; //SPI状态寄存器

#define SPIF 0x80 //SPSTAT.7 

#define WCOL 0x40 //SPSTAT.6 

sfr SPCTL = 0xce; //SPI控制寄存器

#define SSIG 0x80 //SPCTL.7 

#define SPEN 0x40 //SPCTL.6 

#define DORD 0x20 //SPCTL.5 

```c
define MSTR 0x10 //SPCTL.4  
#define CPOL 0x08 //SPCTL.3  
#define CPHA 0x04 //SPCTL.2  
#define SPDHH 0x00 //CPU_CLK/4  
#define SPDH 0x01 //CPU_CLK/16  
#define SPDL 0x02 //CPU_CLK/64  
#define SPDLL 0x03 //CPU_CLK/128  
sfr SPDAT = 0xfc; //SPI数据寄存器
```

```javascript
sbit SS = P2^4; //SPI的SS脚,连接到Flash的CE
```

```txt
define SFC_WREN 0x06 //串行Flash命令集
```

```txt
define SFC_WRDI 0x04 
```

```txt
define SFC_RDSR 0x05 
```

```txt
define SFC_WRSR 0x01 
```

```txt
define SFC_READ 0x03 
```

```txt
define SFC_FASTREAD 0x0B 
```

```txt
define SFC_RDID 0xAB 
```

```txt
define SFC_PAGEPROG 0x02 
```

```batch
define SFC_RDCR 0xA1 
```

```txt
define SFC_WRCR 0xF1 
```

```batch
define SFC_SECTORER 0xD7 
```

```txt
define SFC_BLOCKER 0xD8 
```

```txt
define SFC_CHIPER 0xC7 
```

```c
void InitUart();  
void SendUart(BYTE dat);  
void InitSpi();  
BYTE SpiShift(BYTE dat);  
BOOL FlashCheckID();  
BOOL IsFlashBusy();  
void FlashWriteEnable();  
void FlashErase();  
void FlashRead(DWORD addr, DWORD size, BYTE *buffer);  
void FlashWrite(DWORD addr, DWORD size, BYTE *buffer); 
```

```c
define BUFFER_SIZE 1024 //缓冲区大小  
#defineTEST_ADDR 0 //Flash测试地址
```

```txt
BYTE xdata g Buffer[BUFFER_SIZE]; //Flash读写缓冲区  
BOOL g_fFlashOK; //Flash状态
```

```txt
void main() { 
```

int i; 

//初始化Flash状态

g_fFlashOK $=$ FALSE; 

//初始化串口 和SPI

InitUart(); 

InitSpi(); 

//检测Flash状态

FlashCheckID(); 

//擦除Flash

FlashErase(); 

//读取测试地址的数据

FlashRead(TEST_ADDR, BUFFER_SIZE, g_Buffer); 

//发送到串口

for (i=0; i<BUFFER_SIZE; i++) SendUart(g_Buffer[i]); 

//修改置缓冲区

for (i=0; i<BUFFER_SIZE; i++) g_Buffer[i] = i>>2; 

//将缓冲区的数据写到Flash中

FlashWrite(TEST_ADDR, BUFFER_SIZE, g_Buffer); 

//读取测试地址的数据

FlashRead(TEST_ADDR, BUFFER_SIZE, g_Buffer); 

//发送到串口

for (i=0; i<BUFFER_SIZE; i++) SendUart(g_Buffer[i]); 

FlashErase(); 

//读取测试地址的数据

FlashRead(TEST_ADDR, BUFFER_SIZE, g_Buffer); 

//发送到串口

for (i=0; i<BUFFER_SIZE; i++) SendUart(g_Buffer[i]); 

//修改置缓冲区

for (i=0; i<BUFFER_SIZE; i++) g_Buffer[i] $=$ 255- $( \mathrm { i } ) { > } > 2$ ); 

//将缓冲区的数据写到Flash中

FlashWrite(TEST_ADDR, BUFFER_SIZE, g_Buffer); 

//读取测试地址的数据

FlashRead(TEST_ADDR, BUFFER_SIZE, g_Buffer); 

//发送到串口

for (i=0; i<BUFFER_SIZE; $\mathrm { i } { + } { + }$ ) SendUart(g_Buffer[i]); 

while(1);   
}   
/******   
串口初始化   
入口参数：无   
出口参数：无   
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*   
void InitUart()   
{ AUXR $= 0\mathrm{x}40$ //设置定时器1为1T; TMOD $= 0\mathrm{x}00$ //定时器1为16位重   
TH1 $\equiv$ BAUD>>8; //设置波特率 TL1 $\equiv$ BAUD; TR1 $= 1$ ： SCON $= 0\mathrm{x}5\mathrm{a}$ //设置串口为8位数据   
}

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

发送数据到串口

入口参数:

dat : 准备发送的数据

出口参数: 无

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

```txt
void SendUart(BYTE dat)  
{ while (!TI); //等待上一个数据发送完成  
TI = 0; //清除发送完成标志  
SBUF = dat; //触发本次的数据发送  
}
```

```txt
/***** 
```

SPI初始化

入口参数: 无

出口参数: 无

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

```txt
void InitSpi()  
{  
// ACC = P_SW1; //切换到第一组SPI  
// ACC &= ~(SPI_S0 | SPI_S1); //SPI_S0=0 SPI_S1=0  
// P_SW1 = ACC; //P1.2/SS, P1.3/MOSI, P1.4/MISO, P1.5/SCLK)  
ACC = P_SW1; //可用于测试U7,U7使用的是第二组SPI控制Flash  
ACC &= ~(SPI_S0 | SPI_S1); //SPI_S0=1 SPI_S1=0
```

ACC $\vDash$ SPI_S0; //P2.4/SS_2,P2.3/MOSI_2,P2.2/MISO_2,P2.1/SCLK_2) P_SW1 $=$ ACC;   
//ACC=P_SW1; //切换到第三组SPI   
//ACC&=-(SPI_S0|SPI_S1); //SPI_S0=0 SPI_S1=1   
//ACC $\vDash$ SPI_S1; //P5.4/SS_3,P4.0/MOSI_3,P4.1/MISO_3,P4.3/SCLK_3)   
//P_SW1 $=$ ACC;   
SPSTAT $=$ SPIF|WCOL; //清除SPI状态 SS = 1; SPCTL $=$ SSIG|SPEN|MSTR; //设置SPI为主模式   
}   
**********   
使用SPI方式与Flash进行数据交换   
入口参数: dat：准备写入的数据   
出口参数: 从Flash中读出的数据   
**********   
BYTE SpiShift(BYTE dat)   
{ SPDAT $\equiv$ dat; //触发SPI发送 while(!(SPSTAT&SPI)); //等待SPI数据传输完成 SPSTAT $=$ SPIF|WCOL; //清除SPI状态 return SPDAT;   
}   
**********   
检测Flash是否准备就绪   
入口参数：无   
出口参数: 0：没有检测到正确的Flash 1:Flash准备就绪   
**********   
BOOL FlashCheckID()   
{ BYTE dat1,dat2; SS $= 0$ SpiShift(SFC_RDID); //发送读取ID命令 SpiShift(Ox00); //空读3个字节 SpiShift(Ox00); SpiShift(Ox00);

```c
dat1 = SpiShift(0x00); //读取制造商ID1  
SpiShift(0x00); //读取设备ID  
dat2 = SpiShift(0x00); //读取制造商ID2  
SS = 1; //检测是否为PM25LVxx系列的Flash  
g_fFlashOK = ((dat1 == 0x9d) && (dat2 == 0x7f));  
return g_fFlashOK;
```

```txt
/****** 
```

检测Flash的忙状态

入口参数: 无

出口参数:

0 : Flash处于空闲状态

1 : Flash处于忙状态

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

```txt
BOOL IsFlashBusy()  
{BYTE dat;  
SS = 0;  
SpiShift(SFC_RDSR); //发送读取状态命令  
dat = SpiShift(0); //读取状态  
SS = 1;  
return (dat & 0x01); //状态值的Bit0即为忙标志  
}
```

```txt
/***** 
```

使能Flash写命令

入口参数: 无

出口参数: 无

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

voidFlashWriteEnable()  
{ while(IsFlashBusy())； //Flash忙检测 $\mathrm{SS} = 0$ SpiShift(SFC_WREN); //发送写使能命令 $\mathrm{SS} = 1$ ·   
}

```txt
/****** 
```

擦除整片Flash

入口参数: 无


出口参数: 无


```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

```txt
void FlashErase()  
{  
if (g_fFlashOK)  
{  
    FlashWriteEnable(); //使能Flash写命令  
    SS = 0;  
    SpiShift(SFC_CHIPER); //发送片擦除命令  
    SS = 1;  
}
```

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```


从Flash中读取数据


```txt
入口参数：
```

```txt
addr : 地址参数
```

```txt
size : 数据块大小
```

```txt
buffer：缓冲从Flash中读取的数据
```


出口参数:


```txt
无
```

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

voidFlashRead(DWORDaddr，DWORDsize，BYTE\*buffer)   
{ if(g_fFlashOK) { while(IsFlashBusy(）; //Flash忙检测 SS $= 0$ SpiShift(SFC_FASTREAD); //使用快速读取命令 SpiShift((BYTE\*)&addr)[1]); //设置起始地址 SpiShift((BYTE\*)&addr)[2]); SpiShift((BYTE\*)&addr)[3]); SpiShift(0); //需要空读一个字节 while(size) { \*buffer $=$ SpiShift(0); //自动连续读取并保存 addr++; buffer++; size--; } SS $= 1$ · }

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```

# 写数据到Flash中

入口参数:

addr : 地址参数

size : 数据块大小

buffer : 缓冲需要写入Flash的数据

出口参数: 无


************************************************


```c
void FlashWrite(DWORD addr, DWORD size, BYTE *buffer)  
{  
if (g_fFlashOK)  
while (size)  
{  
    FlashWriteEnable(); //使能Flash写命令  
SS = 0;  
SpiShift(SFC_PAGEPROG); //发送页编程命令  
SpiShift((BYTE*)&addr)[1]); //设置起始地址  
SpiShift((BYTE*)&addr)[2]);  
SpiShift((BYTE*)&addr)[3]);  
while (size)  
{  
    SpiShift(*buffer); //连续页内写  
addr++;  
buffer++;  
size--;  
if ((addr & 0xff) == 0) break;  
}  
SS = 1;  
}
```

# 2、汇编程序

/*- -*/ 

/* --- STC MCU Limited -*/ 

/* --- STC15W4K60S4 系列 SPI的主模式读写外部串行 Flash举例(查询方式)--------*/

/* --- Mobile: (86)13922805190 - -*/ 

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 -*/ 

/* --- Web: www.STCMCU.com -*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/* -*/ 

//本示例在Keil开发环境下请选择Intel的8058芯片型号进行编译

//假定测试芯片的工作频率为18.432MHz

//本示例所读写的目标Flash为PM25LV040,本代码已使用U7编程器测试通过

//BAUD EQU 0FFE8H //(65536 - 11059200 / 4 / 115200) 

BAUD EQU 0FFD8H //(65536 - 18432000 / 4 / 115200) 

//BAUD EQU 0FFD0H //(65536 - 22118400 / 4 / 115200) 

AUXR DATA 08EH //辅助寄存器

P_SW1 DATA 0A2H //外设功能切换寄存器1

SPI_S0 EQU 04H 

SPI_S1 EQU 08H 

SPSTAT DATA 0CDH //SPI状态寄存器

SPIF EQU 080H //SPSTAT.7 

WCOL EQU 040H //SPSTAT.6 

SPCTL DATA 0CEH //SPI控制寄存器

SSIG EQU 080H //SPCTL.7 

SPEN EQU 040H //SPCTL.6 

DORD EQU 020H //SPCTL.5 

MSTR EQU 010H //SPCTL.4 

CPOL EQU 008H //SPCTL.3 

CPHA EQU 004H //SPCTL.2 

SPDHH EQU 000H //CPU_CLK/4 

SPDH EQU 001H //CPU_CLK/16 

SPDL EQU 002H //CPU_CLK/64 

SPDLL EQU 003H //CPU_CLK/128 

SPDAT DATA 0CFH //SPI数据寄存器

SS BIT P2.4 //SPI的SS脚,连接到Flash的CE

SFC_WREN EQU 0x06 //串行 Flash命令集

<table><tr><td>SFC_WRDI</td><td>EQU</td><td>0x04</td></tr><tr><td>SFC_RDSR</td><td>EQU</td><td>0x05</td></tr><tr><td>SFC_WRSR</td><td>EQU</td><td>0x01</td></tr><tr><td>SFC_READ</td><td>EQU</td><td>0x03</td></tr><tr><td>SFC_FASTREAD</td><td>EQU</td><td>0x0B</td></tr><tr><td>SFC_RDID</td><td>EQU</td><td>0xAB</td></tr><tr><td>SFC_PAGEPROG</td><td>EQU</td><td>0x02</td></tr><tr><td>SFC_RDCR</td><td>EQU</td><td>0xA1</td></tr><tr><td>SFC_WRCR</td><td>EQU</td><td>0xF1</td></tr><tr><td>SFC_SECTORER</td><td>EQU</td><td>0xD7</td></tr><tr><td>SFC_BLOCKER</td><td>EQU</td><td>0xD8</td></tr><tr><td>SFC_CHIPER</td><td>EQU</td><td>0xC7</td></tr></table>

<table><tr><td>BUFFER_SIZE</td><td>EQU</td><td>1024</td><td>//缓冲区大小</td></tr><tr><td>TEST_ADDR</td><td>EQU</td><td>0</td><td>//Flash测试地址</td></tr></table>

<table><tr><td>G_BUFFER</td><td>XDATA 0</td><td>//Flash读写缓冲区</td></tr><tr><td>G_FLASHOK</td><td>BIT 20H.0</td><td>//Flash状态</td></tr></table>

<table><tr><td>ADDR</td><td>DATA 21H</td><td>//地址变量,3字节</td></tr><tr><td>SIZE</td><td>DATA 24H</td><td>//大小变量,3字节</td></tr></table>

<table><tr><td colspan="2">ORG 0000H</td></tr><tr><td colspan="2">LJMP MAIN</td></tr><tr><td colspan="2">ORG 0100H</td></tr><tr><td colspan="2">MAIN:</td></tr><tr><td colspan="2">MOV SP,#3FH</td></tr><tr><td>CLR G_FLASHOK</td><td>//初始化Flash状态</td></tr><tr><td>LCALL INITUART</td><td>//初始化串口和SPI</td></tr><tr><td>LCALL INITSPI</td><td></td></tr><tr><td>LCALL FLASHCHECKID</td><td>//检测Flash状态</td></tr><tr><td>LCALL FLASHERASE</td><td>//擦除Flash</td></tr><tr><td colspan="2">MOV ADDR+2,#0</td></tr><tr><td colspan="2">MOV ADDR+1,#HIGH TEST_ADDR</td></tr><tr><td colspan="2">MOV ADDR+0,#LOW TEST_ADDR</td></tr><tr><td colspan="2">MOV SIZE+2,#0</td></tr><tr><td colspan="2">MOV SIZE+1,#HIGH BUFFER_SIZE</td></tr><tr><td colspan="2">MOV SIZE+0,#LOW BUFFER_SIZE</td></tr><tr><td colspan="2">MOV DPTR,#GBUFFER</td></tr><tr><td>LCALL FLASHREAD</td><td>//读取测试地址的数据</td></tr><tr><td colspan="2">MOV SIZE+2,#0</td></tr></table>

MOV SIZE+1,#HIGH BUFFER_SIZE 

MOV SIZE+0,#LOW BUFFER_SIZE 

MOV DPTR,#G_BUFFER 

LCALL SENDUARTBLOCK //发送到串口

MOV SIZE+2,#0 

MOV SIZE+1,#HIGH BUFFER_SIZE 

MOV SIZE+0,#LOW BUFFER_SIZE 

MOV DPTR,#G_BUFFER 

MOV B,#33H 

LCALL XMEMSET //修改置缓冲区

MOV ADDR+2,#0 

MOV ADDR+1,#HIGH TEST_ADDR 

MOV ADDR+0,#LOW TEST_ADDR 

MOV SIZE+2,#0 

MOV SIZE+1,#HIGH BUFFER_SIZE 

MOV SIZE+0,#LOW BUFFER_SIZE 

MOV DPTR,#G_BUFFER 

LCALL FLASHWRITE //将缓冲区的数据写到Flash中

MOV ADDR+2,#0 

MOV ADDR+1,#HIGH TEST_ADDR 

MOV ADDR+0,#LOW TEST_ADDR 

MOV SIZE+2,#0 

MOV SIZE+1,#HIGH BUFFER_SIZE 

MOV SIZE+0,#LOW BUFFER_SIZE 

MOV DPTR,#G_BUFFER 

LCALL FLASHREAD //读取测试地址的数据

MOV SIZE+2,#0 

MOV SIZE+1,#HIGH BUFFER_SIZE 

MOV SIZE+0,#LOW BUFFER_SIZE 

MOV DPTR,#G_BUFFER 

LCALL SENDUARTBLOCK //发送到串口

LCALL FLASHERASE //擦除Flash

MOV ADDR+2,#0 

MOV ADDR+1,#HIGH TEST_ADDR 

MOV ADDR+0,#LOW TEST_ADDR 

MOV SIZE+2,#0 

MOV SIZE+1,#HIGH BUFFER_SIZE 

MOV SIZE+0,#LOW BUFFER_SIZE 

MOV DPTR,#G_BUFFER 

LCALL FLASHREAD //读取测试地址的数据

MOV SIZE+2,#0 

MOV SIZE+1,#HIGH BUFFER_SIZE 

MOV SIZE+0,#LOW BUFFER_SIZE 

MOV DPTR,#G_BUFFER 

LCALL SENDUARTBLOCK //发送到串口

MOV SIZE+2,#0 

MOV SIZE+1,#HIGH BUFFER_SIZE 

MOV SIZE+0,#LOW BUFFER_SIZE 

MOV DPTR,#G_BUFFER 

MOV B,#099H 

LCALL XMEMSET //修改置缓冲区

MOV ADDR+2,#0 

MOV ADDR+1,#HIGH TEST_ADDR 

MOV ADDR+0,#LOW TEST_ADDR 

MOV SIZE+2,#0 

MOV SIZE+1,#HIGH BUFFER_SIZE 

MOV SIZE+0,#LOW BUFFER_SIZE 

MOV DPTR,#G_BUFFER 

LCALL FLASHWRITE //将缓冲区的数据写到Flash中

MOV ADDR+2,#0 

MOV ADDR+1,#HIGH TEST_ADDR 

MOV ADDR+0,#LOW TEST_ADDR 

MOV SIZE+2,#0 

MOV SIZE+1,#HIGH BUFFER_SIZE 

MOV SIZE+0,#LOW BUFFER_SIZE 

MOV DPTR,#G_BUFFER 

LCALL FLASHREAD //读取测试地址的数据

MOV SIZE+2,#0 

MOV SIZE+1,#HIGH BUFFER_SIZE 

MOV SIZE+0,#LOW BUFFER_SIZE 

MOV DPTR,#G_BUFFER 

LCALL SENDUARTBLOCK //发送到串口

SJMP $ 

************************************************ 

发送数据到串口

入口参数:

SIZE : 数据块大小

DPTR : 数据缓冲区

B : 设置的值

出口参数: 无

************************************************ 

# XMEMSET:

MOV A,SIZE 

ORL A,SIZE+1 

ORL A,SIZE+2 

JZ XMSEND 

MOV A,B 

MOVX @DPTR,A //自动连续设置XDATA数据

INC DPTR 

CLR C 

MOV A,SIZE+0 

SUBB A,#1 

MOV SIZE+0,A 

MOV A,SIZE+1 

SUBB A,#0 

MOV SIZE+1,A 

MOV A,SIZE+2 

SUBB A,#0 

MOV SIZE+2,A 

LJMP XMEMSET 

# XMSEND:

RET 

/************************************************ 

串口 初始化

入口参数: 无

出口参数: 无

************************************************ 

# INITUART:

MOV AUXR,#40H //设置定时器1为1T模式

MOV TMOD,#00H //定时器1为16位重载模式

MOV TH1,#HIGH BAUD //设置波特率

MOV TL1,#LOW BAUD 

SETB TR1 

MOV SCON,#5AH //设置串口 为8位数据位,波特率可变模式

RET 

/************************************************ 

发送数据到串口

入口参数:

ACC : 准备发送的数据

出口参数: 无

************************************************* 

# SENDUART:

JNB TI, $ //等待上一个数据发送完成

CLR TI //清除发送完成标志

```txt
MOV SBUF, A //触发本次的数据发送  
RET
```

```txt
/****** 
```

发送数据块到串口

入口参数:

SIZE : 数据块大小

DPTR : 数据缓冲区

出口参数: 无

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```


SENDUARTBLOCK:


```csv
MOV A,SIZE 
```

```csv
ORL A,SIZE+1 
```

```csv
ORL A,SIZE+2 
```

```txt
JZ SUBEND 
```

```csv
MOVX A,@DPTR 
```

```txt
LCALL SENDUART //自动连续发送串口数据
```

```txt
INC DPTR 
```

```txt
CLR C 
```

```csv
MOV A,SIZE+0 
```

```txt
SUBB A,#1 
```

```csv
MOV SIZE+0,A 
```

```csv
MOV A,SIZE+1 
```

```csv
SUBB A,#0 
```

```csv
MOV SIZE+1,A 
```

```csv
MOV A,SIZE+2 
```

```csv
SUBB A,#0 
```

```csv
MOV SIZE+2,A 
```

```txt
LJMP SENDUARTBLOCK 
```

SUBEND: 

RET 

```txt
/****** 
```

SPI初始化

入口参数: 无

出口参数: 无

```javascript
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
```


INITSPI:


```csv
// MOV A,P_SW1 //切换到第一组SPI  
// ANL A,#NOT (SPI_S0 | SPI_S1) //SPI_S0=0 SPI_S1=0  
// MOV P_SW1,A //P1.2/SS, P1.3/MOSI, P1.4/MISO, P1.5/SCLK)  
MOV A,P_SW1 //可用于测试U7,U7使用的是第二组SPI控制Flash  
ANL A,#NOT (SPI_S0 | SPI_S1) //SPI_S0=1 SPI_S1=0  
ORL A,#SPI_S0 //P2.4/SS_2, P2.3/MOSI_2, P2.2/MISO_2, P2.1/SCLK_2)
```

```csv
MOV P_SW1,A  
// MOV A,P_SW1 //切换到第三组SPI  
// ANL A,#NOT (SPI_S0 | SPI_S1) //SPI_S0=0 SPI_S1=1  
// ORL A,#SPI_S1 //P5.4/SS_3, P4.0/MOSI_3, P4.1/MISO_3, P4.3/SCLK_3)  
// MOV P_SW1,A  
MOV SPSTAT,#SPIF | WCOL //清除SPI状态  
SETB SS  
MOV SPCTL,#SSIG | SPEN | MSTR //设置SPI为主模式  
RET
```

************************************************ 

使用SPI方式与Flash进行数据交换

入口参数:

ACC : 准备写入的数据

出口参数:

ACC : 从Flash中读出的数据

************************************************/ 

# SPISHIFT:

MOV SPDAT,A //触发SPI发送

# WAITSPI:

MOV A,SPSTAT //等待SPI数据传输完成

ANL A,#SPIF 

JZ WAITSPI 

MOV SPSTAT,#SPIF | WCOL //清除SPI状态

MOV A,SPDAT 

RET 

/************************************************ 

检测Flash是否准备就绪

入口参数: 无

出口参数: CY

0 : 没有检测到正确的Flash

1 : Flash准备就绪

************************************************* 

# FLASHCHECKID:

CLR SS 

MOV A,#SFC_RDID //发送读取ID命令

LCALL SPISHIFT 

LCALL SPISHIFT //空读3个字节

LCALL SPISHIFT 

LCALL SPISHIFT 

LCALL SPISHIFT //读取制造商ID1

MOV R7,A 

LCALL SPISHIFT //读取设备ID

LCALL SPISHIFT //读取制造商ID2

MOV R6,A 

SETB SS 

CLR G_FLASHOK 

CJNE R7, #9DH,$ //检测是否为PM25LVxx系列的Flash

CJNE R6, #7FH,$ 

SETB G_FLASHOK 

FLASHERROR: 

MOV C, G_FLASHOK 

RET 

************************************************ 

检测Flash的忙状态

入口参数: 无

出口参数: CY

0 : Flash处于空闲状态

1 : Flash处于忙状态

************************************************ 

ISFLASHBUSY: 

CLR SS 

MOV A,#SFC_RDSR //发送读取状态命令

LCALL SPISHIFT 

LCALL SPISHIFT //读取状态

SETB SS 

MOV C, ACC.0 //状态值的Bit0即为忙标志

RET 

*火*火**火******火******火**火****火*火***********火*火***

使能Flash写命令

入口参数: 无

出口参数: 无

************************************************ 

FALSHWRITEENABLE: 

LCALL ISFLASHBUSY 

JC $-3 //Flash忙检测

CLR SS 

MOV A, #SFC_WREN //发送写使能命令

LCALL SPISHIFT 

SETB SS 

RET 

************************************************ 

擦除整片Flash

入口参数: 无

出口参数: 无

************************************************/ 

FLASHERASE: 

JNB G_FLASHOK,FEREXIT 

LCALL FALSHWRITEENABLE //使能Flash写命令

CLR SS 

MOV A,#SFC_CHIPER //发送片擦除命令

LCALL SPISHIFT 

SETB SS 

FEREXIT: 

RET 

/************************************************ 

从Flash中读取数据

入口参数:

ADDR : FALSH地址参数

SIZE : 数据块大小

DPTR : 缓冲区首地址

出口参数:

无

************************************************* 

FLASHREAD: 

JNB G_FLASHOK,FRDEXIT 

LCALL ISFLASHBUSY 

JC $-3 //Flash忙检测

CLR SS 

MOV A,#SFC_FASTREAD //使用快速读取命令

LCALL SPISHIFT 

MOV A,ADDR+2 //设置起始地址

LCALL SPISHIFT 

MOV A,ADDR+1 

LCALL SPISHIFT 

MOV A,ADDR+0 

LCALL SPISHIFT 

LCALL SPISHIFT //需要空读一个字节

FRDNEXTBYTE: 

MOV A,SIZE 

ORL A,SIZE+1 

ORL A,SIZE+2 

JZ FRDEND 

LCALL SPISHIFT 

//自动连续读取并保存

MOVX @DPTR,A 

INC DPTR 

MOV A,ADDR+0 

ADD A,#1 

MOV ADDR+0,A 

MOV A,ADDR+1 

ADDC A,#0 

MOV ADDR+1,A 

MOV A,ADDR+2 

ADDC A,#0 

MOV ADDR+2,A 

CLR C 

MOV A,SIZE+0 

SUBB A,#1 

MOV SIZE+0,A 

MOV A,SIZE+1 

SUBB A,#0 

MOV SIZE+1,A 

MOV A,SIZE+2 

SUBB A,#0 

MOV SIZE+2,A 

LJMP FRDNEXTBYTE 

FRDEND: 

SETB SS 

FRDEXIT: 

RET 

*火*火**火******火******火**火****火*火***********火*火***

写数据到Flash中

入口参数:

ADDR : 地址参数

SIZE : 数据块大小

DPTR : 缓冲需要写入Flash的数据

出口参数: 无

************************************************ 

FLASHWRITE: 

JNB G_FLASHOK,FWREXIT 

FWRNEXTPAGE: 

MOV A,SIZE 

ORL A,SIZE+1 

ORL A,SIZE+2 

JZ FWREXIT 

LCALL FALSHWRITEENABLE 

//使能Flash写命令

CLR SS 

MOV A,#SFC_PAGEPROG 

//发送页编程命令

LCALL SPISHIFT 

MOV A,ADDR+2 

//设置起始地址

LCALL SPISHIFT 

MOV A,ADDR+1 

LCALL SPISHIFT 

MOV A,ADDR+0 

LCALL SPISHIFT 

# FWRNEXTBYTE:

MOV A,SIZE 

ORL A,SIZE+1 

ORL A,SIZE+2 

JZ FRDEND 

MOVX A,@DPTR 

LCALL SPISHIFT 

INC DPTR 

MOV A,ADDR+0 

ADD A,#1 

MOV ADDR+0,A 

MOV A,ADDR+1 

ADDC A,#0 

MOV ADDR+1,A 

MOV A,ADDR+2 

ADDC A,#0 

MOV ADDR+2,A 

CLR C 

MOV A,SIZE+0 

SUBB A,#1 

MOV SIZE+0,A 

MOV A,SIZE+1 

SUBB A,#0 

MOV SIZE+1,A 

MOV A,SIZE+2 

SUBB A,#0 

MOV SIZE+2,A 

MOV A,ADDR+0 

JZ FWREND 

//连续页内写

LJMP FWRNEXTBYTE 

FWREND: 

SETB SS 

LJMP FWRNEXTPAGE 

FWREXIT: 

RET 

END 

# 14.9 SPI的特别注意事项(仅针对以15F和15L开头的单片机)

# 只支持SPI主机模式，不支持SPI从机模式

STC单片机中以15F和15L开头且有SPI功能的单片机(如STC15F2K60S2型号及STC15L408AD单片机)的SPI从机模式暂不能使用，但它们的SPI主机模式可正常使用。因此，建议用户不要使用以15F和15L开头且有SPI功能的单片机的SPI从机模式。

注意，以15W开头的单片机不存在上述问题，以15W开头且有SPI功能的单片机既支持SPI主机模式，也支持SPI从机模式。如，STC15W408S、STC15W1K16S等型号单片机既支持SPI主机模式，也支持SPI从机模式

# 第15章 编译器(汇编器)/ISP编程器(烧录)/仿真器说明

# 15.1 编译器/汇编器的说明及头文件

STC单片机应使用何种编译器/汇编器：

1.任何老的编译器/汇编器都可以支持，流行用Keil C51

2.把STC单片机当成Intel的8052/87C52/87C54/87C58或Philips的P87C52/P87C54/P87C58编译，头文件包含<reg51.h>即可。新增特殊功能寄存器用sfr声明，新增特殊功能寄存器位用sbit声明。例如，对要用到的新增P4口特殊功能寄存器及特殊功能寄存器位的地址声明如下：

# C��语言

sfr P4 = 0xC0; //8 bit Port4 P4.7 P4.6 P4.5 P4.4 P4.3 P4.2 P4.1 P4.0 1111,1111 

sfr $\mathbf { P 4 M 0 _ { \Delta } } =$ 0xB4; // 0000,0000 

sfr P4M1 = 0xB3; // 0000,0000 

sbit P40 = P4^0; 

sbit P41 = P4^1; 

sbit P42 = P4^2; 

sbit P43 P4^3; 

sbit P44 P4^4; 

sbit P45 P4^5; 

sbit P46 P4^6; 

sbit P47 P4^7; 

# 汇编语言 地址声明：

P4 EQU 0C0H ; or P4 DATA 0C0H 

P4M1 EQU 0B3H ; or P4M1 DATA 0B3H 

P4M0 EQU 0B4H ; or P4M1 DATA 0B4H 

P40 EQU 0C0H 

P41 EQU 0C1H 

P42 EQU 0C2H 

P43 EQU 0C3H 

P44 EQU 0C4H 

P45 EQU 0C5H 

P46 EQU 0C6H 

P47 EQU 0C7H 

;以上为P4口新增功能寄存器的地址声明

当然如果新增功能寄存器在用户程序中用不到的话，也可以不声明。

注意：如果用户所需包含的头文件不在Keil C的系统目录(C:\keil\C51\INC)下，用""将该头文件名包含进来，如果所需的头文件在Keil C的系统目录下，既可用""，也可用 $< >$ 包含进来.

对于STC部分单片机，可以到STC官方网站www.STCMCU.com下载用户所使用的相应系列单片机的头文件(如果找不到所需的文件用ctrl+F查找)，STC15系列单片机还可以用最新的ISP下载工具STC-ISP-15xx-V6.58生成相应的头文件并保存，如下图所示。在编译具体STC系列单片机程序时，这些相应的头文件可以代替"reg51.h"。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/4da8b5d88eb759b72ac37081833d78580f8af84c0366752c321bba84967736dd.jpg)


Keil C51集成开发环境有许多版本，而对于8051单片机最常用的版本有Keil μVision2、Keil μVision3及Keil μVision4.

注意：由于STC系列单片机是新发展的芯片，一般情况下在Keil 设备库中没有STC系列单片机。在编辑、编译STC系列单片机应用程序时，可选任何厂家的51或52系列单片机，再用汇编或C语言 对STC系列单片机新增特殊功能寄存器进行定义，也可以通过STC-ISP下载编程工具将STC型号MCU添加到Keil μVision4或Keil μVision3或Keil$\mu \mathrm { V i s i o n } 2$ 的设备库中。

如果用户需在Keil μVision4或Keil μVision3或Keil μVision2的设备库中增加STC型号MCU，则可按如下步骤进行设置：

$\textcircled{1}$ 打开STC-ISP下载编程工具的最新软件STC-ISP-V6.65，选择“Keil仿真设置”页面，点击该页面中的【添加MCU型号到Keil中】按钮。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/3e9764dbe0845019deb44b2d1e62d63b50ad570dbf1933c0d0f778207615527b.jpg)


$\textcircled{2}$ 在弹出的“浏览文件夹”对话框中选择Keil安装目录（一般可能为“C:\keil”），然后单击【确定】，这样就将STC型号的MCU成功添加到Keil μVision2设备库中了。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/3235c5e44eb8cc0013b2530e8ff426d6c7f82fdc8f0f851aafec4c607e1b64d1.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7ab6ac4bae1654358f3fc95b16f8e865b435bdbbd1e4d581a7a2ecb6bdbdc601.jpg)


# 下面以Keil μVision4为例，详细介绍如何使用Keil μVision4开发、编译、调试用户程序。一、如何新建项目及在所新建的项目中添加STC型号MCU进行开发、编译、调试用户程序：

（1）启动Keil μVision4，进入Keil μVision4后的编辑界面如下所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/45f4c0b723e7e1b8894ea6d886aefac9af059b935f9f178f517e73248619a93e.jpg)


（2）建立一个新工程：单击Project菜单，在弹出的下拉菜单中选中New Project选项

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e77de50c627894fa7561387218994cc8e525790ca3245731b1a9a0616315a22f.jpg)


（3）在弹出的对话框中选择新项目要保存的路径和文件名，例如：保存路径为C:\Users\THINK\Documents\STC MCU，项目名为t1，单击保存即可。Keil μVision4的项目文件扩展名为.uvproj

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/8ceccbf3746d8939a45970e9ac590d69e6220d17c3da4e048c927e25d3132a7a.jpg)


（4）因之前已经通过STC-ISP下载编程工具将STC型号MCU添加到Keil μVision2的设备库中，所以在上一步【保存】之后会弹出“选择设备数据库”的对话框，如下图所示。该“选择设备数据库”的对话框中有“通用CPU数据库(Generic CPU Database)”和“STC MCU数据库(STC MCU Database)”两个选项。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/689f725207b9cc70e0f5eda31184ee99721d66494b8e9949e7fd9c3ad77961f4.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/386176a601037ba3e4d32e77d4e23413991e04223d1459fd64a112b87811f393.jpg)


如用户所使用的单片机是STC系列单片机，则在这里选择“STC MCU数据库(STC MCUDatabase)”，点击【OK】按钮确定。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/640edc10a80f00f1553eb9b8eac2db4aa9277a59f2876f3d03fe17f0d8dc43f5.jpg)


（5）在上一步“选择设备数据库”后会弹出"Select Device for Target"对话框，如下所示。因上一步中我们选择了“STC MCU数据库(STC MCU Database)”，所以这里的MCU型号都是STC型号，用户可在左侧的数据列表(Data base)选择自己所使用的具体单片机型号。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d1ab0c5d66742d56b84db024ebf3ed7dd0874da3a94f5aa6781a9c804e7d5a94.jpg)


（6）选择好单片机型号并点击确定后，程序会询问是否将标准51初始化程序(STARTUP.51)加入到项目中，如下图所示。选择【是】按钮，程序会自动复制标准51初始化程序到项目所在目录并将其加入项目中。一般情况下，选择【否】按钮

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5b339e3f281d3ae358a0e59b4ffc991d42b643219e23c3142195510a273ac66e.jpg)


（7）项目建好后开始编写程序了，选择“File”菜单，再在下拉菜单中单击“New”选项

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/758ea68fdff85de28648165cdb35514ea3d110554fd182ff726d543ececd601e.jpg)


新建文件后界面如下图所示

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/240338b341bbbd2de1e82d9aeb5161dc2d1cedf94c757dcea4687e552f56c383.jpg)


此时光标在编辑窗口里闪烁，这时可以键入用户的应用程序了，输入程序后单击菜单上的“File”，在下拉菜单中选中“Save As”选项单击，弹出如下图所示的界面，在“文件名”栏右侧的编辑框中，键入欲使用的文件名，同时必须键入正确的扩展名。注意，如果用C语言 编写程序，则扩展名为(.C)；如果用汇编语言 编写程序，则扩展名必须为(.ASM)，扩展名不分大小写。然后，单击“保存”按钮。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/71d98b4b0fb9a637549451190557113227ca1d2045d50e2870ce6471cb942d77.jpg)


（8）将应用程序添加到项目中：单击“Target 1”前面的“＋”号，然后在“Source Group 1”上单击右键，弹出如下菜单

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5787d89671f79034e1381f659ca15c8e6e31d6daaedc0b5714b6ed56d90c3a2a.jpg)


然后单击“Add File to Group ‘Source Group 1’”，弹出如下图所示的界面

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/001f6d44529193cb0767a5f6128553b5b154485313a36c92131892f3664c8223.jpg)


选中text1.c，然后单击“Add”添加成功。

（9）环境设置：在"Target 1"上单击右键选择Options for Target 'Target1'或选择菜单命令ProjectOptions for Target 'Target1'，弹出Options for Target 'Target1'对话框。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/910b899e2d158f82aebeb8daad209e3c1cef8b3fbce017b612a518a33230ffaa.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a3ccb9ce40c28122167e3d4c6288805d88da7790cc11c37807e04f2d91f6e3f2.jpg)


使用Options for Target 'Target1'对话框设定目标的硬件环境。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b1c402bcd82d59c686867818df4f5a0c9e3243b3843c3bcc8e0b9f04988b0efe.jpg)


Options for Target 'Target1'对话框有多个选项页，用于设备(Device)选择、目标(Target)属性、输出(Output)属性、C51编译器属性、A51编译器属性、BL51连接器属性、调试(Debug)属性等信息的设置。一般情况下按缺省设置，下面介绍几个需用户自己设置的选项。

$\textcircled{1}$ 数据存储器的选择

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/64c3387d836fe85251d869e0f22b619db909f8577494df861121dfe8fa2bfbf9.jpg)


$\textcircled{2}$ 程序代码区的起始地址和结束地址默认如下图所示，默认的起始地址或结束地址是合法

的。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/26df2eadb9143cc53b7fbc3f0c12dacf9110941d577d1f52571aa9a2279cef98.jpg)


但下图的起始地址或结束地址是不合法的，用户须将其修改成为合法的起始地址和结束地址。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/6f0cfb20896e89fa6464df807697b22151bf58859660e92687aa6b64152d4acd.jpg)


具体做法如下：先勾选“Code Banking”选项，然后修改“Bank Area”的起始地址和结束地址，最后去选“Code Banking”选项(记住一定要去选此项)，点击【确定】，这样程序代码区的起始地址和结束地址就设置好了。 $, \quad , \cap$ 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a7d56d38ddb7c25de0de50ca232c6d366e8a3bf9552d2adc84616f14258b07cd.jpg)


$\textcircled{3}$ 设置在编译、连接程序时自动生成机器代码文件(.HEX)，一定要设置此项，因为默认是不输出HEX代码的，所以需用户设置。

单击“Output”中选项，在弹出的Output对话框中勾选“Create HEX File”选项(如下图所示)，使程序编译后产生HEX代码文件(默认文件名为项目文件名，也可以在“Name ofExecutable”信息框中输入HEX文件的文件名)，点击【确定】按钮结束设置。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/04aafc5e1b0256a4e71e51ce89f714b05eef768f2fcd495815afb81de26e494b.jpg)


# 二、如何在用户已建好的项目中改选STC型号MCU进行编译、调试用户程序：

# （1）启动Keil μVision4，并打开已建好的项目，如下图所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/bab626009c66ae33d3802146f30667d800717088170330ed023ea7c61b61021d.jpg)


（2）启动Keil $\mu \mathrm { V i s i o n } 4$ ，并打开已建好的项目，在弹出的对话框“Select Project File”中选择目标项目文件，点击【打开】，如下图所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/494e60e9992ccaa696298514e8e701d5e1758632c9384e6f3617741da94f5ce5.jpg)


（2）在"Target 1"上单击右键选择Options for Target 'Target1'或选择菜单命令Project Optionsfor Target 'Target1'，弹出Options for Target 'Target1'对话框，选择该对话框中“Device”页面，如下图所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/470c14954949bfdd3bd8b0fcc7e2e4e44168bca3443ebfed0dfec5cb806201ee.jpg)


可以看到此时所使用的设备数据库为“通用CPU数据库(Generic CPU Database)”，如用户所使用的单片机为STC单片机，则需更改所使用的设备数据库，具体操作见以下步骤。

（3）因之前已经通过STC-ISP下载编程工具将STC型号MCU添加到Keil μVision4的设备库中(添加方法见上文)，所以此时“Device”页面的中“Database(数据库)”有两个下拉选项“通用CPU数据库(Generic CPU Database)”和“STC MCU数据库(STC MCU Database)”，如下图所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a0ec4d41954fafb4cf908ba04bb33a35d62d20845823fd846488cedf8d1eb838.jpg)


在下拉选项中选择“STC MCU数据库(STC MCU Database)”，确定后用户可在左下侧的设备列表选择自己所使用的具体单片机型号，如下图所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/030f5be4da0eaf0183afc30d712a76cd395176ac24ec0e38fbb66c15aa37b7a9.jpg)


这样就成功地在已建好的项目中将原MCU改选成了STC型号MCU，接来接用户就可以进行编译、调试用户程序了。

# 15.2 ISP编程器/烧录器的说明

我们有: STC-ISP经济型下载编程工具

所有STC-ISP编程工具的分类如下：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b26e30539866fd56c2bcbd1a0c19e8d14d64ad814f76417ac41cb941e56d5f83.jpg)



15.2.1 在系统可编程(ISP)原理使用说明


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/07c11666f24fb554c73684481804c72950eab77682a4815029af9621d535ad63.jpg)


# 15.2.2 STC15系列在系统可编程(ISP)典型应用线路图

# 15.2.2.1 利用RS-232转换器的ISP下载典型应用线路图

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5dd6a62aaee9e3966a5e3eea01a8c7c8e0da17936192f0d9fb1e91d10c400a19.jpg)


内部高可靠

P5.4/RST/MCLKO脚出厂时默认为I/O口，可以通过 STC-ISP 编程器将其设置为RST复位脚.

内部集成高精度R/C时钟 $\left( \pm 0 . 3 \% \right)$ )， $\pm 1 \%$ 温飘 $( - 4 0 ^ { \circ } \mathrm { C } \sim + 8 5 ^ { \circ } \mathrm { C } )$ )，常温下温飘 $\pm 0 . 6 \% ( - 2 0 \% \sim + 6 5 \ \mathrm { ^ \circ C } )$ $\pm 0 . 6 \%$ )，5MHz~35MHz宽范围可设置，可彻底省掉外部昂贵的晶振

建议在Vcc和Gnd之间就近加上电源去耦电容C1 $4 7 \mu \mathrm { F } )$ ), ${ \mathrm { C } } 2 ( 0 . 1 \mu \mathrm { F } )$ , 可去除电源线噪声，提高抗干扰能力

如何产生虚拟串口: $\textcircled{1}$ 安装Windows驱动程序； $\textcircled{2}$ 插上USB-RS232转换线(若客户无USB转换线，STC提供第三方生产的USB-RS232转换线，人民币20元每条.)； $\textcircled{3}$ 确定PC端口COM：右击我的电脑—>属性—>硬件—>设备管理器—>确定所扩展的串口是PC电脑虚拟的第几个COM.

STC系列单片机具有在系统可编程 ISP) ISP的好处是：省去购买通用编程器，

单片机在用户系统上即可下载/烧录用户程序，而无须将单片机从已生产好的产品上拆下，再用通用编程器将程序代码烧录进单片机内部。有些程序尚未定型的产品可以一边生产，一边完善，加快了产品进入市场的速度，减小了新产品由于软件缺陷带来的风险。由于可以在用户的目标系统上将程序直接下载进单片机看运行结果对错，故无须仿真器。

STC系列单片机内部固化有ISP系统引导固件，配合PC端的控制程序即可将用户的程序代码下载进单片机内部，故无须编程器(速度比通用编程器快，几秒一片)。

如何获得及使用STC提供的ISP下载工具(STC-ISP.exe软件)：

# (1).获得STC提供的ISP下载工具(

登陆 www.STCMCU.com 网站，从STC半导体专栏下载PC(电脑) ISP下载工具(软件),然后将其自解压，再安装即可(执行setup.exe)， �

(2).使用STC-ISP下载工具(软件)，�� STC-ISP下载工具目前已到Ver6.57版本

支持*.bin,*.hex(Intel 16 进制格式)文件，少数*.hex文件不支持的话，请转换成*.bin文件请随 时注意升级PC(电脑)端的STC-ISP.exe软件

(3).STC系列单片机出厂时就已完全加密。需要单片机内部的电放光后上电复位(冷起动)才运行系统ISP监控 P3.0检测到合法的下载命令流就下载用户程序，如检测不到就复位到用户程序区，运行用户程序。

(4).如果用户系统接 RS-485通信电路，推荐将RS-485电路接到 [P1.6, P1.7] 或 [P3.6, P3.7]上，这样既方便又安全，�且不用 STC-ISP下载编程工具中 “下次冷启动时需$[ \mathrm { P } 3 . 2 , \mathrm { P } 3 . 3 ] = [ 0 , 0 ]$ 才可以下载程序”。

# 15.2.2.2 利用USB转串口的ISP下载典型应用线路图

特别注意：P0口可复用为地址(Address)/数据(Data)总线使用，不是作A/D转换使用。A/D转换通道在P1口。

因此：管脚图中P0.x/ADx是指P0.x管脚可作为地址(Address)/数据(Data)总线使用，而P1.x/ADCx才是指P1.x管脚可作为A/D转换通道使用。

系统电源(可从电脑USB取电)

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/2ef8ee46ad2157650de5bb9d861ffd7f0e25cd8214b69e72c9c88fec1e009336.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a1187d6caeeb587c7cfca2dfefdc2dbcde9d71bb80ef485bc002980cbd31cc32.jpg)


建议选用CH340G(管脚与CH341不兼容，但成本更低，价格低于RMB￥1.3元)，也可以选择PL2303(价格低于RMB￥1.0元)，详情请查询www.wch.cn

PL2303的生产厂家过多，兼容性不一致，建议尽量选用CH340G

注意：仅可用 [P3.0, P3.1] 作下载/仿真接口，[P3.0, P3.1] 作下载/仿真用，故建议用将串口放在 [P3.6/RxD_2, P3.7/TxD_2]或 [P1.6/RxD_3, P1.7/TxD_3] 上。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/6cc82cc820131c759a709c70535ce05d1458a51aace4f253ea6b86324dfb457e.jpg)


内部高可靠复位，可彻底省掉外部复位电路

P5.4/RST/MCLKO脚出厂时默认为I/O口，可以通过 STC-ISP 编程器将其设置为RST复位脚(高电平复位).

内部集成高精度R/C时钟 $( \pm 0 . 3 \% )$ )， $\pm 1 \%$ 温飘 $( - 4 0 ^ { \circ } \mathrm { C } \sim + 8 5 ^ { \circ } \mathrm { C } )$ )，常温下温飘 $\pm 0 . 6 \%$ (-20℃~+65℃)，5MHz~35MHz宽范围可设置，可彻底省掉外部昂贵的晶振

建议在Vcc和Gnd之间就近加上电源去耦电容C1 $( 4 7 \mu \mathrm { F } )$ , ${ \mathrm { C } } 2 ( 0 . 1 \mu \mathrm { F } )$ , 可去除电源线噪声，提高抗干扰能力

# 15.2.3 所有STC系列单片机封装实物图

STC12/11/10/89/90系列单片机的封装实物图：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/abd6e0b3fdfe0f05f29c8f8641ccde15514ff51caa03f9e27ed727c33b03a73c.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/29ecaa1844e8f25d360028345051883daa48ca1a7486362da551621e2f52be54.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d666805cff864b0d8a994349963f91a462641b80bc2200d0de2ae52ea8137e1b.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d342d8f2d1f95bee0f89adb04f5ebe3879d6111e565b9b94e6bbd791f1cec890.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5216075c27a99c4e2417823145b10c667af823c43a9347171f416fd64e530dda.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b1c639407474cb85c7daff7ab9c17b53b5169197ec0aa4a9d193b1b676cba90f.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/563a1839cd7fdbfe02518a97084a707a64503b3a41508d8bc15d75a994ec7dbf.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/65fa9d7860b6707356c80c75c26e97b9f3f178424af77842f575eeddd52934ae.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/68f94aa3ad6d5b58bb696b88a9c5c809836bbbca8bfb6cd04373242f20e30eeb.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/361c27535469f9953dba43606ef64e565e020af842a0d775a8b68e89e41a0b3a.jpg)



STC15系列单片机的封装实物图：


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ab6ff7ae1f61936691f6dead150cc906919c5108c83d338644d6fd3c0d151b6b.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d4eab5e6f6295d1bf09afcc6ecb40da144ec000edb5bae829a0741759288e561.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/406032ec560c4cf0e5b3cc7ce22af441ae58fef73a66ae9050379a9841fbbdee.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5320836e953b0c7e9637ff4ba7977ace1e03465956c161eb45ea9dca0e570da5.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5f2d8ee29707eb8710315d01798996b7ebfbe0e3ae4238269b27d34f052f499e.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/8fac8660471ae57e24c94ebaf64b2bd2bb5de5ef6c1b7491c340c4ef0e83325d.jpg)


# 15.2.4 STC-ISP下载编程工具硬件— STC-ISP下载板

# 15.2.4.1 STC15系列ISP下载板实物图

STC15系列单片机专用ISP下载编程工具实物图

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e2c12537248e2e29eb0e35ad969a225776695b2f858e056ab4a3d7dd83fc55c9.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/3318dc1c70cc474678aee83c20b2875e47e85c8168c9635701e40ffa5e7efc24.jpg)


STC15系列ISP下载编程工具与STC12/11/10/89/90系列的ISP下载编程工具不兼容，因此注意此ISP下载编程工具适用的单片机型号

STC15系列专用ISP下载编程工具 详细介绍STC-ISP下载板的布局：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/fb721fddb91b1accc2267c4352467724a493324097a056e34aa9de8784e7f59b.jpg)


# 15.2.4.2 如何将单片机安装到STC-ISP下载板上

根据用户所使用的单片机型号及管脚选择相应的STC-ISP下载板，先将下载板上的扳手向上弹起，然后将单片机插入相应的STC-ISP下载板的锁紧座上(具体做法是：将芯片的半圆缺口对准扳手的方向靠下插)，最后将扳手向下按锁紧单片机。

注意：不管是哪种STC-ISP下载编程工具，其正面焊的编程烧录用锁紧座都是40Pin的，紧座第20-Pin接的是地线(GND)，所以�请 �锁紧座的地线插 将芯片的半圆缺口对准扳手的方向靠下插。


STC15系列SKDIP28封装的插法


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/95f59341677af5502a1bdcf360d46d94401f7b733d4c97bf64fa9581f4b3d130.jpg)



STC15系列DIP-8封装的插法


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/8e7862c301d490056c0a266eaca77185db7bfd0953e7e1e608567c3b0a572c11.jpg)


# 15.2.4.3 如何使用转换座将贴片封装的单片机安装到STC-ISP下载板上

STC-ISP下载板的编程烧录锁紧座 40 Pin及40 Pin以下的LQFP、PLCC、SOP等封装的单片机需转换座将这些封装转换成直插式的封装才能插入STC-ISP下载板中。下面介绍几种常用的转换座以及如何使用这些转换座。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/736374c77fd70f7feef3dbeb20d749a0f19beb494516cc1ddfbd5d6b0342e26c.jpg)



LQFP-48的转换座(正面)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/54676c6b1241455bab19114b4717ee2dd308edad3fc9e5ab768dde99585be56d.jpg)



LQFP-48的转换座(内部)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/942552cd00d7e65ccec6d407444277039b7d3f2ae0980eac1a06a9005a2e36b3.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e34d8fb8a996d34b7631278beea3135437a86866d9ef9d1f2559d8187d33d15f.jpg)



LQFP-44的转换座(正面)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d01f01c3a732602fbb2bf3d15daed86135c4ccfd6d10f7a119bc2f6c0c3010f0.jpg)



LQFP-44的转换座(内部)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/25bb2ce88d919bd6e08c5d951ab07b3a0d8aadc33dc57d1944c970d28e3f72f5.jpg)



LQFP-44的转换座(反面)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/91b99a3dea43d9a16ed8563927ad341ae4047f5fb35581ea6dd5381d83e84324.jpg)



PLCC-44的转换座(正面)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/61323686090b7b823fe0e446146f5476b012588b6b034e7a550931056b961fe1.jpg)



PLCC-44的转换座(反面)



Pin-One


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/073de0581ec734cd7534fbc22067fc122c6921cf0858bab72f091603a7d63d0e.jpg)



PLCC-44封装实物图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e82ad7848fd9ba1ddf14f075f72874638b4f8d9aa1ce874eeb584b0fe78d48ec.jpg)



LQFP-32的转换座(正面)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/98bb7138259d42f124cc9a1cdd8bb2c8238c5dcb2b07079a8d6fc3d6d05168bc.jpg)



LQFP-32的转换座(内部)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/0988fdffc6e11294e16f0eda33d2f24e5faca8223a56049808a11d3d8b7bc455.jpg)



LQFP-32的转换座(反面)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/902cd896086ea1b65f4ac07e6093af9fe88b371ba39c510b7a24710e086a0e12.jpg)



LQFP-32封装实物图 第8脚


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c07b35b3ba0cfdc1b1fba7f3268792e80725da9af9c5d8b840ae0571895deb69.jpg)



SOP-32的转换座(正面)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/02fd83cd6fd2b340a4603b67bc7293f1183ff99184bcb385023cff8607c963fb.jpg)



SOP-32的转换座(反面)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/8bfd3ad8d8c5e65d1e191a9220dad09071dd23560b15996fe22b1b7f4ac99be4.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7cf48932ab5ecdf56584da93be00184acd3bb55c862d985cd366bedea0dd7299.jpg)



SOP-28和SOP-20



的转换座(正面)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/1517a30c50e71280a104ef4b471e5a938b723bbf2e6e54f466d33a91459bb1b2.jpg)



SOP-28和SOP-20



的转换座(反面)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d206ce843e43ca1f014c7fed6a9bdbb955380fea930f1c7a2468166d1df95704.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/eff3ed03e3619bd7e9f00dc62ee23209cada6d0fec71fa8a801139f1292e28a4.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/37c978dd2cac3029128555473f16bf2e404e8b779ff5fe3b59a32e81d8555c4c.jpg)



SOP-16和SOP-8



的转换座(正面)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/abe0ef1911d0185db5aecb70a9951e0ca7c3bc6dcca1206ba2c233cd70eea928.jpg)



SOP-16和SOP-8



的转换座(反面)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/9b48df45120a814c0327301b86f7aa66b82e458a0247a92dbb4c4a447f958fb2.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e8d79e07486eea771f1f451c71146797dd44071d72b9213025839804da8dc284.jpg)


给需转换座的单片机烧录程序的具体步骤如下：

（1）根据单片机的封装选择转换座，并将单片机安装进转换座中：

LQFP-48/LQFP-44/LQFP-32封装的单片机按下图所示安装；

$\textcircled{1}$ 打开转换座的盖子

$\textcircled{2}$ 将单片机按右图中所示转换座中

注意：单片机的第一脚(Pin-O对准转换座的左上方

$\textcircled{3}$ 盖上转换座的盖子

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a11dc76becccd937fd9e8ac9982981418a18b824e1aff8ea25c8770f1e21be38.jpg)



LQFP-48封装的单片机安装图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d11b725ffff8506d9e9186aae66c2fdda2fc2a07111255fbb4364779cb8a1a30.jpg)



LQFP-44封装的单片机安装图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/efd0a151454634860ca8074dee7358953818324bff4c10d5f1adbbfad76e733b.jpg)



LQFP-32封装的单片机安装图


PLCC-44封装的单片机按下图所示安装；

首先将单片机正对准转换座上插槽(按右图所示对准)，然后平稳地将单片机推进转换座的插槽中，直到插槽全嵌牢了单片机。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a331a16140feed7dccf6119fb1d3300a69ac33ca121f06b93839edc9abdc4f36.jpg)



PLCC-44封装的单片机安装图


SOP-32和SOP-28/20以及SOP-16/8封装的单片机按下图所示安装；

$\textcircled{1}$ 将转换座上安有弹簧的左右两边往下按

$\textcircled{2}$ 将单片机正对准转换座并靠下插入插槽中(按右图所示对准)

$\textcircled{3}$ 松开转换座上安有弹簧的左右两边

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/2490afcb6ca45902ab97f5b3ad355dc198528bfc4026039e775624be6e372d34.jpg)



SOP-32封装的单片机安装图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/74d62cc488b335ddafb3b9cc88535323d8b31cd9f0ca05ce2ead12f004a7bcba.jpg)



SOP-28封装的单片机安装图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/aa94730a509d31dca03f7deb8626d9bf69e595bfd96f9feaf7b65af36296ed07.jpg)



SOP-20封装的单片机安装图


SOP-28和SOP-20封装的单片机用同一个转换座(SOP-28转换座)，将单片机正对准转换座并靠下插入转换座的插槽中。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7a372b0b77618ef9420ceaa00ada3137891270bbd1699e4b5535347790f8bda2.jpg)



SOP-16封装的单片机安装图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e83f909e777c2f39f0f0008ae9f6463016f1636552f8a66d9d5ad7173c705e0e.jpg)



SOP-8封装的单片机安装图


SOP-16和SOP-8封装的单片机用同一个转换座(SOP-16转换座)，将单片机正对准转换座并靠下插入转换座的插槽中。

（2）将安有单片机的转换座安装在与单片机相对应的STC-ISP下载板锁紧座上，具体做法是：将转换座正对准扳手的方向靠下插。


LQFP-48/LQFP-44转换座的安装


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/1b43bf4b02da4d41c3dd34315d060c462f5a879dccbc4ec4b433da3cb8e99660.jpg)



PLCC-44转换座的安装


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ed3aab904e6392a624f8dc11623de61607b772051dad96a1a74b54ce9f144187.jpg)



LQFP-32转换座的安装


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c535484b85db33bd16dc73df9af25040fa52615b7500054be815e809e8446655.jpg)



SOP-32转换座的安装


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/0ecd904c19b6ff14c933913ffdbeae510d2fe9fb3d03f6e3b412035272fe46f8.jpg)



SOP-28转换座的安装


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/132c57d3d97cd3b0515beac128011dc4df4037b2ca42da5fa626e514df43ef5c.jpg)



SOP-16转换座的安装


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/8c49f9551af8231cd9622380b46c81d3eaf3e0c0f0240ca0d35baf939deb0ef6.jpg)


# 15.2.4.3 如何将STC-ISP下载板连接到电脑

STC-ISP下载编程工具其实就是单片机通过RS-232转换器连接到电脑序工作的

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b564a690833d919d727f9777f1101ceb71537a959da4caa768419e83d84c856a.jpg)


台式电脑或笔记本电脑PC端控制软件：

STC-ISP-15XX-V6.65 

连接线(STC提供或用户自己制作)

对于没有标准RS232串口的笔记本电脑，此处除需STC提供或用户自己制

作的连接线外，还需一条USB-RS232

转换线来扩展一个RS232串口

STC-ISP下载编程工具

用户系统或STC下载板

有些笔记本电脑没有标准RS-232串行口，需一条USB-RS232市场上有很多种USB-RS232转换线，有的是不能与STC下载板或电脑操作系统兼容 �择用CH340/CH341做的USB-RS232转换线或�让 ��购买经过测试的转换或CP2102制作的USB-RS232转换线，请尝试安装不同版本的驱动程序解决它们的不兼容问题。

# 关于硬件连接：

(1). MCU/单片机

RXD(P3.0) 

RS-232转换器

电脑

TXD(COM Port Pin3) 

(2). MCU/单片机

TXD(P3.1) 

RS-232转换器

电脑

RXD(COM Port Pin2) 

(3). MCU/单片机

GND 

电脑

GND(COM Port Pin5) 

(4). 如果您的系统接 RS-485通信电路，推荐将RS-485电路接到 [P1.6, P1.7] 或 [P3.6, P3.7]上，这样既方便又安全，�且不用 STC-ISP下载编程工具中 [P3.2, P3.3]$= [ 0 , 0 ]$ 才可以下载程序”。

(5). RS-232转换器可选用MAX232/SP232(4.5-5.5V),MAX3232/SP3232(3V-5.5V).

# STC-ISP下载板连接 ：

(1).根据单片机的工作电压在STC-ISP下载板上

A). 5V单片机 MCU-VCC和+5V电源管脚短接

B)．3V单片机 MCU-VCC和3.3V电源管脚短接

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c71de178b96970c558d73dabc0056192aff43cf8bd33c74138d86e20373bf4e9.jpg)



单片机电源电压的选择跳线短接MCU-VCC和5V电源管脚


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/022d1623699a39ad73917402c4766320c06249805872567e4c796d4db85ce8bc.jpg)


(2).将STC-ISP下载板连接到电脑端

根据用户所使用的电脑是否有RS-232串行口选择连接电脑的方式。

A).如果用户电脑有RS-232串行口，参照下图连接。

下面是STC-ISP下载板连接有RS-232串行口电脑的方式：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/344094a2b980d6a00b25e5451fef7c62fa69d1841b577b43dbf31d8482f8739a.jpg)


连接线(STC提供或用户自己制作)

$\textcircled{1}$ .将一端有9芯连接座的插头插入电脑 用于通信

$\textcircled{2} .$ 将连接线的“从电脑USB口取电”的 电脑USB接口用于取电

$\textcircled{3} .$ 将连接线中“接STC下载板”的USB插头 STC-ISP下载编程工具的USB1插座用于RS-232通信和供电

B).如果用户电脑没有RS-232串行口，参照下图连接。

下面是STC-ISP下载板连接没有RS-232串行口电脑(需一条USB-RS232转换线扩展一个RS232串行口)的方式：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b62d399c3a490a142acb2c8cbfab98c2a13448a00a6c8257c29abe98fe720c3c.jpg)


连接线(STC提供或用户自己制作)

①.将连接线中一端有9芯连接座的插头插入

$\textcircled{2} .$ 将连接线的“从电脑USB口取电”的 电脑USB接口用于取电

$\textcircled{3} .$ . USB-RS232转换线中的USB插头插入电脑USB

$\textcircled{4}$ .将连接线中“接STC下载板”的USB插头 STC-ISP下载编程工具的USB1插座用于RS-232通信和供电

(3).其他插座不需连接

(4).“系统电源开关Power ON”开关处于非按下状态，此时MCU-VCC Power灯不亮,没有给单片机通电

(5). 过 $\mathbf { \sigma } ^ { \left. \epsilon \right. } [ \mathrm { P 3 } . 2 , \mathrm { P 3 } . 3 ] = [ 0 , 0 ]$ (对于STC12系列、STC11系列、STC10系列、STC89系列及STC90系列为[P1.0, P1.1] = [0,0]) ”控制开关

处于非按下状态， $[ \mathrm { P } 3 . 2 , \mathrm { P } 3 . 3 ] = [ 1 , 1 ]$ ,不短接到地

处于按下状态， $[ \mathrm { P } 3 . 2 , \mathrm { P } 3 . 3 ] = [ 0 , 0 ]$ ,短接到地。

如果单片机已被设成“下次冷启动[P3.2, $\operatorname { P } 3 . 3 ] = [ 0 , 0 ]$ 才判P3.0有无合法下载命令流”就必须将此 � [P3.2, P3.3]短接到地

(6).将单片机插进锁紧座，锁紧单片机, 8-Pin/20-Pin/28-Pin/32-Pin/40-Pin的， 40-Pin,我们的设计是靠下插，(Gnd)

# 15.2.5 针对USB-RS232转换线不兼容问题的几点说明

有些新式笔记本电脑没有标准RS-232串行口，则需要一条USB-RS232RS-232串行口。但有些USB-RS232转换线与STC下载板或电脑操作系统是不能兼容的， �这些不兼容问题提出几点解决方法：

（1）请尽量选择用CH340/CH341制作的USB-RS232转换线

（2）对于市场上有些用PL2303或CP2102制作的USB-RS232转换线，尝试安装不同版本的驱动程序解决它的不兼容问题。

（3）尝试在STC-ISP控制下载软件中将最高波特率和最低波特率设置为相等且都为2400，重新连接。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/8036b9ceed7ca450e5ba6efa9817355ac41e715099c80ef6ebf89109f4f5b958.jpg)


（4）�让 �帮您购买经过测试的转换

# 15.2.6 如何用STC-ISP下载板给在用户系统上的单片机烧录用户程序

利用STC系列ISP下载编程工具( RS-232转换器连接到电脑RS-232转换

# 单片机在用户自己的板上完成下载/烧录：

1．U1-Socket锁紧座不得插入单片机

2．将用户系统上的电源(MCU-VCC,GND)及单片机的[P3.0, P3.1]接入转换板 ���插座”，如下图所示， 电脑进行通信的能力

3．将用户系统的单片机的[P3.2, P3.3] (对于STC12系列、STC11系列、STC10系列、STC89系列及STC90系列为[P1.0, P1.1])接入转换板 ���芯 (如果需要的话)

4．如须 [P3.2, $\mathrm { P } 3 . 3 ] = [ 0 , 0 ] ,$ ,短接到地，可在用户系统上将其短接到地，或将 [P3.2, P3.3]也从用户系统引到STC系列ISP下载编程工具 (其实就是单片机通过RS-232到电脑 控制[P3.2, P3.3] 同时为[0, 0]的开关”按下，则 $[ \mathbf { P } 3 . 2 , \mathbf { P } 3 . 3 ] = [ 0 , 0 ]$ 。

5. 将STC-ISP下载板连接到电脑上进行RS232通信(具体连接方式见下页图

6. 给单片机上电复位(注意是从用户系统自供电，不要从电脑USB取电,电脑USB座不插)

7. 关于软件：选择“Download/下载”

8. 下载程序时，如用户板有外部看门狗电路，不得启动，单片机必须有正确的复位,但不能在ISP下载程序时被外部看门狗复位， �空

9. 如系统接 RS-485通信电路，推荐将RS-485电路接到[P1.6, P1.7]或[P3.6, P3.7]上，这样既方便又安全，�且不用 STC-ISP下载编程工具中 [P3.2, P3.3]$= [ 0 , 0 ]$ 才可以下载程序”

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/742baf94d9d0f3793e0c8ed616e846e7f886dd6d4b84488f4647f9042428729e.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e89f3ba3b8dea9865bef88b236533105edd43b0a323fe9b7c210fff857102df0.jpg)



用户系统



将用户系统按上图所示连接到STC-ISP下载板上


用户系统，可以直接给用户系统的单片机烧录程序，无需将已焊好的用户系统拆卸下来烧录。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/49ade0be1114bb910fbd1dd2c7de6cf4c21a330b1e5a53df7ad159afdf2771a8.jpg)


将连有用户系统的STC-ISP下载板按左图所示连接到电脑上，注意以下几点：

（1）STC-ISP下载板的锁紧座不得插入单片机

（2）“从电脑USB口取电”的USB插头悬空，不要插入电脑，因为是从用户系统自供电

（3）接STC下载板的USB插头仅用于RS232通信。

# 15.2.7 电脑端的STC-ISP控制软件(Ver6.65)的界面使用说明

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/9d585e24cf21c7005016aa752d2381daa54fd608c98474a9fb6e32fb79b3e508.jpg)


最新的ISP下载控制软件V6.65的界面如上图所示。该软件新增了许多新功能(如扫描当前系统中可用的串口、波特率计算器、软件延时计算器、选型/价格/样品表等)。下文将详细介绍该STC-ISP-V6.65软件的各个功能。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ae0398a62006eafa6a84208988aae91bd9399b4d8ca271419d164255ae9db2dc.jpg)


点击界面上的注意/帮助按钮后出现下面的对话框：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/49ebeae49a6a952276916efdc89b33e51a9c75dcacdfee373c5490b3c259f1e3.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/86d91073a02552dbe24dc164251b7591f8aa9399d3efe2ad7c5fcd48795b0ce6.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/aa7a49814e66c07387926f9544e50f77f79c8a6b8b27a8f9f0d087b5741c94cb.jpg)


# 脱机下载界面：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b15060c5a4a0caed4d5cca8df5adafc3a6b1fe588d987affa5da8101e955dd6a.jpg)


# RS485控制界面：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/71ea4d486ba5b55a5dc72e278ac4a611597128e8496a05b9c2100b83bb33fb3f.jpg)



串口助手界面：


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5c213f2b7a9debad2ae26fb4a5f2543118fde846b5659e924510a2349caebb68.jpg)


在串口助手工具选择页上单击鼠标右键进行选择，可以将串行口助手从STC-ISP下载编程软件的主界面中独立出来(如下所示)，关闭独立使用的工具可以再次返回主界面。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/af00b470ba39d2792224019f387f933228a781e7183699df6501708653826a2e.jpg)


最新的STC-ISP-V6.65软件集成了波特率计算器，利用波特率计算器可以很方便地求出波特率，并可以生成相应的代码(C或ASM代码)。波特率计算器界面如下所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/0d420360642bdcf1d88b3205c83be694d3682fabba016e98d1f1f9449710eb7c.jpg)


最新的STC-ISP-V6.65软件还集成了定时器计算器，定时器计算器也可以生成相应的代码(C或ASM代码)，根据用户的设置对定时器的各相关寄存器进行初始化。定时器计算器界面如下所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/3e53bd902ccd0f0b8964ab7d2caf7079c3b7f5b87a87ec95551bb3b17352d1bf.jpg)


另外，最新的STC-ISP-V6.65软件还集成了软件延时计算器，软件延时计算器也可以生成相应的代码(C或ASM代码)，根据用户的设置可以生成相应的延时子函数。软件延时计算器界面如下所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e330dce928c94526a40ea27a5b2460ee9722e58346b02caf27bba21eac789d4b.jpg)


除串口助手外，波特率计算器、定时器计算器、软件延时计算器都可以从STC-ISP下载编程软件的主界面中独立出来，关闭独立使用的工具可以再次返回主界面。

最新的STC-ISP-V6.65软件还设计了“Keil仿真设置”选项，如下图所示

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c7647bc5ddaaa3e0880531945fd7aeb087f479bdfedacbbc6142655682370b74.jpg)


最新的STC-ISP-V6.65软件还包含了头文件，供用户查询和复制。头文件如下所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/505b1ff29c85a4973456573e12f92d0bc5f25c21e6e8ea334aed60697c239a99.jpg)


另外，用户还可以在最新的STC-ISP-V6.65软件中查询STC系列单片机的选型和价格。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c31358170f8683b92efd85996561b84c81ce2d05b6df07f69adaaa313cefa13d.jpg)


# 15.2.8 STC-ISP控制软件(Ver6.65)发布项目程序使用说明

发布项目程序功能主要是将用户的程序代码与相关的选项设置打包成为一个可以直接对目标芯片进行下载编程的超级简单的用户自己界面的可执行文件。

关于界面，用户可以自己进行定制（用户可以自行修改发布项目程序的标题、按钮名称以及帮助信息），同时用户还可以指定目标电脑的硬盘号和目标芯片的ID号，指定目标电脑的硬盘号后，便可以控制发布应用程序只能在指定的电脑上运行(防止烧录人员将程序轻易从电脑盗走,如通过网络发走,如通过U盘烤走,防不胜防,当然盗走你的电脑那就没办法那,所以STC的脱机下载工具比电脑烧录安全,能限制可烧录芯片数量,让前台文员小姐烧,让老板娘烧都可以)，拷贝到其它电脑，应用程序不能运行。同样的，当指定了目标芯片的ID号后，那么用户代码只能下载到具有相应ID号的目标芯片中(对于一台设备要卖几千万的产品特别有用---坦克,可以发给客户自己升级,不需冒着生命危险跑到战火纷飞的伊拉克升级软件啦)，对于ID号不一致的其它芯片，不能进行下载编程。

发布项目程序详细的操作步骤如下：

1、首先选择目标芯片的型号

2、打开程序代码文件

3、设置好相应的硬件选项

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/4ed19b98fc5a84721e1a10b0d15e90a9f1b9a813ceb8ec93b39640793c9b4bb7.jpg)


4、试烧一下芯片，并记下目标芯片的ID号，如下图所示，该芯片的ID号即为“000D001100641D”（如不需要对目标芯片的ID号进行校验，可跳过此步）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/dd9ee8db26320ffca21d981aba9dbdbf75d05af7ecb9b756fdfb0de4be846734.jpg)


5、设置自动增量（如不需要自动增量，可跳过此步

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/4a1ac0b215fe9460e65fcc4fe82ace0dd17920a7ff3469cbece7312d94b509c3.jpg)


6、设置RS485控制信息（如不需要RS485控制，可跳过此步）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/89725307684a563cb53fe2ef8ac20f6d13484a976c9a1ee567589a607fd5541a.jpg)


# 7、设置“收到用户命令后ISP下载”（如不需要此功能，可跳过此步）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5d77850b602a25191aaa26735d3c039d22ab3b9cc1f8b6e4c39dfc87ff426881.jpg)


8、点击界面上的“读取本机硬盘号”按钮，并记下目标电脑的硬盘号（如不需要对目标电脑的硬盘号进行校验，可跳过此步）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5e789f1c65c41571518b7ad562580731efdb3dd70c8e72e62cf0a1475ea43496.jpg)


9、点击“发布项目程序”按钮，进入发布应用程序的设置界面。

10、根据各自的需要，修改发布软件的标题、下载按钮的名称、重复下载按钮的名称、自动增量的名称以及帮助信息

11、若需要校验目标电脑的硬盘号,则需要勾选上“校验硬盘号”，并在后面的文本框内输入前面所记下的目标电脑的硬盘号

12、若需要校验目标芯片的ID号，则需要勾选上“校验芯片ID号”，并在后面的文本框内输入前面所记下的目标芯片的ID号

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e53eead32bbecdc9552b82575d00042e30ca53fb90174621d9ea251d8457183c.jpg)


校验目标电脑的硬盘号，则需要勾选上“校验硬盘号”

13、最后点击发布按钮，将项目发布程序保存，即可得到相应的可执行文件。如下图，设置界面中所定制的内容与发布文件是一一对应的。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/333086d54cf2ba5c1a7d05dd18e9921904792e8eccd5046c2d56ea2e9820d1fe.jpg)


注意：

校验硬盘号与校验目标芯片ID号的功能仅对如下系列及新出的单片机有效：

STC15F2K60S2/STC15L2K60S2 

IAP15F2K61S2/IAP15L2K61S2 

STC15F101W/STC15L101W 

IAP15F105W/STC15L105W 

STC15W104SW/IAP15W105W 

# 15.2.9 “程序加密后传输”功能说明

# 防止烧录时通过串口分析出程序代码

目前，所有的普通串口下载烧录编程都是采用明码通信的(电脑和目标芯片通信时,或脱机下载板和目标芯片通信时)，问题: 如果烧录人员通过分析下载烧录编程时串口通信的数据,高手是可以在烧录时在串口上引2根线出来,通过分析串口通信的数据分析出实际的用户程序代码的。当然用STC的脱机下载板烧程序总比用电脑烧程序强(防止烧录人员将程序轻易从电脑盗走,如通过网络发走,如通过U盘烤走,防不胜防,当然盗走你的电脑那就没办法那,所以STC的脱机下载工具比电脑烧录安全,让前台文员小姐烧,让老板娘烧都可以)。即使是STC全球首创的脱机下载工具,对于要防止天才的不法分子在脱机下载工具烧录的过程中通过分析串口通信的数据，分析出实际的用户程序代码，也是没有办法达到要求的，这就需要用到最新的STC15系列单片机所提供的“程序加密后传输”功能。目前，我司是全球第一家可以防范用户将程序代码给烧录人员烧录时烧录人员通过串口分析出目标程序代码的公司。

“程序加密后传输”功能是用户先将程序代码通过自己的一套专用密钥进行加密，然后将加密后的代码再通过串口下载，此时下载传输的是加密文件，通过串口分析出来的是加密后的乱码,如不通过派人潜入你公司盗窃你电脑里面的加密密钥,就无任何价值,便可起到防止在烧录程序时被烧录人员通过监测串口分析出代码的目的。

“程序加密后传输”功能的使用需要如下的几个步骤：

# 1、生成并保存新的密钥

如下图，进入到“程序加密后传输”页面，点击“生成新密钥”按钮，即可在缓冲区显示新生成的256字节的密钥。然后点击“保存密钥”按钮，即可将生成的新密钥保存为以“.K”为扩展名的的密钥文件（注意：这个密钥文件一定要保存好，以后发布的代码文件都需要使用这个密钥加密，而且这个密钥的生成是非重复的，即任何时候都不可能生成两个完全相同的密钥，所以旦密钥文件丢失将无法重新获得）, 例如我们将密钥保存为“New.k”。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/173b34ca27721669ef831ec784d3aa610c89fc7208f515dfd7b543b829ebc838.jpg)


# 2、对代码文件加密

加密文件前，需要先打开我们自己的密钥。若缓冲区中存放的已经是我们的密钥，则不要再打开。如下图，在“自定义加密下载”页面中点击“打开密钥”按钮，打开我们之前保存的密钥文件，例如“New.k”。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/19d0a85e1b3afdce35f8113492b6324af26a3e05e2bc09e11d58ed335d311fbb.jpg)


然后返回到“程序加密后传输”页面中点击“加密代码”按钮，如下图所示，首先会弹出“打开源文件（未加密）”的对话框，此时选择的是原始的未加密的代码文件。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/9f7ba66589354a49fb81c5aaf8a7d619eaf696f8d393d5d06f19a6c6199258b6.jpg)


# 3、将用户密钥更新到目标芯片中

更新密钥前，需要先打开我们自己的密钥。若缓冲区中存放的已经是我们的密钥，则不要再打开。如下图，在“程序加密后传输”页面中点击“打开密钥”按钮，打开我们之前保存的密钥文件，例如“New.k”。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d9739979d7a8682061d93cc3a109aa13f9daa8fbf60df7ed67091c741b30540a.jpg)


密钥打开后，如下图所示，勾选上“下载用户代码前先更新用户密钥”选项和“本次下载的代码为加密代码”的选项，然后打开我们之前加密过后的文件，打开后点击界面左下角的“下载/编程”按钮，按正常方式对目标芯片下载完成即可更新用户密钥。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7cd47d1dcb519dee40ec3c89483a60c77528f49ba14601eef308ad7eb8f6c333.jpg)


# 4、加密更新用户代码

密钥更新成功后，目标芯片便具有接收加密代码并还原的功能。此时若需要再次升级/更新代码，则只需要参考第二步的方法，将目标代码进行加密，然后如下图

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/fe2d9d1934c39d4bc6e940cdcf08a62b773a5cc9fba366136c4ef1aecee99206.jpg)


首先在“程序加密后传输”页面中选择“本次下载的代码为加密代码”的选项（“下载用户代码前先更新用户密钥”选项不需要选了），然后打开我们之前加过密后的文件，打开后点击界面左下角的“下载/编程”按钮，按正常方式对目标芯片下载即可完成用用户自己专用的加密文件更新用户代码的目的(防止在烧录程序时被烧录人员通过监测串口分析出代码的目的)。

注意：

“程序加密后传输”功能仅对如下系列及新出的单片机有效：

STC15F2K60S2/STC15L2K60S2 

IAP15F2K61S2/IAP15L2K61S2 

STC15F101W/STC15L101W 

IAP15F105W/STC15L105W 

STC15W104SW/IAP15W105W 

# 15.2.10 "发布项目程序"+"程序加密后传输"结合使用

“发布项目程序”与“程序加密后传输”两项新的特殊功能可以结合在一起使用。首先“程序加密后传输”可以确保用户代码在烧录编程时串口通信传输过程当中的保密性，而"发布项目程序"可实现让最终使用者远程升级功能（方案公司的人员不需要亲自到场）。所以两项功能结合起来使用，非常适用于方案公司/生产商在软件需要更新时,让最终使用者自己对终端产品进行软件更新的目的, 又确保现场烧录人员无法通过串口分析出有用程序, 强烈建议方案公司使用。

下面用具体的实例来举例说明"发布项目程序"与“程序加密后传输”结合使用的方法，首先讲解代码的加密以及加密芯片的制作方法

# 1、生成并保存新的密钥

如下图，进入到“程序加密后传输”页面，点击“生成新密钥”按钮，即可在缓冲区显示新生成的256字节的密钥。然后点击“保存密钥”按钮，即可将生成的新密钥保存为以“.K”为扩展名的的密钥文件（注意：这个密钥文件一定要保存好，以后发布的代码文件都需要使用这个密钥加密，而且这个密钥的生成是非重复的，即任何时候都不可能生成两个完全相同的密钥，所以一旦密钥文件丢失将无法重新获得）。比如我们将密钥保存为“New.k”。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a629ea2586a28d8d5839c799dfed8ce916b495d5be3057ed9f899ae412651a58.jpg)


# 2、代码文件加密

加密文件前，需要先打开我们自己的密钥。若缓冲区中存放的已经是我们的密钥，则不要再打开。如下图，在“自定义加密下载”页面中点击“打开密钥”按钮，打开我们之前保存的密钥文件，例如“New.k”。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/0b0fd85b1f489217760a62d616f357ca7af841b2b07460a35bd7c37a9026493a.jpg)


然后返回到“程序加密后传输载”页面中点击“加密代码”按钮，如下图所示，首先会弹出“打开源文件（未加密）”的对话框，此时选择的是原始的未加密的代码文件

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/3d55c501593fb1fdd09872d53f185a32b02ed73b718862aa51cda9e42a63112f.jpg)


点击打开按钮后，马上有会弹出一个类似的对话框，但此时是对加密后的文件进行保存的对话框。如下图所示，点击保存按钮即可保存加密后的文件。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e2ff517f3889eb6592d288ae9d7c6b87f2fbde2b88de4a8d8f0163fa0b5964ce.jpg)


# 3、将用户密钥更新到目标芯片中

更新密钥前，需要先打开我们自己的密钥。若缓冲区中存放的已经是我们的密钥，则不要再打开。如下图，在“程序加密后传输”页面中点击“打开密钥”按钮，打开我们之前保存的密钥文件，例如“New.k”。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/084ec52b475f3d2a8d67aeacf967b1054126e15ca90eec5f2c49d485378daa1f.jpg)


密钥打开后，如下图所示，勾选上“下载用户代码前先更新用户密钥”选项和“本次下载的代码为加密代码”的选项，然后打开我们之前加密过后的文件，打开后点击界面左下角的“下载/编程”按钮，按正常方式对目标芯片下载完成即可更新用户密钥。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/054cf0906a3050a146193a3e553cfc5b499ca2ff2ac71db94c4a179196734045.jpg)


经过上面的三步，此时的目标芯片便具有还原加密代码的功能。便可将目标芯片提供给终端客户使用。

下面讲解如何发布加密项目程序

1、首先选择目标芯片的型号

2、打开程序代码文件

3、设置好相应的硬件选项

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/1528d7cea803b97f99b76922cd00f356fe538de618f75344d2ab3ea595c9915f.jpg)


4 、 试 烧 一 下 芯 片 ， 并 记 下 目 标 芯 片 的 I D 号 ， 如 下 图 所 示 ， 该 芯 片 的 I D 号 即 为“000D001100641D”（如不需要对目标芯片的ID号进行校验，可跳过此步）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/3399cd4bc7c424816fe026bc7578c45676b5f6bf189f4a2c7e261ab3ab579632.jpg)


5、在“程序加密后传输”页面中选择“本次下载的代码为加密代码”选项（注意：加密下载时不支持自动增量）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a3d167ae95302e6aae9117332fdd5abc548181242bbfbc1ce8678343517ddca4.jpg)


6、设置RS485控制信息（如不需要RS485控制，可跳过此步）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ec91634f3186ea351da7e7a7359884c2be326f982194d1884ff9858c01dda519.jpg)


# 7、设置“收到用户命令后ISP下载”（如不需要此功能，可跳过此步）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/6ce9713db25e16c469b409951a96739159a8562ced86517453a9136512b015c8.jpg)


# 8、点击界面上的“读取本机硬盘号”按钮，并记下目标电脑的硬盘号（如不需要对目标电脑的硬盘号进行校验，可跳过此步）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/22772c9b0c07578d501da37b8a740af5767f441beaf146a2f1958dfd2c14b081.jpg)


9、点击“发布项目程序”按钮，进入发布应用程序的设置界面。

10、根据各自的需要，修改发布软件的标题、下载按钮的名称、重复下载按钮的名称、自动增量的名称以及帮助信息

11、若需要校验目标电脑的硬盘号,则需要勾选上“校验硬盘号”，并在后面的文本框内输入前面所记下的目标电脑的硬盘号

12、若需要校验目标芯片的ID号，则需要勾选上“校验芯片ID号”，并在后面的文本框内输入前面所记下的目标芯片的ID号

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/525588057da0d1864ede41db4a97fb465a1b96f9b0924ee5d10b5b3be1d6f46f.jpg)


13、最后点击发布按钮，将项目发布程序保存，即可得到相应的可执行文件。如下图，设置界面中所定制的内容与发布文件是一一对应的。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/77dea949907b62fcd8bd473f884355523eac799b5426b3107acf13bc0f9455d7.jpg)


上面的整个步骤基本与发布项目程序的步骤相一致，唯一不同的地方是打开的不是原始文件，而是加密后的文件，而且一定要勾选上“本次下载的代码为加密代码”的选项。

# 15.2.11 运行用户程序时收到用户命令后自动启动ISP下载(不停电)

“运行用户程序时收到用户命令后自动启动ISP下载”（即软件中的“收到用户命令后ISP下载”）与“程序加密后传输”是两种完全不同功能。相对“程序加密后传输”的功能而言，“运行用户程序时收到用户命令后自动启动ISP下载”的功能要简单一些。

具体的功能为：电脑或脱机下载板在开始发送真正的ISP下载编程握手命令前，先发送用户自定义的一串命令（关于这一串串口命令，用户可以根据自己在应用程序中的串口设置来设置波特率、校验位以及停止位），然后再立即发送ISP下载编程握手命令。

“运行用户程序时收到用户命令后自动启动ISP下载”这一功能主要是在项目的早期开发阶段，实现不断电（不用给目标芯片重新上电）即可下载用户代码。具体的实现方法是：用户需要在自己的程序中加入一段检测自定义命令的代码，当检测到后，执行一句“MOVIAP_CONTR,#60H”的汇编代码或者“IAP_CONTR = 0x60;”的C语言 代码，MCU就会自动复位到ISP区域执行ISP代码。

如下图所示，将自定义命令设置为波特率为115200、无校验位、一位停止位的命令序列：0x12、0x34、0x56、0xAB、0xCD、0xEF、0x12、。当勾选上“每次下载前都先发送自定义命令”的选项后，即可实现自定义下载功能

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d33a3b134912bb920417cfd143994f3f733849ec2f7a53b10788596a8ea20dd0.jpg)


点击“发送用户自定义命令开始下载”或者点击界面左下角的“下载/编程”按钮，应用程序便会发送如下所示的串口数据

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a720a0278edc9309fbb849c935d043d828c1ac3d261ec1ddd4d8a37255a805a2.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ed62c2767c4b95d034382321ce2b0d43ef702749694f758b76f7d51da2a6f281.jpg)


# 15.2.12 用户接口

STC-ISP-V6.65下载编程软件新增了用户接口软件，如下图所示。用户接口功能主要实现了保留用户芯片中的重要信息（如：序列号）不被破坏的作用。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d2a12af19461500090cd2c0acc2ed26a3a9405ad653a8d0ab3862b461a9b8a7c.jpg)


使用用户接口功能时，PC机或者U7编程器首先与用户单片机通讯，将单片机的重要信息(如：序列号等)读取出来并保存，然后用户可以设置发送给用户代码的自定义命令(如设置发送给用户代码的读数据命令或复位命令)，用户代码可以接收自定义命令。当用户代码收到复位命令后可以控制目标单片机自动复位，若用户未设置复位命令，则用户需手动给目标单片机重新上电，当目标单片机上电复位后，就开始更新代码了，此时更新的代码包括上述PC机或U7编程器所保存的重要信息和用户新代码，即将PC机或U7编程器所保存的重要信息和用户新代码一并写入了目标单片机中，从而实现了保留目标单片机中的重要信息不被破坏的目的。

注意：只有使用普通串口或USB转串口直接对单片机进行在线下载或者使用U7编程器进行脱机下载时，用户接口功能才可用；当使用U7编程器在线联机下载时，用户接口功能并不可用。

# 15.2.13 RS485控制使用说明

由于RS485相比RS232具有抑制共模干扰、传输距离长等优点，所以许多大型的工业设备都采用RS485进行串口通讯。但由于RS485采用的是差分信号，所以在进行串口通讯时，只能采用半双工的工作方式，必须使用1个或2个I/O口来控制RS485的发送和接收状态。当需要采用RS485来对STC的新版IC（支持RS485下载的单片机系列在后面会详细列出）进行ISP下载时，必须进行一些设置才可下载代码。

具体的操作步骤如下：

1、首先需要设置好相应的RS485控制端口，并勾选上“下次下载时使能目标芯片的RS485控制功能”这个选项

2、然后使用普通下载方式将RS485相关的硬件选项写入到目标芯片

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/47085b52cac0d6e3c7bfebd150fe781924129ccb977791ee2e58975cc35614d9.jpg)


3、经过前面两步的设置和编程，此时的目标芯片便具有了对RS485的控制功能。接下来仍需要保持RS485的控制选项不变，并勾选上"本次使用RS485进行控制下载"的选项（此选项的作用是使PC端也采用RS485的控制方式进行发送/接收串口数据）

4、再点击下载编程按钮，并对目标芯片重新上电即可实现使用RS485进行通信下载的功能

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/deb83cd05c3d394952b65598e09100d2a9c19fe0a314c012e5572f015144bb12.jpg)


RS485控制功能仅对如下系列及新出的单片机有效：

STC15F2K60S2/STC15L2K60S2 

IAP15F2K61S2/IAP15L2K61S2 

STC15F101W/STC15L101W 

IAP15F105W/STC15L105W 

STC15W104SW/IAP15W105W 

特别注意：

若需要RS485控制功能，则每次都需要将RS485相关的配置设置正确，并勾选上“下次下载时使能目标芯片的RS485控制功能”这个选项，否则在下一次下载时将不具有RS485控制功能了

# 15.3 若无仿真器，如何调试/开发用户程序

STC单片机部分系列无仿真器，如 $\operatorname { S T C 8 9 \mathrm { x } \mathrm { x } }$ 系列、STC90xx系列等，但长沙菊阳微电子有限公司以及南京伟福实业有限公司均有通用的STC89xx、STC90xx系列单片机仿真器购买。当然部分STC单片机也有自己的仿真器，如最新的STC15系列。

现介绍在没有仿真器的情况下如何调试和开发用户程序，具体操作步骤如下：

1.首先参照本手册当中的“用定时器1做波特率发生器”，调通串口程序，这样，要观察变量就可以自己写一小段测试程序将变量通过串口输出到电脑端的STC-ISP.EXE的“串口调试助手”来显示,也很方便。

2.调通按键扫描程序(到处都有大量的参考程序)

3.调通用户系统的显示电路程序，此时变量/寄存器也可以通过用户系统的显示电路显示了

4.调通A/D检测电路(我们用户手册里面有完整的参考程序)

5.调通PWM等电路(我们用户手册里面有完整的参考程序)

这样分步骤模块化调试用户程序，有些系统，熟练的8051用户，三天就可以调通了，难度不大的系统，一般一到二周就可以调通。

用户的串口输出显示程序可以在输出变量/寄存器的值之后，继续全速运行用户程序，也可以等待串口送来的“继续运行命令”，方可继续运行用户程序，这就相当于断点。这种断点每设置一个地方，就必须调用一次该显示寄存器/变量的程序，有点麻烦，但却很实用。

# 15.4 STC仿真器说明指南

# 1. 仿真器的参考硬件图

# （1）利用RS-232转换器连接电脑的的仿真应用线路图

特别注意：P0口可复用为地址(Address)/数据(Data)总线使用，不是作A/D转换使用。A/D转换通道在P1口。

因此：管脚图中P0.x/ADx是指P0.x管脚可作为地址(Address)/数据(Data)总线使用，而P1.x/ADCx才是指P1.x管脚可作为A/D转换通道使用。

系统电源(可从电脑USB取电)

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/547f557b45a65b7fd6136d9348882a0256ba3911b58eae90d40f731bf02fef0f.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/4059e36278b8b19c881af85541ad1fbb69ff22cc430ecf40adfea970022c751c.jpg)



注意：仅可用 [P3.0, P3.1] 作下载/仿真接口，因[P3.0, P3.1] 作下载/仿真用，故建议用将串口1放在 [P3.6/RxD_2, P3.7/TxD_2或 [P1.6/RxD_3, P1.7/TxD_3] 上。


# STC 单片机

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/adc05884d10b6de710bc2b4ee6f7746965e00c42ae8ad32bd6e49cbeec7aa422.jpg)


内部高可靠复位，可彻底省掉外部复位电路，当然也可以使用外部复位电路

P5.4/RST/MCLKO脚出厂时默认为I/O口，可以通过 STC-ISP 编程器将其设置为RST复位脚(高电平复位).

内部集成高精度R/C时钟 $( \pm 0 . 3 \% )$ )， $\pm 1 \%$ 温飘 $( - 4 0 ^ { \circ } \mathrm { C } \sim + 8 5 ^ { \circ } \mathrm { C } )$ )，常温下温飘 $\pm 0 . 6 \% ( - 2 0 \% \sim + 6 5 \% )$ )，5MHz~35MHz宽范围可设置，可彻底省掉外部昂贵的晶振，当然也可以使用外部晶振

建议在Vcc和Gnd之间就近加上电源去耦电容C1 $( 4 7 \mu \mathrm { F } )$ ), ${ \mathrm { C } } 2 ( 0 . 1 \mu \mathrm { F } )$ , 可去除电源线噪声，提高抗干扰能力

# （2）利用USB转串口连接电脑的仿真典型应用线路图

特别注意：P0口可复用为地址(Address)/数据(Data)总线使用，不是作A/D转换使用。A/D转换通道在P1口。

因此：管脚图中P0.x/ADx是指P0.x管脚可作为地址(Address)/数据(Data)总线使用，而P1.x/ADCx才是指P1.x管脚可作为A/D转换通道使用。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ca48e1933d72e74051ca332a40cdf6d037797af1f381aac6d7bb2139117d5e53.jpg)


建议选用兼容，但￥1.3元)，格低于RMwww.wch.

PL2303的一致，建

注意：仅可[P3.将串或

内部高可靠复位，可彻底省掉外部复位电路

P5.4/RST/MCLKO脚出厂时默认为I/O口，可以通过 STC-ISP 编程器将其设置为RST复位脚(高电平复位).

内部集成高精度R/C时钟 $( \pm 0 . 3 \%$ )， $\pm 1 \%$ 温飘 $( - 4 0 ^ { \circ } \mathrm { C } \sim + 8 5 ^ { \circ } \mathrm { C }$ )，常温下温飘 $\pm 0 . 6 \%$ (-20℃~+65℃)，5MHz~35MHz宽范围可设置，可彻底省掉外部昂贵的晶振

建议在Vcc和Gnd之间就近加上电源去耦电容C1 $( 4 7 \mu \mathrm { F } )$ , ${ \mathrm { C } } 2 ( 0 . 1 \mu \mathrm { F } )$ , 可去除电源线噪声，提高抗干扰能力

# 2. 软件环境

对于汇编语言 程序,复位入口的程序必须是长跳转指令,可使用如下语句

ORG 0000H 

;复位入口地址

LJMP RESET 

;使用LJMP指令

;其它中断向量

ORG 100H 

;用户代码地址

RESET: 

;复位入口

;用户代码

# 3. 仿真代码占用的资源

程序空间 :仿真代码占用程序区最后6K字节的空间

如果用IAP15F2K61S2/IAP15L2K61S2单片机仿真时，用户程序只能占55K

(0x0000~0xDBFF)空间,用户程序不要使用从0xDC00到0xF3FF的6K字节空间

常规RAM（data,idata） : 0字节

XRAM(xdata) : 768字节(0x0400 – 0x06FF, 用户在程序中不要使用)

I/O : P3.0 / P3.1 

用户在程序中不得操作P3.0/P3.1, 不要使用INT4/T2CLKO/P3.0, 不要使用T2/P3.1

不要使用外部中断INT4,不要使用T2的时钟输出功能，不要使用T2的外部计数功能对于IAP型号单片机，对EEPROM的操作是通过对多余不用的

程序区进行IAP模拟实现的，此部分要修改程序(IAP起始地址)。

如IAP15F2K61S2单片机的EEPROM区的位置如右图所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/bda6d72d28338bcdbe4339f71bd6caabbd7fbd0b09280f78b96b6ffa976f2455.jpg)


# 4. 仿真器操作步骤

（1）安装Keil版本的仿真驱动，如下图所示:

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/1689e9d76a41f2925eb93c4042c0a3c37949e3052ed025382ce98886bfabdb8f.jpg)


如上图，首先选择“Keil仿真设置”页面，点击“添加MCU型号到Keil中”，在出现的如下的目录选择窗口中，定位到Keil的安装目录(一般可能为“C:\Keil\”)，“确定”后出现下图中右边所示的提示信息，表示安装成功。添加头文件的同时也会安装STC的Monitor51仿真驱动STCMON51.DLL，驱动与头文件的的安装目录如上图所示。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/f6010969f2d4f941a62bac34702d09e1aece4939c871fc943e7ae2de269492f7.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/f63984dd86681b6cf89fe5fecd750dd590506e266e794bc67ef359b01941b778.jpg)


# （2）在Keil中创建项目

若第一步的驱动安装成功，则在Keil中新建项目时选择芯片型号时，便会有“STC MCUDatabase”的选择项，如下图

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/609145a804d88e28dc9a4372dd2f4618ec14b8c23821439e65994860e9e8cdd2.jpg)


然后从列表中选择响应的MCU型号（目前STC支持仿真的型号只有STC15F2K60S2），所以我们在此选择“STC15F2K60S2”的型号，点击“确定”完成选择

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5fe6205578476737b43fbd601ce726a48592b2e466f4ce9499c0154993696dad.jpg)


添加源代码文件到项目中，如下图：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/2e56792d4cd6cb90dc543e0105163d97a746a45855ba53781dac5c6a15e9a9d8.jpg)


保存项目，若编译无误，则可以进行下面的项目设置了

附加说明一点：

当创建的是C语言 项目，且有将启动文件“STARTUP.A51”添加到项目中时，里面有一个命名为“IDATALEN”的宏定义，它是用来定义IDATA大小的一个宏，默认值是128，即十六进制的80H，同时它也是启动文件中需要初始化为0的IDATA的大小。所以当IDATA定义为80H，那么STARTUP.A51里面的代码则会将IDATA的00-7F的RAM初始化为0；同样若将IDATA定义为0FFH，则会将IDATA的00-FF的RAM初始化为0。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ffdf7ae8698f307f3331410ccd96661f4104c99487e85138538bc35448f27001.jpg)


虽然STC15F2K60S2系列的单片机的IDATA大小为256字节（00-7F的DATA和80H-FFH的IDATA），但由于STC15F2K60S2在RAM的最后17个字节有写入ID号以及相关的测试参数，若用户在程序中需要使用这一部分数据，则一定不要将IDATALEN定义为256。


（3）项目设置，选择STC仿真驱动


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7911ec7caf65b4ef35745b2c8360849e1b80f312bf66a3bb7f1c7338805de978.jpg)


如上图，首先进入到项目的设置页面，选择“Debug”设置页，第2步选择右侧的硬件仿真“Use…”，第3步，在仿真驱动下拉列表中选择“STC Monitor-51 Driver”项，然后点击“Settings”按钮，进入下面的设置画面，对串口的端口号和波特率进行设置，波特率一般选择115200或者57600。到此设置便完成了。

# （4）创建仿真芯片

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/94a8c4b242e6622851dd1fc1cf6e3afbc16342e74c9739315963089cb8af87f4.jpg)


准备一颗IAP15F2K61S2或者IAP15L2K61S2的芯片，并通过下载板连接到电脑的串口，然后如上图，选择正确的芯片型号，然后进入到“Keil仿真设置”页面，点击“将IAP15F2K61S2设置为2.0版仿真芯片”按钮或者“将IAP15L2K61S2设置为2.0版仿真芯片”按钮，当程序下载完成后仿真器便制作完成了。

# （5）开始仿真

将制作完成的仿真芯片通过串口与电脑相连接。

将前面我们所创建的项目编译至没有错误后，按“Ctrl+F5”开始调试。

若硬件连接无误的话，将会进入到类似于下面的调试界面，并在命令输出窗口显示当前的仿真驱动版本号和当前仿真监控代码固件的版本号

断点设置的个数目前最大允许20个（理论上可设置任意个，但是断点设置得过多会影响调试的速度）。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/86b430b3368b90f715e03793ce3496d2426d7d77bc4e8f600cc6f97ea26b2649.jpg)


Driverversion ：V1.01 VFimare version:V2.0Load"C:\\Documentsand Settings\\Kaily\\桌面\\Demo\\Demo"

# 15.5 如何让传统的8051单片机学习板可仿真

传统的8051单片机学习板不具有仿真功能，让传统的8051单片机学习板可仿真需要借助转换板，转换板的实物图如下图所示，转换后的引脚排布与传统8051的脚位基本一致, 从而可以实现标准8051学习板的仿真功能。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a7c42ba8e8f0879145f9f6672c4aaeeecb4f28a742a63d6d09e1130d4c0dd765.jpg)



完整转换板



完整转正面



完整转反面


该转换板可进行IAP15F2K61S2/STC15F2K60S2转STC89C52RC/STC89C58RD $^ { + }$ 系列仿真用、IAP15F2K61S2/STC15F2K60S2转STC90C52RC/STC90C58RD $^ { + }$ 系列仿真用、IAP15F2K61S2/STC15F2K60S2转STC10F08XE/STC11F60XE系列仿真用、及IAP15F2K61S2/STC15F2K60S2转STC12C5A60S2系列仿真用。

目前，我公司只是小批量生产此转换板，供客户快速验证用，如需要我们提供样板，售价为：空板：1元人民币；

转换板 $^ +$ 主控芯片（IAP15F2K61S2/STC15F2K60S2）：6元人民币。

若用户自己批量生产此板，成本价可控制在0.40元以下。新产品开发请直接使用STC15F2K60S2/IAP15F2K61S2系列来开发

下图为转换板功能示意图（IAP15F2K61S2转STC89C52/90C52/12C5A60S2仿真用转换板）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/3db38f1989ab382eeeacb4151ce6d996a26cda028a013342b02db89764b856b6.jpg)


注意：

由于内置高精准R/C时钟(5MHz ~ 40MHz可设)，因此不需要外部晶振；

XTAL1和XTAL2是空的

WR和RD 是( WR/P4.2和RD/P4.4)，而不是传统的(WR/P3.6和RD/P3.7)

下面为STC89C52RC和STC12C5A60S2的脚位分布图

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d36c2029013bf505fa2be0a48595a8c0198dc63d391da44ca9b8e6abf7bdeba8.jpg)


# 15.6 USB型联机/脱机下载工具U7/U7-S1

U7/U7-S1是一款集在线联机下载和脱机下载于一体的编程工具系列。应用范围可支持STC目前的全部系列的MCU, Flash程序空间和EEPROM数据空间不受限制。支持包括如下和即将推出的STC全系列芯片：

STC15F2K60S2/STC15L2K60S2系列

STC15F408AD/STC15L408AD系列

STC15W201S系列

STC15F104W/STC15L104W系列

STC15F104E/STC15L104E 

STC15F204EA/STC15L204EA 

STC10Fxx/STC10Lxx系列

STC11Fxx/STC11Lxx系列

STC12C5Axx/STC12LE5Axx系列

STC12C52xx/STC12LE52xx系列

STC12C56xx/STC12LE56xx系列

STC12C54xx/STC12LE54xx系列

STC12Cx052/ STC12Cx052AD/STC12LEx052/STC12LEx052AD系列STC90xx/STC89xx系列

脱机下载工具可以在脱离电脑的情况下进行下载工作，可用于批量生产和远程升级。脱机下载板可支持自动增量、下载次数限制以及用户自定义加密下载等多种功能。

目前的U7/U7-S1系列工具均分为5V工具和3.3V工具两种，正面图如下图所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e376a529da2acb804c728216e92ebd129943d53c95da41f40cf0dbc362e0715a.jpg)



U7（5V）工具



U7（3.3V）工具



U7-S1（5V）工具



U7-S1（3.3V）工具


其反面图如下图所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/6a2ffeeef85d414a9a36efd2e3c2fa82e61d1bf62550992190951519608e1d6e.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/569aa049ed617451939376f871957d952370053db0201d13be9c701ec22b4cb9.jpg)


U7-S1反面图

另外还有如下的一些线材与工具相搭配使用，如：

（1）两头公的USB连接线，如下图所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/8afca48ac640655d4c98da8a7fb65fd427eac7675ec1d06a3220045a641b3bb5.jpg)


注意：此USB线为我公司特别定制的USB加强线，可确保直接用USB供电时能够下载成功。而市面上一些比较劣质的两头公的USB线，内阻太大而导致压降很大（如USB空载时的电压为5.0V左右，当使用劣质的USB线连接U7/U7-S1，到我们的下载板上的电压可能降到4.2V或者更低，从而导致芯片处于复位状态而无法成功下载）。

（2）U7-S1与用户系统连接的下载连接线(U7-S1与用户板上的目标单片机的连接线)，如下图所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/12ca2e21ad8e6ca60ddf50311b259b3065c1cc0756979dd26f388f93b3a00a18.jpg)


# 15.6.1 USB型联机/脱机下载工具U7/U7-S1的功能介绍

# 15.6.1.1 U7的功能介绍(U7的价格为人民币100元)

下面以5V工具为例，详细介绍U7工具的各个接口及功能

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a153ebb21a8a0156ef94167037222de0b5cfcfe86ccb44b0519b1d4d4f564715.jpg)


编程接口：根据不同的供电方式，使用不同的下载连接线连接U7下载板和用户系统。

U7更新系统程序按钮：用于更新U7工具，当有新版本的U7固件时，需要按下此按钮对U7的主控芯片进行更新（注意：必须先将更新/下载选择接口上的跳线跳为更新U7编程器模式）

脱机下载用户程序按钮：开始脱机下载按钮。首先PC将脱机代码下载到U7板上，然后使用下载连接线将用户系统连接到U7，再按下此按钮即可开始脱机下载（每次上电时也会立即开始下载用户代码）。

外接9V电源插座：当进行脱机下载时，可使用外部电源供电。此电源接口可支持6～9V的外部直流供电。

USB接头：用于连接电脑。使用标配的两头公的USB线连接电脑，可对目标芯片进行在线联机下载，也可使用USB供电进行脱机下载。

更新/下载选择接口：当需要对U7的底层固件进行升级时，需要将此跳线跳为更新U7编程器模式，否则，必须将跳线跳为下载用户代码模式。（跳线连接方式请参考上图）

分选机接口：是用于控制分选机进行自动生产的控制接口

对于USB型联机/脱机下载工具，STC公司特别制作了配套的外壳，并在该外壳上对U7上相应位置的器件或管脚进行了标注，将U7安装于该外壳内（如下图所示），可对U7上的线路图一目了然。


U7安装外壳的正面图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7f5eba2b9abb62ab5b9ce592c2d16a950c267fb315a604b7b8a2daa538740628.jpg)



U7安装外壳的反面图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/9c736cea147d3785430eadb0cf638e7253aeb3f37f91b9d3d67035cb5fcc62aa.jpg)


# 15.6.1.2 U7-S1的功能介绍(U7-S1的价格为人民币50元)

下面以5V工具为例，详细介绍U7-S1工具的各个接口及功能

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/13fb8f3a984806204e49678af02d6519178e81151eff8f08edec189b9746ee21.jpg)


编程接口：根据不同的供电方式，使用不同的下载连接线连接U7-S1下载板和用户系统。

U7-S1更新系统程序按钮：用于更新U7-S1工具，当有新版本的U7-S1固件时，需要按下此按钮对U7-S1的主控芯片进行更新（注意：必须先将更新/下载选择接口上的跳线跳为更新模式）

脱机下载用户程序按钮：开始脱机下载按钮。首先PC将脱机代码下载到U7-S1板上，然后使用下载连接线将用户系统连接到U7-S1，再按下此按钮即可开始脱机下载。

5V/3.3V选择接口：用于选择U7-S1下载板系统的工作电压，需要与主控芯片的工作电压一致,现版本，用户不能选，因为现主控芯片不是宽压的。（3.3V和5V的跳线选择参考上图）。

外接9V电源插座：当进行脱机下载时，可使用外部电源供电。此电源接口可支持 $6 { \sim } 9 \mathrm { V }$ 的外部直流供电。

USB接头：用于连接电脑。使用标配的两头公的USB线连接电脑，可对目标芯片进行在线联机下载，也可使用USB供电进行脱机下载。

给外部分选机供电接口：U7-S1额外提供的一个给外部供电的接口，可供应3.3V和5V

更新/下载选择接口：当需要对U7-S1的底层固件进行升级时，需要将此跳线跳为更新U7-S1模式，否则，必须将跳线跳为下载用户代码模式。（跳线连接方式请参考上图）

分选机接口：是用于控制分选机进行自动生产的控制接口

注意：当用户系统的功耗大于50mA时，由U7-S1给用户系统供电易导致三极管T9(如上图所示)损坏，因此，当用户系统的功耗大于50mA时，建议用户系统单独供电或由用户系统给U7-S1供电(即从用户系统供电)。三极管T9型号为S8550,若损坏用户可以自行更换。

由上述两小节可知，USB型联机/脱机下载工具U7与U7-S1相比，只是多了一个“编程锁紧座”，其他各模块及功能均相同，为避免赘述，下文“USB型联机/脱机下载工具的使用介绍”中均仅以USB型联机/脱机下载工具U7为例，用户可对照U7的使用介绍，使用U7-S1的相应模块。

# 15.6.2 如何安装USB型联机/脱机下载工具U7/U7-S1的驱动程序

U7/U7-S1 下载板上使用了一颗CH340 的USB转串口通用芯片。这样可以省去部分没有串口的电脑必须额外买一条USB转串口线才可下载的麻烦。但CH340 和其它USB转串口线一样，在使用之前必须先安装驱动程序。驱动程序可以进行手动安装，也可以自动安装。

# 1、手动安装USB型联机/脱机下载工具U7/U7-S1的驱动程序

在STC的官方网站上手动下载驱动程序，驱动的下载链接为：U7编程器USB转串口驱动（http://www.stcmcu.com/STCISP/CH341SER.exe）。网站上的驱动地址如下图所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/14c002cba5bf2ee6b45ec925b02ce95d78119e29cadb4a38ed520bd370018bff.jpg)


驱动程序下载到本机后，直接双击可执行程序并运行，出现下图所示的界面，点击“安装”按钮开始自动安装驱动

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ba9065e813ef54851cbe02db1b8bf952eb18dc87d6de7765c60f780206ddfc0a.jpg)


直至弹出下面的画面表示驱动已成功安装

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/1a565c3edb4e17a8221dbcb8f1044421eb1af9146b555a18ac812163fe51eccd.jpg)


然后使用 STC 提供的两头公 USB 连接线将 U7/U7-S1 下载板连接到电脑，打开电脑的设备管理器，在端口设备类下面，如果有类似“USB-SERIAL CH340 (COMx)”的设备，就表示U7/U7-S1 可以正常使用了。如下图所示（不同的电脑，串口号可能会不同）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/130315409d00b7777d3022af1e99ed76c29dbcb6a98d5172c9c37192092b6159.jpg)


注意：在后面使用STC-ISP下载软件时，选择的串口号必须选择与此相对应的串口号，如下图所示

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5a3379b13c9e6fb514281ba2d544eb22b1c0b6cac47f7775b681243d7288bfc3.jpg)


# 2、自动安装USB型联机/脱机下载工具U7/U7-S1的驱动程序

若用户所使用的 STC-ISP 下载软件为 V6.58C 及以上版本，则打开该 STC-ISP 下载软件时软件会自动检测本机的 U7/U7-S1 驱动程序的安装情况，若没有安装驱动程序，软件会自动将相应的驱动程序复制到系统目录，此时拔出上一次插入的 U7/U7-S1 工具并再次将其插上时，会出现如下提示框：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ddbca520fce2a60d713f08765e2fca4e2deda58f130474d1ebb6d1e837c43299.jpg)


选“自动安装软件(推荐)(I)”选项，并点击【下一步】按钮，会出现如下画面：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/9b232d9ec281a8831e18f4494b0a0005cdde354d898f9aed729094d018209c76.jpg)


在接下来出现的如下面的对话框中，选中【仍然继续】：

# 硬件安装

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d33e4f6b1367c316bf00f7b315ffd8b54ea6d0a19e8c05cb7a3604afe4149952.jpg)


正在为此硬件安装的软件：

USB-SERIAL CH340 

没有通过Windows徽标测试，无法验证它同WindowsXF的相容性。告诉我为什么这个测试很董要。）

继续安装此软件会立即或在以后使系统变得不稳定。icrosoft建议您现在停止此安装，并同硬件供应商联系，以获得通过Tindors敬标测试的软件。

仍然继续（C）

停止安装（S）

系统便会开始自动安装驱动，如下图所示：

# 找到新的硬件向导

向导正在安装软件，请稍候...

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/640f1c8ef344c14d8815335e90998d738bb63d5f6e254fb88ad0dcbc20965e9c.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b7f61cccca3b037dfbbdf61d60f3f8b0caf914c9bfade3814bb87e729621832a.jpg)


USB-SERIAL CH340 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/83431e9880961839240da18bccc4e06a0db94738194ffff54d5ce9cb9c0e112c.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d3c33de1cc7009e6aaddb77fe258adc6e0e85e92cae16e5d2b14c1d65b73c59b.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d1be50ef1b0dd221344a98f112ade42f261ca09118f973217dde976901692390.jpg)


正在设置系统还原点并备份旧文件，以防将来需要还原系统。

直至出现如下画面，点击【完成】按钮：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/88596af4da53747e1e0d66d08c5be4096d45536f1f1dca70fa92b39691ada612.jpg)


至此，U7/U7-S1的驱动程序便自动安装完成了。如手动安装驱动程序一样，也会如下图所示（不同的电脑，串口号可能会不同）：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/09fb1b1e82356cff3704c37c138c631e3be8ad1bcaa340c288da27b150d09b3f.jpg)


注意：在后面使用STC-ISP下载软件时，选择的串口号必须选择与此相对应的串口号，如下图所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/95a241e57b3f48c625d371684e5cb4372c1fb2af64378afd80eb59ff365f2a80.jpg)


# 15.6.3 U7/U7-S1的在线联机下载使用说明

# 15.6.3.1 目标芯片直接安装于U7上的在线联机下载使用说明

首先使用STC提供的两头公USB连接线将U7连接电脑, 再将目标单片机按如下图所示的方向安装在U7上：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/28e3f6a0fa0bc42366a1692d2a4b240f0a4e524acc7a1fc4f14ac3d7c6c019f6.jpg)


然后在用STC-ISP下载软件下载程序时，在STC-ISP下载软件中选择正确的串口号(USB转串口扩展的)，点击【下载/编程】按钮即可开始在线下载。

建议用户用最新版本的STC-ISP下载软件“STC-ISP (V6.58C).exe”（请随 时留意STC官方网站http://www.STCMCU.com中STC-ISP下载软件的更新，强烈建议用户在官方网站http://www.STCMCU.com中下载最新版本的软件使用）。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e15ee9386f7c1a15c90196eca26154754ffad582cbbd5e67d45b103511df72ea.jpg)


当信息框中有输出下载板的版本号信息以及外挂Flash的相应信息时，表示已正确检测到U7下载工具。

下载的过程中，U7下载工具上的4个LED会以跑马灯的模式显示。下载完成后，若下载成功，则4个LED会同时亮、同时灭；若下载失败，则4个LED全部不亮。

# 15.6.3.2 通过下载线连接目标芯片的U7/U7-S1的在线联机下载使用说明

首先使用STC提供的两头公USB连接线连接电脑, 再将U7/U7-S1通过下载线与用户系统的目标单片机相连接, 连接方式如下图所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/3b3ec8b8091f75e01cceaaf365075f0881026400e53625e46a21d3d879eb5c15.jpg)


虽然图中仅列举了U7与通过下载线与用户系统的目标单片机相连接的示意图，但U7-S1的连接方式与该图相同，因此不再赘述。

然后在用STC-ISP下载软件下载程序时，在STC-ISP下载软件中选择正确的串口号(USB转串口扩展的)，点击【下载/编程】按钮即可开始在线下载。

建议用户用最新版本的STC-ISP下载软件“STC-ISP (V6.58C).exe”（请随 时留意STC官方网站http://www.STCMCU.com中STC-ISP下载软件的更新，强烈建议用户在官方网站http://www.STCMCU.com中下载最新版本的软件使用）。

然后在用STC-ISP下载软件下载程序时，在STC-ISP下载软件中选择正确的串口号(USB转串口扩展的)，点击【下载/编程】按钮即可开始在线下载。

建议用户用最新版本的STC-ISP下载软件“STC-ISP (V6.58C).exe”（请随 时留意STC官方网站http://www.STCMCU.com中STC-ISP下载软件的更新，强烈建议用户在官方网站http://www.STCMCU.com中下载最新版本的软件使用）。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/543366a3e181abdaf5a6679b8736fb2aeda758900da702f30dc36353715a9c01.jpg)


当信息框中有输出下载板的版本号信息以及外挂Flash的相应信息时，表示已正确检测到U7/U7-S1下载工具。

下载的过程中，U/U7-S17下载工具上的4个LED会以跑马灯的模式显示。下载完成后，若下载成功，则4个LED会同时亮、同时灭；若下载失败，则4个LED全部不亮。

# 15.6.4 U7/U7-S1的脱机下载使用说明

# 15.6.4.1 目标芯片直接安装于U7上时通过USB供电进行脱机下载的使用说明

使用USB给U7从而进行脱机下载的步骤如下：

（1）使用STC提供的两头公USB连接线将U7下载板连接到电脑，如下图：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a7db072118cc0b44adc4c62bb7b2afa9491c3e0c99b1dbbd75f068dcfa28a57d.jpg)



连接电脑


（2）在ISP下载程序“STC-ISP (V6.65).exe”中按如下图所示的步骤进行设置：

建议用户用最新版本的STC-ISP下载软件“STC-ISP (V6.58C).exe”（请随 时留意STC官方网站http://www.STCMCU.com中STC-ISP下载软件的更新，强烈建议用户在官方网站http://www.STCMCU.com中下载最新版本的软件使用）。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d7b1dd15c3b9ef860e952e500631cf83467731234cdf6aba063f51f41d542812.jpg)


按照上图的步骤，操作完成后，若下载成功则表示用户代码和相关的设置选项都已下载到U7下载工具中。

（3）再将目标单片机如下图所示的方向放在U7下载工具, 如下图所示

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c7318faa64cf4e72675b82d37791711d0e3d60c448ebb7c82bad1079a3bc62a0.jpg)


（4）然后按下如下图所示的按钮后松开，即可开始脱机下载：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/91df9f9f722e63284a633e4f7ca858d4115e0554d5065cec37d481d3949bd13f.jpg)


下载的过程中，U7下载工具上的4个LED会以跑马灯的模式显示。下载完成后，若下载成功，则4个LED会同时亮、同时灭；若下载失败，则4个LED全部不亮。

# 15.6.4.2 目标芯片通过下载线连接于U7/U7-S1时用USB供电进行脱机下载的使用说明

使用USB给U7/U7-S1从而进行脱机下载的步骤如下：

（1）使用STC提供的两头公USB连接线将U7/U7-S1下载板连接到电脑，如下图：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/73e1a93821d6054e79c7aea1322de64ab5e8bc50bec210512acba0f0187e9092.jpg)


（2）在ISP下载程序“STC-ISP (V6.65).exe”中按如下图所示的步骤进行设置：

建议用户用最新版本的STC-ISP下载软件“STC-ISP (V6.58C).exe”（请随 时留意STC官方网站http://www.STCMCU.com中STC-ISP下载软件的更新，强烈建议用户在官方网站http://www.STCMCU.com中下载最新版本的软件使用）。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ef7fd91d54ad7c19960d8e216df6d7b04816e7a312ad40f25f926815a9888ae6.jpg)


按照上图的步骤，操作完成后，若下载成功则表示用户代码和相关的设置选项都已下载到U7下载工具中。

（3）然后使用连接线连接电脑、将U7/U7-S1下载工具以及用户系统（目标单片机）如下图所示的方式连接起来，并按下图所示的按钮后松开，即可开始脱机下载

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/1f668dc1c817d8ed212c87c7889932acaac5720dab57e182c5a3454be8d0cf1a.jpg)


下载的过程中，U7/U7-S1下载工具上的4个LED会以跑马灯的模式显示。下载完成后，若下载成功，则4个LED会同时亮、同时灭；若下载失败，则4个LED全部不亮。

本节附图中虽然仅列举了U7的连接示意图，但U7-S1的连接方式与U7相同，因此不再赘述。

# 15.6.4.3 目标芯片直接安装于U7上时通过外部9V电源供电进行脱机下载的使用说明

（1）首先使用STC提供的两头公USB连接线将U7下载板连接到电脑，如下图：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/4abc36347a16dc08ea26e9633270a7c05a7584cea4e45a0372a0b3119e5d01e4.jpg)



连接电脑


（2）在ISP下载程序“STC-ISP (V6.65).exe”中按如下图所示的步骤进行设置：

建议用户用最新版本的STC-ISP下载软件“STC-ISP (V6.58C).exe”（请随 时留意STC官方网站http://www.STCMCU.com中STC-ISP下载软件的更新，强烈建议用户在官方网站http://www.STCMCU.com中下载最新版本的软件使用）。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/4a67302296727e1d7d0fd2dc3416237534595346901fe2250c39ca041bbafe05.jpg)


按照上图的步骤，操作完成后，若下载成功则表示用户代码和相关的设置选项都已下载到U7下载工具中。

（3）再将目标单片机如下图所示的方向放在U7脱机下载工具, 如下图所示

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/29311ef7720c95930b04635c3867ee1b2fd3b202e267407ad262ab614e3772ad.jpg)


（4）然后按下如下图所示的按钮后松开，即可开始脱机下载

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/746e801bc2a02e6f841d804d0929571f31a3137b73323756d2a311aeef13e75f.jpg)


下载的过程中，U7下载工具上的4个LED会以跑马灯的模式显示。下载完成后，若下载成功，则4个LED会同时亮、同时灭；若下载失败，则4个LED全部不亮。

# 15.6.4.4 目标芯片通过下载线连接于U7/U7-S1时用外部9V电源供电进行脱机下载的说明

（1）首先使用STC提供的两头公USB连接线将U7/U7-S1下载板连接到电脑，如下图：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b088456d7ec1a4064cebffdfb2da91d3e894c5952c4c57b41f66ce61a7f4f216.jpg)



连接电脑


（2）在ISP下载程序“STC-ISP (V6.65).exe”中按如下图所示的步骤进行设置：

建议用户用最新版本的STC-ISP下载软件“STC-ISP (V6.58C).exe”（请随 时留意STC官方网站http://www.STCMCU.com中STC-ISP下载软件的更新，强烈建议用户在官方网站http://www.STCMCU.com中下载最新版本的软件使用）。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/9df1da3accfe9a0a1d915d5f3ca1731473a736077eb0baa63070207176fcb749.jpg)


按照上图的步骤，操作完成后，若下载成功则表示用户代码和相关的设置选项都已下载到U7下载工具中

（3）然后按下图所示的方式连接9V电源，并按下图中所示按钮后松开，即可开始脱机下载：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/50aa467454b2d540989816a83f6068132d4a36a4c1ffdce1a30fdb766b808663.jpg)


下载的过程中，U7/U7-S1下载工具上的4个LED会以跑马灯的模式显示。下载完成后，若下载成功，则4个LED会同时亮、同时灭；若下载失败，则4个LED全部不亮。

本节附图中虽然仅列举了U7的连接示意图，但U7-S1的连接方式与U7相同，因此不再赘述。

# 15.6.4.5 通过用户板给简易脱机下载器U7/U7-S1供电进行脱机下载的使用说明

（1）首先使用STC提供的两头公USB连接线将U7/U7-S1下载板连接到电脑，如下图：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/3bc81c0f3bec79726fa360a00f0f991d8ec8bec17b63252d1295bb120ca9d762.jpg)


（2）在ISP下载程序“STC-ISP (V6.65).exe”中按如下图所示的步骤进行设置：

建议用户用最新版本的STC-ISP下载软件“STC-ISP (V6.58C).exe”（请随 时留意STC官方网站http://www.STCMCU.com中STC-ISP下载软件的更新，强烈建议用户在官方网站http://www.STCMCU.com中下载最新版本的软件使用）。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d4e6327814f7725e80cf6d1cc6e0f40b0603a02281a1ee32417f92fbf03132f9.jpg)


按照上图的步骤，操作完成后，若下载成功则表示用户代码和相关的设置选项都已下载到U7下载工具中

（3）然后按下图所示的方式连接U7/U7-S1与用户系统，并按下图中所示按钮后松开，即可开始脱机下载：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/77c26f8aa76d6bb9bc1f7d94f090f070929fd01207cd7cb3520422b7d506e495.jpg)


下载的过程中，U7/U7-S1下载工具上的4个LED会以跑马灯的模式显示。下载完成后，若下载成功，则4个LED会同时亮、同时灭；若下载失败，则4个LED全部不亮。

本节附图中虽然仅列举了U7的连接示意图，但U7-S1的连接方式与U7相同，因此不再赘述。

# 15.6.4.6 U7/U7-S1与用户系统各自独立供电进行脱机下载的使用说明

（1）首先使用STC提供的两头公USB连接线将U7/U7-S1下载板连接到电脑，如下图：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/85d96811a55f939ad6feb9d848461ad38a0c39de9459b8e98d636c69cea0e588.jpg)


（2）在ISP下载程序“STC-ISP (V6.65).exe”中按如下图所示的步骤进行设置：

建议用户用最新版本的STC-ISP下载软件“STC-ISP (V6.58C).exe”（请随 时留意STC官方网站http://www.STCMCU.com中STC-ISP下载软件的更新，强烈建议用户在官方网站http://www.STCMCU.com中下载最新版本的软件使用）。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7d1eb23c772a871e19b20f368fae030dd80dd0de167f6e4b24c4dbbf9876e380.jpg)


按照上图的步骤，操作完成后，若下载成功则表示用户代码和相关的设置选项都已下载到U7/U7-S1下载工具中

（3）然后按下图所示的方式连接U7/U7-S1与用户系统，并将图中所示按钮先按下后松开，准备开始脱机下载, 最后给用户系统上电/开电源, 下载用户程序正式开始：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b5881b5833ed41b7b82bfd44884ca1e6b4aea4ade1f5a829107e60b2cd4f20c6.jpg)


下载的过程中，U7/U7-S1下载工具上的4个LED会以跑马灯的模式显示。下载完成后，若下载成功，则4个LED会同时亮、同时灭；若下载失败，则4个LED全部不亮。

本节附图中虽然仅列举了U7的连接示意图，但U7-S1的连接方式与U7相同，因此不再赘述。

# 15.6.5 制作/更新USB型联机/脱机下载工具U7/U7-S1

# 15.6.5.1 制作U7/U7-S1下载母片(U7控制母片)

在制作U7/U7-S1下载母片之前需要将U7/U7-S1下载板的“更新/下载选择接口”设置为更新模式，如下图所示：(下图以U7为例，因U7-S1的模块与U7相同，因此在U7-S1下载板上找到相对应的“更新/下载选择接口”，同样将其设置为更新模式，下文相同)

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b33caba07f109de5b3351777d7a54b98b8ade5ddccf2bebcb543af83697a571c.jpg)


然后在ISP下载程序“STC-ISP (V6.65).exe”中的“脱机下载/U7”页面中点击“将IAP15F2K61S2设置为脱机下载主控芯片（U7控制器）”按钮（5V下载板）或者点击“将IAP15L2K61S2设置为脱机下载主控芯片（U7控制器）”按钮（3.3V下载板），如下图：

（注意：一定要选择U7/U7-S1所对应的串口）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/9eda2df800b29b6a9e9423190a7cf57cfea2a976b139a387b5b1b3e2dda7b5aa.jpg)


然后按下如下图所示的按键，并松开后才能开始制作U7/U7-S1下载母片：

按下此按钮开始

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/cc9160987049c4ddd550a102a9493759d9634419e1f27c75c330e8efdb9a7280.jpg)


在出现如下画面表示U7/U7-S1控制芯片制作完成：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e276768ba6dc00bbcf1f859c7a03a7f924ad1fb6d68ced9580e17242e432a391.jpg)


制作完成后，一定不要忘记将U7/U7-S1的“更新/下载选择接口”切换回下载用户代码模式，并将U7/U7-S1下载工具重新上电，如下图所示：（否则将不能正常进行下载）


切换到用户代码下载模式


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/1de5e39cd8d55b88f781b68cb7b3ec5104dadef7e4c7b2be1f305a6cf37de892.jpg)


# 15.6.5.2 手动升级U7/U7-S1

在手动升级U7/U7-S1之前需要将“更新/下载选择接口”选中为更新模式，如下图所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5c5cafc626c6e1cc7cc2466792fb89013d9f6dee817cc856d7c65f9e9c3d73fe.jpg)


然后在ISP下载程序中的“脱机下载/U7”页面中点击“将IAP15F2K61S2设置为脱机下载主控芯片（U7控制器）”按钮（5V下载板）或者点击“将IAP15L2K61S2设置为脱机下载主控芯片（U7控制器）”按钮（3.3V下载板），如下图：

（注意：一定要选择U7/U7-S1所对应的串口）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/49dd332c909c39e511f2d237b0739ef6fd3b008de468b485371000e3b21c0032.jpg)


此时由于主控芯片已经被设置为U7/U7-S1的下载母片，则点击上面对应的按钮后，芯片会自动进行更新，中间不需要按其它的按键（特殊情况：若软件一直没有反应，则需要用户手动按一下“更新/update”按钮，芯片才能进行更新），直至出现如下画面表示U7/U7-S1控制芯片升级完成：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/825ed1b8bd197bd1d44339d4a6880b185244fabe3e35fb9a48b06b7863589f70.jpg)


升级完成后，一定不要忘记将U7/U7-S1的“更新/下载选择接口”切换回下载用户代码模式，并将U7/U7-S1下载工具重新上电，如下图所示：（否则将不能正常进行下载）

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/06a0d9e6972b26583fcc6c2221303f18db2bb892550bd78bb3a001ddc82961f3.jpg)


# 15.6.5.3 自动升级U7/U7-S1

将U7/U7-S1下载板连接到电脑后，打开STC的ISP下载软件，并选择U7/U7-S1所对应的串口。

然后击下载界面中的“下载/编程”、“检测MCU选项”或者“脱机下载/U7”页面里的“将用户程序下载到U7编程器以供脱机下载”按钮中的其中一个时，下载软件便会自动检测U7/U7-S1的版本，若U7/U7-S1的固件版本比当前下载软件里面所记录的U7/U7-S1固件版本低，软件则会弹出如下升级提示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7a99b6f355676f78cfc558b51791228a936cf91e7781b2e2a28a43ea28e96d4b.jpg)


点击“是”，软件便会自动升级U7/U7-S1，如下所示：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5e71020c2e4dabe1f35d45d46529da6250c0084aa99e852eb4e1a5a54d860850.jpg)


自动升级过程中请不要中途拔出USB线。

升级完成后可看到如下的版本变化：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/4af2fb0afaf4a2a10b7025c8fb0e22ccbc8431fdec01b8bb59d19729c628949f.jpg)


至此，下载软件已自动将U7/U7-S1升级到软件所记录的最新版本（此升级的整个过程中，不需要切换下载板的工作模式，也不需要按更新按钮）

# 15.6.6 USB型联机/脱机下载板U7-S1的参考电路

USB型联机/脱机下载板 U7 为用户提供了如下的常用控制接口（Ver6.53版）：

<table><tr><td>脚位功能</td><td>端口</td><td>功能描述</td></tr><tr><td>电源控制脚</td><td>P2.6</td><td>低位有效</td></tr><tr><td rowspan="2">下载通讯脚</td><td>P1.0</td><td>串口RXD, 连接目标芯片的TXD (P3.1)</td></tr><tr><td>P1.1</td><td>串口TXD, 连接目标芯片的RXD (P3.0)</td></tr><tr><td>编程按键</td><td>P3.6</td><td>低有效</td></tr><tr><td rowspan="4">显示</td><td>P3.2</td><td>LED1</td></tr><tr><td>P3.3</td><td>LED2</td></tr><tr><td>P3.4</td><td>LED3</td></tr><tr><td>P5.5</td><td>LED4</td></tr><tr><td rowspan="4">外挂串行Flash控制脚</td><td>P2.4</td><td>Flash的CE脚</td></tr><tr><td>P2.2</td><td>Flash的SO脚</td></tr><tr><td>P2.3</td><td>Flash的SI脚</td></tr><tr><td>P2.1</td><td>Flash的SCLK脚</td></tr><tr><td rowspan="4">全自动烧录工具分选机信号</td><td>P3.6</td><td>起始信号</td></tr><tr><td>P1.5</td><td>完成信号</td></tr><tr><td>P5.4</td><td>OK信号(良品信号)</td></tr><tr><td>P3.7</td><td>ERROR信号(不良品信号)</td></tr><tr><td>蜂鸣器(BEEP)控制</td><td>P2.5</td><td>高有效(高电平发出声音)</td></tr></table>

电源控制部分参考电路图

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b86f4cae9210a1e2507fb8d1eeeab518cb5f3ff38802d95947e35beb58847a4b.jpg)


Flash控制部分参考电路图

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5ba96f3c78393884cd19c7e7f64f02e3e90b7aab81a7c0919376bee11b761d50.jpg)



按键部分参考电路图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/1306835e16ef8c1e769d166b80123a446b0f717a9ebab81a66b34055d4b3bef2.jpg)



蜂鸣器部分参考电路图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d54431cbed106ea12c8020132b7012103dd3a76aeb903300af86d15a52e91939.jpg)



LED显示部分参考电路图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e046a30cdbd345c4b529c2279d4c8dfcf9aa5ebe07f8197d3a70f42fbd94616b.jpg)



串口通讯脚连接部分参考电路图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/f1fde56c3a66b4e478ddfb906cdece976095354abbe734473c4a5e5602d637d0.jpg)



U7-S1 PCB板正面丝印图：


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/92744b49e70fbeb00ada392943d9c524be33cc48e49364a044086a1174a68487.jpg)



四角的安装孔直径：2．8mm



U7-S1 PCB板反面丝印图：


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/de08adcaef9a58feb0399f043184fdb97de10ece31035acb6f45ba09975f92e8.jpg)



U7-S1 PCB板走线图（正面）：


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a63bea0576f6ecf8a5b109b200b18ca89cb340b2caa758dfcf9a0f40dbdbe984.jpg)



U7-S1 PCB板走线图（反面）：


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/62697f4cc2fc40f790e7144b3219d18fa9dd913ceddf4aab71098906dae4adda.jpg)


在STC官方网站www.STCMCU.com的资源中有用户自己做简易型脱机下载器U7-S1完整原理图以及U7-S1的详细PCB线路图，需要的用户可以自行到网站上下载学习。该原理图及PCB线路图在网站上的位置如下图所示，链接地址分部为：http://www.stcmcu.com/STCISP/用户自己做简易型脱机下载器U7-S1原理图.PDF 及 http://www.stcmcu.com/STCISP/U7-S1-PCB-2x-2013-7-23.PDF 及 U7编程器USB转串口驱动

# STCMCU资料下载

·STC开发/烧录工具说明

免费样品申请

·STC15系列选型广告

·STC15系列选型价格

·STC单片机传统选型指南

·STC8051日单片机选型表

·低价支持请来电咨询·以下是最新单片机资

2012最新奉献，无法解密抗干扰最强的STC15新系列，采用STC第8代加密技术，有全球唯一ID号，无法解密，性能更好，价格更低

2kRAM2UART，10位ADC

STC15F2K60S2系列中文2013/7/22，C版大量供货中

·下载高版本PDF阅读器

·STC15F2K60S2英文资料·用IAP15F2K61S2仿真15

# 系

STC15系列Protel库

STC15F2K08S28K 

Flash 

STC15F2K16S2 16K 

# 选STC抗干扰最强/加密性最强的STC15系列，送仿真器

2013-7-17，STC史上抗干扰最强的STC15W204S定型

·STC15系列报价选型宣传，强烈推荐，性能最好，价格最低

万众期待的仿真说明发布项自程序自定义加密下载自制脱机工具如何支持全自动烧录机械手 $\approx$ 

加强对STC15系列推广支持，新增顾问QQ：13922805190

顾问争取每天有一小时回答STC15系列问题，做不到实时

IAP15F2K61S2/IAP15L2K61S2,LQFP44/DIP40,SOP/SKDIP28 

STC15F2K60S2/STC15L2K60S2,LQFP44/DIP40,SOP/SKDIP28 

STC15F2K16S2/STC15L2K16S2,LQFP44/DIP40,SOP/SKDIP28 

STC15F2K08S2/STC15L2K16S2.LQFP44/DIP40.SOP/SKDIP28 

STC15F408AD/STC15L408AD.LQFP32.SOP/SKDIP28 

IAP15F412AD/IAP15L412AD,LQFP32,SOP/SKDIP28 

STC15F104W，STC15F102WIAP15F105W.SOP8/DIP8 

让8051学习板可仿真，IAP15F2K61S2转8052仿真器，直插

IAP15F2K61S2转89C52/10F08/11F60/12C5A60S2PCB图

推荐STC15F2K60S2系列学习板原理图2.2012/3/30

利用STCIAP15/12/11/10的单片机实现自己的ISP

STC15系列Protel库含原理图库和PCB库

另外一种风格的STC15系列库函数与例程测试版V1.0

易型脱机下载器1-伍用说2桂8-3

用户自2做简易型脱机下载器U7-S1原理图（2013-7-23）

置易型脱机下载器U7-S1-PCB图，放大至2倍（2013-7-23）

# STC-ISP下载编程烧录软件

·STC开发/烧录工具说明

STC-ISP软件V6.53

STC-ISPV6.53请测试STC-ISP软件升级原因

*STC- ISP软件V6.52B

STC-ISP软件V6.52

STC-ISP软件V6.51研发顾问

QQ:13922805190 

STC超强工具包，已含89系

使用该软件的Kei1仿真设置在Kei1中添加器件和仿真

·STC15系单片机仿真说

·STC15系列报价选型宣传

STC15系列Protel库

·防少数电脑新软件不

# 第16章 利用主控芯片对从芯片(限STC15系列)进行ISP下载

STC15系列单片机的用户程序，除可以通过专用的下载工具进行在线联机或离线脱机ISP下载外，还可以利用其他的MCU（如单片机,ARM，DSP等）作主控芯片对其进行ISP下载。

利用其他MCU（如单片机,ARM，DSP等）对STC15系列单片机进行串口ISP下载的系统中，其他MCU为主控芯片，STC15系列单片机为受控的从芯片，主控芯片通过串口控制从芯片进行ISP下载。在利用其他MCU对STC15系列单片机进行ISP下载时，STC15系列单片机（即从芯片）先停电，然后，其他MCU（即主控芯片）发送下载命令给STC15系列单片机（即从芯片），最后，其他MCU控制STC15系列单片机再上电，这样才能正确地对STC15系列单片机进行ISP下载。由于在利用其他MCU（如单片机,ARM，DSP等）对STC15系列单片机进行ISP下载过程中，其他MCU作为主控芯片需要控制从芯片（即STC15系列单片机）电路的电源开关，因此，在进行电路连接时，用户可通过主控芯片的一个I/O口控制从芯片电路的电源开关。STC15系列单片机电路的电源控制部分参考电路图如下：


STC15系列单片机电路的电源控制部分参考电路图


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/0cf5c633c95e18569e6faaedbfaa7be9c9726e624eaf778220662c751f95b33e.jpg)


用户可将主控芯片的一个I/O口连接到上图中的SVCC_E管脚，这样通过主控芯片的该I/O口即可控制STC15系列单片机电路的电源开关，那么，在利用其他MCU对STC15系列单片机进行ISP下载时，其他MCU（主控芯片）就可自由控制STC15系列单片机（从芯片）停电或上电了。

利用其他MCU（如单片机,ARM，DSP等）对STC15系列单片机进行串口ISP下载示例程序(C语言程序）如下：

/* -*/ 

/* --- STC MCU Limited */ 

/* --- 使用主控芯片对从芯片(限STC15系列)进行ISP下载举例 - *

/* --- Mobile: (86)13922805190 - -*/ 

/* --- Fax: 86-755-82905966 -*/ 

/* --- Tel: 86-755-82948412 -*/ 

/* --- Web: www.STCMCU.com --*/ 

/* 如果要在程序中使用此代码,请在程序中注明使用了宏晶科技的资料及程序 */

/* 如果要在文章中应用此代码,请在文章中注明使用了宏晶科技的资料及程序 */

/*- -*/ 

//本示例在Keil开发环境下请选择Intel的8058芯片型号进行编译

//假定测试芯片的工作频率为11.0592MHz

//注意:使用本代码对STC15系列单片机进行下载时, 必须先对STC15系列单片机停电，并要在执行了

// Download代码之后,才给目标芯片上电, 否则目标芯片将无法正确下载

#include "reg51.h" 

typedef bit BOOL; 

typedef unsigned char BYTE; 

typedef unsigned short WORD; 

typedef unsigned long DWORD; 

# //宏、常量定义

#define FALSE 0 

#define TRUE 1 

#define LOBYTE(w) ((BYTE)(WORD)(w)) 

#define HIBYTE(w) ((BYTE)((WORD)(w) >> 8)) 

#define MINBAUD 2400L 

#define MAXBAUD 115200L 

#define FOSC 11059200L //主控芯片工作频率

#define BR(n) (65536 - FOSC/4/(n)) //主控芯片串口波特率计算公式

#define T1MS (65536 - FOSC/1000) //主控芯片1ms定时初值

//#define FUSER 11059200L //STC15系列目标芯片工作频率

//#define FUSER 12000000L //STC15系列目标芯片工作频率

//#define FUSER 18432000L //STC15系列目标芯片工作频率

//#define FUSER 22118400L //STC15系列目标芯片工作频率

#define FUSER 24000000L //STC15系列目标芯片工作频率

#define RL(n) (65536 - FUSER/4/(n)) //STC15系列目标芯片串口波特率计算公式

# //SFR定义

sfr AUXR = 0x8e; 

# //变量定义

BOOL f1ms; //1ms标志位

BOOL UartBusy; //串口发送忙标志位

BOOL UartReceived; //串口数据接收完成标志位

BYTE UartRecvStep; //串口数据接收控制

BYTE TimeOut; //串口通讯超时计数器

BYTE xdata TxBuffer[256]; //串口数据发送缓冲区

BYTE xdata RxBuffer[256]; //串口数据接收缓冲区

char code DEMO[256]; 

//演示代码数据

//函数声明

void Initial(void); 

void DelayXms(WORD x); 

BYTE UartSend(BYTE dat); 

void CommInit(void); 

void CommSend(BYTE size); 

BOOL Download(BYTE *pdat, long size); 

//主函数入口

void main(void) 

{ 

while (1) 

{ 

Initial(); 

if (Download(DEMO, 0x0100)) 

{ 

//下载成功

$\mathrm { P 3 } = 0 \mathrm { x f f } ;$ 

DelayXms(500); 

$\mathrm { P } 3 = 0 \mathrm { x } 0 0$ 

DelayXms(500); 

$\mathrm { P } 3 = 0 \mathrm { x f f } ;$ 

DelayXms(500); 

$\mathrm { P } 3 = 0 \mathrm { x } 0 0$ 

DelayXms(500); 

$\mathrm { P } 3 = \mathrm { 0 x f f }$ ; 

DelayXms(500); 

$\mathrm { P } 3 = 0 \mathrm { x } 0 0$ 

DelayXms(500); 

$\mathrm { P } 3 = 0 \mathrm { x f f }$ ; 

} 

else 

{ 

//下载失败

$\mathrm { P } 3 = 0 \mathrm { x f f }$ ; 

DelayXms(500); 

$\mathrm { P } 3 = 0 \mathrm { x } \mathrm { f } 3$ 

DelayXms(500); 

$\mathrm { P } 3 = 0 \mathrm { x f f }$ ; 

DelayXms(500); 

```txt
P3 = 0xf3;  
DelayXms(500);  
P3 = 0xff;  
DelayXms(500);  
P3 = 0xf3;  
DelayXms(500);  
P3 = 0xff;  
} 
```

//1ms定时器中断服务程序

```lisp
void tm0(void) interrupt 1 using 1  
{  
    static BYTE Counter100;  
    f1ms = TRUE;  
    if (Counter100-- == 0)  
{  
        Counter100 = 100;  
        if (TimeOut) TimeOut--;  
    }  
} 
```

//串口中断服务程序

void uart(void) interrupt 4 using 1   
{ static WORDRecvSum; static BYTERecvIndex; static BYTERecvCount; BYTE dat; if (TI) { TI $= 0$ UartBusy $=$ FALSE; } if (RI) { RI $= 0$ ; dat $=$ SBUF; switch(UartRecvStep) { 

```txt
case 1: if (dat != 0xb9) goto L_CheckFirst; UartRecvStep++; break;   
case 2: if (dat != 0x68) goto L_CheckFirst; UartRecvStep++; break;   
case 3: if (dat != 0x00) goto L_CheckFirst; UartRecvStep++; break;   
case 4: RecvSum = 0x68 + dat; RecvCount = dat - 6; RecvIndex = 0; UartRecvStep++; break;   
case 5: RecvSum += dat; RxBuffer[RecvIndex++] = dat; if (RecvIndex == RecvCount) UartRecvStep++; break;   
case 6: if (dat != HIBYTE(RecvSum)) goto L_CheckFirst; UartRecvStep++; break;   
case 7: if (dat != LOBYTE(RecvSum)) goto L_CheckFirst; UartRecvStep++; break;   
case 8: if (dat != 0x16) goto L_CheckFirst; UartReceived = TRUE; UartRecvStep++; break;   
L_CheckFirst:   
case 0: default: CommInit(); UartRecvStep = (dat == 0x46 ? 1 : 0); break;   
} 
```

}   
//系统初始化   
void Initial(void)   
{ UartBusy $=$ FALSE; SCON $= 0\mathrm{x}\mathrm{d}0$ //串口数据模式必须为8位数据 $+1$ 位偶检验 AUXR $= 0\mathrm{x}\mathrm{c}0$ TMOD $= 0\mathrm{x}00$ TH0 $\equiv$ HIBYTE(T1MS); TL0 $=$ LOBYTE(T1MS); TR0 $= 1$ TH1 $=$ HIBYTE(BR(MINBAUD)); TL1 $=$ LOBYTE(BR(MINBAUD)); TR1 $= 1$ ET0 $= 1$ ES $= 1$ EA $= 1$ }   
//Xms延时程序   
void DelayXms(WORD x)   
{ do { f1ms $=$ FALSE; while(!f1ms); }while(x--);   
}   
//串口数据发送程序   
BYTEUartSend(BYTE dat)   
{ while(UartBusy); UartBusy $=$ TRUE; ACC $=$ dat; TB8 $=$ P; SBUF $=$ ACC; return dat;


//串口通讯初始化


void CommInit(void)   
{ UartRecvStep $= 0$ TimeOut $= 20$ UartReceived $\equiv$ FALSE;   
} 


//发送串口通讯数据包


void CommSend(BYTE size)   
{ WORD sum; BYTE i; UartSend(0x46); UartSend(0xb9); UartSend(0x6a); UartSend(0x00); sum $=$ size $+6 + 0$ x6a; UartSend(size $+6$ for $\mathrm{i = 0}$ ;i<size;i++) { sum $+ =$ UartSend(TxBuffer[i]); } UartSend(HIBYTE(sum)); UartSend(LOBYTE(sum)); UartSend(0x16); while (UartBusy); CommInit(); 


//对STC15系列的芯片进行数据下载程序


```txt
BOOL Download(BYTE *pdat, long size)  
{  
    BYTE arg;  
    BYTE cnt;  
    WORD addr;  
    //握手  
    CommInit();  
    while (1)  
    {  
        if (UartRecvStep == 0)
```

{ UartSend(0x7f); DelayXms(10); } if (UartReceived) { arg $=$ RxBuffer[4]; if (RxBuffer[0] $\equiv = 0$ x50) break; return FALSE; } //设置参数 TxBuffer[0] $= 0\mathrm{x}01$ . TxBuffer[1] $=$ arg; TxBuffer[2] $= 0\mathrm{x}40$ . TxBuffer[3] $=$ HIBYTE(RL(MAXBAUD)); TxBuffer[4] $=$ LOBYTE(RL(MAXBAUD)); TxBuffer[5] $= 0\mathrm{x}00$ . TxBuffer[6] $= 0\mathrm{x}00$ . TxBuffer[7] $= 0\mathrm{x}3$ CommSend(8); while (1) { if(TimeOut $\equiv = 0$ )return FALSE; if(UartReceived) { if (RxBuffer[0] $\equiv = 0$ x01) break; return FALSE; } } //准备 TH1 $=$ HIBYTE(BR(MAXBAUD)); TL1 $=$ LOBYTE(BR(MAXBAUD)); DelayXms(10); TxBuffer[0] $= 0\mathrm{x}05$ ; CommSend(1); while (1) { if(TimeOut $\equiv = 0$ )return FALSE; if(UartReceived) { if (RxBuffer[0] $\equiv = 0$ x05) break;

return FALSE;   
}   
//擦除   
DelayXms(10);   
TxBuffer[0] $= 0\mathrm{x}03$ .   
TxBuffer[1] $= 0\mathrm{x}00$ .   
CommSend(2);   
TimeOut $= 100$ while (1)   
{ if(TimeOut $\equiv = 0$ ) return FALSE; if(UartReceived) { if(RxBuffer[0] $\equiv = 0\mathrm{x}03$ ) break; return FALSE; }   
}   
//写用户代码   
DelayXms(10);   
addr $= 0$ .   
TxBuffer[0] $= 0\mathrm{x}22$ while (addr < size)   
{ TxBuffer[1] $=$ HIBYTE(addr); TxBuffer[2] $=$ LOBYTE(addr); cnt $= 0$ . while (addr < size) { TxBuffer[cnt+3] $=$ pdat(addr); addr++; cnt++; if (cnt >= 128) break; } CommSend(cnt + 3);   
while (1) { if(TimeOut $\equiv = 0$ ) return FALSE; if(UartReceived) { if((RxBuffer[0] $\equiv = 0\mathrm{x}02$ &&(RxBuffer[1] $\equiv = ^{\prime}\mathrm{T})$ )break; return FALSE; }

```c
TxBuffer[0] = 0x02;  
}  
//写硬件选项(如果不需要修改硬件选项,此步骤可直接跳过)  
//说明：在利用其他MCU（如单片机，ARM，DSP等）对STC15系列单片机进行串口ISP下载时，  
// STC15系列单片机的工作时钟频率默认为24MHz，此步骤中的时钟设置即是将STC15系列  
// 单片机的工作时钟设置为24MHz时钟。  
// 如果用户不需要修改硬件选项,此步骤可直接跳过,此时所有的硬件选项都维持不变，  
// STC15系列单片机的频率为上一次所调节频率，反之若写改硬件选项,则STC15系列单片  
// 机的内部IRC频率将被固定写为24M。  
//建议：第一次使用STC-ISP下载软件将从芯片的硬件选项设置好，  
// 以后再使用主控芯片对从芯片下载程序时不写硬件选项  
DelayXms(10);  
for (cnt=0; cnt<128; cnt++)  
{  
    TxBuffer[cnt] = 0xff;  
}  
TxBuffer[0] = 0x04;  
TxBuffer[1] = 0x00;  
TxBuffer[2] = 0x00;  
TxBuffer[34] = 0xff;  
TxBuffer[62] = arg;  
TxBuffer[63] = 0x7f;  
TxBuffer[64] = 0xf7;  
TxBuffer[65] = 0xb;  
TxBuffer[66] = 0x1f;  
CommSend(67);  
while (1)  
{  
    if (TimeOut == 0) return FALSE;  
    if (UartReceived)  
    {  
        if ((RxBuffer[0] == 0x04) && (RxBuffer[1] == 'T')) break;  
        return FALSE;  
    }  
}  
//下载完成  
return TRUE;  
}  
char code DEMO[256] = {  
0x02, 0x00, 0x5E, 0x12, 0x00, 0x4B, 0x75, 0xB0, 0xEF, 0x12, 0
```

<table><tr><td>0x00,</td><td>0x2C,</td><td>0x75,</td><td>0xB0,</td><td>0xFE,</td><td>0x12,</td><td>0x00,</td><td>0x2C,</td></tr><tr><td>0x75,</td><td>0xB0,</td><td>0xFD,</td><td>0x12,</td><td>0x00,</td><td>0x2C,</td><td>0x75,</td><td>0xB0,</td></tr><tr><td>0xFB,</td><td>0x12,</td><td>0x00,</td><td>0x2C,</td><td>0x75,</td><td>0xB0,</td><td>0xF7,</td><td>0x12,</td></tr><tr><td>0x00,</td><td>0x2C,</td><td>0x80,</td><td>0xDA,</td><td>0xE4,</td><td>0xFF,</td><td>0xFE,</td><td>0xE4,</td></tr><tr><td>0xFD,</td><td>0xFC,</td><td>0x0D,</td><td>0xCD,</td><td>0x00,</td><td>0x01,</td><td>0x0C,</td><td>0xBC,</td></tr><tr><td>0x01,</td><td>0xF8,</td><td>0xCD,</td><td>0xF4,</td><td>0xF5,</td><td>0xF0,</td><td>0xBF,</td><td>0x00,</td></tr><tr><td>0x01,</td><td>0xE8,</td><td>0xBE,</td><td>0x03,</td><td>0xE8A,</td><td>0xBF,</td><td>0xE8,</td><td>0xE7,</td></tr><tr><td>0x02,</td><td>0x00,</td><td>0x4B,</td><td>0x75,</td><td>0x80,</td><td>0xFF,</td><td>0x75,</td><td>0x90,</td></tr><tr><td>0xFF,</td><td>0x75,</td><td>0xA0,</td><td>0xFF,</td><td>0x75,</td><td>0xB0,</td><td>0xFF,</td><td>0x75,</td></tr><tr><td>0xC0,</td><td>0xFF,</td><td>0x75,</td><td>0xC8,</td><td>0xFF,</td><td>0x22,</td><td>0x78,</td><td>0x7F,</td></tr><tr><td>0xE4,</td><td>0xF6,</td><td>0xD8,</td><td>0xCD,</td><td>0x75,</td><td>0x81,</td><td>0x07,</td><td>0x02,</td></tr><tr><td>0x00,</td><td>0x03,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td></tr><tr><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td></tr><tr><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td></tr><tr><td>0x00,</td><td>0x01,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td></tr><tr><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td></tr><tr><td>0x00,</td><td>0x02,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td></tr><tr><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td></tr><tr><td>0x00,</td><td>0x03,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td></tr><tr><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x01,</td></tr><tr><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x01,</td></tr><tr><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td></tr><tr><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x01,</td></tr><tr><td>0x00,</td><td>0x01,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x01,</td></tr><tr><td>0x00,</td><td>0x01,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x01,</td></tr><tr><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x01,</td></tr><tr><td>0x00,</td><td>0x01,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td></tr><tr><td>0x01,</td><td>0x01,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x01,</td></tr><tr><td>0x01,</td><td>0x01,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x01,</td></tr><tr><td>0x01,</td><td>0x01,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td></tr><tr><td>0x01,</td><td>0x01,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x00,</td><td>0x01,</td></tr><tr><td>0x02,</td><td>0x02,</td><td>0x01,</td><td>0x01,</td><td>0x01,</td><td>0x01,</td><td>0x01,</td><td>0x01,</td></tr></table>

# 附录A：STC15W104SW系列单片机总体介绍

# A.1 STC15W104SW系列简介(现有工程样品供测试，会用STC15W201S系列取代)

# 管脚P1.0不要用，INT0/INT1/INT2/INT3/INT4不要用

STC15W104SW系列单片机是STC生产的单时钟/机器周期(1T)的单片机，是�宽 ����压//高可靠/低功耗/超强抗干扰的新一代8051单片机，�采用STC第�九代��加密 技术，超���级加密 ， �代码完全兼容传统8051,但速度快8-12倍。 � �� R/C时钟 $( \pm 0 . 3 \% )$ ， $\pm 1 \%$ 温飘 $\mathrm { - 4 0 ^ { \circ } C }$ ${ \sim } + 8 5 \mathrm { \bar { C } }$ )，常温下温飘 $\pm 0 . 6 \% ( - 2 0 \mathrm { ^ { \circ } C \sim + 6 5 ^ { \circ } C ) }$ $\pm 0 . 6 \%$ ， $5 \mathrm { M H z } { \sim } 3 5 \mathrm { M H z }$ 宽范围可设置，可彻底省掉外部昂贵的晶振和外部复位电路(内部已集成高可靠复位电路，ISP编程时16级复位门槛电压可选)。1组高速 异步串行通信口(UART)，可在两组管脚之间进行切换，分时复用可作两组串行口使用，�针对 /电机控制/强干扰场合。

在 Keil C C 开发环境中，选择 Intel 8052 编译，头文件包含<reg51.h>即可

现STC15系列单片机采用STC-Y5超高速 CPU内核，在相同的时钟频率下，速度又比STC早期的1T系列单片机(如STC12系列/STC11系列/STC10系列)的速度快 $2 0 \%$ .

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/268e53134683b57ce8c2f2876f82d32a8b98449bd9e6f47342aad7e73b37c9c4.jpg)


1. 增强型 8051 CPU，1T，单时钟/机器周期，速度比普通8051快8-12倍

2. 工作电压：5.5V - 2.4V

3. 2K/4K/5K字节片内Flash程序存储器，擦写次数10万次以上

4. 片 128字节

5. 有片内EEPROM功能，擦写次数10万次以上

6. ISP/IAP，在系统可编程/在应用可编程，无需编程器/仿真器

7. 内部高可靠复位，ISP编程时16级复位门槛电压可选，可彻底省掉外部复位电路

8. 内部高精 度R/C时钟 $( \pm 0 . 3 \% )$ ， $\pm 1 \%$ 温飘 $( - 4 0 ^ { \circ } \mathrm { C } \sim + 8 5 ^ { \circ } \mathrm { C }$ )，常温下温飘 $\pm 0 . 6 \% ( - 2 0 \% \mathrm { { - } \it { 6 } \mathrm { { 5 } \mathrm { { ( - } \it { 6 } \mathrm { { 5 } \mathrm { { C ) } } } } } } $ $_ { \mathrm { i } \mathrm { 0 . 6 \% } }$ )，内部时钟从5MHz~35MHz可选(5.5296MHz / 11.0592MHz / 22.1184MHz / 33.1776MHz)

9. 工作频率范围： $5 \mathrm { M H z } \sim 3 5 \mathrm { M H z }$ ，相当于普通8051的60MHz～420MHz

10.一组高速 异步行串行口，可在两组管脚之间进行切换，分时复用可当两组串口使用：串口(RxD/P3.0, TxD/P3.1)可以切换到(RxD_2/P3.6, TxD_2/P3.7).

11.低功耗设计：低速模式，空闲模式，掉电模式/停机模式.

12.可将掉电模式/停机模式唤醒的定时器：有内部低功耗掉电唤醒专用定时器。

13.可将掉电模式/停机模式唤醒的资源有：INT0/P3.2, INT1/P3.3 (INT0/INT1上升沿下降沿中断均可), INT2 /P3.6, INT3/P3.7, INT4/P3.0(INT2/INT3 /INT4 仅可下降沿中断)；管脚RxD(可在RxD/P3.0和RxD_2/P3.6之间切换)；管脚T0T2(下降沿，不产生中断，前提是在进入掉电模式/停机模式前定时器中断已经被允许)；内部掉电唤醒专用定时器。

14. 共2个定时器/计数器——T0(兼容普通8051的定时器)/T2。定时器/计数器0和定时器/计数器2都是16位可重装载的定时器/计数器，既可作定时器(对内部系统时钟进行计数)也可作计数器器(对外部管脚的时钟输入进行计数)，并可实现可编程时钟输出T0CLKO/T2CLKO，还可对外部管脚的时钟输入进行时钟分频输出作分频器使用。

15. 可编程时钟输出功能(对内部系统时钟或对外部管脚的时钟输入进行时钟分频输出)：由于STC15系列5V单片机I/O口的对外输出速度最快不超过13.5MHz，所以5V单片机的对外可编程时钟输出速度最快也不超过13.5MHz.；而3.3V单片机I/O口的对外输出速度最快不超过8MHz，故3.3V单片机的对外可编程时钟输出速度最快也不超过8MHz.

$\textcircled{1}$ T0在P1.4/T0CLKO进行可编程输出时钟(对内部系统时钟或对外部管脚T0/P1.2的时钟输入进行可编程时钟分频输出)；

$\textcircled{2}$ T2在P3.0/T2CLKO进行可编程输出时钟(对内部系统时钟或对外部管脚T2/P3.1的时钟输入进行可编程时钟分频输出)；

③以上2个定时器/计数器均可1~65536级分频输出。

主时钟在P5.4/MCLKO对外输出时钟，并可如下分频MCLK/1, MCLK/2, MCLK/4./1, ,

主时钟可以是内部R/C时钟，也可是外部输入的时钟或外部晶体振荡产生的时钟。MCLK是指主时钟频率，MCLKO是指主时钟输出。

STC15系列8-pin单片机(如STC15F101W系列)在MCLKO/P3.4口对外输出主时钟，STC15系列16-pin及其以上单片机、均在MCLKO/P5.4口对外输出主时钟。

16. 硬件�看 �(WDT)

17. 先进的指令集 结构，兼容普通8051指令集 ，有硬件乘法/除法指令

18. 通用I/O口 14个） 准双向口/弱上拉（普通8051传统I/O口）可设置成四种模式：准双向口/弱上拉，强��/强上拉，仅为输入/高阻，开漏每个I/O口驱动能力均可达到20mA，但整个芯片 �流 90mA.如果I/O口不够用，可外接74HC595(参考价0.21元)来扩展I/O口，并可多芯片级联扩展几十个I/O口。

19. 封装：SOP16, DIP16.

20. 全部 $1 7 5 \mathrm { ^ \circ C }$ 八小时高温烘烤，高品质制造保证

21. 开发环境：在 Keil C C 开发环境中，选择 Intel 8052 编译，头文件包含<reg51.h>即可

# A.2 STC15W104SW系列单片机的内部结构图

STC15W104SW系列单片机的内部结构框图如下图所示。STC15W104SW系列单片机中包含中央处理器(CPU)、程序存储器(Flash)、数据存储器(SRAM)、定时器/计数器、掉电唤醒专用定时器、I/O口、看门狗、高速 异步串行通信端口UART、片内高精 度R/C时钟及高可靠复位等模块。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b6c4e17ad73d8384d241aae213ddf0bf59970689e32ed7d4d03e8470062d0ef9.jpg)


STC15W104SW系列内部结构框图

# A.3 STC15W104SW系列单片机管脚图

所有封装形式均满足欧盟RoHS要求，强烈推荐选择SOP16贴片封装，传统的插件DIP16封装稳定供货。

中国大陆本土STC姚永平独立创新设计：

请不要再抄袭我们的设计、规格和管脚排列，

再抄袭就很无..

MCLKO是指主时钟输出，主钟对外输出的时钟可如下分频MCLK/1, MCLK/2, MCLK/4./1, ,

主时钟可以是内部R/C时钟，可是外部输入的时钟或外部晶振荡产生的时钟。MCLK是指时钟频率。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ed4bc727e3a174bdcc035ed4f3fc06e858432f18af7dcae2da16c2488fb1f0bb.jpg)


T0CLKO是指定时器/计数器0的可编程时钟输出

(对内部系统时钟或对外部管脚T0/P1.2的时钟输入进行可编程时钟分频输出);

T2CLKO是指定时器/计数器2的可编程时钟输出

(对内部系统时钟或对外部管脚T2/P3.1的时钟输入进行可编程时钟分频输出);

T0CLKO/T2CLKO除可以对内部系统时钟进行可编程时钟输出外，还可以对外部管脚T0/T2的时钟输入进行时钟分频输出，作分频器使用。

对于STC15系列5V单片机，由于I/O口的对外输出速度最快不超过13.5MHz，所以对外可编程时钟输出速度最快也不超过13.5MHz；对于3.3V单片机，由于I/O口的对外输出速度最快不超过8MHz，所以对外可编程时钟输出速度最快也不超过8MHz；

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>7</td><td>6</td><td>5</td><td>4</td><td>3</td><td>2</td><td>1</td><td>0</td><td>Reset Value</td></tr><tr><td>AUXR1
P_SW1</td><td>A2H</td><td>Auxiliary
register 1</td><td>S1_S1</td><td>S1_S0</td><td>CCP_S1</td><td>CCP_S0</td><td>SPI_S1</td><td>SPI_S0</td><td>0</td><td>DPS</td><td>x1xx,xx0x</td></tr><tr><td>CLK_DIV
(PCON2)</td><td>97H</td><td>时钟分频寄存器</td><td>MCKO_S1</td><td>MCKO_S0</td><td>ADRJ</td><td>Tx_Rx</td><td>Tx2_Rx2</td><td>CLKS2</td><td>CLKS1</td><td>CLKS0</td><td>00x0,x000</td></tr></table>

<table><tr><td colspan="3">串口1/S1可在2个地方切换,由 S1_S0 控制位来选择</td></tr><tr><td>S1_S1</td><td>S1_S0</td><td>串口1/S1可在P1/P3之间来回切换</td></tr><tr><td>0</td><td>0</td><td>串口1/S1在[P3.0/RxD,P3.1/TxD]</td></tr><tr><td>0</td><td>1</td><td>串口1/S1在[P3.6/RxD_2,P3.7/TxD_2]</td></tr><tr><td>1</td><td>0</td><td>串口1/S1在[P1.6/RxD_3/XTAL2,P1.7/TxD_3/XTAL1]串口1在P1口时要使用内部时钟</td></tr><tr><td>1</td><td>1</td><td>无效</td></tr></table>

<table><tr><td>MCKO_S1</td><td>MCKO_S0</td><td>主时钟对外分频输出控制位
(主时钟可以是内部R/C时钟, 也可是外部输入的时钟或外部晶体振荡产生的时钟)</td></tr><tr><td>0</td><td>0</td><td>主时钟不对外输出时钟</td></tr><tr><td>0</td><td>1</td><td>主时钟对外输出时钟, 但时钟频率不被分频, 输出时钟频率 = MCLK / 1</td></tr><tr><td>1</td><td>0</td><td>主时钟对外输出时钟, 但时钟频率被2分频, 输出时钟频率 = MCLK / 2</td></tr><tr><td>1</td><td>1</td><td>主时钟对外输出时钟, 但时钟频率被4分频, 输出时钟频率 = MCLK / 4</td></tr></table>

主时钟可以是内部R/C时钟，也可是外部输入的时钟或外部晶体振荡产生的时钟，MCLK是指主时钟频率。STC15W104SW系列单片机在MCLKO/P5.4口对外输出主时钟。

STC15系列8-pin单片机(如STC15F101W系列)在MCLKO/P3.4口对外输出主时钟，STC15系列16-pin及其以上单片机(如STC15W4K60S4系列和STC15F2K60S2系列)均在MCLKO/P5.4口对外输出主时钟。

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>7</td><td>6</td><td>5</td><td>4</td><td>3</td><td>2</td><td>1</td><td>0</td><td>Reset Value</td></tr><tr><td>CLK_DIV(PCON2)</td><td>97H</td><td>时钟分频寄存器</td><td>MCKO_S1</td><td>MCKO_S0</td><td>ADRJ</td><td>Tx_Rx</td><td>Tx2_Rx2</td><td>CLKS2</td><td>CLKS1</td><td>CLKS0</td><td>00x0,x000</td></tr></table>

# Tx_Rx：串口1的中继广播方式设置

# 0：串口1为正常工作方式

1：串口1为中继广播方式，即将RxD端口输入的电平状态实时输出在TxD外部管脚上，TxD外部管脚可以对RxD管脚的输入信号进行实时整形放大输出，TxD管脚的对外输出实时反映RxD端口输入的电平状态。

串口1的RxD管脚和TxD管脚可以在2组不同管脚之间进行切换：[RxD/P3.0, TxD/P3.1]；

[RxD_2/P3.6, TxD_2/P3.7]. 

<table><tr><td>CLKS2</td><td>CLKS1</td><td>CLKSO</td><td>系统时钟选择控制位
(系统时钟是指对主时钟进行分频后供给CPU、串行口、定时器的实际工作时钟)</td></tr><tr><td>0</td><td>0</td><td>0</td><td>主时钟频率/1,不分频</td></tr><tr><td>0</td><td>0</td><td>1</td><td>主时钟频率/2</td></tr><tr><td>0</td><td>1</td><td>0</td><td>主时钟频率/4</td></tr><tr><td>0</td><td>1</td><td>1</td><td>主时钟频率/8</td></tr><tr><td>1</td><td>0</td><td>0</td><td>主时钟频率/16</td></tr><tr><td>1</td><td>0</td><td>1</td><td>主时钟频率/32</td></tr><tr><td>1</td><td>1</td><td>0</td><td>主时钟频率/64</td></tr><tr><td>1</td><td>1</td><td>1</td><td>主时钟频率/128</td></tr></table>

主时钟可以是内部R/C时钟，也可是外部输入的时钟或外部晶体振荡产生的时钟。

# A.4 STC15W104SW系列单片机选型价格一览表

<table><tr><td rowspan="2">型号</td><td rowspan="2">工作电压(V)</td><td rowspan="2">Flash程序存储器byte)</td><td rowspan="2">大容量SRAM字节</td><td rowspan="2">串行口并可掉电唤醒</td><td rowspan="2">SPI</td><td rowspan="2">普通定时器计数器T0/T2外部管脚也能掉电唤醒</td><td rowspan="2">CCPPCA PWM并可掉电唤醒</td><td rowspan="2">掉电唤醒专用定时器</td><td rowspan="2">标准外部中断支持掉电唤醒</td><td rowspan="2">A/D8路(3路PWM可当3路D/A使用)</td><td rowspan="2">比较器</td><td rowspan="2">DPR</td><td rowspan="2">EEPROM</td><td rowspan="2">内部低压检测中断并可掉电唤醒</td><td rowspan="2">内部复位(可选复位门槛电压)</td><td rowspan="2">看门狗</td><td colspan="2">所有封装SOP16/DIP16价格(RMB ¥)</td></tr><tr><td>SOP16</td><td>DIP16</td></tr><tr><td colspan="18">STC15W104SW系列单片机选型价格一览表</td><td></td></tr><tr><td>STC15W102SW</td><td>5.5-2.4</td><td>2K</td><td>128</td><td>1</td><td>-</td><td>2</td><td>-</td><td>有</td><td>5</td><td>-</td><td>-</td><td>1</td><td>3K</td><td>有</td><td>16级</td><td>有</td><td></td><td></td></tr><tr><td>STC15W104SW</td><td>5.5-2.4</td><td>4K</td><td>128</td><td>1</td><td>-</td><td>2</td><td>-</td><td>有</td><td>5</td><td>-</td><td>-</td><td>1</td><td>1K</td><td>有</td><td>16级</td><td>有</td><td>¥1.7</td><td>¥1.9</td></tr><tr><td rowspan="2">IAP15W105SW</td><td rowspan="2">5.5-2.4</td><td rowspan="2">5K</td><td rowspan="2">128</td><td rowspan="2">1</td><td rowspan="2">-</td><td rowspan="2">2</td><td rowspan="2">-</td><td rowspan="2">有</td><td rowspan="2">5</td><td rowspan="2">-</td><td rowspan="2">-</td><td rowspan="2">1</td><td rowspan="2">IAP</td><td rowspan="2">有</td><td rowspan="2">16级</td><td rowspan="2">有</td><td>¥1.7</td><td>¥1.9</td></tr><tr><td colspan="2">用户可将用户程序区的程序Flash当EEPROM使用</td></tr></table>

# 提供客制化IC服务

建议用户选用SOP16封装，但DIP16封装仍正常供货

封装为DIP16的单片机比封装为SOP16的单片机要贵0.2元；

以上单价为200K起订

量小每片需加0.1元

以上价格运费由客户承担,零售10片起

如对价格不满，可来电要求降价

总结：STC15W104SW系列单片机有：两个16位重装载定时器/计数器(这两个定时器/计数器分别是：定时器/计数器0和定时器/计数器2)；5个支持掉电唤醒的外部中断INT0/INT1/INT2/INT3/INT4；1组高速 异步串行通信端口；1个数据指针DPTR等功能。表中“-”表示该型号的单片机无相应的功能。STC15W104SW系列单片机无SPI、无A/D转换、无CCP/PWM/PCA、无掉电唤醒定时器、无外部数据总线等功能。

因为程序区的最后7个字节单元被强制性的放入全球唯一ID号的内容，所以用户实际可以使用的程序空间大小要比选型表中的大小少7个字节。

# A.5 STC15W104SW单片机在系统可编程典型应用(ISP)线路图

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/2d6f1c28399c99c5da1361226d5b72ecc49e2857a536d4d7502b974410b5034b.jpg)


内部高可靠复位，可彻底省掉外部复位电路

P5.4/RST/MCLKO脚出厂时默认为I/O口，可以通过 STC-ISP 编程器将其设置为RST复位脚(高电平复位).

内部集成高精 度R/C时钟 $( \pm 0 . 3 \%$ )， $\pm 1 \%$ 温飘 $( - 4 0 ^ { \circ } \mathrm { C } \sim + 8 5 ^ { \circ } \mathrm { C } )$ )，常温下温飘 $\pm 0 . 6 \%$ $\pm 0 . 6 \% ( - 2 0 \% \sim + 6 5 \% )$ )，5MHz~35MHz宽范围可设置，可彻底省掉外部昂贵的晶振

建议在Vcc和Gnd之间就近加上电源去耦电容C1 $( 4 7 \mu \mathrm { F } )$ , ${ \mathrm { C } } 2 ( 0 . 1 \mu \mathrm { F } )$ , 可去除电源线噪声，提高抗干扰能力

# A.6 STC15W104SW系列单片机的管脚说明

<table><tr><td>管脚</td><td>管脚编号(封装SOP16/DIP16)</td><td colspan="2">说明</td></tr><tr><td rowspan="2">P1.0/RSTOUT_LOW</td><td rowspan="2">15</td><td>P1.0</td><td>标准I/0口 PORT1[0]</td></tr><tr><td>RSTOUT_LOW</td><td>上电后,输出低电平,在复位期间也是输出低电平,用户可用软件将其设置为高电平或低电平,如果要读外部状态,可将该口先置高后再读</td></tr><tr><td>P1.1</td><td>16</td><td colspan="2">标准I/0口 PORT1[1]</td></tr><tr><td rowspan="2">P1.2/T0</td><td rowspan="2">1</td><td>P1.2</td><td>标准I/0口 PORT1[2]</td></tr><tr><td>T0</td><td>定时器/计数器0的外部输入</td></tr><tr><td>P1.3</td><td>2</td><td colspan="2">标准I/0口 PORT1[3]</td></tr><tr><td rowspan="2">P1.4/T0CLKO</td><td rowspan="2">3</td><td>P1.4</td><td>标准I/0口 PORT1[4]</td></tr><tr><td>TOCLKO</td><td>T0的时钟输出可通过设置INT_CLKO[0]位/T0CLKO将该管脚配置为T0CLKO,也可对T0脚的外部时钟输入进行分频输出</td></tr><tr><td>P1.5</td><td>4</td><td colspan="2">标准I/0口 PORT1[5]</td></tr><tr><td rowspan="4">P3.0/RxD/INT4/T2CLKO</td><td rowspan="4">9</td><td>P3.0</td><td>标准I/0口 PORT3[0]</td></tr><tr><td>RxD</td><td>串口数据接收端</td></tr><tr><td>INT4</td><td>外部中断4,只能下降沿中断,INT4支持掉电唤醒</td></tr><tr><td>T2CLKO</td><td>T2的时钟输出可通过设置INT_CLKO[2]位/T2CLKO将该管脚配置为T2CLKO</td></tr><tr><td rowspan="3">P3.1/TxD/T2</td><td rowspan="3">10</td><td>P3.1</td><td>标准I/O口 PORT3[1]</td></tr><tr><td>TxD</td><td>串口数据发送端</td></tr><tr><td>T2</td><td>定时器/计数器2的外部输入</td></tr><tr><td rowspan="2">P3.2/INT0</td><td rowspan="2">11</td><td>P3.2</td><td>标准I/O口 PORT3[2]</td></tr><tr><td>INT0</td><td>外部中断0,既可上升沿中断也可下降沿中断.如果IT0(TCON.0)被置为1,INT0管脚仅为下降沿中断。如果IT0(TCON.0)被清0,INT0管脚既支持上升沿中断也支持下降沿中断. INT0支持掉电唤醒。</td></tr><tr><td rowspan="2">P3.3/INT1</td><td rowspan="2">12</td><td>P3.3</td><td>标准I/O口 PORT3[3]</td></tr><tr><td>INT1</td><td>外部中断1,既可上升沿中断也可下降沿中断.如果IT1(TCON.2)被置为1,INT1管脚仅为下降沿中断。如果IT1(TCON.2)被清0,INT1管脚既支持上升沿中断也支持下降沿中断. INT1支持掉电唤醒。</td></tr><tr><td rowspan="3">P3.6/INT2/RxD_2</td><td rowspan="3">13</td><td>P3.6</td><td>标准I/0口 PORT3[6]</td></tr><tr><td>INT2</td><td>外部中断2,只能下降沿中断INT2支持掉电唤醒</td></tr><tr><td>RxD_2</td><td>串口数据接收端</td></tr><tr><td rowspan="3">P3.7/INT3/TxD_2</td><td rowspan="3">14</td><td>P3.7</td><td>标准I/0口 PORT3[7]</td></tr><tr><td>INT3</td><td>外部中断3,只能下降沿中断INT3支持掉电唤醒</td></tr><tr><td>TxD_2</td><td>串口数据发送端</td></tr><tr><td rowspan="3">P5.4/RST/MCLKO</td><td rowspan="3">5</td><td>P5.4</td><td>标准I/O口 PORT5[4]</td></tr><tr><td>RST</td><td>复位脚(高电平复位)</td></tr><tr><td>MCLKO</td><td>主时钟输出;输出的频率可为MCLK/1,MCLK/2,MCLK/4。主时钟可以是内部R/C时钟,也可是外部输入的时钟或外部晶体振荡产生的时钟,MCLK指主时钟频率。</td></tr><tr><td>P5.5</td><td>7</td><td colspan="2">标准I/0口 PORT5[5]</td></tr><tr><td>Vcc</td><td>6</td><td colspan="2">电源正极</td></tr><tr><td>Gnd</td><td>8</td><td colspan="2">电源负极,接地</td></tr></table>

# A.7 STC15W104SW系列单片机命名规则

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/0de9ab580ca5b0f7e7f6eefdd0d84a41bd2bf9070d208a020317fadce9b6229d.jpg)


# 附录B：STC15系列单片机电气特性


Absolute Maximum Ratings


<table><tr><td>Parameter</td><td>Symbol</td><td>Min</td><td>Max</td><td>Unit</td></tr><tr><td>Srotage temperature</td><td>TST</td><td>-55</td><td>+125</td><td>°C</td></tr><tr><td>Operating temperature (I)</td><td>TA</td><td>-40</td><td>+85</td><td>°C</td></tr><tr><td>Operating temperature (C)</td><td>TA</td><td>0</td><td>+70</td><td>°C</td></tr><tr><td>DC power supply (5V)</td><td>VDD - VSS</td><td>-0.3</td><td>+5.5</td><td>V</td></tr><tr><td>DC power supply (3V)</td><td>VDD - VSS</td><td>-0.3</td><td>+3.6</td><td>V</td></tr><tr><td>Voltage on any pin</td><td>-</td><td>-0.3</td><td>VCC + 0.3</td><td>V</td></tr></table>


DC Specification (5V MCU)


<table><tr><td rowspan="2">Sym</td><td rowspan="2">Parameter</td><td colspan="4">Specification</td><td rowspan="2">Test Condition</td></tr><tr><td>Min.</td><td>Typ</td><td>Max.</td><td>Unit</td></tr><tr><td>VDD</td><td>Operating Voltage</td><td>3.3</td><td>5.0</td><td>5.5</td><td>V</td><td></td></tr><tr><td>IPD</td><td>Power Down Current</td><td>-</td><td>&lt; 0.1</td><td>-</td><td>uA</td><td>5V</td></tr><tr><td>IIDL</td><td>Idle Current</td><td>-</td><td>3.0</td><td>-</td><td>mA</td><td>5V</td></tr><tr><td>ICC</td><td>Operating Current</td><td>-</td><td>4</td><td>20</td><td>mA</td><td>5V</td></tr><tr><td>VIL1</td><td>Input Low (P0,P1,P2,P3)</td><td>-</td><td>-</td><td>0.8</td><td>V</td><td>5V</td></tr><tr><td>VIH1</td><td>Input High (P0,P1,P2,P3)</td><td>2.0</td><td>-</td><td>-</td><td>V</td><td>5V</td></tr><tr><td>VIH2</td><td>Input High (RESET)</td><td>2.2</td><td>-</td><td>-</td><td>V</td><td>5V</td></tr><tr><td>IOL1</td><td>Sink Current for output low (P0,P1,P2,P3)</td><td>-</td><td>20</td><td>-</td><td>mA</td><td>5V@Vpin=0.45V</td></tr><tr><td>IOH1</td><td>Sourcing Current for output high (P0,P1,P2,P3) (Quasi-output)</td><td>200</td><td>270</td><td>-</td><td>uA</td><td>5V</td></tr><tr><td>IOH2</td><td>Sourcing Current for output high (P0,P1,P2,P3) (Push-Pull, Strong-output)</td><td>-</td><td>20</td><td>-</td><td>mA</td><td>5V@Vpin=2.4V</td></tr><tr><td>IIL</td><td>Logic 0 input current (P0,P1,P2,P3)</td><td>-</td><td>-</td><td>50</td><td>uA</td><td>Vpin=0V</td></tr><tr><td>ITL</td><td>Logic 1 to 0 transition current (P0,P1,P2,P3)</td><td>100</td><td>270</td><td>600</td><td>uA</td><td>Vpin=2.0V</td></tr></table>


DC Specification (3V MCU)


<table><tr><td rowspan="2">Sym</td><td rowspan="2">Parameter</td><td colspan="4">Specification</td><td rowspan="2">Test Condition</td></tr><tr><td>Min.</td><td>Typ.</td><td>Max.</td><td>Unit</td></tr><tr><td>VDD</td><td>Operating Voltage</td><td>2.4</td><td>3.3</td><td>3.6</td><td>V</td><td></td></tr><tr><td>IPD</td><td>Power Down Current</td><td>-</td><td>&lt;0.1</td><td>-</td><td>uA</td><td>3.3V</td></tr><tr><td>IIDL</td><td>Idle Current</td><td>-</td><td>2.0</td><td>-</td><td>mA</td><td>3.3V</td></tr><tr><td>ICC</td><td>Operating Current</td><td>-</td><td>4</td><td>10</td><td>mA</td><td>3.3V</td></tr><tr><td>VIL1</td><td>Input Low (P0,P1,P2,P3)</td><td>-</td><td>-</td><td>0.8</td><td>V</td><td>3.3V</td></tr><tr><td>VIH1</td><td>Input High (P0,P1,P2,P3)</td><td>2.0</td><td>-</td><td>-</td><td>V</td><td>3.3V</td></tr><tr><td>VIH2</td><td>Input High (RESET)</td><td>2.2</td><td>-</td><td>-</td><td>V</td><td>3.3V</td></tr><tr><td>IOL1</td><td>Sink Current for output low (P0,P1,P2,P3)</td><td>-</td><td>20</td><td>-</td><td>mA</td><td>3.3V@Vpin=0.45V</td></tr><tr><td>IOH1</td><td>Sourcing Current for output high (P0,P1,P2,P3) (Quasi-output)</td><td>140</td><td>170</td><td>-</td><td>uA</td><td>3.3V</td></tr><tr><td>IOH2</td><td>Sourcing Current for output high (P0,P1,P2,P3) (Push-Pull)</td><td>-</td><td>20</td><td>-</td><td>mA</td><td>3.3V</td></tr><tr><td>IIL</td><td>Logic 0 input current (P0,P1,P2,P3)</td><td>-</td><td>8</td><td>50</td><td>uA</td><td>Vpin=0V</td></tr><tr><td>ITL</td><td>Logic 1 to 0 transition current (P0,P1,P2,P3)</td><td>-</td><td>110</td><td>600</td><td>uA</td><td>Vpin=2.0V</td></tr></table>

# 附录C：内部常规256字节RAM间接寻址测试程序

;/* --- STC International Limited */ 

;/* --- STC 姚永平 2006/1/6 V1.0 */

;/* --- STC15 系列单片机 内部常规RAM间接寻址测试程序 */

;/* --- 研发顾问QQ: 13922805190 */

;/* --- Fax: 0755-82905966 */ 

;/* --- Tel: 0755-82948409 */ 

;/* --- Web: www.STCMCU.com */ 

;/* --- 本演示程序在STC 15系列 ISP的下载编程工具上测试通过 */

;/* --- 如果要在程序中使用该程序,请在程序中注明使用了STC的资料及程序 */

;/* --- 如果要在文章中引用该程序,请在文章中注明使用了STC的资料及程序 */

TEST_CONST EQU 5AH 

;TEST_RAM EQU 03H 

ORG 0000H 

LJMP INITIAL 

ORG 0050H 

INITIAL: 

MOV R0, #253 

MOV R1, #3H 

TEST_ALL_RAM: 

MOV R2, #0FFH 

TEST_ONE_RAM: 

MOV A, R2 

MOV @R1, A 

CLR A 

MOV A, @R1 

CJNE A, 2H, ERROR_DISPLAY 

DJNZ R2, TEST_ONE_RAM 

INC R1 

DJNZ R0, TEST_ALL_RAM 

OK_DISPLAY: 

MOV P1, #11111110B 

Wait1: 

SJMP Wait1 

ERROR_DISPLAY: 

MOV A, R1 

MOV P1, A 

Wait2: 

SJMP Wait2 

END 

# 附录D：用串口扩展I/O接口

STC15系列单片机串行口的方式0可用于I�/O � �那么将它用来扩展并行 �O �

在操作方式0时，串行口作同步移�位寄存器，其波特率是固定的，为S�YScl��k/12（ � �k系统时钟频率）。数据由RXD端（P3.0 �位时钟由TXD端（P3.1收的是8位数据，低位在先。

# 一、用74HC165扩展并行输入口

下图是利用两片74HC165扩展二个8位并行输入口的接口电路图。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/076f7eb9f4a810df7740788b03320cd3016c8377a024fff9e44c8d4afc813cde.jpg)


74HC165是8位并行置入�移位寄存器。当�移位�/置入端 �L) �数据置入寄存器；当 $\mathrm { S } / \mathrm { L } { = } 1$ ，且时钟禁止端（第15脚）为低电平时，允许时钟输入，这时在时钟脉冲的作用下，数据将由 A到 H方向移位。

上图中，TXD(P3.1)作为移�位脉冲输出端与所有74HC165 �位脉冲输入端CP �；（P3.0）作为串行输入端与74HC165的串行输出端 H相连；P1.0用来控制74HC165 �而同S�/L �；74HC165 ��端（15脚）接地，表示允许时钟输入。当扩展多个8口时，两芯片的首尾（ $\mathsf { Q } _ { \mathrm { H } }$ 与 IN）相连。

下面的程序是从16位扩展口读入5 �它们转存到内部RAM 20H开始的单元中。

<table><tr><td></td><td>MOV</td><td>R7,</td><td>#05H</td><td>;设置读入组数</td></tr><tr><td></td><td>MOV</td><td>RO,</td><td>#20H</td><td>;设置内部RAM数据区首址</td></tr><tr><td>START:</td><td>CLR</td><td>P1.0</td><td></td><td>;并行置入数据,S/L=0</td></tr><tr><td></td><td>SETB</td><td>P1.0</td><td></td><td>;允许串行移位S/L=1</td></tr><tr><td></td><td>MOV</td><td>R1,</td><td>#02H</td><td>;设置每组字节数,即外扩74LS165的个</td></tr><tr><td>RXDATA:</td><td>MOV</td><td>SCON,</td><td>#00010000B</td><td>;设串行方式0,允许接收,启动接收过</td></tr><tr><td>WAIT:</td><td>JNB</td><td>RI,</td><td>WAIT</td><td>;未接收完一帧,循环等待</td></tr><tr><td></td><td>CLR</td><td>RI</td><td></td><td>;清RI标志,准备下次接收</td></tr><tr><td></td><td>MOV</td><td>A,</td><td>SBUF</td><td>;读入数据</td></tr><tr><td></td><td>MOV</td><td>@RO,</td><td>A</td><td>;送至RAM缓冲区</td></tr><tr><td></td><td>INC</td><td>RO</td><td></td><td>;指向下一个地址</td></tr><tr><td></td><td>DJNZ</td><td>R1,</td><td>RXDATA</td><td>;为读完一组数据,继续</td></tr><tr><td></td><td>DJNZ</td><td>R7,</td><td>START</td><td>;5组数据未读完重新并行置入</td></tr><tr><td></td><td>......</td><td></td><td></td><td>;对数据进行处理</td></tr></table>

上面的程序对串行接收过程采用的是查询等待的控制方式，如有必要，也可改用中断方式。从理论上讲，按上图方法扩展的输入口几乎是无限的，但扩展的越多，口的操作速度也就越慢。

# 二、用74HC164扩展并行输出口

74HC164是8位串入并出移位寄存器。下图是利用74HC164扩展二个8位输出口的接口电路。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7c1f2ada009df5aeb4bb96c5c4bfd701ba2a12bc6dbcaf2734ac480f0868dd1e.jpg)


当单片机串行口工作在方式0的发送状态时，串行数据由P3.0（RXD）送出，移位时钟由P3.1（TXD）送出。在移位时钟的作用下，串行口发送缓冲器的数据一位一位地移入74HC164中。需要指出的是，由于74HC164无并行输出控制端，因而在串行输入过程中，其输出端的状态会不断变化，故在某些应用场合，在74HC164的输出端应加接输出三态门控制，以便保证串行输入结束后再输出数据。

下面是将RAM缓冲区30H、31H的内容串行口由74HC164并行输出的子程序。

START： 

MOV R7， #02H ；设置要发送的字节个数

MOV R0， #30H ；设置地址指针

MOV SCON，	 #00H ；设置串行口方式0

SEND： 

MOV A， @R0 

MOV SBUF，	 A ；启动串行口发送过程

WAIT： 

JNB TI， WAIT 一帧数据未发送完，循等待

CLR TI 

INC ；取下一个数

DJNZ R7，	 SEND 

RET 

# 附录E：RS485自动控制或I/O口控制下载线路图

# 1、利用USB转串口连接电脑的RS485控制下载线路图(自动控制或I/O口控制)

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5900d82aebe3396652e86d49be1ac45ddbefeace3050b5b1536699ccb20da58d.jpg)


# 2、利用RS232转串口连接电脑的RS485控制下载线路图(自动控制或I/O口控制)

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/098e7056e1c2b3e0d22bd78aa8eed69e5362e0e25f129167f3732380f7f33672.jpg)


# 附录F：一个I/O口驱动发光二极管并扫描按键

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/1678d8116a5b267da27b98ba1606959918e03c6e4369aa161def1dc095f6b1cd.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5a8ab256694a72863a138eb426a0578436822686e96256f0254e0160775324ee.jpg)


利用STC15系列单片机的I/O口可被设置成弱上拉,强上拉(推挽 )输出,仅为输入(高阻),开漏等四种工作模式的特性,可以将STC15系列单片机的I/O口同时作为发光二极管驱动及按键检测用，这样可以大幅节省I/O口。

当驱动发光二极管时，将该I/O口设置成强推挽 输出，输出高即可点亮发光二极管。当检测按键时，将该I/O口设置成弱上拉输入，再读外部口的状态，即可检测按键。

# 附录G：STC15系列单片机取代传统8051注意事项

STC15系列单片机的定时器0/定时器1与传统8051完全兼容，上电复位后，定时器部分缺省还是除12再计数的,所以定时器完全兼容。

STC15系列单片机对传统8051的111条指令执行速度全面提速,最快的指令快24倍,最慢的指令快3倍.靠软件延时实现精确延时的程序需要调整。

其它需注意的细节：

# 普通I/O口既作为输入又作为输出:

传统8051单片机执行I/O口操作,由高变低或由低变高,以及读外部状态都是12个时钟,而现在STC15系列单片机执行相应的操作是4个时钟.传统8051单片机如果对外输出为低,直接读外部状态是读不对的.必须先将I/O口置高才能够读对,而传统8051单片机由低变高的指令是12个时钟,该指令执行完成后,该I/O口也确实已变高.故可以紧跟着由低变高的指令后面,直接执行读该I/O口状态指令.而STC15系列单片机由于执行由低变高的指令是4个时钟,太快了,相应的指令执行完以后,I/O口还没有变高,要再过一个时钟之后,该I/O口才可以变高.故建议此状况下增加2个空操作延时指令再读外部口的状态。

# I/O口驱动能力:

最新STC15系列单片机I/O口的灌电流是20mA,驱动能力超强,驱动大电流时,不容易烧坏.

传统STC89Cxx系列单片机I/O口的灌电流是6mA,驱动能力不够强,不能驱动大电流,建议使用STC15系列

# 看门狗:

最新STC15系列单片机的看门狗寄存器WDT_CONTR的地址在C1H,增加了看门狗复位标志位

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>7</td><td>6</td><td>5</td><td>4</td><td>3</td><td>2</td><td>1</td><td>0</td><td>Reset value</td></tr><tr><td>WDT_CONTR</td><td>C1h</td><td>Watch-Dog-Timer Control register</td><td>WDT_FLAG</td><td>-</td><td>EN_WDT</td><td>CLR_WDT</td><td>IDLE_WDT</td><td>PS2</td><td>PS1</td><td>PS0</td><td>xx00,0000</td></tr></table>

传统STC89系列增强型单片机看门狗寄存器WDT_CONTR的地址在E1H,没有看门狗复位标志位

<table><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>7</td><td>6</td><td>5</td><td>4</td><td>3</td><td>2</td><td>1</td><td>0</td><td>Reset value</td></tr><tr><td>WDT_CONTR</td><td>E1h</td><td>Watch-Dog-Timer Control register</td><td>-</td><td>-</td><td>EN_WDT</td><td>CLR_WDT</td><td>IDLE_WDT</td><td>PS2</td><td>PS1</td><td>PS0</td><td>xx00,0000</td></tr></table>

最新STC15系列单片机的看门狗在ISP烧录程序可设置上电复位后直接启动看门狗,而传统STC89系列单片机无此功能.故最新STC15系列单片机看门狗更可靠.


与EEPROM


<table><tr><td colspan="12">STC15Fxx单片机ISP/IAP控制寄存器地址和STC89xx系列单片机ISP/IAP控制寄存器地址不同如下:</td></tr><tr><td>Mnemonic</td><td>Add</td><td>Name</td><td>7</td><td>6</td><td>5</td><td>4</td><td>3</td><td>2</td><td>1</td><td>0</td><td>Reset Value</td></tr><tr><td>STC15Fxx 系列IAP_DATASTC89xx 系列ISP_DATA</td><td>C2hE2h</td><td>ISP/IAP FlashData Register</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>1111,1111</td></tr><tr><td>STC15Fxx 系列IAP_ADDRHSTC89xx 系列ISP_ADDRH</td><td>C3hE3h</td><td>ISP/IAP FlashAddress High</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0000,0000</td></tr><tr><td>STC15Fxx 系列IAP_ADDRLSTC89xx 系列ISP_ADDRL</td><td>C4hE4h</td><td>ISP/IAP FlashAddress Low</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0000,0000</td></tr><tr><td>STC15Fxx 系列IAP_CMDSTC89xx 系列ISP_CMD</td><td>C5hE5h</td><td>ISP/IAP FlashCommandRegister</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td><td>MS1</td><td>MS0</td><td>xxxx,xx00</td></tr><tr><td>STC15Fxx 系列IAP_TRIGSTC89xx 系列ISP_TRIG</td><td>C6hE6h</td><td>ISP/IAP FlashCommandTrigger</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>xxxx,xxxx</td></tr><tr><td>STC15Fxx系列IAP_CONTRSTC89xx 系列ISP_CONTR</td><td>C7hE7h</td><td>ISP/IAPControlRegister</td><td>IAPEN</td><td>SWBS</td><td>SWRST</td><td>CMD_FAIL</td><td>-</td><td>WT2</td><td>WT1</td><td>WT0</td><td>0000,x000</td></tr></table>

ISP/IAP_TRIG寄存器有效启动IAP操作,需顺序送入的数据不一样:

STC15系列单片机的ISP/�IAP命令��要生效,要对IAP_�TRIG寄存器按顺序先送5Ah,再送A5h方可

STC89xx 系列单片机的ISP/IAP命令 要生效,要对IAP_TRIG寄存器按顺序先送46h,再送B9h方可

EEPROM起始地址不一样:

STC15系列单片机 �

STC89xx系列单片机的EEPROM起始地址分别有从1000h/2000h/4000h/8000h开始的,程序兼容性不够好.

# 外部中断

最新STC15系列单片机有5个外部中断。其中外部中断0(INTO)和外部中断1(INT1)可配置为2种中断触发方式：

第一种方式，仅下降沿触发中断，与传统8051的外部中断0和1的下降沿中断兼容。

第二种方式，上升沿中断和下降沿中断同时支持。

另外相对传统STC89系列单片机,最新的STC15 �部中断4，这三个新增的外部中断都只能下降沿触发中断。

而传统STC89系列单片机的外部中断0和外部中断1只可以配置为下降沿中断或低电平中断。

# 定时器

最新STC15 � �计数器1与传统STC89系列单片机/计数器0和定时器/计数器1的最大不同在于定时器的工作模式0。最新STC15器/计数器0和定时器/计数器1的工作模式0是16位自动重装载模式，而传统STC89系列单片机定时器/计数器0和定时器/计数器1的模式0是13位定时/计数器模式。最新STC15定时器/计数器0和定时器/计数器1仍保留着其他3种工作模式，这3中工作模式与传统的系列单片机的定时器�/计数器0和定时器�/计数器1的工作模式兼容。�另外传统的机还设有定时器2，而最新STC15

# 外部时钟和内部时钟:

最新STC15系列单片机内部�集成了��高精 度 �C振荡器作为系统时钟时钟。而传统STC89系列单片机只能使用外部晶体或时钟作为系统时钟.

# 功耗:

功耗由2部分组成,晶体振荡器放大电路的功耗和单片机的数字电路功耗组成,

晶体振荡器放大电路的功耗: 最新STC15系列单片机比STC89xx系列低.

单片机的数字电路功耗:时钟频率越高,功耗越大,最新STC15系列单片机在相同工作频率下,指令执行速度比传统STC89系列单片机快3-24倍,故可用较低的时钟频率工作,这样功耗更低. �STC15系列单片机可以利用内部的时钟分频器对时钟进行分频,以较低的频率工作, 得�的功耗更低

# 掉电唤醒:

最新STC15系列单片机支持外部中断上升沿或下降沿均可唤醒，也可仅下降沿唤醒。系列单片机是只支持外部中断低电平唤醒 �外最新STC15定时器

# 附录H：STC15系列对指令系统的提升

与普通8051指令代码完全兼容，但执行的时间效率大幅提升

其中INC DPTR和MUL AB指令的执行速度大幅提升24倍

-共有12条指令，一个时钟就可以执行完成，平均速度快8~12倍

如果按功能分类，STC15系列单片机指令系统可分为：

1.算术操作类指令；

2.逻辑操作类指令；

3.数据传送类指令；

4.布尔变量操作类指令；

5.控制转移类指令。

按功能分类的指令系统表如下表所示。

指令执行速度效率提升总结(新15系列)

指令系统共包括111条指令，其中：

执行速度快24倍的 共2条

执行速度快12倍的 共28条

执行速度快8倍的 共19条

执行速度快6倍的 共40条

执行速度快4.8倍的 共8条

执行速度快4倍的 共14条

根据对指令的使用频率分析统计，STC15系列 1T 的8051单片机比普通的8051单片机在同样的工作频率下运行速度提升了8～12倍。

指令执行时钟数统计（供参考）(新15系列)

指令系统共包括111条指令，其中：

1个时钟就可执行完成的指令 共22条

2个时钟就可执行完成的指令 共37条

3个时钟就可执行完成的指令 共31条

4个时钟就可执行完成的指令 共12条

5个时钟就可执行完成的指令 共8条

6个时钟就可执行完成的指令 共1条

111条指令全部执行完一遍所需的时钟为283个时钟。

现STC15系列单片机采用STC-Y5超高速 CPU内核，在相同的时钟频率下，速度又比STC早期的1T系列单片机(如STC12系列/STC11系列/STC10系列)的速度快 $2 0 \%$ .


算术操作类指令


<table><tr><td>助记符</td><td>功能说明</td><td>字节数</td><td>传统8051单片机所需时钟</td><td>STC15系列单片机所需时钟(采用STC-Y5超高速1T 8051内核)</td><td>效率提升</td></tr><tr><td>ADD A, Rn</td><td>寄存器内容加到累加器</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>ADD A, direct</td><td>直接地址单元中的数据加到累加器</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>ADD A, @Ri</td><td>间接RAM中的数据加到累加器</td><td>1</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>ADD A, #data</td><td>立即数加到累加器</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>ADDC A, Rn</td><td>寄存器带进位加到累加器</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>ADDC A, direct</td><td>直接地址单元的内容带进位加到累加器</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>ADDC A, @Ri</td><td>间接RAM内容带进位加到累加器</td><td>1</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>ADDC A, #data</td><td>立即数带进位加到累加器</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>SUBB A, Rn</td><td>累加器带借位减寄存器内容</td><td>1</td><td>12</td><td>1</td><td>6倍</td></tr><tr><td>SUBB A, direct</td><td>累加器带借位减直接地址单元的内容</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>SUBB A, @Ri</td><td>累加器带借位减间接RAM中的内容</td><td>1</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>SUBB A, #data</td><td>累加器带借位减立即数</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>INC A</td><td>累加器加1</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>INC Rn</td><td>寄存器加1</td><td>1</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>INC direct</td><td>直接地址单元加1</td><td>2</td><td>12</td><td>3</td><td>4倍</td></tr><tr><td>INC @Ri</td><td>间接RAM单元加1</td><td>1</td><td>12</td><td>3</td><td>4倍</td></tr><tr><td>DEC A</td><td>累加器减1</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>DEC Rn</td><td>寄存器减1</td><td>1</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>DEC direct</td><td>直接地址单元减1</td><td>2</td><td>12</td><td>3</td><td>4倍</td></tr><tr><td>DEC @Ri</td><td>间接RAM单元减1</td><td>1</td><td>12</td><td>3</td><td>4倍</td></tr><tr><td>INC DPTR</td><td>地址寄存器DPTR加1</td><td>1</td><td>24</td><td>1</td><td>24倍</td></tr><tr><td>MUL AB</td><td>A乘以B</td><td>1</td><td>48</td><td>2</td><td>24倍</td></tr><tr><td>DIV AB</td><td>A除以B</td><td>1</td><td>48</td><td>6</td><td>8倍</td></tr><tr><td>DA A</td><td>累加器十进制调整</td><td>1</td><td>12</td><td>3</td><td>4倍</td></tr></table>


逻辑操作类指令


<table><tr><td>助记符</td><td>功能说明</td><td>字节数</td><td>传统8051单片机所需时钟</td><td>STC15系列单片机所需时钟(采用STC-Y5超高速1T8051内核)</td><td>效率提升</td></tr><tr><td>ANL A, Rn</td><td>累加器与寄存器相“与”</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>ANL A, direct</td><td>累加器与直接地址单元相“与”</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>ANL A, @Ri</td><td>累加器与间接RAM单元相“与”</td><td>1</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>ANL A, #data</td><td>累加器与立即数相“与”</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>ANL direct, A</td><td>直接地址单元与累加器相“与”</td><td>2</td><td>12</td><td>3</td><td>4倍</td></tr><tr><td>ANL direct, #data</td><td>直接地址单元与立即数相“与”</td><td>3</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>ORL A, Rn</td><td>累加器与寄存器相“或”</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>ORL A, direct</td><td>累加器与直接地址单元相“或”</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>ORL A, @Ri</td><td>累加器与间接RAM单元相“或”</td><td>1</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>ORL A, # data</td><td>累加器与立即数相“或”</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>ORL direct, A</td><td>直接地址单元与累加器相“或”</td><td>2</td><td>12</td><td>3</td><td>4倍</td></tr><tr><td>ORL direct, #data</td><td>直接地址单元与立即数相“或”</td><td>3</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>XRL A, Rn</td><td>累加器与寄存器相“异或”</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>XRL A, direct</td><td>累加器与直接地址单元相“异或”</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>XRL A, @Ri</td><td>累加器与间接RAM单元相“异或”</td><td>1</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>XRL A, # data</td><td>累加器与立即数相“异或”</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>XRL direct, A</td><td>直接地址单元与累加器相“异或”</td><td>2</td><td>12</td><td>3</td><td>4倍</td></tr><tr><td>XRL direct, #data</td><td>直接地址单元与立即数相“异或”</td><td>3</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>CLR A</td><td>累加器清“0”</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>CPL A</td><td>累加器求反</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>RL A</td><td>累加器循环左移</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>RLC A</td><td>累加器带进位位循环左移</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>RR A</td><td>累加器循环右移</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>RRC A</td><td>累加器带进位位循环右移</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>SWAP A</td><td>累加器内高低半字节交换</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr></table>


数据传送类指令


<table><tr><td colspan="2">助记符</td><td>功能说明</td><td>字节数</td><td>传统8051单片机所需时钟</td><td>STC15系列单片机所需时钟(采用STC-Y5超高速1T 8051内核)</td><td>效率提升</td></tr><tr><td>MOV</td><td>A,Rn</td><td>寄存器内容送入累加器</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>MOV</td><td>A,direct</td><td>直接地址单元中的数据送入累加器</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>MOV</td><td>A,@Ri</td><td>间接RAM中的数据送入累加器</td><td>1</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>MOV</td><td>A,#data</td><td>立即数送入累加器</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>MOV</td><td>Rn,A</td><td>累加器内容送入寄存器</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>MOV</td><td>Rn,direct</td><td>直接地址单元中的数据送入寄存器</td><td>2</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>MOV</td><td>Rn,#data</td><td>立即数送入寄存器</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>MOV</td><td>direct,A</td><td>累加器内容送入直接地址单元</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>MOV</td><td>direct,Rn</td><td>寄存器内容送入直接地址单元</td><td>2</td><td>24</td><td>2</td><td>12倍</td></tr><tr><td>MOV</td><td>direct,direct</td><td>直接地址单元中的数据送入另一个直接地址单元</td><td>3</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>MOV</td><td>direct,@Ri</td><td>间接RAM中的数据送入直接地址单元</td><td>2</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>MOV</td><td>direct,#data</td><td>立即数送入直接地址单元</td><td>3</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>MOV</td><td>@Ri,A</td><td>累加器内容送间接RAM单元</td><td>1</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>MOV</td><td>@Ri,direct</td><td>直接地址单元数据送入间接RAM单元</td><td>2</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>MOV</td><td>@Ri,#data</td><td>立即数送入间接RAM单元</td><td>2</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>MOV</td><td>DPTR,#data16</td><td>16位立即数送入数据指针</td><td>3</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>MOVC</td><td>A,@A+DPTR</td><td>以DPTR为基地址变址寻址单元中的数据送入累加器</td><td>1</td><td>24</td><td>5</td><td>4.8倍</td></tr><tr><td>MOVC</td><td>A,@A+PC</td><td>以PC为基地址变址寻址单元中的数据送入累加器</td><td>1</td><td>24</td><td>4</td><td>6倍</td></tr><tr><td>MOVX</td><td>A,@Ri</td><td>将逻辑上在片外、物理上在片内的扩展RAM(8位地址)的内容送入累加器A中,读操作</td><td>1</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>MOVX</td><td>@Ri,A</td><td>将累加器A的内容送入逻辑上在片外、物理上在片内的扩展RAM(8位地址)中,写操作</td><td>1</td><td>24</td><td>4</td><td>8倍</td></tr><tr><td>MOVX</td><td>A,@DPTR</td><td>将逻辑上在片外、物理上在片内的扩展RAM(16位地址)的内容送入累加器A中,读操作</td><td>1</td><td>24</td><td>2</td><td>12倍</td></tr><tr><td>MOVX</td><td>@DPTR,A</td><td>将累加器A的内容送入逻辑上在片外、物理上在片内的扩展RAM(16位地址)中,写操作</td><td>1</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>MOVX</td><td>A,@Ri</td><td>将逻辑上在片外、物理上也在片外的扩展RAM(8位地址)的内容送入累加器A中,读操作</td><td>1</td><td>24</td><td>5×N+2N的取值见下列说明</td><td>*Note1</td></tr><tr><td>MOVX</td><td>@Ri,A</td><td>将累加器A的内容送入逻辑上在片外、物理上也在片外的扩展RAM(8位地址)中,写操作</td><td>1</td><td>24</td><td>5×N+3N的取值见下列说明</td><td>*Note1</td></tr><tr><td>MOVX</td><td>A,@DPTR</td><td>将逻辑上在片外、物理上也在片外的扩展RAM(16位地址)的内容送入累加器A中,读操作</td><td>1</td><td>24</td><td>5×N+1N的取值见下列说明</td><td>*Note1</td></tr><tr><td>MOVX</td><td>@DPTR,A</td><td>将累加器A的内容送入逻辑上在片外、物理上也在片外的扩展RAM(16位地址)中,写操作</td><td>1</td><td>24</td><td>5×N+2N的取值见下列说明</td><td>*Note1</td></tr><tr><td>PUSH</td><td>direct</td><td>直接地址单元中的数据压入堆栈</td><td>2</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>POP</td><td>direct</td><td>栈底数据弹出送入直接地址单元</td><td>2</td><td>24</td><td>2</td><td>12倍</td></tr><tr><td>XCH</td><td>A,Rn</td><td>寄存器与累加器交换</td><td>1</td><td>12</td><td>2</td><td>6倍</td></tr><tr><td>XCH</td><td>A,direct</td><td>直接地址单元与累加器交换</td><td>2</td><td>12</td><td>3</td><td>4倍</td></tr><tr><td>XCH</td><td>A,@Ri</td><td>间接RAM与累加器交换</td><td>1</td><td>12</td><td>3</td><td>4倍</td></tr><tr><td>XCHD</td><td>A,@Ri</td><td>间接RAM的低半字节与累加器交换</td><td>1</td><td>12</td><td>3</td><td>4倍</td></tr></table>


当EXRTS[1:0] = [0,0]时，表中 $\mathrm { N } { = } 1$ ；



当EXRTS[1:0] = [0,1]时，表中 $\mathrm { N } { = } 2$ ；



当EXRTS[1:0] = [1,0]时，表中 $\mathrm { N } { = } 4$ ；



当EXRTS[1:0] = [1,1]时，表中 $\mathrm { N } { = } 8$ .


EXRTS[1：0]为寄存器BUS_SPEED中的B1,B0位


布尔变量操作类指令


<table><tr><td colspan="2">助记符</td><td>功能说明</td><td>字节数</td><td>传统8051单片机所需时钟</td><td>STC15系列单片机所需时钟(采用STC-Y5超高速1T 8051内核)</td><td>效率提升</td></tr><tr><td>CLR</td><td>C</td><td>清零进位位</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>CLR</td><td>bit</td><td>清0直接地址位</td><td>2</td><td>12</td><td>3</td><td>4倍</td></tr><tr><td>SETB</td><td>C</td><td>置1进位位</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>SETB</td><td>bit</td><td>置1直接地址位</td><td>2</td><td>12</td><td>3</td><td>4倍</td></tr><tr><td>CPL</td><td>C</td><td>进位位求反</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr><tr><td>CPL</td><td>bit</td><td>直接地址位求反</td><td>2</td><td>12</td><td>3</td><td>4倍</td></tr><tr><td>ANL</td><td>C, bit</td><td>进位位和直接地址位相“与”</td><td>2</td><td>24</td><td>2</td><td>12倍</td></tr><tr><td>ANL</td><td>C, /bit</td><td>进位位和直接地址位的反码相“与”</td><td>2</td><td>24</td><td>2</td><td>12倍</td></tr><tr><td>ORL</td><td>C, bit</td><td>进位位和直接地址位相“或”</td><td>2</td><td>24</td><td>2</td><td>12倍</td></tr><tr><td>ORL</td><td>C, /bit</td><td>进位位和直接地址位的反码相“或”</td><td>2</td><td>24</td><td>2</td><td>12倍</td></tr><tr><td>MOV</td><td>C, bit</td><td>直接地址位送入进位位</td><td>2</td><td>12</td><td>2</td><td>12倍</td></tr><tr><td>MOV</td><td>bit, C</td><td>进位位送入直接地址位</td><td>2</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>JC</td><td>rel</td><td>进位位为1则转移</td><td>2</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>JNC</td><td>rel</td><td>进位位为0则转移</td><td>2</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>JB</td><td>bit, rel</td><td>直接地址位为1则转移</td><td>3</td><td>24</td><td>5</td><td>4.8倍</td></tr><tr><td>JNB</td><td>bit, rel</td><td>直接地址位为0则转移</td><td>3</td><td>24</td><td>5</td><td>4.8倍</td></tr><tr><td>JBC</td><td>bit, rel</td><td>直接地址位为1则转移,该位清0</td><td>3</td><td>24</td><td>5</td><td>4.8倍</td></tr></table>


控制转移类指令


<table><tr><td>助记符</td><td>功能说明</td><td>字节数</td><td>传统8051单片机所需时钟</td><td>STC15系列单片机所需时钟(采用STC-Y5超高速1T 8051内核)</td><td>效率提升</td></tr><tr><td>ACALL addr11</td><td>绝对(短)调用子程序</td><td>2</td><td>24</td><td>4</td><td>6倍</td></tr><tr><td>LCALL addr16</td><td>长调用子程序</td><td>3</td><td>24</td><td>4</td><td>6倍</td></tr><tr><td>RET</td><td>子程序返回</td><td>1</td><td>24</td><td>4</td><td>6倍</td></tr><tr><td>RETI</td><td>中断返回</td><td>1</td><td>24</td><td>4</td><td>6倍</td></tr><tr><td>AJMP addr11</td><td>绝对(短)转移</td><td>2</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>LJMP addr16</td><td>长转移</td><td>3</td><td>24</td><td>4</td><td>6倍</td></tr><tr><td>SJMP rel</td><td>相对转移</td><td>2</td><td>24</td><td>3</td><td>8倍</td></tr><tr><td>JMP @A+DPTR</td><td>相对于DPTR的间接转移</td><td>1</td><td>24</td><td>5</td><td>4.8倍</td></tr><tr><td>JZ rel</td><td>累加器为零转移</td><td>2</td><td>24</td><td>4</td><td>6倍</td></tr><tr><td>JNZ rel</td><td>累加器非零转移</td><td>2</td><td>24</td><td>4</td><td>6倍</td></tr><tr><td>CJNE A, direct, rel</td><td>累加器与直接地址单元比较,不相等则转移</td><td>3</td><td>24</td><td>5</td><td>4.8倍</td></tr><tr><td>CJNE A, #data, rel</td><td>累加器与立即数比较,不相等则转移</td><td>3</td><td>24</td><td>4</td><td>6倍</td></tr><tr><td>CJNE Rn, #data, rel</td><td>寄存器与立即数比较,不相等则转移</td><td>3</td><td>24</td><td>4</td><td>6倍</td></tr><tr><td>CJNE @Ri, #data, rel</td><td>间接RAM单元与立即数比较,不相等则转移</td><td>3</td><td>24</td><td>5</td><td>4.8倍</td></tr><tr><td>DJNZ Rn, rel</td><td>寄存器减1,非零转移</td><td>2</td><td>24</td><td>4</td><td>6倍</td></tr><tr><td>DJNZ direct, rel</td><td>直接地址单元减1,非零转移</td><td>3</td><td>24</td><td>5</td><td>4.8倍</td></tr><tr><td>NOP</td><td>空操作</td><td>1</td><td>12</td><td>1</td><td>12倍</td></tr></table>

本次指令系统总结更新于2011-10-17日止

# 附录I：如何利用Keil C软件减少代码长度

在Keil C软件中选择����� 作如下设置 ，�������� ��������能将原代码长度最 大��减少 1��0K。

1.在“Project”菜单中选择“Options for Target”

2.在“Options for Target”中选择“C51”

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/73e51ea537e8081d5978c251801f4934cf0d6910e4a73e53726543449866011d.jpg)


3.选择按空间大小，9级优化程序

4.��点击 “确定��”后�，����重新编译 ��

# 附录J：使用STC的IAP系列单片机开发自己的ISP程序

# 基于IAP15F2K61S2单片机

随着IAP（In-Application-Programming）技术在单片机领域的不断发展，给应用系统程序代码升级带来了极大的方便。STC的串口ISP（In-System-Programming）程序就是使用IAP功能来对用户的程序进行在线升级的，但是出于对用户代码的安全着想，底层代码和上层应用程序都没有开源，为此STC推出了IAP系列单片机，即整颗MCU的Flash空间，用户均可在自己的程序中进行改写，从而使得有用户需要开发字节的ISP程序的想法得以实现。本文以STC的IAP15F2K61S2为例，详细说明了使用STC的IAP单片机开发用户自己的ISP程序的方法，并给出了基于Keil环境的汇编和C源码。

# 一．内部FLASH规划

示例单片机使用IAP15F2K61S2，用户可以使用的最大程序空间为60K字节，整个Flash空间划分如下：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/ccf93b6b25a7074e6aa3dd22fdd24cdc787f1cf26325ab12e6163b327f0343ce.jpg)


FLASH空间中，从地址0000H开始的连续60K字节的空间为用户程序区。当满足特定的下载条件时，用户需要自行将程序跳转到用户ISP程序区，此时可对用户程序区进行擦除和改写，以达到更新用户程序的目的。

# 二．程序的基本框架

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7909a7933dd7ad6920f5933c24942fe16198ff703e3236f33a8de8e2c580a6bb.jpg)


# 三．下位机固件程序说明

下位机固件程序包括两部分：ISP（ISP代码）和AP（用户代码）

ISP代码（汇编语言）如下：

; --- STC MCU International Limited 

; --- STC IAP 系列单片机实现用户ISP 演示程序

; --- Mobile: (86)13922805190 

; --- Fax: 86-755-82944243 

; --- Tel: 86-755-82948412 

; --- Web: www.STCMCU.com 

; 如果要在程序中使用或者在文章中引用该程序,请在程序中或文章中注明

; 使用了宏晶科技的资料或程序

;定义常数

UARTBAUD 

EQU 

0FFE8H 

;定义串口波特率发生器的重载值

;(65536-11059200/4/115200) 

;ENABLE_IAP 

EQU 

80H 

;系统工作频率<30MHz

;ENABLE_IAP 

EQU 

81H 

;系统工作频率<24MHz

<table><tr><td colspan="4">STC15F2K60S2系列单片机指南 官方网站:www.STCMCU.com 研发顾问QQ:800003751 STC-全球最大的8051单片机设计公司</td></tr><tr><td>;ENABLE_IAP</td><td>EQU</td><td>82H</td><td>;系统工作频率&lt;20MHz</td></tr><tr><td>ENABLE_IAP</td><td>EQU</td><td>83H</td><td>;系统工作频率&lt;12MHz</td></tr><tr><td>;ENABLE_IAP</td><td>EQU</td><td>84H</td><td>;系统工作频率&lt;6MHz</td></tr><tr><td>;ENABLE_IAP</td><td>EQU</td><td>85H</td><td>;系统工作频率&lt;3MHz</td></tr><tr><td>;ENABLE_IAP</td><td>EQU</td><td>86H</td><td>;系统工作频率&lt;2MHz</td></tr><tr><td>;ENABLE_IAP</td><td>EQU</td><td>87H</td><td>;系统工作频率&lt;1MHz</td></tr><tr><td colspan="4">;定义特殊功能寄存器</td></tr><tr><td>AUXR</td><td>DATA</td><td>08EH</td><td>;附件功能控制寄存器</td></tr><tr><td>WDT_CONTR</td><td>DATA</td><td>0C1H</td><td>;看门狗控制寄存器</td></tr><tr><td>IAP_DATA</td><td>DATA</td><td>0C2H</td><td>;IAP数据寄存器</td></tr><tr><td>IAP_ADDRH</td><td>DATA</td><td>0C3H</td><td>;IAP高地址寄存器</td></tr><tr><td>IAP_ADDRL</td><td>DATA</td><td>0C4H</td><td>;IAP低地址寄存器</td></tr><tr><td>IAP_CMD</td><td>DATA</td><td>0C5H</td><td>;IAP命令寄存器</td></tr><tr><td>IAP_TRIG</td><td>DATA</td><td>0C6H</td><td>;IAP命令触发寄存器</td></tr><tr><td>IAP_CONTR</td><td>DATA</td><td>0C7H</td><td>;IAP控制寄存器</td></tr><tr><td colspan="4">;定义ISP模块使用的变量</td></tr><tr><td>ISPCODE</td><td>EQU</td><td>0F000H</td><td>;ISP模块入口地址(1页),同时也是下载接口地址</td></tr><tr><td>APENTRY</td><td>EQU</td><td>0F200H</td><td>;应用程序入口地址数据(1页)</td></tr><tr><td colspan="4">;</td></tr><tr><td>ORG</td><td>0000H</td><td></td><td></td></tr><tr><td>LJMP</td><td>ISP_ENTRY</td><td></td><td>;系统复位入口</td></tr><tr><td colspan="4">RESET:</td></tr><tr><td>MOV</td><td>SCON,</td><td>#50H</td><td>;设置串口模式(8位数据位,波特率可变,无校验位)</td></tr><tr><td>MOV</td><td>AUXR,</td><td>#40H</td><td>;T1工作于1T模式</td></tr><tr><td>MOV</td><td>TH1,</td><td>#HIGH UARTBAUD</td><td>;波特率设置</td></tr><tr><td>MOV</td><td>TL1,</td><td>#LOW UARTBAUD</td><td>;</td></tr><tr><td>SETB</td><td>TR1</td><td></td><td>;启动定时器1</td></tr><tr><td colspan="4">NEXT1:</td></tr><tr><td>MOV</td><td>R0,</td><td>#16</td><td></td></tr><tr><td colspan="4">NEXT2:</td></tr><tr><td>JNB</td><td>RI,</td><td>$</td><td>;等待串口数据</td></tr><tr><td>CLR</td><td>RI</td><td></td><td></td></tr><tr><td>MOV</td><td>A,</td><td>SBUF</td><td></td></tr><tr><td>CJNE</td><td>A,</td><td>#7FH,NEXT1</td><td>;判断是否为7F</td></tr></table>

DJNZ R0, NEXT2 

LJMP ISPPROGRAM 

;跳转到下载界面

;ISP功能模块

;包括上电自检模块和代码更新模块

ORG ISPCODE 

# ISPPROGRAM:

CLR A 

MOV PSW, A ;ISP模块使用第0组寄存器

MOV IE, A ;关闭所有中断

CLR RI ;清除串口接收标志

SETB TI ;置串口发送标志

CLR TR0 

MOV SP, #5FH ;设置堆栈指针

MOV A, #5AH 

CALL ISP_SENDUART 

MOV A, #055H 

CALL ISP_SENDUART 

CALL ISP_RECVACK ;接收应答数据

MOV IAP_ADDRL, #0 ;首先在第2页起始地址写 "LJMP ISP_ENTRY"指令

MOV IAP_ADDRH, #02H 

CALL ISP_ERASEIAP 

MOV A, #02H 

CALL ISP_PROGRAMIAP ;编程用户代码复位向量代码

MOV A, #HIGH ISP_ENTRY 

CALL ISP_PROGRAMIAP ;编程用户代码复位向量代码

MOV A, #LOW ISP_ENTRY 

CALL ISP_PROGRAMIAP ;编程用户代码复位向量代码

MOV IAP_ADDRL, #0 ;用户代码地址从0开始

MOV IAP_ADDRH, #0 

CALL ISP_ERASEIAP 

MOV A, #02H 

CALL ISP_PROGRAMIAP ;编程用户代码复位向量代码

MOV A, #HIGH ISP_ENTRY 

CALL ISP_PROGRAMIAP ;编程用户代码复位向量代码

<table><tr><td>MOV</td><td>A,</td><td>#LOW ISP_ENTRY</td><td></td></tr><tr><td>CALL</td><td>ISP_PROGRAMIAP</td><td></td><td>;编程用户代码复位向量代码</td></tr><tr><td>MOV</td><td>IAP_ADDRL,</td><td>#0</td><td>;新代码缓冲区地址</td></tr><tr><td>MOV</td><td>IAP_ADDRH,</td><td>#02H</td><td></td></tr><tr><td>MOV</td><td>R7,</td><td>#119</td><td>;擦除60K-512字节</td></tr><tr><td>ISP_ERASEAP:</td><td></td><td></td><td></td></tr><tr><td>CALL</td><td>ISP_ERASEIAP</td><td></td><td></td></tr><tr><td>INC</td><td>IAP_ADDRH</td><td></td><td>;目标地址+512</td></tr><tr><td>INC</td><td>IAP_ADDRH</td><td></td><td></td></tr><tr><td>DJNZ</td><td>R7,</td><td>ISP_ERASEAP</td><td>;判断是否擦除完成</td></tr><tr><td>MOV</td><td>IAP_ADDRL,</td><td>#LOW APENTRY</td><td>;用户代码复位入口页</td></tr><tr><td>MOV</td><td>IAP_ADDRH,</td><td>#HIGH APENTRY</td><td></td></tr><tr><td>CALL</td><td>ISP_ERASEIAP</td><td></td><td></td></tr><tr><td>MOV</td><td>A,</td><td>#5AH</td><td>;返回5AA5到PC,表示ISP编程模块已准备就绪</td></tr><tr><td>CALL</td><td>ISP_SENDUART</td><td></td><td></td></tr><tr><td>MOV</td><td>A,</td><td>#0A5H</td><td></td></tr><tr><td>CALL</td><td>ISP_SENDUART</td><td></td><td></td></tr><tr><td>CALL</td><td>ISP_RECVACK</td><td></td><td>;接收应答数据</td></tr><tr><td>CALL</td><td>ISP_RECVUART</td><td></td><td>;接收长度高字节</td></tr><tr><td>MOV</td><td>R0,</td><td>A</td><td></td></tr><tr><td>CALL</td><td>ISP_RECVUART</td><td></td><td>;接收长度低字节</td></tr><tr><td>MOV</td><td>R1,</td><td>A</td><td></td></tr><tr><td>CLR</td><td>C</td><td></td><td>;将(总长度-3)的补码存入DPTR</td></tr><tr><td>MOV</td><td>A,</td><td>#03H</td><td></td></tr><tr><td>SUBB</td><td>A,</td><td>R1</td><td></td></tr><tr><td>MOV</td><td>DPL,</td><td>A</td><td></td></tr><tr><td>CLR</td><td>A</td><td></td><td></td></tr><tr><td>SUBB</td><td>A,</td><td>R0</td><td></td></tr><tr><td>MOV</td><td>DPH,</td><td>A</td><td></td></tr><tr><td>CALL</td><td>ISP_RECVUART</td><td></td><td>;映射用户代码复位入口代码到映射区</td></tr><tr><td>CALL</td><td>ISP_PROGRAMIAP</td><td></td><td>;0000</td></tr><tr><td>CALL</td><td>ISP_RECVUART</td><td></td><td></td></tr><tr><td>CALL</td><td>ISP_PROGRAMIAP</td><td></td><td>;0001</td></tr><tr><td>CALL</td><td>ISP_RECVUART</td><td></td><td></td></tr><tr><td>CALL</td><td>ISP_PROGRAMIAP</td><td></td><td>;0002</td></tr><tr><td>MOV</td><td>IAP_ADDRL,</td><td>#03H</td><td>;用户代码起始地址</td></tr><tr><td>MOV</td><td>IAP_ADDRH,</td><td>#00H</td><td></td></tr></table>

CALL ISP_RECVUART 

;接收代码数据

CALL ISP_PROGRAMIAP 

;编程到用户代码区

INC DPTR 

MOV A, DPL 

ORL A, DPH 

JNZ ISP_PROGRAMNEXT 

;长度检测

ISP_SOFTRESET: 

MOV IAP_CONTR, #20H 

;软件复位系统

SJMP $ 

;用户ISP主程序的入口地址

ISP_ENTRY: 

MOV IAP_ADDRL, #00H 

;电压测试模块

MOV IAP_ADDRH, #0F0H 

;测试地址F000H

MOV IAP_DATA, #53H 

;测试数据1

CALL ISP_READIAP 

XRL A, #53H 

;测试是否可以读出数据

JZ ISP_ENTRY 

;若读不出数据,则需等待电压稳定

INC IAP_ADDRL 

;测试地址F001H

MOV IAP_DATA, #45H 

;测试数据2

CALL ISP_READIAP 

XRL A, #45H 

;测试是否可以读出数据

JZ ISP_ENTRY 

;若读不出数据,则需等待电压稳定

JMP GOTOAP 

;电压稳定后开始运行用户代码

MOV TMOD, #00H 

MOV SCON, #5AH 

;设置串口模式(8位数据位,波特率可变,无校验位)

MOV AUXR, #40H 

;T1工作于1T模式

MOV TH1, #HIGH UARTBAUD 

;波特率设置

MOV TL1, #LOW UARTBAUD 

SETB TR1 

;启动定时器1

MOV R0, #16 

ISP_CHECKNEXT: 

CALL ISP_RECVUART 

;接收同步数据

JC GOTOAP 

CJNE A, #7FH,GOTOAP 

;判断是否为7F

DJNZ R0, ISP_CHECKNEXT 

MOV A, #5AH 

;返回5A 69到PC,表示ISP模块已准备就绪

CALL ISP_SENDUART 

MOV A, #69H 

CALL ISP_SENDUART 

CALL ISP_RECVACK 

;接收应答数据

LJMP ISPPROGRAM 

;跳转到下载界面

;跳转到用户程序区,开始正常运行用户程序

# GOTOAP:

CLR A 

;将SFR恢复为复位值

MOV TCON, A 

MOV TMOD, A 

MOV TL0, A 

MOV TH0, A 

MOV TL1, A 

MOV TH1, A 

MOV SCON, A 

MOV AUXR, A 

LJMP APENTRY 

;正常运行用户程序

;接收来自于上位机的串口应答数据

# ISP_RECVACK:

CALL ISP_RECVUART 

JC GOTOAP 

XRL A, #7FH 

JZ ISP_RECVACK 

;跳过同步数据 (7FH)

CJNE A, #25H, GOTOAP 

;应答数据1检测(5AH)

CALL ISP_RECVUART 

JC GOTOAP 

XRL A, #69H 

;应答数据2检测(69H)

JNZ GOTOAP 

RET 

;接收1字节串口数据

;出口参数: ACC (接收到的数据)

;出口参数: C (1:超时)

# ISP_RECVUART:

CLR TR0 

CLR A 

MOV TL0, A 

;初始化超时定时器

MOV TH0, A 

CLR TF0 

SETB TR0 

MOV WDT_CONTR, #17H 

;清看门狗

ISP_RECVWAIT: 

JBC TF0, ISP_RECVTIMEOUT 

JNB RI, ISP_RECVWAIT 

MOV A, SBUF 

CLR RI 

CLR C 

RET 

;超时检测

;等待接收完成

;读取串口数据

;清除标志

;正确接收串口数据

ISP_RECVTIMEOUT: 

SETB C 

RET 

;超时退出

;发送1字节串口数据

;入口参数: ACC (待发送的数据)

ISP_SENDUART: 

MOV WDT_CONTR, #17H 

JNB TI, ISP_SENDUART 

CLR TI 

MOV SBUF, A 

RET 

;清看门狗

;等待前一个数据发送完成

;清除标志

;发送当前数据

;擦除IAP扇区

ISP_ERASEIAP: 

MOV WDT_CONTR, #17H 

MOV IAP_CONTR, #ENABLE_IAP 

MOV IAP_CMD, #3 

MOV IAP_TRIG, #5AH 

MOV IAP_TRIG, #0A5H 

RET 

;清看门狗

;使能IAP功能

;擦除命令

;触发ISP命令

;编程IAP字节

;入口参数: ACC (待编程的数据)

ISP_PROGRAMIAP: 

MOV WDT_CONTR, #17H 

MOV IAP_CONTR, #ENABLE_IAP 

MOV IAP_CMD, #2 

;清看门狗

;使能IAP功能

;编程命令

MOV IAP_DATA, A ;将当前数据送IAP数据寄存器

MOV IAP_TRIG, #5AH ;触发ISP命令

MOV IAP_TRIG, #0A5H 

MOV A, IAP_ADDRL ;IAP地址+1

ADD A, #01H 

MOV IAP_ADDRL, A 

MOV A, IAP_ADDRH 

ADDC A, #00H 

MOV IAP_ADDRH, A 

RET 

;读取IAP字节

;出口参数: ACC (读出的数据)

ISP_READIAP: 

MOV IAP_CONTR, #ENABLE_IAP ;使能IAP功能

MOV IAP_CMD, #1 ;读命令

MOV IAP_TRIG, #5AH ;触发ISP命令

MOV IAP_TRIG, #0A5H 

MOV A, IAP_DATA 

RET 

ORG APENTRY 

LJMP RESET 

END 

ISP代码包括如下外部接口模块：

ISPPROGRAM：程序下载入口地址，绝对地址F000H

ISP_ENTRY：上电系统自检程序（系统自动调用）

对于用户程序而言，用户只需要在满足下载条件时，将PC值跳转到ISPPROGRAM （即F000H的绝对地址），即可实现代码更新。

# 用户代码（C语言及汇编语言）示例如下：

# 1、C语言用户代码

/*- -*/ 

/* --- STC MCU International Limited - -*/ 

/* --- STC IAP 系列单片机实现用户ISP 演示程序 -*/

/* --- Mobile: (86)13922805190 - -*/ 

/* --- Fax: 86-755-82944243 - -*/ 

/* --- Tel: 86-755-82948412 -*/ 

/* --- Web: www.STCMCU.com - -*/ 

/* 如果要在程序中使用或者在文章中引用该程序,请在程序中或文章中注明 */

/* 使用了宏晶科技的资料或程序 */

/*- -*/ 

```txt
include"reg51.h" 
```

/* 定义常数 */

#define FOSC 11059200L //系统时钟频率

#define BAUD 115200 //定义串口波特率

#define RELOAD (65536 - FOSC/4/BAUD) //定时器重载值

#define ISPPROGRAM() ((void (code *)())0xF000)() //ISP下载程序入口地址

/* 定义相关SFR */

sfr AUXR 0x8E; //辅助寄存器

void uart() interrupt 4 using 1 //串口中断服务程序

{static char cnt7f ${ } = 0$ ; //7f的计数器

i $\mathrm { f \ ( T I ) \ T I = 0 }$ ; 

if (RI)  
{ if $(\mathrm{SBUF} == 0\mathrm{x7f})$ { if $(++\mathrm{cnt7f} >= 16)$ { ISPPPROGRAM(); //调用下载模块(******重要语句****） } } else { cnt7f $= 0$ 

} RI = 0;   
}   
}   
void main()   
{ SCON $=$ 0x50; //设置串口模式(8位数据位，波特率可变，无校验位) AUXR $=$ 0x40; //T1工作于1T模式 TH1 $=$ RELOAD>>8; //波特率设置 TL1 $=$ RELOAD; TR1 $=$ 1; //启动定时器1 ES $=$ 1; //使能串口中断 EA $=$ 1; //打开全局中断开关 while (1) { P1++; //用户示例代码 }

# 2、汇编语言用户代码

;/*-- -*/ 

;/* --- STC MCU International Limited - -*/ 

;/* --- STC IAP 系列单片机实现用户ISP 演示程序 -*/

;/* --- Mobile: (86)13922805190 -*/ 

;/* --- Fax: 86-755-82944243 - -*/ 

;/* --- Tel: 86-755-82948412 - -*/ 

;/* --- Web: www.STCMCU.com - -*/ 

;/* 如果要在程序中使用或者在文章中引用该程序,请在程序中或文章中注明 */

;/* 使用了宏晶科技的资料或程序 - --*/

;/*- */ 

;/*定义常数*/

UARTBAUD EQU 0FFE8H ;定义串口波特率 (65536-11059200/4/115200)

ISPPROGRAM EQU 0F000H ;ISP下载程序入口地址

;/*定义特殊功能寄存器*/

AUXR 

DATA 

08EH 

;附件功能控制寄存器

;/*定义用户变量*/

CNT7F 

DATA 

60H 

;接收7F的计数器,当连续接收到16次7F后进入ISP下载模式

;/*中断向量表*/

ORG 0000H 

LJMP START 

;系统复位入口

ORG 0023H 

LJMP UART_ISR 

;串口中断入口

;/*串口中断服务程序*/

UART_ISR: 

PUSH ACC 

PUSH PSW 

MOV PSW, #08H 

JNB TI, CHECKRI 

;检测发送中断

CLR TI 

;清除标志

CHECKRI: 

JNB RI, 

UARTISR_EXIT 

;检测接收中断

CLR RI 

;清除标志

MOV A, 

CJNE A, 

SBUF 

INC CNT7F 

MOV A, 

CNT7F 

CJNE A, 

#16, 

UARTISR_EXIT 

LJMP ISPPROGRAM 

;调用下载模块(****重要语句****)

ISNOT7F: 

MOV CNT7F, #0 

UARTISR_EXIT: 

POP PSW 

POP ACC 

RETI 

;/*主程序入口*/


START:


```asm
MOV R0, #7FH ;清RAM  
CLR A  
MOV @R0, A  
DJNZ R0, $-1  
MOV SP, #7FH ;初始化SP  
MOV SCON, #50H ;设置串口模式(8位数据位,波特率可变,无校验位)  
MOV AUXR, #40H ;T1工作于1T模式  
MOV TH1, #HIGH UARTBAUD ;波特率设置  
MOV TL1, #LOW UARTBAUD ;  
SETB TR1 ;启动定时器1  
SETB ES ;使能串口中断  
SETB EA ;开中断总开关  
INC P0 ;用户示例代码  
SJMP MAIN
```

对于汇编语言编写的用户代码需要注意一点：位于0000H的复位入口地址处的指令必须是一个长跳转语句（类似LJMP START）。在用户代码中，需要设置好串口，并在满足下载条件时，跳转到ISPPROGRAM （即F000H的绝对地址），以实现代码更新。

对于汇编语言编写的用户代码，我们可以使用如下图的方法进行调用：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e4570b9457c73a488707426b6fc166b288e0392d1da509e744d7e313db771889.jpg)


对于C语言编写的用户代码，我们可以使用如下图的方法进行调用：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/fef81a4b242b239859702aee64701208258457131a3dda723f64f17b2cd163af.jpg)


# 四．上位机应用程序说明

上位机应用程序请用户在STC官方网站www.STCMCU.com下载。

上位机演示程序是基于MFC的对话框项目，对于串口的访问是直接调用Windows的API函数，而没有使用串口控件，从而省去的控件的注册以及系统版本不兼容的诸多问题。界面较简单，只是为这一功能的实现提供了一个框架，其他的功能及要求均还可以往上面添加。

上位机程序的核心模块是基于类CISPDlg的一个友元函数“UINT Download(LPVOIDpParam)；”。

```txt
// Construction   
public: CISPDLg(CWnd* pParent = NULL); // standard constructor   
friend UINT Download(LPVOID pParam); 
```

此函数负责与下位机通讯，发送各种通讯命令来完成对用户程序的更新。用户可以根据各自不同的需求增加命令。

# 五．上位机应用程序的使用方法

# 1、打开上位机界面，如下图

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/90b7674b99705fe43c68282eb8309ff548aa80715a6454ed1a2d3320fe4dc0c3.jpg)


2、选择串口号，设置与下位机相同的串口波特率

3、打开要下载的源数据文件，Bin或者Intel hex格式均可以

4、点击“下载数据”按钮即可开始下载数据

# 六．下位机固件程序的使用方法

下位机的目标文件有两个：“IAPISP.hex”和“AP.hex”，对于一块新的单片机，第一次必须使用宏晶科技的ISP下载工具将“IAPISP.hex”写入到芯片内。附件中的“AP.hex”是用户程序模板，当满足下载条件时（模板代码中的下载条件是连续就收到16个7FH的数据），用户将程序跳转到用户ISP入口地址（F000H）处，即可实现代码更新。

# 附录K：STC15F2K60S2系列学习板电路示意图

# 说明：

IAP15F/15L2K61S2、STC15F/15L2K08S2可以仿真，但STC15F/15L2K08S2更便宜。

SW23是下载断电按钮，下载时按一下再释放就可以冷启动。

供电方式：可以从USB取5V电，也可以外插8~12V电。

布PCB时MCU的电源退耦电容C1和C2要尽量用粗短线与MCU连接。

将来的宽电压版本(2.4~5.5V)，P5.5是内部退耦端，接一个4.7uF的电容到地。

6个可唤醒按键，可作红外遥控发射或接收学习，或别的功能。

睡眠时，先将P3.4_KEY和P1.7_KEY输出低，P3.2_INT0和

P3.3_INT1输出高，并且在P3.2_INT0和P3.3_INT1都是高电平

时，进入睡眠之后按下任何键均能唤醒。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d8b131da278e99cf44566d48800e48a108c893339554a555c4070d20a51ca0fc.jpg)



0.1μF的电容(0603封装)参考价格为RMB 0.001元；4.7μF的电容(0603封装)参考价格为RMB 0.023元；10μF的电容(0603封装)参考价格为RMB 0.045元。


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c53edd9f24fe84976d81f6f41b8156c7ae9010758c2435d7e0972f3f1e52dbcb.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c032eef08dea57848071d47736781fe87a83288b4b2c16d669249fd51c1ece22.jpg)



每隔10ms左右读一次ADC值，并且保存最后3次的读数，其变化比较小时再判断键。判断键有效时，允许一定的偏差，比如±16个字的偏差。


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/30b6e13ae93b003b821386dc1d1a2cc230ddbd00861cf1cd70f528316621e5e1.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/55bf0c6c2eadd615ebd52890ee309472693e4a8ddc22809b6aa1455215598b7e.jpg)



两片74HC595驱动8个数码管 74HC595(SOP16封装)参考价格为RMB 0.2元。数码管使用共阴极比较好，因为595拉低能力比较强


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/9010de5e6377e20e7533a118fddf8e7cb00a542cbcdb6a2c4f7d61ea7be9d378.jpg)



STC15F2K60S2系列学习板电路示意图续


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c9fd51725b69bcd9eedd6a0e55d4fe9d0ee814c952cc64fb7c05592a62a40599.jpg)



PCB板上根据情况留一些过孔焊盘方便做实验(图例20x20)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/24bda48d3a4da28fd876d1d2ff4daf783d55583b9218ca43231ef34092df7223.jpg)


# 附录L：逻辑代数的基础

# 无微机原理的用户请从本章开始学习

这一章主要讲述的内容有： $\textcircled{1}$ 在数字设备中进行算术运算的基本知识——数制和编码； $\textcircled{2}$ 数字电路中一些常用逻辑运算及其图形符号。它们是学习单片机这门课程的基础。对于没有微机原理基础的用户和同学，请从这章开始学习。

# L.1 数制与编码

数制是人们利用符号进行计数的科学方法。数制有很多种，常用的数制有：二进制，十进制和十六进制。

进位计数制是把数划分为不同的位数，逐位累加，加到一定数量之后，再从零开始，同时向高位进位。进位计数制有三个要素：数码符号、进位规律和计数基数。下表是各常用数制的总体介绍。

<table><tr><td>常用的数制</td><td>表示符号</td><td>数码符号</td><td>进制规律</td><td>计数基数</td></tr><tr><td>二进制</td><td>B</td><td>0、1</td><td>逢二进一</td><td>2</td></tr><tr><td>十进制</td><td>D</td><td>0、1、2、3、4、5、6、7、8、9</td><td>逢十进一</td><td>10</td></tr><tr><td>十六进制</td><td>H</td><td>0、1、2、3、4、5、6、7、8、9、A、B、C、D、E、F</td><td>逢十六进一</td><td>16</td></tr></table>

我们日常生活中计数一般采用十进制。计算机中采用的是二进制，因为二进制具有运算简单，易实现且可靠，为逻辑设计提供了有利的途径、节省设备等优点。为区别于其它进制数，二进制数的书写通常在数的右下方注上基数2，或加后面加B表示。二进制数中每一位仅有0和1两个可能的数码，所以计数基数为2。二进制数的加法和乘法运算如下：

$$
0 + 0 = 0 \quad 0 + 1 = 1 + 0 = 1 \quad 1 + 1 = 1 0
$$

$$
0 \times 0 = 0 \quad 0 \times 1 = 1 \times 0 = 0 \quad 1 \times 1 = 1
$$

由于二进制数在使用中位数太长,不容易记忆，为了便于描述，又常用十六进制作为二进制的缩写。十六进制通常在表示时用尾部标志H或下标16以示区别。

# L.1.1 数制转换

现在我们来介绍这些常用数制之间的转换。

# 一：二进制 — 十进制转换

方法：将二进制数按权(如下式)展开，然后将各项的数值按十进制数相加，就得到相应的等值十进制数。

例如：N=(1101.101)B，那么N所对应的十进制数时多少呢？

按权展开 $\cdot N { = } 1 \times 2 ^ { 3 } + 1 \times 2 ^ { 2 } { + } 0 \times 2 ^ { 1 } { + } 1 \times 2 ^ { 0 } { + } 1 \times 2 ^ { - 1 } { + } 0 \times 2 ^ { - 2 } { + } 1 \times 2 ^ { - 3 } { = } 8 { + } 4 { + } 0 { + } 1 { + } 0 . 5 { + } 0 { + } 0 . 1 2 5 { = } ( 1 3 . 6 2 5 ) 1 3 { \div } 0 $ D

# 二：十进制 — 二进制转换

方法：分两部分进行即整数部分和小数部分。

$\textcircled{1}$ 整数部分转换(基数除法)：

把我们要转换的数除以二进制的基数(二进制的基数为2)，把余数作为二进制的最低位；★

把上一次得的商在除以二进制基数(即2)，把余数作为二进制的次低位；★

继续上一步,直到最后的商为零,这时的余数就是二进制的最高位.★

$\textcircled{2}$ 小数部分转换(基数乘法)：

把要转换数的小数部分乘以二进制的基数(二进制的基数为2)，把得到的整数部分作为二★进制小数部分的最高位；

$\star$ 把上一步得的小数部分再乘以二进制的基数(即2)，把整数部分作为二进制小数部分的次高位；

$\star$ 继续上一步，直到小数部分变成零为止。或者达到预定的要求也可以。

例如：将(213.8125) 化为二进制数可按如下进行：

先化整数部分：

2 213 余数 $ = 1 = k _ { 0 }$ 

1062 余数 $\scriptstyle = 0 = k _ { 1 }$ 

2 53 余数 $\scriptstyle \pm 1 = k _ { 2 }$ 

2 26 余数 $\scriptstyle \equiv 0 = k _ { 3 }$ 

2 13 余数 ${ \bf \bar { \tau } } = 1 = k _ { 4 }$ 

2 余数6 ${ \mathrm { = } } 0 { = } k _ { 5 }$ 

2 3 余数 $\scriptstyle : = 1 = k _ { 6 }$ 

2 1 余数 $\scriptstyle : = 1 = k _ { 7 }$ 0

于是整数部分(213)10=(11010101)2

再化小数部分：

0.8125 $\times \quad 2$ 1.6250 整数部分 $= 1 = k_{-1}$ 0.6250 $\times \quad 2$ 1.2500 整数部分 $= 1 = k_{-2}$ 0.2500 $\times \quad 2$ 0.5000 整数部分 $= 0 = k_{-3}$ 0.5000 $\times \quad 2$ 1.0000 整数部分 $= 1 = k_{-4}$ 

于是小数部分 $( 0 . 8 1 2 5 ) _ { 1 0 } { = } ( 0 . 1 1 0 1 ) _ { 2 }$ 

综上所述，十进制数213.8125=(11010101.1101)2=(11010101.1101)B

# 三：二进制 — 十六进制转换

方法：二进制和十六进制之间满足24 的关系，因此把要转换的二进制从低位到高位每4位一组，高位不足时在有效位前面添“0”，然后把每组二进制数转换成十六进制即可。

例如，将(010111011110.11010010)B转换为十六进制数：

$$
\begin{array}{c c c c c} (0 1 0 1 & 1 1 0 1 & 1 1 1 0. & 1 1 0 1 & 0 0 1 0) \mathrm {B} \\ \downarrow & \downarrow & \downarrow & \downarrow & \downarrow \\ = (5 & D & E & B & 2) \mathrm {H} \end{array}
$$

于是，(010111011110.11010010)B=(5DE.B2)H

# 四：十六进制 — 二进制转换

方法：十六进制转换为二进制时，把上面二进制转换十六进制的过程逆过来，即转换时只需将十六进制的每一位用等值的4位二进制代替就行了。

例如：将(C1B.C6)H转换为二进制数：

$$
\begin{array}{c c c c c} (\mathrm {C} & 1 & \mathrm {B}. & \mathrm {C} & 6) \mathrm {H} \\ \downarrow & \downarrow & \downarrow & \downarrow & \downarrow \\ = (1 1 0 0 & 0 0 0 1 & 1 0 1 1 & 1 1 0 0 & 0 1 1 0) \mathrm {B} \end{array}
$$

于是，(C1B.C6)H=(110000011011.11000110)B

# 五：十六进制 — 十进制转换

方法：将十六进制数按权(如下式)展开，然后将各项的数值按十进制数相加，就得到相应的等值十进制数。

例如：N=(2A.7F)H，那么N所对应的十进制数时多少呢？

按权展开N=2×161 +10×160 +7×16-1+15×16-2=32+10+0.4375+0.05859375 $=$ (42.49609375)D于是，(2A.7F)H $=$ (42.49609375)D

# 六：十进制 — 十六进制转换

方法：将十进制数转换为十六进制数时，可以先将十进制数转换为二进制数，然后再将得到的二进制数转换为等值的十六进制数。

# L.1.2 原码、反码及补码

在生活中,数有正负之分,在计算机中是怎样表示数的正负符号呢？

在生活中表示数的时候一般都是把正数前面加一个“+”，负数前面加一个“-”，但是计算机是不认识这些的，通常在二进制数前面增加一位符号位。符号位为“0”表示“+”，符号位为“1”表示“-”。这种形式的二进制数称为原码。如果原码为正数，则原码的反码和补码都与原码相同。如果原码为负数，则将原码(除符号位外)按位取反，所得的新二进制数称为原码的反码，反码加1为其补码。

原码、反码、补码这三种形式的总结如下表所示：

<table><tr><td></td><td>真值</td><td>原码</td><td>反码</td><td>补码</td></tr><tr><td>正数</td><td>+N</td><td>0N</td><td>0N</td><td>0N</td></tr><tr><td>负数</td><td>-N</td><td>1N</td><td>(2&quot;-1)+N</td><td>2&quot; + N</td></tr></table>

例1：求+18和-18八位原码、反码、补码形式。

真值

原码

反码

+18 

00010010 

00010010 

-18 

10010010 

11101101 

补码

00010010 

11101110 

# L.1.3 常用编码

指定某一组二进制数去代表某一指定的信息，就称为编码。

# 一：十进制编码

用二进制码表示的十进制数，称为十进制编码。它具有二进制的形式，还具有十进制的特点它可作为人们与数字系统的联系的一种间表示。十进制编码有很多种，最常用的一种是BCD码，又称8421码。

下面我们用表列出几种常见的十进制编码:

<table><tr><td>编码
十进
种类
制数</td><td>8421码
(BCD码)</td><td>余3码</td><td>2421码</td><td>5211码</td><td>7321码</td></tr><tr><td>0</td><td>0000</td><td>0011</td><td>0000</td><td>0000</td><td>0000</td></tr><tr><td>1</td><td>0001</td><td>0100</td><td>0001</td><td>0001</td><td>0001</td></tr><tr><td>2</td><td>0010</td><td>0101</td><td>0010</td><td>0100</td><td>0010</td></tr><tr><td>3</td><td>0011</td><td>0110</td><td>0011</td><td>0101</td><td>0011</td></tr><tr><td>4</td><td>0100</td><td>0111</td><td>0100</td><td>0111</td><td>0101</td></tr><tr><td>5</td><td>0101</td><td>1000</td><td>1011</td><td>1000</td><td>0110</td></tr><tr><td>6</td><td>0110</td><td>1001</td><td>1100</td><td>1001</td><td>0111</td></tr><tr><td>7</td><td>0111</td><td>1010</td><td>1101</td><td>1100</td><td>1000</td></tr><tr><td>8</td><td>1000</td><td>1011</td><td>1110</td><td>1101</td><td>1001</td></tr><tr><td>9</td><td>1001</td><td>1100</td><td>1111</td><td>1111</td><td>1010</td></tr><tr><td>权</td><td>8421</td><td></td><td>2421</td><td>5211</td><td>7321</td></tr></table>

十进制编码分为有权和无权编码。有权编码码是指每一位十进制数符均用一组四位二进制码来表示，而且二进制码的每一位都有固定权值。无权编码码是指二进制码中每一位都没有固定的权值。 上表中8421码(即BCD码)、2421码、5211码、7321码都是有权编码，而余3码是无权编码。

# 二： 奇偶校验码

在数据的存取、运算和传送过程中，难免会发生错误，把“1”错成“0”或把“0”错成“1”。奇偶校验码是一种能检验这种错误的代码。它分为两部分；信息位和奇偶校验位。有奇数个“1”称为奇校验，有偶数个“1”则称为偶校验。

# L.2 几种常用的逻辑运算及其图形符号

逻辑代数中常用的运算有：与(AND)、或(OR)、非(NOT)、与非(NAND)、或非(NOR)、与或非(AND-NOR)、异或(EXCLUSIVE OR)、同或(EXCLUSIVE NOR)等。其中与(AND)、或(OR)、非(NOT)运算时三种最基本的运算。

# 一：与运算及与门

与运算：决定事件结果的全部条件同时具备时，事件才发生。

逻辑变量A和B进行与运算时可写成：Y=A·B

<table><tr><td colspan="3">真值表</td></tr><tr><td>A</td><td>B</td><td>Y</td></tr><tr><td>0</td><td>0</td><td>0</td></tr><tr><td>0</td><td>1</td><td>0</td></tr><tr><td>1</td><td>0</td><td>0</td></tr><tr><td>1</td><td>1</td><td>1</td></tr></table>

与门：实行与逻辑运算的单元电路。

与门图形符号：

# 二：或运算及或门

或运算：决定事件结果的各条件中只要有任何一个满足，事件就会发生。

逻辑变量A和B进行或运算时可写成：Y=A+B

<table><tr><td colspan="3">真值表</td></tr><tr><td>A</td><td>B</td><td>Y</td></tr><tr><td>0</td><td>0</td><td>0</td></tr><tr><td>0</td><td>1</td><td>1</td></tr><tr><td>1</td><td>0</td><td>1</td></tr><tr><td>1</td><td>1</td><td>1</td></tr></table>

或门：实行或逻辑运算的单元电路。

或门图形符号：

# 三：非运算及非门

非运算：条件具备时，事件不会发生；条件不具备时，事件才会发生。

逻辑变量A进行非运算时可写成：Y=A $^ { \prime }$ 

<table><tr><td colspan="2">真值表</td></tr><tr><td>A</td><td>Y</td></tr><tr><td>0</td><td>1</td></tr><tr><td>1</td><td>0</td></tr></table>

非门：实行非逻辑运算的单元电路。

非门图形符号：

# 四：与非运算及与非图形符号

与非运算：先进行与运算，然后将结果求反，最后得到的即为与非运算结果。

逻辑变量A和B进行与非运算时可写成： $\mathrm { Y = }$ (A·B)

<table><tr><td colspan="3">真值表</td></tr><tr><td>A</td><td>B</td><td>Y</td></tr><tr><td>0</td><td>0</td><td>1</td></tr><tr><td>0</td><td>1</td><td>1</td></tr><tr><td>1</td><td>0</td><td>1</td></tr><tr><td>1</td><td>1</td><td>0</td></tr></table>

与非图形符号：

# 五：或非运算及或非图形符号

或非运算：先进行或运算，然后将结果求反，最后得到的即为或非运算结果。

逻辑变量A和B进行或非运算时可写成：Y=(A+B)

<table><tr><td colspan="3">真值表</td></tr><tr><td>A</td><td>B</td><td>Y</td></tr><tr><td>0</td><td>0</td><td>1</td></tr><tr><td>0</td><td>1</td><td>0</td></tr><tr><td>1</td><td>0</td><td>0</td></tr><tr><td>1</td><td>1</td><td>0</td></tr></table>

或非图形符号：

# 六：与或非运算及与或非图形符号

与或非运算：在与或非逻辑运算中有4个逻辑变量A、B、C、D。假设A和B为一组，C和D为一组，A、B之间以及C、D之间都是与的关系，只要A、B或C、D任何一组同时为1，输出Y就是0。只有当每一组输入都不全是1时，输出Y才是1。

逻辑变量A和B进行或非运算时可写成：Y=(A·B+C·D)

<table><tr><td colspan="5">真值表</td></tr><tr><td>A</td><td>B</td><td>C</td><td>D</td><td>Y</td></tr><tr><td>0</td><td>0</td><td>0</td><td>0</td><td>1</td></tr><tr><td>0</td><td>0</td><td>0</td><td>1</td><td>1</td></tr><tr><td>0</td><td>0</td><td>1</td><td>0</td><td>1</td></tr><tr><td>0</td><td>0</td><td>1</td><td>1</td><td>0</td></tr><tr><td>0</td><td>1</td><td>0</td><td>0</td><td>1</td></tr><tr><td>0</td><td>1</td><td>0</td><td>1</td><td>1</td></tr><tr><td>0</td><td>1</td><td>1</td><td>0</td><td>1</td></tr><tr><td>0</td><td>1</td><td>1</td><td>1</td><td>0</td></tr><tr><td>1</td><td>0</td><td>0</td><td>0</td><td>1</td></tr><tr><td>1</td><td>0</td><td>0</td><td>1</td><td>1</td></tr><tr><td>1</td><td>0</td><td>1</td><td>0</td><td>1</td></tr><tr><td>1</td><td>0</td><td>1</td><td>1</td><td>0</td></tr><tr><td>1</td><td>1</td><td>0</td><td>0</td><td>0</td></tr><tr><td>1</td><td>1</td><td>0</td><td>1</td><td>0</td></tr><tr><td>1</td><td>1</td><td>1</td><td>0</td><td>0</td></tr><tr><td>1</td><td>1</td><td>1</td><td>1</td><td>0</td></tr></table>

(接上表)

与或非图形符号：

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a60c92948b2f657f6dd7e31ecb8e436ff569377476209abe9e8142245af99afe.jpg)


# 七：异或运算及异或图形符号

异或运算：当A、B不同时，输出Y为1；而当A、B相同时，输出Y为0。

逻辑变量A和B进行异或运算时可写成： $\mathbf { Y } = \mathbf { A } \oplus \mathbf { B } = ( \mathbf { A } \cdot \mathbf { B } ^ { \prime } ) + ( \mathbf { A } ^ { \prime } \cdot \mathbf { B } )$ 

<table><tr><td colspan="3">真值表</td></tr><tr><td>A</td><td>B</td><td>Y</td></tr><tr><td>0</td><td>0</td><td>0</td></tr><tr><td>0</td><td>1</td><td>1</td></tr><tr><td>1</td><td>0</td><td>1</td></tr><tr><td>1</td><td>1</td><td>0</td></tr></table>

异或图形符号：

# 八：同或运算及同或图形符号

同或运算：当A、B不同时，输出Y为0；而当A、B相同时，输出Y为1。

逻辑变量A和B进行同或运算时可写成： $\mathrm { ~ Y ~ } = \mathrm { ~ A \odot B ~ } = \mathrm { ~ ( A ~ } \bullet \mathrm { ~ B ) } + ( \mathrm { A } ^ { \prime } \bullet \mathrm { ~ B } ^ { \prime } )$ 

<table><tr><td colspan="3">真值表</td></tr><tr><td>A</td><td>B</td><td>Y</td></tr><tr><td>0</td><td>0</td><td>1</td></tr><tr><td>0</td><td>1</td><td>0</td></tr><tr><td>1</td><td>0</td><td>0</td></tr><tr><td>1</td><td>1</td><td>1</td></tr></table>

同或图形符号：

# 附录M：STC对单片机相关学科群部分课程改革呼吁

工信部一位对推动中国单片机教学改革有兴趣的朋友约我对这方面提一点看法，与高校及企业合作多年的经验，我确实也深有感触。

STC自成立起就一直专注于国内流行的8051单片机的研发工作，和各高校以及企业保持着密切的联系和紧密的合作。根据我们STC与高校及企业合作多年的经验，我们深刻感受到当前大学里单片机课程教育存在的弊端，主要是开设的时间和顺序以及完整性，不需要增加教学时间，还可适当减少课时，当前单片机课程教育的改革迫在眉睫。对此我们提出以下建议。

单片机相关课程教学之最小系统课程：

《C语言程序设计》 大学一年级第一学期

《数字电路基础》 大学一年级第一学期

《微机原理及单片机应用》 大学一年级第二学期

《数据结构》 大学一年级第二学期

《实时操作系统》 大学二年级第一学期

《模拟电路》 大学二年级第一学期

首先，我们建议《C语言程序设计》课程必须保证在大学一年级第一学期开设，很多高校已这样做了，但还有部分学校滞后了，我的观念晚学不如早学，工科非工科都应将此门课作为进入信息时代的计算机扫盲课（word/excel/打字就由学生自学吧），学好了《C语言程序设计》课程就打好了单片机学习中的部分软件基础。相对于用汇编语言开发程序，C语言也将程序开发难度降低了很多，对开发人员来说，效率得到极大的提高，打个不恰当的比方，

大专生就相当于本科生的能力了，本科生就相当于研究生的能力了。

其次，我们强烈建议将《数字电路》课程提前放在大学一年级第一学期开设，《数字电路》能帮助学生理解微机原理和基本的数字系统，并能设计一些简单的硬件电路系统，是单片机学习的硬件基础。

再次，就是要学习《微机原理及单片机应用》了，我们强烈建议将《微机原理及单片机应用》课程提前到大学一年级第二学期开设。许多学校的相关工科专业都是在大学三年级第二学期才开设这门课程。由于接触单片机的时间晚，学生根本没时间认真学习和研究单片机，更没时间应用所学的知识开发一些单片机项目。在许多学生只学到一些单片机皮毛的情况下，他们便匆匆步入社会进入了相关行业。这种情况往往导致很多学生不能胜任自己的岗位，工作起来很吃力，而且极容易被淘汰。这就有了“学生抱怨就业难，企业却反映招不到人才”的怪现象。如果将《微机原理及单片机应用》课程提前至大学一年级第二学期开设，学生及早接触单片机的话，那么对单片机有兴趣或以后想从事相关行业的同学在意识到单片机的重要性后，仍然有充足的时间去研究单片机，从而将单片机系统设计搞熟。这样在他们毕业以后进入相关行

业及企业工作就会很快能胜任。单片机课程不是一门纯理论性的课程，更多的需要学生去动手实践和开发，所以学习单片机以及开发单片机项目能提高学生的创新能力，如果学得太晚就很难学以致用。其实很多工科的专业课程都如此，很多学生在学习完这些专业课程后之所以云里雾里、不知所云，就是因为没有花时间或没有足够的时间去研究和实践应用所学的内容。如果这些动手实践型的专业课程开设的太晚，学生在学习完之后根本没有时间去动手应用的话，那么这些课程就会形同虚设，对学生以后的就业将起不到应有的帮助作用。

另外，为了使学生在开发程序时，能得心应手，我们建议在大学一年级第二学期应再开设《数据结构》课程，提高开发效率，降低开发难度，同时如果《C语言程序设计》没学好，通过对《数据结构》的学习，也可算对《C语言程序设计》的复习，为单片机开发打好软件基础。还是那个不恰当的比方，有《数据结构》作为基础比没有《数据结构》作为基础的，大专生就相当于本科生的能力了，本科生就相当于研究生的能力了。

最后，我们建议在大学二年级第一学期开设《实时操作系统》和《模拟电路》等后续课程。这些课程是对前面所学课程的补充和提高，如果《数据结构》没学好，学习《实时操作系统》也可算对《数据结构》的复习，为单片机开发打好软件基础。基于实时操作系统的单片机开发，对开发者的能力要求可大幅降低，能较容易开发出大型、复杂的单片机项目。还是那个不恰当的比方，有《实时操作系统》作为基础比没有《实时操作系统》作为基础的，大专生就相当于本科生的能力了，本科生就相当于研究生的能力了。

有了以上基础，相信大学生创新竞赛会更有价值！

乘风破浪会有时，直挂云帆济沧海。

相信单片机课程教育的改革会给当前的单片机教育和科技创新开创一片新的天地，相信各高校一定能培养出更多、更专业、更符合社会需求的优秀人才。

# 附录N：STC对单片机课程教育改革的贡献

当前绝大部分高校都以8051单片机作为单片机课程教育的基础，但普通的8051单片机诞生与上世纪70年代，不可避免地面临着落伍的危险。为此，STC宏晶科技对8051单片机进行了全面的技术升级与创新，对当前单片机课程教育的改革有巨大的贡献。

宏晶科技STC单片机设计公司是全球最大的8051单片机设计公司，致力于开发设计1T增强型8051单片机，速度平均比普通8051快7~12倍，指令代码完全兼容普通8051单片机。STC单片机全部采用Flash技术(可反复编程10万次以上)和ISP/IAP(在系统可编程/在应用可编程)技术，并对传统8051进行了全面提速，指令最快提高了24倍。另外，STC针对抗干扰进行了专门设计，针对加密进行了特别加密设计，如宏晶STC15系列超强抗干扰，现无法解密。其次，STC单片机大幅提高了集成度，如集成了A/D、CCP/PCA/PWM(PWM还可当D/A使用)、高速同步串行通信端口SPI、高速异步串行通信端口UART(如宏晶STC15F2K60S2系列集成了两个串行口，分时复用可当5组串口使用)、定时器(宏晶STC15F2K60S2系列最多可达到6个定时器)、看门狗、高可靠复位电路(可彻底省掉外部复位)、内部高精准时钟(-40℃ ~ +85℃之间最大只有 $\pm 1 \%$ 的温飘，可彻底省掉外部昂贵的晶振)、大容量SRAM(如宏晶STC15F2K60S2系列集成了2K字节的SRAM)、大容量EEPROM、大容量Flash程序存储器等。STC单片机几乎包含了数据采集和控制中所需要的所有单元模块，可称得上是一个真正的片上系统(SysTem Chip或SysTem on Chip,简写为STC,这是宏晶科技STC名称的由来)。可以说，STC单片机来源于普通8051单片机，却又高于普通8051单片机。如果学生或单片机爱好者以STC单片机作为学习的工具，将会对8051单片机有个更全面更透彻的掌握。

STC单片机除对普通8051单片机的技术技术进行升级外，还对普通8051单片机一些复杂难懂的知识点进行了简化。例如，对初学者而言，定时器T0/T1的四种工作模式只需学习其中的模式0(16位自动重装载模式)，定时器0的模式3(不可屏蔽中断的16位自动重装载模式)还可作实时操作系统节拍定时器，定时器2也只需学习一种模式。另外，串行口的波特率计算公式也比普通8051的计算公式简单的多。例如，我们用定时器2作为串行口的波特率发生器，则串行口的波特率计数公式为：

串行口的波特率 $=$ (定时器T �出率)/4 ；

注意：此波特率与SMOD无关

……对教学而言，这些简化减少了教学的课时，从而大大减轻了教学压力。

STC公司设计生产的一些辅助工具，如STC-ISP下载编程工具，能够更好地帮助学生和单片机爱好者更容易地学习和理解STC单片机。对于单片机学习者而言，波特率的计算、定时器的计算、头文件的编写等一直是重点和难点，很多学习者在学习完单片机后不知道如何计算波特率、定时器的参数等等。最新的STC15系列ISP下载编程工具集成了波特率计算器、定时器计算器、软件延时器、头文件等有用的工具，所以使用STC单片机的用户再也不用担心不会计算波特率、定时器等参数了。

从宏晶科技STC单片机设计公司多年的发展来看，使用STC单片机的用户越来越多，可见STC对高校课程教育改革乃至对社会贡献的巨大。

# 附录O：STC推荐的单片机教材

# O.1 两本基于可仿真的STC15F2K60S2系列单片机的本科教材

# 一、《单片微型计算机原理及接口技术》，作者陈桂友，高等教育出版社出版

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/34e8bf751031b4373fd78cf926093219fd60708f428a37c427701d27983fc898.jpg)


《单片微型计算机原理及接口技术》，山东大学陈桂友教授主编，姚永平、王威康主审，由原教育部副部长吴启迪教授和教育部高等学校自动化专业分委员会主任、中国工程院院士清华大学吴澄教授共同作序，高等教育出版社出版，于2012年4月出版，受到热烈欢迎，至今已第三次印刷，得到了国内众多高校的教师普遍认可，计划2014年推出第二版。

此教材以可仿真的STC15F2K60S2系列单片机为背景，从介绍微型计算机的基本结构和工作原理入手，介绍单片微型计算机（单片机）的构成、各个模块的工作过程、接口原理、应用电路设计、汇编语言和C语言程序设计，精选应用实例，强化单片机技术的实践性与应用性，内容尽可能地选择了目前实际工程中常用的新技术、新器件，力图达到学以致用的根本目的。

全书共分12章，第1章简要介绍微型计算机的发展历史及应用；第2章介绍微型计算机的基础知识，包括数制编码、微型计算机的常见电路、常见技术术语等；第3章介绍计算机系统的组成与工作原理，介绍模型机的构成及工作过程，并介绍单片机的内部结构及典型系统构成；第4章介绍单片机的指令系统及汇编语言程序设计，介绍单片机程序仿真调试和下载的方法；第5章介绍单片机的C语言程序设计与调试，介绍C语言与单片机汇编语言之间的联系；第6章介绍中断的概念和单片机的中断系统；第7章介绍定时器计数器与可编程计数器阵列；第8章介绍数据通信技术，主要介绍常用的并行接口和串行接口工作原理、接口方法以及常用的数据接口芯片及其使用实例；第9章是模数转换器与数模转换器，分别介绍两种转换器的原理和典型芯片的应用；第10章介绍人机交互接口设计，人机交互接口是单片机应用系统必不可少的接口应用；第11章介绍单片机系统的看门狗技术、时钟选择及省电方式的原理和技术；第12章介绍应用系统的设计实例，从硬件和软件两个方面介绍应用系统的设计。每章都有配套的习题，所举例程均经调试通过，很多程序均来自科研和实际应用系统。为了便于学习，开发了与教材配套的综合教学实验平台，该平台提供了20余种实验供学生选用学习，也为善于思考、乐于动手实践的学生提供了自学习实验手段。

本书深入浅出，层次分明，实例丰富，通俗易懂，突出实用，可操作性强，特别适合于作为普通高校计算机类、电子类、电气自动化及机械专业的教学用书。还可作为高职高专以及培训班的教材使用。同时，也可作为从事单片机应用领域的工程技术人员的参考书。

网上订购：当当网、京东商城、亚马逊等

# 二、《单片微机原理及接口技术》——基于可仿真的STC15系列单片机，作者丁向荣

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/f80f8fbb3dab42022d5d69fa64e66cc67c6328c14721b6fbce798bdf6d7656b5.jpg)


《单片微机原理与接口技术(ASM+C) -基于STC15系列单片机》 ，作者丁向荣，本教材于2012年9月出版，于2013年8月第二次印刷，使用本教材的大学有中国矿业大学、深圳大学、河海大学、九江学院、苏州大学、北方理工大学、东北石油大学、北方工业大学等。

此教材选用可在线仿真、在线编程、内置复位电路与时钟电路的STC15系列单片机；将微机原理与单片机技术有机结合，汇编语言与C语言“双语言”对照编程； 精选应用实例，强化单片机技术的实践性与应用性。

在全国各大书店和当当网、京东商城、亚马逊等网店有售

该书内容简介：

STC15系列增强型8051单片机集成了上电复位电路与高精准R/C振荡器，给单片机芯片加上电源就可跑程序；集成了大容量的程序存储器、数据存储器以及EEPRM，集成了A/D、PWM、SPI等高功能接口部件，可大大地简化单片机应用系统的外围电路，促使单片机应用系统的设计更加简捷，系统性能更加高效、可靠。本教材以STC15F2K60S2单片机为主线，系统地介绍了STC15F2K60S2单片机的硬件结构、指令系统与应用编程，系统地介绍了单片机应用系统的开发流程与接口设计，同时，提出多种实践模式：Keil C集成开发环境、Proteus仿真软件以及实物运行开发环境，使得单片机的学习与应用变得更简单、更清晰。

本书可作为普通高校计算机类、电子信息类、电气自动化与机电一体化等专业的教学用书，基础较好的高职高专也可选用本书。此外，可作为电子设计竞赛、电子设计工程师考证的培训教材。也是传统8051单片机应用工程师升级转型的重要参考书籍。

# O.2 一本基于可仿真的STC15系列单片机的高职高专教材

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/80f2730d5f34bdf3de8684ef286b1a8916ab94bd1a4072e7a50af272f5e56a49.jpg)


《增强型单片机8051单片机原理与系统开发（C51版）》，作者丁向荣，于2013年9月清华大学出版。本教材可作为高职或应用本科计算机类、电子信息类、电气自动化与机电一体化等专业的教学用书。此外，本书可作为电子设计竞赛、电子设计工程师考证的培训教材，也是传统8051单片机应用工程师升级转型的重要参考书。

此教材基于可在线仿真、在线编程、内置复位电路与时钟电路的STC15系列单片机，工学结合，采用任务驱动模式组织教材内容，将教学内容嵌入到一个个单片机应用系统中，学习单片机就是在做单片机应用系统，可实施“教、学、做”一体化教学模式，能有效提高单片机应用实践能力与编程能力。

本教材在当当网、京东商城、亚马逊等网店有售。

STC15F2K60S2系列增强型8051单片机集成了上电复位电路与高精准RC振荡器，给单片机芯片加上电源就可以运行程序；集成了大容量的程序存储器、数据存储器以及E2PROM，集成了A/D、PWM、SPI等高功能接口部件，可大大地简化单片机应用系统的外围电路，促使单片机应用系统的设计更加简便、快捷，系统性能更加高效、可靠。

STC15F2K60S2单片机的可仿真技术是STC系列单片机的一大创举，它可自定义为仿真芯片或目标应用芯片，仿真时无需增加任何电路，使得单片机仿真变得简单而实用。

本教材按照“教、学、做”一体化教学模式组织教学内容，分基础篇与应用篇，共17个项目，42个任务，兼顾少学时与多学时教学体系。

本书可作为高职或应用本科计算机类、电子信息类、电气自动化与机电一体化等专业的教学用书。此外，本书可作为电子设计竞赛、电子设计工程师考证的培训教材，也是传统8051单片机应用工程师升级转型的重要参考书。

# 附录P：每日更新内容的备忘录

# 2012-3-19更新内容：

（1）更新了“STC对单片机教育改革的贡献”的内容；

（2）增加了附录“学习板/开发板的推荐参考电路图”；

（3）更新了“A/D转换模块的参考电压源”中的线路图；

（4）将“利用USB转串口的ISP下载编程典型应用线路图”中的CH341T换成了成本更低的CH340T

# 2012-3-25更新内容：

（1）增加了“I/O口行列式按键扫描应用线路图”一节；

（2）增加了“两片74HC595驱动8个数码管的应用线路图”一节；

（3）更新了附录中“电源典型线路图”一节；

（4）修正了“I/O口的外部输入何时为低电平(0.8V以下)何时为高电平(2.2V以上)”这一节的内容；

（5）更新了“STC15F2K60S2选型一览表”一节；

# 2012-3-29更新内容：

（1）增加了“STC15F2K60S2系列学习板电路示意图”一节

（2）增加了“利用74HC595扩展I/O口的线路图(串行扩展，3根线)”一节

（3）修改了“利用74HC595驱动8个数码管的线路图(串行扩展，3根线)”一节

（4）增加了“利用I/O口方式控制74HC595驱动8个数码管的测试程序”一节

（5）增加了“利用SPI方式控制74HC595驱动8个数码管的测试程序”一节

（6）修改了“I/O口行列式按键扫描应用线路图”一节；

（7）修改了“A/D转换模块的基准参考电压源典型线路图”一节；

# 2012-4-11更新内容：

（1）增加了“74HC595的关键介绍及逻辑表”一节；

（2）增加了“STC15F2K60S2系列接外部晶振和外部复位(实际不需要接)的线路图”一节

（3）增加了“利用SPI接口控制74HC595驱动8位数码管(串行扩展，3根线)的线路图及其测试程序(C和汇编)”一节

（4）增加了“利用SPI接口和TLC2543扩展12位ADC的应用线路图”一节；

（5）修改了附录“利用并行总线扩展32K SRAM的典型应用线路图”；

（6）修改了STC15W4K60S4系列的管脚图，在STC15W4K60S4系列的管脚上增加了P4.2/CCP3、P4.4/CCP4、P4.5/CCP5，即STC15W4K60S4系列新增加了3路CCP/PCA/PWM，共6路CCP/PCA/PWM；

（7）修改了“STC15W4K60S4系列彩色宣传资料”

# 2012-4-17更新内容：

（1）修正了“74HC595的关键介绍及逻辑表”一节中图上的错误；

（2）在“利用74HC595扩展I/O口的线路图(串行扩展，3根线)”一节中将74HC595每个口的对外拉电流能力修正为30mA；

（3）在“利用74HC595驱动8个数码管的线路图(串行扩展，3根线)”中第二个74HC595(U6)上增加了一个电容(104)。

（4）修改了“利用SPI方式控制74HC595驱动8个数码管的测试程序”

（5）修改了“利用SPI接口和TLC2543扩展12位ADC的应用线路图”一节；

（6）修改了“STC15W4K60S4系列彩色宣传资料”

（7）在第三章的外部数据总线扩展章节后增加了“利用并行总线扩展32K SRAM的典型应用线路图”一节

（8）第三章的标题改为“存储器和特殊功能寄存器(SFRs)”。

# 2012-4-28更新内容：

（1）更正了“SOP32封装尺寸图”中的尺寸错误；

（2）STC15系列的串行口1建议放在[P3.6/RxD_2,P3.7/TxD_2]或[P1.6/RxD_3/XTAL2,P1.7/TxD_3/XTAL1]上；

（3）调整的第二章“时钟、复位及省电模式”的章节顺序；

（4）修正了“利用并行总线扩展外部32K SRAM的典型应用线路图”；

（5）更正了“STC15系列仿真器的说明”一节中的少量错误；

（6）调整了“STC15系列CCP/PCA/PWM/DAC应用”章中的小节顺序；

（7）在“STC15系列单片机的A/D转换器”一章中去掉了“利用CCP/PCA模块实现8~16位DAC的参考线路图”小节.

# 2012-5-1更新内容：

（1）更正了“74HC595管脚介绍”中的错误；

（2）更正了“利用普通I/O口控制74HC595驱动8个数码管的测试程序(C和汇编)”中的错误；

（3）更正了“利用SPI控制74HC595驱动8个数码管的测试程序(C和汇编)”中的错误；

（4）更正了“利用SPI接口扩展12位ADC(TLC2543)的应用线路图”中的错误；

（5）修改了“PWM输出时I/O口的状态”，STC15系列单片机的I/O口作PWM用时不改变口的输出状态，要软件设置，与STC12系列不一样；

（6）掉电唤醒专用定时器的功耗：3V器件典型值低于3uA；5器件典型值低于5uA；

（7）修改了“串口1自动地址识别功能的介绍”；

（8）修改了“多机通信”中的错误；

# 2012-7-1更新内容：

（1）更正了SPI章节“作为主机/从机的额外注意事项”中的错误；

（2）更正了SPI章节“数据模式”中的错误；

（3）将文中“请求中断标志位”的错误更正为“中断请求标志位”；

# 2012-8-22更新内容：

（1）STC15F104S系列更名为STC15W104SW系列，即STC15W104SW系列有内部掉电唤醒专用定时器；

（2）STC15F101W系列新增加了两个型号STC15F102和STC15F104，这两个型号的单片机无内部掉电唤醒专用定时器；

（3）STC-ISP下载编程工具升级为STC-ISP-V6.58版本；

# 2013-6-13更新内容：

（1） 更新了STC彩色宣传资料

（2） STC15F104SW系列更名为STC15W104SW系列；

（3） STC15F408AD系列删掉了20-pin和16-pin的封装；

（4） 删掉了型号STC15F204W；

（6） 增加了型号STC15W201S；

（7） STC15F104SW系列更名为STC15W104SW系列；

（8） STC15F204AD系列更名为STC15W408AS系列；

（9） 删掉了型号STC151K28AD；

（10）STC15F412X系列更名为STC15W408S系列；

（11）STC15F1K60W系列更名为STC15W1K16S系列；

（12）STC15W4K60S4系列更名为STC15W4K60S4系列；

（13）增加了一章“STCW比较器”说明；

（14）STC-ISP下载编程工具升级为STC-ISP-V6.25版本,详细说明了仿真器/下载编程器；

（15）更新了附录H“STC15F2K60S2学习板电路示意图”；

# 2013-6-19更新内容：

（1） 更新了STC彩色宣传资料

（2） STC15F412AD系列更名为STC15F408AD系列；

（3） STC15F104W系列更名为STC15F101W系列；

（4） STC15W204S系列更名为STC15W201S系列；

（5） STC15W204AD系列更名为STC15W408AS系列；

（6） 比较器相关管脚CMPP更正为CMP+,CMPN更正为CMP-；

# 2013-6-23更新内容：

（1）增加了1.13节“关于ID号在大批量生产中的应用方法(较多用户的用法)”

（2）增加了1.14节“在全球唯一身份证号码(ID号)前添加软复位指令”

（3）增加了12.1节“比较器的外部掉电检测电路”；

（4）删除了14.2.13节“如何解决VB版ISP在XP或WIN7下控件过期或不能注册问题”；

# 2013-6-24更新内容：

（1）更新了STC彩色宣传资料

（2）更正了12.3节“比较器的外部掉电检测电路”说明；

# 2013-6-30更新内容：

（1）新增STC15W1K16S系列彩色宣传资料

（2）新增12.4节“STC15系列比较器作ADC的程序举例(C语言)”；

（3）STC15W408AS系列单片机有外部晶振XTAL1/XTAL2；

（4）更新了14.4节“STC仿真器说明指南”

（5）更正了12.3节“比较器的外部掉电检测电路”说明；

# 2013-7-7更新内容：

（1）更新了14章“编译器(汇编器)/ISP编程器(烧录)/仿真器说明”

（2）调整了第一章各系列单片机的“选型价格一览表”小节、“封装价格一览表”小节与“命名规则”小节的顺序；

# 2013-7-8更新内容：

更新了STC15W1K16S系列彩色宣传资料

# 2013-7-13更新内容：

添加了10.7节“利用新增的ADC第9通道测量内部参考电压的测试程序——所测量的内部参考电压BandGap电压用来计算工作电压Vcc”

# 2013-7-15更新内容：

（1）14.4节“仿真器说明指南”；

（2）增加了 12.5节“现供货的STC15W201S系列A版本比较器下降沿中断不响应，将在STC15W201S系列B版修正”的说明；

（3）增加了 13.8节“现供货的STC15F2K60S2及STC15L2K60S2系列C版本SPI从机模式不能用，将在STC15W2K60S2系列修正”的说明；

（4）增加了 13.9节“现供货的STC15F408AD及STC15L408AD系列C版本SPI从机模式不能用，将在STC15F408AD及STC15L408AD系列D版本修正”的说明。

# 2013-8-18更新内容：

（1）STC15W201S系列已开始大批量供货；

（2）STC15W1K16S系列将在2013年10月15日开始供货；

（3）修正了附录E“一个I/O驱动发光二极管并按键扫描”中图的错误；

（4）更新了14.5“简易脱机下载工具U7-S1的使用说明”；

（5）新增了1.1.11节“现供货的STC15F2K60S2系列C版本的BUG声明及其解决办法”；

（6）现供货的STC15F2K60S2系列C版本的主时钟在MCLKO/P5.4只能对外输出内部R/C时钟，暂时不能对外输出外部输入的时钟或外部晶体振荡产生的时钟；

（7）现供货的STC15F2K60S2系列C版本的RxD管脚不能唤醒掉电模式/停机模式；

（8）将在STC15W201S系列管脚图中的P1.0更正为P1.0/RSTOUT_LOW，即该管脚上电后,输出低电平，在复位期间也是输出低电平，用户可用软件将其设置为高电平或低电平，如果要读外部状态，可将该口先置高后再读；

（9）更正了12.5节“现供货的STC15W201S系列A版本的比较器下降沿中断不响应”的说明；

（10）在STC15W系列20-pin及其以上单片机的P1.6管脚上增加MCLKO_2/P1.6，即STC15W系列20-pin及其以上单片机还可在MCLKO_2/P1.6口对外输出主时钟，并同时将STC15W系列单片机的寄存器CLK_DIV中的B3设置为MCLKO_2来选择主时钟输出的位置。若该寄存器位MCLKO_2/CLK_DIV.3为1，则主时钟输出在MCLKO_2/P1.6口；否则，主时钟输出在MCLKO/P5.4口

# 2013-9-12更新内容：

（1）新增官方网站：www.GXWMCU.com

（2）STC15W408S系列和STC15W1K16S系列将于2014年1月开始供货；

（3）修正了5.3.1节及5.3.2节“传统8051单片机指令定义详解”中的错误；

（4）更新了8.2.2节中“串行口模式1功能结构示意图”中的错误及8.2.4节中“串行口模式3功能结构示意图”中的错误；

（5）STC15W系列单片机采用宏晶第九代加密技术加密，无法解密

# 2013-10-18更新内容：

（1）STC15W408S系列和STC15W1K16S系列单片机无管脚XTAL2及管脚XTAL1

（2）STC15F2K60S2系列中RxD2管脚也不能唤醒掉电模式/停机模式

（3）STC15F408AD系列中RxD管脚不能唤醒掉电模式/停机模式

（4）STC15系列中串口1的切换寄存器位[S1_S1, S1_S0]的默认值由[0, 1]修改为[0, 0]，即串口1默认不在[P3.6/RxD_2, P3.7/TxD_2]上，若用户需要将串口1放在[P3.6/RxD_2, P3.7/TxD_2]上，则须在程序中将[S1_S1, S1_S0]的值设置为[0, 1]，且还须在用STC-ISP下载编程软件烧录用户程序时勾选中该软件的【硬件选项】工具栏中的选项【串口1数据线[RxD, TxD]从[P3.0, P3.1]切换到[P3.6, P3.7]，P3.7脚输出P3.6脚的输入电平】

（5）新增小节1.15“现供货的STC15系列为实现的计划功能”；

（6）新增“简易脱机下载器U7的使用说明”；

（7）修正12章“比较器内部规划图”中的错误；

（8）原研发顾问QQ13922805190容量已满，现将研发顾问QQ更为；800003751

# 2013-11-21更新内容：

（1）新增DFN-8封装尺寸图

（2）STC15F/L104W及STC15F/L105W型号单片机新提供DFN-8封装。

# 2013-11-22更新内容：

修正14.5.1.1“简易脱机下载器U7的功能介绍”的图中User_Vcc与S_Vcc的位置介绍错误

# 2013-11-29更新内容：

（1）更新了14.5节“简易脱机下载工具的使用说明”

（2）更新了部分系列的供货时间

# 2013-12-16更新内容：

（1）新增了章节14.5“如何让传统8051单片机学习板可仿真”

（2）更新了STC15W4K60S4系列的管脚图

（3）推荐了三本单片机教材

（4）新增STC15W408AS系列彩色宣传资料

# 2014-1-19更新内容：

（1）新增了附录E

（2）新增了附录J

（3）更新了STC15W4K60S4系列的管脚图

（4）更新了彩色宣传资料

# 2014-2-8更新内容：

（1）更新了彩色宣传资料

（2）更新了STC15系列产品的价格

# 2014-2-23更新内容：

（1）更新了彩色宣传资料

（2）新增了14.2.12节“用户接口”介绍

（3）将“程序加密后传输，收到用户命令后ISP下载”功能修正为“程序加密后传输”功能

（4）STC15W408S及STC15W1K16S系列单片机已开始供货，且要用其T0CLKO时钟输出功能需将P3.5设置为强推挽输出模式

（5）STC15W201S、STC15W408S及STC15W1K16S系列中以STC开头的单片机不能用MOVC读EEPROM.

# 2014-3-11更新内容：

（1）更新了彩色宣传资料

（2）STC15W408AS系列已开始供货，STC15W1K16S系列大批量供货中，STC15W408S系列供货中，STC15W4K60S4系列2014年6月开始送样。

（3）将文中输写错误“TOCLKO”更正为“T0CLKO”

（4）STC15W408S系列及STC15W408AS系列中以STC开头的单片机可以用MOVC读EEPROM.

（5）暂无STC15W2K60S2系列，删除原文中STC15W2K60S2系列的介绍

# 2014-3-21更新内容：

（1）更新了彩色宣传资料；

（2）STC15W408AS系列所有型号单片机新增TSSOP28封装，封装为TSSOP28的单片机比封装为SOP28的单片机贵0.1元；

（3）IAP15W1K29S型号单片机新增TSSOP20封装，该型号的封装为TSSOP20的单片机与其封装为SOP28的单片机的价格相同；

（4）IAP15F2K61S2型号单片机新增TSSOP20封装，该型号的封装为TSSOP20的单片机与其封装为SOP28的单片机的价格相同；

（5）新增TSSOP28封装尺寸图；

（6）新增TSSOP20封装尺寸图；

（7）新增第15章“利用其他MCU对STC15系列单片机进行串口ISP下载”

# 2014-3-31更新内容：

（1）更新了彩色宣传资料；

（2）更新了STC15F2K60S2系列单片机的价格；

（3）新增第16章“使用STC15系列单片机的ADC做电容感应触摸按键”；

（4）新增13.8节“利用STC15系列单片机SPI的主模式读写外部串行Flash”；

（5）新增10.9节"利用BandGap电压精确测量外部输入电压值及测试程序"；

（6）新增12.5节“在比较器负端产生不同的电压由比较器正端进行比较”；

（7）STC15W201S系列新增8-pin的封装为SOP8的单片机

# 2014-4-12更新内容：

（1）更新了彩色宣传资料；

（2）将第16章“使用STC15系列单片机的ADC做电容感应触摸按键”调整为第13章；

（3）STC15F/L104W系列、STC15F/L2K60S2系列、STC15F/L408AD系列及STC15W408AS系列单片机可用MOVC指令读取程序区和EEPROM区的数据；而STC15W204S系列、STC15W1K16S系列及STC15W408S系列单片机只能用MOVC读取程序区,不能读取EEPROM区的数据,否则程序会复位。

# 附录Q：STC彩色宣传资料

Q.1 STC15F2K60S2系列彩色宣传资料

Q.2 STC15W1K16S系列彩色宣传资料

Q.3 STC15W408AS系列彩色宣传资料

Q.4 STC15F101W系列彩色宣传资料

Q.6 STC12C5A60S2系列彩色宣传资料

Q.7 STC11/10系列带外部数据总线的彩色宣传资料

Q.8 STC11/10系列无外部数据总线的彩色宣传资料

Q.9 STC12C5201AD系列彩色宣传资料

Q.10 STC12C5620AD系列彩色宣传资料

Q.11 STC12C5410AD/STC12C2052AD系列彩色宣传资料

Q.12 STC89C51/STC90C51系列彩色宣传资料

Q.13 STC15W4K60S4系列彩色宣传资料

# STC micro TM

# 宏 晶 科 技

# 超强抗干扰， 无法解密

8051单片机全球第一品牌，全球最大的8051单片机设计公司

全部中国大陆本土独立自主知识产权；品质保证：TSMC上海制造

宣方网站 www.STCMCU.com

www.GXWMCU.com 

南通 Tel: 0513-5501 2928 5501 2929

深圳 Tel: 0755-8294 8411 8294 8412

# STC15F2K60S2系列1T 8051单片机，2K字节SRAM，超高速双串口，高速A/D

不需外部晶振的单片机不需外部复位的单片机

送仿真器

全球第一款真正意义上的单片机ISP/IAP技术全球领导者

采用宏晶第八代加密技术，现悬赏10万元人民币请专家帮忙查找加密有无漏洞

STC15F101W系列，大批量供货中，RMB1.2元起(STC15F101W)

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/a563b0c8af611b9733619a8e37198dfb2b7018ab5a74303f1757da742f7d50d6.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/9058f7a5ff3146a0cf5a6084b777f45330476592e86a126228612fc70838b91b.jpg)


<table><tr><td>型号</td><td>工作电压(V)</td><td>Flash 程序存储器byte)</td><td>大容量 RAM A字节</td><td>S P 1 位有机模式</td><td>普通定时器计数器T0-T2外部解掉电 嘌频</td><td>CCP PCA PWM PWM T0-T2 排除掉电 嘌频</td><td>标准外部中断支持掉电频</td><td>A/D 8路(3路)PWM 可选D/A 使用</td><td>D</td><td>EEPROM</td><td>内部低压检测中断可掉掉电频</td><td>内部复位可选门限电压</td><td>信号后盖机后盖传输层</td><td>是否支持RS485 下载</td><td>所有封装 LQFP44/DP140 LQFP32 SOP28/SKDP28/TSSOP20 (现此系列未生产PLCC44和/SOP32封装) 部分封装价格(RMB V) TSSOP20/SOP29 SKDPI28/LQFP32</td><td>XLTA XLTA</td><td></td><td></td><td></td><td></td><td></td></tr><tr><td rowspan="41">大批量现货供应中</td><td colspan="17">STC15F2K60S2 特别提醒:35CCP/PCA/PWM还可当3路定时器使用</td><td></td><td></td><td></td><td></td></tr><tr><td>STC15F2K08S2 5.5-3.8</td><td>8K</td><td>2K</td><td>2组</td><td>3</td><td>3-3-ch</td><td>有</td><td>5</td><td>10位</td><td>2</td><td>53K</td><td>有</td><td>8级</td><td>有</td><td>是</td><td></td><td>¥3.8</td><td>¥4.0</td><td>¥3.9</td><td>¥4.5</td><td>¥4.0</td></tr><tr><td>STC15F2K162S2 5.5-3.8</td><td>16K</td><td>2K</td><td>2组</td><td>3</td><td>3-3-ch</td><td>有</td><td>5</td><td>10位</td><td>2</td><td>45K</td><td>有</td><td>8级</td><td>有</td><td>是</td><td>¥4.0</td><td>¥4.2</td><td>¥4.1</td><td>¥4.7</td><td>¥4.2</td><td></td></tr><tr><td>STC15F2K322S2 5.5-3.8</td><td>32K</td><td>2K</td><td>2组</td><td>3</td><td>3-3-ch</td><td>有</td><td>5</td><td>10位</td><td>2</td><td>29K</td><td>有</td><td>8级</td><td>有</td><td>是</td><td>¥4.3</td><td>¥4.5</td><td>¥4.4</td><td>¥4.9</td><td>¥4.5</td><td></td></tr><tr><td>STC15F2K402S2 5.5-3.8</td><td>40K</td><td>2K</td><td>2组</td><td>3</td><td>3-3-ch</td><td>有</td><td>5</td><td>10位</td><td>2</td><td>21K</td><td>有</td><td>8级</td><td>有</td><td>是</td><td>¥4.4</td><td>¥4.6</td><td>¥4.5</td><td>¥4.9</td><td>¥4.6</td><td></td></tr><tr><td>STC15F2K482S2 5.5-3.8</td><td>48K</td><td>2K</td><td>2组</td><td>3</td><td>3-3-ch</td><td>有</td><td>5</td><td>10位</td><td>2</td><td>13K</td><td>有</td><td>8级</td><td>有</td><td>是</td><td>¥4.4</td><td>¥4.6</td><td>¥4.5</td><td>¥4.9</td><td>¥4.6</td><td></td></tr><tr><td>STC15F2K562S2 5.5-3.8</td><td>56K</td><td>2K</td><td>2组</td><td>3</td><td>3-3-ch</td><td>有</td><td>5</td><td>10位</td><td>2</td><td>5K</td><td>有</td><td>8级</td><td>有</td><td>是</td><td>¥4.4</td><td>¥4.6</td><td>¥4.5</td><td>¥4.9</td><td>¥4.6</td><td></td></tr><tr><td>STC15F2K602S2 5.5-3.8</td><td>60K</td><td>2K</td><td>2组</td><td>3</td><td>3-3-ch</td><td>有</td><td>5</td><td>10位</td><td>2</td><td>1K</td><td>有</td><td>8级</td><td>有</td><td>是</td><td>¥4.4</td><td>¥4.6</td><td>¥4.5</td><td>¥4.9</td><td>¥4.6</td><td></td></tr><tr><td colspan="20">IAP15F2K612S 本身就是仿真器</td><td></td></tr><tr><td>ICRC15F2K63S2 5.5-3.8</td><td>61K</td><td>2K</td><td>2组</td><td>3</td><td>3-3-ch</td><td>有</td><td>5</td><td>10位</td><td>2</td><td>IAP</td><td>有</td><td>8级</td><td>有</td><td>是</td><td>¥4.4</td><td>¥4.6</td><td>¥4.5</td><td>¥4.9</td><td>¥4.6</td><td></td></tr><tr><td colspan="20">用户可将用户程序区的程序Flash/EEPROM使用</td><td></td></tr><tr><td>ICRC15F2K64S2 5.5-3.8</td><td>63.5K</td><td>2K</td><td>2组</td><td>3</td><td>3-3-ch</td><td>有</td><td>5</td><td>10位</td><td>2</td><td>IAP</td><td>有</td><td>固定</td><td>有</td><td>无</td><td colspan="5">否</td><td></td></tr><tr><td colspan="20">用户可将用户程序区的程序Flash当EEPROM使用</td><td></td></tr><tr><td colspan="20">IAP15F2K61S 本用户可将用户程序区的程序Flash/EEPROM使用</td><td></td></tr><tr><td colspan="20">STC15F1011W 系列单片机选型价格一览表,另有STC15L系列工作电压2.4V-3.6V</td><td></td></tr><tr><td colspan="20">串行口功能可由P3.0 INT4、P3.1组合定时器实现</td><td></td></tr><tr><td colspan="20">SOP8</td><td></td></tr><tr><td colspan="20">DIP8</td><td></td></tr><tr><td colspan="20">DFN8</td><td></td></tr><tr><td colspan="20">¥1.2</td><td></td></tr><tr><td colspan="20">¥1.5</td><td></td></tr><tr><td colspan="20">¥1.6</td><td></td></tr><tr><td colspan="20">¥1.7</td><td></td></tr><tr><td colspan="20">¥1.8</td><td></td></tr><tr><td colspan="20">¥1.9</td><td></td></tr><tr><td colspan="20">¥1.1</td><td></td></tr><tr><td colspan="20">¥1.1</td><td></td></tr><tr><td colspan="20">¥1.1</td><td></td></tr><tr><td colspan="19">¥1.1</td><td></td><td></td></tr><tr><td colspan="19">¥1.1</td><td></td><td></td></tr><tr><td colspan="19">¥1.1</td><td></td><td></td></tr><tr><td colspan="19">¥1.1</td><td></td><td></td></tr><tr><td colspan="11">¥1.1</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td colspan="11">¥1.1</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td colspan="11">¥1.1</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td colspan="11">¥1.1</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td colspan="10">¥1.1</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td colspan="10">¥1.1</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td colspan="10">¥1.1</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td colspan="10">¥1.1</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td colspan="2">¥1.1</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr></table>


以上单价为 起定量，量小每片需加 元，以上价格运费由客户承担，零售 片起，如对价格不满，可来电要求降



上表中以I�RC�开头的单片机内部复位门槛电压固定�，不支持"程序加密后传输"功能(以STC�及I�AP�开头的单片机支持"程序加密后传输"功能),王在位管职大的4不可机当复位管们体使用是，不文与下载出



程序加密后传输： 程序拥有者产品出厂时将源程序和加密钥匙一起烧录MCU中，以后需要升级软件时，就可将程序加密后再用"发布项目程序"功能，生成一个用户自己界面的只有一个升级按钮的简单易用的升级软件，给最终使用者自己升级，而拦截不到您的原始程序。


# 宏晶•STC15F2K60S2系列主要性能：

大容量2048字节片内RAM数据存储器

. 高速：1个时钟/机器周期，增强型8051内核，速度比 �8051快7～12倍速度也 STC早期的1T系列单片机(如STC12/11/10系列)的速度快20%

宽电压：5.5～3.8V，2.4～3.6V(STC15L2K60S2系列)●

低功耗设计：低速模式，��模式，掉电模式(可由外部中断或内部掉电唤醒定时器 )●

. 不需外部复位的单片机，ISP编程时8级复位门槛电压可选，内置高可靠复位电路

. 不需外部晶振的单片机，ISP编程时内部时钟从 可设 � � ： ～ )内部高精度R/C时钟 $\cdot$ )，±1%温飘(-40℃~+85℃)，常温下温飘±0.6%(-20℃~+65℃)

支持掉电唤醒的资源有：INT0/INT1(上升沿/下降沿中断均可), INT2/INT3/INT4(下降沿中断)；●CCP0/CCP1/CCP2/T0/T1/T2管脚；内部掉电唤醒专用定时器

8/16/24/32/40/48/56/60/61/63.5K字节片内Flash程序存储器，擦写次数10万次以上●

大容量 EEPROM功能,擦写次数10万次以上●

ISP/IAP，在系统可编程/在应用可编程,无需编程器/仿真器●

. 高速ADC，8通道10位，速度可达30万次/秒�。3路PWM还可当3路D/A使用

3通道捕获/比较单元(CCP/PCA/PWM)●

-也可用来再实现3路 或 个定时器或 个外部中断(支持上升沿/下降沿中断)

6个定时器，2个16位可重装载定时器T0和T1兼容普通8051的定时器，新增了一个16位的定时器T2，●并都可实现可编程时钟输出，另外管脚 可将内部主时钟对外分频输出(÷1或÷2或÷4)，3路CCP/PCA可再实现3个定时器

# STC 单片机在线编程/ISP及仿真线路(USB转

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/64060aee46bd02432f50e6ecb4da836e329ef14ded00d4b6c26388ca3e8407e2.jpg)


建议用户将串口1设在[P3.6/RxD_2,P3.7/TxD_2]或[P1.6/RxD_3, P1.7/TxD_3]大陆本土宏晶STC姚永平独立创新设计，

请不要再抄袭我们的设计、规格和管脚排列，再抄袭就很无...

可编程时钟输出功能(对内部系统时钟或外部管脚的时钟输入进行时钟分频输出)：$\textcircled{1}$ T0在P3.5输出时钟； $\textcircled{2}$ T1在P3.4输出时钟； $\textcircled{3}$ T2在P3.0输出时钟，以上3个定时器/计数器输出时钟均可1~65536级分频输出； $\textcircled{4}$ 内部主时钟在P5.4/MCLKO对外输出时钟(STC15系列8-pin单片机的主时钟在P3.4/MCLKO对外输出时钟)

超高速双串口/UIART 两个完全独立的高速异步串行通信端口分时切换可当5组串口使用

高速同步串行通信接口●

硬件看门狗(WDT)●

先进的指令集结构，兼容普通8051指令集，有硬件乘法/除法指令●

通用I/O口(42/38/30/26/18个)�，复位后�为：准双�向口/�弱上�拉(8051传统I/O口)●可设置四种模式：准双向口/弱上拉， 强��推挽 /强上��拉， 仅�为输入/高���阻，开 漏每个I/O口驱动能力均可达到20mA，但整个芯片最大不要超过120mA

如果I/O口不够用可以用3根普通I/O口线外接74HC595(¥0.21元)来扩展I/O口，并可多芯片级联扩展几十个I/O口，还可用A/D作按键扫描来节省I/O口

# 选择宏晶•STC15F2K60S2系列单片机理由：

片内大容量2048字节SRAM★

无法解密，宏晶第八代加密技术，现悬赏10万元人民币请专家帮忙查找加密有无漏洞★

★ 超强抗干扰：

1.高抗静电(ESD保护)整机轻松过2万伏静电测试

2.轻松过4kV快速脉冲干扰(EFT测试)

3.宽电压，不怕电源抖动

4.宽温度范围，-40℃~+85℃

大幅降低 ，内部可配置时钟，1个时钟/机器周期，★

可用低频时钟----出口欧美的有力保证

超低功耗：★

1.掉电模式:外部中断唤醒功耗

2.空闲 模式: 典型功耗<1mA,

3.正常工作模式:4mA ~ 6mA

4.掉由模式可中外部中断或内部掉由晚醒专用定时器唤醒、适用于由池供电系统、如水表、气表等

在系统可仿真� �统 ，无需专用编程器,无需专用 � �★

可送USB型联机/脱机下载烧录工具STC-U7(人民币100元),1万片/人/天★

# STC micro TM

# 宏 晶 科 技

# 超强抗干扰， 无法解密

8051单片机全球第一品牌，全球最大的8051单片机设计公司

全部中国大陆本土独立自主知识产权；品质保证：TSMC上海制造

www.STCMCU.com 

www.GXWMCU.com 

南通 Tel: 0513-5501 2928 5501 2929

深圳 Tel: 0755-8294 8411 8294 8412

# STC15W1K16S 系列 1T 8051 单片机，宽电压，超高速串行口，比较器

不需外部晶振的单片机不需外部复位的单片机

# 送仿真器

全球第一款真正意义上的单片机ISP/IAP技术全球领导者

采用宏晶第九代加密技术，现悬赏20万元人民币

请专家帮忙查找STC15W201S系列单片机加密有无漏洞

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d66b00e29184746ba581204e175b5e036d788f9852f14d5c497768ee87989bf1.jpg)


# STC15W201S系列是目前全球抗干扰最强的Flash型单片机

现悬赏20万元人民币寻找比STC15W201S系列抗干扰更强的Flash型单片机

<table><tr><td rowspan="2">型号</td><td rowspan="2">工作电压(V)</td><td rowspan="2">Flash存储器byte</td><td rowspan="2">大容量S RAM字节</td><td rowspan="2">串行口并行掉电唤醒</td><td rowspan="2">普通定时器计数器TO-T2外部管脚也能掉电唤醒</td><td rowspan="2">CCP PWM可当外部中断可掉电唤醒</td><td rowspan="2">标准外部中断支持掉电唤醒</td><td rowspan="2">A/D(3路PWM可当3路D/A使用)</td><td rowspan="2">比较器(可当AD或RAM)</td><td rowspan="2">EEPROM</td><td rowspan="2">内部低序检测中并列掉电</td><td rowspan="2">内部位可变位模压</td><td rowspan="2">看片机</td><td rowspan="2">是否支持RS485下载</td><td colspan="3">所有封装LQFP44/PDP40LQFP32SOP28/SKDP28TSSOP2SOP16/DIP16</td><td></td><td></td><td></td><td></td><td></td></tr><tr><td colspan="3">封装价格(RMB ¥)</td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>STC15W201S</td><td>2.4-5.5</td><td>1K</td><td>256</td><td>1</td><td>T0/T2</td><td>-</td><td>有</td><td>5</td><td>-</td><td>有</td><td>4K</td><td>有</td><td>16级</td><td>有</td><td>是</td><td>¥1.3</td><td>¥1.4</td><td>¥1.6</td><td>-</td><td>-</td><td>-</td><td></td></tr><tr><td>STC15W202S</td><td>2.4-5.5</td><td>2K</td><td>256</td><td>1</td><td>T0/T2</td><td>-</td><td>有</td><td>5</td><td>-</td><td>有</td><td>3K</td><td>有</td><td>16级</td><td>有</td><td>是</td><td>¥1.4</td><td>¥1.5</td><td>¥1.7</td><td>-</td><td>-</td><td>-</td><td></td></tr><tr><td>STC15W203S</td><td>2.4-5.5</td><td>3K</td><td>256</td><td>1</td><td>T0/T2</td><td>-</td><td>有</td><td>5</td><td>-</td><td>有</td><td>2K</td><td>有</td><td>16级</td><td>有</td><td>是</td><td>¥1.5</td><td>¥1.6</td><td>¥1.8</td><td>-</td><td>-</td><td>-</td><td></td></tr><tr><td>STC15W204S</td><td>2.4-5.5</td><td>4K</td><td>256</td><td>1</td><td>T0/T2</td><td>-</td><td>有</td><td>5</td><td>-</td><td>有</td><td>1K</td><td>有</td><td>16级</td><td>有</td><td>是</td><td>¥1.6</td><td>¥1.7</td><td>¥1.9</td><td>-</td><td>-</td><td>-</td><td></td></tr><tr><td>IAP15W205S</td><td>2.4-5.5</td><td>5K</td><td>256</td><td>1</td><td>T0/T2</td><td>-</td><td>有</td><td>5</td><td>-</td><td>有</td><td>1AP</td><td>有</td><td>16级</td><td>有</td><td>是</td><td>¥1.6</td><td>¥1.7</td><td>¥1.9</td><td>-</td><td>-</td><td>-</td><td></td></tr><tr><td rowspan="4">IRC15W207S固定使用内部24MHz时钟</td><td rowspan="4">2.4-5.5</td><td rowspan="4">7.5K</td><td rowspan="4">256</td><td rowspan="4">1</td><td rowspan="4">T0/T2</td><td rowspan="4">-</td><td rowspan="4">有</td><td rowspan="4">5</td><td rowspan="4">-</td><td rowspan="4">有</td><td rowspan="4">1AP</td><td rowspan="4">有</td><td rowspan="4">固定</td><td rowspan="4">有</td><td rowspan="4">无</td><td>¥1.6</td><td>¥1.7</td><td>¥1.9</td><td>-</td><td>-</td><td>-</td><td></td></tr><tr><td colspan="6">用户可将用户程序区的程序/Flash当EEPROM使用</td><td></td></tr><tr><td colspan="6">用户可将用户程序区的程序/Flash当EEPROM使用</td><td></td></tr><tr><td colspan="6">SOP28/SKDP28/FP32P32D/PQP40/FPQ44</td><td></td></tr><tr><td colspan="22">STC15W408S系列单片机选型价格一览表,供货中</td><td></td></tr><tr><td>STC15W404S</td><td>2.4-5.5</td><td>4K</td><td>512</td><td>1</td><td>有</td><td>3</td><td>-</td><td>有</td><td>5</td><td>-</td><td>有</td><td>9K</td><td>有</td><td>16级</td><td>有</td><td>是</td><td>¥2.3</td><td>¥2.5</td><td>¥2.4</td><td>¥3.0</td><td>¥2.5</td><td></td></tr><tr><td>STC15W408S</td><td>2.4-5.5</td><td>8K</td><td>512</td><td>1</td><td>有</td><td>3</td><td>-</td><td>有</td><td>5</td><td>-</td><td>有</td><td>5K</td><td>有</td><td>16级</td><td>有</td><td>是</td><td>¥2.5</td><td>¥2.7</td><td>¥2.6</td><td>¥3.0</td><td>¥2.7</td><td></td></tr><tr><td>STC15W410S</td><td>2.4-5.5</td><td>10K</td><td>512</td><td>1</td><td>有</td><td>3</td><td>-</td><td>有</td><td>5</td><td>-</td><td>有</td><td>3K</td><td>有</td><td>16级</td><td>有</td><td>是</td><td>¥2.6</td><td>¥2.8</td><td>¥2.7</td><td>¥3.3</td><td>¥2.8</td><td></td></tr><tr><td rowspan="2">IAP15W413S</td><td rowspan="2">2.4-5.5</td><td rowspan="2">13K</td><td rowspan="2">512</td><td rowspan="2">1</td><td rowspan="2">有</td><td rowspan="2">3</td><td rowspan="2">-</td><td rowspan="2">有</td><td rowspan="2">5</td><td rowspan="2">-</td><td rowspan="2">有</td><td rowspan="2">1AP</td><td rowspan="2">有</td><td rowspan="2">16级</td><td rowspan="2">有</td><td rowspan="2">是</td><td rowspan="2" colspan="6">用户可将用户程序区的程序/Flash当EEPROM使用</td></tr><tr></tr><tr><td rowspan="19">IRC15W415S固定使用内部24MHz时钟</td><td rowspan="19">2.4-5.5</td><td rowspan="18">15.5K</td><td rowspan="18">512</td><td rowspan="18">1</td><td rowspan="18">有</td><td rowspan="18">3</td><td rowspan="18">-</td><td rowspan="18">有</td><td rowspan="18">5</td><td rowspan="18">-</td><td rowspan="18">有</td><td rowspan="18">1AP</td><td rowspan="18">有</td><td rowspan="18">固定</td><td rowspan="18">有</td><td rowspan="18">无</td><td rowspan="18">¥2.6</td><td rowspan="18">¥2.8</td><td rowspan="18">¥2.7</td><td rowspan="18">¥3.3</td><td rowspan="13">¥2.8</td><td rowspan="5"></td></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr><td></td></tr><tr><td></td></tr><tr><td></td></tr><tr><td></td></tr><tr><td></td></tr><tr><td></td></tr><tr><td></td></tr><tr><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td colspan="20">STC15W1K16S系列单片机选型价格一览表,大批量供货中</td><td></td></tr><tr><td>STC15W1K16S</td><td>2.6-5.5</td><td>16K</td><td>1K</td><td>1</td><td>有</td><td>3</td><td>-</td><td>有</td><td>5</td><td>-</td><td>有</td><td>13K</td><td>有</td><td>16级</td><td>有</td><td>是</td><td>¥3.3</td><td>¥3.5</td><td>¥3.4</td><td>¥4.0</td><td>¥3.5</td><td></td></tr><tr><td>STC15W1K24S</td><td>2.6-5.5</td><td>24K</td><td>1K</td><td>1</td><td>有</td><td>3</td><td>-</td><td>有</td><td>5</td><td>-</td><td>有</td><td>5K</td><td>有</td><td>16级</td><td>有</td><td>是</td><td>¥3.6</td><td>¥3.8</td><td>¥3.7</td><td>¥4.3</td><td>¥3.8</td><td></td></tr><tr><td>IAP15W1K29S</td><td>2.6-5.5</td><td>29K</td><td>1K</td><td>1</td><td>有</td><td>3</td><td>-</td><td>有</td><td>5</td><td>-</td><td>有</td><td>IAP</td><td>有</td><td>16级</td><td>有</td><td>是</td><td>¥3.6</td><td>¥3.6</td><td>¥3.8</td><td>¥3.7</td><td>¥4.3</td><td>¥3.8</td></tr><tr><td rowspan="3">IRC15W1K31S固定使用内部24MHz时钟</td><td rowspan="3">2.6-5.5</td><td rowspan="3">31.5K</td><td rowspan="3">1K</td><td rowspan="3">1</td><td rowspan="3">有</td><td rowspan="3">3</td><td rowspan="3">-</td><td rowspan="3">有</td><td rowspan="3">5</td><td rowspan="3">-</td><td rowspan="3">有</td><td rowspan="3">IAP</td><td rowspan="3">有</td><td rowspan="3">固定</td><td rowspan="3">有</td><td rowspan="3">无</td><td rowspan="3">¥3.6</td><td>¥3.8</td><td>¥3.7</td><td>¥4.3</td><td>¥3.8</td><td></td></tr><tr><td colspan="5">用户可将用户程序区的程序/Flash当EEPROM使用</td></tr><tr><td colspan="5">用户可将用户程序区的程序/Flash当EEPROM使用</td></tr></table>


以上单价为10K/M起定量，量小每片需加0.1元，以上价格运费由客户承担，零售10片起，如对价格不满，可来电要求降



上表中以IRC开头的单片机固定使用内部24MHz时钟，且其内部复位门槛电压固定，同时不支持"程序加蜜后传输"功能（以STC及IAR开头



的单片机支持"程序加密后传输"功能），无复位管脚，其P5.4不可当复位管脚RST使用，且P3.2/P3.3与下载无关



程序加密后传输，程序押有考产品出厂时奖源程序和加密组匙一起修录MCU中，以后需要升级款件时，就可将程序加密后更用"发布项目



程序有能，生成一个用户自己界面的日有一个升级按钮的，简单易用的升级软件，给最终使用考自己升级而栏载不


到您的原始程序。

大陆本土宏晶STC姚永平独立创新设计，

请不要再抄袭我们的设计、规格和管脚

排列，再抄袭就很无...

/RxD_3/P1.6 D O 20 P3.5/T1/T0CLKO TxD_3/P1.7 10 IP2 19 P3.4/T0/T1CLKO 1112O/RST/P5.4Vcc 18 P3.3/INT1 Vcc 17 P3.2/INT0 CMP+/P5.5 P3.1/TxD/T2 Gnd 14 15 P3.0/RxD/INT4/T2CLKO 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/5d0bbc296d60179ac0761238919db34ab15a9dfdebd2273894288be8c966ca8c.jpg)


硬件看门狗(WDT)●

超高速异步串行通信端口 ,分时切换可当 组串口使用 高速同步串行通信接口

先进的指令集结构，兼容普通8051指令集，有硬件乘法/除法指令●

通用I/O口(42/38/30/26/18个)�，复位后�为：准双�向口/�弱上�拉(8051传统I/O口)●

可设置四种模式：准双向口/弱上拉， 强��推挽 /强上��拉， 仅�为输入/高���阻，开 漏

每个I/O口驱动能力均可达到20mA，但整个芯片最大不要超过120mA

如果I/O口不够用可以用3根普通I/O口线外接74HC595(¥0.21元)来扩展I/O口，并可多芯片●

级联扩展几十个 口，还可用 作按键扫描来节省 口

# 选择宏晶•STC15W1K16S系列单片机理由：

# 宏晶•STC15W1K16S系列主要性能：

. 大容量1024字节片内RAM数据存储器

高速： 个时钟/机器周期，增强型 内核，速度比 � 快 ～ 倍

速度也 STC早期的1T系列单片机(如STC12/11/10系列)的速度快20%

宽电压： ～ ●

低功耗设计：低速模式，��模式，掉电模式 可由外部中断或内部掉电唤醒定时器●

. 不需外部复位的单片机，ISP编程时16级复位门槛电压可选，内置高可靠复位电路

不需外部晶振的单片机，ISP编程时内部时钟从 可设 � � ： ～

内部高精度R/C时钟(±0.3%)，±1%温飘(-40℃~+85℃)，常温下温飘±0.6%(-20℃~+65℃)

支持掉电唤醒的资源有：INT0/INT1(上升沿/下降沿中断均可), INT2 / INT3 / INT4(下降沿中断)；●

RxD/T0/T1/T2管脚；内部掉电唤醒专用定时器

16/24/29K/31.5K字节片内Flash程序存储器，擦写次数10万次以上●

大容量 功能,擦写次数 万次以上●

·ISP/IAP、在系统可编程/在应用可编程 无需编程器/仿直器

比较器，可当1路ADC使用，并可作掉电检测，支持外部管脚CMP+与外部管脚CMP-进行比较，可产生中断，并可在管脚CMPO上产生输出（可设置极性），也支持外部管脚CMP+与内部参考电压进行比较

3个16位可重装载定时器/计数器(T0/T1/T2，其中T0/T1兼容普通8051的定时器/计数器)，并都可实现可编程时钟输出，另外管脚 可将内部主时钟对外分频输出（÷1或÷2或÷4）

片内大容量 字节

无法解密，宏晶第九代加密技术，★

现悬赏20万元人民币请专家帮忙查找STC15W201S系列和STC15W1K16S系列加密有无漏洞

★ 超强抗干扰：

1.高抗静电(ESD保护)整机轻松过2万伏静电测试

3.宽电压，不怕电源抖动

2.轻松过4kV快速脉冲干扰(EFT测试)

4.宽温度范围，-40℃~+85℃

大幅降低 ，内部可配置时钟，1个时钟/机器周期，★

可用低频时钟----出口欧美的有力保证

超低功耗：★

1.掉电模式:外部中断唤醒功耗 <0.1uA

2.空闲 模式: 典型功耗<1mA,

3.正常工作模式:4mA ~ 6mA

4.掉电模式可由外部中断或内部掉电唤醒专用定时器唤醒��，适 用�于电�池供电系��统， 如�����水表、气表、便携设备等

★ 在系统可仿真� �统 ，无需专用编程器,无需专用 � �

可送USB型联机/脱机下载烧录工具STC-U7(人民币100元),1万片/人/天★

# STC micro TM

# 宏 晶 科 技

# 超强抗干扰， 无法解密

8051单片机全球第一品牌，全球最大的8051单片机设计公司

全部中国大陆本土独立自主知识产权；品质保证：TSMC上海制造

www.STCMCU.com 

www.GXWMCU.com 

南通 Tel: 0513-5501 2928 5501 2929

深圳 Tel: 0755-8294 8411 8294 8412

# 宏晶•STC15W408AS 系列 1T 8051 单片机，宽电压，高速A/D，比较器

不需外部晶振的单片机不需外部复位的单片机

# 送仿真器

全球第一款真正意义上的单片机ISP/IAP技术全球领导者

提供客制化IC设计服务

512 字节SRAM

4K/8K/13K/15.5K字节 Flash程序存储器

IA 内

统 INT2 仅可INT0

/INT3/INT4下降沿中断/INT1

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/03f5bd1abf839483b235dc17a9cd576f05a7af55b110a6db2d8dda4b81290d16.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/fda453d24382207ae67a1fe6202f90765cb4438b5e388bde42fa4a2dfc32b0f4.jpg)


建议用户将串口1设在[P3.6/RxD_2,P3.7/TxD_2]

<table><tr><td rowspan="3">型号</td><td rowspan="3">工作电压(V)</td><td rowspan="3">Flash程序存储器byte)</td><td rowspan="3">SRAM字节</td><td rowspan="3">串行口并行P1</td><td rowspan="3">串行口并行P1</td><td rowspan="3">普通定时器计数器T0/T2外部管脚也能掉电唤醒</td><td rowspan="3">CCP/PCAMPW</td><td rowspan="3">掉电频率专用电池唤醒</td><td rowspan="3">标准外部断电保持电池唤醒</td><td rowspan="3">A/D8路(3路PWM可当3路D/A使用)</td><td rowspan="3">比较器(可当1路ADC使用)</td><td rowspan="3">D</td><td></td><td rowspan="3">EEPROM</td><td rowspan="3">内部低压检测中断可掉电唤醒</td><td rowspan="3">内部复位(可选复位门极电压)</td><td rowspan="3">看门狗</td><td rowspan="3">程序加密后传输(防截)</td><td rowspan="3">是否支持RS485下载</td><td rowspan="3" colspan="7">所有封装SOP28/SKDP28/TSSOP28SOP20/DIP20/TSSOP20SOP16/DIP16</td><td></td><td></td></tr><tr><td></td><td colspan="7">部分封装价格(RMB Y)</td><td></td></tr><tr><td></td><td>SOP16</td><td>DIP16</td><td>SOP20</td><td>DIP20</td><td>TSSOP20</td><td>SOP28</td><td>SKDP28</td><td>TSSOP28</td></tr><tr><td colspan="28">STC15W40A0AS系列单片机选型价格一览表，已开始供货特别提示：3路CCP/PCA/PMN可当3路定时器使用</td><td></td></tr><tr><td>STC15W40A0AS 2.4-5.5</td><td>4K</td><td>512</td><td>1</td><td>有</td><td>2</td><td>3-ch</td><td>有</td><td>5</td><td>10-bit</td><td>有</td><td>1</td><td>9K</td><td>有</td><td>16级</td><td>有</td><td>有</td><td>是</td><td>¥1.99</td><td>¥2.20</td><td>¥2.20</td><td>¥2.40</td><td>¥2.30</td><td>¥2.50</td><td>¥2.70</td><td>¥2.70</td><td>¥2.70</td><td>¥2.60</td><td></td></tr><tr><td>STC15W40A0AS 2.4-5.5</td><td>8K</td><td>512</td><td>1</td><td>有</td><td>2</td><td>3-ch</td><td>有</td><td>5</td><td>10-bit</td><td>有</td><td>1</td><td>5K</td><td>有</td><td>16级</td><td>有</td><td>有</td><td>是</td><td>¥2.20</td><td>¥2.40</td><td>¥2.40</td><td>¥2.60</td><td>¥2.50</td><td>¥2.70</td><td>¥2.70</td><td>¥2.90</td><td>¥2.80</td><td></td><td></td></tr><tr><td>IAP15W40A0AS 2.4-5.5</td><td>13K</td><td>512</td><td>1</td><td>有</td><td>2</td><td>3-ch</td><td>有</td><td>5</td><td>10-bit</td><td>有</td><td>1</td><td>IAP</td><td>有</td><td>16级</td><td>有</td><td>有</td><td>是</td><td>¥2.30</td><td>¥2.50</td><td>¥2.50</td><td>¥2.70</td><td>¥2.60</td><td>¥2.80</td><td>¥3.00</td><td>¥2.90</td><td></td><td></td><td></td></tr><tr><td rowspan="3">IRC15W415AS使用内部24MHz时钟或外部版板</td><td rowspan="3">2.4-5.5</td><td rowspan="3">15.5K</td><td rowspan="3">512</td><td rowspan="3">1</td><td rowspan="3">有</td><td rowspan="3">2</td><td rowspan="3">3-ch</td><td rowspan="3">有</td><td rowspan="3">5</td><td rowspan="3">10-bit</td><td rowspan="3">有</td><td rowspan="3">1</td><td rowspan="3">IAP</td><td rowspan="3">有</td><td rowspan="3">固定</td><td rowspan="3">有</td><td rowspan="3">无</td><td rowspan="3">否</td><td rowspan="3">¥2.30</td><td rowspan="3">¥2.50</td><td>¥2.50</td><td>¥2.70</td><td>¥2.60</td><td>¥2.80</td><td>¥3.00</td><td>¥2.90</td><td></td><td></td></tr><tr><td colspan="7">用户可将用户程序程序的程序Flash当EEPROM使用</td><td></td></tr><tr><td colspan="7">用户可将用户程序程序的程序Flash当EEPROM使用</td><td></td></tr></table>


以上单价为10K/M起定量，量小每片需加0.1元，以上价格运费由客户承担，需售10片起，如对价格不满，可来电要求降价



上表中以I�RC�开头的单片机固定使用内部24M��Hz时钟或外部晶振�，且其内部复位门槛电压固定�，同时不支持"程序加密后传输"功能



(以STC及IAP开头的单片机支持"程序加密后传输"功能),无复位管脚，其P5.4不可当复位管脚RST使用，且P3.2/P3.3与下载无关。


程序加密后传输：程序拥有者产品出厂时将源程序和加密钥匙一起烧录MCU中，以后需要升级软件时，就可将程序加密后再用

"发布项目程序"功能，生成一个用户自己界面的只有一个升级按钮的简单易用的升级软件，给最终使用者

自己升级，而拦截不到您的原始程序。

# 宏晶•STC15W408AS系列主要性能：

● 512 RAM数据存储器

. 高速：1个时钟/机器周期，增强型8051内核，速度比 �8051快7～12倍速度也 STC早期的1T系列单片机(如STC12/11/10系列)的速度快20%

宽电压：2.4V ～ 5.5V●

低功耗设计：低速模式，��模式，掉电模式(可由外部中断或内部掉电唤醒定时器 )●

● 不需外部复位的单片机，ISP编程时16级复位门槛电压可选，内置高可靠复位电路

不需外部晶振的单片机，ISP编程时内部时钟从5MHz~35MHz可设 � � 8051：60～420MHz)内部高精度R/C时钟 $\cdot$ )，±1%温飘(-40℃~+85℃)，常温下温飘±0.6%(-20℃~+65℃)

支持掉电唤醒的资源有：INT0/INT1(上升沿/下降沿中断均可), INT2 /INT3/INT4(下降沿中断)；●

管脚；内部掉电唤醒专用定时器

4K/8K/13K/15.5K字节片内Flash程序存储器，擦写次数10万次以上●

大容量 EEPROM功能,擦写次数10万次以上●

ISP/IAP，在系统可编程/在应用可编程,无需编程器/仿真器●

高速ADC，8通道10位，速度可达30万次/秒�，3路PWM还可当3路D/A使用

● 比较器，可当1路ADC使用，并可作掉电检测，支持外部管脚CMP+与外部管脚CMP-进行比较，可产生中断，并可在管脚CMPO上产生输出(可设置极性)，也支持外部管脚CMP+与内部参考电压进行比较

3通道捕获/比较单元(CCP/PCA/PWM)●

-也可用来再实现3路D/A或3个定时器或3个外部中断(支持上升沿/下降沿中断)

5个定时器，2个16位可重装载定时器/计数器(T0/T2，其中T0兼容普通8051的定时器/计数器)，●并都可实现可编程时钟输出，另外管脚MCLKO可将内部主时钟对外分频输出(÷1或 $\div 2$ 2或 $\div 4 )$ )，3路CCP/PCA可再实现3个定时器

可编程时钟输出功能(对内部系统时钟或外部管脚的时钟输入进行时钟分频输出)：$\textcircled{1}$ T0在P3.5输出时钟； $\textcircled{2}$ T2在P3.0输出时钟，以上2个定时器/计数器输出时钟均可1~65536级分频输出； $\textcircled{3}$ 内部主时钟在P5.4/MCLKO对外输出时钟(STC15系列8-pin单片机的主时钟在P3.4/MCLKO对外输出时钟)

硬件看门狗( )●

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/724d013e49dfb38832afd49e35ae130021fb2beea1be5f72ec3062b6669edaab.jpg)


超高速异步串行通信端口/UART,分时切换可当3组串口使用

SPI高速同步串行通信接口●

先进的指令集结构，兼容普通8051指令集，有硬件乘法/除法指令●

通用I/O口(26/18/14个)�，复位后�为：准双�向口/�弱上�拉(8051传统I/O口)可设置四种模式：准双向口/弱上拉， 强��推挽 /强上��拉， 仅�为输入/高���阻，开 漏每个I/O口驱动能力均可达到20mA， 但整个芯片最大不要超过120mA

# 选择宏晶•STC15W408AS系列单片机理由：

无法解密，宏晶第九代加密技术，现悬赏 万元人民币请专家帮忙查找加密有无漏洞★

★ 超强抗干扰：

1.高抗静电(ESD保护)整机轻松过2万伏静电测试

2.轻松过4kV快速脉冲干扰(EFT测试)

3.宽电压，不怕电源抖动

4.宽温度范围，-40℃~+85℃

大幅降低 ，内部可配置时钟，1个时钟/机器周期，★

可用低频时钟----出口欧美的有力保证

超低功耗：★

1.掉电模式:外部中断唤醒功耗 <0.1uA

2.空闲 模式: 典型功耗<1mA,

3.正常工作模式:4mA ~ 6mA

4.掉电模式可由外部中断或内部掉电唤醒专用定时器唤醒��，适 用�于电�池供电系��统， 如��水表、气表、 便携设备等

在系统可仿真� �统 ，无需专用编程器,无需专用 � �★

可送USB型联机/脱机下载烧录工具STC-U7(人民币100元),1万片/人/天★

# STC micro TM

# 宏 晶 科 技

# 超强抗干扰， 无法解密

8051单片机全球第一品牌，全球最大的8051单片机设计公司

全部中国大陆本土独立自主知识产权；品质保证：TSMC上海制造

www.STCMCU.com 

www.GXWMCU.com 

南通 Tel: 0513-5501 2928 5501 2929

深圳 Tel: 0755-8294 8411 8294 8412

# 宏晶•STC15F101W系列新一代 1T 8051 单片机，高速，高可靠，超低价

不需外部晶振的单片机

不需外部复位的单片机

# 送仿真器

全球第一款真正意义上的单片机

ISP/IAP技术全球领导者

采用宏晶第八代加密技术，现悬赏10万元人民币请专家帮忙查找加密有无漏洞

提供客制化

IC设计服务

128 字节SRAM

1/2/3/4/5/7K字节 Flash程序存储器

IAP 

内置系统ISP监控程序

INT2/INT3/INT4仅可下降沿中断INT0/INT1上升沿/下降沿中

E2 PROM Data Flash 

看门狗

集成高精度R/C时钟±1%温飘-40℃ ~ +85℃

集成MAX810专用复位电路

ISP编程时可设置8级复位门槛电压

1T 

8 

051 微处理器 1微处理器

STC 

超低功耗，超低价 超低功耗，超低价速（0-35M)， (0-35M)，高可靠 高可靠

抗干扰，无法解密

内置高精准时钟(ISP编程时5~35MHz可任意设置)内置高可靠复位电路(8级复位门槛电压可设置)

掉电模式：<0.2uA，可由外中断或专用定时器唤醒 断或专用定时器唤醒

可由[P3.0,P3.1]结合定时器软件实现串口

定时器0/定时器2掉电唤醒专用定时器

1组

并行端

(无P3.6/P3.7口)

共6个I/O

提升的是性能降低的是成本

<table><tr><td rowspan="2">型号</td><td rowspan="2">工作电压(V)</td><td rowspan="2">Flash程序存储器byte</td><td rowspan="2">SRAM字节</td><td rowspan="2">EEPROM</td><td rowspan="2">串行口</td><td rowspan="2">普通定时器计数器T0/T2外部管脚也能掉电唤醒</td><td rowspan="2">CCP PCA PWM D/A</td><td rowspan="2">掉电唤醒定时器</td><td rowspan="2">标准外部中断支持掉电唤醒</td><td rowspan="2">A/D 8路</td><td rowspan="2">看门狗</td><td rowspan="2">内部低压检测中断</td><td rowspan="2">内部复位(可选复位门槛电压)</td><td rowspan="2">程序加密后传输拦截</td><td rowspan="2">是否支持RS485下载</td><td colspan="3">封装8-PinSOP-8/DIP-8/DFN-8(6个I/O1)价格(RMB ¥)</td><td></td></tr><tr><td>SOP-8</td><td>DIP-8</td><td>DFN-8</td><td></td></tr><tr><td colspan="18">STC15F101W系列单片机选型价格一览表,另有STC15L系列(工作电压2.4V-3.6V)串行口功能可由P3.0/INT4,P3.1结合定时器实现此系自到2014年4月版已开始大批量供货</td><td></td><td></td></tr><tr><td>STC15F100W</td><td>5.5-3.8</td><td>512</td><td>128</td><td>无</td><td>无</td><td>无</td><td>2</td><td>无</td><td>有</td><td>5个</td><td>无</td><td>有</td><td>有</td><td>8级</td><td>有</td><td>是</td><td>¥0.99</td><td>无</td><td></td></tr><tr><td>STC15F101W</td><td>5.5-3.8</td><td>1K</td><td>128</td><td>4K</td><td>无</td><td>无</td><td>2</td><td>无</td><td>有</td><td>5个</td><td>无</td><td>有</td><td>有</td><td>8级</td><td>有</td><td>是</td><td>¥1.2</td><td>无</td><td></td></tr><tr><td>STC15F102W</td><td>5.5-3.8</td><td>2K</td><td>128</td><td>3K</td><td>无</td><td>无</td><td>2</td><td>无</td><td>有</td><td>5个</td><td>无</td><td>有</td><td>有</td><td>8级</td><td>有</td><td>是</td><td>¥1.3</td><td>¥1.5</td><td></td></tr><tr><td>STC15F104W</td><td>5.5-3.8</td><td>4K</td><td>128</td><td>1K</td><td>无</td><td>无</td><td>2</td><td>无</td><td>有</td><td>5个</td><td>无</td><td>有</td><td>有</td><td>8级</td><td>有</td><td>是</td><td>¥1.4</td><td>¥1.6</td><td>¥1.5</td></tr><tr><td>IAP15F105W</td><td>5.5-3.8</td><td>5K</td><td>128</td><td>IAP</td><td>无</td><td>无</td><td>2</td><td>无</td><td>有</td><td>5个</td><td>无</td><td>有</td><td>有</td><td>8级</td><td>有</td><td>是</td><td>¥1.4</td><td>¥1.6</td><td>¥1.5</td></tr><tr><td rowspan="2">IRC15F107W使用内部24MHz时钟或外部晶振</td><td rowspan="2">5.5-3.8</td><td rowspan="2">7K</td><td rowspan="2">128</td><td rowspan="2">IAP</td><td rowspan="2">无</td><td rowspan="2">无</td><td rowspan="2">2</td><td rowspan="2">无</td><td rowspan="2">有</td><td rowspan="2">5个</td><td rowspan="2">无</td><td rowspan="2">有</td><td rowspan="2">有</td><td rowspan="2">固定</td><td rowspan="2">无</td><td rowspan="2">否</td><td>¥1.4</td><td>¥1.6</td><td></td></tr><tr><td colspan="3">用户可将用户程序区的程序FLASH当EEPROM使用</td></tr></table>


以上单价为10K/M起定量，量小每片需加0.1元，以上价格运费由客户承担，零售10片起，如对价格不满，可来电要求降



上表中以I�RC�开头的单片机内部复位门槛电压固定�，不支持"程序加密后传输"功能（以STC�及I�AP�开头的单片机支持"程序加密后传输"功能），无复位管脚，其P5.4不可当复位管脚RST使用，且P3.2/P3.3与下载无关。


程序加密后传输：程序拥有者产品出厂时将源程序和加密钥匙一起烧录MCU中，以后需要升级软件时，就可将程序加密后再用"发布项目程序"功能，生成一个用户自己界面的只有一个升级按钮的简单易用的升级软件，给最终使用者自己升级，而拦截不到您的原始程序。

# 宏晶•STC15F101W系列主要性能：

高速：1个时钟/机器周期，增强型8051内核，速度比普通8051快6～12倍速度也 STC早期的1T系列单片机(如STC12/11/10系列)的速度快20%

宽电压：● $5 . 5 \sim 3 . 8 \mathrm { V }$ ，2.4～3.6V(STC15L101W系列)

低功耗设计：低速模式，��模式，掉电模式(可由外部中断或内部掉电唤醒定时器 )●

不需外部复位的单片机，ISP编程时8级复位门槛电压可选，内置高可靠复位电路●

不需外部晶振的单片机，ISP编程时内部时钟从5MHz~35MHz可设 � �8051：60～420MHz)内部高精度R/C时钟 $\cdot$ )，±1%温飘 $\_$ )，常温下温飘±0.6%(-20℃~+65℃)

支持掉电唤醒的资源有：INT0/INT1(上升沿/下降沿中断均可), INT2/INT3/INT4(下降沿●中断)；T0/T2管脚；内部掉电唤醒专用定时器

1K/2K/3K/4K/5K/7K字节片内Flash程序存储器，擦写次数10万次以上●

128字节片内RAM数据存储器●

片内EEPROM功能,擦写次数10万次以上●

ISP/IAP，在系统可编程/在应用可编程,无需编程器/仿真器●

2个16位可重装载定时器T0/T2，并可实现时钟输出功能，另外管脚MCLKO可将内部主时钟对外分频输出（÷1或÷2或÷4）

可编程时钟输出功能(对内部系统时钟或外部管脚的时钟输入进行时钟分频输出)：●

$\textcircled{1}$ T0在P3.5输出时钟； $\textcircled{2}$ T2在P3.0输出时钟； $\textcircled{3}$ 内部主时钟在P3.4/MCLKO对外输出时钟(STC15系列8-pin以上单片机的主时钟在P5.4/MCLKO对外输出时钟)

硬件看门狗(WDT)●

串口功能可由[P3.0/INT4, P3.1]结合定时器实现●

先进的指令集结构，兼容普通8051指令集，有硬件乘法/除法指令●

STC15F101W系列，已开始大批量供货，RMB1.2元起(STC15F101W)

全部175℃8小时高温烘烤

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/9dadff3a9ffe7818eced1b1df43b7d5e3b82f890d202a3bd9f5bc320c8f1f448.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/bc3268ca0a7ba1d6a68103c8d66b380b19a7dfc3386f8fe5c2354e1519ec3388.jpg)



SOP-8/DIP-8/DFN-8


封装形式：

SOP-8/DIP-8/DFN-8 

强烈推荐选择SOP-8贴片封装

注意：STC15F101W系列与STC15F104E系列是不同的两个系列，STC15F101W系列采用STC-Y5超高速CPU内核，在相同的时钟频率下，速度比STC早期的1T系列单片机(如STC12/STC11/STC10系列)的速度快20%，而STC104E系列采用的是STC-Y3 CPU内核，速度没有STC15F101W系列的速度快。

每片单片机具有

全球唯一身份证号码(ID号)

无法解密，加密坚不可摧

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d087684e4d7896d876776969772298c5843031700dfe1effa3f6dcd4d317101a.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/245e0e47284eb4d3c1f9a7b0f4da29bd9c6a74f40cc8f6d47ed441f5341f6ed8.jpg)


大陆本土宏晶STC姚永平独立创新设计，

请不要再抄袭我们的设计、规格和管脚排列，再抄袭就很无..

通用I/O口(8个)�，复位后�为：准双�向口/�弱上�拉(8051传统I/O口)●

可设置四种模式：准双向口/弱上拉， 强��推挽 /强上��拉， 仅�为输入/高���阻，开 漏每个I/O口驱动能力均可达到20mA，但整个芯片最大不要超过90mA

如果I/O口不够用可以用3根普通I/O口线外接74HC595(¥0.21元)来扩展I/O口，并可多芯片级联扩展几十个I/O口，还可用A/D作按键扫描来节省I/O口

# 选择宏晶•STC15F101W系列单片机理由：

不需外部晶振的单片机，内部集成高精度R/C时钟★ $( \pm 0 . 3 \% )$ )，

±1%温飘(-40℃~+85℃)，常温下温飘±0.6%(-20℃~+65℃)

不需外部复位的单片机，内部集成高可靠复位电路，★

编程时 级复位门槛电压可选，当然也可以继续用外部复位电路

$\star$ 无法解密，宏晶第八代加密技术,现悬赏10万元人民币请专家帮忙查找加密有无漏洞

超强抗干扰：★

1.高抗静电( 保护)整机轻松过2万伏静电测试

2.轻松过 快速脉冲干扰( 测试)

3.宽电压，不怕电源抖动

4.宽温度范围，-40℃~+85℃

大幅降低EMI，内部可配置时钟，1个时钟/机器周期，可用低频时钟★出口欧美的有力保证

超低功耗：★

1.掉电模式：外部中断唤醍功耗 $< 0 . 2 { \mathrm { u A } }$ 

2.空闲 模式: 典型功耗 <1mA,

3.正常工作模式:

4.掉电模式可由外部中断唤醒��，适 用�于电�池供电系��统， 如������水表、气表、 便携设备�等

在系统可仿真� �统 ，无需专用编程器,无需专用 � �★

可送 �B型联机/脱机下载烧录工具 �(人民币100元★

# STC micro TM

# 宏 晶 科 技

# 超强抗干扰， 超级加密

8051单片机全球第一品牌，全球最大的8051单片机设计公司全部中国大陆本土独立自主知识产权；品质保证：TSMC上海制造

官方网站： www.STCMCU.com

南通 Tel: 0513-5501 2928 5501 2929深圳 Tel: 0755-8294 8411 8294 8412

# STC12C5A60S2系列 1T 8051 单片机，2-3个串口，2路CCP/PCA/PWM，高速A/D

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/22f885821cb417f863e4e4196392b2fed8b2c2314ae15dd34ac66e6c2d4ec6ea.jpg)


<table><tr><td rowspan="3">型号</td><td rowspan="3">工作电压(V)</td><td rowspan="3">Flash程序存储器byte)</td><td rowspan="3">SRAM字节</td><td rowspan="3">EEPROM</td><td rowspan="3">串行口并掉电唤醒</td><td rowspan="3">SPP</td><td rowspan="3">普通定时器计数器T0/T1外部管脚也能掉电唤醒</td><td rowspan="3">CCPPCA PWM可当外部中断可掉电唤醒</td><td rowspan="3">D波特率发生器</td><td rowspan="3">D独立片体</td><td rowspan="3">A/D8路25万次每秒(2路PWM还可当2路D/A使用)</td><td rowspan="3">看门狗</td><td rowspan="3">内置复位</td><td rowspan="3">外部实时低压检测中断</td><td rowspan="3">外部复位(可调门槛电压)</td><td>LQF48LQF44PDIP40不推荐PLCC44</td><td></td></tr><tr><td>部分封装价格(RMBV)</td><td></td></tr><tr><td>LQFP44 PDIP40</td><td></td></tr><tr><td colspan="17">STC12CSA60S2系列单片机选型价格一览表</td><td></td></tr><tr><td colspan="17">特别提醒:2路CCPPCA/PWM还可当2路定时器使用,另有STC12LE系列(工作电压2.1V-3.6V)</td><td></td></tr><tr><td>STC12CSA08S2</td><td>5.5-4.0</td><td>8K</td><td>1280</td><td>53K</td><td>2-3</td><td>有</td><td>2</td><td>2-ch</td><td>有</td><td>2</td><td>10位</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥4.5</td><td>¥5.0</td></tr><tr><td>STC12CSA16S2</td><td>5.5-4.0</td><td>16K</td><td>1280</td><td>45K</td><td>2-3</td><td>有</td><td>2</td><td>2-ch</td><td>有</td><td>2</td><td>10位</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥4.7</td><td>¥5.2</td></tr><tr><td>STC12CSA32S2</td><td>5.5-4.0</td><td>32K</td><td>1280</td><td>29K</td><td>2-3</td><td>有</td><td>2</td><td>2-ch</td><td>有</td><td>2</td><td>10位</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥5.49</td><td>¥5.99</td></tr><tr><td>STC12CSA40S2</td><td>5.5-4.0</td><td>40K</td><td>1280</td><td>21K</td><td>2-3</td><td>有</td><td>2</td><td>2-ch</td><td>有</td><td>2</td><td>10位</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥5.99</td><td>¥6.49</td></tr><tr><td>STC12CSA48S2</td><td>5.5-4.0</td><td>48K</td><td>1280</td><td>13K</td><td>2-3</td><td>有</td><td>2</td><td>2-ch</td><td>有</td><td>2</td><td>10位</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥5.99</td><td>¥6.49</td></tr><tr><td>STC12CSA56S2</td><td>5.5-4.0</td><td>56K</td><td>1280</td><td>5K</td><td>2-3</td><td>有</td><td>2</td><td>2-ch</td><td>有</td><td>2</td><td>10位</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥5.99</td><td>¥6.49</td></tr><tr><td>STC12CSA60S2</td><td>5.5-4.0</td><td>60K</td><td>1280</td><td>1K</td><td>2-3</td><td>有</td><td>2</td><td>2-ch</td><td>有</td><td>2</td><td>10位</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥5.99</td><td>¥6.49</td></tr><tr><td>IAP12CSA62S2</td><td>5.5-4.0</td><td>62K</td><td>1280</td><td>IAP</td><td>2-3</td><td>有</td><td>2</td><td>2-ch</td><td>有</td><td>2</td><td>10位</td><td>有</td><td>有</td><td>有</td><td>有</td><td colspan="2">用户可将用户程序的程序Flash当EEPROM使用</td></tr></table>


以上单价为200K/M起定量，以上价格运费由客户承担，零售10片起�， �可来电要求降


# 宏晶•STC12C5A60S2系列主要性能：

高速： 个时钟/机器周期，增强型 内核，速度比普通 快 ～ 倍●

宽电压：● $5 . 5 \mathrm { \sim } 4 . 0 0 $ ，2.1～3.6V（STC12LE5A60S2系列）

增加第二复位功能脚/P4.6(高可靠复位，可调整复位门槛电压，频率<12MHz时，无需此功能)●

增加外部掉电检测电路/P4.6，可在掉电时，及 时将数据保存进EEPROM，正常工作时●无需操作

低功耗设计：��空闲 模式(可由�任意�一个中断唤醒)●

低功耗设计：掉电模式(可由外部中断唤醒)�， �●

支持掉电唤醒的管脚：P3.2/INT0, P3.3/INT1, T0/P3.4, T1/P3.5, RxD/P3.0, P1.3/CCP0(或P4.2/CCP0), P1.4/CCP1 (或P4.3/CCP1), EX_LVD/P4.6

工作频率：0～35MHz，相 当于普通8051：0～420MHz●

时钟：外部晶体或内部 振荡器可选，在 下载编程用户程序时设置●

8/16/32/40/48/56/60/62K字节片内Flash程序存储器，擦写次数10万次以上●

1280字节片内RAM数据存储器●

大容量 EEPROM功能,擦写次数10万次以上●

，在系统可编程/在应用可编程,无需编程器/仿真器●

通道，10位高速 ，速度可达 万次/秒， 路PWM还可当 路 使用●

2通道捕获/比较单元(CCP/PCA/PWM)，●

也可用来再实现 个定时器或 个外部中断(支持上升沿/下降沿中断)

2个16位定时器(兼容普通8051定时器T0/T1)，2路PCA可再实现2个定时器●

可编程时钟输出功能(T0在P3.4输出时钟，T1在P3.5输出时钟,BRT在P1.0输出时钟●

硬件看门狗 WDT)●

独立波特率发生器●

SPI高速同步串行通信接口●

双串口，全双工异步串行口(UART)，兼容普通8051串口，分时复用可当3组使用●

先进的指令集结构，兼容普通 指令集，有硬件乘法/除法指令●

通用 口( 个)，复位后为： 准双向口/弱上拉（普通 传统 口）●可设置成四种模式：准双向口/弱上拉， 强��/强上拉， 仅为输入/高阻，开 漏每个I/O口驱动能力均可达到20mA，但建议整个芯片不要超过120mA


STC 单片机在线编程/ISP线路


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/d01b7bb22238002204c369de6eba0862439950b353fcd667fd57b5382765066c.jpg)



该芯片也可使用USB转串口芯片CH340G,其价格低于RMB 1.3元


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/31ab0531c79daae0af2ec9d8951d79e8752e028167c9b8a38e8148881fdc0e13.jpg)


强烈推荐选择LQFP44, LQFP48贴片封装

# 每片单片机具有全球唯一身份证号码(ID号)超级加密，加密坚不可摧

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/07315d7a399d49a7fe2391cfa91306d2a60cb32f57fcf614b70f59234efbf572.jpg)


大陆本土宏晶STC姚永平独立创新设计，

请不要再抄袭我们的设计、规格和管脚排列，再抄袭就很无...

复位脚：烧录程序时如设置为I/O口,可当I/O口使用或浮空

EX_LVD:是外部低压检测中断/比较器

不用的I/O口：浮空即可

如果I/O口不够用可以用3根普通I/O口线外接74HC595(¥0.21元)来扩展I/O口，●并可多芯片级联扩展几十个I/O口，还可用A/D作按键扫描来节省I/O口

# 选择宏晶•STC12C5A60S2系列单片机理由：

超级加密，采用宏晶第六代加密技术★

超强抗干扰，超强抗静电，整机轻松过 万伏静电测试★

速度快，1个时钟/机器周期，可用低频晶振，大幅降低EMI★-出口欧美的有力保证

输入/输出口多，最多有44个I/O，A/D做按键扫描还可以节省很多I/O★

超低功耗：★

掉电模式：外部中断唤醒功耗 ${ < } 0 . 1 \mathrm { u A }$ ，支持下降沿/上升沿/ �适用于电池供电系统， 如水表、气表、 便携设备等。

空闲 模式： <1.3mA,正常工作模式 2mA -7mA

在系统可编程,无需编程器,无需仿真器，可远程升级★

可送USB型联机/脱机下载烧录工具STC-U7(人民币100元),1万片/人/天★

内部集成高可靠复位电路，外部复位电路可彻底省掉，当然也可以继续用外部★复位电路

全部175℃，8小时高温烘烤，高可靠制造保证★

# STC11/10xx系列带外部数据总线的 1T 8051 单片机，高速，高可靠，1-2个串口

传统8051单片机划时代升级换代产品，管脚完全兼容，直接取代传统89C51/89S51系列单片机

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/523d98cb9b02f0ef8a051fef700253e425755bf7ae1c3258f1955c64bc300022.jpg)


<table><tr><td rowspan="3">型号</td><td rowspan="3">工作电压(V)</td><td rowspan="3">Flash程序存储器byte)</td><td rowspan="3">GRAM字节</td><td rowspan="3">EEPROM</td><td rowspan="3">串行口并可掉电唤醒</td><td rowspan="3">S/P1</td><td rowspan="3">普通定时器计数器T0/TT外部管脚也能掉电唤醒</td><td rowspan="3">独立振荡发生器</td><td rowspan="3">掉电唤醒专用定时器</td><td rowspan="3">CCPPCA PWM</td><td rowspan="3">当内部中断并可掉电唤醒</td><td rowspan="3">A/D电路</td><td rowspan="3">看门限</td><td rowspan="3">支持掉电唤醒外部中断</td><td rowspan="3">内部低压检测中断</td><td rowspan="3">内部复位(可选门限电压)</td><td>LQFP44PDIP40</td><td>管脚兼容传统落后型号</td><td></td></tr><tr><td colspan="2">部分封装价格(RMBV)</td><td></td></tr><tr><td>LQFP44</td><td>PDIP40</td><td></td></tr><tr><td colspan="19">STC10Fxx系列单片机选型价格一览表,另有STC10L系列(工作电压2.1V-3.6V)</td><td></td></tr><tr><td>STC10F04</td><td>5.5-3.8/3.3</td><td>4K</td><td>256</td><td>-</td><td>1-2</td><td>无</td><td>2</td><td>有</td><td>-</td><td>无</td><td>无</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥2.5</td><td>¥3.0</td><td>89C51</td></tr><tr><td>STC10F04XE</td><td>5.5-3.8/3.3</td><td>4K</td><td>512</td><td>5K</td><td>1-2</td><td>无</td><td>2</td><td>有</td><td>-</td><td>无</td><td>无</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥2.7</td><td>¥3.2</td><td>89C51</td></tr><tr><td>STC10F08</td><td>5.5-3.8/3.3</td><td>8K</td><td>256</td><td>-</td><td>1-2</td><td>无</td><td>2</td><td>有</td><td>-</td><td>无</td><td>无</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥3.1</td><td>¥3.6</td><td>89C52</td></tr><tr><td>STC10F08XE</td><td>5.5-3.8/3.3</td><td>8K</td><td>512</td><td>5K</td><td>1-2</td><td>无</td><td>2</td><td>有</td><td>-</td><td>无</td><td>无</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥3.2</td><td>¥3.7</td><td>89C52</td></tr><tr><td>STC10F10XE</td><td>5.5-3.8/3.3</td><td>10K</td><td>512</td><td>3K</td><td>1-2</td><td>无</td><td>2</td><td>有</td><td>-</td><td>无</td><td>无</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥3.6</td><td>¥4.1</td><td>89C54</td></tr><tr><td>STC10F12XE</td><td>5.5-3.8/3.3</td><td>12K</td><td>512</td><td>1K</td><td>1-2</td><td>无</td><td>2</td><td>有</td><td>-</td><td>无</td><td>无</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥3.99</td><td>¥4.49</td><td>89C54</td></tr><tr><td>IAP10F14X</td><td>5.5-3.8</td><td>14K</td><td>512</td><td>IAP</td><td>1-2</td><td>无</td><td>2</td><td>有</td><td>-</td><td>无</td><td>无</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td colspan="2">用户可将用户程序区的程序/Flash当EEPROM用</td><td></td></tr><tr><td colspan="19">STC11Fxx系列单片机选型价格一览表,另有STC11L系列(工作电压2.1V-3.6V)</td><td></td></tr><tr><td>STC11F16XE</td><td>5.5-4.1/3.7</td><td>16K</td><td>1280</td><td>45K</td><td>1-2</td><td>无</td><td>2</td><td>有</td><td>有</td><td>无</td><td>无</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥4.3</td><td>¥4.8</td><td>89C54</td></tr><tr><td>STC11F32XE</td><td>5.5-4.1/3.7</td><td>32K</td><td>1280</td><td>29K</td><td>1-2</td><td>无</td><td>2</td><td>有</td><td>有</td><td>无</td><td>无</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥4.6</td><td>¥5.1</td><td>89C58</td></tr><tr><td>STC11F56XE</td><td>5.5-4.1/3.7</td><td>56K</td><td>1280</td><td>5K</td><td>1-2</td><td>无</td><td>2</td><td>有</td><td>有</td><td>无</td><td>无</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥4.7</td><td>¥5.2</td><td>89C516</td></tr><tr><td>STC11F60XE</td><td>5.5-4.1/3.7</td><td>60K</td><td>1280</td><td>1K</td><td>1-2</td><td>无</td><td>2</td><td>有</td><td>有</td><td>无</td><td>无</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>¥4.7</td><td>¥5.2</td><td>89C516</td></tr><tr><td>IAP11F62X</td><td>5.5-4.1/3.7</td><td>62K</td><td>1280</td><td>IAP</td><td>1-2</td><td>无</td><td>2</td><td>有</td><td>有</td><td>无</td><td>无</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td colspan="2">用户可将用户程序区的程序/Flash当EEPROM用</td><td></td></tr></table>


以上单价为 起定量，以上价格运费由客户承担，零售10片起�， �可来电要求降封装为PDIP40的单片机比封装为LQFP44的单片机要贵0.5元。


# 宏晶•STC11/10xx系列主要性能：

. 高速：1个时钟/机器周期，增强型8051内核，速度比普通8051快6～12倍

宽电压：5.5～4.1V/3.7V，2.1/2.4～3.6V(STC11/10L系列)●

低功耗设计：��空闲 模式(可由�任意�一个中断唤醒)●

低功耗设计：掉电模式(可由�任意�一个外部中断唤醒�， �●唤醒，STC11xx系列还可通过内部掉电唤醒专用定时器唤醒)

支持掉电唤醒的管脚：P3.2/INT0,P3.3/INT1,T0/P3.4,T1/P3.5,RxD/P3.0(或RxD/P1.6)●

内部掉电唤醒专用定时器(只有STC11系列才有，STC10系列无)●

工作频率：0～35MHz，相 当于普通8051：● $0 { \sim } 4 2 0 \mathrm { M H z }$ 

时钟：外部晶体或内部RC振荡器可选，在ISP下载编程用户程序时设置●

4/8/12/16/32/48/60/62K字节片内Flash程序存储器，擦写次数10万次以上●

1280/512/256字节片内RAM数据存储器●

大容量 EEPROM功能,擦写次数10万次以上●

ISP/IAP，在系统可编程/在应用可编程,无需编程器/仿真器●

2个16位定时器，兼容普通8051定时器T0/T1●

个独立波特率发生器(故无需T2做波特率发生器)，缺省是 做波特率发生器●

可编程时钟输出功能，T0在P3.4输出时钟，T1在P3.5输出时钟，BRT在P1.0输出时钟●

硬件看门狗（WDT）●

全双工异步串行口(UART), 兼容普通8051, 可当2组串口使用(串口可在P3与P1之间●任意切换)

先进的指令集结构，兼容普通8051指令集，有硬件乘法/除法指令●

通用I/O口(36/40个)，复位后为： 准双向口/弱上拉(普通8051传统I/O口)●可设置成四种模式：准双向口/弱上拉， 强��推挽 / 强上��拉， 仅�为输入/高���阻，开 漏每个I/O口驱动能力均可达到20mA，44/40管脚的IC建议整个芯片不要超过120mA

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/bbd752b234e53919d3807625928a8533a34b9fc078a6f95b6e35048844b7fcaf.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/42b5e576098da60302ea0b35caf0dfba025cfbb20572077129fdbaaca6302707.jpg)


串口作主机通信时，可控制串口通信在[RxD/P3.0,TxD/P3.1]和[RxD/P1.6,TxD/P1.7]之间任意切换，实现2组串口建议用户将串口设在[RxD/P1.6,TxD/P1.7]

强烈推荐选择LQFP44贴片封装SOP20/16贴片封装

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/cbb51d3430abe36217dfd429c2709bc524156ed8ed89b011df73128799c6942b.jpg)


大陆本土宏晶STC姚永平独立创新设计，请不要再抄袭我们的设计、规格和管脚排列，再抄袭就很无..

复位脚：烧录程序时如设置为I/O口,可当I/O口使用或浮空不用的I/O口：浮空即可

如果I/O口不够用可以用3根普通I/O口线外接74HC595(¥0.21元)来扩展I/O口，并可多芯片级联扩展几十个I/O口，还可用A/D作按键扫描来节省I/O口

# 选择宏晶•STC11/10xx系列单片机理由：

$\star$ 超级加密，采用宏晶第六代加密技术

超强抗干扰，超强抗静电，整机轻松过2万伏静电测试★

速度快， 个时钟/机器周期，可用低频晶振，大幅降低★-出口欧美的有力保证

输入/输出口多，最多有40个I/O，复位脚如当I/O口使用，可省去外部复位电路★

超低功耗：★

掉电模式：外部中断唤醒功耗 ${ < } 0 . 1 \mathrm { u A }$ ，支持下降沿/低电平和远程唤醒STC11xx系列增加了掉电唤醒专用定时器，启动掉电唤醒定时器典型功耗 $< 2 \mu \mathrm { A }$ 适用于电池供电系统， 如水表、气表、 便携设备等。

空闲 模式： <1.3mA,

正常工作模式 2mA -7mA

在系统可编程,无需编程器,无需仿真器，可远程升级★

可送 �B型联机/脱机下载烧录工具 �(人民币100元★

内部集成高可靠复位电路,复位脚设置为I/O口使用时，复位脚可浮空★

# STC11xx系列无外部数据总线 1T 8051 单片机，高速，高可靠，1-2个串口

传统8051单片机划时代升级换代产品，管脚完全兼容，直接取代传统89C51/89S51系列单片机

全球最低价：宏晶• STC11F01-SOP16 RMB 1.99元，STC11F04 RMB 2.49元宏晶• STC11F02-SOP20 RMB 2.20元，可取代89C2051/89C4051


每片单片机具有全球唯一身份证号码(ID号)超级加密，加密坚不可摧


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c788a6bb863d515e37dad91c1facadcf823e24cc66d174f4fd9fa2234177ca1d.jpg)


<table><tr><td rowspan="2">型号</td><td rowspan="2">工作电压(V)</td><td rowspan="2">Flash程序存储器(bit)</td><td rowspan="2">SRAM字节</td><td rowspan="2">EEPROM</td><td rowspan="2">串行口并可掉电唤醒</td><td rowspan="2">S P I</td><td rowspan="2">普通定时器计数器T0/T1外部管脚也能掉电唤醒</td><td rowspan="2">独立滤波器发生器</td><td rowspan="2">掉电唤醒专用定时器</td><td rowspan="2">CCPPCA PWM</td><td rowspan="2">可当外部中断并可掉电唤醒</td><td rowspan="2">A/D 8路</td><td rowspan="2">看门电路</td><td rowspan="2">支持掉电唤醒外部中断</td><td rowspan="2">内部低压检测中断</td><td rowspan="2">内部复位(可选复位门槛电压)</td><td colspan="3">SOP20/DIP20/LSSOP20DIP-16/SOP16/DIP16</td></tr><tr><td colspan="3">部分封装价格(RMB ¥)</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>SOP20</td><td>SOP16</td><td>DIP-18</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>3.10</td><td>3.29</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>3.10</td><td>3.29</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>3.10</td><td>3.29</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td colspan="3">用户可将用户程序区的程序Flash当EEPROM用</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>4.10</td><td>4.29</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>1.10</td><td>1.29</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td><td>有</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>有</td><td>无</td><td>无</td><td>有</td><td>5个</td><td>有</td><td>有</td><td>有</td><td></td><td></td><td></td></tr></table>


以上单价为200K/M起定量，以上价格运费由客户承担，零售10片起�， �可来电要求降封装为DIP20的单片机比封装为SOP20的单片机要贵0.2元； 封装为LSSOP20的单片机比封装为SOP20的单片机要贵0.1元；封装为DIP16的单片机比封装为SOP16的单片机要贵0.2元。


# 宏晶•STC11xx系列主要性能：

高速：1个时钟/机器周期，增强型8051内核，速度比普通8051快6～12倍●

宽电压：5.5～4.1V/3.7V，2.1/2.4～3.6V(STC11L系列)●

低功耗设计：��空闲 模式(可由�任意�一个中断唤醒)●

低功耗设计：掉电模式(可由�任意�一个外部中断唤醒�●远程唤醒，STC11xx系列还可通过内部掉电唤醒专用定时器唤醒)

支持掉电唤醒的管脚：P3.2/INT0,P3.3/INT1,T0/P3.4,T1/P3.5,RxD/P3.0(或RxD/P1.6)●

内部掉电唤醒专用定时器(只有STC11系列才有，STC10系列无)●

工作频率：0～35MHz，相 当于普通8051：0～420MHz●

时钟：外部晶体或内部RC振荡器可选，在ISP下载编程用户程序时设置●

1/2/3/4/5/6K字节片内Flash程序存储器，擦写次数10万次以上●

256字节片内RAM数据存储器●

大容量 EEPROM功能,擦写次数10万次以上●

ISP/IAP，在系统可编程/在应用可编程,无需编程器/仿真器●

2个16位定时器，兼容普通8051定时器T0/T1●

个独立波特率发生器(故无需T2做波特率发生器)，缺省是 做波特率发生器●

可编程时钟输出功能，T0在P3.4输出时钟，T1在P3.5输出时钟●

硬件看门狗（WDT）●

全双工异步串行口(UART), 兼容普通8051, 可当2组串口使用(串口可在P3与P1之间●任意切换)

先进的指令集结构，兼容普通8051指令集，有硬件乘法/除法指令●

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/e6b5bebcdb67c6f4eca437941153c9ffb3071e721ad79a176a1c93f043d657ae.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/1ecfab6898ee72f5d7f101df809200197eba3bbf246a3dbf01d5286ac749bd18.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/07478c0591554e99781508d863a9d0e6cbd8aa7b3b0a25cf46989f6f5000cd19.jpg)


串口作主机通信时，可控制串口通信在[RxD/P3.0,TxD/P3.1]和[RxD/P1.6,TxD/P1.7]之间任意切换，实现2组串口建议用户将串口设在[RxD/P1.6,TxD/P1.7]

大陆本土宏晶STC姚永平独立创新设计，

请不要再抄袭我们的设计、规格和管脚排列，再抄袭就很无..

复位脚：烧录程序时如设置为I/O口,可当I/O口使用或浮空不用的I/O口：浮空即可

通用I/O口(16/14/12个)，复位后为： 准双向口/弱上拉(普通8051传统I/O口)●可设置成四种模式：准双向口/弱上拉， 强��推挽 / 强上��拉， 仅�为输入/高���阻，开 漏每个I/O口驱动能力均可达到20mA,20/18/16管脚的IC建议整个芯片不要超过70mA

如果I/O口不够用可以用3根普通I/O口线外接74HC595(¥0.21元)来扩展I/O口，并可多芯片级联扩展几十个I/O口，还可用A/D作按键扫描来节省I/O口

# 选择宏晶•STC11xx系列单片机理由：

$\star$ 超级加密，采用宏晶第六代加密技术

超强抗干扰，超强抗静电，整机轻松过2万伏静电测试★

速度快，1个时钟/机器周期，可用低频晶振，大幅降低EMI★-出口欧美的有力保证

输入/输出口多，最多有16个I/O，复位脚如当I/O口使用，可省去外部复位电路★

超低功耗：★

掉电模式： $< 0 . 1 { \mathrm { u A } }$ ，支持下降沿/低电平和远程唤醒

STC11xx系列增加了掉电唤醒专用定时器，启动掉电唤醒定时器典型功耗 $< 2 \mu \mathrm { A }$ 适用于电池供电系统， 如水表、气表、 便携设备等。

空闲 模式： <1.3mA,

正常工作模式

在系统可编程,无需编程器,无需仿真器，可远程升级★

可送 �B型联机/脱机下载烧录工具 �(人民币100元★

内部集成高可靠复位电路,复位脚设置为I/O口使用时，复位脚可浮空★

# STC micro TM

# 宏 晶 科 技

# 超强抗干扰， 超级加密

8051单片机全球第一品牌，全球最大的8051单片机设计公司全部中国大陆本土独立自主知识产权；品质保证：TSMC上海制造

官方网站：www.STCMCU.com

南通 Tel: 0513-5501 2928 5501 2929深圳 Tel: 0755-8294 8411 8294 8412

# STC12C5201AD系列 1T 8051 单片机，超低价，2路CCP/PCA/PWM，高速A/D

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/3a3132506ba56d2dc2164ee7c126623c45f39cb5ce925237b7c3ac835bd94897.jpg)


<table><tr><td rowspan="3">型号</td><td rowspan="3">工作电压(V)</td><td rowspan="3">Flash 程序存储器byte</td><td rowspan="3">SRAM字节</td><td rowspan="3">EEPROM</td><td rowspan="3">串行口并可掉电唤醒</td><td rowspan="3" colspan="2">普通定时器计数器T0/T1外部管脚也能掉电唤醒</td><td rowspan="3">CCP PCA PWM 可当外部中断并可掉电唤醒</td><td rowspan="3">DTR PWR 30万次(2路PWM可当2路D/A使用)</td><td rowspan="3">A/D 8路每次(2路PWM可当2路D/A使用)</td><td rowspan="3">看门狗</td><td rowspan="3">外部实时低/高检测中断</td><td rowspan="3">外部复位</td><td colspan="4">LQFP32/SOP32(不推荐)SOP28/SKDP28SOP20/DIP20/LSSOP20SOP16/DIP16</td></tr><tr><td colspan="4">部分封装价格(RMB ¥)</td></tr><tr><td>SOP16价格</td><td>SOP20价格</td><td>SOP28价格</td><td>LQFP32价格</td></tr><tr><td colspan="18">STC12C5201AD系列单片机选型价格一览表特别提醒:2路CCP/PCA/PWM还可当2路定时器使用,另有STC12LE系列(工作电压2.1V-3.6V)</td></tr><tr><td>STC12C5201AD</td><td>5.5-4.0</td><td>IK</td><td>256</td><td>2K</td><td>1</td><td>无</td><td>2</td><td>2-ch</td><td>1</td><td>8位</td><td>有</td><td>有</td><td>有</td><td>¥2.49起</td><td></td><td></td><td></td></tr><tr><td>STC12C5202AD</td><td>5.5-4.0</td><td>2K</td><td>256</td><td>2K</td><td>1</td><td>无</td><td>2</td><td>2-ch</td><td>1</td><td>8位</td><td>有</td><td>有</td><td>有</td><td></td><td>¥2.99起</td><td></td><td></td></tr><tr><td>STC12C5203AD</td><td>5.5-4.0</td><td>3K</td><td>256</td><td>2K</td><td>1</td><td>无</td><td>2</td><td>2-ch</td><td>1</td><td>8位</td><td>有</td><td>有</td><td>有</td><td></td><td>¥3.20起</td><td>¥3.30起</td><td></td></tr><tr><td>STC12C5204AD</td><td>5.5-4.0</td><td>4K</td><td>256</td><td>1K</td><td>1</td><td>无</td><td>2</td><td>2-ch</td><td>1</td><td>8位</td><td>有</td><td>有</td><td>有</td><td></td><td>¥3.30起</td><td>¥3.50起</td><td>¥3.99起</td></tr><tr><td>STC12C5205AD</td><td>5.5-4.0</td><td>5K</td><td>256</td><td>1K</td><td>1</td><td>无</td><td>2</td><td>2-ch</td><td>1</td><td>8位</td><td>有</td><td>有</td><td>有</td><td></td><td>¥3.30起</td><td>¥3.50起</td><td>¥3.99起</td></tr><tr><td>STC12C5206AD</td><td>5.5-4.0</td><td>6K</td><td>256</td><td>1AP</td><td>1</td><td>无</td><td>2</td><td>2-ch</td><td>1</td><td>8位</td><td>有</td><td>有</td><td>有</td><td colspan="4">用户可将用户程序区的程序Flash当EEPROM使用</td></tr></table>


以上单价为200K/M起定量，以上价格运费由客户承担，零售10片起�， �可来电要求降封装为SKDIP28的单片机比封装为SOP28的单片机要贵0.2元； 封装为DIP20的单片机比封装为SOP20的单片机要贵0.2元；封装为LSSOP20的单片机比封装为SOP20的单片机要贵0.1元； 可用IAP15F2K61S2仿真(仅供参考)封装为DIP16的单片机比封装为SOP16的单片机要贵0.2元。


# 宏晶•STC12C5201AD系列主要性能：

高速：1个时钟/机器周期，增强型8051内核，速度比普通8051快6～12倍●

宽电压：● $5 . 5 \mathrm { \sim } 4 . 0 0 $ ，2.2～3.6V(STC12LE5201AD系列）

增加第二复位功能脚/P1.2(高可靠复位，可调整复位门槛电压，频率<12MHz时，●无需此功能)

增加外部掉电检测电路/P1.2，可在掉电时，及 时将数据保存进EEPROM，正常工●作时无需操作EEPROM

低功耗设计：��空闲 模式(可由�任意�一个中断唤醒)�，掉电模式●

支持掉电唤醒的管脚：P3.2/INT0, P3.3/INT1, T0/P3.4, T1/P3.5, RxD/P3.0, P3.7/CCP0, ●P3 5/CCP1 EX IVD/P12

工作频率：● $0 { \sim } 3 5 \mathrm { M H z }$ ，相 当于普通8051：0～420MHz

时钟：外部晶体或内部RC振荡器可选，在ISP下载编程用户程序时设置●

1K/2K/3K/4K/5K/6K字节片内Flash程序存储器，擦写次数10万次以上●

256字节片内RAM数据存储器●

片内EEPROM功能,擦写次数10万次以上●

ISP/IAP，在系统可编程/在应用可编程,无需编程器/仿真器●

8通道，8位高速ADC，速度可达30万次/秒，2路PWM还可当2路D/A使用●

2通道捕获/比较单元(CCP/PCA/PWM)，●

---也可用来再实现2个定时器或2个外部中断(支持上升沿/下降沿中断)

2个16位定时器，兼容普通8051的定时器T0/T1,2路PCA可再实现2个定时器●

可编程时钟输出功能，T0在P3.4输出时钟，T1在P3.5输出时钟●

硬件看门狗（WDT）●

全双工异步串行口(UART)，兼容普通8051的串口●

先进的指令集结构，兼容普通8051指令集，有硬件乘法/除法指令●

通用I/O口(27/23/15个)，复位后为： 准双向口/弱上拉（普通8051传统I/O口）●可设置成四种模式：准双向口/弱上拉， 强��推挽 /强上��拉， 仅�为输入/高���阻，开 漏每个I/O口驱动能力均可达到20mA，但建议整个芯片不要超过90mA

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/2acf92293891488823db510d48e9b932a7d92e5ffafa2727ff58dd1748ef8132.jpg)


复位脚：烧录程序时如设置为I/O口,可当I/O口使用或浮空

EX_LVD:是外部低压检测中断/比较器

不用的I/O口：浮空即可

如选32-Pin，推 荐优先选择LQFP32●

如果I/O口不够用可以用3根普通I/O口线外接74HC595(¥0.21元)来扩展I/O口，●并可多芯片级联扩展几十个I/O口，还可用A/D作按键扫描来节省I/O口

# 选择宏晶•STC12C5201AD系列单片机理由：

$\star$ 超级加密，采用宏晶第六代加密技术

超强抗干扰：★

1.高抗静电(ESD保护)，整机轻松过2万伏静电测试

2.轻松过4KV快速脉冲干扰(EFT测试)

3.宽电压，不怕电源抖动

速度快，1个时钟/机器周期，可用低频晶振，大幅降低EMI★

-出口欧美的有力保证

$\star$ 超低功耗：

1.掉电模式;外部中断唤醒功耗<01uA

2.空闲 模式: 典型功耗 ,

3.正常工作模式:

4.掉电模式可由外部中断唤醒��，适 用�于电�池供电系��统， 如������水表、气表、 便携设备�等

$\star$ 在系统可编程,无需编程器,无需仿真器，可远程升级

可送USB型联机/脱机下载烧录工具STC-U7(人民币100元),1万片/人/天★

内部集成高可靠复位电路，外部复位电路可彻底省掉，当然也可以继续用外部复位★电路

全部 ℃， 小时高温烘烤，高可靠制造保证★

# STC micro TM

# 宏 晶 科 技

# 超强抗干扰， 超级加密

8051单片机全球第一品牌，全球最大的8051单片机设计公司全部中国大陆本土独立自主知识产权；品质保证：TSMC上海制造

官方网站：www.STCMCU.comwww.GXWMCU.com

南通 Tel: 0513-5501 2928 5501 2929深圳 Tel: 0755-8294 8411 8294 8412

# STC12C5620AD系列 1T 8051 单片机，4路PWM/PCA，8路10位A/D转换

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/4bef46c18e2a0002929ea49477d5f0be31a557c2e8145d35980d29b17db41294.jpg)


<table><tr><td rowspan="3">型号</td><td rowspan="3">工作电压(V)</td><td rowspan="3">Flash程序存储器byte)</td><td rowspan="3">SRAM字节</td><td rowspan="3">EEPROM</td><td rowspan="3">串行口并可掉电唤醒</td><td rowspan="3">S/P1</td><td rowspan="3">普通定时器计数器T0/T1外部管脚也能掉电唤醒</td><td rowspan="3">PCA PWM可当外部中断并可掉电唤醒</td><td rowspan="3">D P T R</td><td rowspan="3">A/D 8路10万次每秒4路PWM可当4路D/A使用</td><td rowspan="3">看门板</td><td rowspan="3">内部低压检测中断</td><td rowspan="3">内部复位(可选复位门槛电压)</td><td colspan="3">LQFP32/SOP32(不推荐)SOP28:SKDP28SOP20/DIP20/TSSOP20</td></tr><tr><td colspan="2">部分封装价格(RMB¥)</td><td rowspan="2">LQFP32价格(RMB¥)</td></tr><tr><td>SOP20价格(RMB¥)</td><td>SOP28价格(RMB¥)</td></tr><tr><td colspan="17">STC12CS60AD系列单片机选型价格一览表特别提醒:4路CCP/PCA/PWM还可当4路定时器使用,另有STC12LE系列(工作电压2.2V-3.6V)</td></tr><tr><td>STC12CS604AD</td><td>5.5-3.5</td><td>4K</td><td>768</td><td>4K</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td>有</td><td>有</td><td>¥3.60起</td><td></td><td></td></tr><tr><td>STC12CS608AD</td><td>5.5-3.5</td><td>8K</td><td>768</td><td>4K</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td>有</td><td>有</td><td>¥3.8起</td><td></td><td></td></tr><tr><td>STC12CS612AD</td><td>5.5-3.5</td><td>12K</td><td>768</td><td>1AP</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td>有</td><td>有</td><td colspan="3">用户可将用户程序区的程序Flash当EEPROM使用</td></tr><tr><td>STC12CS616AD</td><td>5.5-3.5</td><td>16K</td><td>768</td><td>4K</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td>有</td><td>有</td><td></td><td>¥4.99起</td><td></td></tr><tr><td>STC12CS620AD</td><td>5.5-3.5</td><td>20K</td><td>768</td><td>4K</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td>有</td><td>有</td><td></td><td></td><td></td></tr><tr><td>STC12CS624AD</td><td>5.5-3.5</td><td>24K</td><td>768</td><td>4K</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td>有</td><td>有</td><td></td><td></td><td></td></tr><tr><td>STC12CS628AD</td><td>5.5-3.5</td><td>28K</td><td>768</td><td>1AP</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td>有</td><td>有</td><td colspan="3">用户可将用户程序区的程序Flash当EEPROM使用</td></tr><tr><td>STC12CS630AD</td><td>5.5-3.5</td><td>30K</td><td>768</td><td>1AP</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td>有</td><td>有</td><td colspan="3">用户可将用户程序区的程序Flash当EEPROM使用</td></tr></table>


以上单价为200K/M起定量，以上价格运费由客户承担，零售10片起�， �可来电要求降



封装为SKDIP28的单片机比封装为SOP28的单片机要贵0.2元封装为DIP20的单片机比封装为SOP20的单片机要贵0.2元。


# 宏晶•STC12C5620AD系列主要性能：

高速：1个时钟/机器周期，增强型8051内核，速度比普通8051快8～12倍●

宽电压：5.5～3.5V，2.2～3.6V(STC12LE5620AD系列)●

低功耗设计：��空闲 模式(可由�任意�一个中断唤醒)�，掉电模式●

工作频率：● $0 { \sim } 3 5 \mathrm { M H z }$ ，相 当于普通8051：0～420MHz

时钟：外部晶体或内部RC振荡器可选，在ISP下载编程用户程序时设置●

30K/28K/24K/20K/16K/12K/8K/4K节片内Flash程序存储器，擦写次数10万次以上●

768字节● $( 2 5 6 + 5 1 2 )$ 片内RAM数据存储器

片内EEPROM功能�， 10万次以上●

ISP/IAP，在系统可编程/在应用可编程,无需编程器/仿真器●

8通道，10位ADC，速度可达10万次/秒，4路PWM还可当4路D/A使用●

4通道捕获/比较单元(PWM/PCA)，●

---也可用来再实现4个定时器或4个外部中断(支持上升沿/下降沿中断)

2个16位定时器，兼容普通8051的定时器T0/T1，4路PCA可再实现4个定时器●

可编程时钟输出功能，T0在P1.0输出时钟，T1在P1.1输出时钟●

硬件看门狗（WDT）●

SPI高速同步串行●

全双工异步串行口(UART)，兼容普通8051的串口●

先进的指令集结构，兼容普通 指令集，有硬件乘法/除法指令●

通用 口( 个)，复位后为： 准双向口/弱上拉（普通 传统 口）●可设置成四种模式：准双向口/弱上拉， 强��推挽 /强上��拉， 仅�为输入/高���阻，开 漏每个I/O口驱动能力均可达到20mA，但建议整个芯片不要超过90mA

如选32-Pin，推 荐选LQFP32★

如果 口不够用，可以用 根普通 口线外接 (参考价 元)来扩展★口，并可多芯片级联扩展几十个I/O口，还可用A/D做按键扫描来节省I/O口

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/6b77c5c95c4f9b83b1ba2b55eb91fb48dc27107bb5a0fca59bb81635f32a8c81.jpg)



大陆本土宏晶STC姚永平独立创新设计，请不要再抄袭我们的设计、规格和管脚排列，再抄袭就很无...


# 选择宏晶•STC12C5620AD系列单片机理由：

$\star$ 超级加密，采用宏晶第六代加密技术

超强抗干扰：★

1.高抗静电(ESD保护),整机轻松过2万伏静电测试

2.轻松过4KV快速脉冲干扰(EFT测试)

3.宽电压，不怕电源抖动 4.宽温度范围，-40℃~+85℃

速度快，1个时钟/机器周期，可用低频晶振，大幅降低EMI★

出口欧美的有力保证

超低功耗：★

1.掉电模式:外部中断唤醒功耗 ${ < } 0 . 1 \mathrm { u A }$ 

2.空闲 模式: 典型功耗 1.8mA, 3.正常工作模式:2.7mA -7mA

4.掉电模式可由外部中断唤醒��，适 用�于电�池供电系��统， 如������水表、气表、 便携设备�等

$\star$ 在系统可编程,无需编程器,无需仿真器，可远程升级

可送USB型联机/脱机下载烧录工具STC-U7(人民币100元),1万片/人/天★

内部集成专用 �， �12MHz以下可放心使用内部复★位，外部复位电路可 ��

# STC micro TM

# 宏 晶 科 技

# 超强抗干扰， 超级加密

8051单片机全球第一品牌，全球最大的8051单片机设计公司全部中国大陆本土独立自主知识产权；品质保证：TSMC上海制造

官方网站：www.STCMCU.comwww.GXWMCU.com

南通 Tel: 0513-5501 2928 5501 2929深圳 Tel: 0755-8294 8411 8294 8412

# STC12C5410AD/2052AD系列 1T 8051 单片机，4路PWM/PCA，8路10位A/D

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c5dde1d5c405dde02d59acf132e3880d6d5acaac58dfeac417b48b879fed5987.jpg)


<table><tr><td rowspan="3">型号</td><td rowspan="3">工作电压(V)</td><td rowspan="3">Flash程序存储器byte)</td><td rowspan="3">S RAM字节</td><td rowspan="3">EEPROM</td><td rowspan="3">串行口并可掉电唤醒</td><td rowspan="3">S P I</td><td rowspan="3">普通定时器计数器T0/T1外部管脚也能掉电唤醒</td><td rowspan="3">PCA PWM可当外部中断并可掉电唤醒</td><td rowspan="3">A/D 8路每秒4路PWM可当4路D/A使用</td><td rowspan="3">看门板</td><td rowspan="3">内部复位(可选复位门槛电压)</td><td colspan="3">LQFP32/SOP32(不推荐)SOP28/SKDP28SOP20/DIP20/TSSOP20</td></tr><tr><td colspan="3">部分封装价格(RMB¥)</td></tr><tr><td>SOP20价格(RMB¥)</td><td>SOP28价格(RMB¥)</td><td>LQFP32价格(RMB¥)</td></tr><tr><td colspan="15">STC12CS410AD系列单片机选型价格一览表</td></tr><tr><td colspan="15">特别提醒:4路CCP/PCA/PWM还可当4路定时器使用,另有STC12LE系列(工作电压2.2V-3.6V)</td></tr><tr><td>STC12CS401AD</td><td>5.5-3.5</td><td>1K</td><td>512</td><td>有</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td></td><td></td><td></td></tr><tr><td>STC12CS402AD</td><td>5.5-3.5</td><td>2K</td><td>512</td><td>有</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td></td><td></td><td></td></tr><tr><td>STC12CS404AD</td><td>5.5-3.5</td><td>4K</td><td>512</td><td>有</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td></td><td></td><td></td></tr><tr><td>STC12CS406AD</td><td>5.5-3.5</td><td>6K</td><td>512</td><td>有</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td></td><td></td><td></td></tr><tr><td>STC12CS408AD</td><td>5.5-3.5</td><td>8K</td><td>512</td><td>有</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td></td><td></td><td></td></tr><tr><td>STC12CS410AD</td><td>5.5-3.5</td><td>10K</td><td>512</td><td>有</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td></td><td></td><td></td></tr><tr><td>STC12CS412AD</td><td>5.5-3.5</td><td>12K</td><td>512</td><td>IAP</td><td>1</td><td>有</td><td>2</td><td>4-ch</td><td>1</td><td>10位</td><td>有</td><td colspan="3">用户可将用户程序区的程序Flash当EEPROM使用</td></tr><tr><td colspan="15">STC12CS2052AD系列单片机选型价格一览表</td></tr><tr><td colspan="15">特别提醒:2路CCP/PCA/PWM还可当2路定时器使用,另有STC12LE系列(工作电压2.2V-3.6V)</td></tr><tr><td>STC12C1052AD</td><td>5.5-3.5</td><td>1K</td><td>256</td><td>有</td><td>1</td><td>有</td><td>2</td><td>2-ch</td><td>1</td><td>8位</td><td>有</td><td colspan="3">SOP20/DIP20/TSSOP20</td></tr><tr><td>STC12C2052AD</td><td>5.5-3.5</td><td>2K</td><td>256</td><td>有</td><td>1</td><td>有</td><td>2</td><td>2-ch</td><td>1</td><td>8位</td><td>有</td><td colspan="3">SOP20/DIP20/TSSOP20</td></tr><tr><td>STC12C4052AD</td><td>5.5-3.5</td><td>4K</td><td>256</td><td>有</td><td>1</td><td>有</td><td>2</td><td>2-ch</td><td>1</td><td>8位</td><td>有</td><td colspan="3">SOP20/DIP20/TSSOP20</td></tr><tr><td>STC12C5052AD</td><td>5.5-3.5</td><td>5K</td><td>256</td><td>IAP</td><td>1</td><td>有</td><td>2</td><td>2-ch</td><td>1</td><td>8位</td><td>有</td><td colspan="3">用户可将用户程序区的程序Flash当EEPROM使用</td></tr></table>


以上单价为200K/M起定量，以上价格运费由客户承担，零售10片起�， �可来电要求降封装为SKDIP28的单片机比封装为SOP28的单片机要贵0.2元；封装为 的单片机比封装为 的单片机要贵 元。 可用IAP15F2K61S2仿真(仅供参考)


# 宏晶•STC12C5410AD/2052AD系列主要性能：

高速：1个时钟/机器周期，增强型8051内核，速度比普通8051快6～12倍●

宽电压：● $5 . 5 { \sim } 3 . 5 \mathrm { V }$ ，2.2～3.8V(STC12LE5410AD/2052AD系列)

低功耗设计：��空闲 模式(可由�任意�一个中断唤醒)�，掉电模式●

工作频率：0～35MHz，相 当于普通8051：0～420MHz●

时钟：外部晶体或内部RC振荡器可选，在ISP下载编程用户程序时设置●

16K/12K/10K/8K/6K/4K/2K/1K节片内Flash程序存储器，擦写次数10万次以上●

512 / 256 字节 RAM数据存储器●

片内EEPROM功能,擦写次数10万次以上●

ISP/IAP，在系统可编程/在应用可编程,无需编程器/仿真器●

8通道，10位ADC，STC12C2052AD系列为8位ADC，4路PWM还可当4路D/A使用●

4通道捕获/比较单元(PWM/PCA)，STC12C2052AD系列为2通道●

--也可用来再实现 个定时器或 个外部中断(支持上升沿/下降沿中断)

2个16位定时器，兼容普通8051的定时器T0/T1，4路PCA可再实现4个定时器●

可编程时钟输出功能，T0在P1.0输出时钟，T1在P1.1输出时钟●

硬件看门狗(WDT)●

SPI高速同步串行●

全双工异步串行口(UART)，兼容普通8051的串口●

先进的指令集结构，兼容普通8051指令集●4组8个8位通用工作�寄存器(�共32个通用�寄存器)有硬件乘法/除法指令

通用I/O口(27/23/15个)，复位后为： 准双向口/弱上拉（普通8051传统I/O口）●可设置成四种模式：准双向口/弱上拉， 强��推挽 /强上��拉， 仅�为输入/高���阻，开 漏每个I/O口驱动能力均可达到20mA，但建议整个芯片不要超过90mA

STC12C10 

尽量优先选择成本更低，抗干更强，采用新加密技术的宏晶STC15xx/11xx/12C52xx/12C56x列取代，原有老产品继续长期生

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/c383a536fced249eca320e49d31fd9fa3a4c61670b0b2af336ff659cc8e5eed6.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/39c7e296aa867739b6747552c8fd656b630634c0139995da5fcb274c80ed13e1.jpg)



STC 单片机在线编程(也可使用USB转串CH340G,价格低于R


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/b34406acb6034845c9f93ca191cf79b6c8c3425e390802ee519c83b4e84d7513.jpg)



大陆本土宏晶STC姚永平独立创新设计，请不要再抄袭我们的设计、规格和管脚排列，再抄袭就很无...



全部175℃小时高温烘烤


![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7344dc0eef1d283bcf60de178fa13bffcb5bfc6213460bd18d1abef23e7dfd00.jpg)



如选32-Pin，推 荐选LQFP32★



如果I/O口不够用，可以用3根普通I/O口线外接74HC595(参考价0.21元)来扩展I/O口，★并可多芯片级联扩展几十个I/O口，还可用A/D做按键扫描来节省I/O口


# 选择宏晶•STC12C5410AD/2052AD系列单片机理由：

超级加密★

超强抗干扰：★

1.高抗静电(ESD保护)

2.轻松过4KV快速脉冲干扰(EFT测试)

3.宽电压，不怕电源抖动

4.宽温度范围，-40℃~+85℃

$\star$ 速度快，1个时钟/机器周期，可用低频晶振，大幅降低EMI---出口欧美的有力保证

$\star$ 超低功耗：

1. <0.1uA 

2.空闲 模式: 典型功耗 1.8mA,

3.正常工作模式:2.7mA -7mA

4.掉电模式可由外部中断唤醒��，适 用�于电�池供电系��统， 如������水表、气表、 便携设备�等

所有封装均符合欧盟RoHS要求★

在系统可编程,无需编程器,无需仿真器，可远程升级★

可送USB型联机/脱机下载烧录工具STC-U7(人民币100元),1万片/人/天★

# 宏晶 • STC 89C5190C51 系列单片机，直接兼容传统8051

欢迎使用STC90C51系列(软硬件完全兼容)取代89C51系列，STC90C51系列抗干扰能力更强，成本更低

或请使用第六代加密技术加密、加密性强的STC11/10xx系列取代89C51系列

或强烈建议使用第九代加密技术加密、无法解密的STC15xx系列取代89C51系列，

已有大批量供货10年以上的历史

可用IAP15F2K61S2仿真(仅供参考)

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/622f3210ab429b39fa892bd844fe500932199c1851863b7a0b228b33f8b4dc66.jpg)


<table><tr><td>型号</td><td>工作电压(%)</td><td>Flash程序存储器(字节)</td><td>SRAM字节</td><td>EEPROM(字节)</td><td>定时器</td><td>A/D10位8路</td><td>降低EMI</td><td>双/信道</td><td>支持掉电保护电路</td><td>信号前置电路</td><td>有源</td><td>DSP</td><td>LAP</td><td>LQFP44价格</td><td>PID40价格</td><td>PLCC44价格</td><td>兼容传统落后型号</td><td>价格更低功能更强不需要外部时钟不需外部复位的替代型号</td></tr><tr><td>STC89C51RC</td><td>5.5-3.5</td><td>4K</td><td>512</td><td>9K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥2.8</td><td>¥3.3</td><td>¥3.4</td><td>89C51</td></tr><tr><td>STC90C51RC</td><td>5.5-3.5</td><td>4K</td><td>512</td><td>9K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥2.7</td><td>¥3.2</td><td>¥3.3</td><td>89C51</td></tr><tr><td>STC15W40AS</td><td>5.5-2.4</td><td>4K</td><td>512</td><td>9K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>42个</td><td>5个</td><td>强</td><td>强</td><td>✓</td><td>✓</td><td>¥2.5</td><td>¥3.0</td><td></td><td></td></tr><tr><td>STC89C52RC</td><td>5.5-3.5</td><td>8K</td><td>512</td><td>5K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥2.8</td><td>¥3.1</td><td>¥3.4</td><td>89C52</td></tr><tr><td>STC90C52RC</td><td>5.5-3.5</td><td>8K</td><td>512</td><td>5K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥2.7</td><td>¥3.0</td><td>¥3.3</td><td>89C52</td></tr><tr><td>STC15W40S</td><td>5.5-2.4</td><td>8K</td><td>512</td><td>5K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>42个</td><td>5个</td><td>强</td><td>强</td><td>✓</td><td>✓</td><td>¥2.7</td><td>¥3.0</td><td></td><td></td></tr><tr><td>STC89C53RC</td><td>5.5-3.5</td><td>12K</td><td>512</td><td>-</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥3.5</td><td>¥4.0</td><td>¥4.1</td><td>89C53</td></tr><tr><td>STC90C53RC</td><td>5.5-3.5</td><td>12K</td><td>512</td><td>-</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥3.4</td><td>¥3.9</td><td>¥4.0</td><td>89C54</td></tr><tr><td>IAP15W413S</td><td>5.5-2.4</td><td>13K</td><td>512</td><td>IAP</td><td>3个</td><td>-</td><td>✓</td><td>-</td><td>42个</td><td>5个</td><td>强</td><td>强</td><td>✓</td><td>✓</td><td>¥2.8</td><td>¥3.3</td><td></td><td></td></tr><tr><td>STC89C54RD+</td><td>5.5-3.5</td><td>16K</td><td>1280</td><td>45K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥4.5</td><td>¥5.0</td><td>¥5.1</td><td>89C54</td></tr><tr><td>STC90C54RD+</td><td>5.5-3.5</td><td>16K</td><td>1280</td><td>45K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥4.4</td><td>¥4.9</td><td>¥5.0</td><td>89C54</td></tr><tr><td>STC15W1K16S</td><td>5.5-2.6</td><td>16K</td><td>1024</td><td>13K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>42个</td><td>5个</td><td>强</td><td>强</td><td>✓</td><td>✓</td><td>¥3.5</td><td>¥4.0</td><td></td><td></td></tr><tr><td>STC89C58RD+</td><td>5.5-3.5</td><td>32K</td><td>1280</td><td>29K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥4.5</td><td>¥5.0</td><td>¥5.1</td><td>89C58</td></tr><tr><td>STC90C58RD+</td><td>5.5-3.5</td><td>32K</td><td>1280</td><td>29K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥4.4</td><td>¥4.9</td><td>¥5.0</td><td>89C58</td></tr><tr><td>IAP15W1K29S</td><td>5.5-2.6</td><td>29K</td><td>1024</td><td>IAP</td><td>3个</td><td>-</td><td>✓</td><td>-</td><td>42个</td><td>5个</td><td>强</td><td>强</td><td>✓</td><td>✓</td><td>¥3.8</td><td>¥4.3</td><td></td><td></td></tr><tr><td>STC89C516RD+</td><td>5.5-3.5</td><td>61K</td><td>1280</td><td></td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥4.5</td><td>¥5.0</td><td>¥5.1</td><td>89C516</td></tr><tr><td>STC90C516RD+</td><td>5.5-3.5</td><td>61K</td><td>1280</td><td></td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥4.4</td><td>¥4.9</td><td>¥5.0</td><td>89C516</td></tr><tr><td>IAP15F2K61S</td><td>5.5-3.8</td><td>61K</td><td>2048</td><td>IAP</td><td>3个</td><td>-</td><td>✓</td><td>-</td><td>42个</td><td>5个</td><td>强</td><td>强</td><td>✓</td><td>✓</td><td>¥4.0</td><td>¥4.5</td><td></td><td></td></tr><tr><td>STC90C510RD+</td><td>5.5-3.5</td><td>40K</td><td>1280</td><td>21K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥4.4</td><td>¥4.9</td><td>¥5.0</td><td>89C516</td></tr><tr><td>STC90C512RD+</td><td>5.5-3.5</td><td>40K</td><td>1280</td><td>13K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥4.4</td><td>¥4.9</td><td>¥5.0</td><td>89C516</td></tr><tr><td>STC90C514RD+</td><td>5.5-3.5</td><td>56K</td><td>1280</td><td>5K</td><td>3个</td><td>-</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥4.4</td><td>¥4.9</td><td>¥5.0</td><td>89C516</td></tr><tr><td>STC90C54AD</td><td>5.5-3.8</td><td>16K</td><td>4352</td><td>45K</td><td>3个</td><td>有</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥7.4</td><td>¥7.9</td><td>¥8.0</td><td rowspan="4">特别要求:A/D输入电压需&lt;1/2Vcc</td></tr><tr><td>STC90C58AD</td><td>5.5-3.8</td><td>32K</td><td>4352</td><td>29K</td><td>3个</td><td>有</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥8.4</td><td>¥8.9</td><td>¥9.0</td></tr><tr><td>STC90C514AD</td><td>5.5-3.8</td><td>56K</td><td>4352</td><td>5K</td><td>3个</td><td>有</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥9.4</td><td>¥9.9</td><td>¥10.0</td></tr><tr><td>STC90C516AD</td><td>5.5-3.8</td><td>61K</td><td>4352</td><td>-</td><td>3个</td><td>有</td><td>✓</td><td>✓</td><td>39个</td><td>4个</td><td>有</td><td>有</td><td>✓</td><td>✓</td><td>¥10.4</td><td>¥10.9</td><td>¥11.0</td></tr></table>


以上单价为10K/M起定量，以上价格运费由客户承担，零售10片起�， �可来电要求降



用"不需外部时钟/外部复位"的"STC15W404S/STC15W408S/IAP15W413S, 取代89C51/89C52/89C53, 成本用"不需外部时钟/外部复位"的"STC15W1K16S/STC15W1K24S/IAP15W1K29S" 取代89C54/89C58, 成本用 不需外部时钟 外部复位 的 取代 成本更低


宏晶STC90C58AD系列单片机 �A/D转换)

串口可从 $[ \mathrm { P } 3 . 0 / \mathrm { R } \mathrm { x } \mathrm { D }$ ，P3.1/TxD]切换到

[P1.6/RxD，P1.7/TxD]，可当双串口使用

宏晶STC90C58AD系列(带A/D转换)P4口地址在C0H，

其它不带A/D转换 90系列单片机P4口地址在E8H

免费索取

从网上下载样品申请单,

传真至深圳申请STC单片机

样片及ISP下载/编程工具

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/7c3a1d8b72029117992d59ffb0f98473a5efd7d550722c2914144d816bb8bc3f.jpg)



CH340G,价格低于RMB 1.3元


# 选择宏晶•STC90C51系列单片机理由：

超大容量SRAM, 最高达4.2K字节SRAM★

直接取代传统8051单片机，成本更低★

10位A/D，可达25万次/秒★

超强抗干扰：★

1.高抗静电(ESD保护，整机轻松过2万伏静电测试)

2.轻松过4KV快速脉冲干扰(EFT测试)

3.宽电压，不怕电源抖动

4.宽温度范围，-40℃~+85℃

三大降低单片机时钟对外部电磁辐射的措施：★

-出口欧美的有力保证

1.禁止ALE输出；

2.如选6时钟/机器周期，外部时钟频率可降低一半；

3.单片机时钟振荡器增益可设为1/2gain

超低功耗：★

1.掉电模式：典型功耗 <0.1uA

2.正常工作模式 4mA -7mA

3.掉电模式可由外部中断唤醒��，适用�于电�池供电系��统， 如��水表、

气表、 便携设备等。

在系统可编程,无需编程器�及仿真器� �★

送 �B型联机/脱机下载烧录工具 �(人民币100元 1万片/人/天★

全部175℃，8小时高温烘烤，高可靠制造保证★

★强烈推荐LQFP44小型封装★

★尽量不选落后的PDIP和PLCC封装★

# 提供客制化IC设计服务

INT3 P1.0/ADC0/T2 P1.1/ADC1/T2EX ADC3 ADC2 ADC4 

P1.4/ P1.3/ P1.2/ P1.1/A P1.0/A P4.2/ Vcc P0.0 P0.1  P0.2  P0.3 1 

1  44  43  42  41  40 

39个I/O口增加了P4口并可位寻址

27 18  19  20  21  22  23  24  25  26  27  28 

WR/P3.6 RD/P3.7 XTAL2 XTAL1 GndD/P3.7 4.0 20 .  2.1  22 .  23 .  2.4 

39
38
37
36
35
34
33
32
31
30
29 P0.4 P0.5 P0.6 P0.7 P4.7EA P4.1 ALE/P4.5 P4.4/PSEN P2.7 P2.6 P2.5 

Vcc 

# STC micro TM

# 宏 晶 科 技

# 超强抗干扰， 无法解密

8051单片机全球第一品牌，全球最大的8051单片机设计公司全部中国大陆本土独立自主知识产权；品质保证：TSMC上海制造

官方网站：www.STCMCU.com

南通 Tel: 0513-5501 2928 5501 2929深圳 Tel: 0755-8294 8411 8294 8412

# STC15W4K60S4系列1T 8051单片机，4K字节SRAM，超高速四串口，8路10位PWM

不需外部晶振的单片机不需外部复位的单片机

# 送仿真器

全球第一款真正意义上的单片机ISP/IAP技术全球领导者 提

采用宏晶第九代加密技术，现悬赏20万元人民币请专家帮忙查找加密有无漏洞

![image](https://cdn-mineru.openxlab.org.cn/result/2026-04-08/665d5869-307a-49bb-a44f-f0f510f85259/2e7c04737d9ec4cf58a357b240815a2406054e706f6007c6e3d60959f7ad5473.jpg)


以上单价为10K/M起定量，量小每片需加0.1元，以上价格运费由客户承担，零售10片起，如对价格不满，可来电要求降价

上表中以I�RC�开头的单片机固定使用内部24M��Hz时钟或外部晶振�，且其内部复位门槛电压固定�，同时不支持"程序加密后传输"功能（以STC�及

IAP开头的单片机支持"程序加密后传输"功能），无复位管脚，其P5.4不可当复位管脚RST使用，且P3.2/P3.3与下载无关。

程序”能，生成一个用自自己男面的日有一个升经按钮的简单易用的升级款件，给是终使用考自己升级，而希却不

到您的原始程序。

建议用户将串口1设在[P3.6/RxD_2,P3.7/TxD_2]

建议用户将串□1设在[P3.6/F

# 宏晶•STC15W4K60S4系列主要性能：

大容量4096字节片内RAM数据存储器

. 高速： 个时钟/机器周期，增强型 内核，速度比 � 快 ～ 倍

速度也 STC早期的1T系列单片机(如STC12/11/10系列)的速度快20%

宽电压：2.4V～5.5V●

低功耗设计：低速模式，��模式，掉电模式 可由外部中断或内部掉电唤醒定时器●

. 不需外部复位的单片机，ISP编程时16级复位门槛电压可选，内置高可靠复位电路

● 不需外部晶振的单片机，ISP编程时内部时钟从5MHz~35MHz可设 � � 8051：60～420MHz)

内部高精度R/C时钟(±0.3%)，±1%温飘(-40℃~+85℃)，常温下温飘±0.6%(-20℃~+65℃)

支持掉电唤醒的资源有：INT0/INT1(上升沿/下降沿中断均可), INT2/INT3/INT4(下降沿中断)；CCP0/●CCP1/RxD/RxD2/RxD3/RxD4/T0/T1/T2/T3/T4管脚；内部掉电唤醒专用定时器

16/32/40/48/56/60/61K/63.5K字节片内Flash程序存储器，擦写次数10万次以上●

·大容量片内EEPROM功能擦写次数10万次以上

ISP/IAP，在系统可编程/在应用可编程,无需编程器/仿真器●

高速 ， 通道 位，速度可达 万次/秒 路PWM还可当 路 使用●

● 比较器，可当1路ADC使用，并可作掉电检测，支持外部管脚CMP+与外部管脚CMP-进行比较，可产生中断，并可在管脚CMPO上产生输出（可设置极性），也支持外部管脚CMP+与内部参考电压进行比较

8通道PWM(可选10位或8位), 其包括2通道CCP(捕获/比较/PWM)和6通道专门的PWM(带死区控制)-可用来再实现8路D/A,或2个16位定时器，或2个外部中断(支持上升沿/下降沿中断)

·共7个定时器/计数器，5个16位可重装裁定时器/计数器(T0/T1/T2/T3/T4其中T0和T1兼容普通8051的定时器/计数器)，并均可实现时钟输出，另外管脚MCLKO可将内部主时钟对外分频输出（÷1或-2或六4）。路 可再实现 个定时器

可编程时钟输出功能(对内部系统时钟或外部管脚的时钟输入进行时钟分频输出)：$\textcircled{1}$ T0在P3.5输出时钟； $\textcircled{2}$ T1在P3.4输出时钟； $\textcircled{3}$ T2在P3.0输出时钟； $\textcircled{4}$ T3在P0.6输出时钟； $\textcircled{5}$ T4在P0.4输出时钟，以上5个定时器/计数器输出时钟均可1~65536级分频输出； $\textcircled{6}$ 内部主时钟在P5.4/MCLKO对外输出时钟(STC15系列8-pin单片机的主时钟在P3.4/MCLKO对外输出时钟)

■、超高速四串口/UAPT，四个完全独立的高速异步串行通信端口，分时切换可当9组串口使用

高速同步串行通信接口●

硬件看门狗(WDT)●

先进的指令集结构，兼容普通 指令集，有硬件乘法/除法指令●

通用 口( 个)�，复位后�为：准双�向口/�弱上�拉( 传统 口)●

可设置四种模式：准双向口/弱上拉， 强��推挽 /强上��拉， 仅�为输入/高���阻，开 漏

每个I/O口驱动能力均可达到20mA，但整个芯片最大不要超过120mA

# 选择宏晶•STC15W4K60S4系列单片机理由：

8通道PWM(可选10位或8位), 其包括2通道CCP(捕获/比较/PWM)和6通道专门的PWM(带死区控制)★-可用来再实现 路 或 个 位定时器，或 个外部中断 支持上升沿 下降沿中断

↓ 无法解密，宏晶第九代加密技术，现悬赏 万元人民币请专家帮忙查找加密有无漏洞

超强抗干扰：★

1.高抗静电(ESD保护)整机轻松过2万伏静电测试

3.宽电压，不怕电源抖动

大幅降低 ，内部可配置时钟，1个时钟/机器周期，可用低频时钟★

-出口欧美的有力保证

超低功耗：★

1. <0.1uA 

2.空闲 模式:典型功耗 <1mA,

4.掉电模式可由外部中断或内部掉电唤醒专用定时器唤醒,适�用于�电池�供电系统�,如������水表、气表等

★、在系统可仿真 在系统可编程 天需专用编程器 天需专用仿直器 可远程升纸

可送 �B型联机/脱机下载烧录工具 �(人民币100元★