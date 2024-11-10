---
layout: page
title: Research
permalink: /research/
---

Research highlights: 
- [AdaGrad - first adaptive gradient algorithm](https://dl.acm.org/doi/10.5555/1953048.2021068)  
  Adaptive gradient methods are the method of choice for training deep learning models. They started from the Adagrad algorithm and the theory of adaptive regularization, introduced in this paper. See [this blog post](https://www.minregret.com/2023/05/15/meta-optimization.html) for more information. 

- [Online Newton Step algorithm - first logarithmic regret for online convex optimization](https://link.springer.com/article/10.1007/s10994-007-5016-8)  
  This work explored the deep connection between mathematical optimization and online learning: it shows that the phenomenon of logarithmic regret, present in the work of [Tom Cover](https://en.wikipedia.org/wiki/Thomas_M._Cover) on [universal portfolio selection](https://en.wikipedia.org/wiki/Universal_portfolio_algorithm), is an artifact of curvature of the loss function, and can be explained using efficient methods from mathematical optimization. The paper gives an online variant of Newton's method, which has found numerous applications since.
 
- [First sublinear time algorithms for machine learning](https://arxiv.org/abs/1010.4408) and for [semi-definite programming](https://link.springer.com/article/10.1007/s10107-015-0932-z) 
  In this work we ask whether mathematical optimization problems can be approximately solved in less time than it takes to transmit a full representation? Although counter-intuitive, it is possible to use randomness to solve certain problems in sublinear time with high probability. 

- [Provable low-rank fast and simple SDP solver](https://link.springer.com/chapter/10.1007/978-3-540-78773-0_27)  
  Semidefinite programming is a powerful case of convex optimization which is widely used in applications. However, while polynomial time solvable, it is notoriously impractical. This paper gives a simple and practical algorithm for approximating semidefinite programs which is also particularly simple to analyze. 

- [First linearly converging projection-free (Frank-Wolfe) algorithm](https://arxiv.org/abs/1301.4666)  
  The Frank-Wolfe algorithm is the canonical example of a projection-free method: an optimization algorithm that replaces expensive operations known as "projections" by linear programming. In this paper we analyze the first non-trivial case of a projection-free algorithm that is linearly converging: its convergence rate is propertional to $\log \frac{1}{\epsilon}$, where $\epsilon$ is the required accuracy. Previous methods required poly($\frac{1}{\epsilon}$) iterations. 

- [Introduction of Online Nonstochastic Control Theory](https://sites.google.com/view/online-nonstochastic-control/home)  
  This line of work introduces a new methodology in control which is inherently online and based on regret minimization in repeated games. The framework gives rise to new algorithms that optimize disturbance based policies, as opposed to state-feedback policies. See this [book draft](https://arxiv.org/abs/2211.09619) for more details. 

- [Spectral Transformers](https://sites.google.com/view/gbrainprinceton/projects/spectral-transformers)  
  Most recently our group has proposed a new neural architecture based on ideas from online control, namely spectral filtering. The resulting architecture has provable length generalization guarantees and near-constant time inference. See this [website](https://sites.google.com/view/gbrainprinceton/projects/spectral-transformers) for more details. 

More details, recent research and blog posts are in [our group webpage](https://www.minregret.com).

