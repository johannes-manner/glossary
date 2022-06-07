---
title: 容器
status: Completed
category: 技术
---

## 是什么

容器是由计算机操作系统管理的具有资源和能力限制的运行进程。
容器进程可用的文件被打包为容器镜像。
容器在同一台机器上彼此相邻运行，但通常操作系统会阻止单独的容器进程相互交互。

## 解决的问题

在容器可用之前，需要单独的机器来运行应用程序。每台机器都需要自己的操作系统，它占用 CPU、内存和磁盘空间，
所有这些都是为了让单个应用程序运行。此外，操作系统的维护、升级和启动是另一个重要的工作来源。

## 如何帮助

容器共享相同的操作系统及其机器资源，分散了操作系统的资源开销并创建了物理机器的有效使用。
这种能力之所以成为可能，是因为容器之间的交互通常受到限制。
这允许更多的应用程序在同一台物理机器上运行。

但是，有一些限制。由于容器共享相同的操作系统，因此可以认为进程不如替代方法安全。 容器还需要对共享资源进行限制。 为了保证资源，
管理员必须约束和限制内存和 CPU 的使用，以使其他应用程序不会表现不佳。
