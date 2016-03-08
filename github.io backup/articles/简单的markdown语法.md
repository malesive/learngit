---
title: 简单的markdown语法
date: 2016-03-08 15:36:24
categories: Blog
tags: markdown
---
这篇文章简单记录了markdown的语法，方便以后写文章查询用
<!--more-->
## 1.标题
使用#号，一个到五个，后面有空格，表示层级  
## 2.图片
可以使用这个格式!+[Alt text]+(/path/to/img.jpg)，正式用要去掉+号
![new pic](https://raw.githubusercontent.com/malesive/learngit/master/github.io%20backup/images/testImage.jpg)
## 3.强调
在首尾加星号或者下划线，以数量区分，比如  
*强调* 或者 _强调_  (示例：斜体)  
**加重强调** 或者 __加重强调__ (示例：粗体)  
***特别强调*** 或者 ___特别强调___ (示例：粗斜体)  
## 4.代码
单行代码在首尾加上键盘左上角的重音符，也就是使用反引号(esc键下面的按钮)将代码包裹起来, 比如`bitcode`  
多行代码用使用制表符或者至少4个空格进行缩进的行（好像还要加个回车），比如   

	- (BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions {  
    IQKeyboardManager *manager = [IQKeyboardManager sharedManager];
    manager.enable = YES;
    manager.shouldResignOnTouchOutside = YES;
    manager.shouldToolbarUsesTextFieldTintColor = YES;
    manager.enableAutoToolbar = NO;
    return YES;
	}
## 5.换行
如果我们想把一行文本进行换行，我们可以在需要换行的地方输入至少两个空格，然后回车即可，
注意，如果不回车，是没有效果的  
## 6.引用
如果我们在文章中引用了资料，那么我们可以通过一个右尖括号">"来表示这是一段引用内容。我们可以在开头加一个，也可以在每一行的前面都加一个。我们还可以在引用里面嵌套其他的引用
> A shit world  
> 

## 7.链接
如果我们文章中加入一个链接，那么我们通过下面的方式添加(类似图片，前面没叹号)
[链接文字]+(链接地址)
例子：[baidu](http://baidu.com)
## 8.分割线
如果我们想用分割线对内容进行分割，我们可以在单独一行里输入3个或以上的短横线、星号或者下划线实现。短横线和星号之间可以输入任意空格。以下每一行都产生一条水平分割线。
## 9.列表标记
如果我们的内容需要进行标记，那么我们可以使用下面的方式(数字序号或者星号或者短横线)
加个列表
* 列兵1
* 列兵2
* 列兵3  

还有  
- 准尉1  
- 准尉2  
- 准尉3


来个有序的
1. 士官1
2. 士官2
3. 士官3

## 10.hexo
主页文章显示摘要 编辑md文件的时候，在要作为摘要的文字后面添加<+!--more--+>即可（去掉+号）。
## 参考资料
1. [原来Github上的README.md文件这么有意思——Markdown语言详解](http://blog.csdn.net/zhaokaiqiang1992/article/details/41349819)

