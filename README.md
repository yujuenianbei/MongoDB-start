# MongoDB windows使用教程

author:yujuenianbei
version:v0.0.1

#### 注：本教程默认目录 E:\WEB\MongoDB 如果目录不同除了serverStart serverStop这两个之外所有的bat文件都需要进行修改

先安装好mongodb在本目录中,配置文件为mongod.cfg

### 第一步

创建data文件夹 

再在data中创建db,log两个文件夹。db用于存放数据库，log用于存放日志

### 第二步

开启 start.bat测试是否能够正常启动数据库

### 第三步

在全局中添加 当前文件夹 + bin/ 使全局能够使用mongo命令

### 第四步

开启 install.bat 导入配置到data文件夹中

### 第五步

开启 serverStart.bat 开启MongoDB服务

### 第六步

开启 connect.bat测试是否连接到data.db中的数据库

### 第七步

开启serverStop.bat关闭MongoDB服务


