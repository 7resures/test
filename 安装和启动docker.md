```linux
//服务器安装docker
//安装docker compose
sudo apt-get update
sudo apt-get install docker-compose

// 确认安装成功
docker-compose --version


// 确保docker运行
sudo systemctl start docker

//开启自启动
sudo systemctl enable docker

// 查看docker的服务状态
sudo systemctl status docker

// 查看docker容器列表
```

