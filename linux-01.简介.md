<!-- TOC -->

- [1. 第一章：linux操作系统简介](#1-第一章linux操作系统简介)
  - [1.1. linux系统的特点和组成](#11-linux系统的特点和组成)
    - [1.1.1. linux系统的特点：](#111-linux系统的特点)
    - [1.1.2. linux系统组成](#112-linux系统组成)
      - [1.1.2.1. 内核](#1121-内核)
      - [1.1.2.2. Shell](#1122-shell)
      - [1.1.2.3. 文件系统](#1123-文件系统)
      - [1.1.2.4. 应用程序](#1124-应用程序)
    - [1.1.3. linux系统与Windows系统比较](#113-linux系统与windows系统比较)
  - [1.2. linux版本号](#12-linux版本号)
- [2. 主流Linux发型版本](#2-主流linux发型版本)
  - [2.1. Red Hat概述](#21-red-hat概述)

<!-- /TOC -->
# 1. 第一章：linux操作系统简介
1. 免费的、多用户、多任务，运行方式、功能和UNIX系统很相似，但linux系统的稳定性、安全性与网络功能是许多商业操作系统所无法比拟的
2. 应用涉及方法：
    1. linux应用服务器
        + 支持多种硬件平台，容易和系统共存
    2. 嵌入式linux系统领域
        + 嵌入式操作系统在该领域的低成本、小内核以及模块化有着自己的特色。
    3. 软件开发平台
        + linux开发者可以使用C、C++、Perl、PHP来开发应用程序
    4. 桌面应用
        + 集办公应用、多媒体应用、游戏娱乐和网络应用等多方面功能于一体的图形界面操作系统
    
## 1.1. linux系统的特点和组成

### 1.1.1. linux系统的特点：
1. 开放性：
    1. 源代码完全公开
    2. 在符合GNU/GPL(通用公共许可证)的原则，任何人都可以自由取得、传播甚至修改源代码。
    3. 遵守开放系统互联(OSI)国际标准.
2. 多用户:
    1. 是指系统资源可以被不同用户各自拥有、使用，每个用户对自己的资源有特定的权限，并且互不影响。
3. 多任务：
    1. 计算机可以同时执行多个程序，并且每个程序的处理相互独立。
    2. linux系统调度每一个进程，平等地访问计算机处理器。
4. 良好的用户界面
    1. 文本界面(Shell)
    2. 图形界面
5. 设备独立性:
    1. 是指操作系统把所有外设统一当做文件来看待，只要安装他们的驱动设备统一当做文件来看待，只要安装他们的驱动程序，任何用户都可以像使用文件一样操纵、使用这些设备，而不必知道它们的具体存在形式。
6. 丰富的网络功能：提供了完善、强大的网络
7. 可靠的系统安全
    1. 采取了很多措施保证系统安全
    2. 对读写进权限控制
    3. 带保护措施的子系统
    4. 审计跟踪
    5. 核心授权
8. 良好的可移植性
    1. 是指操作系统从一个平台转移到另一个平台时，它仍然能按其自身的方式运行的特征。
    2. 可以从微型计算机到大型计算机。

### 1.1.2. linux系统组成
#### 1.1.2.1. 内核

1. 内核是操作系统的核心，具有很多最基本的功能，如虚拟内存、多任务、共享库、需求加载、可执行程序和TCP/IP网络功能。
2. 主要模块：
    1. 存储管理
    2. CPU和进程管理
    3. 文件系统
    4. 设备管理和驱动
    5. 网络通信
    6. 系统的初始化和系统调用

#### 1.1.2.2. Shell
1. 系统的用户界面，提供了用户与内核进行交互操作的一种接口。它接收用户输入的命令并把它送入内核去执行。
2. Shell编程语言具有普通编程语言的很多特点。

#### 1.1.2.3. 文件系统
1. 文件系统是指文件放在磁盘等存储设备上的组织方法
2. 支持的文件系统:ext3、ext4、FAT、FAT32、VFAT和ISO9660等。
   1. ext4:最新版本

#### 1.1.2.4. 应用程序
1. 包含：
    1. 文本编辑器
    2. 编程语言
    3. XWindow
    4. 办公软件
    5. Internet工具和数据库

### 1.1.3. linux系统与Windows系统比较
1. 共性
    1. 多用户操作系统
    2. 支持多种文件系统
    3. 支持多种端口和设备
    4. 支持联网功能
    5. 服务
2. 区别：见PPT

## 1.2. linux版本号
1. 分为两部分:
    1. 内核版本
        + 内核版本号由r.x.y三个字母组成
        + r:目前发布的内核主版本
        + x:偶数表示稳定版本，奇数表示开发版本
        + y:错误修补的次数
    2. 发行版本：
        + 一些组织和厂家，将Linux系统的内核、 应用软件和文档包装起来，并提供一些系统安 装界面、系统配置设定管理工具，就构成了Linux发行版本，相对于Linux操作系统内核版本，各发布厂商发行版本的版本号各不相同，与Linux系统内核的版本号是相对独立的。

# 2. 主流Linux发型版本
1. Oracle:在linux发表之后进行下载
2. CentOS
3. Red Hat:
4. 上述三个差别不大

## 2.1. Red Hat概述
1. Red Hat Linux是初学linux系统的最佳选择。