---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
tags: ['', '', '', '']
description: ''
draft: true
cover: 
toc: true
grow: large
math: md
aplayer: true
dplayer: true
---
<!-- 音乐aplayer，实际写的时候 '['替换为 '{' ']'替换为'}' -->
[[< aplayer
    url="https://qiniu.sukoshi.xyz/public/music/鹿乃 - アイロニ.mp3"
    name="アイロニ"
    artist="鹿乃"
    cover="https://qiniu.sukoshi.xyz/public/music/鹿乃 - アイロニ.jpg"
    lrc="https://qiniu.sukoshi.xyz/public/music/鹿乃 - アイロニ.lrc"
    lrcType="3"
>]]

{{< bilibili av498363026 >}}
[[< youtube hDy9BrB9_VU >]]


<!-- 视频调用dplyer，实际写的时候 '['替换为 '{' ']'替换为'}' -->
[[< dplayer
    url="https://qiniu.sukoshi.xyz/video/%E7%BE%8E.mp4"
    pic="https://qiniu.sukoshi.xyz/video/%E7%BE%8E.mp4?vframe/jpg/offset/10"
>]]