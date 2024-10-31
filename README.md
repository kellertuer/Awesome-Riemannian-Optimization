# A Handbook on Riemannian Optimization
This repo contains papers, books, tutorials and resources on Riemannian optimization. ⚡ This repo is currently under-developed. ⚡

   
<details open>
  <summary><h2><b> Contents </b></h2></summary>

  * [1. Books](#books)
  * [2. Papers](#papers)
    * [Acceleration](#acceleration)
    * [Geodesic Convex Optimization](#geodesic-convex-optimization)
    * [Stochastic Optimization](#stochastic-optimization)
    * [Scalable Riemannian Optimization](#scalable-riemannian-optimization)
      * [Stiefel (Orthogonal) Manifold](#stiefel-orthogonal-manifold)
      * [SPD Manifold](#spd-manifold)
      * [General Manifold](#general-manifold)
</details>

# 📘 Books

1. [Optimization Algorithms on Matrix Manifolds](https://press.princeton.edu/absil?srsltid=AfmBOorlfmgaTCzFeGcEDw9mxNrVvWMaKhY578kDlMOKlYY9D-G9ar3n) *Cambridge University Press*. 2023

2. [An introduction to Optimization on smooth manifolds](https://www.nicolasboumal.net/book/) *Princeton University Press*. 2008.

# 📜 Papers
 

## Acceleration
> Accelerated gradient methods and analysis on Riemannian manifolds. 

[Accelerated Gradient Dynamics on Riemannian Manifolds: Faster Rate and Trajectory Convergence](https://arxiv.org/pdf/2312.06366) *Arxiv*. 2023.

[Riemannian accelerated gradient methods via extrapolation](https://proceedings.mlr.press/v206/han23a/han23a.pdf)  *AISTATS*. 2023.

[Accelerated Riemannian Optimization: Handling Constraints with a Prox to Bound Geometric Penalties](https://proceedings.mlr.press/v195/martinez-rubio23a/martinez-rubio23a.pdf)  *COLT*. 2023.

[An Accelerated First-Order Method for Non-convex Optimization on Manifolds](https://link.springer.com/article/10.1007/s10208-022-09573-9) *Found. Comput. Math.* 2022.

[Understanding Riemannian acceleration via a proximal extragradient framework](https://proceedings.mlr.press/v178/jin22a/jin22a.pdf)  *COLT*. 2022.

[A variational formulation of accelerated optimization on Riemannian manifolds](https://epubs.siam.org/doi/abs/10.1137/21M1395648)  *SIAM J. Math. Data Sci.* 2022.

[Global Riemannian acceleration in hyperbolic and spherical spaces](https://proceedings.mlr.press/v167/martinez-rubio22a/martinez-rubio22a.pdf)  *ALT*. 2022.

[Accelerated Gradient Methods for Geodesically Convex Optimization: Tractable Algorithms and Convergence Analysis](https://proceedings.mlr.press/v162/kim22k/kim22k.pdf)  *ICML*. 2022.

[Accelerated optimization with orthogonality constraints](https://www.global-sci.org/intro/article_detail.html?journal=undefined&article_id=18372)  *J. Comp. Math.* 2021.

[Momentum Improves Optimization on Riemannian Manifolds](https://proceedings.mlr.press/v130/alimisis21a/alimisis21a.pdf)  *AISTATS*. 2021.

[From Nesterov’s Estimate Sequence to Riemannian Acceleration](https://proceedings.mlr.press/v125/ahn20a/ahn20a.pdf)  *COLT*. 2020. 

[A continuous-time perspective for modeling acceleration in Riemannian optimization](https://proceedings.mlr.press/v108/alimisis20a/alimisis20a.pdf) *AISTATS*. 2020.

[Accelerated First-order Methods for Geodesically Convex Optimization on Riemannian Manifolds](https://proceedings.neurips.cc/paper_files/paper/2017/file/6ef80bb237adf4b6f77d0700e1255907-Paper.pdf)  *NeurIPS*. 2017.

[Towards Riemannian accelerated gradient methods](https://arxiv.org/pdf/1806.02812) *Arxiv*. 2018. 

## Stochastic Optimization
> Methods for stochastic and finite-sum optimization on Riemannian manifolds


[Averaging Stochastic Gradient Descent on Riemannian Manifolds](https://proceedings.mlr.press/v75/tripuraneni18a/tripuraneni18a.pdf) *COLT*. 2018.

[Riemannian SVRG: Fast Stochastic Optimization on Riemannian Manifolds](https://proceedings.neurips.cc/paper_files/paper/2016/file/98e6f17209029f4ae6dc9d88ec8eac2c-Paper.pdf) *NeurIPS*. 2016.

[Stochastic gradient descent on Riemannian manifolds](https://ieeexplore.ieee.org/abstract/document/6487381) *IEEE Trans. Autom. Control.* 2013.


## Geodesic Convex Optimization
> Convergence theory, analysis and lower bound for geodesic convex optimization on Riemannian manifolds

[Curvature and complexity: Better lower bounds for geodesically convex optimization](https://proceedings.mlr.press/v195/criscitiello23a/criscitiello23a.pdf) *COLT*. 2023.

[Geodesic convex optimization: Differentiation on manifolds, geodesics, and convexity](https://arxiv.org/pdf/1806.06373) *Arxiv*. 2018.

[First-order Methods for Geodesically Convex Optimization](https://proceedings.mlr.press/v49/zhang16b.pdf) *COLT*. 2016.



## Scalable Riemannian Optimization
> Tackling expensive retraction for scaling Riemannian optimization.

###  Stiefel (Orthogonal) Manifold

[Solving Optimization Problems over the Stiefel Manifold by Smooth Exact Penalty Functions](https://global-sci.org/intro/article_detail.html?journal=undefined&article_id=23277)  *J. Comp. Math.* 2024.

[A Block Coordinate Descent Method for Nonsmooth Composite Optimization under Orthogonality Constraints](https://arxiv.org/pdf/2304.03641) *Arxiv*. 2023.

[Infeasible Deterministic, Stochastic, and Variance-Reduction Algorithms for Optimization under Orthogonality Constraints](https://arxiv.org/pdf/2303.16510) *Arxiv*. 2023.

[Fast and accurate optimization on the orthogonal manifold without retraction](https://proceedings.mlr.press/v151/ablin22a/ablin22a.pdf) *AISTATS*. 2022.

[A Class of Smooth Exact Penalty Function Methods for Optimization Problems with Orthogonality Constraints](https://www.tandfonline.com/doi/full/10.1080/10556788.2020.1852236) *Optim. Methods Softw.* 2020.

[Parallelizable algorithms for optimization problems with orthogonality constraints](https://epubs.siam.org/doi/10.1137/18M1221679) *SIAM J. Sci. Comput.* 2019.

[Coordinate-descent for learning orthogonal matrices through Givens rotations](https://proceedings.mlr.press/v32/shalit14.pdf) *ICML*. 2014.

###  SPD Manifold

[Low-complexity subspace-descent over symmetric positive definite manifold](https://arxiv.org/pdf/2305.02041) *Arxiv*. 2023.

### General Manifold

[Riemannian Coordinate Descent Algorithms on Matrix Manifolds](https://proceedings.mlr.press/v235/han24c.html) *ICML*. 2024.

[Coordinate Descent Without Coordinates: Tangent Subspace Descent on Riemannian Manifolds](https://pubsonline.informs.org/doi/full/10.1287/moor.2022.1253?af=R) *Math. Oper. Res.* 2022

[Dissolving Constraints for Riemannian Optimization](https://dl.acm.org/doi/abs/10.1287/moor.2023.1360) *Math. Oper. Res.* 2023.



