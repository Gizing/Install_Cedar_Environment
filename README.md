# Install_Cedar_Environment
## 说明
一个在CentOS6.8及以下系统简便安装Cedar编译环境的方法，包含六个文件：*Lib.tar.gz*、*yumsource_part1.tar.gz*、*yumsource_part2.tar.gz*和*libonev.tar.gz*四个压缩包和*obeninstall1*和*obeninstall2*两个脚本文件，六个文件均位于同个文件夹中，将此文件夹置于`/home/admin`下。

## 下载地址
|文件名           |下载地址   |
|-----------------|:----------|
|Lib.tar.gz	            |[http://pan.baidu.com/s/1dFmTwq9](http://pan.baidu.com/s/1dFmTwq9)|
|yumsource_part1.tar.gz |[http://pan.baidu.com/s/1dFFtFLf](http://pan.baidu.com/s/1dFFtFLf)|
|yumsource_part2.tar.gz |[http://pan.baidu.com/s/1skWqa1f](http://pan.baidu.com/s/1skWqa1f)|
|libonev.tar.gz	        |[http://pan.baidu.com/s/1miM6YV2](http://pan.baidu.com/s/1miM6YV2)|

## 使用方法
1. 使用root账户执行obeninstall1
2. 断开ssh连接后重新连接
3. 使用admin账户执行obeninstall2

注意：执行过程中可能需要输入相应账户密码。断开重连是为了使obeninstall1中生成的.bashrc文件能够生效。