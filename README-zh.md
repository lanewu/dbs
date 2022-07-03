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

# 贡献代码

## 编码标准
请在编辑器中设置4空格缩进后，查看和编辑本项目的源代码。制表符用于行的初始缩进，每个缩进级别使用一个制表符。空格用于一行内的其他对齐方式。

部分代码遵循 [Allman 风格](https://en.wikipedia.org/wiki/Indent_style#Allman_style)；部分代码遵循 [K&R 风格](https://en.wikipedia.org/wiki/Indent_style#K.26R_style) ———— 这主要取决于最初的版本。 **最重要的是，您修改代码的时候请保持一致，并在修改现有源代码时将空格更改保持在最低限度。** 对于新代码，大多数人倾向于 Allman 风格，因此请尽量使用这种风格。

## 提交代码
完成代码开发后，您应该向 master 分支提交拉取请求 (PR) 并填写拉取请求模板。拉取请求会自动触发持续整合 (CI) 流程，代码只有在通过 CI 并审核后才会被合并。 如果 CI 运行失败，您可以登录 Jenkins 平台查看失败原因。虽然在审核您的 PR 之前必须满足上述先决条件，但审核者可能会要求您完成额外的设计工作、测试、或其他更改，然后才能最终接受 PR。

更多详细信息，请参阅 [CONTRIBUTING](CONTRIBUTING.md)。

# 许可证
[AGPL 3.0](LICENSE)
