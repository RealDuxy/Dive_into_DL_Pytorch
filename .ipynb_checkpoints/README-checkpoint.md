# Dive_into_DL_Pytorch

 动手学深度学习个人笔记

## 环境:

Pytorch 1.4.0

## 线性回归

利用torch.utils.data.Dataset构建Dataset和dataloader

利用numpy从0实现一个LinearRegression

利用pytorch的全连接层实现LinearRegression

torch.nn定义了许多神经网络层， data是数据处理的工具包，torch.nn.init是初始化模块方法, torch.nn.optim则提供了常见的优化器

## softmax回归
同样是从0实现和利用pytorch简洁实现。
在自己实现的时候softmaxregression存在数值不稳定的问题，因为softmax和regression是分开实现的。相比来说pytorch的函数更加稳定。
同时也回顾了一下pytorch建模的基本步骤



