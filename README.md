# Markdown语法
Markdown learning

https://coding.net/help/doc/project/markdown.html#i-9

@[TOC]
#hello


#Markdown语法介绍
Markdown 是一种轻量级标记语言，让写作者专注于写作而不用关注样式。Coding 的许多版块均采用了 Markdown 语法，比如冒泡、讨论、Pull Request 等。

##1.1 标题

用 Markdown 书写时，只需要在文本前面加上『# 』即可创建一级标题。同理，创建二级标题、三级标题等只需要增加『# 』个数即可，Markdown 共支持六级标题。如下所示：



[comment]: 可以用专一符号\插入特殊符号，如#


## 1.2 锚点
Coding会针对每个标题，在解析时都会添加锚点ID，如
> \#锚点

会被解析成
>\\\<h1 id="user-content-锚点">锚点</h1>

注意我们添加了一个 user-content- 的前缀，所以如果要自己添加跳转链接要使用 Markdown 的形式，且链接要加一个 user-content- 前缀，如：



## 1.3 引用

Markdown 标记区块引用和 email 中用 『>』的引用方式类似，只需要在整个段落的第一行最前面加上 『>』 ：

    hello


## 1.4 列表

- Red
- blue
- yellow

* hello
* this
* is

1. 一个
2. 两个
3. sange

## 1.5 代码



```
print("hello Markdown")
```



## 1.6 强调

*斜体*

**加粗**

_斜体_

__加粗__



## 1.7 自动链接



## 1.8 表格

|First Header | Second Header | Third Header|

------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell

|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

| 123 |
|----|
|abc|




##1.9 分割线

haha？？？？
---
haha



##1.10 图片





##1.11 流程图

```graph
 graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->E;
    E-->F;
    D-->F;
    F-->G;
```





## 1.12 时序图




## 1.13 甘特图

```graph
gantt
        dateFormat  YYYY-MM-DD
        title Adding GANTT diagram functionality to mermaid
        section A section
        Completed task            :done,    des1, 2014-01-06,2014-01-08
        Active task               :active,  des2, 2014-01-09, 3d
        Future task               :         des3, after des2, 5d
        Future task2               :         des4, after des3, 5d
        section Critical tasks
        Completed task in the critical line :crit, done, 2014-01-06,24h
        Implement parser and jison          :crit, done, after des1, 2d
        Create tests for parser             :crit, active, 3d
        Future task in critical line        :crit, 5d
        Create tests for renderer           :2d
        Add to mermaid                      :1d
```

