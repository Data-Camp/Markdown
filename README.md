# Markdown - 规范书写语言 

## Markdown语言简介

Markdown语法的目标是：成为一种适用于网络的书写语言。特性是「易读易书写」。Markdown是一种书写语言，是大家约定好的一种书写有结构的文本文件的方式。而HTML，pdf是发布的格式。一份使用 Markdown 格式撰写的文件应该可以直接以纯文本发布，并且看起来不会像是由许多标签或是格式指令所构成。

Markdown的设计目标是容易转化成HTML发布。所有在Markdown中的标记实际都被MD编辑器转化成HTML元素了。Markdown实质是简化易读易写的HTML书写语言，解释成HTML。MD和HTML是完全兼容的，可以在MD中加入HTML的标签。

Markdown有许多衍生版本，GitHub Flavored Markdown（GFM）是GitHub的一个MD语言扩展，对程序员来说很有爱。GFM部分的有爱特性：（1）代码高亮（2）任务列表（3）自动URL链接。

## 为什么要写解释性文本？

可读性。写报告是给别人（机器）看的，不能默认别人和你一样了解你的思路，所以你有义务引导别人更好的理解你的思路。另外，自己也可以忘记之前的思路，所以需要记录方便回忆。

可以看到，可读性是解释性文本的精髓，为了实现可读性，就要求我们保持文本的美观性和指代清晰。Markdown语言正是带着这样的初衷提出的，所以Jupyter在这里选用了Markdown来作为官方的解释性文本编辑语言。

Markdown通过如下设计来实现美观性和指代清晰：
美观性：表格的自动排版，空行缩进的自动控制，超链接的准确定义等，数学公式 (配合Latex)
指代清晰：标题的精准分类调用，加粗斜体的精准调用等

对比直接使用Word进行最合乎直觉的文本编辑，使用Markdown在早期有一个简单的学习曲线，主要是学习各种格式的引用方法。一旦入门，您将逐步感受到Markdown语言的准确性和美观性给文本编辑带来的便捷。

## Markdown语法范例：

标题
# 一级标题
1. 加粗/斜体
	**数据分析** 加粗；*机器学习* 斜体；*You **can** combine them*
2. 转义字符 (Backslash Escapes)
	\*Who am I\*
3. 有序标签/无序标签
   * 项目一
   1. 项目二
4. 超链接
[GitHub](http://github.com)
5. 图片
	![GitHub Logo](https://tse4-mm.cn.bing.net/th?id=OIP.3aMGy-X3Qd1B3ek2dsipDAHaHa&p=0&o=5&pid=1.1)
6. 代码块

  空四行(Tab)：

  print (1)

  GFM: 英文键盘数字1左边键
```python
print (2)
```
7. 引用
	> Machine Learning
	> Deep Learning

## 参考
1. [简书：献给写作者的 Markdown 新手指南](https://www.jianshu.com/p/q81RER)
2. [GitHub: Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
3. [Wikipedia：转义字符](https://zh.wikipedia.org/wiki/%E8%BD%AC%E4%B9%89%E5%AD%97%E7%AC%A6)
4. [StackEdit：最棒的在线Markdown编辑器](https://stackedit.io/app)
