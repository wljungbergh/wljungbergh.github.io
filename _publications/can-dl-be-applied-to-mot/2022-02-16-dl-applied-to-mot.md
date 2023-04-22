---
layout: publication
title: "Can deep learning be applied to model-based multi-object tracking?"
date: 2022-02-16 09:42:42 +07:00
venue: arXiv
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
  - henk:
    name: Henk Wymeersch
    org: Chalmers University of Technology
    scholar: a7mYN_EAAAAJ
  - lennart:
    name: Lennart Svensson
    org: Chalmers University of Technology
    scholar: AMM9vE4AAAAJ
arxiv: https://arxiv.org/abs/2202.07909
thumbnail: /assets/img/publications/dl-applied-mot.png
---

# Abstract
Multi-object tracking (MOT) is the problem of tracking the state of an unknown and time-varying number of objects using noisy measurements, with important applications such as autonomous driving, tracking animal behavior, defense systems, and others. In recent years, deep learning (DL) has been increasingly used in MOT for improving tracking performance, but mostly in settings where the measurements are high-dimensional and there are no available models of the measurement likelihood and the object dynamics. The model-based setting instead has not attracted as much attention, and it is still unclear if DL methods can outperform traditional model-based Bayesian methods, which are the state of the art (SOTA) in this context. In this paper, we propose a Transformer-based DL tracker and evaluate its performance in the model-based setting, comparing it to SOTA model-based Bayesian methods in a variety of different tasks. Our results show that the proposed DL method can match the performance of the model-based methods in simple tasks, while outperforming them when the task gets more complicated, either due to an increase in the data association complexity, or to stronger nonlinearities of the models of the environment.