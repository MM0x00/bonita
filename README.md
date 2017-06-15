# bonita 在线实验环境

## 软件简介
bonita BPM是一个开放源码的业务流程管理和工作流程套件，于2001年创建。它开始于法国计算机科学研究所，然后在法国计算机科学公司Groupe Bull内孵化了几年。自2009年以来，Bonita的发展得到了一家致力于此项活动的公司的支持：Bonitasoft

所属类型是企业应用

License:LGPL v2.1 and GPL v2.0

## 软件官网

https://en.wikipedia.org/wiki/Bonita_BPM

## Dockerfile 使用方法

快速开始
```
$ docker run --name bonita -d -p 8080:8080 bonita
```
这将启动一个容器运行Tomcat Bundle与Bonita BPM引擎+ Bonita BPM门户。没有指定环境变量，就像在主机上使用启动启动捆绑软件一样。{sh | bat}（在REST和HTTP API上安全加固，cf安全部分）。Bonita BPM在这里使用H2数据库。

您可以使用http：// localhost：8080 / bonita访问Bonita BPM门户，并使用默认凭据登录：install / install

## 资源链接

- http://www.oschina.net/p/bonita
- https://hub.docker.com/_/bonita/
- https://en.wikipedia.org/wiki/Bonita_BPM
