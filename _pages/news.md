---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% include base_path %}
<style>
/* Bright academic palette: clear category colors, light surfaces, gold-blue accents. */
.news-list {
  --news-text: #43536a;
  --news-muted: #7d8ba0;
  display: grid;
  gap: 15px;
  margin-top: 1.15rem;
}

.news-list .news-item {
  --accent: #70afe8;
  --accent-dark: #397fb9;
  --accent-soft: #eaf5ff;
  --card-start: #ffffff;
  --card-end: #f4f9ff;
  --outline: #dcecff;

  display: grid;
  grid-template-columns: 112px minmax(0, 1fr);
  align-items: start;
  gap: 19px;
  margin: 0;
  padding: 19px 22px;
  border: 1px solid var(--outline);
  border-left: 5px solid var(--accent);
  border-radius: 16px;
  background: linear-gradient(120deg, var(--card-start) 0%, var(--card-end) 100%);
  box-shadow: 0 4px 16px rgba(56, 82, 116, 0.055);
  transition: transform 160ms ease, box-shadow 160ms ease;
}

.news-list .news-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 9px 23px rgba(56, 82, 116, 0.10);
}

.news-list .news-date {
  display: inline-flex;
  justify-content: center;
  align-items: center;
  width: fit-content;
  min-width: 91px;
  margin-top: 1px;
  padding: 8px 12px;
  border: 1.5px solid var(--accent);
  border-radius: 999px;
  background: var(--accent-soft);
  color: var(--accent-dark);
  font-size: 0.91rem;
  font-weight: 750;
  letter-spacing: 0.015em;
  line-height: 1.25;
  white-space: nowrap;
  font-variant-numeric: tabular-nums;
}

.news-list .news-content {
  min-width: 0;
}

.news-list .news-category {
  display: inline-flex;
  align-items: center;
  gap: 5px;
  margin: 0 0 8px;
  padding: 4px 10px;
  border: 1px solid color-mix(in srgb, var(--accent) 25%, white);
  border-radius: 999px;
  background: var(--accent-soft);
  color: var(--accent-dark);
  font-size: 0.69rem;
  font-weight: 750;
  letter-spacing: 0.065em;
  line-height: 1.45;
  text-transform: uppercase;
}

.news-list .news-copy {
  margin: 0;
  color: var(--news-text);
  font-size: 0.97rem;
  line-height: 1.72;
  overflow-wrap: anywhere;
}

.news-list .news-copy strong {
  color: #30445e;
  font-weight: 750;
}

.news-list .news-copy em {
  color: #354b66;
}

.news-list .news-copy a {
  color: var(--accent-dark);
  font-weight: 650;
  text-decoration: none;
  border-bottom: 1px solid color-mix(in srgb, var(--accent) 45%, transparent);
}

.news-list .news-copy a:hover {
  border-bottom-color: var(--accent-dark);
}

/* Internship: bright sky blue */
.news-list .news-item--internship {
  --accent: #65b4ed;
  --accent-dark: #287eb8;
  --accent-soft: #e9f6ff;
  --card-end: #f2f9ff;
  --outline: #d7edfc;
}

/* Work: deeper blue in the same family */
.news-list .news-item--talk {
  --accent: #477fd0;
  --accent-dark: #315fa8;
  --accent-soft: #e8f0ff;
  --card-end: #f1f5ff;
  --outline: #d9e5fb;
}

/* Academic: fresh teal */
.news-list .news-item--academic {
  --accent: #86A9D2;
  --accent-dark: #587BA5;
  --accent-soft: #EDF4FC;
  --card-end: #F6F9FE;
  --outline: #DDE8F5;
}

/* Invited talks: periwinkle / blue-violet */
/* Invited talks: deep academic navy blue */
.news-list .news-item--work {
  --accent: #315D91;
  --accent-dark: #24486F;
  --accent-soft: #E7EFF8;
  --card-end: #F2F6FB;
  --outline: #D4E1EF;
}

/* Awards: champagne gold */
.news-list .news-item--award {
  --accent: #d6ad50;
  --accent-dark: #987326;
  --accent-soft: #fff4d8;
  --card-end: #fffaf0;
  --outline: #f3e6c5;
}

/* First prize: stronger gold, within the same award family */
.news-list .news-item--award.news-item--first-prize {
  --accent: #c58d24;
  --accent-dark: #8c6217;
  --accent-soft: #ffedbd;
  --card-end: #fff7e5;
  --outline: #eed9a7;
}

@media (max-width: 650px) {
  .news-list {
    gap: 11px;
  }

  .news-list .news-item {
    grid-template-columns: 1fr;
    gap: 9px;
    padding: 16px 17px;
    border-left-width: 4px;
    border-radius: 14px;
  }

  .news-list .news-date {
    min-width: 0;
    padding: 6px 11px;
    font-size: 0.83rem;
  }

  .news-list .news-copy {
    font-size: 0.93rem;
    line-height: 1.68;
  }
}

@media (prefers-reduced-motion: reduce) {
  .news-list .news-item {
    transition: none;
  }
  .news-list .news-item:hover {
    transform: none;
  }
}
</style>

<div class="news-list">

  <article class="news-item news-item--talk">
    <time class="news-date" datetime="2026-11">2026.11</time>
    <div class="news-content">
      <span class="news-category">🎤 Invited Talk</span>
      <p class="news-copy">
        ✨✨✨ Delighted to have been invited to deliver a talk at <em>the Qin-Chuan Academic Conference on Precision Radiotherapy and Tsinghua University RTUP-PEM 2026 Annual Meeting</em>.
      </p>
    </div>
  </article>

  <article class="news-item news-item--talk">
    <time class="news-date" datetime="2026-10">2026.10</time>
    <div class="news-content">
      <span class="news-category">🎤 Invited Talk</span>
      <p class="news-copy">
        ✨✨✨ Honored to have been invited to deliver a talk at <em>the 2026 Pan-Southwest Academic Conference on Radiation Physics and Technology</em>, organized by the Medical Physics Division of the Chinese Society of Biomedical Engineering.
      </p>
    </div>
  </article>

  <article class="news-item news-item--award">
    <time class="news-date" datetime="2026-10">2026.10</time>
    <div class="news-content">
      <span class="news-category">🏆 Award · Runner-up</span>
      <p class="news-copy">
        We won the <strong>Runner-up Award</strong> in EchoRisk: AI for Cardiac Function Estimation, Assessment &amp; Early Prediction of Therapy-Induced Cardiotoxicity from Echocardiography at MICCAI 2026! <a href="https://jdyfy.com/info/1241/208411.htm" target="_blank" rel="noopener noreferrer">The achievement was also featured by the hospital.</a> 🥈
      </p>
    </div>
  </article>

  <article class="news-item news-item--award news-item--first-prize">
    <time class="news-date" datetime="2026-07">2026.07</time>
    <div class="news-content">
      <span class="news-category">🥇 Award · First Prize</span>
      <p class="news-copy">
        🥇🥇🥇 We are pleased to announce that our “AI-based individualized decision-making system for radiotherapy of metaplastic breast cancer” has won the <strong>First Prize</strong> of the Shaanxi Enterprise “Three New and Three Small” Innovation Competition.
      </p>
    </div>
  </article>

  <article class="news-item news-item--academic">
    <time class="news-date" datetime="2026-02">2026.02</time>
    <div class="news-content">
      <span class="news-category">🎓 Publication</span>
      <p class="news-copy">
        🎊 Happy to share that our paper has been accepted at <strong>CVPR 2026</strong> (Findings track), focusing on depth prediction in endoscopic images and supporting subsequent clinical polyp and cancer screening. 🥳
      </p>
    </div>
  </article>

  <article class="news-item news-item--academic">
    <time class="news-date" datetime="2025-12">2025.12</time>
    <div class="news-content">
      <span class="news-category">Academic Service</span>
      <p class="news-copy">
        ✨✨✨ Pleased to be invited as a reviewer for <strong>the Hainan Medical Journal</strong> (Chinese Core Journal).
      </p>
    </div>
  </article>

  <article class="news-item news-item--work">
    <time class="news-date" datetime="2025-09">2025.09</time>
    <div class="news-content">
      <span class="news-category">🔬 Professional Appointment</span>
      <p class="news-copy">
        🧐 Officially joining the Xi’an Jiaotong University Health Science Center (The First Affiliated Hospital) as a medical physicist (Junior Researcher) in the Department of Radiation Oncology, <strong>with the hope of helping more cancer patients regain their health.</strong>
      </p>
    </div>
  </article>

  <article class="news-item news-item--academic">
    <time class="news-date" datetime="2025-07">2025.07</time>
    <div class="news-content">
      <span class="news-category">Academic Service</span>
      <p class="news-copy">
        ✨✨✨ Honored to be invited as a reviewer for DT4H (Digital Twin for Healthcare) at <strong>MICCAI 2025</strong>.
      </p>
    </div>
  </article>

  <article class="news-item news-item--internship">
    <time class="news-date" datetime="2025-03">2025.03</time>
    <div class="news-content">
      <span class="news-category">🩺 Clinical Training</span>
      <p class="news-copy">
        👨‍⚕️ Looking forward to joining Sun Yat-sen University Cancer Center for clinical training, where I will primarily focus on learning <strong>TomoTherapy and adaptive radiotherapy techniques</strong>.
      </p>
    </div>
  </article>

  <article class="news-item news-item--internship">
    <time class="news-date" datetime="2024-06">2024.06</time>
    <div class="news-content">
      <span class="news-category">🔬 Research Internship</span>
      <p class="news-copy">
        🤠 Excited to start a research internship at <strong>the Massachusetts Institute of Technology (MIT)’s</strong> M3S research group (<a href="https://smart.mit.edu/" target="_blank" rel="noopener noreferrer">SMART</a>, Singapore).
      </p>
    </div>
  </article>
</div>
