---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I'm a first-year master's student majoring in Computer Science at Columbia University. I'm a member of the [Digital Video and Multimedia (DVMM) Lab](https://www.ee.columbia.edu/ln/dvmm/) and the [Robotic Manipulation and Mobility (ROAM) Lab](https://roam.me.columbia.edu/) at Columbia University, fortunate to be advised by Prof. [Shih-Fu Chang](https://www.ee.columbia.edu/~sfchang/). It is also have the great honor to work with Prof. [Krzysztof Choromanski](https://research.google/people/KrzysztofChoromanski/) on several projects related to SE3-Performers and more.

My research spans several fields of machine learning, including representation learning and deep learning frameworks design (e.g. Transformers), as well as Monte Carlo methods. Despite such diversity, I'm chiefly fond of the **theory-grounded algorithms** with applications in computer vision and robotics. Specifically, my research aims at making algorithms more *efficient* \[[1](#Topographer),[5](#HRF),[7](#OMC)\] and *scalable* \[[4](#Toeplitz),
[6](#GKAT)], as well as designing *simple but effective* \[[2](#SMKD)\] learning algorithms as a *better alternative to traditional heuristics* \[[3](#TANDEM)\].

If you are interested in my research and would like collaboration, please feel free to contact me via email! :)

**I'm applying for Fall 2023 CS Ph.D. programs and looking for Spring & Summer 2023 research assistant positions. Feel free to reach out!**

<br/>


<h1 id="publications"> Publications</h1>


### <a name="Topographer"></a> 1. **(Preprint 2023)** **Efficient Graph Field Integrators Meet Point Clouds**
*Krzysztof Choromanski\*, Arijit Sehanobish\*, **Han Lin**\*, Yunfan Zhao\*, Eli Berger, Alvin Pan, Tetiana Parshakova, Tianyi Zhang, David Watkins, Valerii Likhosherstov, Somnath Basu Roy Chowdhury, Avinava Dubey, Deepali Jain, Tamas Sarlos, Snigdha Chaturvedi, Adrian Weller*
<br>\[[Paper](https://arxiv.org/abs/2302.00942)\]

<img align='center' src="https://github.com/HL-hanlin/HL-hanlin.github.io/blob/master/images/ICML2023_front_image.png?raw=true"  width="820px"/>

Highlight: We present two new classes of algorithms for efficient field integration on graphs encoding point clouds.
<br><br>

### <a name="SMKD"></a> 2. **(Preprint 2023)** **Supervised Masked Knowledge Distillation for Few-shot Transformers**
***Han Lin**\*, Guangxing Han\*, Jiawei Ma, Shiyuan Huang, Xudong Lin, Shih-Fu Chang*
<br>[Paper coming soon]\[[Code](https://github.com/HL-hanlin/SMKD)\]\[[Slides](https://www.dropbox.com/s/29n9gjgzbqjqqbk/SMKD.pdf?dl=0)\]

<img align='center' src="https://github.com/HL-hanlin/HL-hanlin.github.io/blob/master/images/SMKD3.png?raw=true"  width="820px"/>

Highlight: We propose a novel framework for few-shot Transformers which incorporates label information into self-distillation. Compared with previous self-supervised methods, we allow intra-class knowledge distillation on both class and patch tokens, and introduce the challenging task of masked patch tokens reconstruction across intra-class images. 
<br><br>

### <a name="TANDEM"></a> 3. **(ICRA 2023)** [**Active Tactile Exploration for 3D Object Recognition**](https://arxiv.org/abs/2209.08772)
*Jingxi Xu\*, **Han Lin\***, Shuran Song, Matei Ciocarlie*
<br>\[[Paper](https://arxiv.org/abs/2209.08772)\]\[[Blog](https://jxu.ai/tandem3d/)\]\[[Video](https://www.youtube.com/watch?v=z_90xVf1-88)\]

<img align='center' src="https://github.com/HL-hanlin/HL-hanlin.github.io/blob/master/images/TANDEM.png?raw=true" height='340px' width="700px"/>

Highlight: We propose TANDEM3D, a co-training framework for exploration and decision making to 3D object recognition with tactile signals. TANDEM3D is based on a novel encoder that builds 3D object representation from contact positions and normals using PointNet++, and enables 6DOF movement.
<br><br>


### <a name="Toeplitz"></a> 4. **(ICML 2022)** [**From block-Toeplitz matrices to differential equations on graphs: towards a general theory for scalable masked Transformers**](http://arxiv.org/abs/2107.07999)
*Krzysztof Choromanski\*, **Han Lin**\*, Haoxian Chen\*, Tianyi Zhang, Arijit Sehanobish, Valerii Likhosherstov, Jack Parker-Holder, Tamas Sarlos, Adrian Weller, Thomas Weingarten*
<br>\[[Paper](http://arxiv.org/abs/2107.07999)\]\[[Code](https://github.com/HL-hanlin/GKAT)\]\[[Poster](https://icml.cc/media/PosterPDFs/ICML%202022/f231f2107df69eab0a3862d50018a9b2_mzhGQSV.png)\]

<img align='center' src="https://github.com/HL-hanlin/HL-hanlin.github.io/blob/master/images/Toeplitz.png?raw=true" height='200px'  width="700px"/>

Highlight: We leverage many mathematical techniques ranging from spectral analysis through dynamic programming and random walks and proposed a comprehensive approach for incorporating various masking mechanisms into Transformers architectures in a scalable way, including efficient d-dimensional RPE-masking and graph-kernel masking.
<br><br>

### <a name="HRF"></a> 5. **(ICLR 2022)** [**Hybrid Random Features**](https://arxiv.org/abs/2110.04367)
*Krzysztof Choromanski\*, **Han Lin**\*, Haoxian Chen\*, Yuanzhe Ma\*, Arijit Sehanobish\*, Deepali Jain, Michael S Ryoo, Jake Varley, Andy Zeng, Valerii Likhosherstov, Dmitry Kalashnikov, Vikas Sindhwani, Adrian Weller*
<br>\[[Paper](https://arxiv.org/abs/2110.04367)\]\[[Code](https://github.com/HL-hanlin/HRF_ICLR2022)\]\[[Video](https://iclr.cc/virtual/2022/poster/6410)\]\[[Slides](https://iclr.cc/media/iclr-2022/Slides/6410.pdf)\]

<img align='center' src="https://github.com/HL-hanlin/HL-hanlin.github.io/blob/master/images/HRF.png?raw=true" width="750px"/>

Highlight: We propose a new class of random feature methods for linearizing softmax and Gaussian kernels called hybrid random features (HRFs) equipted with strong theoretical guarantees - unbiased approximation and strictly smaller worst-case relative errors than its counterparts.
<br><br>

### <a name="GKAT"></a> 6. **(Preprint 2021)** [**Graph Kernel Attention Transformers**](https://github.com/HL-hanlin/GKAT/blob/main/GKAT_16Jul2021.pdf)
*Krzysztof Choromanski\*, **Han Lin**\*, Haoxian Chen\*, Jack Parker-Holder*
<br>\[[Paper](https://github.com/HL-hanlin/GKAT/blob/main/GKAT_16Jul2021.pdf)\]\[[Code](https://github.com/HL-hanlin/GKAT)\]

<img align='center' src="https://github.com/HL-hanlin/HL-hanlin.github.io/blob/master/images/GKAT.png?raw=true"  width="750px"/>

Highlight: We introduce a new class of graph neural networks, called GKAT, by combining several concepts that were so far studied independently - graph kernels, attention-based networks with structural priors and more recently, efficient Transformers architectures applying small memory footprint implicit attention methods via low rank decomposition techniques.
<br><br>


### <a name="OMC"></a> 7. **(NeurIPS 2020)** [**Demystifying Orthogonal Monte Carlo and Beyond**](https://arxiv.org/abs/2005.13590)
***Han Lin**\*, Haoxian Chen\*, Tianyi Zhang, Clement Laroche, Krzysztof Choromanski*
<br>\[[Paper](https://arxiv.org/abs/2005.13590)\]\[[Code](https://github.com/HL-hanlin/OMC)\]\[[Video](https://slideslive.com/38936089/demystifying-orthogonal-monte-carlo-and-beyond?ref=search-presentations-orthogonal+monte+carlo+and+be)\]
<img align='center' src="https://github.com/HL-hanlin/HL-hanlin.github.io/blob/master/images/OMC.png?raw=true"  width="700px"/>

<img align='center' src="https://github.com/HL-hanlin/HL-hanlin.github.io/blob/master/images/OMC2.png?raw=true"  width="700px"/>

Highlight: In this paper we shed new light on the theoretical principles behind Orthogonal Monte Carlo (OMC), applying theory of negatively dependent random variables to obtain several new concentration results. We also propose a novel extensions of the method leveraging number theory techniques and particle algorithms, called Near-Orthogonal Monte Carlo (NOMC).
<br><br>

\* Co-First Authors, Equal Contribution.\\
Slideslive video recording and conference poster presenter for \[[5](https://iclr.cc/virtual/2022/poster/6410), [7](https://slideslive.com/38936089/demystifying-orthogonal-monte-carlo-and-beyond?ref=search-presentations-orthogonal+monte+carlo+and+be)\]. \\
Github code maintainer for \[[2](https://github.com/HL-hanlin/SMKD), [4](https://github.com/HL-hanlin/GKAT), [5](https://github.com/HL-hanlin/HRF_ICLR2022), [7](https://github.com/HL-hanlin/OMC)\], contributor for \[[3](https://jxu.ai/tandem3d/)\].

<br />



<h1 id="teaching"> Teaching Assistants</h1>


- [IEOR 4752 Forecasting: A Real-World Application], Fall 2022
  - Prof. Garud Iyengar, Department of IEOR, Columbia University
- [IEOR 4540 Data Mining](https://www.coursicle.com/columbia/courses/IEOR/E4540/), Fall 2022
  - Prof. Krzysztof Choromanski, Department of IEOR, Columbia University


<br />



<h1 id="services"> Academic Services</h1>


%%- Conference Reviewer: ICML 2022, 2023; NeurIPS 2022
%%- Conference Volunteer: RSS 2022


