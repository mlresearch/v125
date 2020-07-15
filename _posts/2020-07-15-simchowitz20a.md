---
title: Improper Learning for Non-Stochastic Control
abstract: " We consider the problem of controlling a possibly unknown linear dynamical
  system with adversarial perturbations, adversarially chosen convex loss functions,
  and partially observed states, known as non-stochastic control. We  introduce a
  controller parametrization based on the denoised observations, and prove that applying
  online gradient descent to this parametrization yields a new controller which attains
  sublinear regret vs. a large class of closed-loop policies. In the fully-adversarial
  setting, our controller attains an optimal regret bound of $\\sqrt{T}$-when the
  system is known, and, when combined with an initial stage of least-squares estimation,
  $T^{2/3}$ when the system is unknown;  both yield the first sublinear regret for
  the partially observed setting. Our bounds are the first in the non-stochastic control
  setting that compete with \\emph{all} stabilizing linear dynamical controllers,
  not just state feedback. Moreover, in the presence of semi-adversarial noise containing
  both stochastic and adversarial components, our controller attains the optimal regret
  bounds of $\\mathrm{poly}(\\log T)$ when the system is known, and  $\\sqrt{T}$ when
  unknown. To our knowledge, this gives the first end-to-end $\\sqrt{T}$ regret for
  online Linear Quadratic Gaussian controller, and applies in a more general setting
  with adversarial losses and semi-adversarial noise."
layout: inproceedings
series: Proceedings of Machine Learning Research
id: simchowitz20a
month: 0
tex_title: Improper Learning for Non-Stochastic Control
firstpage: 3320
lastpage: 3436
page: 3320-3436
order: 3320
cycles: false
bibtex_author: Simchowitz, Max and Singh, Karan and Hazan, Elad
author:
- given: Max
  family: Simchowitz
- given: Karan
  family: Singh
- given: Elad
  family: Hazan
date: 2020-07-15
address: 
publisher: PMLR
container-title: Proceedings of Thirty Third Conference on Learning Theory
volume: '125'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 7
  - 15
pdf: http://proceedings.mlr.press/v125/simchowitz20a/simchowitz20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
