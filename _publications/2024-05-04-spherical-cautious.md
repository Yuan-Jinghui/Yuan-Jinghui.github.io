---
title: "Spherical Cautious Optimizers"
collection: publications
permalink: /publication/2024-05-04-spherical-cautious
excerpt: 'Representative Work on Optimization Algorithms.'
date: 2024-05-04
venue: 'Preprint / PR to Timm'
---
**First Author** (Representative Work)

Spherical Cautious Optimizers: Due to the large-scale application of technologies like BatchNorm and RMSNorm in deep neural networks, scale-invariant parameters are absolutely in the majority in deep learning. Since scale-invariant parameters have gradients located in the tangent space but momentum located in the embedding space, cautious optimizers suffer from radial noise interference, leading to poor training performance. We suggest that for scale-invariant parameters, they should be viewed as a quotient manifold of a spherical manifold, and the cautious mask should be processed in the tangent space. With just one extra line of code, the training results are effectively improved. This has been integrated into mainstream deep learning frameworks such as HuggingFace Timm.
