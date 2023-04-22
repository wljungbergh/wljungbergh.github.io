---
layout: publication
title: "Next generation multitarget trackers: Random finite set methods vs transformer-based deep learning"
date: 2021-11-01 09:42:42 +07:00
venue: IEEE 24th International Conference on Information Fusion (FUSION), 2021
extras: best student paper
selected: 3
authors:
  - juliano:
    name: Juliano Pinto
    org: Chalmers University of Technology
    scholar: 4g7N7JUAAAAJ
  - georg:
    name: Georg Hess
    org: Zenseact, Chalmers University of Technology
    scholar: ZvUoV2EAAAAJ
  - william:
    name: William Ljungbergh
    org: Zenseact, Linköping University
    scholar: RXEPFo0AAAAJ
  - yuxuan:
    name: Yuxuan Xia
    org: Chalmers University of Technology
    scholar: ONkHTSwAAAAJ
  - lennart:
    name: Lennart Svensson
    org: Chalmers University of Technology
    scholar: AMM9vE4AAAAJ
  - henk:
    name: Henk Wymeersch
    org: Chalmers University of Technology
    scholar: a7mYN_EAAAAJ
arxiv: https://arxiv.org/abs/2104.00734
thumbnail: /assets/img/publications/next-gen-trackers.png
---

# Abstract
Multitarget Tracking (MTT) is the problem of tracking the states of an unknown number of objects using noisy measurements, with important applications to autonomous driving, surveillance, robotics, and others. In the model-based Bayesian setting, there are conjugate priors that enable us to express the multi-object posterior in closed form, which could theoretically provide Bayes-optimal estimates. However, the posterior involves a super-exponential growth of the number of hypotheses over time, forcing state-of-the-art methods to resort to approximations for remaining tractable, which can impact their performance in complex scenarios. Model-free methods based on deep-learning provide an attractive alternative, as they can, in principle, learn the optimal filter from data, but to the best of our knowledge were never compared to current state-of-the-art Bayesian filters, specially not in contexts where accurate models are available. In this paper, we propose a high-performing deep-learning method for MTT based on the Transformer architecture and compare it to two state-of-the-art Bayesian filters, in a setting where we assume the correct model is provided. Although this gives an edge to the model-based filters, it also allows us to generate unlimited training data. We show that the proposed model outperforms state-of-the-art Bayesian filters in complex scenarios, while matching their performance in simpler cases, which validates the applicability of deep-learning also in the model-based regime. The code for all our implementations is made available [here](https://github.com/JulianoLagana/MT3).