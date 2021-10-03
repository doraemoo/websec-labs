# websec-labs
Many web broken website docker
把6个常见web安全开源靶场项目在docker中搭建 一条命令开启6个靶场，简单实用！

由Jonathan&Leonard:D整理

![image](https://user-images.githubusercontent.com/30892536/135741455-a74a49a8-e2df-46fd-bc15-3f177459b55c.png)

# Usage

确保已经安装docker
Ubuntu安装方法参考官网

https://docs.docker.com/engine/install/ubuntu/

`sudo docker search jojosec`

![image](https://user-images.githubusercontent.com/30892536/135741729-3ef7fb78-8e1d-4a07-86f8-2f82bbe309bc.png)

拉取镜像

`sudo docker pull jojosec/websec-labs:v2`

![image](https://user-images.githubusercontent.com/30892536/135741836-32684a9d-bcf3-4722-b5fe-db473b080b0a.png)

![image](https://user-images.githubusercontent.com/30892536/135741873-137fe201-55a3-4759-9068-5cd48bc317a4.png)

启动容器

`sudo docker run -d -p 8080:80 [IMAGE ID]`

![image](https://user-images.githubusercontent.com/30892536/135741907-0529d600-1c8b-485d-8284-ae6e4e1e9d71.png)

访问http://127.0.0.1:8080 即可开启web安全训练之旅！

# 注意
bWAPP初次启动需要手动创建数据库
![image](https://user-images.githubusercontent.com/30892536/135742004-2ef8361e-f5b3-4056-9bd5-e33080b600f1.png)

访问install.php创建数据库即可使用
![image](https://user-images.githubusercontent.com/30892536/135742035-0049bf98-9fa6-4158-a0b1-4be148cb231e.png)

有问题联系
QQ：1642059190
or
QQ：2429713788
