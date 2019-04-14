# 学习线性代数用于机器学习的 5 个理由

> 原文： [https://machinelearningmastery.com/why-learn-linear-algebra-for-machine-learning/](https://machinelearningmastery.com/why-learn-linear-algebra-for-machine-learning/)

### 为什么学习线性代数进行机器学习？

线性代数是一个数学领域，可以称为数学数学。

无可否认，它是机器学习领域的一个支柱，许多人建议它在开始机器学习之前作为学习的先决条件。这是一种误导性建议，因为线性代数一旦具有应用机器学习过程的上下文就可以对实践者更有意义。

在这篇文章中，您将发现为什么机器学习从业者应该学习线性代数来提高他们作为从业者的技能和能力。

阅读这篇文章后，你会知道：

*   不是每个人都应该学习线性代数，这取决于你在学习机器学习的过程中所处的位置。
*   5 个理由为什么中间机器学习从业者需要更深入地理解线性代数。
*   一旦你有动力开始进入线性代数领域的旅程，从哪里开始。

让我们开始吧。

![5 Reasons to Learn Linear Algebra for Machine Learning](img/dfe9ae7ed77705b50b06313d13690368.jpg)

学习机器学习线性代数的 5 个理由
照片来自 [a.poll_o](https://www.flickr.com/photos/105307156@N06/38927948862/) ，保留一些权利。

## 不学习线性代数的原因

在我们解释你应该学习线性代数的原因之前，让我们先看一下你不应该学习的原因。

我认为如果你刚开始应用机器学习，你不应该学习线性代数。

*   **不需要**。为了使用机器学习作为解决问题的工具，不需要了解一些机器学习算法的抽象操作。
*   **这很慢**。在机器学习之前花费数月到数年来研究整个相关领域将延迟实现您能够通过预测建模问题的目标。
*   **这是一个巨大的领域**。并非所有线性代数都与理论机器学习相关，更不用说应用机器学习了。

我建议采用广度优先的方法开始应用机器学习。

我称这种方法是结果优先的方法。在这里，您首先要学习和实践使用工具（例如 scikit-learn 和 Python 中的 Pandas）进行端到端预测建模问题（例如，如何获得结果）的步骤。

然后，此过程提供了逐步深化您的知识的框架和上下文，例如算法如何工作以及最终构成它们的数学。

在您知道如何解决预测建模问题之后，让我们看看为什么您应该加深对线性代数的理解。

## 1.你需要学习线性代数表示法

您需要能够读取和写入向量和矩阵表示法。

使用向量和矩阵表示法在书籍，论文和网站上描述算法。

线性代数是数据的数学，符号允许您使用特定的运算符精确地描述数据操作。

您需要能够读写这种表示法。这项技能将允许您：

*   阅读教科书中现有算法的描述。
*   解释并实施研究论文中新方法的描述。
*   向其他从业者简要描述您自己的方法。

此外，Python 等编程语言提供了直接实现线性代数表示法的有效方法。

理解符号以及如何在您的语言或库中实现它将允许更短且可能更有效地实现机器学习算法。

## 你需要学习线性代数算术

与线性代数的符号相结合是执行的算术运算。

您需要知道如何添加，减去和乘以标量，向量和矩阵。

线性代数领域的新手面临的挑战是诸如矩阵乘法和张量乘法之类的操作，这些操作并未实现为这些结构的元素的直接乘法，并且乍一看似乎不直观。

同样，大多数（如果不是全部）这些操作都是通过现代线性代数库中的 API 调用有效实现并提供的。

作为能够有效读写矩阵表示法的一部分，需要理解如何实现向量和矩阵运算。

## 你需要学习线性代数的统计学

您必须学习线性代数才能学习统计数据。特别是多变量统计。

统计和数据分析是支持机器学习的数学的另一个支柱领域。他们主要关注描述和理解数据。作为数据的数学，线性代数已将其指纹留在许多相关的数学领域，包括统计学。

为了能够阅读和解释统计数据，您必须学习线性代数的符号和操作。

现代统计学使用线性代数的符号和工具来描述统计方法的工具和技术。从用于数据均值和方差的向量，到描述多个高斯变量之间的关系的协方差矩阵。

两个领域之间的一些合作的结果也是主要机器学习方法，例如主成分分析，或简称 PCA，用于数据减少。

## 4.你需要学习矩阵分解

基于符号和算术的基础是矩阵分解的思想，也称为矩阵分解。

您需要知道如何对矩阵进行分解以及它意味着什么。

矩阵分解是线性代数中的关键工具，广泛用作线性代数（如矩阵逆）和机器学习（最小二乘）中许多更复杂运算的元素。

此外，还有一系列不同的矩阵分解方法，每种方法都有不同的优势和能力，其中一些可以被认为是“机器学习”方法，例如奇异值分解，或简称 SVD，用于数据缩减。

为了阅读和解释高阶矩阵运算，您必须理解矩阵分解。

## 5.你需要学习线性最小二乘法

您需要知道如何使用矩阵分解来求解线性最小二乘法。

线性代数最初是为解决线性方程组而开发的。这些是存在比未知变量（例如系数）更多的方程的情况。因此，它们在算术上难以解决，因为没有单一解决方案，因为没有线或平面可以适应数据而没有一些错误。

这种类型的问题可以被定义为平方误差的最小化，称为最小二乘，并且可以用线性代数的语言重新编程，称为线性最小二乘。

线性最小二乘问题可以使用诸如矩阵分解之类的矩阵运算在计算机上有效地解决。

最小二乘法因其在线性回归模型解决方案中的作用而闻名，但在一系列机器学习算法中也发挥着更广泛的作用。

为了理解和解释这些算法，您必须了解如何使用矩阵分解方法来解决最小二乘问题。

## 还有一个原因

如果我能再给出一个理由，那就是：因为它很有趣。

认真。

学习线性代数，至少我用实际例子和可执行代码教它的方式，很有趣。一旦您可以看到操作如何处理实际数据，就很难避免对方法产生强烈的直觉。

您是否有更多理由说明为什么对于中级机器学习从业者来说学习线性代数至关重要？

如果以下评论，请告诉我。

## 在线性代数中从哪里开始？

也许现在你有动力进入线性代数领域。

我会提醒你不要直接使用线性代数。这是一个很大的领域，并非所有这些都与您作为机器学习从业者相关或适用，至少在一开始就不是。

我建议采用交错方法，从以下与机器学习相关的线性代数区域开始。

*   向量和矩阵表示法。
*   向量和矩阵算法。
*   多变量统计。
*   矩阵分解。
*   线性最小二乘法。

我认为这是一个有效的机器学习从业者所需的最小线性代数。

您可以更深入地了解操作是如何得出的，这反过来可能加深您在应用机器学习的某些方面的理解和有效性，但它可能超出了大多数从业者的收益递减点，至少就当天而言普通机器学习从业者的日常活动。

## 摘要

在这篇文章中，您发现了为什么作为机器学习从业者，您应该加深对线性代数的理解。

具体来说，你学到了：

*   不是每个人都应该学习线性代数，这取决于你在学习机器学习的过程中所处的位置。
*   5 个理由为什么中间机器学习从业者需要更深入地理解线性代数。
*   一旦你有动力开始进入线性代数领域的旅程，从哪里开始。

你有任何问题吗？
在下面的评论中提出您的问题，我会尽力回答。