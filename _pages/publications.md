---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a></u>.
{% endif %}

<style>
.pub { display: flex; gap: 1.2em; margin: 1.6em 0; align-items: flex-start; }
.pub-img { flex: 0 0 150px; width: 150px; height: 150px; border: 1px solid #e3e3e3;
           border-radius: 6px; overflow: hidden; background: #fff; }
.pub-img img { width: 100%; height: 100%; object-fit: contain; margin: 0; }
.pub-text { flex: 1; min-width: 0; }
.pub-title { font-weight: 600; line-height: 1.35; margin-bottom: 0.3em; }
.pub-title a { color: inherit; text-decoration: none; }
.pub-title a:hover { text-decoration: underline; }
.pub-authors { font-size: 0.9em; margin-bottom: 0.2em; }
.pub-venue { font-size: 0.9em; font-style: italic; color: #555; }
@media (max-width: 600px) {
  .pub { flex-direction: column; }
  .pub-img { width: 100%; max-width: 260px; height: auto; aspect-ratio: 1 / 1; flex-basis: auto; }
}
</style>

<div class="pub">
  <div class="pub-img"><img src="/images/pubs/neurips26.png" alt="Alignment-Utility Asymmetry"></div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://arxiv.org/abs/2609.32717">LLM Alignment–Utility Asymmetry under Semantic-Preserving Transformations</a></div>
    <div class="pub-authors"><b>Mohan Li</b>, Chengyu Yu, Francesco Sovrano, Marc Langheinrich, Martin Gjoreski</div>
    <div class="pub-venue">NeurIPS 2026</div>
  </div>
</div>

<div class="pub">
  <div class="pub-img"><img src="/images/pubs/iclr26.png" alt="Profile Mapping FL"></div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://openreview.net/forum?id=thoPskdIcE">Federated Learning with Profile Mapping under Distribution Shifts and Drifts</a></div>
    <div class="pub-authors"><b>Mohan Li</b>, Dario Fenoglio, Martin Gjoreski, Marc Langheinrich</div>
    <div class="pub-venue">ICLR 2026</div>
  </div>
</div>

<div class="pub">
  <div class="pub-img"><img src="/images/pubs/flux.png" alt="FLUX"></div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://neurips.cc/virtual/2025/loc/san-diego/poster/116099">FLUX: Efficient Descriptor-Driven Clustered Federated Learning under Arbitrary Distribution Shifts</a></div>
    <div class="pub-authors">Dario Fenoglio, <b>Mohan Li</b>, Pietro Barbiero, Nicholas D. Lane, Marc Langheinrich, Martin Gjoreski</div>
    <div class="pub-venue">NeurIPS 2025</div>
  </div>
</div>

<div class="pub">
  <div class="pub-img"><img src="/images/pubs/fl-survey.png" alt="FL survey"></div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://arxiv.org/abs/2501.04000">A Survey on Federated Learning in Human Sensing</a></div>
    <div class="pub-authors"><b>Mohan Li</b>, Martin Gjoreski, Pietro Barbiero, Gašper Slapničar, Mitja Luštrek, Nicholas D. Lane, Marc Langheinrich</div>
    <div class="pub-venue">arXiv preprint, 2025</div>
  </div>
</div>

<div class="pub">
  <div class="pub-img"><img src="/images/pubs/mffl.png" alt="Multi-Frequency FL"></div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://ieeexplore.ieee.org/document/10599924">Multi-Frequency Federated Learning for Human Activity Recognition Using Head-Worn Sensors</a></div>
    <div class="pub-authors">Dario Fenoglio, <b>Mohan Li</b>, Davide Casnici, Matias Laporte, Shkurta Gashi, Silvia Santini, Martin Gjoreski, Marc Langheinrich</div>
    <div class="pub-venue">International Conference on Intelligent Environments (IE), 2024</div>
  </div>
</div>

<div class="pub">
  <div class="pub-img"><img src="/images/pubs/cardiac.png" alt="Wearable cardiac imager"></div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://www.nature.com/articles/s41586-022-05498-z">A wearable cardiac ultrasound imager</a></div>
    <div class="pub-authors">Hongjie Hu, Hao Huang, <b>Mohan Li</b>, Xiaoxiang Gao, Lu Yin, Ruixiang Qi, Ray S. Wu, et al.</div>
    <div class="pub-venue">Nature, 2023</div>
  </div>
</div>

<div class="pub">
  <div class="pub-img"><img src="/images/pubs/modulus.png" alt="Stretchable ultrasonic arrays"></div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://www.nature.com/articles/s41551-023-01038-w">Stretchable ultrasonic arrays for the three-dimensional mapping of the modulus of deep tissue</a></div>
    <div class="pub-authors">Hongjie Hu, Yuxiang Ma, Xiaoxiang Gao, Dawei Song, <b>Mohan Li</b>, Hao Huang, Xuejun Qian, et al.</div>
    <div class="pub-venue">Nature Biomedical Engineering, 2023</div>
  </div>
</div>
