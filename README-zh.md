# ZettaStor DBS

[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/1486/badge)](https://bestpractices.coreinfrastructure.org/projects/1486)
[![LICENSE](https://img.shields.io/badge/licence-AGPL--3-blue.png)](https://github.com/lanewu/dbs/blob/master/LICENSE)

[English](README.md) | 简体中文

# 项目简介

云计算是产业发展的潮流和趋势，对于传统企业来说，云环境部署更加复杂。块存储作为云上不可或缺的一部分，其可靠性和稳定性至关重要。
ZettaStor DBS 可为大规模虚拟化、私有云和容器环境，提供高可用、高性能、易扩展、易维护的企业级用户业务存储解决方案，成为核心应用坚实的数据底座。

- [x] IT技术架构升级：采用软件定义技术，池化共享存储资源，支持多场景应用，避免竖井架构
- [x] 节约总体成本：基于标准服务器和IP网络硬件，完美兼容，比传统存储降低TCO60%以上
- [x] 按需定制灵活扩容：横向扩展、线性扩容，性能容量按需增减，降低扩容成本
- [x] 无缝迁移安全高效：原有系统无需修改，迁移简单，可视化操作

| 功能特性 | 社区版  | 商业版 | 
| ------------- | ------------- |  ------------- | 
| 去中心化架构 | ![CI (Linux)](https://img.shields.io/badge/-支持-brightgreen)| ![CI (Linux)](https://img.shields.io/badge/-支持-brightgreen) |
| 亚毫秒级延迟 | ![CI (macOS)](https://img.shields.io/badge/-支持-brightgreen) | ![CI (macOS)](https://img.shields.io/badge/-支持-brightgreen) |
| 大规模节点部署 | ![CI (Windows)](https://img.shields.io/badge/-支持-brightgreen) | ![CI (Windows)](https://img.shields.io/badge/-支持-brightgreen) |
| 实时技术支持 | ![Build documentation](https://img.shields.io/badge/-不支持-red)| ![Build documentation](https://img.shields.io/badge/-支持-brightgreen) |
| 系统节点规模 | ![minimum](https://img.shields.io/badge/最小-%E2%89%A53-blue) ![maximum](https://img.shields.io/badge/最大-%E2%89%A510000-blue) | ![minimum](https://img.shields.io/badge/最小-%E2%89%A53-blue) ![maximum](https://img.shields.io/badge/最大-%E2%89%A510000-blue) |
| 数据冗余模式 | ![redundancy](https://img.shields.io/badge/-2%20副本-blue) | ![redundancy](https://img.shields.io/badge/-2%20副本-blue) ![redundancy](https://img.shields.io/badge/-3%20副本-blue) |
| 前端访问协议 | ![SCSI](https://img.shields.io/badge/-scsi-blue)  ![ISCSI](https://img.shields.io/badge/-iscsi-blue) | ![SCSI](https://img.shields.io/badge/-scsi-blue)  ![ISCSI](https://img.shields.io/badge/-iscsi-blue) ![CIFS](https://img.shields.io/badge/-cifs-blue)  ![NFS](https://img.shields.io/badge/-nfs-blue)  |

# Quick Start

## Installation on CentOS

If you're on a UNIX-like system (including Linux and macOS), it could be as easy as typing

```bash
make install
```
## Installation on Ubuntu
```bash
make install
```

# Where can I find out more?
Documentation

# Contributing

## Coding standard
Source code should be viewed and edited with your editor set to use four spaces per tab. Tabs are used for initial indentation of lines, with one tab used per indentation level. Spaces are used for other alignment within a line.

Some parts of the code follow [Allman style](https://en.wikipedia.org/wiki/Indent_style#Allman_style); some parts of the code follow [K&R style](https://en.wikipedia.org/wiki/Indent_style#K.26R_style) -- mostly depending on who wrote the original version. **Above all else, be consistent with what you modify, and keep whitespace changes to a minimum when modifying existing source.** For new code, the majority tends to prefer Allman style, so if you don't care much, use that.

## Submit your code
After finishing the development of your code, you should submit a pull request to master branch and fill out a pull request template. The pull request will trigger the CI automatically, and the code will only be merged after passing the CI and being reviewed. The Jenkins username and password of CI is netease/netease. If the CI fails to run, you can login to the Jenkins platform to view the reason for the failure.While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

For more details, please refer to [CONTRIBUTING](CONTRIBUTING.md).

# License
[AGPL 3.0](LICENSE)
