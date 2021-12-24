# 生物机器人–机器学习概述

> 原文:[https://www . geesforgeks . org/bio Tyson-机器学习-概述/](https://www.geeksforgeeks.org/biopython-machine-learning-overview/)

机器学习算法在生活的各个方面都很有用，可以准确地分析数据。生物信息学可以很容易地使用机器学习获得信息，没有机器学习，就很难分析巨大的遗传信息。

机器学习算法大致分为三个部分:监督学习、非监督学习和强化学习。本文只讨论基于监督学习的内容。

监督学习算法根据训练数据集迭代预测结果，并由主管(可以假设为教师)进行纠正。简而言之，数学表达式监督学习取决于方程 Y=f(X)，其中基于输入数据 X 预测输出变量 Y。

监督学习问题是使用两种方法中任何一种最合适的方法来解决的，这两种方法分为:分类(输出值在一个类别中)、回归(输出值是一个实数)。以下是一些模型，它们使用监督学习来获得生物信息学领域中出现的不同问题的结果:

**逻辑回归:**

确定因变量和一个或多个自变量之间关系的技术，其中因变量的类型是二进制变量。该模型用于使用加权和预测 K 类。通过这个模型，我们可以计算任何事件发生的概率。

Biopython 有 Bio。此类操作的物流配送模块。目前 K 值为 2，用于搜索 DNA。两类是 OP(同一人的相邻基因)和 NOP(不同人的相邻基因)。Biopython 中逻辑回归模型的一个例子是细菌中的基因调控(增加或减少基因产物的多种方式)。

**朴素贝叶斯:**

它是一个算法的集合，所有的算法都依赖于贝叶斯定理(它基于一个事件发生在它之前的事件的概率)。这符合新的观察和以前的数据。所有数据都是相互独立的。

生物。天真贝叶斯模块就是为了解决这个问题。由于朴素贝叶斯算法被认为非常适合推荐系统，基于朴素贝叶斯模型的基因推荐研究正在进行。

**马尔可夫模型&最大熵:**

隐马尔可夫模型(一种对序列数据建模的简单方法)用于基因组数据分析。对于基于片段或序列的基因区域鉴定，使用该模型。最大熵用于基因序列的生物学建模。

在生物信息学领域，这两个模型正在一起工作。生物。最大值，生物。马尔可夫模型和/或生物模型。马尔可夫模型模块用于支持这些模型提供的应用程序工作。

**k-最近邻:**

该模型首先存储不同数量的案例，然后根据符合模型的最近邻数据对数据进行分类。统计估计和模式识别用于此目的。

生物知识网络模块适用于这种类型的操作。基因对(细胞中存在的特定基因的两个拷贝)准确性检查是使用这种模型检索结果的问题的一个例子**。**