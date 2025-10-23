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

<!-- 统一容器样式，增加上下间距避免内容拥挤 -->

<div style="display:flex; gap:12px; flex-wrap:wrap; align-items:center; justify-content:center; margin:20px auto; padding:0 15px;">
  <!-- 优化跳动动画：增加缓动效果，让跳动更自然 -->
  <a href="https://www.ifdian.net/a/leoowa" target="_blank" rel="noopener noreferrer" 
     style="text-decoration:none; display:inline-block; animation: bounce 1.2s infinite ease-in-out; transition: transform 0.2s;">
    <img src="https://raw.github.com/Aleeyoo/note-gen-image-sync/main/b608f211-4aec-4994-9d43-8f80c150c21d.gif" 
         style="width:32px; height:32px; border:0; border-radius:4px; transition: opacity 0.3s;">
  </a>

<!-- 其他图标添加hover效果，提升交互感 -->

<a href="https://github.com/Aleeyoo" target="_blank" rel="noopener noreferrer" style="text-decoration:none; transition: transform 0.2s;">
    <img src="https://img.shields.io/badge/Aleeyoo-3498db?style=for-the-badge&logo=blogger&logoColor=white" 
         style="height:32px; width:auto; border:0; border-radius:4px; transition: opacity 0.3s;">
  </a>
  <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/" target="_blank" rel="noopener noreferrer" style="text-decoration:none; transition: transform 0.2s;">
    <img src="https://img.shields.io/badge/CC%20BY--NC--SA%204.0-9b59b6?style=for-the-badge&logo=creative-commons&logoColor=white" 
         style="height:32px; width:auto; border:0; border-radius:4px; transition: opacity 0.3s;">
  </a>
</div>

<style>
  /* 优化跳动动画：调整幅度和节奏，避免过于生硬 */
  @keyframes bounce {
    0%, 100% {
      transform: translateY(0);
    }
    50% {
      transform: translateY(-8px); /* 减小跳动幅度，更显精致 */
    }
  }
  
  /* 统一hover效果：所有图标hover时轻微放大+提升透明度 */
  a:hover {
    transform: scale(1.05);
  }
  a:hover img {
    opacity: 0.9;
  }
</style>



