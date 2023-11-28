## bioinformatics-rss-feed

### 简介

我是一名生信从业人员，日常接收专业信息的渠道主要有以下几个：
- 期刊杂志。
- blog。
- 推特（X）。
- 微信公众号
- 别人分享。

目前我用RSS订阅了一些期刊和少量blog，这些都是自带RSS支持的。但是微信公众号、推特等并不支持RSS订阅，之前我并考虑将其纳入RSS。最近考虑丰富一下RSS中的内容，特别是想把RSS作为主力的信息获取方式，减少打开不同app的操作。另外，随着关注的微信公众号的增加，有价值的信息被稀释，专业信息变得并不容易获取。而推特由于众所周知的原因，我并能方便的在碎片化时间处理（手机增强上网与内网穿透软件不可同时打开）。这增加了我想把不同渠道的信息汇总到RSS中的欲望。因此我创建了本仓库，用来探索、分享不同渠道信息转换成RSS的方法。

### 杂志（journal）

分类|名称|RSS|增强上网|备注
---|---|---|---|---
杂志|Nature Reviews Genetics|https://www.nature.com/nrg.rss|N|官方支持
杂志|Nature Methods|https://www.nature.com/nmeth.rss|N|官方支持
杂志|Nature Genetics|https://www.nature.com/ng.rss|N|官方支持
杂志|Nature|https://www.nature.com/nature.rss|N|官方支持
杂志|Most Recent Articles: BMC Bioinformatics|https://bmcbioinformatics.biomedcentral.com/articles/most-recent/rss.xml|N|官方支持
杂志|Most Accessed Articles: BMC Bioinformatics|https://bmcbioinformatics.biomedcentral.com/articles/most-accessed/rss.xml|N|官方支持
杂志|Bioinformatics : nature.com subject feeds|https://www.nature.com/subjects/bioinformatics.rss|N|官方支持


之前订阅了oxford academic旗下三本杂志，但是最近这些地址在TTRSS软件无法解析。奇怪的是用thunderbird可以成功解析。我去官网也没找到RSS的入口，怀疑是不是官方要做了什么修改。后续有空再研究吧。
- [Human Reproduction Current Issue](https://academic.oup.com/rss/site_5285/3151.xml).雷鸟可以订阅，但是ttrss无法订阅。
- [Nucleic Acids Research Current Issue](https://academic.oup.com/rss/site_5127/3091.xml).
- [Briefings in Bioinformatics Current Issue](http://academic.oup.com/bib)
- [Bioinformatics Current Issue](http://academic.oup.com/bioinformatics)。

**NCBI pubmed是支持把搜索条件转换成RSS的，可以作为一种信息来源**。

### 博客（blog）

独立博客几乎都支持RSS。

分类|名称|RSS|增强上网|备注
---|---|---|---|---
blog|Ensembl blog|https://www.ensembl.info|N|官方支持
blog|Heng Li's blog|https://lh3.github.io/rss.xml|N|官方支持
blog|阮一峰的网络日志|http://www.ruanyifeng.com/blog/atom.xml|N|官方支持
blog|月光博客|https://www.williamlong.info/rss.xml|N|官方支持

### 推特（X）

推特本身不支持RSS，但是借助nitter这个项目可以曲折实现，但是需要增强上网。关注的人员见[此](parts/twitters.utf-8.txt)。
