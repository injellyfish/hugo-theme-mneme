---
title: "Markdown Test"
slug: "mt"
date: 2021-08-28T21:16:25+08:00
description: "这是一段描述"
---

### 1-1 基础元素

|  效果   | Markdown  |  HTML |  快捷键  |
| :----:  | :----:  | :----:  | :----: |
| **加租**  | `**加粗**` |  `<b>加粗</b>` | Ctrl+B |
| *斜体*  | `*斜体*` |  `<i>斜体</i>` | Ctrl+I |
| 加租斜体  | `加粗斜体` |  `<b><i>加粗</i></b>` | Ctrl+B+I |
| ~~删除线~~  | `~~删除线~~` |  `<s>删除线</s>` | Alt+S |
| <u>下划线</u>  | `\` |  `<u>下划线</u>` | \ |


### 1-2  标题

```
<!-- 注意#后要空格 -->
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

### 1-3 分割线  
```
三个或三个以上的 *** 或 --- 或 ___
```
***

### 1-4 列表
```
<!-- 有序列表 -->
1. 需要空格
2. 第二个
   1. 第三个
```
1. 需要空格
2. 第二个
   1. 第三个

```
<!-- 无序列表 -->
- 也要空格
- 你好！
    - Hello
```
- 也要空格
- 你好！
  - Hello

```
<!-- 任务列表 -->
- [ ] 还没完成（中间有空格）
- [x] 完成了
```
- [ ] 还没完成（中间有空格）
- [x] 完成了

### 1-5 引用
```
> 需要空格
> >继续引用
```
> 需要空格
>
> >继续引用

### 1-6 脚注
```
这是一段文字[^1]
[^1]: 这是脚注
```

这是一段文字[^1]
[^1]: 这是脚注

### 1-7 表格
```
|  左对齐   | 居中  |  右对齐 |
| :----  | :----:  | ----:  |
| Hello  | World | 你好 |
```
|  左对齐   | 居中  |  右对齐 |
| :----  | :----:  | ----:  |
| 这是左对齐的文本  | 这是居中的文本 | 这是右对齐的文本 |

### 1-8 链接
```
[GitHub]([https://github.com/)
```
[GitHub]([https://github.com/)

### 1-9 图片
```
![](图片地址)

<!-- 建议使用<img src="">标签插入图片 -->
```

![](https://images.unsplash.com/photo-1512621776951-a57141f2eefd?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=750&q=80)

> Photo by <a href="https://unsplash.com/@annapelzer?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Anna Pelzer</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

### 1-10 代码
```
`代码内容`
<!-- 代码块是用```包住代码 -->
```
`代码内容`
