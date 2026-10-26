---
layout: page
title: Research
permalink: /research/
---

I develop algorithms and mathematical foundations for machine learning, optimization, and control. I co-developed [AdaGrad](https://jmlr.org/papers/v12/duchi11a.html), which helped establish adaptive gradient methods in machine learning. A growing focus is evaluating and aligning AI systems that may surpass their human supervisors.

## AI evaluation and alignment

At [Princeton AI Alignment and Safety (AIAS)](https://alignment.dais.princeton.edu/), we use game theory, mechanism design, and online learning to evaluate capabilities beyond human expertise and design incentives for reliable behavior.

- [Measuring Intelligence Beyond Human Scale (SepaRank)](https://arxiv.org/abs/2607.07040): model-generated challenges for relative evaluation without human-authored benchmarks or a semantic judge.
- [AI Alignment via Incentives and Correction](https://arxiv.org/abs/2605.01643): adapting rewards for solver–auditor interactions using bandit feedback.

## Online learning and optimization

I study efficient algorithms for sequential decision-making, focusing on regret minimization, adaptive optimization, and bandit feedback, with connections to game theory and reinforcement learning.

Book: [Introduction to Online Convex Optimization](https://sites.google.com/view/intro-oco/).

## Control and sequence modeling

We develop [online nonstochastic control](https://sites.google.com/view/online-nonstochastic-control/home) and spectral methods for learning dynamical systems and modeling long sequences.

- [Universal Sequence Preconditioning](https://arxiv.org/abs/2502.06545): memory-efficient prediction using orthogonal polynomials, with a [second-order extension](https://arxiv.org/abs/2605.08390).
- [Universal Learning of Nonlinear Dynamics](https://arxiv.org/abs/2508.11990): provable prediction through observation-based spectral filtering.
- [Spectral Transformers](https://sites.google.com/view/gbrainprinceton/projects/spectral-transformers): neural sequence architectures; [FutureFill](https://arxiv.org/abs/2410.03766): fast generation for convolutional sequence models.

## Selected contributions

- **[AdaGrad and adaptive regularization](https://jmlr.org/papers/v12/duchi11a.html)**  
  Adapting updates to past gradient geometry, with regret guarantees ([background](https://www.minregret.com/2023/05/15/meta-optimization.html)).

- **[Online Newton Step and logarithmic regret](https://link.springer.com/article/10.1007/s10994-007-5016-8)**  
  An efficient online Newton method achieving logarithmic regret for exp-concave losses.

- **[Sublinear-time optimization for machine learning](https://arxiv.org/abs/1010.4408) and [semidefinite programming](https://link.springer.com/article/10.1007/s10107-015-0932-z)**  
  Approximate solutions to classification, minimum enclosing ball, and certain semidefinite problems in less time than reading the full input.

- **[Sparse approximate solutions to semidefinite programs](https://link.springer.com/chapter/10.1007/978-3-540-78773-0_27)**  
  A simple algorithm constructing low-rank approximate solutions to large semidefinite programs.

- **[Linearly convergent projection-free optimization](https://arxiv.org/abs/1301.4666)**  
  Linear convergence for smooth, strongly convex objectives over polyhedral sets, using one linear optimization step per iteration.

- **[Online nonstochastic control](https://sites.google.com/view/online-nonstochastic-control/home)**  
  Learning disturbance-based policies under adversarial disturbances and changing costs, with regret guarantees against a benchmark policy class ([book](https://arxiv.org/abs/2211.09619)).

See [Google Scholar](https://scholar.google.com/citations?user=LnhCGNMAAAAJ&hl=en&view_op=list_works&sortby=pubdate) for all publications and [our group webpage](https://www.minregret.com) for research updates.
