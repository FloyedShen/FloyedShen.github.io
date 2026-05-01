---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# 👻 About Me

<span class='anchor' id='about-me'></span>

Guobin Shen is a fifth-year doctoral student at the [Institute of Automation, Chinese Academy of Sciences](https://ia.cas.cn/), supervised by Prof. [Yi Zeng](https://braincog.ai/~yizeng/). His research bridges neuroscience, cognitive science, and AI to develop brain-inspired approaches for building scalable, trustworthy, and safe large-scale models. He focuses on alignment methods, uncertainty quantification, and robustness against failure modes such as jailbreak attacks and hallucinations, aiming to create AI systems that are not only powerful but also interpretable and reliable.


**🚀 He is actively seeking postdoctoral positions and industry opportunities for Fall 2026.**

You can find his CV here: [📋 English](pdf/Guobin_Shen_CV.pdf) \| [📋 中文](pdf/cv_guobin_shen_zh_CN.pdf).

 <!-- <a href='https://scholar.google.com/citations?user=Sv-WdBkAAAAJ'> -->
  <!-- <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"> -->
<!-- </a> -->

His research interests include:
- **Reinforcement Learning for Large Language Models**
- **Scalable Alignment for Large Models**
- **Interpretability & Trustworthy AI**
- **Cognitive Science and Neuroscience-Inspired AI**

# 📰 News

1. Our paper [**BrainAlign**](https://arxiv.org/abs/2507.01966) has been accepted by **ICML 2026**.
2. Our [**VESPO**](https://huggingface.co/papers/2602.10693) has been integrated into [**HuggingFace TRL**](https://github.com/huggingface/trl/issues/5196). 💻[[Code]](https://github.com/FloyedShen/VESPO)
3. Our paper [**VESPO**](https://huggingface.co/papers/2602.10693), a principled variational framework for stable off-policy RL training of LLMs, ranked **#3** on [HuggingFace Weekly Papers (2026-W09)](https://huggingface.co/papers/week/2026-W09). 💻[[Code]](https://github.com/FloyedShen/VESPO)
2. Our paper on [**Safety Instincts**](https://arxiv.org/abs/2510.01088), which enables LLMs to develop internal safety mechanisms for safety alignment, has been accepted by **ICLR 2026**.
2. Our two papers have been accepted by **NeurIPS 2025**: [**Learning the Plasticity**](https://arxiv.org/abs/2308.12063) on plasticity-driven learning framework in spiking neural networks (main conference), and [**STEP**](https://arxiv.org/abs/2505.11151) evaluation platform (Dataset and Benchmark Track).
3. Our work **SpikePack**, which unifies direct training and conversion of spiking neural networks from an information flow perspective and explores the relationship with ANNs, has been accepted by **ICCV 2025**. 🔗[[Arxiv]](https://arxiv.org/abs/2501.14484v2)
4. We released **PandaGuard**, a systematic evaluation framework for LLM safety against jailbreaking attacks. 🏠[[Project]](https://panda-guard.github.io) 🔗[[Arxiv]](https://arxiv.org/abs/2505.13862) 💻[[Code]]((https://github.com/Beijing-AISI/panda-guard)) 🤗[[Dataset]](https://huggingface.co/datasets/Beijing-AISI/panda-bench)
5. We released **CVC**, a large-scale Chinese value rule corpus for value alignment of large language models. 💻[[Code]]((https://github.com/Beijing-AISI/CVC)) 🤗[[Dataset]](https://huggingface.co/datasets/Beijing-AISI/CVC)
6. Our paper on [**LLM jailbreak antidote**](https://openreview.net/forum?id=s20W12XTF8) has been accepted by **ICLR 2025**.
7. Our two papers, [**StressPrompt**](https://openreview.net/forum?id=vbasQ4Kr6k) on LLM stress analysis and [**DVS data augmentation**](https://openreview.net/forum?id=pCNJkhoskj), have been accepted by **AAAI 2025**. 
8. Our [**multimodal LLM framework**](https://neurips.cc/virtual/2024/poster/93607) on fMRI, vision, and language has been accepted by **NeurIPS 2024**. See you in Vancouver!
9. Our paper on [**SNN efficiency analysis**](https://cvpr.thecvf.com/virtual/2024/poster/29731) has been accepted by **CVPR 2024** and selected as a **highlight paper**.
10. Our work on **neuro-evolution strategies** has been accepted by **PNAS**. [Read more](https://www.pnas.org/doi/10.1073/pnas.2218173120).

# 📝 Publications 

<!-- ### English  -->
### 2026

- `Shen, Guobin`, Zhao, Chenxiao, Cheng, Xiang, Huang, Lei, and Yu, Xing. "VESPO: Variational Sequence-Level Soft Policy Optimization for Stable Off-Policy LLM Training." *arXiv preprint arXiv:2602.10693*, 2026. 🤗[[Paper]](https://huggingface.co/papers/2602.10693) 💻[[Code]](https://github.com/FloyedShen/VESPO)

- `Shen, Guobin`, Zhao, Dongcheng, Tong, Haibo, Li, Jindong, Zhao, Feifei, and Zeng, Yi. "Safety Instincts: LLMs Learn to Trust Their Internal Compass for Self-Defense." *Proceedings of the 14th International Conference on Learning Representations (ICLR 2026)*, 2026. 🔗[[Arxiv]](https://arxiv.org/abs/2510.01088)

### 2025

- `Shen, Guobin`, Zhao, Dongcheng, Dong, Yiting, Li, Yang, Zhao, Feifei, and Zeng, Yi. "Learning the Plasticity: Plasticity-Driven Learning Framework in Spiking Neural Networks." *Advances in Neural Information Processing Systems* (NeurIPS), 2025. 🔗[[Arxiv]](https://arxiv.org/abs/2308.12063)
  
- Shen, Sicheng, Zhao, Dongcheng, Feng, Linghao, Yue, Zeyang, Li, Jindong, Li, Tenglong, `Shen, Guobin`, and Zeng, Yi. "STEP: A Unified Spiking Transformer Evaluation Platform for Fair and Reproducible Benchmarking." *Advances in Neural Information Processing Systems (NeurIPS) Dataset and Benchmark Track*, 2025. 🔗[[Arxiv]](https://arxiv.org/abs/2505.11151)

- `Shen, Guobin`, Zhao, Dongcheng, Feng, Linghao, He, Xiang, Wang, Jihang, Shen, Sicheng, Tong, Haibo, Dong, Yiting, Li, Jindong, Zheng, Xiang, and others. "PandaGuard: Systematic Evaluation of LLM Safety in the Era of Jailbreaking Attacks." *arXiv preprint arXiv:2505.13862*, 2025. 🏠[[Project]](https://panda-guard.github.io) 🔗[[Arxiv]](https://arxiv.org/abs/2505.13862) 💻[[Code]]((https://github.com/Beijing-AISI/panda-guard)) 🤗[[Dataset]](https://huggingface.co/datasets/Beijing-AISI/panda-bench)

- Li, Jindong, Li, Tenglong, Chen, Ruiqi, `Shen, Guobin`, Zhao, Dongcheng, Zhang, Qian, and Zeng, Yi. "Hummingbird: A Smaller and Faster Large Language Model Accelerator on Embedded FPGA." The 2025 International Conference on Computer-Aided Design (ICCAD), 2025. 📃[[PDF]](https://arxiv.org/pdf/2507.03308)

- Li, Jindong, Li, Tenglong, `Shen, Guobin`, Zhao, Dongcheng, Zhang, Qian, and Zeng, Yi. "Pushing Up to the Limit of Memory Bandwidth and Capacity Utilization for Efficient LLM Decoding on Embedded FPGA." *2025 Design, Automation & Test in Europe Conference (DATE)*, IEEE, 2025, pp. 1-7. 📃[[PDF]](https://ieeexplore.ieee.org/abstract/document/10993087/)

- Wu, Ping, `Shen, Guobin`, Zhao, Dongcheng, Wang, Yuwei, Dong, Yiting, Shi, Yu, Lu, Enmeng, Zhao, Feifei, and Zeng, Yi. "CVC: A Large-Scale Chinese Value Rule Corpus for Value Alignment of Large Language Models." *arXiv preprint arXiv:2506.01495*, 2025. 🔗[[Arxiv]](https://arxiv.org/abs/2506.01495) 💻[[Code]]((https://github.com/Beijing-AISI/CVC)) 🤗[[Dataset]](https://huggingface.co/datasets/Beijing-AISI/CVC)
  
- `Shen, Guobin`, Zhao, Dongcheng, Dong, Yiting, He, Xiang, and Zeng, Yi. "Jailbreak Antidote: Runtime Safety-Utility Balance via Sparse Representation Adjustment in Large Language Models." *Proceedings of the 13th International Conference on Learning Representations (ICLR 2025)*, 2025. 🔗[[OpenReview]](https://openreview.net/forum?id=s20W12XTF8) 📃[[PDF]](https://arxiv.org/pdf/2410.02298)

- `Shen, Guobin`, Li, Jindong, Li, Tenglong, Zhao, Dongcheng, and Zeng, Yi. "*SpikePack*: Enhanced Information Flow in Spiking Neural Networks with High Hardware Compatibility." *Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)*, 2025. 🔗[[Arxiv]](https://arxiv.org/abs/2501.14484)
  
- `Shen, Guobin`, Zhao, Dongcheng, Bao, Aorigele, He, Xiang, Dong, Yiting, and Zeng, Yi. "StressPrompt: Does Stress Impact Large Language Models and Human Performance Similarly?" *Proceedings of the 39th AAAI Conference on Artificial Intelligence (AAAI)*, 2025. 🔗[[OpenReview]](https://openreview.net/forum?id=vbasQ4Kr6k) 📃[[PDF]](https://arxiv.org/pdf/2409.17167)

- `Shen, Guobin`, Zhao, Dongcheng, and Zeng, Yi. "Exploiting High-Performance Spiking Neural Networks with Efficient Spiking Patterns." *IEEE Transactions on Emerging Topics in Computational Intelligence (TETCI)*, 2025. 📃[[PDF]](pdf/shen2025exploting.pdf)

- Yu, Yonghao, Zhao, Dongcheng, `Shen, Guobin`, Dong, Yiting, and Zeng, Yi. "Brain-Inspired Stepwise Patch Merging for Vision Transformers." *IJCAI*, 2025. 🔗[[Arxiv]](https://arxiv.org/abs/2409.06963)

- Zhao, Dongcheng, `Shen, Guobin`, Dong, Yiting, Li, Yang, and Zeng, Yi. "Improving Stability and Performance of Spiking Neural Networks through Enhancing Temporal Consistency." *Pattern Recognition*, vol. 159, 2025, p. 111094. Pergamon. 🔗[[Arxiv]](https://arxiv.org/abs/2305.14174) 📃[[PDF]](pdf/zhao2025improving.pdf)

- Dong, Yiting, He, Xiang, `Shen, Guobin`, Zhao, Dongcheng, Li, Yang, and Zeng, Yi. "EventZoom: A Progressive Approach to Event-Based Data Augmentation for Enhanced Neuromorphic Vision." *Proceedings of the 39th AAAI Conference on Artificial Intelligence (AAAI 2025)*, 2025. 🔗[[OpenReview]](https://openreview.net/forum?id=pCNJkhoskj)
  

### 2024

- `Shen, Guobin`, Zhao, Dongcheng, Li, Tenglong, Li, Jindong, and Zeng, Yi. "Are Conventional SNNs Really Efficient? A Perspective from Network Quantization." *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 2024, pp. 27538-27547. 📃[[PDF]](https://openaccess.thecvf.com/content/CVPR2024/papers/Shen_Are_Conventional_SNNs_Really_Efficient_A_Perspective_from_Network_Quantization_CVPR_2024_paper.pdf) 🔗[[Poster]](https://cvpr.thecvf.com/virtual/2024/poster/29731)


- `Shen, Guobin`, Zhao, Dongcheng, He, Xiang, Feng, Linghao, Dong, Yiting, Wang, Jihang, Zhang, Qian, and Zeng, Yi. "Neuro-Vision to Language: Image Reconstruction and Interaction via Non-invasive Brain Recordings." *Proceedings of the 38th Conference on Neural Information Processing Systems (NeurIPS 2024)*, 2024. 📃[[PDF]](https://proceedings.neurips.cc/paper_files/paper/2024/file/b1c62bdeee97b38c34dcda152c829511-Paper-Conference.pdf) 🔗[[Poster]](https://neurips.cc/virtual/2024/poster/93607)

- Dong, Yiting, `Shen, Guobin`, Zhao, Dongcheng, He, Xiang, and Zeng, Yi. "Harnessing Task Overload for Scalable Jailbreak Attacks on Large Language Models." *arXiv preprint arXiv:2410.04190*, 2024. 🔗[[Arxiv]](https://arxiv.org/abs/2410.04190)

- `Shen, Guobin`, Zhao, Dongcheng, Shen, Sicheng, and Zeng, Yi. "Enhancing Spiking Transformers with Binary Attention Mechanisms." *The Second Tiny Papers Track at ICLR 2024*. 📃[[PDF]](https://openreview.net/pdf?id=6X3TNqLb5t)

- `Shen, Guobin`, Zhao, Dongcheng, and Zeng, Yi. "Exploiting Nonlinear Dendritic Adaptive Computation in Training Deep Spiking Neural Networks." *Neural Networks*, vol. 170, 2024, pp. 190-201. Pergamon. 📃[[PDF]](pdf/shen2024nonlinear.pdf)

- Li, Jindong, `Shen, Guobin`, Zhao, Dongcheng, Zhang, Qian, and Zeng, Yi. "Firefly v2: Advancing Hardware Support for High-Performance Spiking Neural Network with a Spatiotemporal FPGA Accelerator." *IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems*, 2024. IEEE. 📃[[PDF]](pdf/li2024fireflyv2.pdf)

- Han, Bing, Zhao, Feifei, Zeng, Yi, and `Guobin Shen`. "Developmental Plasticity-Inspired Adaptive Pruning for Deep Spiking and Artificial Neural Networks." *IEEE Transactions on Pattern Analysis and Machine Intelligence*, 2024. IEEE. 📃[[PDF]](pdf/han2024developmental.pdf)

- Pan, Wenxuan, Zhao, Feifei, `Shen, Guobin`, Han, Bing, and Zeng, Yi. "Brain-Inspired Multi-Scale Evolutionary Neural Architecture Search for Deep Spiking Neural Networks." *IEEE Transactions on Evolutionary Computation*, 2024. IEEE. 

- Li, Jindong, Li, Tenglong, `Shen, Guobin`, Zhao, Dongcheng, Zhang, Qian, and Zeng, Yi. "Revealing Untapped DSP Optimization Potentials for FPGA-Based Systolic Matrix Engines." *2024 34th International Conference on Field-Programmable Logic and Applications (FPL)*, IEEE, 2024, pp. 197-203. 🔗[[Arxiv]](https://arxiv.org/abs/2409.03508) 📃[[PDF]](pdf/li2024revealing.pdf)
  
- Li, Tenglong, Li, Jindong, `Shen, Guobin`, Zhao, Dongcheng, Zhang, Qian, and Zeng, Yi. "FireFly-S: Exploiting Dual-Side Sparsity for Spiking Neural Networks Acceleration with Reconfigurable Spatial Architecture." *IEEE Transactions on Circuits and Systems I: Regular Papers*, 2024. IEEE. 📃[[PDF]](pdf/li2024fireflys.pdf)

- Dong, Yiting, Li, Yang, Zhao, Dongcheng, `Shen, Guobin`, and Zeng, Yi. "Bullying10K: A Large-Scale Neuromorphic Dataset Towards Privacy-Preserving Bullying Recognition." *Advances in Neural Information Processing Systems*, vol. 36, 2024. 📃[[PDF]](https://proceedings.neurips.cc/paper_files/paper/2023/file/05ffe69463062b7f9fb506c8351ffdd7-Paper-Datasets_and_Benchmarks.pdf) 🔗[[Poster]](https://neurips.cc/virtual/2023/poster/73636)

- He, Xiang, Liu, Xiangxi, Li, Yang, Zhao, Dongcheng, `Shen, Guobin`, Kong, Qingqun, Yang, Xin, and Zeng, Yi. "CACE-Net: Co-guidance Attention and Contrastive Enhancement for Effective Audio-Visual Event Localization." *Proceedings of the 32nd ACM International Conference on Multimedia*, 2024, pp. 985-993. 🔗[[OpenReview]](https://openreview.net/forum?id=ue6UUvoL8B) 📃[[PDF]](https://dl.acm.org/doi/pdf/10.1145/3664647.3681503)

- Shen, Sicheng, Zhao, Dongcheng, `Shen, Guobin`, and Zeng, Yi. "TIM: An Efficient Temporal Interaction Module for Spiking Transformer." *Proceedings of the 33rd International Joint Conference on Artificial Intelligence (IJCAI 2024)*, 2024. 📃[[PDF]](https://www.ijcai.org/proceedings/2024/0347.pdf)

- He, Xiang, Zhao, Dongcheng, Li, Yang, `Shen, Guobin`, Kong, Qingqun, and Zeng, Yi. "An Efficient Knowledge Transfer Strategy for Spiking Neural Networks from Static to Event Domain." *Proceedings of the AAAI Conference on Artificial Intelligence*, vol. 38, no. 1, 2024, pp. 512-520. 🔗[[Arxiv]](https://arxiv.org/abs/2303.13077)

- Feng, Linghao, Zhao, Dongcheng, Shen, Sicheng, Dong, Yiting, `Shen, Guobin`, and Zeng, Yi. "Time Cell Inspired Temporal Codebook in Spiking Neural Networks for Enhanced Image Generation." *arXiv preprint arXiv:2405.14474*, 2024. 🔗[[Arxiv]](https://arxiv.org/abs/2405.14474)


### 2023  

- `Shen, Guobin`, Zhao, Dongcheng, Dong, Yiting, and Zeng, Yi. "Brain-Inspired Neural Circuit Evolution for Spiking Neural Networks." *Proceedings of the National Academy of Sciences*, vol. 120, no. 39, 2023, p. e2218173120. National Academy of Sciences. 📃[[PDF]](https://www.pnas.org/doi/epub/10.1073/pnas.2218173120)

- `Shen, Guobin`, Zhao, Dongcheng, and Zeng, Yi. "EventMix: An Efficient Data Augmentation Strategy for Event-Based Learning." *Information Sciences*, vol. 644, 2023, p. 119170. Elsevier. 📃[[PDF]](pdf/shen2023eventmix.pdf)

- Li, Jindong, `Shen, Guobin`, Zhao, Dongcheng, Zhang, Qian, and Zeng, Yi. "Firefly: A High-Throughput Hardware Accelerator for Spiking Neural Networks with Efficient DSP and Memory Optimization." *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*, vol. 31, no. 8, 2023, pp. 1178-1191. IEEE. 📃[[PDF]](pdf/li2023firefly.pdf)

- Han, Bing, Zhao, Feifei, Zeng, Yi, Pan, Wenxuan, and `Shen, Guobin`. "Enhancing Efficient Continual Learning with Dynamic Structure Development of Spiking Neural Networks." *Proceedings of the 32nd International Joint Conference on Artificial Intelligence (IJCAI 2023)*, 2023. 📃[[PDF]](https://www.ijcai.org/proceedings/2023/0334.pdf)

- Zeng, Yi, Zhao, Dongcheng, Zhao, Feifei, `Shen, Guobin`, Dong, Yiting, Lu, Enmeng, Zhang, Qian, Sun, Yinqian, Liang, Qian, Zhao, Yuxuan, and others. "BrainCog: A Spiking Neural Network Based, Brain-Inspired Cognitive Intelligence Engine for Brain-Inspired AI and Brain Simulation." *Patterns*, 2023, p. 100789. 📃[[PDF]](pdf/zeng2023braincog.pdf)

- `Shen, Guobin`, Zhao, Dongcheng, Dong, Yiting, Li, Yang, and Zeng, Yi. "Dive into the Power of Neuronal Heterogeneity." *arXiv preprint arXiv:2305.11484*, 2023. 🔗[[Arxiv]](https://arxiv.org/abs/2305.11484)

- `Shen, Guobin`, Zhao, Dongcheng, Dong, Yiting, Li, Yang, Li, Jindong, Sun, Kang, and Zeng, Yi. "Astrocyte-Enabled Advancements in Spiking Neural Networks for Large Language Modeling." *arXiv preprint arXiv:2312.07625*, 2023. 🔗[[Arxiv]](https://arxiv.org/abs/2312.07625)

- He, Xiang, Zhao, Dongcheng, Li, Yang, `Shen, Guobin`, Kong, Qingqun, and Zeng, Yi. "Improving the Performance of Spiking Neural Networks on Event-Based Datasets with Knowledge Transfer." *arXiv preprint arXiv:2303.13077*, 2023. 🔗[[Arxiv]](https://arxiv.org/abs/2305.14174)
  
  
### 2022

- `Shen, Guobin`, Zhao, Dongcheng, and Zeng, Yi. "Backpropagation with Biologically Plausible Spatiotemporal Adjustment for Training Deep Spiking Neural Networks." *Patterns*, vol. 3, no. 6, 2022. Elsevier. 📃[[PDF]](pdf/shen2022back.pdf)



# 🔍 Academic Services

Served as a reviewer for conferences including **NeurIPS**, **ICML**, **ICLR**, **CVPR**, **ICCV**, **ECCV**, **AAAI**, among others, as well as journals such as **Neural Networks** and **Neurocomputing**.

# 🧑‍🏫 Teaching 

- *2023.08 - 2023.12*, ***Teaching Assistant***, Systems and Computational Neuroscience, University of Chinese Academy of Sciences. 


# 🚀 Projects

**BrainCog** - A comprehensive spiking neural network framework for brain-inspired AI research. `Lead Developer`  💻[[GitHub]](https://github.com/BrainCog-X/Brain-Cog) ![GitHub stars](https://img.shields.io/github/stars/BrainCog-X/Brain-Cog?style=social)

**PandaGuard** - A systematic evaluation framework for LLM safety against jailbreaking attacks. `Lead Developer`  💻[[GitHub]](https://github.com/Beijing-AISI/panda-guard) ![GitHub stars](https://img.shields.io/github/stars/Beijing-AISI/panda-guard?style=social)

# 🎓 Educations 
 
- *2021.08 - 2026.06 (expected)*, ***Ph.D.***, [Institute of Automation, Chinese Academy of Sciences](https://ia.cas.cn/), Beijing, China. 
- *2017.08 - 2021.06*, ***B.S.***, School of Electronics and Information Technology, [Sun Yat-sen University](https://www.sysu.edu.cn/), Guangzhou, China. 



# 🏅 Honors and Awards
- *2025.06* President's Scholarship, Chinese Academy of Sciences `Top 1%`
- *2024.11* National Scholarship (Doctoral Student) `Top 1%`
- *2022.11* Best Paper Award, Chinese Scientists with Cell Press
- *2020.11* National Scholarship (Undergraduate) `Top 1%`
- *2019.11* National Scholarship (Undergraduate) `Top 1%`
- *2019.09* Runner-Up, International Aerial Robotics Competition (Asia-Pacific Region)
- *2019.09* National Second Prize, National Undergraduate Electronic Design Competition `Top 5%`


<!-- # 💬 Conferences

- *2021.10*, National Seminar on Electromagnetic Nondestructive Testing Technology and the 14th Plenary Session of the 11th Session of the Electromagnetic Professional Technology Conference of China, Xian China, Oral.
- *2019.09*, The 19th International Symposium on Applied Electromagnetics and Mechanics (ISEM 2019), Nanjing China, Poster.
- *2017.10*, The 6th China International Pipeline Conference (CIPC 2017), Langfang China, Visit. -->


# 🏭 Internships
- *2025.10 - Present*, ***RedStar Intern***, [Xiaohongshu](https://www.xiaohongshu.com/) Hi Lab, Beijing, China.
