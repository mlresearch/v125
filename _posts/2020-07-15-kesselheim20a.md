---
title: Online Learning with Vector Costs and Bandits with Knapsacks
abstract: " We introduce online learning with vector costs ($OLVC_p$)  where in each
  time step $t \\in \\{1,\\ldots, T\\}$, we need to play an action $i \\in \\{1,\\ldots,n\\}$
  that incurs an unknown vector cost in $[0,1]^d$. The goal of the online algorithm
  is to minimize the $\\ell_p$ norm of the sum of its cost vectors. This captures
  the classical online learning setting for $d=1$, and is interesting for general
  $d$ because of applications like online scheduling where we want to balance the
  load between different machines (dimensions). We study $OLVC_p$ in both stochastic
  and adversarial arrival settings, and give a general procedure to reduce the  problem
  from $d$ dimensions to  a single dimension. This allows us to use classical online
  learning algorithms in both full and bandit feedback models to obtain (near) optimal
  results. In particular, we obtain a single algorithm   (up to the choice of learning
  rate) that gives sublinear regret for stochastic arrivals and a tight $O(\\min\\{p,
  \\log d\\})$ competitive ratio for adversarial arrivals. The $OLVC_p$ problem also
  occurs as a natural subproblem when trying to solve the popular Bandits with Knapsacks
  (BWK) problem. This connection allows us to use our $OLVC_p$ techniques to obtain
  (near) optimal results for BWK in both stochastic and adversarial settings. In particular,
  we obtain a tight $O(\\log d \\cdot \\log T)$ competitive ratio algorithm for adversarial
  BWK, which improves over the $O(d \\cdot \\log T)$ competitive ratio algorithm  of
  Immorlica et al. (2019)."
layout: inproceedings
series: Proceedings of Machine Learning Research
id: kesselheim20a
month: 0
tex_title: Online Learning with Vector Costs and Bandits with Knapsacks
firstpage: 2286
lastpage: 2305
page: 2286-2305
order: 2286
cycles: false
bibtex_author: Kesselheim, Thomas and Singla, Sahil
author:
- given: Thomas
  family: Kesselheim
- given: Sahil
  family: Singla
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
pdf: http://proceedings.mlr.press/v125/kesselheim20a/kesselheim20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
