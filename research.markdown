---
layout: page
title: Research
permalink: /research/
---

My research develops algorithms and mathematical foundations for machine learning, optimization, and control. A growing focus is how to evaluate and align AI systems whose capabilities may exceed those of their human supervisors.

## Current research

### AI evaluation and alignment

How can we measure capabilities beyond human expertise, and design incentives that support reliable behavior and effective oversight? We study these questions using game theory, mechanism design, and online learning, as part of [Princeton AI Alignment and Safety (AIAS)](https://alignment.dais.princeton.edu/).

- [Measuring Intelligence Beyond Human Scale (SepaRank)](https://arxiv.org/abs/2607.07040). SepaRank rewards models for proposing questions that distinguish other models, enabling relative evaluation without a fixed human-authored benchmark or a semantic judge.
- [AI Alignment via Incentives and Correction](https://arxiv.org/abs/2605.01643). We study how rewards shape the interaction between a solver and an auditor, and use bandit methods to adapt rewards from feedback about their joint behavior.

### Online learning and optimization

I develop algorithms that learn from sequential feedback and adapt to changing environments. Central themes include regret minimization, adaptive optimization, bandit feedback, and computationally efficient learning. These ideas connect mathematical optimization to game theory, reinforcement learning, and the design of learning systems. See [Introduction to Online Convex Optimization](https://sites.google.com/view/intro-oco/) for an overview, and the foundational contributions below for selected results.

### Control and sequence modeling

We use online learning and spectral methods to learn and control dynamical systems, and to build efficient models for long sequences. Recent work connects provable prediction guarantees with memory compression and fast generation.

- [Universal Sequence Preconditioning](https://arxiv.org/abs/2502.06545) uses orthogonal polynomials to reduce the memory needed for prediction. Its [second-order extension](https://arxiv.org/abs/2605.08390) gives dimension-free, polylogarithmic regret for marginally stable linear systems under a spectral restriction.
- [SpectraLDS](https://arxiv.org/abs/2505.17868) distills spectral predictors into recurrent linear dynamical systems, with guarantees for symmetric dynamics and per-token inference costs that do not grow with sequence length.
- [Universal Learning of Nonlinear Dynamics](https://arxiv.org/abs/2508.11990) develops observation-based spectral filtering for prediction of nonlinear systems, with guarantees governed by a quantitative notion of learnability.
- [Spectral Transformers](https://sites.google.com/view/gbrainprinceton/projects/spectral-transformers) brings these ideas into neural sequence architectures. Related work includes [FutureFill](https://arxiv.org/abs/2410.03766), an algorithm for fast generation from convolutional sequence models.

## Selected foundational contributions

- **[AdaGrad and adaptive regularization](https://jmlr.org/papers/v12/duchi11a.html)**  
  AdaGrad adapts its updates to the geometry of previously observed gradients. This work introduced a framework for adaptive regularization with regret guarantees and helped establish adaptive gradient methods as a central tool in machine learning. See [this blog post](https://www.minregret.com/2023/05/15/meta-optimization.html) for more background.

- **[Online Newton Step and logarithmic regret](https://link.springer.com/article/10.1007/s10994-007-5016-8)**  
  This work connects curvature in mathematical optimization to fast rates in online learning. Online Newton Step achieves logarithmic regret for exp-concave losses, providing an efficient online counterpart of Newton's method and extending ideas from universal portfolio selection.

- **[Sublinear-time optimization for machine learning](https://arxiv.org/abs/1010.4408) and [semidefinite programming](https://link.springer.com/article/10.1007/s10107-015-0932-z)**  
  Can an optimization problem be approximately solved in less time than it takes to read its full input? These works use randomized sampling and online learning to obtain sublinear-time algorithms for problems including linear classification, minimum enclosing balls, and a class of semidefinite optimization problems.

- **[Sparse approximate solutions to semidefinite programs](https://link.springer.com/chapter/10.1007/978-3-540-78773-0_27)**  
  Semidefinite optimization can be computationally demanding at large scales. This work gives a simple algorithm that constructs low-rank approximate solutions, making the representation of the solution itself more efficient.

- **[Linearly convergent projection-free optimization](https://arxiv.org/abs/1301.4666)**  
  Frank-Wolfe methods replace expensive projections with linear optimization. For smooth, strongly convex objectives over polyhedral sets, this work gives a method with linear convergence using one linear optimization step per iteration. The number of iterations grows logarithmically with the inverse target accuracy, with additional dependence on the objective and domain geometry.

- **[Online nonstochastic control](https://sites.google.com/view/online-nonstochastic-control/home)**  
  This framework applies regret minimization to control with adversarial disturbances and changing costs. Its methods learn disturbance-based policies and compete with a benchmark class of policies in hindsight. See [Introduction to Online Control](https://arxiv.org/abs/2211.09619) for the theory and algorithms.

For a full publication list, see [Google Scholar](https://scholar.google.com/citations?user=LnhCGNMAAAAJ&hl=en&view_op=list_works&sortby=pubdate). More research updates and blog posts are on [our group webpage](https://www.minregret.com).
