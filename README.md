# redis demo

## deploy

```shell
docker-compose up -d  # 启动镜像

docker exec -it redis /bin/bash  # 进入镜像

redis-cli  # 进入客户端

# Ctrl + D  # 退出

docker-compose down  # 停止所有up命令启动的容器

docker-compose ps  # 查看正在运行中的容器

```

## demos

**string**

* 缓存
* 分布式锁
* 计数器
* 限流
* 频控
* 消息队列

TODO:

## ref

