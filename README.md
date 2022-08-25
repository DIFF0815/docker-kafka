# docker-kafka

## 开始
* 修改配置
```shell
# 进入根目录,执行下面命令，需要修改.env 里面的自己的host
cp .env.example .env 
cp docker-compose.example.yml docker-compose.yml
```
* 启动容器
```shell
#执行下面命令（会构建镜像和启动容器）
docker-compose up 
```