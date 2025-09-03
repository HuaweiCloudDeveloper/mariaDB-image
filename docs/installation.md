# Memcached部署指南

## ‌一、环境准备
### 系统配置
> -  服务器：鲲鹏服务器
> -  操作系统：Huawei Cloud EulerOS 2.0 64bit 
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GrB

## ‌二、安装部署部署

### 1.安装docker
参考：[安装Docker](https://support.huaweicloud.com/bestpractice-hce/hce_bp_0002.html)

### 2.拉取官方镜像
```bash
docker pull mariadb:latest
```

### 3.容器启动
```bash
docker run --name mariadb -e MYSQL_ROOT_PASSWORD=mariadb -p 3306:3306 -d mariadb
```
