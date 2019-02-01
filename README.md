# Vditor

## 简介

[Vditor](https://github.com/b3log/vditor) 是一款浏览器端的 Markdown 编辑器，使用 TypeScript 实现。

## 背景

我们在开发 [Solo](https://github.com/b3log/solo)、[Pipe](https://github.com/b3log/pipe)、[Sym](https://github.com/b3log/symphony) 的初期是直接使用 WYSIWYG 富文本编辑器的。那时候基于 HTML 的编辑器非常流行，项目中引用起来也很方便，也符合用户当时的使用习惯。

后来，Markdown 的崛起逐步改变了大家的排版方式。再加上我们这几个项目都是面向程序员用户的，所以迁移到 md 上也是大势所趋。我们选择了 [CodeMirror](https://github.com/codemirror/CodeMirror)，这是一款优秀的编辑器，它对开发者提供了丰富的编程接口，对各种浏览器的兼容性也比较好。

再后来，随着我们项目业务需求方面的沉淀，使用 CodeMirror 有时候会感到比较“笨重”。比如要实现 @自动完成用户名列表、插入 Emoji、上传文件等就需要比较深入的二次开发，而这些业务需求恰恰是很多项目场景共有且必备的。

终于，我们决定开始在社区项目 Sym 上自己实现编辑器。随着几个版本的迭代，Sym 的编辑器也日趋成熟。在我们运营的社区[黑客派](https://hacpai.com)上陆续有人问我们是否能将编辑器单独抽离出来提供给大家使用。与此同时，我们的前端主程 [V](https://hacpai.com/member/Vanessa) 同学对于维护分散在各个项目中的编辑器也感到有点力不从心了，外加她最近在学 TypeScript 正好需要练手实践，所以就决定使用 ts 来实现一个全新的浏览器端 md 编辑器。

于是，Vditor 就这样诞生了。

## 功能

* 插入原生 Emoji、可设置常用表情列表
* Markdown 语法排版、支持工具栏按钮、快捷键
* 上传文件、支持多文件同时上传、实时进度、速率显示
* 全屏、分屏实时预览、滚动同步定位
* 多主题支持、内置黑白两套
* 多语言支持、内置中英文
* 支持主流浏览器、支持移动端

## 文档

* [《提问的智慧》精读注解版](https://hacpai.com/article/1536377163156)
* Vditor 使用指南 TBD

## 授权

Vditor 使用 [MIT](https://opensource.org/licenses/MIT) 开源协议，请务必遵循该开源协议相关约定。

## 社区

* [讨论区](https://hacpai.com/tag/vditor)
* [报告问题](https://github.com/b3log/viditor/issues/new/choose)

## 鸣谢

* [Markdown](https://en.wikipedia.org/wiki/Markdown)：轻量级纯文本排版语言
* [TypeScript](https://github.com/Microsoft/TypeScript)：类型化的 JavaScript 超集
* [Sym](https://github.com/b3log/symphony)：一款用 Java 实现的现代化社区（论坛/BBS/社交网络/博客）平台