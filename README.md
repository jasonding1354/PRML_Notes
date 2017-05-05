# PRML_Notes

##项目概要
该项目是关于机器学习经典书籍《Pattern Recognition and Machine Learning》的学习笔记，用python实现了书籍中的大部分实例，希望帮助大家更好的理解抽象的概念和复杂的公式。

##内容目录

### 1. 概率分布(Probability Distribution)
* [1.1 Binary_Variables](http://nbviewer.ipython.org/github/jasonding1354/PRML_Notes/blob/master/1.PROBABILITY_DISTRIBUTIONS/1.1%20Binary_Variables.ipynb)——二元变量、伯努利分布、二项式分布、Beta分布作为二项式分布的先验概率分布
* [1.2 Multinomial_Variables](http://nbviewer.ipython.org/github/jasonding1354/PRML_Notes/blob/master/1.PROBABILITY_DISTRIBUTIONS/1.2%20Multinomial_Variables.ipynb)——多项式分布、狄利克雷分布
* [1.3 The_Gaussian_Distribution](http://nbviewer.ipython.org/github/jasonding1354/PRML_Notes/blob/master/1.PROBABILITY_DISTRIBUTIONS/1.3%20The_Gaussian_Distribution.ipynb)——高斯分布、高斯分布的几何解释


### p1. Figaro库的介绍
Figaro是一个构造概率性模型的Scala库。在Figaro中，该模型由任意数量的数据结构（称作“元素”）组成。每个元素代表在您的情境中可取任意数量值的一个变量。这些数据结构用Scala实现，您可以用这些数据结构编写Scala程序创建模型。可以通过关于元素值的信息提供证据，也可以指定希望在查询中了解的元素。至于推理算法，您可以选择一个Figaro内建推理算法并应用到模型上，根据证据回答您的查询。推理算法以Scala实现，其调用就是一个Scala函数调用。推理结果是查询元素不同值的概率。

![](http://write.epubit.com.cn/api/storage/getbykey/screenshow?key=170396812d6f8339a94a)
* [Figaro的hello world程序](http://nbviewer.jupyter.org/github/jasonding1354/PRML_Notes/blob/master/p1.Figaro_intro/1.figaro_helloworld.ipynb)
* [Figaro的基本元素介绍](http://nbviewer.jupyter.org/github/jasonding1354/PRML_Notes/blob/master/p1.Figaro_intro/2.basic_element.ipynb) 介绍使用Figaro的元素定义常见的概率分布

### p2. 使用Figaro编写概率程序
* [使用贝叶斯网络模型进行打印机故障原因的诊断](http://nbviewer.jupyter.org/github/jasonding1354/PRML_Notes/blob/master/p2.Figaro_dependent_model/1.use_bayesian_net_to_diagnose_printer.ipynb)
* []()
