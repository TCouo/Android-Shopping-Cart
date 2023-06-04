# 简介

该电商APP采用前后端分离，前端为安卓模块化开发，模块化开发的优势在于便于功能拓展与维护。后端采用Spring Boot与数据库链接，通过ip接口访问Spring Boot后台提供的业务逻辑服务操作数据库。

# 部署

## 前端

![image-20230604004044833](.\images\README\image-20230604004044833.png)

如果是手机是虚拟机，此处的ip地址应为电脑分配给手机虚拟机的那张虚拟网卡，分配给电脑的ip地址，端口号为后端服务程序给定（注意：确保端口没有被占用）

## 后端

Mysql 8.0 、Redis

![image-20230604005117634](.\images\README\image-20230604005117634.png)

java环境建议java 8或11

![image-20230604005454628](images\README\image-20230604005454628.png)

### 启动

在 `cart-backend`文件夹下打开cmd 运行指令

~~~bash
java -jar cart-backend.jar
~~~

