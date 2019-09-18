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

- 外部链接：[百度](https://www.baidu.com "Baidu")
- 链接至其他文档（当前目录）：[TESTE_MD1](test_md1.md)
- 链接至其他文档（其他目录）：[TESTE_MD1](docs/test_md2.md)
- 连接至本文档其他部分：[基础语法](Markdown.md#有序列表)

**引用式链接**

- 外部链接： [ Baidu ][] 

- 链接至其他文档：[ TESTE_MD1 ][]
- 连接至本文档其他部分：[基础语法][]

### 图片

- 图片的Markdown语法

  ![]( URL "Title")

- 插入网络图片

![](https://www.baidu.com/img/bd_logo1.png?where=super "Baidu")

- 菜如仓库内图片 (绝对路径)

![](E:\Programing\Git\my_test\images\markdown.png)

- 菜如仓库内图片 (相对路径)

![](images/markdown.png)

- 图片的引用式链接

![][Baidu_png]

### 引用

>这是一个引文， 这是一个引文 

​                                                                                                                                                                 --- 出自《出处》

> > > 这是多重引用

### 代码块

- 块式代码

```bash
# echo "Hello World";
# ls -ltar
```

- 行内代码

这个代码中用来声明的变量`var a=10`。







<!--引用时链接-->


[ Baidu ]: https://www.baidu.com
[ TESTE_MD1 ]: test_md1.md
[基础语法]: Markdown.md#有序列表
[Baidu_png]:https://www.baidu.com/img/bd_logo1.png?where=super

