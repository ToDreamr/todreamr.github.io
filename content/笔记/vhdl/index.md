---
title: "状态机"
date: 2023-10-12T19:01:39+08:00
tags : ["硬件语言"]
---


### 有限状态机
寄存器和组合时序逻辑电路构成硬件时序逻辑电路

特点：只能在时钟沿发生跳变时才能完成状态转移，状态机可以在时钟跳变时完成复杂的任务。

### 状态机的结构

状态寄存器由一组寄存器构成,n个寄存器可存储2^n个状态

输出取决于状态和输入时，这样的状态机称为Mealy状态机，只和当前状态有关的称为Moore状态机

描述有限状态机的方法：
always语句和case语句

