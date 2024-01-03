---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017]
nav: true
---

[[Google scholar](https://scholar.google.com/citations?user=842OjAQAAAAJ)] | [[DBLP](https://dblp.org/pid/87/3021-4.html)]
###### Preprints
- Xin Fan, Yue Wang, Weishan Zhang, Zhipeng Cai, Yingshu Li, and Zhi Tian. GANFed: GAN-based Federated Learning with Non-IID Datasets. Submitted to IEEE ICC 2024.
- Xin Fan, Yue Wang, Zhipeng Cai, Yingshu Li, and Zhi Tian. Enhancing Reliability of Distributed Learning over Edge Networks. Submitted to IEEE ICC 2024.
- Xin Fan, Yan Huo. An Overview of Low latency for Wireless Communications: An Evolutionary Perspective[J] arXiv preprint arXiv:2107.03484, 2021.
- Yue Wang, Zhi Tian, Xin Fan, Zhipeng Cai, Cameron Nowzari, Kai Zeng, Distributed Swarm Learning for Internet of Things at the Edge: Where Artificial Intelligence Meets Biological Intelligence [J], arXiv preprint arXiv:2210.16705, Submitted to IEEE Communications Magazine, under review.
- Yu Yan, Tao Jing, Qinghe Gao, Yan Huo, Xin Fan, Yue Wang and Yawei Wang, "An Initial Phase-added and RIS-assisted Physical Layer Security Scheme Based on Deep Reinforcement Learning [J]", 2023, Submitted to IEEE Transactions on Vehicular Technology, under review.
- Bing Yang, Yan Huo, Xin Fan, Yu Yan, Tao Jing. Effective Integrated Waveform Design for Integrated Sensing and Communication [J].  Submitted to IEEE Communications Magazine, under review.
- Xiangqing Su, Yan Huo, Xiaoxuan Wang, Tao jing, Xin Fan, Zhiwei Yang. Empowering Large Models: Active Federated Semi-Supervised Learning for Object Detection in the Internet of Vehicles[J], 2023, Submitted to IEEE Transactions on Vehicular Technology, under review.





###### Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>

###### Patents
- Xin Fan, Yan Huo, Tao Jing. A blockchain-based method for spectrum access and management, ZL 2019 1 
0197190.3.
- Tao Jing, Qianwen An, Xin Fan, Yan Huo. A three-dimensional method for channel parameter estimation 
based on atomic norm minimization, ZL 2019 1 0483315.9.
