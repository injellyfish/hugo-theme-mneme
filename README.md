# Mneme

> 用于中文小说写作的 Hugo 主题

<b>WARNING：作者很菜，这个主题不能保证后续更新或维护😥🙏</b>

**另：请使用 `public` 发布博客，避免部署时出现错误！**

## 安装

1. 新建一个 [Hugo](https://gohugo.io/) 站点文件
2. `Clone` 或者 `Download` 这个仓库，移动到 `themes` 文件夹
3. 用 `exampleSite/config.yaml` 替换掉站点文件里的 `config.toml`
4. 修改 `config.yaml` 的配置，完成

## 写作

### 新书籍：

① 在终端执行以下命令：

> 建议“BookName”使用英文或数字

```
hugo new --kind book BookName
```

② 在站点的 `content` 文件夹里会生成一个 `BookName` 文件，点开 `BookName/_index.md` 修改书籍信息：

```
---
title: "书籍名称"
warning: "阅读须知"
description: "书籍简述"
categories:
    - "分类"
tags:
    - "标签"
---

书籍详细内容，会出现在书籍目录上方

```

完成。

### 新章节：

① 在终端执行以下命令：

```
hugo new BookName/ChapterName.md
```

② 在 `content/BookName/ChapterName.md` 下修改章节信息：

```
---
title: "章节标题"
slug: "链接"
date: 日期，自动生成
description: "章节描述，如设置为空则会选取章节前五十字"
---
```

> 目录按照章节的日期进行排序，旧章节位于前面

完成。

## 评论

可以把评论系统的代码放置在 `themes/hugo-theme-mneme/layouts/partials/comment.html` 里面。

我所知的评论系统（排名不分先后）：[Disqus](http://disqus.com/)，[Gitalk](https://github.com/gitalk/gitalk)，[Waline](https://waline.js.org/)，[Vssue](https://vssue.js.org/)，[Utterances](https://utteranc.es/)，[Giscus](https://giscus.app/) 和 [Cusdis](https://cusdis.com/)。

## 感谢

|  内容   |  来源  |  许可  |
| :---:  | :----:  | :----:  |
| 主题来源 | [@yihui/hugo-ivy](https://github.com/yihui/hugo-ivy)| [The Unlicense](https://github.com/yihui/hugo-ivy/blob/master/LICENSE.md) |
| 夜间模式 | [@BetaHuhn/drkmd.js](https://github.com/BetaHuhn/drkmd.js) | [MIT License](https://github.com/BetaHuhn/drkmd.js/blob/master/LICENSE) |
| 夜间配色 | [@arcticicestudio/nord](https://github.com/arcticicestudio/nord) | [MIT License](https://github.com/arcticicestudio/nord/blob/develop/LICENSE.md) |
| 排版参考 | [@sofish/typo.css](http://github.com/sofish/typo.css) | [MIT License](https://github.com/sofish/typo.css/blob/master/license.txt) |
| 排版参考 | [@lepture/yue.css](https://github.com/lepture/yue.css) | MIT License |
| 图标图案 | [Font Awesome](https://fontawesome.com/) | [Creative Commons Attribution 4.0 International license](https://fontawesome.com/license) |

## 许可

[The Unlicense](https://github.com/injellyfish/hugo-theme-mneme/blob/master/LICENSE)

欢迎你自由地使用或修改 Mneme！但请注意主题中使用到的其他仓库许可。
