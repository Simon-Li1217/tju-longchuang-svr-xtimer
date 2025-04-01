# spring boot 模板服务

该项目为一个基于 Spring Boot 的子服务项目模板，旨在帮助快速构建分布式微服务系统，满足工业级应用的高并发和高可靠性需求。

## 模块简介
依托天津市产学研合作，推动工业车间智能化转型，实现对生产设备的全方位智能监控与管理

## 接入能力

* spring cloud nacos 服务注册
* spring cloud nacos 配置中心
* spring cloud open feign 服务通信
* lombok 简化开发

## 使用说明

1. 复制`bitstorm-svr-tmpl`修改项目名为新项目名称
2. 修改新项目`pom.xml`文件`artifactId`节点为新项目名称 
3. 修改根项目`pom.xml`文件`modules`节点，加入新项目
4. 修改`package`包名，包括 import 的包名 
5. 修改`启动类名称`

## 备注

本项目模板适用于基于 Spring Boot 的微服务架构开发，具备良好的模块化设计和扩展性，能够快速响应业务需求，适用于工业智能制造等高负载场景。
