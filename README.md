# Embedded-V4L2-Camera-System
本项目是一个基于 Linux V4L2 框架开发的高性能相机流处理模块。项目实现了从底层硬件（USB/MIPI 摄像头）采集原始视频帧，经过色彩空间转换与图像缩放算法处理，最终在本地 Framebuffer 显示及通过 MJPG-Streamer 进行网络远程推送的完整链路。
