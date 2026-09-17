# `simple-im`- Go即时通信系统

## 项目简介

基于Go语言开发的即时通信系统，复刻刘丹冰《8小时转职Golang工程师》教程

## 技术栈

- Go语言
- 网络编程
- 并发处理

## 功能特点

- 实时消息传输
- 多用户在线
- 客户端-服务器架构

## 项目结构

- server/: 服务器端实现
- client/: 客户端实现

## 使用教程

1. 克隆项目到本地

```bash
git clone https://github.com/anhyxdy/simple-im.git
```

2. 进入项目目录

```bash
cd simple-im
```

3. 安装依赖

```bash
go mod tidy
```

4. 配置数据库连接

- 编辑 `dao/dao.go` 文件，修改数据库连接配置。

5. 启动服务端

```bash
go run main.go
```

6. 新开终端，启动客户端

```bash
go run client/main.go
```

## 学习资源

教程视频：[Bilibili链接](https://www.bilibili.com/video/BV1gf4y1r79E)
