# 一个简单的Docker部署的PHP环境

### 文件目录
* MySQL/ 
MySQL容器的目录，包含`Dockerfile`、数据目录、日志目录。
* Nginx/
Nginx容器的目录，包含`Dockerfile`、`conf`目录(配置文件)。
* phpMyAdmim/
phpMyAdmim容器的目录，只有`Dockerfile`。
* src/
php项目以及静态文件路径。

### 启动方法
使用前安装`Docker`以及`docker-compose`。
#### 后台启动
`docker-compose up -d`
#### 正常启动(查看log)
`docker-compose up`
#### 关闭容器
`docker-compose down`