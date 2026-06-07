---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S., Department of Informatics, [**The University of Electro-Communications (UEC)**](https://www.uec.ac.jp/), Apr 2025 – Mar 2027 *(in progress)*
  * Graduate School of Informatics and Engineering
  * [Inaba Laboratory](https://www.inaba.aix.uec.ac.jp/) (Assoc. Prof. Michimasa Inaba)
* B.Eng., Department of Media Informatics, School of Informatics and Engineering, [**The University of Electro-Communications (UEC)**](https://www.uec.ac.jp/), Apr 2021 – Mar 2025

Experience
======
* **COO**, [B-Roca Inc.](https://broca.co.jp/), Tokyo, Japan — *Jul 2024 – present*
  * AI-driven business development and generative-AI system implementation
  * Launched [**EntryUp**](https://entryup.jp/) — an AI SaaS / LLM-powered chatbot for corporate recruitment pages
    * *Jan 2026* — [initial release](https://prtimes.jp/main/html/rd/p/000000001.000172359.html)
    * *Mar 2026* — [Rich Menu feature](https://prtimes.jp/main/html/rd/p/000000003.000172359.html) (one-tap application / interview booking inside chat)
  * Currently leading the development of marketing-support tools powered by generative AI
* **Project Manager**, Almondo Inc., Tokyo, Japan — *May 2024 – Mar 2025*
  * Managed projects developing and deploying LLMs with cutting-edge training techniques
* **Software Developer**, Nuco Inc., Shibuya, Tokyo — *Jul 2023 – May 2024*
  * Built web applications using generative AI, Python, and TypeScript

Research interests
======
* Conversational Recommendation Systems (CRS)
* Preference Optimization (DPO / SimPO / KTO / ORPO)
* Long-context dialogue · information extraction
* Real-world generative AI · physical AI (interest area)

Research Projects
======
* [**GENIAC**](https://weblab.t.u-tokyo.ac.jp/geniac_llm/teams/) (Generative AI Accelerator Challenge) — Phase 1, **Team 天元突破 (Tengen Toppa)**, *Mar – May 2024*
  * National Japanese-LLM development project funded by METI / NEDO ("Post-5G Information and Communication Systems Infrastructure Strengthening R&D Program", JPNP20017)
  * Team led by Daisei Ozaki (尾崎 大晟). Focus: minimizing hallucinations in Japanese LLMs, strengthening logical reasoning via debate data, and releasing a public Mixture-of-Experts (MoE) implementation

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
