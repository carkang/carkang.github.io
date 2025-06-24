---
layout: post
title: PAM3是什么？
categories: PAM3
description: Automoitve Ethernet T1
keywords: PAM3, 10Base-T1,100Base-T1
mermaid: false
sequence: false
flow: True
mathjax: false
mindmap: false
mindmap2: false
---

PAM3是什么？
PAM是Pulse Amplitude Modulation的缩写，大家可能对PWM比较熟。
PAM3是通过变换脉冲的幅度，通过三种电平，正负零来传输信号的。
不像CAN总线，LIN总线，FlexRay总线上的电平只有0，1两种状态，车载以太网的PAM3多出一种状态-1，这样通过编码就可以用较低的波特率传输更多的数据。
类似于用三进制表达二进制的数据需要的数据长度更短。这样100BaseT1的波特率其实只需要66.6MHz就可以完成100Mbps的数据传输。
