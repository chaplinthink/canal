## Canal

This is a repo forked from [Canal](https://github.com/alibaba/canal), and maintained by [chaplinthink](https://github.com/chaplinthink).

## How to build
```
mvn clean package -DskipTests -Prelease
```
It will gennerate the follow packages in  /target folder.

- canal.adapter-xx.tar.gz
- canal.admin-xx.tar.gz
- canal.deployer-xx.tar.gz
- canal.example-xx.tar.gz


## 文档

- [Home](https://github.com/alibaba/canal/wiki/Home)
- [Introduction](https://github.com/alibaba/canal/wiki/Introduction)
- [QuickStart](https://github.com/alibaba/canal/wiki/QuickStart)
  - [Docker QuickStart](https://github.com/alibaba/canal/wiki/Docker-QuickStart)
  - [Canal Kafka/RocketMQ QuickStart](https://github.com/alibaba/canal/wiki/Canal-Kafka-RocketMQ-QuickStart")
  - [Aliyun RDS for MySQL QuickStart](https://github.com/alibaba/canal/wiki/aliyun-RDS-QuickStart)
  - [Prometheus QuickStart](https://github.com/alibaba/canal/wiki/Prometheus-QuickStart)
- Canal Admin
  - [Canal Admin QuickStart](https://github.com/alibaba/canal/wiki/Canal-Admin-QuickStart)
  - [Canal Admin Guide](https://github.com/alibaba/canal/wiki/Canal-Admin-Guide)
  - [Canal Admin ServerGuide](https://github.com/alibaba/canal/wiki/Canal-Admin-ServerGuide)
  - [Canal Admin Docker](https://github.com/alibaba/canal/wiki/Canal-Admin-Docker)
- [AdminGuide](https://github.com/alibaba/canal/wiki/AdminGuide)
- [ClientExample](https://github.com/alibaba/canal/wiki/ClientExample)
- [ClientAPI](https://github.com/alibaba/canal/wiki/ClientAPI)
- [Performance](https://github.com/alibaba/canal/wiki/Performance)
- [DevGuide](https://github.com/alibaba/canal/wiki/DevGuide)
- [BinlogChange(MySQL 5.6)](https://github.com/alibaba/canal/wiki/BinlogChange%28mysql5.6%29)
- [BinlogChange(MariaDB)](https://github.com/alibaba/canal/wiki/BinlogChange%28MariaDB%29)
- [TableMetaTSDB](https://github.com/alibaba/canal/wiki/TableMetaTSDB)
- [ReleaseNotes](http://alibaba.github.com/canal/release.html)
- [Download](https://github.com/alibaba/canal/releases)
- [FAQ](https://github.com/alibaba/canal/wiki/FAQ)

## 多语言

canal 特别设计了 client-server 模式，交互协议使用 protobuf 3.0 , client 端可采用不同语言实现不同的消费逻辑，欢迎大家提交 pull request 
  
- canal java 客户端: [https://github.com/alibaba/canal/wiki/ClientExample](https://github.com/alibaba/canal/wiki/ClientExample)
- canal c# 客户端: [https://github.com/dotnetcore/CanalSharp](https://github.com/dotnetcore/CanalSharp)
- canal go客户端: [https://github.com/CanalClient/canal-go](https://github.com/CanalClient/canal-go)
- canal php客户端: [https://github.com/xingwenge/canal-php](https://github.com/xingwenge/canal-php)
- canal Python客户端：[https://github.com/haozi3156666/canal-python](https://github.com/haozi3156666/canal-python)
- canal Rust客户端：[https://github.com/laohanlinux/canal-rs](https://github.com/laohanlinux/canal-rs)
- canal Nodejs客户端：[https://github.com/marmot-z/canal-nodejs](https://github.com/marmot-z/canal-nodejs)

canal 作为 MySQL binlog 增量获取和解析工具，可将变更记录投递到 MQ 系统中，比如 Kafka/RocketMQ，可以借助于 MQ 的多语言能力 

- 参考文档: [Canal Kafka/RocketMQ QuickStart](https://github.com/alibaba/canal/wiki/Canal-Kafka-RocketMQ-QuickStart)
