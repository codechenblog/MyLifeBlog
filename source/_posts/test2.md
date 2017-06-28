
---
layout: post
title: "Blog test"
date: 2017-06-28 
comments: false
tags: 
	- 博客教程 

---
<img src="https://github.com/codechenblog/codechenblog.github.io/blob/master/2017/06/28/test2/test3.JPG?raw=true" width="60%" height="60%">
<!--more-->
![](https://github.com/codechenblog/codechenblog.github.io/blob/master/2017/06/28/test2/test3.JPG?raw=true)
![](https://github.com/codechenblog/codechenblog.github.io/blob/master/2017/06/28/test2/test3.JPG?raw=true)
图文无关，用于测试(图为北大图书馆前)

注意：每次创建一个blog时 比如使用命令：hexo new "blog_test"
以上命令会在xx.io/source/_posts 目录中生成两个文件：blog_test.md 和文件夹blog_test
其中blog_test.md 用于编写blog，遵循MarkDown语法
其中blog_test文件夹可以存放该blog所需的文件，如图片等

比如本blog我用hexo new "test2"生成的
本文档的名字就是：test2.md
以上图片放在test2文件夹中，文件名字为test3.JPG
于是有以上两种放置图片的方式，方式一是用html的语法，直接按照比例现实图片（因为：width="60%" height="60%"）
```
<img src="https://github.com/codechenblog/codechenblog.github.io/blob/master/2017/06/28/test2/test3.JPG?raw=true" width="60%" height="60%">
```
该方法的结果就是不管是用pc端还是移动端，都按照比例现实图片

第二种放置图片的方式为MarkDown语法，这么放的话由于MarkDown不支持图片by design
所以我是直接图片先调整大小再放到test文件夹里面的
```
![](https://github.com/codechenblog/codechenblog.github.io/blob/master/2017/06/28/test2/test3.JPG?raw=true)
```
这个的好处是在移动端观看图片时，图片时适应屏幕的大小，不会显得太小
调整方法：
> 在Mac下直接双击打开图片
  Tools->Adjust Size
  建议width 20cm左右

## 那以上图片地址是如何得到的呢
 
 
我是先把图片放到：xx.io/source/_posts/test2文件夹中
然后就上传图片到Github: 

```
hexo g
hexo d
```

然后打开Github打开找到对应的文件夹（test2）中的图片，复制浏览器中的地址
 
 
END
