#### docker-php-web

基于docker 构建php + nginx + mysql + redis的web环境

> 配置说明

##### 版本:

`PHP` 7.2  redis swoole  扩展

`Mysql` 5.6 

`openresty` 1.11.2.3

##### 结构:

├── README.md
├── config
│   └── nginx
│       └── html.conf   #host文件 
├── docker-compose.yaml  #安装文件
├── files
│   ├── cgi
│   │   ├── Dockerfile  #PHP
│   │   ├── docker-entrypoint.sh
│   │ 
│   └── proxy
│       ├── Dockerfile  #nginx  
│       └── docker-entrypoint.sh
├── logs
│   └── nginx #日志
│       ├── 
├── runtime #mysql & redis



> 使用方法

安装docker

https://www.runoob.com/docker/ubuntu-docker-install.html

安装docker-compose

https://www.runoob.com/docker/docker-compose.html

安装yaml

`cd /docker-php-web && docker-compose up -d `

结果展示

![image-20220317153755710](/Users/qihongyun/Library/Application Support/typora-user-images/image-20220317153755710.png)



DONE !!!
