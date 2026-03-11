---
title: "BERN-NN-IBF: Enhancing Neural Network Bound Propagation Through Implicit Bernstein Form and Optimized Tensor Operations"
date: "2024-11-06"
tags: ["GPU Programming", "Tensor Operations", "Neural Network Bounds", "Formal Verification"]
author: ["Wael Fatnassi", "Arthur Feeney", "Valen Yamamoto", "Aparna Chandramowlishwaran", "Yasser Shoukry"]
venue: "IEEE TCAD 2024"
description: "This paper explores methods to perform efficient bounds-propagation on neural networks. Published in IEEE Transactions on Computer-Aided Design." 
summary: "This paper explores methods to perform efficient bounds-propagation on neural networks." 
cover:
    image: "bern-nn.png"
    alt: "bern-nn high-level diagram"
    relative: true

---

#### Project Link

+ [ieeexplore](https://ieeexplore.ieee.org/abstract/document/10745795)

#### Abstract

Neural networks have emerged as powerful tools across various domains, exhibiting remarkable empirical performance that motivated their widespread adoption in safety-critical applications, which, in turn, necessitates rigorous formal verification techniques to ensure their reliability and robustness. Tight bound propagation plays a crucial role in the formal verification process by providing precise bounds that can be used to formulate and verify properties, such as safety, robustness, and fairness. While state-of-the-art tools use linear and convex approximations to compute upper/lower bounds for each neuron’s outputs, recent advances have shown that nonlinear approximations based on Bernstein polynomials lead to tighter bounds but suffer from scalability issues. To that end, this article introduces BERN-NN-IBF, a significant enhancement of the Bernstein-polynomial-based bound propagation algorithms. BERN-NN-IBF offers three main contributions: 1) a memory-efficient encoding of Bernstein polynomials to scale the bound propagation algorithms; 2) optimized tensor operations for the new polynomial encoding to maintain the integrity of the bounds while enhancing computational efficiency; and 3) tighter under-approximations of the ReLU activation function using quadratic polynomials tailored to minimize approximation errors. Through comprehensive testing, we demonstrate that BERN-NN-IBF achieves tighter bounds and higher computational efficiency compared to the original BERN-NN and state-of-the-art methods, including linear and convex programming used within the winner of the VNN-COMPETITION.

#### Citation

```BibTex
@ARTICLE{10745795,
  author={Fatnassi, Wael and Feeney, Arthur and Yamamoto, Valen and Chandramowlishwaran, Aparna and Shoukry, Yasser},
  journal={IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems}, 
  title={BERN-NN-IBF: Enhancing Neural Network Bound Propagation Through Implicit Bernstein Form and Optimized Tensor Operations}, 
  year={2024},
  volume={43},
  number={11},
  pages={4334-4345},
  keywords={Tensors;Memory management;Approximation algorithms;Polynomials;Robustness;Encoding;Computational efficiency;Biological neural networks;Formal verification;Testing;Formal verification;model checking;neural networks},
  doi={10.1109/TCAD.2024.3447577}}
```
