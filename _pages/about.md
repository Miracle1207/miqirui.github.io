---
permalink: /
title: "Qirui Mi (米祈睿)"
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

<div class="hero-tagline">
  <p class="tagline-text">Building intelligent agents that compute and learn the dynamics of economic systems.</p>
  <a href="mailto:miqirui2021@ia.ac.cn" class="cta-button">Contact Me</a>
  <span class="cta-email">miqirui2021@ia.ac.cn</span>
</div>
I am a final-year Ph.D. student at the Institute of Automation, Chinese Academy of Sciences (CASIA), working in [the Collective Decision Intelligence Lab](http://marl.ia.ac.cn/), supervised by [Prof. Jun Wang](http://www0.cs.ucl.ac.uk/staff/Jun.Wang/) and [Prof. Haifeng Zhang](https://pkuzhf.github.io/). During 2024–2025, I was a Visiting Ph.D. student at Nanyang Technological University (NTU), co-advised by [Prof. Bo An](https://personal.ntu.edu.sg/boan/). I closely collaborate with [Prof. Bo Li](https://liboecon.com/) from Peking University on research at the intersection of artificial intelligence and economics.

My technical background spans ``multi-agent systems``,`` reinforcement learning``, ``LLM-driven agents``, and ``collective decision-making``. I have extensive experience in **AI for Economics**, particularly **agent-based economic decision-making**, a direction I began pursuing when this intersection was still relatively underexplored. The core motivation is straightforward: *real-world economic systems are inherently large-scale multi-agent systems, making them a natural domain for multi-agent AI*.

<div class="research-intro">
  <p>My research agenda has two complementary directions: (1) <strong>AI for Economics</strong>: building <strong>economic world models</strong> that leverage AI to compute and forecast real-world economic dynamics, and solving for optimal policies that provide actionable insights for practice; and (2) <strong>Agent Economy</strong>: investigating how the rapid adoption of AI reshapes production, labor, and resource allocation, and designing governance mechanisms for AI's expanding economic role.</em></p>
</div>

<p class="highlight-announcement">🎉 I will be joining the School of Computer Science and Artificial Intelligence at <strong>Shanghai University of Finance and Economics (SUFE)</strong> as an <strong>Assistant Professor</strong> in August 2026. If you are interested in our research directions, feel free to <a href="mailto:miqirui2021@ia.ac.cn">contact me</a>.</p>

<span class='anchor' id='education'></span>

# 📖 Education

- **Ph.D. in Pattern Recognition and Intelligent Systems, [Institute of Automation, Chinese Academy of Sciences (CASIA)](http://www.ia.cas.cn/)**  
  Sep. 2021 – Jun. 2026, Beijing, China  
  Supervisor: [Prof. Jun Wang](http://www0.cs.ucl.ac.uk/staff/Jun.Wang/) and [Prof. Haifeng Zhang](https://pkuzhf.github.io)

- **Visiting Ph.D. in College of Computing and Data Science (CCDS), [Nanyang Technological University (NTU)](https://www.ntu.edu.sg/)**  
  Oct. 2024 – Aug. 2025, Singapore  
  Supervisor: [Prof. Bo An](https://personal.ntu.edu.sg/boan/)

<span class='anchor' id='research-directions'></span>

# 🔬 Research Directions

<div class="research-grid">
<div class="research-card">
  <h3>🌍 Economic World Model</h3>
  <p>An internal model that simulates and predicts economic dynamics emerging from multi-agent interactions, enabling agents to make rational decisions under resource constraints.</p>
  <div class="research-card-papers">
    <a href="https://miracle1207.github.io/econgym_page/" class="research-tag">EconGym <small>(NeurIPS'25)</small></a>,
    <a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p1390.pdf" class="research-tag">TaxAI <small>(AAMAS'24 Oral)</small></a>
  </div>
</div>



<div class="research-card">
  <h3>🏙️ Social Simulation</h3>
  <p>Leveraging large language model agents to simulate population-level decision dynamics and emergent social phenomena, bridging computational models with realistic human behavior.</p>
  <div class="research-card-papers">
    <a href="https://neurips.cc/virtual/2025/loc/san-diego/poster/116242" class="research-tag">MF-LLM <small>(NeurIPS'25)</small></a>,
    <a href="https://neurips.cc/virtual/2025/loc/san-diego/poster/121445" class="research-tag">EconGym <small>(NeurIPS'25)</small></a>
  </div>
</div>

<div class="research-card">
  <h3>👥 Multi-Agent Systems</h3>
  <p>Designing algorithms for multi-agent games, with a particular focus on large-scale multi-agent systems and the complex decision-making problems that arise in economic environments.</p>
  <div class="research-card-papers">
    <a href="https://arxiv.org/abs/2403.12093" class="research-tag">DSMFG <small>(ECAI'25)</small></a>,
    <a href="https://arxiv.org/abs/2511.12876" class="research-tag">LAMP <small>(AAAI'26)</small></a>,
    <a href="https://arxiv.org/abs/2404.09324" class="research-tag">AMFCE <small>(AAMAS'25)</small></a>
  </div>
</div>

<div class="research-card">
  <h3>🧠 Agent Evolution</h3>
  <p>Enabling agents to evolve their capabilities autonomously by accumulating experience through environmental interaction.</p>
  <div class="research-card-papers">
    <a href="https://arxiv.org/abs/2602.01869" class="research-tag research-tag-highlight">Skill-Pro <small>(ICML'26 Spotlight)</small></a>
  </div>
</div>

</div>


# 🔥 News

<div class="headline-news">
  <div class="headline-label">Highlight · May 2026</div>
  <h3>Successfully passed my PhD defense! 🎓</h3>
  <p>A wonderful conclusion to five years of doctoral study at CASIA.</p>
</div>

<div class="headline-news">
  <div class="headline-label">Highlight · Apr 2026</div>
  <h3>Skill-Pro accepted to ICML 2026 as Spotlight (top 2.6%)</h3>
  <p>Learning reusable skills from experience via non-parametric PPO for LLM agents.</p>
  <div class="headline-links">
    <a href="https://arxiv.org/abs/2602.01869">Paper →</a>
    <a href="https://icml.cc/virtual/2026/poster/65830">ICML pages →</a>
  </div>
</div>

- **2025.12**: Attended [NeurIPS 2025](https://neurips.cc/) in San Diego, United States.
- **2025.11**: Attended the [5th Workshop on Network Economics and Game Theory](https://mp.weixin.qq.com/s/oSSoEfwzSyrEQmZ8h84Slw).
- **2025.11**: Our paper was accepted to AAAI 2026: [*Think, Speak, Decide: Language-Augmented Multi-Agent Reinforcement Learning for Economic Decision-Making*](https://arxiv.org/abs/2511.12876).
- **2025.9**: Two papers were accepted to NeurIPS 2025: 
  - [*EconGym: A Scalable AI Testbed with Diverse Economic Tasks*](https://www.arxiv.org/pdf/2506.12110);
  - [*MF-LLM: Simulating Population Decision Dynamics via a Mean-Field Large Language Model Framework*](https://arxiv.org/abs/2504.21582).
- **2025.7**: Our paper was accepted to ECAI 2025: [*Learning Macroeconomic Policies through Dynamic Stackelberg Mean-Field Games*](https://arxiv.org/abs/2403.12093).
- **2025.6**: We released [**EconGym**](https://www.arxiv.org/pdf/2506.12110), a unified simulation platform bridging economics and AI, covering 25+ real-world economic tasks. 🌐 [website](https://miracle1207.github.io/econgym_page/)
- **2025.5**: Attended [AAMAS 2025](https://aamas2025.org/) and gave talks on the AAMAS Competition and our accepted paper [*Mean Field Correlated Imitation Learning*](https://arxiv.org/abs/2404.09324).
- **2025.5**: Our [AAMAS 2025 Computational Economic Competition](http://jidiai.cn/aamas_tax_2025/) has successfully concluded!
- **2025.5**: Released our new paper [*MF-LLM: Simulating Population Decision Dynamics via a Mean-Field Large Language Model Framework*](https://arxiv.org/abs/2504.21582).
- **2025.3**: Our [AAMAS 2025 Computational Economic Competition](http://jidiai.cn/aamas_tax_2025/) has officially started!
- **2025.2**: Our competition proposals were accepted by [AAMAS 2025](https://aamas2025.org/).
- **2024.12**: Attended the [4th Workshop on Network Economics and Game Theory](https://asleepx.github.io/Workshop/).
- **2024.12**: Our paper was accepted to AAMAS 2025: [*Mean Field Correlated Imitation Learning*](https://arxiv.org/abs/2404.09324).
- **2024.10**: Started a visiting position in Prof. Bo An's group.
- **2024.5**: Attended [AAMAS 2024](https://www.aamas2024-conference.auckland.ac.nz/) and gave an oral presentation.




<span class='anchor' id='selected-publications'></span>

# 📝 Selected Publications  

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge badge-spotlight">ICML 2026 Spotlight</div>
      <img src='images/publications/SkillPro.png' alt="Skill-Pro" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Skill-Pro: Learning Reusable Skills from Experience via Non-Parametric PPO for LLM Agents**

**Qirui Mi**, Zhijian Ma, Mengyue Yang, Haoxuan Li, Yisen Wang, Haifeng Zhang, Jun Wang

  [Paper](https://arxiv.org/abs/2602.01869), [Github](https://github.com/Miracle1207/Skill-Pro)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2025</div>
      <img src='images/publications/EconGym.png' alt="EconGym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **EconGym: A Scalable AI Testbed with Diverse Economic Tasks**

  **Qirui Mi**, Qipeng Yang, Zijun Fan, Wentian Fan, Heyang Ma, Chengdong Ma, Siyu Xia, Bo An, Jun Wang, Haifeng Zhang*

  [Paper](https://www.arxiv.org/pdf/2506.12110), [Website](https://miracle1207.github.io/econgym_page/), [Github](https://github.com/Miracle1207/EconGym)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2025</div>
      <img src='images/publications/mf_llm.png' alt="MF-LLM" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **MF-LLM: Simulating Population Decision Dynamics via a Mean-Field Large Language Model Framework**

  **Qirui Mi**, Mengyue Yang, Xiangning Yu, Zhiyu Zhao, Cheng Deng, Bo An, Haifeng Zhang*, Xu Chen*, Jun Wang*

  [Paper](https://arxiv.org/abs/2504.21582), [Github](https://github.com/Miracle1207/Mean-Field-LLM)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">AAAI 2026</div>
      <img src='images/publications/LAMP.png' alt="LAMP" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Think, Speak, Decide: Language-Augmented Multi-Agent Reinforcement Learning for Economic Decision-Making**

  Heyang Ma†, **Qirui Mi†**, Qipeng Yang, Zijun Fan, Bo Li, Haifeng Zhang*

  [Paper](https://arxiv.org/abs/2511.12876)
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ECAI 2025</div>
      <img src='images/publications/SMFG.png' alt="SMFG" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Learning Macroeconomic Policies through Dynamic Stackelberg Mean-Field Games**

  **Qirui Mi**, Zhiyu Zhao, Siyu Xia, Yan Song, Jun Wang, Haifeng Zhang*

  [Paper](https://arxiv.org/abs/2403.12093)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">AAMAS 2025</div>
      <img src='images/publications/AMFCE_AAMAS25.png' alt="AMFCE" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Mean Field Correlated Imitation Learning**

  Zhiyu Zhao, **Qirui Mi**, Ning Yang, Xue Yan, Haifeng Zhang, Jun Wang, Yaodong Yang

  [Paper](https://arxiv.org/abs/2404.09324)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2024</div>
      <img src='images/publications/starcraft_LLM.png' alt="StarCraft LLM" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Large Language Models Play StarCraft II: Benchmarks and a Chain of Summarization Approach**

  Weiyu Ma, **Qirui Mi**, Yongcheng Zeng, Xue Yan, Yuqiao Wu, Runji Lin, Haifeng Zhang, Jun Wang*

  [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/f0ebc318e2df08360b2df559e81602e5-Abstract-Conference.html)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge badge-oral">AAMAS 2024 (Oral)</div>
      <img src='images/publications/TaxAI_AAMAS24.png' alt="TaxAI" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **TaxAI: A Dynamic Economic Simulator and Benchmark for Multi-Agent Reinforcement Learning**

  **Qirui Mi**, Siyu Xia, Yan Song, Haifeng Zhang, Shenghao Zhu, Jun Wang*

  [Paper](https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p1390.pdf), [Github](https://github.com/jidiai/TaxAI)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">GLOBECOM 2021</div>
      <img src='images/publications/joint_cache.png' alt="Joint Caching" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Joint Caching and Transmission in the Mobile Edge Network: A Multi-Agent Learning Approach**

  **Qirui Mi**, Ning Yang, Haifeng Zhang, Haijun Zhang, Jun Wang

  [Paper](https://ieeexplore.ieee.org/abstract/document/9685590)

  </div>
</div>


<span class='anchor' id='invited-talks'></span>

# 🎤 Invited Talks

- **AI Agents for Economic Decision-Making: Simulation and Policy Optimization**  
  Beijing Institute for General Artificial Intelligence (BIGAI), 2025.12  
  *Invited by Prof. Xue Feng*.

- **AI Agents for Economic Decision-Making: Simulation and Policy Optimization**  
  School of Statistics and Data Science, Shanghai University of Finance and Economics (SUFE), 2025.11  
  *Invited by Prof. Zhiheng Zhang*. [link](https://mp.weixin.qq.com/s/BR-ViylLEfajl9PQU3DIag)

- **AI Agents for Economic Decision-Making: Simulation and Policy Optimization**  
  School of Computer and Artificial Intelligence, Shanghai University of Finance and Economics (SUFE), 2025.11  
  [link](https://mp.weixin.qq.com/s/UOfA07YrIsvB4tgiGgNJ3Q)

- **EconGym: A Scalable AI Testbed with Diverse Economic Tasks**  
  [Conference on Machine Learning in Economics](https://liboecon.com/program.html), Peking University, 2025.6  
  *Invited by Prof. Bo Li*.

- **Game-Theoretic Agents for Economic and Social Governance**  
  [Dadao Forum (大道论坛)](../images/publications/shandong_talk.png), Shandong Institute of Business and Technology, 2025.03  
  *Invited by Prof. Chongjin Wang*.

- **Game-Theoretic Agents for Economic Problems**  
  Shanghai Jiao Tong University ([JHC Lecture Series](https://mp.weixin.qq.com/s/sHpYNGbdhmb1I_BALd9NXg)), 2024.12  
  *Invited by Prof. Ying Wen*.

- **Game-Theoretic Agents for Economic Problems**  
  Fudan University, 2024.12  
  *Invited by Prof. Zhongyu Wei*.

- **TaxAI: A Dynamic Economic Simulator and Benchmark for Multi-Agent Reinforcement Learning**  
  International Conference on Distributed Artificial Intelligence (DAI 2024), 2024.12


# 🏆 Awards
* Outstanding Student Leader · 2024
* Outstanding Merit Student · 2023
* Outstanding Graduate of Beijing Colleges and Universities · 2021
* Outstanding Undergraduate Thesis of Beijing Colleges and Universities · 2021
* Meritorious Winner, Mathematical Contest in Modeling (MCM), USA · 2019
* Second Prize, 10th 'Challenge Cup' Academic and Technological Works Competition for Beijing College Students · 2019
