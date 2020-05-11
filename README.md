# tudui-os-tutorial
**操作系统笔记及 Linux 0.11 项目实战（土堆教程）**

这是自己学习操作系统的笔记，记录了自己的一些思考。

同时，以 Linux 0.11 作为一个项目，在学习相应知识的基础上，去改动和添加 Linux 0.11 的部分实现。

更多教程，请关注 [土堆教程](https://github.com/xiaotudui/tudui-tutorials)

---

### 教程目录

#### 操作系统

1. [什么是操作系统](\notes\os\什么是操作系统.md)
2. 异常
3. 系统调用
4. 解密Linux异常

#### 进程

1. [程序是如何运行起来的？什么是进程？](/notes/process/1.什么是进程？.md)
2. 第一个进程创建全过程
3. 后续进程的创建
4. 进程的初始化
5. 进程间通信与实战

#### 线程

1. 什么是线程？与进程的区别
2. 线程的创建
3. 线程切换
4. 线程间通信与实战

#### 虚拟内存

1. 内存的管理与使用
2. [分段](/notes/memory/1.%20分段.md)
3. 分页
4. 段页结合
5. 内存管理全过程梳理
6. 共享内存

#### 多线程

1. 锁
2. 信号量

#### 文件

1. 文件系统

---

### 参考书籍

[《操作系统导论》【免费，推荐】](https://github.com/remzi-arpacidusseau/ostep-translations/tree/master/chinese)

[《深入理解计算机系统》](https://book.douban.com/subject/26912767/)

[《操作系统概念》](https://book.douban.com/subject/4289836/)

[《Linux内核完全剖析》](https://book.douban.com/subject/3229243/) （注意：要看 0.11 版本）

**看书，可以按照笔记目录提及的章节来看，笔记开头会讲解关联到书中的哪些章节。**

---

### 参考视频

[操作系统（哈工大李治军老师）32讲（全）超清](https://www.bilibili.com/video/BV1d4411v7u7)

---

### 练手项目

主要在 Linux 0.11 基础上，对 进程切换、多线程、虚拟内存上进行部分添加实现或改动。

* 将 Linux 0.11 的进程切换，改为基于内核栈的进程切换；
* 添加信号量的实现；
* 为 Linux 0.11 添加共享内存的功能；

