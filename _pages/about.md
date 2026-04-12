---
permalink: /
title: ""
excerpt: ""
author_profile: false
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

<div class="profile-section">
  <div class="profile-photo">
    <img src="images/android-chrome-512x512.png" alt="Yuhan Liu">
  </div>
  <div class="profile-info">
    <h1 class="profile-name">Yuhan Liu</h1>
    <p class="profile-title">Postdoctoral Research Fellow</p>
    <p class="profile-affiliation">Machine Learning Department, MBZUAI</p>
    <p class="profile-affiliation">Mohamed bin Zayed University of Artificial Intelligence</p>
    <p class="profile-location">Abu Dhabi, UAE</p>
    <div class="profile-links">
      <a href="mailto:yuhan.liu@mbzuai.ac.ae" title="Email"><i class="fas fa-envelope"></i></a>
      <a href="mailto:liuyuhaning@gmail.com" title="Gmail"><i class="fas fa-envelope"></i></a>
      {% if site.author.googlescholar %}<a href="{{ site.author.googlescholar }}" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>{% endif %}
      {% if site.author.github %}<a href="https://github.com/{{ site.author.github }}" title="GitHub"><i class="fab fa-github"></i></a>{% endif %}
      {% if site.author.linkedin %}<a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" title="LinkedIn"><i class="fab fa-linkedin"></i></a>{% endif %}
      {% if site.author.twitter %}<a href="https://twitter.com/{{ site.author.twitter }}" title="Twitter"><i class="fab fa-twitter"></i></a>{% endif %}
      {% if site.author.dblp %}<a href="{{ site.author.dblp }}" title="DBLP"><i class="ai ai-dblp"></i></a>{% endif %}
      {% if site.author.orcid %}<a href="{{ site.author.orcid }}" title="ORCID"><i class="ai ai-orcid"></i></a>{% endif %}
    </div>
    <p class="profile-bio">
      I am currently a Postdoctoral Research Fellow at the Machine Learning Department of MBZUAI, working with <a href="https://nilslukas.github.io">Dr. Nils Lukas</a>, <a href="https://lahlou.org">Dr. Salem Lahlou</a>, and <a href="https://mtakac.com">Dr. Martin Takac</a>. I received my Ph.D. in Artificial Intelligence from <a href="http://ai.ruc.edu.cn">Gaoling School of Artificial Intelligence</a>, Renmin University of China (2021-2025), supervised by Prof. <a href="http://ai.ruc.edu.cn/english/GSAI_FACULTY/28026f7425324f61991c70d279372d13.htm">Rui Yan</a>. Prior to RUC, I earned my M.S. in Mathematics and B.S. in Automation from China University of Petroleum (Beijing).
    </p>
  </div>
</div>

<div class="highlight-box">
<strong>I am on the 2026 Fall job market, actively seeking faculty and postdoctoral positions.</strong> Feel free to reach out at <a href="mailto:liuyuhaning@gmail.com">liuyuhaning@gmail.com</a>.
</div>

## Research Interests
{: #research}

My research focuses on **building safe and secure Agentic AI**, including:

- **Responsible Agentic Systems**: How to build safe and secure agentic systems
- **Fake News and Social Systems**: Investigating the use of LLMs in addressing the propagation of fake news and their role in social dynamics
- **Vision-Language Models and Reasoning**: Exploring complex reasoning paradigms in VLMs and their applications
- **Societal Challenges of LLMs**: Exploring issues such as hallucination, hate speech, bias, and the alignment of LLMs with societal norms

## News
{: #news}

<div class="news-list">
<ul>
<li><span class="news-date">2026.01</span> One paper accepted by <strong>ICLR 2026</strong> (Rio de Janeiro, Brazil)</li>
<li><span class="news-date">2025.11</span> Awarded a <strong>DAAD fellowship</strong></li>
<li><span class="news-date">2025.10</span> Invited to serve as <span class="highlight-text">Area Chair</span> for ACL Rolling Review</li>
<li><span class="news-date">2025.08</span> Three papers accepted by <strong>EMNLP 2025</strong> (Suzhou, China)</li>
<li><span class="news-date">2025.08</span> Joined <strong>MBZUAI</strong> as a Postdoctoral Research Fellow of Machine Learning</li>
<li><span class="news-date">2025.07</span> Attending <strong>ACL 2025</strong> in Vienna</li>
<li><span class="news-date">2025.05</span> Successfully defended my <strong>PhD thesis</strong></li>
<li><span class="news-date">2025.05</span> Three papers accepted by <strong>ACL 2025</strong> (Vienna, Austria)</li>
<li><span class="news-date">2025.05</span> Two papers accepted by <strong>SIGIR 2025</strong> (Padua, Italy)</li>
<li><span class="news-date">2024.12</span> Won the <strong>Gold Medal</strong> in the Tencent Multi-Agent Application Competition (Rank 1/210)</li>
<li><span class="news-date">2024.08</span> Attending <strong>IJCAI 2024</strong> in South Korea</li>
<li><span class="news-date">2024.07</span> Invited to serve as <span class="highlight-text">Session Chair</span> for IJCAI 2024 NLP Track</li>
<li><span class="news-date">2024.05</span> One paper accepted by <strong>IJCAI 2024</strong> (<span class="highlight-text">Oral</span>)</li>
<li><span class="news-date">2024.05</span> Attending <strong>COLING 2024</strong> in Italy</li>
<li><span class="news-date">2024.05</span> Attending <strong>WWW 2024</strong> in Singapore</li>
<li><span class="news-date">2024.02</span> One paper accepted by <strong>COLING 2024</strong> (Turin, Italy)</li>
<li><span class="news-date">2024.02</span> Selected as a delegate for the RUC-Yale "Artificial Intelligence, Emerging Technologies" International Forum</li>
<li><span class="news-date">2024.01</span> One paper accepted by <strong>The Web Conference 2024</strong> (Singapore)</li>
</ul>
</div>

## Publications
{: #publications}

<p class="pub-note"><code>*</code> indicates co-corresponding author</p>

<div class="pub-list">

<div class="pub-row">
  <div class="pub-venue">EMNLP 2025</div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://arxiv.org/abs/2410.19064">The Stepwise Deception: Simulating the Evolution from True News to Fake News with LLM Agents</a></div>
    <div class="pub-authors"><strong>Yuhan Liu</strong>, Zirui Song, Juntian Zhang, Xiaoqing Zhang, Xiuying Chen, Rui Yan</div>
    <div class="pub-extra"><span class="highlight-text">Oral</span></div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">SIGIR 2025</div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://arxiv.org/abs/2505.08532">The Truth Becomes Clearer Through Debate! Multi-Agent Systems with Large Language Models Unmask Fake News</a></div>
    <div class="pub-authors"><strong>Yuhan Liu</strong>, Yuxuan Liu, Xiaoqing Zhang, Xiuying Chen, Rui Yan</div>
    <div class="pub-extra"><span class="highlight-text">Oral</span></div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">EMNLP 2025</div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://arxiv.org/abs/2502.10708">Injecting Domain-Specific Knowledge into Large Language Models: A Comprehensive Survey</a></div>
    <div class="pub-authors">Zirui Song, Bin Yan, <strong>Yuhan Liu</strong>, Miao Fang, Mingzhe Li, Rui Yan, Xiuying Chen</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">EMNLP 2025</div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://arxiv.org/abs/2505.16429">Beyond Static Testbeds: An Interaction-Centric Agent Simulation Platform for Dynamic Recommender Systems</a></div>
    <div class="pub-authors">Song Jin, Juntian Zhang, <strong>Yuhan Liu*</strong>, Xun Zhang, Yufei Zhang, Guojun Yin, Fei Jiang, Wei Lin, Rui Yan*</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">ACL 2025</div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://arxiv.org/abs/2504.20199">Weaving Context Across Images: Improving Vision-Language Models through Focus-Centric Visual Chains</a></div>
    <div class="pub-authors">Juntian Zhang, Chuanqi Cheng, <strong>Yuhan Liu*</strong>, Wei Liu, Jian Luan, Rui Yan*</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">ACL 2025</div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://aclanthology.org/2025.findings-acl.1195.pdf">Thinking Before Running! Efficient Code Generation with Thorough Exploration and Optimal Refinement</a></div>
    <div class="pub-authors">Xiaoqing Zhang, <strong>Yuhan Liu*</strong>, Flood Sung, Xiuying Chen, Rui Yan*</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">ACL 2025</div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://aclanthology.org/2025.acl-long.1475/">More is not always better? Enhancing Many-Shot In-Context Learning with Differentiated and Reweighting Objectives</a></div>
    <div class="pub-authors">Xiaoqing Zhang, Ang Lv, <strong>Yuhan Liu</strong>, Xiuying Chen, Rui Yan</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">SIGIR 2025</div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://dl.acm.org/doi/10.1145/3726302.3730334">SAGraph: A Large-Scale Social Graph Dataset with Comprehensive Context for Influencer Selection in Marketing</a></div>
    <div class="pub-authors">Xiaoqing Zhang, <strong>Yuhan Liu</strong>, Jianzhou Wang, Zhenxing Hu, Xiuying Chen, Rui Yan</div>
    <div class="pub-extra"><span class="highlight-text">Oral</span></div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">VLDB 2025</div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://www.vldb.org/2025/Workshops/VLDB-Workshops-2025/DATAI/DATAI25_9.pdf">SoAgent: A Real-world Data Empowered Agent Pool to Facilitate LLM-Driven Generative Social Simulation</a></div>
    <div class="pub-authors">Na Ta, Kaiyu Li, Yushu Zhou, <strong>Yuhan Liu</strong></div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">IJCAI 2024</div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://arxiv.org/abs/2403.09498">From Skepticism to Acceptance: Simulating the Attitude Dynamics Toward Fake News</a></div>
    <div class="pub-authors"><strong>Yuhan Liu</strong>, Xiuying Chen, Xiaoqing Zhang, Xing Gao, Ji Zhang, Rui Yan</div>
    <div class="pub-extra"><span class="highlight-text">Oral</span>, Human-Centred AI Track, <span class="highlight-text">4% acceptance rate</span></div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">COLING 2024</div>
  <div class="pub-text">
    <div class="pub-title">IAD: In-Context Learning Ability Decoupler of Large Language Models in Meta-Training</div>
    <div class="pub-authors"><strong>Yuhan Liu</strong>, Xiuying Chen, Xing Gao, Ji Zhang, Rui Yan</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">WWW 2024</div>
  <div class="pub-text">
    <div class="pub-title">Bridging the Space Gap: Unifying Geometry Knowledge Graph Embedding with Optimal Transport</div>
    <div class="pub-authors"><strong>Yuhan Liu</strong>, Zelin Cao, Xing Gao, Ji Zhang, Rui Yan</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">CCL 2023</div>
  <div class="pub-text">
    <div class="pub-title">Unleashing the power of large models: Exploring human-machine conversations</div>
    <div class="pub-authors"><strong>Yuhan Liu</strong>, Xiuying Chen, Rui Yan</div>
    <div class="pub-extra"><span class="highlight-text">Oral</span></div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">ICLR 2026</div>
  <div class="pub-text">
    <div class="pub-title">Paper at ICLR 2026</div>
    <div class="pub-authors"><strong>Yuhan Liu</strong> et al.</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">Preprint</div>
  <div class="pub-text">
    <div class="pub-title">Pastiche Novel Generation: Creating Fan Fiction You Love in Your Favorite Author's Style</div>
    <div class="pub-authors">Xueran Han, <strong>Yuhan Liu</strong>, Mingzhe Li, Wei Liu, Sen Hu, Rui Yan, Zhiqiang Xu, Xiuying Chen</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">Preprint</div>
  <div class="pub-text">
    <div class="pub-title">A large-scale time-aware agents simulation for influencer selection in digital advertising campaigns</div>
    <div class="pub-authors">Xiaoqing Zhang, <strong>Yuhan Liu</strong>, Jianzhou Wang, Zhenxing Hu, Xiuying Chen, Rui Yan</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">AMC</div>
  <div class="pub-text">
    <div class="pub-title">A quasi fractional order gradient descent method with adaptive stepsize and its application in system identification</div>
    <div class="pub-authors">Jianjun Liu, <strong>Yuhan Liu</strong>, et al.</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-venue">Info. Sci.</div>
  <div class="pub-text">
    <div class="pub-title">Clustering based on grid and local density with priority-based expansion for multi-density data</div>
    <div class="pub-authors">Jianjun Liu, <strong>Yuhan Liu</strong>, et al.</div>
  </div>
</div>

</div>

## Honors and Awards
{: #awards}

- **2024** &mdash; "Qiushi Academic-Dongliang" Academic Project Funding, RUC
- **2022, 2023, 2024** &mdash; Merit Student, RUC
- **2017, 2020, 2025** &mdash; Outstanding Graduate, Beijing
- **2019-2020** &mdash; National Scholarship

## Academic Services
{: #services}

- **Session Chair**: IJCAI 2024 NLP Track (Jeju, Republic of Korea)
- **Area Chair**: ACL Rolling Review
- **Reviewer**: ACL, EMNLP, ICLR, WWW, ACL Rolling Review
- **Program Committee**: AAAI, IJCAI
- **Journal Reviewer**: *IEEE Transactions on Artificial Intelligence*, *Information Sciences*, *Financial Innovation*

## Invited Talks
{: #talks}

- **2025.05** &mdash; True Yet False: Large Language Model-based Multi-Agent Systems for Enhanced Security, XiaMen University
- **2025.04** &mdash; Large Language Model-Based Multi-Agent System for Fake News, School of Journalism and Communication, Renmin University of China
- **2024.08** &mdash; From Skepticism to Acceptance: Simulating the Attitude Dynamics Toward Fake News, Microsoft Research Asia

## Experience
{: #experience}

- **2024.11 - 2025.06** &mdash; MeiTuan, Beijing
- **2022.09 - 2024.11** &mdash; Alibaba Damo Academy, Beijing
- **2020.07 - 2021.08** &mdash; Xiaomi Tech, Beijing
- **2019.06 - 2019.09** &mdash; Sinovation Ventures, Beijing
- **2019.03 - 2019.06** &mdash; Lenovo Corporate Research, Beijing
- **2018.05 - 2018.09** &mdash; Tencent WeChat, Beijing

## Teaching
{: #teaching}

- **2024 Spring, 2022 Spring** &mdash; Natural Language Processing
- **2019 Fall** &mdash; Applied Statistical Methods
- **2019 Spring** &mdash; Optimization Algorithm
- **2019 Fall, 2017 Fall** &mdash; Stochastic Process
- **2018 Fall** &mdash; Advanced Algebra
- **2018 Spring** &mdash; Advanced Mathematics

## Best Friends
{: #friends}

Thanks to my best friends! Your help and encouragement are my greatest motivation, and I look forward to creating a better future with all of you!

- <a href="https://iriscxy.github.io/">Xiuying Chen</a> &mdash; Assistant Professor at MBZUAI
- <a href="https://wuyichen-97.github.io/">Yichen Wu</a> &mdash; Postdoctor at Harvard
- <a href="https://scholar.google.com/citations?user=K-6vOfkAAAAJ&hl=zh-CN">Juntian Zhang</a> &mdash; Master's student at Renmin University of China
- <a href="https://trestad.github.io/">Ang Lv</a> &mdash; Ph.D. Candidate at Renmin University of China and Interning at ByteDance Top Seed
- <a href="https://www.linkedin.com/in/bowen-li-5a3610344/">Bowen Li</a> &mdash; Ph.D. Candidate at Tsinghua University and visiting at University of Twente
