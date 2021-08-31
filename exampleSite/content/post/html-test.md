---
title: "Html Test"
slug: ""
date: 2021-08-28T21:32:38+08:00
description: ""
---

我们可以借助 HTML 来丰富编辑格式。

### 2-1 文字颜色&大小
```
<font size=5px>这是5px的字号</font>
<font color=#33FFFF>这是蓝色的字</font>
<font size=5px color=#33FFFF>这是蓝色的字</font>
```
<font size=5px>这是5px的字号</font>
<font color=#33FFFF>这是蓝色的字</font>
<font size=5px color=#33FFFF>这是蓝色的5px字</font>


### 2-2 文字上标&下标
```
这是上标<sup>2</sup>
这是下标<sub>1</sub>
```
这是上标<sup>2</sup>
这是下标<sub>1</sub>


### 2-3 换行&空格
```
<br><!-- 换行 -->
&nbsp;  <!-- 一个字符的半角的空格 -->
&ensp;  <!-- 一个字符的半角的空格（1/2个中文宽度） -->
&emsp;  <!-- 两个字符的全角的空格（1个中文宽度） -->
&thinsp;  <!-- 小于一个字符的空格 -->
```


### 2-4 新标签页打开
```
<a href="https://github.com" target="_blank">GitHub</a>
```
<a href="https://github.com" target="_blank">GitHub</a>


### 2-5 高亮文本
```
<mark>高亮文本</mark>
```
<mark>高亮文本</mark>


### 2-6 位置
```
<center>居中</center>
<p style="text-align:left">居左</p>
<p style="text-align:right">居右</p>
```
<center>居中</center>
<p style="text-align:left">居左</p>
<p style="text-align:right">居右</p>



### 2-7 图片设置高宽
```
<img src="图片地址"  width="300" height="300">
```
<img src="https://images.unsplash.com/photo-1512621776951-a57141f2eefd?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=750&q=80"  width="192" height="108">

> Photo by <a href="https://unsplash.com/@annapelzer?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Anna Pelzer</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

### 2-8 文本提示
```
<abbr title="显示内容">将鼠标移上来看看</abbr>
```
<abbr title="显示内容">将鼠标移上来看看</abbr>


### 2-9 注音
```
<ruby>你好<rt>Ni Hao</rt>！<ruby>
```
<ruby>你好<rt>Hello</rt>！<ruby>


### 2-10 折叠
```
<details>
<summary>点击展开文本</summary>
<p>Hello World!</p>
</details>
```
<details>
<summary>点击展开文本</summary>
<p>Hello World!</p>
</details>