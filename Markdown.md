# Markdown语法

## 基础语法

### 标题

一级标题：#

二级标题：##

三级标题：###

### 强调 （加粗）
方法一：**文本**
方法二：__文本__

### 斜体
方法一：*文本*
方法二：_文本_

## 列表

#### 无序列表

**单级无列表：**

- 示例一
- 示例二
- 示例三

**多级无序列表：**

- 示例一
  - 示例一
    - 示例一

#### 有序列表

**单级有序列表**

1. 示例一
2. 示例二
3. 示例三

**多级有序列表**

1. 示例一
   1. 示例一
      1. 示例一

### 删除线

方法：~~文本~~

## 高级语法

### 链接

**内嵌式链接**

- 外部链接：[百度 <img src="https://www.baidu.com/img/bd_logo1.png?where=super" height="25">](https://www.baidu.com "Baidu")
- 链接至其他文档（当前目录）：[TESTE_MD1](test_md1.md)
- 链接至其他文档（其他目录）：[TESTE_MD1](docs/test_md2.md)
- 连接至本文档其他部分：[基础语法](Markdown.md#有序列表)

**引用式链接**

- 外部链接： [ Baidu ][] 
- 链接至其他文档：[ TESTE_MD1 ][]
- 连接至本文档其他部分：[基础语法][]

### 图片

- 图片的Markdown语法

  `![]( URL "Title")`

- 插入网络图片

  `![](https://www.baidu.com/img/bd_logo1.png?where=super "Baidu")`

- 插入仓库内图片 (绝对路径)

  `![](E:\Programing\Git\my_test\images\markdown.png)`

- 插入仓库内图片 (相对路径)
`[](images/markdown.png )`
`![](images/markdown.png)`
`![](https://raw.githubusercontent.com/swwang109/My_test/master/images/markdown.png)`
- 图片的引用式链接 

  `![][Baidu_png]`

### 引用

- 单重引用：

>这是一个引文， 这是一个引文 

--- 出自《出处》

- 多重引用：

> > > 这是多重引用

### 代码块

- 块式代码

```bash
# echo "Hello World";
# ls -ltar
```

- 行内代码

这个代码中用来声明的变量`var a=10`。


### 水平分割线

- 方法一： ---

---

- 方法二：***

***

- 方法三：___

___

### HTML代码

Markdown格式化文档非常简单。很多人喜欢Markdown。

但如果文档格式超出了Markdown的处理效果，可以计入HTML。

比如：

<p align='center'> 居中</p>
### 表格

| 第一行 | 第一行 | 第一行 | 第一行 | 第一行 | 第一行 |
| :----: | :----: | :----: | :----: | :----: | :----: |
| 第二行 | 第二行 | 第二行 | 第二行 | 第二行 | 第二行 |
| 第三行 | 第三行 | 第三行 | 第三行 | 第三行 | 第三行 |
| 第四行 | 第四行 | 第四行 | 第四行 | 第四行 | 第四行 |

### GFM语法

- [x] Task List 1
- [ ] Task List 2

### emoji 表情符号

更多表情符号链接：https://www.webfx.com/tools/emoji-cheat-sheet/

`:smile_cat:`表示:smile_cat:
`:scream:`表示:scream:
`:kissing_heart:`表示 :kissing_heart:
`:yum:`表示 :yum:

`:snake:`表示：:snake:

### 混合强调模式

- **加粗**
- *斜体*
- ~~删除~~



- **~~加粗删除~~**
- ~~**删除加粗**~~
- *~~斜体删除~~*
- ~~*删除斜体*~~
- ***~~加粗删除斜体~~***
- *~~**斜体删除加粗**~~*



### 图片链接

`[Baidu](https://www.baidu.com)`

`![](https://www.baidu.com/img/bd_logo1.png?where=super)`



`[![](https://www.baidu.com/img/bd_logo1.png?where=super)](https://www.baidu.com)`

- 注意：对于图片链接，当鼠标放置于图片上方时，鼠标形状变为小手。



### 多级列表打断

-  item 1
  - item 2

1. item 1
   1. item 1
2. item 2
   1. item 2
3. item 3
4. item 4



<!--行注释-->

<!--引用时链接-->


[ Baidu ]: https://www.baidu.com
[ TESTE_MD1 ]: test_md1.md
[基础语法]: Markdown.md#有序列表
[Baidu_png]:https://www.baidu.com/img/bd_logo1.png?where=super