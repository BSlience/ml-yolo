# 优化算法

几乎所有的机器学习的问题都可以归结为求损失函数的极值问题，即最优化问题。这里可能是最小化损失、最大化期望或者是在强化学习中的最大化回报。优化算法可以帮助我们更有效率的、找到性能尽可能好的的解。
总体来看，机器学习的核心目标是给出一个模型（一般是映射函数），然后定义对这个模型好坏的评价函数（目标函数），求解目标函数的极大值或者极小值，以确定模型的参数，从而得到我们想要的模型。在这三个关键步骤中，前两个是机器学习要研究的问题，建立数学模型。第三个问题是纯数学问题，即最优化方法，为本文所讲述的核心。

对于形式和特点各异的机器学习算法优化目标函数，我们找到了适合它们的各种求解算法。除了极少数问题可以用暴力搜索来得到最优解之外，我们将机器学习中使用的优化算法分成两种类型：
- 公式解(解析解)
- 数值优化

## 公式解
### 费马定理
### 拉格朗日乘数法
## 数值优化
### 随机梯度下降法
### 随机梯度下降法的加速
### 梯度验证
### 牛顿法
### 拟牛顿法

## L1正则化使得模型具有参数稀疏性的原理
