# cs229_learningNotes
使用python完成cs229的课后作业以及记录相应的学习笔记  
参考 https://github.com/fengdu78/Coursera-ML-AndrewNg-Notes  
## 主要内容
### 1. ex1-linearRegression  
分别通过批量梯度下降法和求解正规方程组来求解线性回归的参数。并绘制了在不同学习速率下，cost function的下降情况。
### 2. ex2-logisticRegression  
主要实现了带正则化项的逻辑回归（当然，先实现了不带正则化项的逻辑回归），通过批量梯度下降法求解其参数。同时进行Feature mapping,使得逻辑回归能够更好地处理线性不可分的情况。并绘制了在正则化参数lambda不同取值下，决策边界的变化情况（即过拟合与欠拟合）。
### 3. ex3-neuralNetwork  
整理了ex2实现的逻辑回归函数，采用one-vs-all的方法，使用逻辑回归对手写数字进行识别。并采用已经训练好的神经网络权重，实现了神经网络的前向传播，对手写数字进行识别。
## 补充材料
### 1. linearRegressionh
* locally weighted linear regression
推导并实现了局部加权线性回归，并选取不同的bandwidth进行拟合，可视化了不同bandwidth对局部加权线性回归的影响。
### 2. logisticRegression
* logistic regression
主要总结了逻辑回归的常用公式。介绍如何通过最大似然估计推出逻辑回归的cost function，推导了逻辑回归cost function的gradient和Hessian矩阵。介绍了牛顿法的原理，并且采用牛顿法求解逻辑回归的参数。