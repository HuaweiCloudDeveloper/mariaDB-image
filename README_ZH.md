 <h1 align="center">MariaDB数据库</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>


## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍

[MariaDB](https://github.com/MariaDB/server) 是一个开源的关系型数据库管理系统，由 MySQL 的创始人 Michael Widenius 主导开发，旨在提供完全兼容 MySQL 的同时，实现更快的开发迭代和更强的扩展性‌。本商品基于鲲鹏服务器的Huawei Cloud EulerOS 2.0 64bit系统，提供开箱即用的MariaDB。

## 核心特性

- **开发背景‌：** 
  - 作为 MySQL 的分支出现，应对 Oracle 收购 MySQL 后的闭源风险
  - 由 MariaDB 基金会维护，采用 GPLv2 许可协议
- **技术兼容性：** 
  - 与 MySQL 保持二进制兼容，支持无缝迁移
  - 兼容 MySQL 的 API、命令行、文件格式和连接器
- **‌存储引擎‌：** 
  - 默认使用 XtraDB（InnoDB 增强版）和 Maria 存储引擎
  - 包含 PrimeBase XT 和 FederatedX 等扩展引擎
- **性能优势：** 
  - 在高并发读写场景下性能比 MySQL 提升 13%-22%
  - 原生支持 Galera Cluster 多主同步集群


本项目提供的开源镜像商品 [**MariaDB数据库**](https://marketplace.huaweicloud.com/hidden/contents/ee4ce35a-358b-4463-a583-22e2d06e4990#productid=OFFI1164144698985668608) 已预先安装10.4.34版本的Memcached及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。


> **系统要求如下：**
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                      | 特性说明 | 备注 |
|-----------------------------------------------------------------------------------------------------------| --- | --- |
| [MariaDB-10.4.34-kunpeng](https://github.com/HuaweiCloudDeveloper/memcached-image/tree/MariaDB-10.4.34-kunpeng) | 基于鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/mariaDB-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md
