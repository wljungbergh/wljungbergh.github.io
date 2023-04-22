---
layout: publication
title: Raw or Cooked? Object detection on RAW images
venue: Scandinavian Conference on Image Analysis (SCIA), 2023
extras: oral presentation
selected: 2
authors:
  - william:
    name: William Ljungbergh
    org: Zenseact, Linköping University
    scholar: RXEPFo0AAAAJ
  - joakim:
    name: Joakim Johnander
    org: Zenseact, Linköping University
    scholar: 5sUDSxQAAAAJ
  - christoffer:
    name: Christoffer Petersson
    org: Zenseact, Chalmers University of Technolgy
    scholar: SeRMUJwAAAAJ
  - michael:
    name: Michael Felsberg
    org: Linköping University
    scholar: lkWfR08AAAAJ
code:
arxiv: https://arxiv.org/abs/2301.08965
thumbnail: /assets/img/publications/raw-or-cooked.png
---

# Abstract
Images fed to a deep neural network have in general undergone several handcrafted image signal processing (ISP) operations, all of which have been optimized to produce visually pleasing images. In this work, we investigate the hypothesis that the intermediate representation of visually pleasing images is sub-optimal for downstream computer vision tasks compared to the RAW image representation. We suggest that the operations of the ISP instead should be optimized towards the end task, by learning the parameters of the operations jointly during training. We extend previous works on this topic and propose a new learnable operation that enables an object detector to achieve superior performance when compared to both previous works and traditional RGB images. In experiments on the open PASCALRAW dataset, we empirically confirm our hypothesis.
