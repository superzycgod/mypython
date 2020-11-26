# Python运行环境
> https://www.python.org/ftp/python/3.5.3/python-3.5.3.exe
Python 3.5.3 (v3.5.3:1880cb95a742, Jan 16 2017, 15:51:26) [MSC v.1900 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license" for more information.

# 使用阿里云的源
> 无网络环境下无需配置

## 命令方式
````
pip config set global.index-url https://mirrors.aliyun.com/pypi/simple/
````

## 配置文件

在用户目录下创建文件pip/pip.ini，文件内容如下：

````
[global]
index-url = https://mirrors.aliyun.com/pypi/simple/
````

# 安装三方库

执行install.bat脚本
