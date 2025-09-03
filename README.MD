<h1 align="center">MariaDB Database</h1>
  <p align="center">
    <strong>English</strong> | <a href="README_ZH.md"><strong>Simplified Chinese</strong></a>
  </p>


## Table of Contents

- [Repository Introduction](#repository-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction

[MariaDB](https://github.com/MariaDB/server) is an open-source, distributed, and easily scalable native graph database. It can handle ultra-large-scale datasets containing hundreds of billions of nodes and trillions of edges, and provides millisecond-level queries. This product is based on the Huawei Cloud EulerOS 2.0 64-bit system of Kunpeng servers, offering out-of-the-box MariaDB.

## Core Features

- **Development Background**:
    - Emerged as a branch of MySQL to address the risk of closed-source after Oracle's acquisition of MySQL
    - Maintained by the MariaDB Foundation, under the GPLv2 license agreement
- **Technical Compatibility**:
    - Maintains binary compatibility with MySQL, supporting seamless migration
    - Compatible with MySQL's APIs, command lines, file formats, and connectors
- **Storage Engines**:
    - By default uses XtraDB (enhanced version of InnoDB) and Maria storage engines
    - Includes extended engines such as PrimeBase XT and FederatedX
- **Performance Advantages**:
    - 13%-22% better performance than MySQL in high-concurrency read-write scenarios
    - Natively supports Galera Cluster multi-master synchronous clusters


The open-source image product [**MariaDB Database**](https://marketplace.huaweicloud.com/intl/hidden/contents/5d13e190-5921-4e42-9db0-064c7c22808d) provided by this project has pre-installed version 10.4.34 of Memcached and its related runtime environment, and offers deployment templates. Follow the user guide to easily start your "out-of-the-box" efficient experience.


> **System Requirements are as follows:**
> - CPU: 2vCPUs or higher
> - RAM: 4GB or larger
> - Disk: At least 40GB

## Prerequisites
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description

| Image Specification                                                                                                      | Feature Description | Remarks |
|-----------------------------------------------------------------------------------------------------------| --- | --- |
| [MariaDB-10.4.34-kunpeng](https://github.com/HuaweiCloudDeveloper/memcached-image/tree/MariaDB-10.4.34-kunpeng) | Installed and deployed based on Kunpeng server + Huawei Cloud EulerOS 2.0 64bit |  |

## Get Help
- For more questions, you can contact us through [issue](https://github.com/HuaweiCloudDeveloper/mariaDB-image/issues) or the service support of the specified product in the Huawei Cloud Marketplace
- For other open-source images, please refer to [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## How to Contribute
- Fork this repository and submit a pull request
- Synchronously update README.md based on your open-source image information