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
| 卷操作 | ![create](https://img.shields.io/badge/-创建-blue) ![delete](https://img.shields.io/badge/-删除-blue) ![details](https://img.shields.io/badge/-详情-blue) ![resize](https://img.shields.io/badge/-扩展-blue) | ![create](https://img.shields.io/badge/-创建-blue) ![delete](https://img.shields.io/badge/-删除-blue) ![details](https://img.shields.io/badge/-详情-blue) ![resize](https://img.shields.io/badge/-扩展-blue) ![migrate](https://img.shields.io/badge/-迁移-brightgreen) ![clone](https://img.shields.io/badge/-克隆-brightgreen) ![copy](https://img.shields.io/badge/-拷贝-brightgreen) ![snapshot](https://img.shields.io/badge/-快照-brightgreen) |
| QoS 策略 | ![rebalance](https://img.shields.io/badge/-负载均衡-blue) | ![rebalance](https://img.shields.io/badge/-负载均衡-blue) ![access](https://img.shields.io/badge/-数据访问-brightgreen) ![rebuild](https://img.shields.io/badge/-数据重构-brightgreen) |
| 驱动 |  | ![csi](https://img.shields.io/badge/-Kubernetes%20CSI-brightgreen) |
| 实时技术支持 | ![Build documentation](https://img.shields.io/badge/-不支持-red)| ![Build documentation](https://img.shields.io/badge/-支持-brightgreen) |

# 快速上手
如果您使用的是类 UNIX 系统（如 Linux），可以通过键入下列命令进行编译和安装：

## 在 CentOS 系统编译
```bash
make
```
## 在 Ubuntu 系统编译
```bash
make
```

## 在 CentOS 系统安装
```bash
make install
```
## 在 Ubuntu 系统安装
```bash
make install
```

# 更多文档
请参阅 [详细开发文档和使用说明](https://github.com/lanewu/dbs/wiki)。

# 贡献代码

## 当前构建状态
| 操作系统/编译环境   | 状态        | 
| ------------- |:-------------:| 
| CentOS/Java 8 | ![CI (Linux)](https://github.com/mamedev/mame/workflows/CI%20(Linux)/badge.svg) |
| Ubuntu/Java 8 | ![CI (Windows)](https://github.com/mamedev/mame/workflows/CI%20(Windows)/badge.svg) |
| UI | ![Compile UI translations](https://github.com/mamedev/mame/workflows/Compile%20UI%20translations/badge.svg) |
| 文档 | ![Build documentation](https://github.com/mamedev/mame/workflows/Build%20documentation/badge.svg) |

## 编码标准
请在编辑器中设置2空格缩进后，查看和编辑本项目的源代码，每个缩进级别使用一次缩进。空格可用于一行内的其他对齐方式。

大部分代码遵循 [Google Java 风格](https://google.github.io/styleguide/javaguide.html)；也有一些代码遵循 [Oracle 编码约定](https://www.oracle.com/java/technologies/javase/codeconventions-contents.html) —— 这主要取决于最初的版本。 **最重要的是，您修改代码的时候请保持一致，并在修改现有源代码时将空格更改保持在最低限度。** 对于新代码，请使用 Google Java 风格。

## 提交代码
完成代码开发后，您应该向 master 分支提交拉取请求 (PR) 并填写拉取请求模板。拉取请求会自动触发持续整合 (CI) 流程，代码只有在通过 CI 并审核后才会被合并。 如果 CI 运行失败，您可以登录 Jenkins 平台查看失败原因。虽然在审核您的 PR 之前必须满足上述先决条件，但审核者可能会要求您完成额外的设计工作、测试、或其他更改，然后才能最终接受 PR。

更多详细信息，请参阅 [CONTRIBUTING](CONTRIBUTING.md)。

# 许可证
[AGPL 3.0](LICENSE)
