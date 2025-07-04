# Awesome Diffusion/Flow Based Samplers
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#readme)
> Collecting research materials on neural samplers with diffusion/flow models

## Table of Contents
- [Workshops & Symposiums](#workshops--symposiums)
- [Papers](#papers)
  - [Diffusion & Flow Based](#diffusion--flow-based)
  - [Optimal Control & GFlowNet & Others](#optimal-control--gflownet--others)
  - [Applications](#applications)

## Workshops & Symposiums

- [FPI Workshop at ICLR 2025.](https://sites.google.com/view/fpiworkshop/about?authuser=0)


## Papers

### Diffusion & Flow Based

**RNE: a plug-and-play framework for diffusion density estimation and inference-time control**\
*Jiajun He, José Miguel Hernández-Lobato, Yuanqi Du, Francisco Vargas*\
arXiv:2506.05668 [[Paper](https://arxiv.org/abs/2506.05668)]\
27 June 2025

**On scalable and efficient training of diffusion samplers**\
*Minkyu Kim, Kiyoung Seong, Dongyeop Woo, Sungsoo Ahn, Minsu Kim*\
arXiv:2505.19552 [[Paper](https://arxiv.org/abs/2505.19552)]\
6 June 2025

**Test-Time Alignment of Discrete Diffusion Models with Sequential Monte Carlo**\
*Chinmay Pani, Zijing Ou, Yingzhen Li*\
arXiv:2505.22524 [[Paper](https://arxiv.org/abs/2505.22524)]\
28 May 2025

**Energy-based generator matching: A neural sampler for general state space**\
*Dongyeop Woo, Minsu Kim, Minkyu Kim, Kiyoung Seong, Sungsoo Ahn*\
arXiv:2505.19646 [[Paper](https://arxiv.org/abs/2505.19646)]\
27 May 2025

**Importance Weighted Score Matching for Diffusion Samplers with Enhanced Mode Coverage**\
*Chenguang Wang, Xiaoyu Zhang, Kaiyuan Cui, Weichen Zhao, Yongtao Guan, Tianshu Yu*\
arXiv:2505.19431 [[Paper](https://arxiv.org/abs/2505.19431)]\
26 May 2025

**Discrete Neural Flow Samplers with Locally Equivariant Transformer**\
*Zijing Ou, Ruixiang Zhang, Yingzhen Li*\
arXiv:2505.17741  [[Paper](https://arxiv.org/abs/2505.17741)]\
23 May 2025

**Path Gradients after Flow Matching**\
*Lorenz Vaitl, Leon Klein*\
arXiv:2505.10139 [[Paper](https://arxiv.org/abs/2505.10139)]\
15 May 2025

**Feynman-Kac Correctors in Diffusion: Annealing, Guidance, and Product of Experts**\
*Marta Skreta, Tara Akhound-Sadegh, Viktor Ohanesian, Roberto Bondesan, Alán Aspuru-Guzik, Arnaud Doucet, Rob Brekelmans, Alexander Tong, Kirill Neklyudov*\
arXiv:2503.02819 [[Paper](https://arxiv.org/abs/2503.02819)]\
4 Mar 2025

**Scalable Equilibrium Sampling with Sequential Boltzmann Generators**\
*Charlie B. Tan, Avishek Joey Bose, Chen Lin, Leon Klein, Michael M. Bronstein, Alexander Tong*\
arXiv:2502.18462 [[Paper](https://arxiv.org/abs/2502.18462)]\
25 Feb 2025


**Generalised Parallel Tempering: Flexible Replica Exchange via Flows and Diffusions**\
*Leo Zhang, Peter Potaptchik, Arnaud Doucet, Hai-Dang Dau, Saifuddin Syed*\
arXiv:2502.10328 [[Paper](https://arxiv.org/abs/2502.10328)]\
14 Feb 2025

**LEAPS: A discrete neural sampler via locally equivariant networks**\
*Peter Holderrieth, Michael S. Albergo, Tommi Jaakkola*\
arXiv:2502.10843 [[Paper](https://arxiv.org/abs/2502.10843)]\
15 Feb 2025

**Single-Step Consistent Diffusion Samplers**\
*Pascal Jutras-Dubé, Patrick Pynadath, Ruqi Zhang*\
arXiv:2502.07579 [[Paper](https://arxiv.org/abs/2502.07579)]\
11 Feb 2025

**Neural Flow Samplers with Shortcut Models**\
*Wuhao Chen, Zijing Ou, Yingzhen Li*\
arXiv:2502.07337 [[Paper](https://arxiv.org/abs/2502.07337)]\
11 Feb 2025

**No Trick, No Treat: Pursuits and Challenges Towards Simulation-free Training of Neural Samplers**\
*Jiajun He, Yuanqi Du, Francisco Vargas, Dinghuai Zhang, Shreyas Padhy, RuiKang OuYang, Carla Gomes, José Miguel Hernández-Lobato*\
arXiv:2502.06685 [[Paper](https://arxiv.org/abs/2502.06685)]\
10 Feb 2025

**End-to-end Learning of Gaussian Mixture Priors for Diffusion Sampler**\
*Denis Blessing, Xiaogang Jia, Gerhard Neumann*\
ICLR 2025. [[Paper](https://openreview.net/forum?id=iXbUquaWbl)]\
11 Feb 2025

**Complexity Analysis of Normalizing Constant Estimation: from Jarzynski Equality to Annealed Importance Sampling and beyond**\
*Wei Guo, Molei Tao, Yongxin Chen*\
ICLR 2025. [[Paper](https://arxiv.org/abs/2502.04575)]\
7 Feb 2025

**Underdamped Diffusion Bridges with Applications to Sampling**\
*Denis Blessing, Julius Berner, Lorenz Richter, Gerhard Neumann*\
ICLR 2025. [[Paper](https://openreview.net/forum?id=Q1QTxFm0Is)]\
23 Jan 2025

**Neural Sampling from Boltzmann Densities: Fisher-Rao Curves in the Wasserstein Geometry**\
*Jannis Chemseddine, Christian Wald, Richard Duong, Gabriele Steidl*\
ICLR 2025. [[Paper](https://openreview.net/forum?id=TUvg5uwdeG)]\
22 Jan 2025

**A General Framework for Inference-time Scaling and Steering of Diffusion Models**\
*Raghav Singhal, Zachary Horvitz, Ryan Teehan, Mengye Ren, Zhou Yu, Kathleen McKeown, Rajesh Ranganath*\
arXiv:2501.06848 [[Paper](https://arxiv.org/abs/2501.06848)]\
16 Jan 2025

**Learned Reference-based Diffusion Sampling for multi-modal distributions**\
*Maxence Noble, Louis Grenioux, Marylou Gabrié, Alain Oliviero Durmus*\
ICLR 2025. [[Paper](https://arxiv.org/abs/2410.19449)]\
25 Dec 2024

**Sequential Controlled Langevin Diffusions**\
*Junhua Chen, Lorenz Richter, Julius Berner, Denis Blessing, Gerhard Neumann, Anima Anandkumar*\
ICLR 2025. [[Paper](https://openreview.net/forum?id=dImD2sgy86)]\
10 Dec 2024

**Diffusion-PINN Sampler**\
*Zhekun Shi, Longlin Yu, Tianyu Xie, Cheng Zhang*\
arXiv:2410.15336 [[Paper](https://arxiv.org/abs/2410.15336)]\
20 Oct 2024

**NETS: A Non-Equilibrium Transport Sampler**\
*Michael S. Albergo, Eric Vanden-Eijnden*\
arXiv:2410.02711 [[Paper](https://arxiv.org/abs/2410.02711)]\
3 Oct 2024

**BNEM: A Boltzmann Sampler Based on Bootstrapped Noised Energy Matching**\
*RuiKang OuYang, Bo Qiang, José Miguel Hernández-Lobato*\
arXiv:2409.09787 [[Paper](https://arxiv.org/abs/2409.09787)]\
15 Sep 2024

**Efficient and Unbiased Sampling of Boltzmann Distributions via Consistency Models**\
*Fengzhe Zhang, Jiajun He, Laurence I. Midgley, Javier Antorán, José Miguel Hernández-Lobato*\
arXiv:2409.07323 [[Paper](https://arxiv.org/abs/2409.07323)]\
11 Sep 2024

**Iterated Energy-based Flow Matching for Sampling from Boltzmann Densities**\
*Dongyeop Woo, Sungsoo Ahn*\
arXiv:2408.16249 [[Paper](https://arxiv.org/abs/2408.16249)]\
29 Aug 2024

**Dynamical Measure Transport and Neural PDE Solvers for Sampling**\
*Jingtong Sun, Julius Berner, Lorenz Richter, Marius Zeinhofer, Johannes Müller, Kamyar Azizzadenesheli, Anima Anandkumar*\
NeurIPS 2024. [[Paper](https://arxiv.org/abs/2407.07873)]\
10 Jul 2024

**Markovian Flow Matching: Accelerating MCMC with Continuous Normalizing Flows**\
*Alberto Cabezas, Louis Sharrock, Christopher Nemeth*\
NeurIPS 2024. [[Paper](https://arxiv.org/abs/2405.14392)] [[Code](https://github.com/albcab/mfm)]\
23 May 2024

**Liouville Flow Importance Sampler**\
*Yifeng Tian, Nishant Panda, Yen Ting Lin*\
ICML 2024. [[Paper](https://arxiv.org/abs/2405.06672)] [[Code](https://github.com/lanl/LFIS)]\
3 May 2024

**Faster Sampling via Stochastic Gradient Proximal Sampler**\
*Xunpeng Huang, Difan Zou, Yi-An Ma, Hanze Dong, Tong Zhang*\
ICML 2024. [[Paper](https://arxiv.org/abs/2405.16734)] \
27 May 2024

**Path-Guided Particle-based Sampling**\
*Mingzhou_Fan, Ruida Zhou, Chao Tian, Xiaoning Qian*\
ICLR 2024. [[Paper](https://openreview.net/forum?id=Kt4fwiuKqf)]\
2 May 2024

**Stochastic Localization via Iterative Posterior Sampling**\
*Louis Grenioux, Maxence Noble, Marylou Gabrié, Alain Oliviero Durmus*\
ICML 2024. [[Paper](https://arxiv.org/abs/2402.10758)] \
16 Feb 2024

**Iterated Denoising Energy Matching for Sampling from Boltzmann Densities**\
*Tara Akhound-Sadegh, Jarrid Rector-Brooks, Avishek Joey Bose, Sarthak Mittal, Pablo Lemos, Cheng-Hao Liu, Marcin Sendera, Siamak Ravanbakhsh, Gauthier Gidel, Yoshua Bengio, Nikolay Malkin, Alexander Tong*\
ICML 2024. [[Paper](https://arxiv.org/abs/2402.06121)] [[Code](https://github.com/jarridrb/DEM)]\
9 Feb 2024

**Particle Denoising Diffusion Sampler**\
*TAngus Phillips, Hai-Dang Dau, Michael John Hutchinson, Valentin De Bortoli, George Deligiannidis, Arnaud Doucet*\
ICML 2024. [[Paper](https://arxiv.org/abs/2402.06320)] [[Code](https://github.com/angusphillips/particle_denoising_diffusion_sampler)]\
9 Feb 2024

**Diffusive Gibbs Sampling**\
*Wenlin Chen, Mingtian Zhang, Brooks Paige, José Miguel Hernández-Lobato, David Barber*\
ICML 2024. [[Paper](https://arxiv.org/abs/2402.03008)] [[Code](https://github.com/Wenlin-Chen/DiGS)]\
5 Feb 2024

**Reverse Diffusion Monte Carlo**\
*Xunpeng Huang, Hanze Dong, Yifan Hao, Yi-An Ma, Tong Zhang*\
ICLR 2024. [[Paper](https://openreview.net/forum?id=kIPEyMSdFV)]\
2 Oct 2023

**Transport meets Variational Inference: Controlled Monte Carlo Diffusions**\
*Francisco Vargas, Shreyas Padhy, Denis Blessing, Nikolas Nüsken*\
ICLR 2024. [[Paper](https://arxiv.org/abs/2307.01050)]\
3 Jul 2023

**Improved sampling via learned diffusions**\
*Lorenz Richter, Julius Berner*\
ICLR 2024. [[Paper](https://openreview.net/forum?id=h4pNROsO06)] [[Code](https://github.com/juliusberner/sde_sampler)]\
3 Jul 2023

**Learning Interpolations between Boltzmann Densities**\
*Bálint Máté, François Fleuret*\
TMLR 2023. [[Paper](https://openreview.net/forum?id=TH6YrEcbth)] [[Code](https://github.com/balintmate/boltzmann-interpolations)]\
30 May 2023

**Action Matching: Learning Stochastic Dynamics from Samples**\
*Kirill Neklyudov, Rob Brekelmans, Daniel Severo, Alireza Makhzani*\
ICML 2023. [[Paper](https://arxiv.org/abs/2210.06662)] [[Code](https://github.com/necludov/jam#tutorials)]\
6 Feb 2023

**Denoising Diffusion Samplers**\
*Francisco Vargas, Will Sussman Grathwohl, Arnaud Doucet*\
ICLR 2023. [[Paper](https://openreview.net/forum?id=8pvnfTAbu1f)]\
2 Feb 2023




### Optimal Control & GFlowNet & Others

**Adjoint Schrödinger Bridge Sampler**\
*Guan-Horng Liu, Jaemoo Choi, Yongxin Chen, Benjamin Kurt Miller, Ricky T. Q. Chen*\
arXiv:2506.22565 [[Paper](https://arxiv.org/abs/2506.22565)]\
27 June 2025

**Adjoint Sampling: Highly Scalable Diffusion Samplers via Adjoint Matching**\
*Aaron Havens, Benjamin Kurt Miller, Bing Yan, Carles Domingo-Enrich, Anuroop Sriram, Brandon Wood, Daniel Levine, Bin Hu, Brandon Amos, Brian Karrer, Xiang Fu, Guan-Horng Liu, Ricky T. Q. Chen*\
arXiv:2504.11713 [[Paper](https://arxiv.org/abs/2504.11713)]\
16 Apr 2025

**Adjoint Matching: Fine-tuning Flow and Diffusion Generative Models with Memoryless Stochastic Optimal Control**\
*Carles Domingo-Enrich, Michal Drozdzal, Brian Karrer, Ricky T. Q. Chen*\
ICLR 2025 [[Paper](https://arxiv.org/abs/2409.08861)]\
7 Jan 2025

**Value Gradient Sampler: Sampling as Sequential Decision Making**\
*Sangwoong Yoon, Himchan Hwang, Hyeokju Jeong, Dong Kyu Shin, Che-Sang Park, Sehee Kwon, Frank Chongwoo Park*\
arXiv:2502.13280 [[Paper](https://www.arxiv.org/abs/2502.13280)]\
18 Feb 2025

**Denoising Fisher Training For Neural Implicit Samplers**\
*Weijian Luo, Wei Deng*\
arXiv:2411.01453 [[Paper](https://arxiv.org/abs/2411.01453)]\
3 Nov 2024

**Steering Masked Discrete Diffusion Models via Discrete Denoising Posterior Prediction**\
*Jarrid Rector-Brooks, Mohsin Hasan, Zhangzhi Peng, Zachary Quinn, Chenghao Liu, Sarthak Mittal, Nouha Dziri, Michael Bronstein, Yoshua Bengio, Pranam Chatterjee, Alexander Tong, Avishek Joey Bose*\
ICLR 2025. [[Paper](https://arxiv.org/abs/2410.08134)]\
10 Otc 2024

**Training Neural Samplers with Reverse Diffusive KL Divergence**\
*Jiajun He, Wenlin Chen, Mingtian Zhang, David Barber, José Miguel Hernández-Lobato*\
AISTAT 2025 [[Paper](https://arxiv.org/abs/2410.12456)] [[Code](https://github.com/jiajunhe98/DiKL)]\
16 Oct 2024

**Flow Annealed Importance Sampling Bootstrap meets Differentiable Particle Physics**\
*Annalena Kofler, Vincent Stimper, Mikhail Mikhasenko, Michael Kagan, Lukas Heinrich*\
arXiv:2411.16234 [[Paper](https://arxiv.org/abs/2411.16234)]\
25 Nov 2024

**Functional Gradient Flows for Constrained Sampling**\
*Shiyue Zhang, Longlin Yu, Ziheng Cheng, Cheng Zhang*\
NeurIPS 2024. [[Paper](https://arxiv.org/abs/2410.23170)]\
30 Oct 2024

**Transferable Boltzmann Generators**\
*Leon Klein, Frank Noé*\
NeurIPS 2024. [[Paper](https://arxiv.org/abs/2406.14426)]\
20 Jun 2024

**Improved off-policy training of diffusion samplers**\
*Marcin Sendera, Minsu Kim, Sarthak Mittal, Pablo Lemos, Luca Scimeca, Jarrid Rector-Brooks, Alexandre Adam, Yoshua Bengio, Nikolay Malkin*\
NeurIPS 2024. [[Paper](https://arxiv.org/abs/2402.05098)]\
26 May 2024

**An optimal control perspective on diffusion-based generative modeling**\
*Julius Berner, Lorenz Richter, Karen Ullrich*\
TMLR 2024. [[Paper](https://arxiv.org/abs/2211.01364)] [[Code](https://github.com/juliusberner/sde_sampler)]\
26 Mar 2024

**Diffusion Generative Flow Samplers: Improving learning signals through partial trajectory optimization**\
*Dinghuai Zhang, Ricky T. Q. Chen, Cheng-Hao Liu, Aaron Courville, Yoshua Bengio*\
ICLR 2024. [[Paper](https://arxiv.org/abs/2310.02679)]\
4 Oct 2023

**Entropy-based Training Methods for Scalable Neural Implicit Sampler**\
*Weijian Luo, Boya Zhang, Zhihua Zhang*\
NeurIPS 2023. [[Paper](https://openreview.net/forum?id=lXOoR4KYcJ)]\
8 Jun 2023

**GFlowNets and variational inference**\
*Nikolay Malkin, Salem Lahlou, Tristan Deleu, Xu Ji, Edward Hu, Katie Everett, Dinghuai Zhang, Yoshua Bengio*\
ICLR 2023. [[Paper](https://arxiv.org/abs/2210.00580)]\
2 Oct 2022 

**Flow Annealed Importance Sampling Bootstrap**\
*Laurence Illing Midgley, Vincent Stimper, Gregor N. C. Simm, Bernhard Schölkopf, José Miguel Hernández-Lobato*\
ICLR 2023. [[Paper](https://openreview.net/forum?id=XCTVFJwS9LJ)] [[Code](https://github.com/lollcat/fab-jax)]\
3 Aug 2022

**Path Integral Sampler: a stochastic control approach for sampling**\
*Qinsheng Zhang, Yongxin Chen*\
ICLR 2022. [[Paper](https://openreview.net/forum?id=_uCb2ynRu7Y)] [[Code](https://github.com/qsh-zh/pis)]\
30 Nov 2021

**Solving high-dimensional Hamilton-Jacobi-Bellman PDEs using neural networks: perspectives from the theory of controlled diffusions and measures on path space**\
*Nikolas Nüsken, Lorenz Richter*\
arXiv:2005.05409 [[Paper](https://arxiv.org/abs/2005.05409)]\
11 May 2020

### Applications

**Energy-Weighted Flow Matching for Offline Reinforcement Learning**\
*Shiyuan Zhang, Weitong Zhang, Quanquan Gu*\
ICLR 2025 [[Paper](https://arxiv.org/abs/2503.04975)]\
6 Mar 2025

**Scalable Discrete Diffusion Samplers: Combinatorial Optimization and Statistical Physics**\
*Sebastian Sanokowski, Wilhelm Berghammer, Martin Ennemoser, Haoyu Peter Wang, Sepp Hochreiter, Sebastian Lehner*\
ICLR 2025 [[Paper](https://arxiv.org/abs/2502.08696)]\
12 Feb 2025

**Debiasing Guidance for Discrete Diffusion with Sequential Monte Carlo**\
*Cheuk Kit Lee, Paul Jeha, Jes Frellsen, Pietro Lio, Michael Samuel Albergo, Francisco Vargas*\
arXiv:2502.06079 [[Paper](https://arxiv.org/abs/2502.06079)]\
10 Feb 2025

**Syntactic and Semantic Control of Large Language Models via Sequential Monte Carlo**\
*João Loula, Benjamin LeBrun, Li Du, Ben Lipkin, Clemente Pasti, Gabriel Grand, Tianyu Liu, Yahya Emara, Marjorie Freedman, Jason Eisner, Ryan Cotterell, Vikash Mansinghka, Alexander K. Lew, Tim Vieira, Timothy J. O'Donnell*\
ICLR 2025. [[Paper](https://openreview.net/forum?id=xoXn62FzD0)]\
23 Jan 2025

**Step-by-Step Reasoning for Math Problems via Twisted Sequential Monte Carlo**\
*Shengyu Feng, Xiang Kong, Shuang Ma, Aonan Zhang, Dong Yin, Chong Wang, Ruoming Pang, Yiming Yang*\
ICLR 2025. [[Paper](https://arxiv.org/abs/2410.01920)]\
23 Jan 2025

**Alignment without Over-optimization: Training-Free Solution for Diffusion Models**\
*Sunwoo Kim, Minkyu Kim, Dongmin Park*\
ICLR 2025. [[Paper](https://openreview.net/forum?id=vi3DjUhFVm)]\
23 Jan 2025

**Posterior Inference in Sequential Models with Soft Value Guidance**\
*Nikolas Nüsken, Lorenz Richter*\
Blog Post. [[Blog](https://brekelma.github.io/soft-value-guidance/)]\
6 Jan 2025

**On Diffusion Posterior Sampling via Sequential Monte Carlo for Zero-Shot Scaffolding of Protein Motifs**\
*James Matthew Young, O. Deniz Akyildiz*\
arXiv:2412.05788 [[Paper](https://arxiv.org/abs/2412.05788)]\
8 Dec 2024

**Efficient Diversity-Preserving Diffusion Alignment via Gradient-Informed GFlowNets**\
*Zhen Liu, Tim Z. Xiao, Weiyang Liu, Yoshua Bengio, Dinghuai Zhang*\
ICLR 2025. [[Paper](https://arxiv.org/abs/2412.07775)]\
10 Dec 2024

**Diffusion Models as Constrained Samplers for Optimization with Unknown Constraints**\
*Lingkai Kong, Yuanqi Du, Wenhao Mu, Kirill Neklyudov, Valentin De Bortoli, Dongxia Wu, Haorui Wang, Aaron Ferber, Yi-An Ma, Carla P. Gomes, Chao Zhang*\
AISTATS 2025. [[Paper](https://arxiv.org/abs/2402.18012)]\
21 Oct 2024

**Plug-and-Play Controllable Generation for Discrete Masked Models**\
*Wei Guo, Yuchen Zhu, Molei Tao, Yongxin Chen*\
arXiv:2410.02143 [[Paper](https://arxiv.org/abs/2410.02143)]\
3 Oct 2024

**Improving GFlowNets for Text-to-Image Diffusion Alignment**\
*Dinghuai Zhang, Yizhe Zhang, Jiatao Gu, Ruixiang Zhang, Josh Susskind, Navdeep Jaitly, Shuangfei Zhai*\
TMLR 2025. [[Paper](https://arxiv.org/abs/2412.07775)]\
2 Jun 2024

**Probabilistic Inference in Language Models via Twisted Sequential Monte Carlo**\
*Stephen Zhao, Rob Brekelmans, Alireza Makhzani, Roger Grosse*\
ICML 2024 Best Paper Award. [[Paper](https://arxiv.org/abs/2404.17546)]\
26 Apr 2024

**Monte Carlo guided Diffusion for Bayesian linear inverse problems**\
*Gabriel Cardoso, Yazid Janati El Idrissi, Sylvain Le Corff, Eric Moulines*\
ICLR 2024. [[Paper](https://arxiv.org/abs/2308.07983)]\
15 Aug 2023

**Practical and Asymptotically Exact Conditional Sampling in Diffusion Models**\
*Luhuan Wu, Brian L. Trippe, Christian A. Naesseth, David M. Blei, John P. Cunningham*\
NeurIPS 2023. [[Paper](https://arxiv.org/abs/2306.17775)]\
30 Jun 2023

