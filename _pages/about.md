---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I'm a second-year master‘s student majoring in Computer Science at Columbia University. I'm a member of the [Robotic Manipulation and Mobility (ROAM) Lab](https://roam.me.columbia.edu/) and the [Digital Video and Multimedia (DVMM) Lab](https://www.ee.columbia.edu/ln/dvmm/) at Columbia University, fortunate to be advised by Professor [Matei Ciocarlie](https://www.me.columbia.edu/faculty/matei-ciocarlie), Professor [Shuran Song](https://www.cs.columbia.edu/~shurans/), and [Jingxi Xu](https://jxu.ai/) on robotics projects; Professor [Shih-Fu Chang](https://www.ee.columbia.edu/~sfchang/) and [Guangxing Han](https://guangxinghan.github.io/) on computer vision projects. I also work closely with Professor [Krzysztof Choromanski](https://research.google/people/KrzysztofChoromanski/) on multiple projects related to ML theories and algorithms.


I have a broad interest in several fields of machine learning, including representation learning, reinforcement learning, architecture design (Transformers, Graph Neural Networks), as well as Monte Carlo methods. Despite such diversity, I'm mostly interested in the **theory-grounded algorithms** behind these areas. Specifically, my research aims at making machine learning more *efficient* \[[4](#HRF),[6](#OMC)\] and *scalable* \[[3](#Toeplitz),
[5](#GKAT)], as well as designing *simple but effective*\[[1](#SMKD)\] learning algorithms as a *better alternative to traditional heuristics*\[[2](#TANDEM)\].

If you are interested in my research and would like collaboration, please feel free to contact me via email: hl3199 at columbia dot edu! :)

**I'm applying to Fall 2023 CS Ph.D. programs and looking for Spring & Summer 2023 research assistant positions. Feel free to reach out!**

<br />

# **Publications**



### <a name="SMKD"></a> 1. **(Preprint 2022)** **Supervised Masked Knowledge Distillation for Few-shot Transformers**

  ***Han Lin**\*, Guangxing Han\*, Jiawei Ma, Shiyuan Huang, Xudong Lin, Shih-Fu Chang*

  Highlight: We propose a novel framework for few-shot Transformers which incorporates label information into self-distillation. Compared with previous self-supervised methods, we allow intra-class knowledge distillation on both class and patch tokens, and introduce the challenging task of masked patch tokens reconstruction across intra-class images.




### <a name="TANDEM"></a> 2. **(Preprint 2022)** [**Active Tactile Exploration for 3D Object Recognition**](https://arxiv.org/abs/2209.08772)

  *Jingxi Xu\*, **Han Lin\***, Shuran Song, Matei Ciocarlie*

  Highlight: We propose TANDEM3D, a co-training framework for exploration and decision making to 3D object recognition with tactile signals. TANDEM3D is based on a novel encoder that builds 3D object representation from contact positions and normals using PointNet++, and enables 6DOF movement.

### <a name="Toeplitz"></a> 3. **(ICML 2022)** [**From block-Toeplitz matrices to differential equations on graphs: towards a general theory for scalable masked Transformers**](https://arxiv.org/abs/2107.07999)

  *Krzysztof Choromanski\*, **Han Lin**\*, Haoxian Chen\*, Tianyi Zhang, Arijit Sehanobish, Valerii Likhosherstov, Jack Parker-Holder, Tamas Sarlos, Adrian Weller, Thomas Weingarten*

  Highlight: We leverage many mathematical techniques ranging from spectral analysis through dynamic programming and random walks and proposed a comprehensive approach for incorporating various masking mechanisms into Transformers architectures in a scalable way, including efficient d-dimensional RPE-masking and graph-kernel masking.


### <a name="HRF"></a> 4. **(ICLR 2022)** [**Hybrid Random Features**](https://arxiv.org/abs/2110.04367)

  *Krzysztof Choromanski\*, **Han Lin**\*, Haoxian Chen\*, Yuanzhe Ma\*, Arijit Sehanobish\*, Deepali Jain, Michael S Ryoo, Jake Varley, Andy Zeng, Valerii Likhosherstov, Dmitry Kalashnikov, Vikas Sindhwani, Adrian Weller*

  Highlight: We propose a new class of random feature methods for linearizing softmax and Gaussian kernels called hybrid random features (HRFs) equipted with strong theoretical guarantees - unbiased approximation and strictly smaller worst-case relative errors than its counterparts.


### <a name="GKAT"></a> 5. **(Preprint 2021)** [**Graph Kernel Attention Transformers**](https://github.com/HL-hanlin/GKAT/blob/main/GKAT_16Jul2021.pdf)

  *Krzysztof Choromanski\*, **Han Lin**\*, Haoxian Chen\*, Jack Parker-Holder*

  Highlight: We introduce a new class of graph neural networks, called GKAT, by combining several concepts that were so far studied independently - graph kernels, attention-based networks with structural priors and more recently, efficient Transformers architectures applying small memory footprint implicit attention methods via low rank decomposition techniques.
  

### <a name="OMC"></a> 6. **(NeurIPS 2020)** [**Demystifying Orthogonal Monte Carlo and Beyond**](https://arxiv.org/abs/2005.13590)

  ***Han Lin**\*, Haoxian Chen\*, Tianyi Zhang, Clement Laroche, Krzysztof Choromanski*

  Highlight: In this paper we shed new light on the theoretical principles behind Orthogonal Monte Carlo (OMC), applying theory of negatively dependent random variables to obtain several new concentration results. We also propose a novel extensions of the method leveraging number theory techniques and particle algorithms, called Near-Orthogonal Monte Carlo (NOMC).


\* Co-First Authors, Equal Contribution.\\
Slideslive video recording and conference poster presenter for \[[4](https://iclr.cc/virtual/2022/poster/6410), [6](https://slideslive.com/38936089/demystifying-orthogonal-monte-carlo-and-beyond?ref=search-presentations-orthogonal+monte+carlo+and+be)\]. \\
Github code maintainer for \[[1](https://github.com/HL-hanlin/SMKD), [3](https://github.com/HL-hanlin/GKAT), [4](https://github.com/HL-hanlin/HRF_ICLR2022), [6](https://github.com/HL-hanlin/OMC)\], contributor for \[[2](https://jxu.ai/tandem3d/)\].

<br />



# **Teaching Experience**


- COMS 4231 Analysis of Algorithms, Fall 2022
  - Prof. Mihalis Yannakakis, Department of Computer Science, Columbia University
- COMS 4732 Computer Vision 2: Learning, Spring 2022 
  - Prof. Carl Vondrick, Department of Computer Science, Columbia University
- COMS 4721 Machine Learning for Data Science, Spring 2022 
  - Prof. Daniel Hsu, Department of Computer Science, Columbia University
- QMSS 5073 Machine Learning for Social Science, Fall 2021
  - Prof. Michael Parrott, Department of Statistics, Columbia University
- IEOR 4007 Optimization Models & Methods for FE, Fall 2019 
  - Prof. Garud Iyengar, Department of IEOR, Columbia University
- IEOR 4418 Transportation Analytics & Logistics, Spring 2019 
  - Prof. Adam Elmachtoub, Department of IEOR, Columbia University


<br />

# **Services**

- Conference Reviewer: ICML 2022, NeurIPS 2022
- Conference Volunteer: RSS 2022


