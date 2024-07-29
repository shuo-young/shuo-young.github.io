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

I'm currently a second-year Ph.D. student at the School of Software Engineering, Sun Yat-sen University. 

I am under the supervision of <a href='http://www.zibinzheng.com/cv'>Prof. Zibin Zheng (郑子彬)</a> and <a href='https://jiachi-chen.github.io/'>Dr. Jiachi Chen (陈嘉弛)</a> at <a href='http://www.inpluslab.com'>InPlusLab</a> since Aug. 2021. 

My research interests include software security and empirical study (especially for smart contracts), static analysis, and LLM. I have published 5 papers at the top (CCF-A) international Software Engineering/Security conferences/journals such as ICSE, ISSTA, TOSEM, TIFS.

 <!-- with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.07*: &nbsp;🎉 One paper is accepted by ICSE 2025
- *2024.05*: &nbsp;🎉 One paper is accepted by TOSEM
- *2023.12*: &nbsp;🎉 One paper is accepted by TIFS
- *2023.10*: &nbsp;🎉 I win the President Scholarship for Doctoral Students of SYSU
- *2023.10*: &nbsp;🎉 One paper is accepted by ICSE 2024 
- *2023.08*: I join LightYear Security Lab, AntGroup as a research intern in Hangzhou, China
- *2023.04*: &nbsp;🎉 One paper is accepted by ISSTA 2023

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICSE 2025</div><img src='images/hyperion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Hyperion: Unveiling DApp Inconsistencies using LLM and Dataflow-Guided Symbolic Execution (Accepeted by ICSE 2025 Early Cycle!)

**Shuo Yang**, Xingwei Lin, Jiachi Chen, Qingyuan Zhong, Lei Xiao, Renke Huang, Yanlin Wang, Zibin Zheng

[**Project**](https://github.com/shuo-young/Hyperion)
- [Hyperion](https://github.com/shuo-young/Hyperion) is the first work that unveils 7 types of inconsistencies between DApp frontend description and backend smart contracts
- Combined techniques with LLM and program analysis
- Contract IR-based symbolic execution guided by preliminary dataflow analysis
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICSE 2024</div><img src='images/blockwatchdog.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Uncover the Premeditated Attacks: Detecting Exploitable Reentrancy Vulnerabilities by Identifying Attacker Contracts](https://arxiv.org/abs/2403.19112)

**Shuo Yang**, Jiachi Chen, Mingyuan Huang, Zibin Zheng, Yuan Huang

[**Project**](https://github.com/shuo-young/BlockWatchdog) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- [BlockWatchdog](https://github.com/shuo-young/BlockWatchdog)<img alt="GitHub forks" src="https://img.shields.io/github/stars/shuo-young/BlockWatchdog" style="margin: 0 3px"/> is the first work to identify reentrancy attacker contracts based on static dataflow analysis
- We provide the rust implementation [Lydia](https://github.com/shuo-young/lydia) (>10% faster)<img alt="GitHub forks" src="https://img.shields.io/github/stars/shuo-young/lydia" style="margin: 0 3px"/>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISSTA 2023</div><img src='images/nftguard.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Definition and Detection of Defects in NFT Smart Contracts](https://dl.acm.org/doi/10.1145/3597926.3598063)

**Shuo Yang**, Jiachi Chen, Zibin Zheng

[**Project**](https://github.com/NFTDefects/nftdefects)
- [NFTGuard](https://github.com/NFTDefects/nftdefects)<img alt="GitHub forks" src="https://img.shields.io/github/stars/NFTDefects/nftdefects" style="margin: 0 3px"/> is the first work to define and detect the 5 defects in NFT smart contracts
</div>
</div>

- `TOSEM` [FunFuzz: A Function-oriented Fuzzer for Smart Contract Vulnerability Detection with High Effectiveness and Efficiency](https://dl.acm.org/doi/abs/10.1145/3674725), Mingxi Ye, Yuhong Nan, Hong-Ning Dai, **Shuo Yang**, Zibin Zheng, Xiapu Luo. 
- `TIFS` [Towards Understanding Asset Flows in Crypto Money Laundering Through the Lenses of Ethereum Heist](https://ieeexplore.ieee.org/document/10371347), Jiajing Wu, Dan Lin, Qishuang Fu, **Shuo Yang**, Ting Chen, Zibin Zheng, Bowen Song. 


# 🎖 Honors and Awards
- *2023.10* President Scholarship for Doctoral Students
- *2023.09* 1st prize of China Service Computing Innovation Contest
- *2023.04* 8th Place at Numen Cyper CTF (Capture-The-Flag)
- *2021.06* 3rd Prize of Competition of Service Outsourcing and Entrepreneurship Innovation
- *2021.05* 3rd Prize of Chinese Undergraduate Internet Software Design Competition
- *2020.06* 3rd Prize of Competition of Service Outsourcing and Entrepreneurship Innovation
- *2019.08* 2nd Prize of Chinese Undergraduate Computer Design Contest

# 📖 Educations
- *2022.06 - now*, Phd, Sun Yat-sen University, Zhuhai. 
- *2018.09 - 2022.06*, Undergraduate, Zhongnan University of Economics and Law, Wuhan.
- *2015.09 - 2018.06*, Hubei Wuchang Experimental High School, Wuhan. 

# 💬 Invited Talks
- *2024.04*, ICSE 2024 oral presentation, Lisbon, Portugal
- *2024.02*, ICSE'24 accepted papers symposium held by CCF Software Engineering Committee, Virtual
- *2023.07*, ISSTA 2023 oral presentation, Seattle, USA

# 💻 Internships
- *2023.08 - 2024.01*, [LightYear Security Lab, AntGroup](https://www.antgroup.com/en), Hangzhou.
- *2021.10 - 2022.01*, [R&D of blockchain underlying platform, Webank](https://www.webank.com/), Shenzhen.
- *2021.07 - 2021.08*, [YGSoft](https://www.ygsoft.com/), Wuhan.

# 🔧 Skills
- English: IELTS 7.0, GRE 321+4.0, CET6 566, CET4 626
- Programming Language: Python, Java, Solidity, Rust, C/C++, JavaScript