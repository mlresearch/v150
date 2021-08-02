---
title: A Recursive Markov Boundary-Based Approach to Causal Structure Learning
abstract: Constraint-based methods are one of the main approaches for causal structure
  learning that are particularly valued as they are asymptotically guaranteed to find
  a structure that is Markov equivalent to the causal graph of the system. On the
  other hand, they may require an exponentially large number of conditional independence
  (CI) tests in the number of variables of the system. In this paper, we propose a
  novel recursive constraint- based method for causal structure learning that significantly
  reduces the required number of CI tests compared to the existing literature. The
  proposed approach aims to use Markov boundary information to identify a specific
  variable that can be removed from the set of variables without affecting the statistical
  dependencies among the other variables. Having identified such a variable, we discover
  its neighborhood, remove that variable from the set of variables, and recursively
  learn the causal structure over the remaining variables. We further provide a lower
  bound on the number of CI tests required by any constraint-based method. Comparing
  this lower bound to our achievable bound demonstrates the efficiency of the proposed
  approach. Our experimental results show that the proposed algorithm outperforms
  state-of-the-art both on synthetic and real-world structures.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mokhtarian21a
month: 0
tex_title: A Recursive Markov Boundary-Based Approach to Causal Structure Learning
firstpage: 26
lastpage: 54
page: 26-54
order: 26
cycles: false
bibtex_author: Mokhtarian, Ehsan and Akbari, Sina and Ghassami, AmirEmad and Kiyavash,
  Negar
author:
- given: Ehsan
  family: Mokhtarian
- given: Sina
  family: Akbari
- given: AmirEmad
  family: Ghassami
- given: Negar
  family: Kiyavash
date: 2021-08-02
address:
container-title: Proceedings of The KDD'21 Workshop on Causal Discovery
volume: '150'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 8
  - 2
pdf: http://proceedings.mlr.press/v150/mokhtarian21a/mokhtarian21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
