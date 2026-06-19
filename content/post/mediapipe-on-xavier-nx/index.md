---
title: "TensorRT部署MediaPipe Hands全过程"

date: 2026-06-18

draft: false

categories:
- Coding

tags:
- TensorRT
- MediaPipe
- Jetson
---

# 前言

本文记录 Jetson Xavier NX 上部署 MediaPipe Hands 的全过程。

# 环境配置

JetPack 5.1.2

TensorRT 8.5

OpenCV 4.8

# 遇到的问题

1. ROI 裁剪方向错误
2. 左右手判定问题

# 性能优化

单帧推理时间约 15 ms。

# 总结

部署成功，实现双手实时跟踪。