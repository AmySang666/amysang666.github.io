---
layout: post
title:  "概率论复习与测度论"
date:  2023-01-18 08:14:54
categories: 概率论 复习 概率测度
tags: 概率论 复习 概率测度
excerpt: 概率论复习与测度论。
mathjax: true
---

# 概率论的基本概念

样本空间，sample space，记作$ \Omega $：基本事件的集合。

$\sigma $代数，$\sigma $ -field/algebra, 记作$ \mathcal{F} $，有如下定义。

定义： 若$ \mathcal{F} $是$ \Omega $的子集簇，如果满足
$$ \left\{\begin{matrix}
\Omega \in  \mathcal{F} \\ 
A \in \mathcal{F} \Rightarrow A^c \in \mathcal{F} \\
A_i \in \mathcal{F} \Rightarrow \bigcup_{i=1}^{\infty } A_i  \in \mathcal{F}

\end{matrix}\right.
$$则称\mathcal{F}为 $\sigma $代数

$( \Omega,\mathcal{F},P )$