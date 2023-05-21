---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
---

[[Google scholar](https://scholar.google.com/citations?user=842OjAQAAAAJ)] | [[DBLP](https://dblp.org/pid/87/3021-4.html)] #|[[View by topic](https://jd92.wang/research/)]

#### Preprints
- Xin Fan, Yue Wang, Yan Huo, Zhi Tian. CB-DSL: Communication-efficient and Byzantine-robust Distributed Swarm Learning on Non-i.i.d. Data[J]. arXiv preprint arXiv:2208.05578, 2022. Submitted to IEEE Transactions on Cognitive Communications and Networking, under R2.review.
- Xin Fan, Yan Huo. An Overview of Low latency for Wireless Communications: An Evolutionary Perspective[J] arXiv preprint arXiv:2107.03484, 2021.
- Yue Wang, Zhi Tian, Xin Fan, Yan Huo, Cameron Nowzari, Kai Zeng, Distributed Swarm Learning for Internet of Things at the Edge: Where Artificial Intelligence Meets Biological Intelligence[J], arXiv preprint arXiv:2210.16705, 2022, Submitted to IEEE Wireless Communications.
<!-
- Exploring Vision-Language Models for Imbalanced Learning. Yidong Wang, Zhuohao Yu, **Jindong Wang**, Qiang Heng, Hao Chen, Wei Ye, Rui Xie, Xing Xie, Shikun Zhang. [[arxiv](https://arxiv.org/abs/2304.01457)] [[code](https://github.com/Imbalance-VLM/Imbalance-VLM)]
- An Embarrassingly Simple Baseline for Imbalanced Semi-Supervised Learning. Hao Chen, Yue Fan, Yidong Wang, **Jindong Wang**, Bernt Schiele, Xing Xie, Marios Savvides, Bhiksha Raj. [[arxiv](https://arxiv.org/abs/2211.11086)] 
- FIXED: Frustratingly Easy Domain Generalization with Mixup. Wang Lu, **Jindong Wang**, Han Yu, Lei Huang, Xiang Zhang, Yiqiang Chen, Xing Xie. [[arxiv](https://arxiv.org/abs/2211.05228)]
- Domain-Specific Risk Minimization for Out-of-Distribution Generalization. YiFan Zhang, **Jindong Wang**, Jian Liang, Zhang Zhang, Baosheng Yu, Liang Wang, Xing Xie, and Dacheng Tao. [[arxiv](https://arxiv.org/pdf/2208.08661.pdf)]
- Conv-Adapter: Exploring Parameter Efficient Transfer Learning for ConvNets. Hao Chen, Ran Tao, Han Zhang, Yidong Wang, Wei Ye, Jindong Wang, Guosheng Hu, and Marios Savvides. [[arxiv](https://arxiv.org/abs/2208.07463)]
- Towards Optimization and Model Selection for Domain Generalization: A Mixup-guided Solution. Wang Lu, **Jindong Wang**, Yidong Wang, Kan Ren, Yiqiang Chen, Xing Xie. [[arxiv](https://arxiv.org/abs/2209.00652)]
- Equivariant Disentangled Transformation for Domain Generalization under Combination Shift. Yivan Zhang, **Jindong Wang**, Xing Xie, and Masashi Sugiyama. [[arxiv](https://arxiv.org/abs/2208.02011)]
- Boosting Cross-Domain Speech Recognition with Self-Supervision. Han Zhu, Gaofeng Cheng, **Jindong Wang**, Wenxin Hou, Pengyuan Zhang, and Yonghong Yan. [[arxiv](https://arxiv.org/abs/2206.09783)]
- Learning Invariant Representations across Domains and Tasks. **Jindong Wang**, Wenjie Feng, Chang Liu, Chaohui Yu, Mingxuan Du, Renjun Xu, Tao Qin, and Tie-Yan Liu. [[arxiv](https://arxiv.org/abs/2103.05114)]
- Learning to match distributions for domain adaptation. Chaohui Yu, **Jindong Wang**, Chang Liu, Tao Qin, Renjun Xu, Wenjie Feng, Yiqiang Chen, and Tie-Yan Liu. [[arxiv](https://arxiv.org/abs/2007.10791)]


#### Books

<div class="publications">

{% for y in page.years %}
  {% bibliography -f books -q @*[year={{y}}]* %}
{% endfor %}

</div>
-->

#### Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Patents
- Xin Fan, Yan Huo, Tao Jing. A blockchain-based method for spectrum access and management, ZL 2019 1 
0197190.3.
- Tao Jing, Qianwen An, Xin Fan, Yan Huo. A three-dimensional method for channel parameter estimation 
based on atomic norm minimization, ZL 2019 1 0483315.9.
