# [Serif 和 Sans-Serif 字体的区别](http://kb.cnblogs.com/page/192018/)

在西方国家罗马字母阵营中，字体分为两大种类：Sans Serif 和 Serif，打字机体虽然也属于 Sans Serif，但由于是等宽字体，所以另外独立出 Monospace 这一种类。例如在 Web 中，展示计算机程序代码时，常常要使用**等宽字体**（Monospace）。

Serif 的意思是，在字的笔划开始及结束的地方有额外的**装饰**，而且笔划的粗细会因直横的不同而有不同。相反的，Sans Serif 则**没有**这些额外的装饰，笔划粗细大致差不多。如下图： 


![Sans Serif和Serif](http://images.cnitblog.com/kb/1/201311/01112728-71dd2eade8c24ab38769eaa00be7fedf.jpg)
![Sans Serif和Serif](http://img1.ph.126.net/Hvy3B1ZG83Oq0cRFSJvTVQ==/2522015791345425397.jpg)

可以看出，我们平时所用的 `Georgia`、`Times New Roman` 等就属于 Serif 字体，而 `Arial`、`Tahoma`、`Verdana` 等则属于 Sans Serif 字体。对中文而言，同样存在这两大种类，很明显，`宋体`、`细明体`(繁体中常用)等就属于 Serif，而`黑体`、`幼圆`等则属于Sans Serif。 

## Serif 和 Sans Serif 的比较

- Serif 字体容易**辨认**，因此易读性较高。反之 Sans Serif 则较**醒目**，但在行文阅读的情况下，Sans Serif 容易造成字母辨认的困扰，常会有来回重读及上下行错乱的情形。  
- Serif 强调了字母笔划的开始及结束，因此较易前后连续性的**辨识**。  
- Serif 强调一个**词**(word），而非单一的**字母**（character）；反之 Sans Serif 则强调**个别**字母。  
- 在**小字体**的场合，通常 Sans Serif 比 Serif 更清晰。  

因为**黑体字**属于“**无衬线体**”（Sans-serif），而宋体字属于“**有衬线体**”（Serif），后者对于人眼的辨识来说会更轻松一些，所以阅读的时候会比较舒服。日本文字偏欧美的无衬线体（Sans-serif），所以大部分的人都使用**歌德体**(Gothic，相当于西洋文字的无衬线体)。

![宋体和黑体](http://images.cnitblog.com/kb/1/201311/01112801-e55fefdf2fe64904b96d7834e36a9dd3.jpg)

![衬线和非衬线](http://images.cnitblog.com/kb/1/201311/01112828-acdada9b66e8408fbecb9f74c20d0f5c.jpg)

## 适用用途
通常文章的**内文、正文**使用的是易读性较佳的 Serif 字体，这可增加易读性。而且长时间阅读下因为会以 word 为单位来阅读，较不容易疲倦。而**标题、表格**内用字则采用较醒目的 Sans Serif 字体，它需要显著、醒目，但不必长时间盯着这些字来阅读。

像宣传品、海报类，为求**醒目**，它的短篇段落也会采用 Sans Serif 字体。但在书籍、报刊杂志，正文有相当篇幅的情形下，则应采用 Serif 字体来减轻读者阅读上的负担。在 Web 设计及浏览器设置中也应遵循此原则为是。

## 实际应用
在 Firefox 中（目前似乎只有 Firefox 有此功能），可以分别单独指定 Sans Serif、Serif 及 Monospace 的中西文字体。然而这个选项并未设置在工具菜单中，不过可以在 Addressbar 中键入 `about: config`，然后在 Filter 中过滤 font 找到如下 Preference Name：

```
font.name.monospace.x-western
font.name.monospace.zh-CN
font.name.sans-serif.x-western
font.name.sans-serif.zh-CN
font.name.serif.x-western
font.name.serif.zh-CN
```

你可以依照上述 Sans Serif、Serif 及 Monospace 的原则来分别指定一种对应字体。按照 W3C 的 CSS 规则，在 font（或者 font-family）的最后都要求指定一个 Serif 这样的 Generic-family，避免客户端实在没有指定字体时使用本机上的 Serif 默认字体。

### 衬线字体
![Georgia-TimesNewRoman-宋体](http://images.cnitblog.com/kb/1/201311/01112858-2687d87da74f4ec68dcc09afad69f362.jpg)

因为衬线字体的可读性非常好，所以它应用的最多的地方也正是出版物或者印刷品的正文内容等以**大段文字**作为表现形式的作品上。

比较常见的衬线字体有：西文的 Georgia, Garamond, Times New Roman； 中文的**宋体**等等。

### 无衬线字体
![Verdana-Arial-幼圆](http://images.cnitblog.com/kb/1/201311/01112918-c103afd324144980aa28611d1c216340.jpg)

无衬线字体比较圆滑，线条一般粗细均匀。比较适合用作**艺术字**、**标题**等。因为无衬线字体通常粗细比较均匀，所以在小字体显示的时候，可读性会降低，容易引起视觉疲劳。

常见的无衬线字体有：西文的 Trebuchet MS, Tahoma, Verdana, Arial, **Helvetica**；中文的幼圆，隶书等。

### 其他的通用字体族
在印刷学中，除了 Serif 和 Sans-Serif 之外，通常还有 Monospace 等宽字体、scripts 手写体（比如花体）、blackletter 铅字体（也叫 gothic 哥特体，严格的说，很多常用的 Serif 字体其实是 gothic 字体）、ornamental 装饰体（那些在文字笔划上或者周围有装饰花纹的字体。很多中世纪书籍上很常见。如果脑残体真的成了字体，那么应该可以算装饰体吧……）和 symbol 符号字体（比如有名的 wedding123……）

#### Monospace 等宽字体
所谓的**等宽字体**，是指每个字符宽度都一致的字体。一个著名的例子就是 Courier New 字体。

因为字符宽度一致，所以特别容易对齐，能快速精确的定位到某行某列，因此经常用来显示代码。

Cursive 书写体：相当于印刷学中的手写体，中文的华文行草就是这样一个字体。

#### 网页设计字体
网页设计中的默认字体：字体大小(12px)、行高(18px)

```CSS
font: 12px/1.5 Tahoma, Helvetica, Arial, sans-serif;
```

- font-family 默认采用 Tahoma. **Tahoma** 是英文 Windows 操作系统的默认字体，这个字体比较均衡，显示中英文混排很不错，是经久耐看的一款字体。  
- Mac OS X 系统有一款比 Tahoma 更典雅的系统默认字体：**Helvetica**。非 Mac 系统的 Helvetica 字体都是 Rip 版。  
- Arial 是早期 Windows 英文系统的默认字体，XP 和 Vista 上都是 Tahoma。  
- 最后的 sans-serif 是针对强悍的 Linux DIY 族。Linux 默认只有 kernel，字体完全由用户自定义，针对这部分用户，sans-serif 可能能派上用场。  
- 最后，无论在 XP 还是 Vista 下，不指定网页的中文字体时，默认就是**宋体**。因此 font-family 里的'宋体'是多余的，可以省去。  
