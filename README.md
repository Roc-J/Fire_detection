#  A simple fire detector火焰检测 视频检测

## Introduction

这是一个简单的采用OpenCV编写的识别视频中着火点的程序。通过输入一个视频，输入一个视频然后一帧一帧的处理视频。主要是将色彩空间转换为HSV空间，通过对HSV空间的颜色相对RGB的来说更符合人类视觉。通过设置颜色的高低阈值来设置mask来对每一帧进行处理，得到我们定义的色彩。

## How to run

直接运行python程序即可。

## 要求

> 1. Python2.7
> 2. 已经安装好openCV以及numpy包



