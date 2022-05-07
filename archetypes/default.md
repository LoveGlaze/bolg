---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
timezone: "UTC+8"
tags: ['🏷️短篇', '🏷️随笔']  #标签
categories: ['摘抄']  #分类
description: ''  #描述
weight: 1  #置顶，1显示第一，依次递减
draft: false 
cover: "/images/.jpg" #封面图
toc: true  #左边目录显示控制
grow: large | full   #封面图片大小，large占两个格子，full占一栏
math: md  #数学符号
aplayer: true  #aplayer支持
dplayer: true
math: true   #litax渲染
slug: {{ substr (md5 (printf "%s%s" .Date (replace .TranslationBaseName "-" " " | title))) 4 8 }} #日期和标题计算哈希值，生成永久链接
---

<!-- 音乐aplayer， -->
{{<aplayer
url="https://lovekevin.top/d/放松一下/Chouchou - sign 0 (サインノート).flac"
name="sign 0 (サインノート)"
artist="Chouchou"
cover="/images/000.jpg"
lrc="https://lovekevin.top/d/放松一下/Chouchou - sign 0 (サインノート).lrc"
lrcType="3"
>}}

<div style="display:none">
<!--B站视频应用-->
{{< bilibili av498363026 >}}
<!--油管视频引用-->
{{< youtube hDy9BrB9_VU >}}


<!-- 视频调用dplyer， -->
{{< dplayer
url="https://qiniu.sukoshi.xyz/video/%E7%BE%8E.mp4"
pic="https://qiniu.sukoshi.xyz/video/%E7%BE%8E.mp4?vframe/jpg/offset/10"
>}}
</div>
<div align=center>




</div>
<p align=right>by：LoveGlaze</p>

<div>
    <div> 文章均来源于网络，侵权联系作者删帖。</div>    
    <div>来源 <a target="_blank" href="glaze.lovekevn.top"> © LoveGlaze's Blog </a></div>
    <div class="copyright-text">作品采用 <a class="text-decoration-none" target="_blank" href="https://creativecommons.org/licenses/by/4.0/deed.zh">
     知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议 </a>进行许可 </div>
</div>