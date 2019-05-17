![](docs/resource/img/BKCN.jpg)
---
[![license](https://img.shields.io/badge/license-mit-brightgreen.svg?style=flat)](https://github.com/Tencent/bk-cmdb/blob/master/LICENSE)
[![Release Version](https://img.shields.io/badge/release-3.2.2-brightgreen.svg)](https://github.com/Tencent/bk-cmdb/releases)
[![Build Status](https://travis-ci.org/Tencent/bk-cmdb.svg?branch=master)](https://travis-ci.org/Tencent/bk-cmdb)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Tencent/bk-cmdb/pulls)

[(English Documents Available)](readme_en.md)

> **重要提示**: `master` 分支在开发过程中可能处于 *不稳定或者不可用状态* 。
请通过[releases](https://github.com/tencent/bk-cmdb/releases) 而非 `master` 去获取稳定的二进制文件。

蓝鲸配置平台（蓝鲸CMDB）是一个面向资产及应用的企业级配置管理平台。

蓝鲸配置平台提供了全新自定义模型管理，用户不仅可以方便地实现内置模型属性的拓展，同时也能够根据不同的企业需求随时新增模型和关联关系，把网络、中间件、虚拟资源等纳入到CMDB的管理中。除此之外还增加了更多符合场景需要的新功能：机器数据快照、数据自动发现、变更事件主动推送、更加精细的权限管理、可拓展的业务拓扑等功能。

在技术构建上，架构的核心聚焦于资源，我们把CMDB管理的原子资源分为主机、进程和通用对象三种类型，并构建了对这些资源的原子操作层。在这些原子操作之上，我们构建了更贴近用户操作的场景层，场景层通过对不同资源的组合操作来完成用户的请求。

![front-page](docs/resource/img/frontpage.jpg)

## Overview
* [架构设计](docs/overview/architecture.md)
* [代码目录](docs/overview/code_framework.md)
* [设计理念](docs/overview/design.md)
* [使用场景](docs/overview/usecase.md)

## Features
* 拓扑化的主机管理：主机基础属性、主机快照数据、主机归属关系管理
* 组织架构管理：可扩展的基于业务的组织架构管理
* 模型管理：既能管理业务、集群、主机等内置模型，也能自定义模型
* 进程管理：基于模块的主机进程管理
* 事件注册与推送：提供基于回调方式的事件注册与推送
* 通用权限管理：灵活的基于用户组的权限管理
* 操作审计：用户操作行为的审计与回溯

如果想了解以上功能的详细说明，请参考[功能说明](http://bk.tencent.com/document/bkprod/000120.html)

## Experience

[极速体验容器化部署蓝鲸CMDB](docs/wiki/container-support.md)

## Getting started
* [下载与编译](docs/overview/source_compile.md)
* [安装部署](docs/overview/installation.md)
* [API使用说明](docs/apidoc/readme.md)
* [使用CMDB开源版替换社区版](docs/overview/upgrade-from-ce.md)

## Version plan
* [版本迭代](docs/VERSION.md)

## Support
1. 阅读 [wiki](https://github.com/Tencent/bk-cmdb/wiki/cmdb-3.0) 或者寻求帮助
2. 常见 [FAQ](https://github.com/Tencent/bk-cmdb/wiki/FAQ)
3. 了解蓝鲸社区相关信息：[蓝鲸社区版交流1群](https://jq.qq.com/?_wv=1027&k=5zk8F7G)
4. 联系我们，bk-cmdb技术交流QQ群(305496802), 扫码入群戳[这里](docs/resource/img/qq.png)。


## Contributing
关于 bk-cmdb 分支管理、issue 以及 pr 规范，请阅读 [bk-cmdb Contributing Guide](docs/CONTRIBUTING.md)。  
[腾讯开源激励计划](https://opensource.tencent.com/contribution) 鼓励开发者的参与和贡献，期待你的加入。

**合作伙伴：**

![jiawei](docs/resource/img/jiawei-logo.png)　　![youole](docs/resource/img/youole-logo.png)　　![yuanding](docs/resource/img/yuanding-logo.png)

## License
bk-cmdb 是基于 MIT 协议， 详细请参考 [LICENSE](LICENSE) 。
