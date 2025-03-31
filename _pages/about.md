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

Jialun CAO received her PhD degree from the Department of Computer Science and Engineering at The Hong Kong University of Science and Technology <a href='https://hkust.edu.hk/'>(HKUST)</a>, under the supervision of <a href="https://www.cse.ust.hk/faculty/scc/">Prof. S.C. Cheung</a>. She is now a Research Assistant Professor in HKUST.

Her research interests lie in the intersection of <strong>Software Engineering (SE) and Large language models (LLMs)</strong>, with an emphasis on LLM4SE, and LLM Evaluation. She has published more than 20 papers at the top conferences and journals with total google scholar citations <a href='https://scholar.google.com/citations?user=UsLXSAEAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>, including ICSE, FSE, ASE, TOSEM, CAV, Usenix Security, AAAI, etc. She serves as a program committee member in top conferences such as ICSE, FSE, and ASE; a reviewer for top journals including TOSEM, TSE, EmSE, etc. 


# 🔥 News
- *2025.03.08*: Our 🤗<a href='https://huggingface.co/fm-universe'>Huggingface repo</a> reached 1.6k+ downloads. Contributions are welcomed 👉 <a href='https://huggingface.co/fm-universe'>[Link]</a> The Chinese <a href='https://mp.weixin.qq.com/s/oyhICTRo2fJL5MZkDrutXg'>article</a> has reached 37k+ reads👀 and 2k+ forwards↗️. Full paper 👉 <a href='https://arxiv.org/abs/2501.16207'>[Paper]</a>
- *2025.02.12*: &nbsp;🎉🎉 Our paper 📑 "SemBIC: Semantic-aware Identification of Bug-inducing Commits" has been accepted to **FSE 2025**. Congrats to Xiao!
- *2025.02.07*: &nbsp;🎉🎉 Honored to appear in CSE Department News page, titled "Dr. Jialun Cao Receives ACM SIGSOFT Outstanding Dissertation Award"!
- *2025.02.02*: &nbsp;🎉🎉 Our paper 📑 "A study on Prompt Design, Advantages and Limitations of ChatGPT for Deep Learning Program Repair" has been accepted to **JASE 2025**. Finally!
- *2025.01.23*: &nbsp;🎉🎉 Glad to receive the prestigious 🏆<a href='https://www2.sigsoft.org/awards/dissertation/'><strong>ACM SIGSOFT 2025 Outstanding Dissertation Award</strong></a>! 
- *2024.12.10*: &nbsp;🎉🎉 Our paper 📑 "<a href='https://arxiv.org/pdf/2408.13204'>DOMAINEVAL: An Auto-Constructed Benchmark for Multi-Domain Code Generation</a>" has been accepted to **AAAI 2025**. Congrats to Qiming!
- *2024.12.10*: &nbsp;🎉🎉 Our paper 📑 "<a href='https://arxiv.org/abs/2412.18216'>ICM-Assistant: Instruction-tuning Multimodal Large Language Models for Rule-based Explainable Image Content Moderation</a>" has been accepted to **AAAI 2025**. Congrats to Mengyang!


# 📝 Publications 

### 2025

📚 **Jialun Cao**, Meiziniu Li, Ming Wen, Shing-chi Cheung. *A study on prompt design, advantages and limitations of chatgpt for deep learning program repair*. In Journal of Automated Software Engineering (**ASEJ**). 🔗[[paper]](https://arxiv.org/abs/2304.08191)

📄 Xiao Chen, Hengcheng Zhu, **Jialun Cao (Corresponding)**, Ming Wen, Shing-Chi Cheung (Corresponding). *SemBIC: Semantic-aware Identification of Bug-inducing Commits*. In **FSE** 2025.

📄 Qiming Zhu, **Jialun Cao (Co-1st)**, Yaojie Lu, Hongyu Lin, Xianpei Han, Ben He, Le Sun, Shing-Chi Cheung. _DomainEval: An Auto-Constructed Benchmark for Multi-Domain Code Generation._ In **AAAI** 2025. 🔗[[Paper]](https://arxiv.org/pdf/2408.13204) 🎯[[Leaderboard]](https://domaineval.github.io/leaderboard.html) 💻 [[Github]](https://github.com/domaineval/DomainEval) 

📄 Mengyang Wu, Yuzhi Zhao, **Jialun Cao**, Mingjie Xu, zhongming jiang, Xuehui Wang, Qinbin Li, Guangneng Hu, Shengchao Qin, Chi-Wing Fu. _ICM-Assistant: Instruction-tuning Multimodal Large Language Models for Rule-based Explainable Image Content Moderation._ In AAAI 2025. 🔗[[Paper]](https://arxiv.org/abs/2412.18216)

📝 **Jialun Cao**, Yuk-Kit Chan*, Zixuan Ling* , Wenxuan Wang†, Shuqing Li, Mingwei Liu, Ruixi Qiao, Yuting Han, Chaozheng Wang, Boxi Yu, Pinjia He, Shuai Wang, Zibin Zheng, Michael R. Lyu, Shing-Chi Cheung. _How Should We Build A Benchmark? Revisiting 274 Code-Related Benchmarks For LLMs_ In arXiv 2025. 🔗[[Paper]](https://arxiv.org/pdf/2501.10711)

📝 **Jialun Cao**, Yaojie Lu, Meiziniu Li, Haoyang Ma, Haokun Li, Mengda He, Cheng Wen, Le Sun, Hongyu Zhang, Shengchao Qin, Shing-Chi Cheung, Cong Tian. _From Informal to Formal -- Incorporating and Evaluating LLMs on Natural Language Requirements to Verifiable Formal Proofs_ In arXiv 2025. 🔗[[Paper]](https://arxiv.org/abs/2501.16207) 🤗 [[Huggingface]](https://huggingface.co/fm-universe)


# 🎖 Honors and Awards
- *2025* ACM SIGSOFT Outstanding Doctoral Dissertation Award (1 or 2 award receivers worldwide per year)
- *2024* Shortlisted Participant for the Rising Stars Women in Engineering Workshop at Asian Deans' Forum
- *2024* Hong Kong Postgraduate Scholarship
- *2024* ACM SIGSOFT CAPS Travel Grant (ASE 2024)
- *2023* ACM SIGSOFT CAPS Travel Grant (ESEC/FSE 2023)
- *2019 - 2023*: Huawei Fellowship Scholarship
- *2017*: China National Scholarship (Postgraduate, Rank 1/106, Top 1%)
- *2014*: China National Scholarship (Undergraduate, Rank 1/52, Top 2%)


# 🎓 Educations
- *2019.09 - 2024.03*, **Ph.D**, The Hong Kong University of Science and Technology
- *2016.09 - 2019.06*, **M.S.**, State Key Laboratory of Computer Science, Institute of Software, Chinese Academy of Sciences
- *2012.09 - 2016.06*, **B.S.**, Shandong University


# 👩🏻‍💻 Working Experiment
- *2024.08 - now*, **Research Assistant Professor** at the Department of Computer Science and Engineering at The Hong Kong University of Science and Technology
- *2024.04 - 2024.07*, **Postdoctoral Fellow** at HKUST, working with <a href="https://www.cse.ust.hk/faculty/scc/">Prof. S.C. Cheung</a>


# 💬 Invited Talks
- *2025.01*, **From Benchmarks to Practice: A Preliminary Study on the Code Capabilities of Large Language Models.** In the Next Era of AI-assisted R&D Seminar (2025华为AI辅助研发Next研讨会) by Huawei, Hong Kong. 📽️[[Recording]](https://www.chaspark.com/#/live/1095803543143456768?videoId=1100606948265017344)
- *2024.11*, **Is Large Language Model a Rescue for Code Generation & Code Reasoning?** In Trusted Large Language Model Evaluation and Open-Source Technology Forum by CCF China Open Source Conference. 
- *2024.10*, **Exploring Automatic Testing and Verification for Software Programs using Large Language Models.** In High Trust Software Engineering Technology Laboratory, Guangzhou Research Institute, Xidian University.
- *2024.08*, **Trusted Architecture of Intelligent CPS Systems**. Micro-Forum of Intelligent Software Development hosted by Fudan University. 🔗 [[Link]](https://mp.weixin.qq.com/s/03JZNjTbinRYmDirEapBoA)
- *2024.08*, **Can AI be a Panacea for Software Reliability? Exploring Automatic Testing and Verification for Software Programs.** In the Software Systems Engineering Group at University College London.
- *2024.07*, **Concerned with Data Contamination? Assessing Countermeasures in Code Language Model**. In the IEEE World Congress on Service - Cloud & AI Symposium
- *2024.05*, **From Requirement to Formal Specification and Model Generation via Large Language Models** In the Formal Methods Committee Strategic Seminar (2024 CCF形式化方法专委会战略研讨会——形式化方法与人工智能的交叉融合：机遇与挑战) hosted in China Computer Federation (CCF). 📽️[[Recording]](https://www.chaspark.com/#/live/994058991643467776?videoId=1006392740579553280) 🪧[[News]](https://www.ccf.org.cn/Chapters/TC/News_/2024-05-12/821601.shtml)
- *2023.12*, **Crafting Future: A Dancer's Leap into Computer Science.** The 1st Forum for Women Scholars in Software Engineering hosted by ChinaSoft.
- 

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
