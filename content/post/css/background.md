---
title: "CSS - 背景顏色 & 背景圖片"
date: 2019-01-03T15:10:20+08:00
lastmod: 2019-01-03T15:10:20+08:00
draft: false
keywords: ["CSS"]
description: ""
tags:  ["CSS"]
categories: ["CSS"]
author: "常常喜樂"

# You can also close(false) or open(true) something for this content.
# P.S. comment can only be closed
comment: false
toc: false
autoCollapseToc: true
# You can also define another contentCopyright. e.g. contentCopyright: "This is another copyright."
contentCopyright: false
reward: false
mathjax: false
---

## 一、背景顏色 background-color

```
<div style="background-color:#FFBB73">CSS background-color #FFBB73</div>
```
<div style="background-color:#FFBB73">CSS background-color #FFBB73</div>

```
<div style="background-color:pink">CSS background-color pink</div>
```
<div style="background-color:pink">CSS background-color pink</div>

```
<div style="background-color:rgb(232,106,192)">CSS background-color RGB 232,106,192</div>
```
<div style="background-color:rgb(232,106,192)">CSS background-color RGB 232,106,192</div>  

## 二、背景圖片 background-image

```
1. 網頁背景圖片

<html>

<head>
<style type="text/css">
body
{ 
background-image: 
url('要顯示的圖片網址');
background-repeat: repeat-x repeat-y;
background-color: 背景顏色;
}
</style>
</head>

<body>
</body>

</html>

2. 區塊背景圖片

<style>
#DIV1{
width:300px;
height:200px;
background-color:lightskyblue;　//淡藍色背景
border:1px #ccc solid;
}
#DIV2{
width:300px;
height:200px;
background-image:url(/images/b01.png);　//插入背景圖片
background-color:lightskyblue;　//淡藍色背景
border:1px #ccc solid;
}
</style>
<div id="DIV1">
這是沒套用背景圖片的 DIV 區塊
</div>
<div id="DIV2">
這是有套用背景圖片的 DIV 區塊
</div>

--- 簡言之 ---
<div style="background-image:url(背景圖片);width:380px;height:120px;">
這個 DIV 區塊使用 300x120 的背景圖片
</div>
```

<style>
#DIV1{
width:300px;
height:200px;
background-color:lightskyblue;　//淡藍色背景
border:1px #ccc solid;
}
#DIV2{
width:300px;
height:200px;
background-image:url(/images/css-bg.png);　//插入背景圖片
background-color:lightskyblue;　//淡藍色背景
border:1px #ccc solid;
}
</style>
<div id="DIV1">
這是沒套用背景圖片的 DIV 區塊
</div>
<div id="DIV2">
這是有套用背景圖片的 DIV 區塊
</div>