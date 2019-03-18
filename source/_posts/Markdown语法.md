---
title: Markdown语法简介
date: 2018-02-18 22:00:20
tags:
   - Markdown
---

## 标题
代码：

    # h1
    ## h2
    ### h3

## 引用

单行引用
代码：

    > hello md

演示：

> hello md

多行引用
代码：

    > hello md
    > hello md
    > hello md

演示：

> hello md
> hello md
> hello md

## 代码块

代码：

  

    `hello md`

演示
> `hello md`

多行代码块
代码：
 
> ```
    hello md
    hello md
    hello md
```

演示：

```
    hello md
    hello md
    hello md
```


## 列表

无序：//+，*，-

+ 1
+ 2
+ 3

有序：//1,2,3

1. one
2. two
3. three

## 强调

>  *hello*                 // *
> **hello**                   // ** 
~~hello~~                    // ~~

## 表格

代码：

```
|col1|col2|col3|col4|
|:---:|:---:|:---:|:---:|
|aaa|bbb|ccc|ddd|
|111|222|333|444|
```

演示：

|col1|col2|col3|col4|
|:---:|:---:|:---:|:---:|
|aaa|bbb|ccc|ddd|
|111|222|333|444|

## 插入图片

代码：

    ![](http://ovvd7k5mv.bkt.clouddn.com/18-2-7/20259758.jpg)


演示：

![此处输入图片的描述][1]

## 插入链接

代码：


    [百度1](http://www.baidu.com/)

邮箱链接：


    <xxx@outlook.com>


## 插入视频

Markdown 语法是不支持直接插入视频的
普遍的做法是 插入HTML的 iframe 框架，通过网站自带的分享功能获取

代码：

    <iframe height=498 width=510 src='http://player.youku.com/embed/XMjk4NzA1OTMzNg==' frameborder=0 'allowfullscreen'></iframe>

演示：
<iframe height=498 width=510 src='http://player.youku.com/embed/XMjk4NzA1OTMzNg==' frameborder=0 'allowfullscreen'></iframe>

## 推荐

MD编辑器：[作业部落][2]
图床：[七牛云+chrome插件+极简图床][3]
  
  


  [1]: http://ovvd7k5mv.bkt.clouddn.com/18-2-7/20259758.jpg
  [2]: https://www.zybuluo.com/mdeditor
  [3]: https://jiantuku.com