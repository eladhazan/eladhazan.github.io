---
layout: page
title: Research
permalink: /research/
---

I develop algorithms and mathematical foundations for machine learning, optimization, and control, increasingly focusing on evaluating and aligning AI systems that may surpass their human supervisors.

## Current research

### AI evaluation and alignment

At [Princeton AI Alignment and Safety (AIAS)](https://alignment.dais.princeton.edu/), we use game theory, mechanism design, and online learning to study how to measure capabilities beyond human expertise and design incentives for reliable behavior and effective oversight.

- [Measuring Intelligence Beyond Human Scale (SepaRank)](https://arxiv.org/abs/2607.07040). SepaRank rewards models for proposing questions that distinguish other models, enabling relative evaluation without a fixed human-authored benchmark or a semantic judge.
- [AI Alignment via Incentives and Correction](https://arxiv.org/abs/2605.01643). We study how rewards shape solver–auditor interactions, adapting rewards with bandit methods from feedback on their joint behavior.

### Online learning and optimization

I develop computationally efficient algorithms that learn from sequential feedback and adapt to changing environments. Themes include regret minimization, adaptive optimization, and bandit feedback, connecting mathematical optimization to game theory, reinforcement learning, and learning system design. See [Introduction to Online Convex Optimization](https://sites.google.com/view/intro-oco/) for an overview and the foundational contributions below for selected results.

### Control and sequence modeling

We use online learning and spectral methods to learn and control dynamical systems and efficiently model long sequences, connecting provable prediction guarantees with memory compression and fast generation.

- [Universal Sequence Preconditioning](https://arxiv.org/abs/2502.06545) uses orthogonal polynomials to reduce the memory needed for prediction. Its [second-order extension](https://arxiv.org/abs/2605.08390) gives dimension-free, polylogarithmic regret for marginally stable linear systems under a spectral restriction.
- [SpectraLDS](https://arxiv.org/abs/2505.17868) distills spectral predictors into recurrent linear dynamical systems, with guarantees for symmetric dynamics and per-token inference costs that do not grow with sequence length.
- [Universal Learning of Nonlinear Dynamics](https://arxiv.org/abs/2508.11990) develops observation-based spectral filtering to predict nonlinear systems, with guarantees governed by a quantitative notion of learnability.
- [Spectral Transformers](https://sites.google.com/view/gbrainprinceton/projects/spectral-transformers) applies these ideas to neural sequence architectures; [FutureFill](https://arxiv.org/abs/2410.03766) enables fast generation from convolutional sequence models.

## Selected foundational contributions

- **[AdaGrad and adaptive regularization](https://jmlr.org/papers/v12/duchi11a.html)**  
  AdaGrad adapts updates to the geometry of past gradients. This work introduced an adaptive regularization framework with regret guarantees, helping establish adaptive gradient methods as a central tool in machine learning. See [this blog post](https://www.minregret.com/2023/05/15/meta-optimization.html) for background.

- **[Online Newton Step and logarithmic regret](https://link.springer.com/article/10.1007/s10994-007-5016-8)**  
  Connecting optimization curvature to fast online learning rates, Online Newton Step achieves logarithmic regret for exp-concave losses. It provides an efficient online counterpart of Newton's method and extends ideas from universal portfolio selection.

- **[Sublinear-time optimization for machine learning](https://arxiv.org/abs/1010.4408) and [semidefinite programming](https://link.springer.com/article/10.1007/s10107-015-0932-z)**  
  Using randomized sampling and online learning, these algorithms approximately solve problems including linear classification, minimum enclosing balls, and a class of semidefinite programs in less time than reading the full input.

- **[Sparse approximate solutions to semidefinite programs](https://link.springer.com/chapter/10.1007/978-3-540-78773-0_27)**  
  Addressing the computational cost of large-scale semidefinite optimization, this simple algorithm constructs low-rank approximate solutions with efficient representations.

- **[Linearly convergent projection-free optimization](https://arxiv.org/abs/1301.4666)**  
  Frank-Wolfe methods replace expensive projections with linear optimization. This method achieves linear convergence for smooth, strongly convex objectives over polyhedral sets with one linear optimization step per iteration. Iteration counts grow logarithmically with inverse target accuracy and also depend on the objective and domain geometry.

- **[Online nonstochastic control](https://sites.google.com/view/online-nonstochastic-control/home)**  
  Under adversarial disturbances and changing costs, this framework uses regret minimization to learn disturbance-based control policies, competing with a benchmark policy class in hindsight. See [Introduction to Online Control](https://arxiv.org/abs/2211.09619) for theory and algorithms.

See [Google Scholar](https://scholar.google.com/citations?user=LnhCGNMAAAAJ&hl=en&view_op=list_works&sortby=pubdate) for all publications and [our group webpage](https://www.minregret.com) for research updates and blog posts.
