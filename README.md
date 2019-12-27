# Markdown语法
Markdown learning

https://coding.net/help/doc/project/markdown.html#i-9

@[TOC]
#hello


#Markdown语法介绍
Markdown 是一种轻量级标记语言，让写作者专注于写作而不用关注样式。Coding 的许多版块均采用了 Markdown 语法，比如冒泡、讨论、Pull Request 等。

##标题

用 Markdown 书写时，只需要在文本前面加上『# 』即可创建一级标题。同理，创建二级标题、三级标题等只需要增加『# 』个数即可，Markdown 共支持六级标题。如下所示：



[comment]: 可以用专一符号\插入特殊符号，如#


##锚点
Coding会针对每个标题，在解析时都会添加锚点ID，如
> \#锚点

会被解析成
>\\\<h1 id="user-content-锚点">锚点</h1>

注意我们添加了一个 user-content- 的前缀，所以如果要自己添加跳转链接要使用 Markdown 的形式，且链接要加一个 user-content- 前缀，如：



##引用

Markdown 标记区块引用和 email 中用 『>』的引用方式类似，只需要在整个段落的第一行最前面加上 『>』 ：

    hello



