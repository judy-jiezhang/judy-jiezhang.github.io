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

<span class='anchor' id='about-me'></span>

Hi, 👋 I'm Jie ZHANG, currently a Research Assistant Professor in the Department of Computer Science and Engineering (<a href='https://cse.hkust.edu.hk/'><strong><span id='cse'>CSE</span></strong></a>) at <a href='https://hkust.edu.hk/'><strong><span id='hkust'>The Hong Kong University of Science and Technology (HKUST)</span></strong></a>, Hong Kong SAR, China. I obtained my Ph.D. degree from the Department of Computing (<a href='https://www.polyu.edu.hk/comp/'><strong><span id='comp'>COMP</span></strong></a>) at <a href='https://www.polyu.edu.hk/'><strong><span id='polyu'>The Hong Kong Polytechnic University (PolyU)</span></strong></a> in 2022, under the supervision of <a href='https://cse.hkust.edu.hk/~songguo/'><strong><span id='guo'>Prof. Song Guo</span></strong></a>, Fellow of IEEE. Prior to that, I obtained my B.E. and M.E. degree from China University of Geosciences, Wuhan, China.

My research interests mainly focus on ***<font color=red>Pervasive Learning and Intelligence</font>***, including Edge AI, Federated Learning, Distributed Systems, Foundation Models' **Meta-cognition** (Large Reasoning Models), **Autonomy** (LLM Agents) and **Efficiency** (Inference Acceleration). My vision is to develop native AI/ML systems that empower ubiquitous intelligent services, particularly in resource-constrained environments, to enrich human life in diverse aspects. I have published multiple top-tier international journal and conference papers, including NeurIPS, AAAI, ICML, ICLR, CVPR, IEEE TC, IEEE TPDS, IEEE TMC, etc.


# 🔥 News
- *2025.08*: [Conference] Serve as Reviewer for ICLR 2026.
- *2025.08*: [Conference] Serve as Reviewer for AAAI 2026.
- *2025.07*: [<font color=red>Grant</font>] &nbsp;🎉🎉 One research project has been awarded under the NSFC’s Key Programme. 
- *2025.07*: [<font color=red>Grant</font>] &nbsp;🎉🎉 One General Research Fund (GRF) has been granted by Research Grants Council (RGC) of Hong Kong; Gratefulness!

  
# 💰 Grants
- **<font color=red>[PI]</font>**: **RGC General Research Fund (GRF)**  
Project title: Evolving Edge Foundation Models via Adaptive Knowledge Editing in Diverse Environments  
Funding source: Research Grants Council of Hong Kong, 2025-2028

- **<font color=red>[PI]</font>**: **NSFC’s Key Programme**  
Project title: “面向多模态联邦学习多层异质性问题的软硬件协同优化关键技术研究”  
Funding source: National Natural Science Foundation of China, 2026-2028

# 📝 Selected Publications 

<font color=red>#: Corresponding Author(s), *: equal contribution (co-first authors)</font>

## *--2025--*

- **<font color=blue>[Arxiv]</font>** [CoRE: Enhancing Metacognition with Label-free Self-evaluation in LRMs](https://arxiv.org/pdf/2507.06087)  
H. Li, S. Bai, **J. Zhang<sup>#</sup>**, S. Guo.   
arXiv preprint arXiv:2507.06087.

- **<font color=blue>[Arxiv]</font>** [Think How to Think: Mitigating Overthinking with Autonomous Difficulty Cognition in Large Reasoning Models](https://arxiv.org/abs/2507.02663)  
Y. Liu, H. Li, X. Ma, **J. Zhang<sup>#</sup>**, S. Guo   
arXiv preprint arXiv:2507.02663.

- **<font color=blue>[Arxiv]</font>** [LazyEviction: Lagged KV Eviction with Attention Pattern Observation for Efficient Long Reasoning](https://arxiv.org/abs/2506.15969)  
H. Zhang, H. Zhang, X. Ma, **J. Zhang<sup>#</sup>**, S. Guo   
arXiv preprint arXiv:2506.15969.

- **<font color=blue>[Arxiv]</font>** [ToFe: Lagged Token Freezing and Reusing for Efficient Vision Transformer Inference](https://arxiv.org/abs/2507.16260)  
H. Zhang, **J. Zhang<sup>#</sup>**, S. Guo  
arXiv preprint arXiv:2507.16260.

- **<font color=red>[ICCV]</font>** [VA-MoE: Variables-Adaptive Mixture of Experts for Incremental Weather Forecasting](https://arxiv.org/abs/2412.02503)  
H. Chen, T. Han, S. Guo, **J. Zhang**, Y. Yu, Y. Dong, L. Bai    
International Conference on Computer Vision (ICCV), 2025. (CCF-A)  

- **<font color=red>[ACM-MM]</font>** [BoxSeg: Quality-Aware and Peer-Assisted Learning for Box-supervised Instance Segmentation](https://arxiv.org/abs/2504.05137)  
J. Lai, W. Wu, J. Zhan, J. Li, B. Gao, J. Liu, **J. Zhang**, S. Guo  
ACM International Conference on Multimedia (ACM-MM), 2025. (CCF-A)

- **<font color=purple>[TNNLS]</font>** [Feature Correlation-guided Knowledge Transfer for Federated Self-supervised Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10908709)    
Y. Liu, S. Guo, **J. Zhang<sup>#</sup>**, Y. Zhan, Q. Zhou, Y. Wang   
IEEE Transactions on Neural Networks and Learning Systems (TNNLS), 2025. (CCF-B)   

- **<font color=red>[ICLR]</font>**  [Causally Motivated Sycophancy Mitigation for Large Language Models](https://openreview.net/forum?id=yRKelogz5i)     
H. Li, X. Tang, **J. Zhang<sup>#</sup>**, S. Guo, S. Bai, P. Dong, Y. Yu    
The Thirteenth International Conference on Learning Representations (ICLR), 2025. (CCF-A).

- **<font color=red>[ICLR]</font>**  [Exploring Prosocial Irrationality for LLM Agents: A Social Cognition View](https://openreview.net/forum?id=u8VOQVzduP)     
X. Liu, **J. Zhang<sup>#</sup>**, H. Shang, S. Guo, C. Yang, Q. Zhu     
The Thirteenth International Conference on Learning Representations (ICLR), 2025. (CCF-A).

## *--2024--*

- **<font color=red>[ICML]</font>**  [Easing Concept Bleeding in Diffusion via Entity Localization and Anchoring](https://openreview.net/forum?id=MsnJl6JkZS)   
J. Zhang, S. Guo, P. Dong, **J. Zhang**, Z. Liu, Y. Yu, X. Wu   
International Conference on Machine Learning (ICML), 2024. (CCF-A).

- **<font color=red>[ICML]</font>**  [Causally Motivated Personalized Federated Invariant Learning with Shortcut-Averse Information-Theoretic Regularization](https://openreview.net/forum?id=Kbd9A4lVoX)   
X. Tang, S. Guo, J. Guo, **J. Zhang<sup>#</sup>**, Y. Yu    
International Conference on Machine Learning (ICML), 2024. (CCF-A).

- **<font color=red>[ICML]</font>**  [Amend to Alignment: Decoupled Prompt Tuning for Mitigating Spurious Correlation in Vision-Language Models](https://openreview.net/forum?id=f8G2KSCSdp)   
**J. Zhang**, X. Ma, S. Guo, P. Li, W. Xu, X. Tang, Z. Hong      
International Conference on Machine Learning (ICML), 2024. (CCF-A).

- **<font color=red>[NeurIPS]</font>**  [Towards Safe Concept Transfer of Multi-modal Diffusion via Causal Representation Editing
](https://openreview.net/forum?id=qaC4sSztlF)    
P. Dong, B. Wang, S. Guo, J. Wang, **J. Zhang**, Z. Hong          
Advances in Neural Information Processing Systems 37, 12708-12738 (NeurIPS), 2024. (CCF-A).

- **<font color=red>[ACM-MM]</font>** [SFP: Spurious Feature-targeted Pruning for Out-of-Distribution Generalization](https://dl.acm.org/doi/pdf/10.1145/3664647.3680969)         
Y. Wang, J. Guo, S. Guo, Y. Liu, **J. Zhang**, W. Zhang   
ACM International Conference on Multimedia (ACM-MM), 2024. (CCF-A)

- **<font color=Teal>[TC]</font>** [Collaborative Neural Architecture Search for Personalized Federated Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10713262)   
Y. Liu, S. Guo, **J. Zhang<sup>#</sup>**, Z. Hong, Y. Zhan, Q. Zhou    
IEEE Transactions on Computers (TC), 2024. (CCF-A)

- **<font color=Teal>[TMC]</font>** [Model Decomposition and Reassembly for Purified Knowledge Transfer in Personalized Federated Learning](https://ieeexplore.ieee.org/abstract/document/10689471)     
**J. Zhang**, S. Guo, X. Ma, W. Xu, Q. Zhou, J. Guo, Z. Hong, S. Jun.    
IEEE Transactions on Mobile Computing (TMC), 2024. (CCF-A).

- **<font color=red>[INFOCOM]</font>** [Otas: An Elastic Transformer Serving System via Token Adaptation](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10621087)   
J. Chen, W. Xu, Z. Hong, S. Guo, H. Wang, **J. Zhang**, D. Zeng    
IEEE INFOCOM 2024-IEEE Conference on Computer Communications (INFOCOM), 2024. (CCF-A)

- **<font color=red>[ICLR]</font>**  [Learning Personalized Causally Invariant Representations for Heterogeneous Federated Clients](https://openreview.net/forum?id=8FHWkY0SwF)    
X. Tang, S. Guo, **J. Zhang<sup>#</sup>**, J. Guo   
The Twelfth International Conference on Learning Representations (ICLR), 2024. (CCF-A)  

- **<font color=red>[CVPR]</font>**  [DiPrompT: Disentangled Prompt Tuning for Multiple Latent Domain Generalization in Federated Learning](https://openaccess.thecvf.com/content/CVPR2024/papers/Bai_DiPrompT_Disentangled_Prompt_Tuning_for_Multiple_Latent_Domain_Generalization_in_CVPR_2024_paper.pdf)    
**S. Bai<sup>*</sup>**, **J. Zhang<sup>*</sup>**, S. Guo, S. Li, J. Guo, J. Hou, T. Han, X. Lu    
The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024. (CCF-A)

- **<font color=red>[AAAI]</font>**  [Combating Data Imbalances in Federated Semi-supervised Learning with Dual Regulators](https://dl.acm.org/doi/10.1609/aaai.v38i10.28974)    
S. Bai, S. Li, W. Zhuang, **J. Zhang<sup>#</sup>**, K. Yang, J. Hou, S. Yi, S. Zhang, J. Gao        
Annual AAAI Conference on Artificial Intelligence (AAAI), 2024. (CCF-A)

- **<font color=red>[AAAI]</font>**  [On the Robustness of Neural-Enhanced Video Streaming against Adversarial Attacks
](https://ojs.aaai.org/index.php/AAAI/article/view/29657)      
Q. Zhou, J. Guo, S. Guo, R. Li, **J. Zhang**, B. Wang, Z. Xu    
Annual AAAI Conference on Artificial Intelligence (AAAI), 2024. (CCF-A)

## *--2023--*
- **<font color=red>[NeurIPS]</font>**  [SwapPrompt: Test-Time Prompt Adaptation for Vision-Language Models](https://openreview.net/pdf?id=EhdNQiOWgQ)      
X. Ma, **J. Zhang<sup>#</sup>**, S. Guo, W. Xu          
Advances in Neural Information Processing Systems (NeurIPS), 2023.  (CCF-A)     

- **<font color=red>[ICML]</font>**  [Towards Unbiased Training in Federated Open-world Semi-supervised Learning](https://proceedings.mlr.press/v202/zhang23af/zhang23af.pdf)    
**J. Zhang**, X. Ma, S. Guo, W. Xu    
International Conference on Machine Learning (ICML), 2023. (CCF-A).

- **<font color=Teal>[TC]</font>** [Towards Data-independent Knowledge Transfer in Model-heterogeneous Federated Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10115052)   
**J. Zhang**, S. Guo, J. Guo, D. Zeng, J. Zhou, A. Zomaya   
IEEE Transactions on Computers (TC), 2023. (CCF-A).

## *--2022--*
- **<font color=Teal>[TPDS]</font>** [Adaptive Vertical Federated Learning on Unbalanced Features
](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9783035)    
**J. Zhang**, S. Guo, Z. Qu, D. Zeng, H. Wang, Q. Liu, AY. Zomaya    
IEEE Transactions on Parallel and Distributed Systems (TPDS) 33 (12), 4006-4018, 2022. (CCF-A)   

- **<font color=red>[CVPR]</font>** [Layer-wised Model Aggregation for Personalized Federated Learning](https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_Layer-Wised_Model_Aggregation_for_Personalized_Federated_Learning_CVPR_2022_paper.pdf)     
**X. Ma<sup>*</sup>**, **J. Zhang<sup>*</sup>**, S. Guo, W. Xu     
Proceedings of the IEEE/CVF conference on computer vision and pattern (CVPR), 2022. (CCF-A)  

## *--2021--*
- **<font color=red>[NeurIPS]</font>** [Parameterized Knowledge Transfer for Personalized Federated Learning
](https://proceedings.neurips.cc/paper_files/paper/2021/file/5383c7318a3158b9bc261d0b6996f7c2-Paper.pdf)   
**J. Zhang**, S. Guo, X. Ma, H. Wang, W. Xu, F. Wu    
Advances in Neural Information Processing Systems (NeurIPS) 34, 10092-10104, 2021. (CCF-A)

- **<font color=Teal>[TC]</font>** [Adaptive Federated Learning on Non-IID Data With Resource Constraint](https://ieeexplore.ieee.org/document/9496155)    
**J. Zhang**, S. Guo, Z. Qu, D. Zeng, Y. Zhan, Q. Liu, R. Akerkar   
IEEE Transactions on Computers (TC) 71 (7), 1655-1667, 2021. (CCF-A)

- **<font color=Purple>[CSUR]</font>** [Edge Learning: The Enabling Technology for Distributed Big Data Analytics in the Edge
](https://dl.acm.org/doi/10.1145/3464419)   
**J. Zhang**, Z. Qu, C. Chen, H. Wang, Y. Zhan, B. Ye, S. Guo    
ACM Computing Surveys (CSUR) 54 (7), 1-36, 2021. (CCF-B)

More publications can be found on [my Google Scholar](https://scholar.google.com/citations?hl=zh-CN&user=JRCNlI8AAAAJ)

# 👩‍💻 Teachings
**As Instructor**
- COMP 1021 - Introduction to Computer Science, HKUST, Spring 2025.
- COMP 1021 - Introduction to Computer Science, HKUST, Fall 2025.

**As Teaching Assistant**
- Programming Fundamentals, PolyU, Spring 2019, Autumn 2019.
- Big Data Analytics, PolyU, Spring 2020, Spring 2021.
- Big Data Computing, PolyU, Autumn 2020, Autumn 2021.

# 👔 Services
**PC Member / Journal Reviewer**
- Reviewer for The IEEE / CVF Computer Vision and Pattern Recognition Conference (CVPR)
- Reviewer for Conference on Neural Information Processing Systems (NeurIPS)
- Reviewer for The International Conference on Machine Learning (ICML)
- Reviewer for IEEE Transactions on Parallel and Distributed Systems (IEEE TPDS)
- Reviewer for IEEE Transactions on Mobile Computing (IEEE TMC)
- Reviewer for IEEE Transactions on Computers (IEEE TC)

# 🎖 Honors and Awards
- **2nd Prize, CUMCM (Contemporary Undergraduate Mathematical Contest in Modeling)** (2023),         
  Awarded by CSIAM (China Society for Industrial and Applied Mathematics).
 
- **National Encouragement Scholarship** (2014),         
  Awarded by China University of Geoscience.
 
- **Outstanding Undergraduate Student Honor** (2015),    
  Awarded by China University of Geoscience.

- **1st Prize, Science and Technology Paper Seminar** (2017),      
  Awarded by China University of Geoscience.


