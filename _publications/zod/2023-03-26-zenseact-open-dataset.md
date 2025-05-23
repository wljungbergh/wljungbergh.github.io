---
title: "Zenseact Open Dataset: A large-scale and diverse multimodal dataset for autonomous driving"
layout: publication
permalink: /publications/zod/
date: 2023-03-09 09:45:47 +07:00
venue: International Conference on Computer Vision (ICCV), 2023
authors:
  - mina:
    name: Mina Alibeigi
    org: Zenseact
    scholar: gJA_rJYAAAAJ
  - william:
    name: William Ljungbergh
    org: Zenseact, Linköping University
    scholar: RXEPFo0AAAAJ
  - adam t:
    name: Adam Tonderski
    org: Zenseact, Lund University
    scholar: 2R5ZLp0AAAAJ
  - georg:
    name: Georg Hess
    org: Zenseact, Chalmers University of Technology
    scholar: ZvUoV2EAAAAJ
  - adam l:
    name: Adam Lilja
    org: Zenseact, Chalmers University of Technology
    scholar: zYn4o0AAAAAJ
  - carl:
    name: Carl Lindström
    org: Zenseact, Chalmers University of Technology
    scholar: ufjSqs0AAAAJ
  - junsheng:
    name: Junsheng Fu
    org: Zenseact
    scholar: z3lud1UAAAAJ
  - daria:
    name: Daria Motorniuk
    org: Zenseact
    scholar: RT0Mw8wAAAAJ
  - jenny:
    name: Jenny Widahl
    org: Zenseact
  - christoffer:
    name: Christoffer Petersson
    org: Zenseact, Chalmers University of Technolgy
    scholar: SeRMUJwAAAAJ
thumbnail: /assets/img/publications/zod_thumbnail.jpg
website: https://zod.zenseact.com
code: https://github.com/zenseact/zod
arxiv: https://arxiv.org/abs/2305.02008
---

# Abstract
Existing datasets for autonomous driving (AD) often lack diversity and long-range capabilities, focusing instead on 360° perception and temporal reasoning. To address this gap, we introduce Zenseact Open Dataset (ZOD), a large-scale and diverse multimodal dataset collected over two years in various European countries, covering an area 9× that of existing datasets. ZOD boasts the highest range and resolution sensors among comparable datasets, coupled with detailed keyframe annotations for 2D and 3D objects (up to 245m), road instance/semantic segmentation, traffic sign recognition, and road classification. We believe that this unique combination will facilitate breakthroughs in long-range perception and multi-task learning. The dataset is composed of Frames, Sequences, and Drives, designed to encompass both data diversity and support for spatio-temporal learning, sensor fusion, localization, and mapping. Frames consist of 100k curated camera images with two seconds of other supporting sensor data, while the 1473 Sequences and 29 Drives include the entire sensor suite for 20 seconds and a few minutes, respectively. ZOD is the only AD dataset released under the permissive CC BY-SA 4.0 license, allowing for both research and commercial use. The
dataset is accompanied by an extensive [development kit](https://github.com/zenseact/zod).
Data and more information are available [online](https://zod.zenseact.com/).