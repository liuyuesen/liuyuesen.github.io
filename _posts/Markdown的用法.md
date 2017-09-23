---
layout:     post
title:      ReactiveCocoa 进阶
subtitle:   函数式编程框架 ReactiveCocoa 进阶
date:       2017-01-06
author:     BY
header-img: img/post-bg-ios9-web.jpg
catalog: true
tags:
- iOS
- ReactiveCocoa
- 函数式编程
- 开源框架
---

二，Markdown 语法的简要规则
标题
![标题](http://upload-images.jianshu.io/upload_images/7498199-2e0b1492d26ff9bc.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)标题

标题是每篇文章都需要也是最常用的格式，在 Markdown 中，如果一段文字被定义为标题，只要在这段文字前加#
号即可。
# 一级标题

## 二级标题

### 三级标题

以此类推，总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。
列表
熟悉 HTML 的同学肯定知道有序列表与无序列表的区别，在 Markdown 下，列表的显示只需要在文字前加上-
或*
即可变为无序列表，有序列表则直接在文字前加1.
2.
3.
符号要和文字之间加上一个字符的空格。
![无序列表与有序列表](http://upload-images.jianshu.io/upload_images/7498199-1ddba19949174714.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)无序列表与有序列表

引用
如果你需要引用一小段别处的句子，那么就要用引用的格式。
例如这样

只需要在文本前加入>
这种尖括号（大于号）即可
![引用](http://upload-images.jianshu.io/upload_images/7498199-0dbe3604357c9d7a.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)引用

图片与链接
插入链接与插入图片的语法很像，区别在一个!
号
图片为：![](){ImgCap}{/ImgCap}

链接为：[]()

插入图片的地址需要图床，这里推荐[围脖图床修复计划](http://weibotuchuang.sinaapp.com) 与 [CloudApp](http://www.getcloudapp.com) 的服务，生成URL地址即可。
![URL 与图片](http://upload-images.jianshu.io/upload_images/7498199-91c2a47ff65673db.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)URL 与图片

粗体与斜体
Markdown 的粗体和斜体也非常简单，用两个*
包含一段文本就是粗体的语法，用一个*
包含一段文本就是斜体的语法。
例如：**这里是粗体** *这里是斜体* 
表格
表格是我觉得 Markdown 比较累人的地方，例子如下：
| Tables | Are | Cool || ------------- |:-------------:| -----:|| col 3 is | right-aligned | $1600 || col 2 is | centered | $12 || zebra stripes | are neat | $1 |

这种语法生成的表格如下：
Tables
Are
Cool

col 3 is
right-aligned
$1600

col 2 is
centered
$12

zebra stripes
are neat
$1

代码框
如果你是个程序猿，需要在文章里优雅的引用代码框，在 Markdown下实现也非常简单，只需要用两个 ` 把中间的代码包裹起来。图例：
![](http://upload-images.jianshu.io/upload_images/7498199-27400a69844aa2e1.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

使用tab
键即可缩进。
分割线
分割线的语法只需要三个*
号，例如：
到这里，Markdown 的基本语法在日常的使用中基本就没什么大问题了，只要多加练习，配合好用的工具，写起东西来肯定会行云流水。更多的语法规则，其实 Mou 的 Help 文档栗子很好，当你第一次使用 Mou 时，就会显示该文档。可以用来对用的查找和学习。

![](http://upload-images.jianshu.io/upload_images/7498199-304ef9483303c373.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

