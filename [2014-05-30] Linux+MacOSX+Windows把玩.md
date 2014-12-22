
# Linux + MacOSX + Windows


## MacOSX

[每个Mac OS X 命令行用户应当知道的八个终端工具](http://aimijia.net/2014/05/each-mac-os-x-command-line-users-should-be-aware-of-the-eight-terminal-tool/)

[mac系统tomcat使用80端口](http://openwares.net/linux/mac_tomcat_port_80.html)
> mac与linux一样,1024以下的端口为特权端口,只有root用户才有权监听。
> 因此要使用80端口要么使用root启动tomcat,要么使用端口转发。


### 常用软件集

[alfred](http://wellsnake.com/jekyll/update/2014/06/15/001/)

----------

## CentOS

### 问题

[yum下载仓库rpm包到指定目录](http://www.issacy.com/?p=541)
[在CentOS/RHEL 6.4上安装Chromium](http://www.linuxeden.com/html/softuse/20130627/140767.html)

[在 CentOS 上使用 Apache 的 Proxy mode 使 Node.js 和 Apache 共用 80 端口](http://www.tfan.org/nodejs-running-on-port-80-with-apache/)
>  安装完后,需要yum update 否则无法启动

[shell脚本转发80端口数据包给Node.js服务器](http://www.jb51.net/article/48146.htm)

> iptables -t nat -A PREROUTING -p tcp --dport 80 -j REDIRECT --to-port 你的端口号



[chromium shockwave flash crashes](http://shebangme.blogspot.co.uk/2012/08/how-to-fix-shockwave-flash-crashes-in.html)

>  adobe官网下载适配的flash包并安装，然后设置chrome://plugins便可。

[ 解决libc.so.6: version `GLIBC_2.14' not found问题](http://blog.csdn.net/cpplang/article/details/8462768)

### 常用软件集

* 浏览器
 
  chrome,firfox,opera

* 聊天

  webqq,wechat
  
* email

  ThunderBird Email


* download


* ftp


* 文件管理


* 压缩软件

 ark


* 文本编辑软件


* 电子书阅读


* 音频播放


* 视频播放


* 刻录软件


* 办公套件

  wps

* 图像处理






------------------


## Windows

### 常用软件集

#### 效率篇

* [Clover] - 给资源管理器加上chrome一样的标签
* [Evernote] - ...
* [PowerCmd] - windows下窗口命令行工具
* [Everthing] - 搜索利器
* [Chrome] - ...
* [greenshot] - 开源截图软件
* [Sublime] - ..
* [7z] - 7-Zip是一款高压缩比的压缩软件，不仅支持独有的7z文件格式，而且还支持各种其它压缩文件格式，其中包括 ZIP、RAR、CAB、GZIP、BZIP2和TAR等格式。此软件压缩的压缩比要比普通ZIP文件高30-50%
* [DropBox] - ..
* [Listary Pro] - 能极大幅度提高你 Windows 文件浏览与搜索速度效率的「超级神器」
* [qq安全卫士] - --!
* [搜狗拼音] - ...
* [企业qq] - ...
* [foxmail] - ...

#### 开发篇

* [Pencil] - 免费的手绘风格开源原型图设计工具
* [Git] - ...
* [TortoiseSVN] - TortoiseSVN是Subversion版本控制系统的一个免费开源客户端
* [Xshell] - Xshell是一款非常好用的免费SSH客户端
* [Webstorm] - ...
* [Eclipse] - ...
* [IntellijIDEA] - ...
* [NodeJS] - ...
* [Mysql] - ...
* [Navicat] - ...
* [PhotoShop] - ...

> 开发的因人而异吧，有些环境比较繁琐，可能还需xxx .

#### Linux下环境搭建(通用)

1. 下载以及配置java sdk
2. 安装带tar所需的ide等相关环境
3. 将软件配置成桌面快捷方式以方便使用(类似windows)




