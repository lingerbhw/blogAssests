---
title: 关于导数的定义与简单应用
subtitle: 导数学习1
description: 数学人的探索
tags: 数学
categories: 数学
abbrlink: 7ed0dfc2
date: 2024-10-18 22:33:34
businesscard: true
cover: 'https://i.33xp.cn/__imgapi.cn__/__imgapi.cn__5ca56f398fe30.jpg'
---
### 一般定义

在维基百科中，我们可以得到导数的一般定义。

设函数$y=f(x)$在点$x_0$的某个邻域内有定义，当自变量$x$在$x_0 $处取得增量$\Delta x$（点$x_0+\Delta x$仍在该邻域内）时，相应地函数$y$取得增量$\Delta y=f(x_0+\Delta x)-f(x_0)$如果$\Delta y$与$\Delta x$之比当$\Delta x\to 0$时的极限存在，则称函数$y=f(x)$在点$x_0$处可导，并称这个极限为函数$y=f(x)$在点$x_0$处的导数，记为$f'(x_0)$，即

$$
f'(x)=\lim\limits_{x \rightarrow 0} \frac{\Delta y}{\Delta x}
$$

即

$$
f'(x)=\lim\limits_{x \rightarrow 0} \frac{f(x_0+\Delta x)-f(x)}{\Delta x}
$$

这也是在高中范围内的基本定义。

### 几何意义

设$P_0$为曲线上的一个定点，$ P$为曲线上的一个动点。当$P$沿曲线逐渐趋向于点$P_0$时，并且割线$P$$P_0$的极限位置$P_0$$T$存在，则称$P_0T$为曲线在$P_0$处的切线

此时切线的斜率为

$tanx=\lim\limits_{x \rightarrow 0} \frac{f(x_0+\Delta x)-f(x)}{\Delta x} $

因此，导数的几何意义为该点处切线的斜率

### 简单应用

例1: 求函数$f(x)=2x+\frac{8}{x} $的极值

解：    求导得$f'(x)=2-\frac{8}{x^2} $

当$f'(x)$为0时    解得$x=\pm 2$

$\therefore$在$x>2$或$x<-2$时$f'(x)>0$

在$-2<x<2$时$f'(x)<0$

$\therefore f(x)$在$x \in (-\infty,-2)$和$x \in (2,+\infty)$单调递增

$f(x)$在$x \in (-2,2)$单调递减

 $\therefore x=-2$时取得极大值-8，$x=2$时取得极小值8
