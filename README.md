# slidev-theme-zjsu

[![NPM version](https://img.shields.io/npm/v/slidev-theme-cuc?color=3AB9D4&label=)](https://www.npmjs.com/package/slidev-theme-cuc)

A (...) theme for [Slidev](https://github.com/slidevjs/slidev).

[Live Demo](https://slidev-theme-cuc.netlify.app)
<!--
  Learn more about how to write a theme:
  https://sli.dev/themes/write-a-theme.html
--->

<!--
  run `npm run dev` to check out the slides for more details of how to start writing a theme
-->

<!--
  Put some screenshots here to demonstrate your theme

  Live demo: [...]
-->

## Install

Add the following frontmatter to your `slides.md`. Start Slidev then it will prompt you to install the theme automatically.

<pre><code>---
theme: <b>ZJSU</b>
---</code></pre>

Learn more about [how to use a theme](https://sli.dev/themes/use).

## Layouts

This theme provides the following layouts:

### cover

![cover](https://cdn.jsdelivr.net/gh/ranxi2001/blog-imgs@main/img/cover.jpg)

### default page

![about](https://cdn.jsdelivr.net/gh/ranxi2001/blog-imgs@main/img/Snipaste_2023-05-11_15-19-45.jpg)

### imagex

```markdown
---
layout: imagex
image: https://gitee.com/isaaccaa/pictures/raw/master/img2022/0186795d843896a8012060be1cbe75.jpg
pos: center
size: h-260px
---

somgthing

---
```

![image](https://cdn.jsdelivr.net/gh/ranxi2001/blog-imgs@main/img/Snipaste_2023-05-11_15-19-57.jpg)

## Contributing

- `npm install`
- `npm run dev` to start theme preview of `example.md`
- Edit the `example.md` and style to see the changes
- `npm run export` to generate the preview PDF
- `npm run screenshot` to generate the preview PNG

## Usage
- 安装方法：`npm init slidev`
- 修改方法：用typora修改slides.md
- 终端运行开始展示：`npx slidev`
- 导出pdf： `npx slidev export`
- 环境软件使用教程：[slidev环境使用教程](https://wzzju.github.io/slides/slidev/2022/03/20/make-slides/#:~:text=3.2%20%E5%8D%95%E7%8B%AC%E5%AF%BC%E5%87%BAPDF%E6%96%87%E4%BB%B6%201%20%E5%AE%89%E8%A3%85%20playwright-chromium%20%EF%BC%9A%202%20%E5%AF%BC%E5%87%BApdf%E6%A0%BC%E5%BC%8F%E5%B9%BB%E7%81%AF%E7%89%87%EF%BC%9A,%23%20slidev%20%3E%3D%20v0.21%20npx%20slidev%20export%20--with-clicks)
- Slidev语法教程：[slidev语法教程](https://juejin.cn/post/7177724154399948857)
- 官网使用教程：[Slidev官网教程]https://cn.sli.dev/guide/syntax.html#embedded-styles
