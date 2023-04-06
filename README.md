# Attention Mechanism
This repository contains the detailed introduction and implementation of attention mechanisms.

## 1 注意力机制的直观理解

&emsp;&emsp;如下图所示，当过载信息映入眼帘时，大脑会把注意力放在主要的信息上，这就是大脑的注意力机制。同样，当读一句话时，大脑也会首先记住重要的词汇，这样就可以把注意力机制应用到自然语言处理任务中，于是相关学者通过借助人脑处理信息过载的方式，提出了Attention机制。

<center><img src="https://github.com/li-lindong/Attention-Mechanism/blob/main/%E5%9B%BE%E7%89%87/%E6%B3%A8%E6%84%8F%E5%8A%9B%E6%9C%BA%E5%88%B6%E5%8F%AF%E8%A7%86%E5%8C%96%E5%9B%BE.png" width=30%></center>

## 2 注意力机制的抽象模型

&emsp;&emsp;注意力机制的抽象模型如下图所示，该机制本质上是从大量信息（Value-1, Value-2,..., Value-N）中筛选出少量重要信息，并用于后续操作或任务。大体过程是，通过Query和Key-1、Key-2等计算注意力权重，然后利用权重对信息（Value-1, Value-2,..., Value-N）加权求和即得到注意力机制的输出。其中，权重代表了对应信息的重要性。

<center><img src="https://github.com/li-lindong/Attention-Mechanism/blob/main/%E5%9B%BE%E7%89%87/%E6%B3%A8%E6%84%8F%E5%8A%9B%E6%9C%BA%E5%88%B6%E7%9A%84%E6%8A%BD%E8%B1%A1%E6%A8%A1%E5%9E%8B.png" width=60%></center>

&emsp;&emsp;具体计算过程可抽象为三个步骤：

## Self-Attention Mechanism

## Reference
https://blog.csdn.net/dagouxiaohui/article/details/125966378

https://blog.csdn.net/qq_44543774/article/details/121078454?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-121078454-blog-125966378.pc_relevant_3mothn_strategy_recovery&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-121078454-blog-125966378.pc_relevant_3mothn_strategy_recovery&utm_relevant_index=1

https://zhuanlan.zhihu.com/p/265108616

https://zhuanlan.zhihu.com/p/349436540

https://zhuanlan.zhihu.com/p/94077451
