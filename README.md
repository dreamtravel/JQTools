## 介绍

JQTools，为 Jason Qt Tools 的简称

这是一个基于Qt开发的开源小工具包。

包含了在开发程序（尤其是Qt程序）时，需要的各种小功能。

本工具使用 QML(界面) 和 C++(逻辑) 开发，源码均已开源在了GitHub上。

GitHub地址：https://github.com/188080501/JQTools

若不想下载源码编译，也可以点击这里直接下载可执行文件：
 
[OS X版本dmg包（V16.5.16，落后于源码）](http://flw-other.oss-cn-hangzhou.aliyuncs.com/JQTools_V16.5.16.dmg)

[Windows版本zip包（V16.5.16，落后于源码）](http://flw-other.oss-cn-hangzhou.aliyuncs.com/JQTools_V16.5.16.zip)

若需要其他版本，请下载源码自行编译。 

方便的话，帮我点个星星，或者反馈一下使用意见，这是对我莫大的帮助。

若你已经有了更好的建议，或者想要一些新功能，可以直接邮件我，我的邮箱是：Jason@JasonServer.com

## 开发计划

类别|功能|计划完成日期
---|---|---
文本类|UTF16转换|已完成
文本类|RGB转16进制|已完成
文本类|大小写转换|2016-05
文本类|URL转码|2016-05
||
计算类|HASH计算器|已完成
计算类|Unix时间戳转换|2016-05
计算类|屏幕二维码解析器|2016-06
||
制作类|图标生成器|已完成
制作类|图标字体转PNG|2016-06
||
工具类|代码行数统计|2016-05
工具类|拾色器|2016-07
工具类|局域网文件传输|2016-07
工具类|局域网远程构建|2016-08
||
Qt相关|PNG警告消除|已完成
Qt相关|Q_PROPERTY代码生成器|2016-06
Qt相关|TS文件自动翻译器|2016-08

## 功能介绍

* PNG警告

	消除在Qt里，部分PNG图片在加载时控制台会报警告的问题

* UTF16转换

	将字符串和UTF-16之间进行互转

* HASH计算器

	计算常用的摘要值，如SHA1、MD5
	
* RGB转16进制

	RGB颜色与16进制互转
	
* 大小写转换

	文本大小写转换

* Unix时间戳转换

	Unix时间戳转换
	
* 代码行数统计

	可以统计文件中，代码行数

* 图标生成器

	根据已有的PNG图片，生成可以用于发布App的特定分辨率图片

* 屏幕二维码解析器

	可以解析屏幕上的二维码

* 图标字体转PNG

	将ttf字体或者svg字体，转换为PNG
	
* URL转码

	URL转码功能
	
* Q_PROPERTY代码生成器

	可以根据Q_PROPERTY的内容，生成代码
	
* 拾色器

	可以拾取屏幕中，某个点的颜色
	
* 局域网文件传输

	可以在局域网中传输文件
	
* 局域网远程构建

	可以在局域网中远程控制其他电脑编译代码，并传回
	
* TS文件自动翻译器

	可以使用百度翻译，自动翻译TS文件