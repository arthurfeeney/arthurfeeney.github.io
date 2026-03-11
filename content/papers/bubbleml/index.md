---
title: "BubbleML: A Multi-Physics Dataset and Benchmarks for Machine Learning" 
date: "2023-12-10"
tags: ["Machine Learning for Science", "Thermal Science", "Boiling", "PDE"]
author: ["Sheikh Md Shakeel Hassan", "Arthur Feeney", "Akash Dhruv", "Jihoon Kim",
         "Youngjoon Suh", "Jaiyoung Ryu", "Yoonjin Won", "Aparna Chandramowlishwaran"]
venue: "NeurIPS 2023 (Spotlight)"
description: "This paper creates a challenging multiphase, multiphysics dataset for PDE Surrogates and does analysis of current limitations. Spotlight paper at NeurIPS 2023" 
summary: "This paper creates a challenging multiphase, multiphysics dataset for PDE Surrogates and does analysis of current limitations." 
cover:
    image: "bubbleml.png"
    alt: "BubbleML boiling simulation"
    relative: true

---

#### Project Links

+ [NeurIPS Poster](https://neurips.cc/virtual/2023/poster/73722)
+ [Openreview](https://openreview.net/forum?id=0Wmglu8zak)
+ [Github](https://github.com/HPCForge/BubbleML)

---

#### Abstract

In the field of phase change phenomena, the lack of accessible and diverse datasets suitable for machine learning (ML) training poses a significant challenge. Existing experimental datasets are often restricted, with limited availability and sparse ground truth, impeding our understanding of this complex multiphysics phenomena. To bridge this gap, we present the BubbleML dataset which leverages physics-driven simulations to provide accurate ground truth information for various boiling scenarios, encompassing nucleate pool boiling, flow boiling, and sub-cooled boiling. This extensive dataset covers a wide range of parameters, including varying gravity conditions, flow rates, sub-cooling levels, and wall superheat, comprising 79 simulations. BubbleML is validated against experimental observations and trends, establishing it as an invaluable resource for ML research. Furthermore, we showcase its potential to facilitate the exploration of diverse downstream tasks by introducing two benchmarks: (a) optical flow analysis to capture bubble dynamics, and (b) neural PDE solvers for learning temperature and flow dynamics. The BubbleML dataset and its benchmarks aim to catalyze progress in ML-driven research on multiphysics phase change phenomena, providing robust baselines for the development and comparison of state-of-the-art techniques and models.

#### Frame of subcooled boiling simulation

![](bubbleml.png)

---

#### Citation

```BibTeX
@inproceedings{
    hassan2023bubbleml,
    title={Bubble{ML}: A Multi-Physics Dataset and Benchmarks for Machine Learning},
    author={Sheikh Md Shakeel Hassan and Arthur Feeney and Akash Dhruv and Jihoon Kim and 
            Youngjoon Suh and Jaiyoung Ryu and Yoonjin Won and Aparna Chandramowlishwaran},
    booktitle={Advances in Neural Information Processing Systems},
    year={2023},
    url={https://openreview.net/forum?id=0Wmglu8zak}
}
```

---