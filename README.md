# 三体MATLAB模拟

## 所需软件

MATLAB较近版本。笔者本人用的是MATLAB R2018a。

## 编码

文件内所有中文编码为utf-8。用MATLAB打开时可能会出现乱码。

## 运行

打开three_body_main.m文件，运行即可。

## 简介

本程序用于模拟多个有质量质点在二维平面内受到万有引力运动的运动情况。

- 初始条件: 坐标, 速度大小, 速度方向, 质量
- 基础参数: 结束时间, 时间间隔, 万有引力系数, 输出图像边界大小, 是否输出图像
- 输出文件: 该程序运行完毕后, 会在改文件夹下创建出three_body.avi视频文件