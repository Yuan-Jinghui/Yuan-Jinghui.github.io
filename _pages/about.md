---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a Master's student at the School of Artificial Intelligence, Optics and Electronics (iOPEN), [Northwestern Polytechnical University (NWPU)](https://www.nwpu.edu.cn/), where I also received my B.E. degree in Automation (NWPU) in 2024. My research interests primarily lie in **efficient optimization algorithms for deep neural networks** and **machine learning theory**. Previously, I spent a wonderful time as a Machine Learning Research Intern at TeleAI.

I have published multiple articles as the first author at top-tier AI conferences such as ICLR and ICML, and have also published papers as a primary author in other journals and conferences. 

In fact, rather than merely publishing papers, I tend to prioritize conducting interesting research—regardless of whether it gets accepted or not. Below are some examples of such work.

### Interesting Works:
* 🎈[**Spherical Cautious Optimizers:**](https://openreview.net/forum?id=OyT2CJ4fh7) I noticed that the [Cautious Optimizer](https://arxiv.org/abs/2411.16085) tends to misinterpret scale-invariant parameters—a type of parameter ubiquitous in neural networks. By adding just a single line of projection code, I was able to significantly improve training results. The Spherical Cautious Optimizer has since been <span style="color: #b30000; font-weight: bold;">incorporated into the [HuggingFace Timm library](https://github.com/huggingface/pytorch-image-models)</span>, making me a [contributor](https://github.com/huggingface/pytorch-image-models/pull/2657) to the project (<span style="color: #b30000; font-weight: bold;">which is pretty cool! 🎉</span>).
* 🎈[**Riemannian Fuzzy K-Means:**](https://openreview.net/forum?id=RURIyF9Vuu) I introduced Riemannian Fuzzy K-Means, which successfully answers a Open Problem in manifold clustering. By avoiding expensive Frechet center loops, it reduces the time complexity from $\mathcal{O}(\nu\omega)$ to $\mathcal{O}(\nu)$, achieving over 100x speedup. This algorithm has been incorporated into [Manify](https://github.com/pchlenski/manify)-a machine learning library for manifolds—making me a [contributor](https://github.com/pchlenski/manify/pull/5) to the project. I am also thrilled that the authors of Manify [described this work](https://arxiv.org/abs/2503.09576) by stating, <span style="color: #b30000; font-weight: bold;">"It overcomes the significant computational hurdles" </span>(and I am grateful for their generous praise 🎉).

This personal homepage currently serves primarily as a space for me to share some of my preliminary—yet exciting—research ideas. You are most welcome to browse my blog!

If you have any questions or interesting ideas, please feel free to contact me at any time.

