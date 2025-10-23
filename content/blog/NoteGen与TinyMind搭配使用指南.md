---
title: NoteGen与TinyMind搭配使用指南
date: 2025-10-23
---
🔗 **工具简介**

[NoteGen](https://notegen.top/) 支持将笔记同步到GitHub仓库的笔记软件。

[TinyMind](https://github.com/mazzzystar/tinymind) 通过GitHub登录，自动创建仓库并提供在线编辑功能的博客网页。

## 📝 **配置步骤**


![屏幕截图 2025-10-23 172755.png](https://raw.githubusercontent.com/Aleeyoo/note-gen-image-sync/main/a8333a4c-cc06-4550-af00-474c9aae4b8c.png)
之后便可以在content-blog目录下编写博客。

1. 参考教程创建仓库后，按NoteGen教程设置同步仓库为"tinymind-blog"
2. 同步配置关键项：
   * 选择GitHub平台并创建Access Token（需勾选repo权限）
   * 自定义同步仓库名填写"tinymind-blog"
   * 确认仓库状态显示为"可用"

### 🖼️ **图片处理**

按照官方教程设置图库即可，之后在NoteGen中编辑直接粘贴图片便可自动上传GitHub相关仓库。

### ⏰ **时间轴修复**

在网页编写的博客会自带时间戳：

```
----------------------------
title: NoteGen与TinyMind搭配使用指南
date: 2025-10-23T06:08:06.191Z
------------------------------
```

因此，在NoteGen编辑在文章开头加上即可。
