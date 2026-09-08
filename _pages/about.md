---
layout: about
title: about
permalink: /

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false

selected_papers: false
social: true

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

I am a Ph.D. candidate at the School of Software Engineering, [Sun Yat-sen University](https://www.sysu.edu.cn/) (中山大学), advised by [Prof. Zibin Zheng](http://www.zibinzheng.com/cv) (郑子彬) and [Dr. Jiachi Chen](https://jiachi-chen.github.io/) (陈嘉弛) since September 2022. I expect to graduate in June 2027.

My research interests include:

- **AI for Security**: AI-assisted security analysis for Web3 (smart contracts, blockchain clients, on-chain txs, etc.) and complex software systems.
- **AI Agent Security**: Security and trustworthiness of autonomous agents and AI-native systems.
- **AI for Program Analysis**: Combining AI with program analysis for software understanding, testing, and security.

My work includes 8 papers published at top-tier (CCF-A) venues, including **ICSE**, **ISSTA**, **USENIX Security**, **TOSEM**, **TSE**, and **TIFS**.
Beyond academic research, ongoing work includes real-world vulnerability discovery, PoC development, and open-source security tooling. Selected projects include [![X Views](https://img.shields.io/badge/X%2FTwitter_Defi__Nerd__sec-300k%2B%20views-white?logo=x&style=social&logoColor=gray)](https://x.com/Defi_Nerd_sec), and [DarkNavySecurity/web3-skills](https://github.com/DarkNavySecurity/web3-skills) ![GitHub stars](https://img.shields.io/github/stars/DarkNavySecurity/web3-skills).

<div class="clearfix"></div>

## <a href="{{ '/news/' | relative_url }}" style="color: inherit">news</a>

{% include news.liquid limit=true %}

## security highlights

<div class="security-highlights mb-4">
  <div class="mb-2">
    <strong>$22,800+</strong> in rewards from <a href="https://immunefi.com/">Immunefi</a> Web3 bug bounties.
  </div>
  <div class="mb-2">
    PoCs of <strong>10 previously uncovered attacks</strong> confirmed by <a href="https://github.com/SunWeb3Sec/DeFiHackLabs">DeFiHackLabs</a> <a href="https://github.com/SunWeb3Sec/DeFiHackLabs"><img src="https://img.shields.io/github/stars/SunWeb3Sec/DeFiHackLabs" alt="GitHub stars for DeFiHackLabs" style="vertical-align: middle;"></a>.
  </div>
  <div class="mb-2">
    <strong>Two prompt-leak vulnerabilities</strong> were confirmed by the developers of two <a href="https://chatgpt.com/gpts">GPTs</a>, who adopted our prompt-protection method.
  </div>
  <div class="mb-2">
    Confirmed issues in <a href="https://github.com/Uniswap/v4-periphery">Uniswap V4 Periphery</a> <a href="https://github.com/Uniswap/v4-periphery"><img src="https://img.shields.io/github/stars/Uniswap/v4-periphery" alt="GitHub stars for Uniswap V4 Periphery" style="vertical-align: middle;"></a> and <a href="https://github.com/saucepoint/v4-stoploss">Stop Loss Orders with Uniswap V4 Hooks</a> <a href="https://github.com/saucepoint/v4-stoploss"><img src="https://img.shields.io/github/stars/saucepoint/v4-stoploss" alt="GitHub stars for Stop Loss Orders with Uniswap V4 Hooks" style="vertical-align: middle;"></a>.
  </div>
</div>

## industry experience

<style>
.experience-item {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 0.65rem;
  gap: 0.5rem 1rem;
}
.experience-main {
  display: flex;
  align-items: center;
  gap: 10px;
}
.experience-logo {
  width: 24px;
  height: 24px;
  min-width: 24px;
  border-radius: 4px;
  object-fit: cover;
  border: 1px solid rgba(0, 0, 0, 0.08);
}
.experience-meta {
  font-size: 0.88rem;
  color: var(--global-text-color-light, #6c757d);
  white-space: nowrap;
}
@media (max-width: 650px) {
  .experience-item {
    flex-direction: column;
    align-items: flex-start;
    gap: 0.15rem;
    margin-bottom: 0.75rem;
  }
  .experience-meta {
    padding-left: 34px;
    white-space: normal;
    font-size: 0.82rem;
  }
}
.publications ol.bibliography li div.links {
  display: inline-flex !important;
  flex-wrap: wrap !important;
  align-items: center !important;
  gap: 6px !important;
  margin-right: 8px !important;
  margin-bottom: 0.25rem !important;
  vertical-align: middle !important;
}
.publications ol.bibliography li div.links a.btn {
  margin-right: 0 !important;
  margin-bottom: 0 !important;
}
.publications ol.bibliography li div.badges {
  display: inline-flex !important;
  flex-wrap: wrap !important;
  align-items: center !important;
  gap: 8px !important;
  padding-bottom: 0.25rem !important;
  vertical-align: middle !important;
}
.publications ol.bibliography li div.badges span,
.publications ol.bibliography li div.badges a {
  display: inline-flex !important;
  align-items: center !important;
  padding-right: 0 !important;
}
.publications ol.bibliography li div.badges .__dimensions_badge_embed__ {
  margin-bottom: 0 !important;
}
</style>

<div class="experience-section mb-4">
  <div class="experience-item">
    <div class="experience-main">
      <img src="{{ site.baseurl }}/assets/img/logo_darknavy.png" alt="DarkNavy logo" class="experience-logo">
      <span><strong>DarkNavy</strong> — Research Intern</span>
    </div>
    <div class="experience-meta">Shanghai, China · Jul. 2025 – Aug. 2026</div>
  </div>

  <div class="experience-item">
    <div class="experience-main">
      <img src="{{ site.baseurl }}/assets/img/logo_goplus.png" alt="GoPlus logo" class="experience-logo">
      <span><strong>GoPlus</strong> — Research Intern</span>
    </div>
    <div class="experience-meta">Remote · Sep. 2024 – Dec. 2024</div>
  </div>

  <div class="experience-item">
    <div class="experience-main">
      <img src="{{ site.baseurl }}/assets/img/logo_antgroup.png" alt="Ant Group logo" class="experience-logo">
      <span><strong>Skyward Lab, Ant Group</strong> — Research Intern</span>
    </div>
    <div class="experience-meta">Hangzhou, China · Aug. 2023 – Jan. 2024</div>
  </div>

  <div class="experience-item">
    <div class="experience-main">
      <img src="{{ site.baseurl }}/assets/img/logo_webank.png" alt="WeBank logo" class="experience-logo">
      <span><strong>WeBank</strong> — Blockchain R&D Intern</span>
    </div>
    <div class="experience-meta">Shenzhen, China · Oct. 2021 – Jan. 2022</div>
  </div>
</div>

## selected honors and awards

<div class="awards-section mb-4">
  <div class="d-flex justify-content-between align-items-baseline mb-2 flex-wrap" style="gap: 0.25rem 1rem;">
    <span>National Scholarship for Graduate Students</span>
    <span class="text-muted" style="font-size: 0.88rem; white-space: nowrap;">Nov. 2024</span>
  </div>
  <div class="d-flex justify-content-between align-items-baseline mb-2 flex-wrap" style="gap: 0.25rem 1rem;">
    <span>President Scholarship for Graduate Students, Sun Yat-sen University</span>
    <span class="text-muted" style="font-size: 0.88rem; white-space: nowrap;">Oct. 2023</span>
  </div>
  <div class="d-flex justify-content-between align-items-baseline mb-2 flex-wrap" style="gap: 0.25rem 1rem;">
    <span>1st Prize, China Service Computing Innovation Contest</span>
    <span class="text-muted" style="font-size: 0.88rem; white-space: nowrap;">Sep. 2023</span>
  </div>
  <div class="d-flex justify-content-between align-items-baseline mb-2 flex-wrap" style="gap: 0.25rem 1rem;">
    <span>8th Place, Numen Cyber CTF</span>
    <span class="text-muted" style="font-size: 0.88rem; white-space: nowrap;">Apr. 2023</span>
  </div>
</div>

## <a href="{{ '/publications/' | relative_url }}" style="color: inherit">selected publications</a>

{% include selected_papers.liquid %}

<div class="visitor-map" style="max-width: 360px; margin: 2.5rem auto 1rem auto; text-align: center;">
  <iframe src="{{ site.baseurl }}/assets/html/map.html" style="width: 100%; height: 175px; border: none; overflow: hidden; border-radius: 8px;" scrolling="no"></iframe>
</div>
