This is the official project page for the paper:  **Escaping Local Minima Provably in Non-convex Matrix Sensing: A Deterministic Framework via Simulated Lifting**

---
##  Links
* **arXiv:** [https://arxiv.org/abs/2602.05887](https://arxiv.org/abs/2602.05887)

## Abstract
Low-rank matrix sensing is a fundamental yet challenging nonconvex problem whose optimization landscape typically contains numerous spurious local minima, making it difficult for gradient-based optimizers to converge to the global optimum. Recent work has shown that over-parameterization via tensor lifting can convert such local minima into strict saddle points, an insight that also partially explains why massive scaling can improve generalization and performance in modern machine learning. Motivated by this observation, we propose a Simulated Oracle Direction (SOD) escape mechanism that simulates the landscape and escape direction of the over-parametrized space, without resorting to actually lifting the problem, since that would be computationally intractable. In essence, we designed a mathematical framework to project over-parametrized escape directions onto the original parameter space to guarantee a strict decrease of objective value from existing local minima. To the best of the our knowledge, this represents the first deterministic framework that could escape spurious local minima with guarantee, especially without using random perturbations or heuristic estimates. Numerical experiments demonstrate that our framework reliably escapes local minima and facilitates convergence to global optima, while incurring minimal computational cost when compared to explicit tensor over-parameterization. We believe this framework has non-trivial implications for nonconvex optimization beyond matrix sensing, by showcasing how simulated over-parameterization can be leveraged to tame challenging optimization landscapes.

## Authors
* **Tianqi Shen** 
* **Jinji Yang** 
* **Junze He** 
* **Kunhan Gao** 
* **Ziye Ma*** (Corresponding Author, City University of Hong Kong)

