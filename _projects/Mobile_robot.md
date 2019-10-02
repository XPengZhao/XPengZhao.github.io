---
layout: page
title: Mobile Robot
description: base on Raspberry Pi or Arduino
img: /assets/img/backdrop.jpg
---

# Readme

> 具体代码请参见Github链接:  
> Raspberry: <https://github.com/XPengZhao/rpi-alphabot2>  
> Arduino: <https://github.com/XPengZhao/Carduino>  
> STM32: <https://github.com/XPengZhao/AGV>

这三个项目是智能小车的入门级项目。三个项目设计由易到难。下面是三个项目的简介，详细介绍请查看Github链接。

## 1. Raspberry小车

小车的主控板为Raspberry Pi 3B，根据小车搭载的硬件，实现以下的基本功能：

- 能够顺着地上的黑色线条自动循迹
- 对于没有黑线的地方，通过Socket进行命令传输，从而控制运动，并可通过图形界面控制。
- 对于前方有障碍物，能够自动停止前进。

## 2. Arduino小车

包含了三个小项目，均基于Arduino开发，由易到难分别为：

- 循迹小车
- 蓝牙遥控小车
- 双轮自平衡车
- 重力感应遥控（MPU6050)的自平衡车（通过MPU6050进行手势控制）

## 3. STM32小车

小车的主控板为STM32F103，具有以下功能：

- 装有mecanum wheels，可实现全向运动
- 可由PS2手柄进行控制
- 基于MPU6050与编码器积分的移动位置计算