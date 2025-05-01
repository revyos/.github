# RevyOS

[English](https://github.com/revyos/docs/blob/master/docs/./index.en.md)

## 简介

[RevyOS](https://github.com/orgs/revyos/repositories)是由 RuyiSDK 团队的 RevyOS 小队支持开发的一款针对 XuanTie 生态芯片的 Debian 优化定制发行版。

RevyOS 是 [RuyiSDK](https://ruyisdk.org/) 的一部分。RuyiSDK 是一个由 [PLCT Lab](https://plctlab.org/en/) 所启动的开源项目，该项目旨在为 RISC-V 开发者提供一个便捷、完善的开发环境，其提供了相关最新的硬件信息、软件支持，例如在支持的设备中有提供相关支持硬件情况；软件层面提供了镜像（如 RevyOS）、工具链、包管理器等。

__RevyOS__ 围绕玄铁 C906、C910、C920、C908 等芯片提供了完整而全面的适配和优化支持，默认集成支持玄铁扩展指令集和 RVV 1.0 的 GCC 工具链，并搭载使用 RVV 1.0 指令集优化过的 Glibc 和 Kernel。

目前，__RevyOS__ 在办公、网页浏览、观看视频等方面已经能满足用户的基本使用需求。

基于上述定制和优化的 __RevyOS__，在 Milk-V Meles，LicheePi 4A 等硬件平台上，能够提供优秀的性能和极佳的体验。

## 镜像下载

__RevyOS__ 的用户版镜像目前在 ISCAS（中国科学院软件研究所）开源镜像站进行更新。如您想获取 __RevyOS__ 最新版镜像请访问[镜像下载](https://mirror.iscas.ac.cn/revyos/extra/images/)目录，根据所使用设备来获取对应镜像。在下载完成后，请点击[镜像刷写](https://github.com/revyos/docs/blob/master/docs/./Installation/install.md)获取对应设备的镜像刷写教程。

| 支持设备          | 镜像下载（最新版本）                                                             |  SD 卡支持 |
| ----------------- | -------------------------------------------------------------------------------- | --------- |
| Lichee Pi 4A      | [20250123](https://mirror.iscas.ac.cn/revyos/extra/images/lpi4a/20250123/)       | 支持       |
| Milk-V Meles      | [20250123](https://mirror.iscas.ac.cn/revyos/extra/images/meles/20250123/)       | 支持       |
| Milk-V Pioneer    | [20241230](https://mirror.iscas.ac.cn/revyos/extra/images/sg2042/20241230/)      | 支持       |
| Lichee Cluster 4A | [20240720](https://mirror.iscas.ac.cn/revyos/extra/images/lpi4a/)                |           |
| Lichee Console 4A | [20240720](https://mirror.iscas.ac.cn/revyos/extra/images/lcon4a/20240720/)      |           |
| Lichee Book 4A    | [20240720](https://mirror.iscas.ac.cn/revyos/extra/images/laptop4a/)             |           |
| Beagle-Ahead      | [20231210](https://mirror.iscas.ac.cn/revyos/extra/images/beagle/20231210/)      |           |
| Huiwei book       | [20240617](https://mirror.iscas.ac.cn/revyos/extra/images/huiwei/test/20240617/) |           |

### 如何启用 T-Head 优化 GCC

详见这篇文档[如何启用优化 GCC](https://github.com/revyos/docs/blob/master/docs/build/debian/enable_optimization_gcc.md)

## 更新日志

镜像版本更新后我们会公布当前版本镜像支持内容，如您想查看镜像支持内容请点击[RevyOS 版本更新日志](https://github.com/revyos/docs/blob/master/docs/./changelog/changelog-index.md)后选择您所需要的版本进行查看。

## issue 相关

如果您在使用过程中遇到问题，可以进行[issue 申报](https://github.com/revyos/docs/blob/master/docs/./issue.md)。

## 用户文档

在本 DOCS 中，我们拥有相关的使用构建与适配文档以及测试文档方便让用户对部分内容进行参考，完善的文档支持加快了用户对于系统的上手时间。

## 用户群组

RevyOS 有自己的 Telegram 群组：[邀请链接](https://t.me/+Pi6px22-OsUxM2M1)

## 实习生招聘

现在正在招聘测试实习生，详情请看：[RevyOS 小队测试实习生招聘](https://github.com/plctlab/weloveinterns/blob/master/open-internships.md#j143-revyos%E5%B0%8F%E9%98%9F%E6%B5%8B%E8%AF%95%E5%AE%9E%E4%B9%A0%E7%94%9F20241111%E5%BC%80%E6%94%BE100%E5%90%8D)
