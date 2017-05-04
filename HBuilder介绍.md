#自我介绍

姓名：徐风杰

负责：前端

分享的内容是HBuilder：

+ 什么是HBuilder？
+ 如何安装HBuilder
+ 为什么用HBuilder(HBuilder有哪些优点)？
+ HBuilder强大的项目模版



![HBuilder logo](http://www.uedsc.com/wp-content/uploads/2014/06/text-b.png)

##1、什么是HBuilder？
HBuilder首先是一个编辑器。由**DCloud**（数字天堂）推出，支持 *HTML5* 的一款Web开发IDE(集成开发环境)。

HBuilder的**特点**：

+ 其本身主体是由**Java**编写，它基于Eclipse，所以顺其自然地兼容了Eclipse的插件。

+ **快**，是HBuilder的最大优势，通过完整的语法提示和代码输入法、代码块等，大幅提升HTML、js、css的开发效率。


##2、如何安装HBuilder

HBuilder下载地址：在HBuilder官网<a href="http://www.dcloud.io/">http://www.dcloud.io/</a>点击免费下载，下载最新版的HBuilder。

HBuilder的两个版本：windows版，mac版。可根据自己的电脑选择适合自己的版本。

---
---
---

#为什么用HBuilder(HBuilder有哪些优点)？

| 序号 | 原因描述 |
|----|----|
|1|方便的新建快捷方式|
|2|边改边看模式|
|3|强大的代码块，减少大量的重复代码工作量|
|4|灵活的快捷键|
|5|使用CSS选择器语法来快速开发HTML和CSS(支持Emmet)|
|6|强大的JS解析引擎大大加快JS开发的速度|
|7|快速跳转到class、id、js方法定义处|
---

##1、方便的新建快捷方式
###新建项目
  + 1、依次点击文件→新建→选择Web项目
  + 2、W可以触发快速新建,按下Ctrl+N(MacOS请使用Command+N,然后左键点击Web项目)

![show creat new project img](http://www.runoob.com/wp-content/uploads/2016/04/1460087324-6242-ctrln.png)

![show creat new project img](http://www.runoob.com/wp-content/uploads/2016/04/1460087323-2889-newproject.png)

  + A处填写新建项目的名称
  + B处填写(或选择)项目保存路径(更改此路径HBuilder会记录，下次默认使用更改后的路径)
  + C处可选择使用的模板(可点击自定义模板,参照打开目录中的readme.txt自定义模板)

###新建html文件使用如下图：

![show creat new html](http://www.runoob.com/wp-content/uploads/2016/04/1460087323-9522-newhtml.png)

##2、边改边看模式
###快捷键
  + windows系统：Ctrl ＋ P
  + MacOS系统：Command ＋ P
###右侧工具栏选择视图模式

##3、强大的代码块，减少大量的重复代码工作量
###什么是代码块？
代码块是常用的代码组合；

代码块激活字符原则有：

  + 连续单词的首字母；
  + 整段HTML一般使用**tag**的名称；
  + 同一个tag，有多个代码块输出则在最后加后缀；
  + 如果原始语法超过4个字符，针对常用语法，则第一个单词的激活符使用缩写；
  + js的关键字代码块，是在关键词最后加一个重复字母


代码描述以上几个规则：

	<!DOCTYPE html>
	<html>
		<head>
			<meta charset="UTF-8"/>
			<meta name="keywords" content="测试,奥维,奥维测试"/>
			<title></title>
		</head>
		<style type="text/css">
			body
			{
				/*原则1，连续单词的首字母：dn*/
				display: none;
			}
		</style>
		<!--原则2，整段HTML一般使用tag的名称，style script，通常，敲最多4个字母即可匹配到需要的代码块，不需要完整录入，如sc回车、st回车，即可完成script、style标签的输入-->
		<script type="text/javascript">
			
		</script>
		<body>
			<!--原则4，如果原始语法超过4个字符，针对常用语法，则第一个单词的激活符使用缩写，输入inbutton点击enter键-->
			<input type="button" id="" value="" />
			<!-- 
			    div#box>ul#list>li.item*2>a
			    点击tag健
			-->
			<div id="box">
				<ul id="list">
					<li class="item"><a href=""></a></li>
					<li class="item"><a href=""></a></li>
				</ul>
			</div>
		</body>
	</html>
		
##4、灵活的快捷键

|快捷键|使用说明|
|----|----|
|ctrl+回车|在当前的下一行插入空行，并将光标移动到下一行|
|输入sc，回车|使用sc代码块生成一个script块来编写js代码|
|输入fnn，回车|使用fnn代码块编写一个js方法|
|alt+下|跳转至下一个编辑区域|

图片展示：
![以上快捷键说明图片展示](http://www.runoob.com/wp-content/uploads/2016/04/1460087325-9324-hellohbuilder1.gif)

##5、使用CSS选择器语法来快速开发HTML和CSS(支持Emmet)
输入div#box>ul#list>li.item*2>a,按下tab生成代码

	<!-- div#box>ul#list>li.item*2>a 点击tag键-->
	<div id="box">
		<ul id="list">
			<li class="item"><a href=""></a></li>
			<li class="item"><a href=""></a></li>
		</ul>
	</div>
	
![使用CSS选择器语法快速开发html和css的图片说明](http://www.runoob.com/wp-content/uploads/2016/04/1460087325-8859-emmet.gif)

##6、强大的JS解析引擎大大加快JS开发的速度

  + js中提示HTML（id名、标签名）、CSS（css类名）
  + js中提示JSON
  + js提示自定义系统方法
  + js提示对象引用及其属性、方法
  + js提示闭包对象

展示提示html中的ID的图片如下：

![提示html中的ID的图片](http://www.runoob.com/wp-content/uploads/2016/04/1460087327-6133-id.gif)

##7、快速跳转到class、id、js方法定义处

按下Alt,左键点击引用的方法名、ID、CSS类、文件(链接、图片),均可跳转到引用的地方,跨文件的引用也可以哦
例：如下图

![跳转class方法定义处](http://www.runoob.com/wp-content/uploads/2016/04/1460087334-4724-jsjump.gif)

---
---
---

#HBuilder强大的项目模版
##1、web项目
###新建web项目
![creat new web project](markdownimg/web1.png)
###执行上面操作，会出现以下弹框信息
一般选择默认项目模板
![creat new web project](markdownimg/web2.png)
###创建完成后，项目如下
可以清晰的看到，默认模板当中给自动创建了最基本的3个文件夹：css、img、js及项目默认初始进入页面index.html文件

在右侧可以选择视图模式（开发视图、边改边看模式、团队同步视图3种）；
![creat new web project](markdownimg/web3.png)



##2、app项目

###新建app项目
![creat new web project](markdownimg/app1.png)

###执行上面操作，会出现以下弹框信息
一般选择mui项目模板
![creat new web project](markdownimg/app2.png)

###创建完成后，项目如下
模板当中给自动创建了最基本的3个文件夹：css、fonts、js每个文件夹中对应的有mui项目自带的原始文件；

项目默认初始进入页面index.html文件

要比web项目当中多一个关于app初始配置文件，manifest.json;这个文件的功能是非常重要、强大的。

在右侧选择边改边看的视图模式以后，可以点击设置，设置不同的比例查看html对应的手机屏幕上效果

![creat new web project](markdownimg/app3.png)

###manifest.json文件为什么重要、强大？

![creat new web project](markdownimg/app4.png)
