---
title: NoteGen与TinyMind奇妙搭配
date: 2025-10-23
---

## 介绍

[NoteGen](https://notegen.top/) 作为一个将笔记同步到GitHub仓库的笔记软件。

[TinyMind](https://github.com/mazzzystar/tinymind) 作为一个通过GitHub登录，自动创建仓，在线编辑的博客网页。

## 搭配

通过[教程](https://tinymind.me/blog/%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA%E7%9A%84%E4%B8%89%E7%A7%8D%E6%96%B9%E5%BC%8F)创建仓库后，按照NoteGen教程步骤，设置同步仓库为tinymind-blog。
![屏幕截图 2025-10-23 172755.png](https://raw.githubusercontent.com/Aleeyoo/note-gen-image-sync/main/a8333a4c-cc06-4550-af00-474c9aae4b8c.png)
之后便可以在content-blog目录下编写博客。

## 其他

### 图片

按照官方教程设置图库即可，之后在NoteGen中编辑直接粘贴图片便可自动上传GitHub相关仓库。

### 时间轴修复

在网页编写的博客会自带时间戳：

```
----------------------------
title: NoteGen与TinyMind奇妙搭配
date: 2025-10-23T06:08:06.191Z
------------------------------
```

因此，在NoteGen编辑在文章开头加上即可。

