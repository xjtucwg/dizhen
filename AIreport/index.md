---
title: 地震目录查询报告
author: doicu
mode : selfcontained
framework: revealjs
hitheme : tommrow
knit: slidify::knit2slides
url :  {lib: /libraries}
revealjs:
  theme: sky
  transition: cube
  center: "true"
bootstrap:
  theme: amelia
navbar:
  title: Slidify
  items: 
    - {item: Home, href: index,  icon: home}
    - {item: "Start", href: start, icon: signin}
    - {item: Author, href: about, icon: pencil}
    - {item: Style, href: style, icon: hand-right, class: dropdown, 
        dropdown: true, menu: [
         {item: io2012, href: 'samples/intro'},
         {item: deck.js, href: 'samples/deck.js'},
         {item: shower, href: 'samples/shower'},
         {item: landslide, href: 'samples/landslide'}
        ]
      }
    - {item: Customize, href: customize, icon: gift}
    - {item: Extend, href: extend, icon: cogs}
    - {item: Publish, href: publish, icon: github}
---



<style>
td{
font-size: 3
}
.title-slide {
  background-color: #e2e2e2;
}

.title-slide hgroup > h1{
  font-family: 'Oswald', '黑体';
  color: #202020;
}

.title-slide hgroup > h2{
  font-family: 'Signika Negative', 'Calibri', '黑体';
  color: #202020;
}

.reveal {font-family: 'Signika Negative', 'Calibri', '黑体';
  color: #202020;
}

strong{
 color: #4876FF;
}
</style>

##  地震目录查询报告
Created by doicu <br/>

[***DOICU***](www.doicu.com)

<script src="../libraries/jquery.min.js"></script>
<script>
			document.write( '<link rel="stylesheet" href="libraries/frameworks/revealjs/css/print/' + ( window.location.search.match( /print-pdf/gi ) ? 'pdf' : 'paper' ) + '.css" type="text/css" media="print">' );
		</script>


---&vertical
## 查询内容

> - .highlight-red 您在***2050月13日25时61分***提交的地震目录查询要求（时间范围:***2050-2100***，空间范围:***ABC-DEF-123***，震级范围:***1-100***），共查询到***-1000***条地震事件，报告已生成并上传至服务器。（蓝色粗体部分为人造数据以保密）


---&vertical ds:soothe
## 事件统计

***ds:soothe
地震事件的统计信息如下表

<iframe src="./pic/1.html" height="280px" width="500px"></iframe>

***ds:soothe
seismicity of all catalog

<iframe src="./pic/下载.png" height="500px" width="400px"></iframe>




---&vertical 
## 空间分析

*** 
### 地震-地理空间分布图

<iframe src="./pic/下载11.png" height="550" width="850"></iframe>

*** 
### 地震-构造空间分布图

<iframe src="./pic/下载22.png" height="550" width="820"></iframe>


---&vertical ds:soothe
## 时间分析 

***ds:soothe
### 地震事件M-T关系图

<iframe src="./pic/下载2.png" height="400px" width="800px"></iframe>

***ds:soothe
### 地震事件G-R关系图

<iframe src="./pic/下载3.png" height="400px" width="800px"></iframe>

***ds:soothe
### 地震事件累计数量时间关系图

<iframe src="./pic/下载4.png" height="400px" width="500px"></iframe>

---&vertical
## 事件列表

查询到主要地震事件详细列表如下：

<iframe src="./pic/2.html" height="400px" width="800px"></iframe>





---&vertical ds:soothe
#### 此报告由AI自动完成

扫描二维码,分享此报告

<iframe src="./pic/下载5.png" height="400px" width="380px"></iframe>

<script>
$('ul.incremental li').addClass('fragment')
</script>

