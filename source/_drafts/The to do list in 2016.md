title: The to do list in 2016
date: 2016-03-12 22:41:13
comments:
categories: Notes
tags:
  - to do
---
https://github.com/IanLunn/Hover/#using-fontawesome-with-icon-effects
这样获取说明

http://urzone.github.io/cv/pdf/CV.pdf


<input type='checkbox' onclick='return false;' checked>Learn to make graphics using [echarts](http://echarts.baidu.com).   Make a map where I have been; 制作一个胶束破裂的动图； 

<input type='checkbox' onclick='return false;' checked>Use [wordcloud](http://timdream.org/wordcloud/) to visualise to statistical data.  

<input type='checkbox' onclick='return false;'>Learn how to control versions using [Git](http://iissnan.com/progit/html/zh/ch1_1.html) and [here](http://www.bootcss.com/p/git-guide/) 

<input type='checkbox' onclick='return false;' checked>完整版 Markdown [语法说明](http://wowubuntu.com/markdown/index.html)(简体中文版)  

<input type='checkbox' onclick='return false;' checked> Use [Pandoc](http://johnmacfarlane.net/pandoc/) to change file formation.  

<input type='checkbox' onclick='return false;' >Use [Gitbook](https://www.gitbook.com/) to make e-textbooks.  

<input type='checkbox' onclick='return false;' >Hover.css  

<input type='checkbox' onclick='return false;' >add a [whitesmoke layer onto a photo or word](http://25.io/mou/store/)   

<input type='checkbox' onclick='return false;' >introduce the Password Protection. 1. [Salty](https://salty.pw) 2. MasterPassword.  

<input type='checkbox' onclick='return false;' >add[ flowchat ](https://iimx.net/2015/09/25/Diagram%20Test/)  or [1](https://github.com/akfish/hexo-diagram) or [淘宝镜像](http://npm.taobao.org) 再或者直接 Graph Omini 直接画吧。and footnote into hexo. or just 

<input type='checkbox' onclick='return false;' > [Baidu H5](http://h5.baidu.com/store)

<input type='checkbox' onclick='return false;' >[ 复选框 ](http://chitanda.me/2015/06/16/css3-checkbox-diy-without-js/)

<input type='checkbox' onclick='return false;' checked> 进度条 [Pace](http://github.hubspot.com/pace/) and [NProgress](http://ricostacruz.com/nprogress/)

<input type='checkbox' onclick='return false;' > Favicon generator

<input type='checkbox' onclick='return false;' > 文件比较用 Dans tool  
<input type='checkbox' onclick='return false;' >  [SVG 流程图](https://bramp.github.io/js-sequence-diagrams/)  and  [Wordcloud](http://timdream.org/wordcloud/)  and [Slides](http://www.sequencejs.com)

<input type='checkbox' onclick='return false;' > [SideComments.js](http://aroc.github.io/side-comments-demo/)

<input type='checkbox' onclick='return false;' >[CSS animations](http://daneden.github.io/animate.css/) [Gitpage](https://github.com/urzone/animate.css)

山高水远 - 阿鲲  
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="330" height="86" src="https://music.163.com/outchain/player?type=2&amp;id=28457786&amp;auto=0&amp;height=66"></iframe>






富可敌国权可遮天的人看到那些在他们手掌中跳舞的商人们心想，你们就整天跑来跑去谈东谈西，有什么意思呢。
富豪看着手下的手下员工心想，你们就整天码码字递递东西，半年赚不出一平米，有什么意思呢。
手下员工看着屌丝搬砖工心想，你们就会用体力换点小钱喝喝酒，一辈子都开不上车，有什么意思呢
屌丝搬砖看着村子里面的农民心想，你们就会抽烟种天爱劳动，晚上都舍不得开灯看电视，有什么意思呢
农民看着自己家池子里的乌龟心想，你们就会天天趴著，有什么意思呢。
乌龟天天趴著，心想人类活这么短时间却还整天忙来忙去，有什么意思呢。

作者：Tassandar
链接：https://www.zhihu.com/question/20170422/answer/15583363



# Markdown 语法和 MWeb 写作使用说明

## Markdown 的设计哲学

> Markdown 的目標是實現「易讀易寫」。
> 不過最需要強調的便是它的可讀性。一份使用 Markdown 格式撰寫的文件應該可以直接以純文字發佈，並且看起來不會像是由許多標籤或是格式指令所構成。
> Markdown 的語法有個主要的目的：用來作為一種網路內容的*寫作*用語言。

<!-- more -->

## 本文约定

如果有写 `效果如下：`， 在 MWeb 编辑状态下只有用 `CMD + R` 预览才可以看效果[^book]。

[^book]: this is for test.

hello[^hello]


[^hello]: hi

## 标题

Markdown 语法：

```
# 第一级标题 `<h1>` 
## 第二级标题 `<h2>` 
###### 第六级标题 `<h6>` 
```

效果如下：

# 第一级标题 `<h1>` 
## 第二级标题 `<h2>` 
###### 第六级标题 `<h6>` 



## 强调

Markdown 语法：

```
*这些文字会生成`<em>`*
_这些文字会生成`<u>`_

**这些文字会生成`<strong>`**
__这些文字会生成`<strong>`__
```

在 MWeb 中的快捷键为： `CMD + U`、`CMD + I`、`CMD + B`
效果如下：

*这些文字会生成`<em>`*
_这些文字会生成`<u>`_

**这些文字会生成`<strong>`**
__这些文字会生成`<strong>`__

## 换行

四个及以上空格加回车。
如果不想打这么多空格，只要回车就为换行，请勾选：`Preferences` - `Themes` - `Translate newlines to <br> tags`

## 列表

### 无序列表

Markdown 语法：

```
* 项目一 无序列表 `* + 空格键`
* 项目二
	* 项目二的子项目一 无序列表 `TAB + * + 空格键`
	* 项目二的子项目二
```

在 MWeb 中的快捷键为： `Option + U`
效果如下：

* 项目一 无序列表 `* + 空格键`
* 项目二
	* 项目二的子项目一 无序列表 `TAB + * + 空格键`
	* 项目二的子项目二

### 有序列表

Markdown 语法：

```
1. 项目一 有序列表 `数字 + . + 空格键`
2. 项目二 
3. 项目三
	1. 项目三的子项目一 有序列表 `TAB + 数字 + . + 空格键`
	2. 项目三的子项目二
```

效果如下：

1. 项目一 有序列表 `数字 + . + 空格键`
2. 项目二 
3. 项目三
	1. 项目三的子项目一 有序列表 `TAB + 数字 + . + 空格键`
	2. 项目三的子项目二

### 任务列表（Task lists）

Markdown 语法：

```
- [ ] 任务一 未做任务 `- + 空格 + [ ]`
- [x] 任务二 已做任务 `- + 空格 + [x]`
```

效果如下：

- [ ] 任务一 未做任务 `- + 空格 + [ ]`
- [x] 任务二 已做任务 `- + 空格 + [x]`


## 图片

Markdown 语法：

```
![GitHub set up](http://zh.mweb.im/asset/img/set-up-git.gif)
格式: ![Alt Text](url)
```

`Control + Shift + I` 可插入Markdown语法。
如果是 MWeb 的文档库中的文档，还可以用拖放图片、`CMD + V` 粘贴、`CMD + Option + I` 导入这三种方式来增加图片。
效果如下：

![GitHub set up](http://zh.mweb.im/asset/img/set-up-git.gif)

## 链接

Markdown 语法：

```
email <example@example.com>
[GitHub](http://github.com)
自动生成连接  <http://www.github.com/>
```

`Control + Shift + L` 可插入Markdown语法。
如果是 MWeb 的文档库中的文档，拖放或`CMD + Option + I` 导入非图片时，会生成连接。
效果如下：

Email 连接： <example@example.com>
[连接标题Github网站](http://github.com)
自动生成连接像： <http://www.github.com/> 这样

## 区块引用

Markdown 语法：

```
某某说:
> 第一行引用
> 第二行费用文字
```

`CMD + Shift + B` 可插入Markdown语法。
效果如下：

某某说:
> 第一行引用
> 第二行费用文字

## 行内代码

Markdown 语法：

```
像这样即可：`<addr>` `code`
```

`CMD + K` 可插入Markdown语法。
效果如下：

像这样即可：`<addr>` `code`

## 多行或者一段代码

Markdown 语法：

	```js
	function fancyAlert(arg) {
	  if(arg) {
	    $.facebox({div:'#foo'})
	  }

	}
	```

`CMD + Shift + K` 可插入Markdown语法。
效果如下：

```js
function fancyAlert(arg) {
	if(arg) {
		$.facebox({div:'#foo'})
	}
	
}
```

## 顺序图或流程图

Markdown 语法：

	```sequence
	张三->李四: 嘿，小四儿, 写博客了没?
	Note right of 李四: 李四愣了一下，说：
	李四-->张三: 忙得吐血，哪有时间写。
	```

	```flow
	st=>start: 开始
	e=>end: 结束
	op=>operation: 我的操作
	cond=>condition: 确认？

	st->op->cond
	cond(yes)->e
	cond(no)->op
	```

效果如下（ `Preferences` - `Themes` - `Enable sequence & flow chart` 才会看到效果 ）：

```sequence
张三->李四: 嘿，小四儿, 写博客了没?
Note right of 李四: 李四愣了一下，说：
李四-->张三: 忙得吐血，哪有时间写。
```

```flow
st=>start: 开始
e=>end: 结束
op=>operation: 我的操作
cond=>condition: 确认？

st->op->cond
cond(yes)->e
cond(no)->op
```

更多请参考：<http://bramp.github.io/js-sequence-diagrams/>, <http://adrai.github.io/flowchart.js/>

## 表格

Markdown 语法：

```
第一格表头 | 第二格表头
--------- | -------------
内容单元格 第一列第一格 | 内容单元格第二列第一格
内容单元格 第一列第二格 多加文字 | 内容单元格第二列第二格
```

效果如下：

第一格表头 | 第二格表头
--------- | -------------
内容单元格 第一列第一格 | 内容单元格第二列第一格
内容单元格 第一列第二格 多加文字 | 内容单元格第二列第二格


## 删除线

Markdown 语法：

	加删除线像这样用： ~~删除这些~~

效果如下：

加删除线像这样用： ~~删除这些~~

## 分隔线

以下三种方式都可以生成分隔线：

	***

	*****

	- - -

效果如下：

***

*****

- - -


## MathJax

Markdown 语法：


```
块级公式：
$$	x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$

\\[ \frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} =
1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}}
{1+\frac{e^{-8\pi}} {1+\ldots} } } } \\]

行内公式： $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$
```

效果如下（`Preferences` - `Themes` - `Enable MathJax` 才会看到效果）：

块级公式：
$$	x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$

\\[ \frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} =
1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}}
{1+\frac{e^{-8\pi}} {1+\ldots} } } } \\]


行内公式： $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$


## 脚注（Footnote）

Markdown 语法：

```
这是一个脚注：[^sample_footnote]
```

效果如下：

这是一个脚注：[^sample_footnote]

[^sample_footnote]: 这里是脚注信息

## 注释和阅读更多

<!-- comment -->
<!-- more -->
Actions->Insert Read More Comment *或者* `Command + .`
**注** 阅读更多的功能只用在生成网站或博客时。

## TOC

Markdown 语法：

```
[TOC]
```

效果如下：

[TOC]


