---
title: 基础参数
order: 4
icon: star-half
---

在获取`AiISP`工具后，我们就可以简单测试工具了，需要注意这几个基础参数。

## -c, --chip <目标芯片型号>

该参数用来指示当前的芯片型号，目前只支持`air001`。

## -p, --port <串口名称>

该参数用来指示是所有的串口名称，如`COM12`、`/dev/ttyUSB2`。

## -b, --baud <串口波特率>

该参数用来表示通信时需要使用的波特率，如若使用劣质串口转USB芯片导致通信失败，需要降低波特率再试，比如`9600`。

## -e,--erase-all

如果加上了这个参数，表示会先全片擦除后在进行接下来的操作。

:::tip

烧录固件时请务必加上这个参数，未擦除的时候刷入的固件一般跑不起来。

:::