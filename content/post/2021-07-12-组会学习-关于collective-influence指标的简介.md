---
title: 【组会学习】关于collective influence指标的简介
author: xyq
date: '2021-07-12'
slug: 组会学习-关于collective-influence指标的简介
categories:
  - 组会分享
tags:
  - ibids
disable_comments: yes
---

晓斌的论文分享

> Luo, S., Morone, F., Sarraute, C., Travizano, M., & Makse, H. A. (2017). Inferring personal economic status from social network location. Nature Communications, 8(1), 1-7.

讲了一个有趣的指标：**collective influence (CI) metric**

该指标，来自于2015年Morone等人在Nature上发表的工作
> Morone, F., & Makse, H. A. (2015). Influence maximization in complex networks through optimal percolation. Nature, 524(7563), 65-68.

怎么计算的：

> CI is the degree-minus-one of the central node times the sum of the degree-minus-one of the nodes at the boundary of the sphere of influence.

`$$CI=(k_i-1)\sum_{j\in\partial Ball(i,l)}(k_j -1)$$`

the boundary of the sphere of influencede的意思就是，比如选个3度有以内的所有节点来计算，或者选个5度以内的所有节点来计算

示例：

![Patterns of network influence mimic patterns of income inequality](/img/collective_influence_metric.png)

我的一个疑问：尽管这个指标能反应节点对于信息的控制，说明一些度小的节点可能会有很大的影响力。比如总统直接连接的好友不多，但通过好友的好友，总统的影响力就很广。**但是这个指标和betweenness centrality有什么差别呢？**

---

我的分享：

三个关于:
*Batchnormalization、data augmentation和迁移学习*
的简单示例

以及一篇论文
> Wang, J., Gu, Q., Wu, J., Liu, G., & Xiong, Z. (2016, December). Traffic speed prediction and congestion source exploration: A deep learning method. In 2016 IEEE 16th international conference on data mining (ICDM) (pp. 499-508). IEEE.


