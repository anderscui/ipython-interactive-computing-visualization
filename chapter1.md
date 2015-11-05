# 第一章 快速入门

## 安装

**注意**：[IPython](http://ipython.org/)的结构已经在《Learning IPython》之后发生了很大的变化（从IPython4.0开始）。

一般来说，安装IPython有10种方式，1种是不需要折腾的，1种是需要折腾的。对于不愿意折腾的同学来说，可选择使用一些all-in-one发布包来安装，比较推荐[Anaconda](http://continuum.io/downloads)。对于那些想折腾的人来说，我就不说什么了，自己折腾去吧。

【回来】发布包的问题是，我们拿到的不仅是需要的库，还有另一些不需要的，对于对Python较熟悉的同学来说，按需安装会更合适。这里仅列出若干重要的库，至于具体安装步骤，不再赘述：

* IPython
* NumPy：提供的多维数组可进行高性能和向量运算
* SciPy：高级数值算法
* Matplotlib：绘图和可视化
* Matplotlib-basemap：a mapping toolbox for Matplotlib
* Pandas：处理表格化（tabular）数据
* NetworkX：处理图表
* Python Imaging Library（PIL）：图像处理算法
* PySide/PyQt：GUI库
* Cython：在Python中使用C

除了从源代码安装，还可以考虑使用安装包。有些安装文件可从PyPI获取官方版本，有时需要下载非官方安装包，此时：
* Windows下建议看看由[Christoph Gohlke维护的页面](www.lfd.uci.edu/~gohlke/pythonlibs/)
* OS X：MacPorts和Homebrew
* Linux：略

最后，不管你是否喜欢折腾，了解pip的用法都是必须的。

## IPython的10个重要特性

### 1. 作为Python控制台使用

在terminal或console中运行ipython即可。IPython内置了数十个命令，可以大大提高生产力。比如当你不确定super函数的用法时，可使用```super?```来查看它的帮助文档。

### 2. 作为系统shell使用

IPython不仅可作为Python控制台的替代物，更可作为系统shell的替代物。所有系统shell中的命令都可在IPython中使用，如pwd、ls、cd等。

IPython亦提供了一系列的**魔法方法**，完整的魔法方法列表可通过%lsmagic命令查看。魔法方法都有%前缀，不过在automagic开关打开的情况下，多数时候%是可省略的，只要不与其它python变量冲突。

### 3. 使用命令历史

IPython命令行会保存一个命令历史列表，而且该历史可以是跨越会话（session）的。也就是说，我们可以访问上次会话中使用的命令列表。

最基本的使用方法，使用上下方向键前后遍历输入历史。如果已输入几个字符，此时的

## 小结
