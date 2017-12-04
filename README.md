# MongoDB windows使用教程

author:yujuenianbei
version:v0.0.1

#### 注：本教程默认目录 E:\WEB\MongoDB 如果目录不同除了serverStart serverStop这两个之外所有的bat文件都需要进行修改

先安装好mongodb在本目录中,配置文件为mongod.cfg

### 第零步

开启 start.bat测试是否能够正常启动数据库

### 第一步

在全局中添加 当前文件夹 + bin/ 使全局能够使用mongo命令

### 第二步

开启 install.bat 导入配置到data文件夹中

### 第三步

开启 serverStart.bat 开启MongoDB服务

### 第四步

开启 connect.bat测试是否连接到data.db中的数据库

### 第五步

开启serverStop.bat关闭MongoDB服务


