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

Haonan Zhang (张浩楠 in Chinese) is currently with Alibaba Tongyi Lab, where he conducts research on Qwen Character. He received his Ph.D. in Computer Science and Technology from the University of Electronic Science and Technology of China (UESTC) in 2026, supervised by Prof. [Lianli Gao](https://scholar.google.com/citations?hl=en&user=zsm2dpYAAAAJ) and Prof. [Jingkuan Song](https://cfm.uestc.edu.cn/~songjingkuan/). During his doctoral studies, he was also a visiting Ph.D. student with the Multimedia and Human Understanding Group (MHUG) at the University of Trento, supervised by Prof. [Nicu Sebe](https://scholar.google.com/citations?user=stFCYOAAAAAJ&hl=en).

Before his doctoral studies, he received his bachelor’s degree in Computer Science and Technology from Xidian University in 2020. In the same year, he joined UESTC as a master’s student and later transferred to the Ph.D. program in 2022. His research interests include multimodal learning, large language models, character intelligence, and multimodal interactive agents.

For more information, please see my [CV](https://zchoi.github.io/assets/cv_haonanzhang_0611.pdf).


# 🔥 News
- *2026.07*: &nbsp;🎉🎉 Our survey “[A Survey on Post-training of Multimodal Large Language Models](https://zchoi.github.io/MMPoT-Survey/)” is now available! The first comprehensive survey on post-training of multimodal large language models. The [Paper](https://www.preprints.org/manuscript/202607.1494), [HomePage](https://zchoi.github.io/MMPoT-Survey/), and [GitHub](https://github.com/zchoi/Awesome-Post-Training-for-MLLMs) are all released!
- *2026.04*: &nbsp;🎉🎉 One paper is accepted by **TPAMI 2026**.
- *2026.02*: &nbsp;🎉🎉 One paper is accepted by **ACL 2026 main, Oral (top 3%)**.
- *2026.02*: &nbsp;🎉🎉 One paper is accepted by **CVPR 2026**.
- *2025.10*: &nbsp;🎉🎉 We release [A Survey on Efficient Vision-Language-Action Models](https://evla-survey.github.io/)![GitHub Repo stars](https://img.shields.io/github/stars/YuZhaoshu/Efficient-VLAs-Survey), the first comprehensive survey specifically dedicated to efficient Vision-Language-Action (VLA) models.
- *2025.09*: &nbsp;🎉🎉 Two papers are accepted by **NeurIPS 202**5.
- *2025.09*: &nbsp;🎉🎉 Excited to join the University of Trento 🇮🇹 as a visiting student this September, supervised by Prof. Nicu Sebe. Looking forward to new collaborations and challenges! 🚀
- *2025.05*: &nbsp;🎉🎉 Two papers are accepted by **ACL 2025**.
- *2025.05*: &nbsp;🎉🎉 One paper is accepted by **TIP 2025**.
- *2024.07*: &nbsp;🎉🎉 One paper is accepted by **TCSVT 2024**.
- *2024.07*: &nbsp;🎉🎉 One paper is accepted by **ACM Multimedia 2024**.
- *2024.05*: &nbsp;🎉🎉 Join **Tongyi Lab@Beijing** for a summer internship.
- *2023.11*: &nbsp;🎉🎉 One paper is accepted by **TCSVT 2023**.
- *2023.07*: &nbsp;🎉🎉 Release [Awesome-Embodied-Robotics-and-Agent](https://github.com/zchoi/Awesome-Embodied-Robotics-and-Agent), a curated list of "Embodied robotics or agent with Vision-Language Models (VLMs) and Large Language Models (LLMs)" research! ![GitHub Repo stars](https://img.shields.io/github/stars/zchoi/Awesome-Embodied-Robotics-and-Agent)



# 📝 Publications 
<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
-->

\* indicates equal contribution

- A Survey on Post-training of Multimodal Large Language Models. Preprints 2026. <br>
**Haonan Zhang**, Pengpeng Zeng, Libin Cao, Wenrui Lai, Jinlong Li, Duo Peng. Yi Bin. Xuanhan Wang, Ji Zhang, Jingkuan Song, Nicu Sebe, Yuchuan Wu, Yongbin Li, Heng Tao Shen, Jieping Ye<br>
[[Paper]](https://www.preprints.org/manuscript/202607.1494) [[GitHub]](https://github.com/zchoi/Awesome-Post-Training-for-MLLMs) [[HomePage]](https://zchoi.github.io/MMPoT-Survey/)

- OmniCharacter++: Towards Comprehensive Benchmark for Realistic Role-Playing Agents. TPAMI 2026. <br>
**Haonan Zhang**, Pengpeng Zeng, Ji Zhang, Jingkuan Song, Nicu Sebe, Heng Tao Shen, and Lianli Gao <br>
[[Paper]](https://ieeexplore.ieee.org/abstract/document/11506238?casa_token=VQR1PcA3qjAAAAAA:INXRqxI_XAopWIijLyYjcYhhON94qX4cr4o_rqVBUx8lR3HKjGgZVJmak2uS4kgAAiPllSNeL17t) [[Code]](https://github.com/zchoi/OmniCharacter-plus) [[Project Page]](https://zchoi.github.io/OmniCharacter-plus/)


- Token Reduction via Local and Global Contexts Optimization for Efficient Video Large Language Models. CVPR 2026. <br>
Jinlong Li, Liyuan Jiang, **Haonan Zhang**, Nicu Sebe<br>
[[Paper]](https://arxiv.org/abs/2603.01400) [[Github]](https://github.com/TyroneLi/AOT) [[Project Page]](https://tyroneli.github.io/AOT/)<br>

- A Survey on Efficient Vision-Language-Action Models. arXiv 2025. <br>
Zhaoshu Yu, Bo Wang, Pengpeng Zeng, **Haonan Zhang**, Ji Zhang, Lianli Gao, Jingkuan Song, Nicu Sebe, and Heng Tao Shen<br>
[[Paper]](https://arxiv.org/abs/2510.24795) [[Github]](https://github.com/YuZhaoshu/Efficient-VLAs-Survey) [[Project Page]](https://evla-survey.github.io/)<br>

- Prototype-based Regularization Learning For Text-Video Retrieval. arXiv 2025. <br>
**Haonan Zhang**, Yunwei Ma, Pengpeng Zeng, Lianli Gao, Jingkuan Song, Nicu Sebe, Heng Tao Shen <br>
[Paper] [Code]<br>

- OpenOmni: Large Language Models Pivot Zero-shot Omnimodal Alignment across Language with Real-time Self-Aware Emotional Speech Synthesis. **NeurIPS 2025**. <br>
Run Luo, Ting-En Lin, **Haonan Zhang**, Yuchuan Wu, Xiong Liu, Min Yang, Yongbin Li, Longze Chen, Jiaming Li, Lei Zhang, Yangyi Chen, Hamid Alinejad-Rokny, Fei Huang <br>
[[Paper]](https://arxiv.org/pdf/2501.04561) [[Code]](https://github.com/RainBowLuoCS/OpenOmni)

- Bipolar Self-attention for Spiking Transformers. **NeurIPS 2025 (spotlight)**. <br>
Shuai Wang, Malu Zhang, Jingya Wang, Dehao Zhang, Yimeng Shan, Jieyuan Zhang, Yichen Xiao, Honglin Cao, **Haonan Zhang**, Zeyu Ma, Yang Yang, Haizhou Li <br>

- OmniCharacter: Towards Immersive Role-Playing Agents with Seamless Speech-Language Personality Interaction. **ACL 2025**. <br>
**Haonan Zhang**, Run Luo, Xiong Liu, Yuchuan Wu, Ting-En Lin, Pengpeng Zeng, QIANG QU, Feiteng Fang, Min Yang, Lianli Gao, Jingkuan Song, Fei Huang, Yongbin Li<br>
[[Paper]](https://www.arxiv.org/pdf/2505.20277) [Code]

- MMEvol: Empowering Multimodal Large Language Models with Evol-Instruct. **ACL 2025（Findings）**.  <br>
Run Luo\*, **Haonan Zhang**\*, Longze Chen\*, Ting-En Lin\*, Xiong Liu, Yuchuan Wu, Min Yang, Minzheng Wang, Pengpeng Zeng, Lianli Gao, Heng Tao Shen, Yunshui Li, Xiaobo Xia, Fei Huang, Jingkuan Song, Yongbin Li <br>
[[Project Page]](https://mmevol.github.io/home_page.html) [[Paper]](https://arxiv.org/pdf/2409.05840) [[Code]](https://github.com/RainBowLuoCS/MMEvol)

- Text-Video Retrieval with Global-Local Semantic Consistent Learning. **TIP 2025**. <br>
**Haonan Zhang**, Pengpeng Zeng, Lianli Gao, Jingkuan Song, Yihang Duan, Xinyu Lyu, Heng Tao Shen <br>
[[Paper]](https://ieeexplore.ieee.org/document/11024127?source=authoralert) [[Code]](https://github.com/zchoi/GLSCL)

- UMP: Unified Modality-aware Prompt Tuning for Text-Video Retrieval. **TCSVT 2024**. <br>
**Haonan Zhang**, Pengpeng Zeng, Lianli Gao, Jingkuan Song, Heng Tao Shen<br>
[[Paper]](https://ieeexplore.ieee.org/abstract/document/10599510/) [[Code]](https://github.com/zchoi/UMP_TVR)

- MPT: Multi-grained Prompt Tuning for Text-Video Retrieval. **ACM Multimedia 2024**. <br>
**Haonan Zhang**, Pengpeng Zeng, Lianli Gao, Jingkuan Song, Heng Tao Shen<br>
[[Paper]](https://openreview.net/pdf?id=sIwZ6TIn0P) [[Code]](https://github.com/zchoi/MPT)

- SPT: Spatial pyramid transformer for image captioning. **TCSVT 2023**. <br>
**Haonan Zhang**, Pengpeng Zeng, Lianli Gao, Xinyu Lyu, Jingkuan Song, Heng Tao Shen<br>
[[Paper]](https://ieeexplore.ieee.org/abstract/document/10328641) [[Code]](https://github.com/zchoi/SPT)

- Depth-aware sparse transformer for video-language learning. **ACM Multimedia 2023**. <br>
**Haonan Zhang**, Lianli Gao, Pengpeng Zeng, Alan Hanjalic, Heng Tao Shen<br>
[[Paper]](https://dl.acm.org/doi/abs/10.1145/3581783.3611714) [[Code]](https://github.com/zchoi/DAST)

- Learning visual question answering on controlled semantic noisy labels. **PR 2023**. <br>
**Haonan Zhang**, Pengpeng Zeng, Yuxuan Hu, Jin Qian, Jingkuan Song, Lianli Gao <br>
[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0031320323000407) [[Code]](https://github.com/zchoi/SNLC)

- Video Question Answering with Prior Knowledge and Object-sensitive Learning. **TIP 2022**. <br>
Pengpeng Zeng, **Haonan Zhang**, Lianli Gao, Jingkuan Song, Heng Tao Shen<br>
[[Paper]](https://ieeexplore.ieee.org/document/9882977) [[Code]](https://github.com/zchoi/PKOL)

- S2 Transformer for image captioning. **IJCAI 2022**. <br>
Pengpeng Zeng\*, **Haonan Zhang**\*, Jingkuan Song, and Lianli Gao <br>
[[Paper]](https://www.ijcai.org/proceedings/2022/0224.pdf) [[Code]](https://github.com/zchoi/S2-Transformer) 

# 🎖 Honors and Scholarships
- 2025.03 “Academic Newcomer” Graduate Student Honor Award.
- 2024.12 National Scholarship.
- 2024.07 The Ninth-Place Winner in Challenge of Black-box Adversarial Attacks on Vision Foundation Models in CVPR 2024.
- 2024.05 Shenzhen Stock Exchange Scholarship.
- 2024.04 The 1<sup>st</sup> Place Winner in Attribute Recognition track in MMVRAC, ICME 2024.
- 2023.11 First-class Scholarship.
- 2022.07 Outstanding Graduate Student Cadre.
- 2023.06 Outstanding Graduate Teaching Assistant Award.
- 2022.06 “Academic Youth” Graduate Student Honor Award.

# 📖 Educations
- 2022.09 - (now), University of Electronic Science and Technology of China, Chengdu, China, Ph.D. student of Computer Science and Technology.
- 2020.09 - 2022.06, University of Electronic Science and Technology of China, Chengdu, China, Master of Computer Technology, transferred to Ph.D.
- 2016.09 - 2020.06, Xidian University, Xian, China, Bachelor of Computer Science and Technology.

# 💻 Internships
- *2024.05 - 2025.04*, [Tongyi Lab](https://careers-tongyi.alibaba.com/home?lang=zh), Alibaba Group, China.

# 💬 Services
Program Committee of AAAI25, Reviewer for CVPR23-25, ICCV25, ICLR25, ACM MM, etc.

Reviewer for TIP, TCSVT, TMM, etc.

<a href="https://www.easycounter.com/">
<img src="https://www.easycounter.com/counter.php?haonanzhang"
border="0" alt="Free Web Counters"></a> visitors since Apr. 2025
