# Linux系统安装Tomcat8.5

## 安装JDK8

安装Tomcat之前需要先安装JDK

* 下载JDK

官网链接：https://www.oracle.com/java/technologies/javase-downloads.html

选择tar.gz的Linux版本下载

* 解压安装

把下载好的JDK压缩包上传到服务器，再解压到指定目录：tar -zvxf ···

* 配置环境变量

安装之后需要配置环境变量才可用

如果是root用户，则打开'/etc/profile'，然后在里面添加Java环境变量

如果是普通用户，则打开'.bash_profile'，然后在里面添加Java环境变量

添加完成之后，执行source profile刷新一下全局配置！

* 验证是否安装成功

输入 java -version出现安装版本信息

## 安装Tomcat

* 下载Tomcat

官网链接：https://tomcat.apache.org/download-80.cgi

选择tar.gz的Linux版本下载

* 解压安装

把下载好的安装包上传到服务器，再解压到指定目录：tar -zvxf ···

* 启动Tomcat

进入安装目录的bin目录下执行：./startup.sh

打开浏览器，输入：http://ip:port/ 查看页面
