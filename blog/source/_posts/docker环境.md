---
title: docker环境
date: 2022-04-24 09:25:16
tags: docker
category: CS
---

容器化能够帮助高效的帮助搭建环境

## 单机容器化环境
### docker
> yum install docker -y
> echo "{\"registry-mirrors\": [\"https://registry.docker-cn.com\"]}" | tee /etc/docker/daemon.json
> service docker restart

### docker compose
>yum install docker-compse -y
docker-compose version

## 容器化基本操作
### Docker
#### build
> 待补充
#### run
docker run -i -t IMAGE_ID -p HOST_PORT:CONTAINER_PORT --name 
#### exec

常用docker镜像: https://github.com/douglaswei/dockerFiles

## 小结
1. 虽没有大的进步|进展，但回到熟悉的节奏，感觉挺好
2. 凡事需要以正确的方式去做才能获得结果；需要总结方法，按照方法去实践；
