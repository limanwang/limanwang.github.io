---
layout: page
---

<style>
/* ===== Personal homepage redesign ===== */
.profile-page {
  --text: #2f2f2f;
  --muted: #6f6f6f;
  --line: #e7e7e7;
  --panel: #fafafa;
  --accent: #2f5f8f;
  --accent-soft: #eef4fa;
  color: var(--text);
  font-size: 16px;
  line-height: 1.7;
}

.profile-page * {
  box-sizing: border-box;
}

.profile-page a {
  color: var(--accent);
  text-decoration: none;
  border-bottom: 1px solid rgba(47, 95, 143, 0.25);
}

.profile-page a:hover {
  border-bottom-color: var(--accent);
}

.profile-hero {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 168px;
  gap: 34px;
  align-items: center;
  padding: 8px 0 28px;
}

.profile-kicker {
  margin: 0 0 6px;
  color: var(--accent);
  font-size: 0.78rem;
  font-weight: 700;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.profile-name {
  margin: 0 0 10px !important;
  font-size: clamp(2rem, 4vw, 2.8rem) !important;
  line-height: 1.1 !important;
  letter-spacing: -0.03em;
}

.profile-intro {
  margin: 0 0 12px;
  font-size: 1.08rem;
}

.profile-summary {
  margin: 0;
  color: #444;
}

.profile-photo {
  width: 168px;
  height: 168px;
  object-fit: cover;
  border-radius: 24px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.10);
}

.focus-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 20px 0 0;
  padding: 0;
  list-style: none;
}

.focus-tags li {
  margin: 0;
  padding: 5px 11px;
  background: var(--accent-soft);
  border-radius: 999px;
  color: #365b7d;
  font-size: 0.88rem;
  font-weight: 600;
}

.profile-section {
  padding: 30px 0;
  border-top: 1px solid var(--line);
}

.profile-section h2 {
  margin: 0 0 18px !important;
  font-size: 1.55rem !important;
  line-height: 1.25 !important;
}

.section-subtitle {
  margin: -8px 0 20px;
  color: var(--muted);
  font-size: 0.94rem;
}

.interest-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 12px;
}

.interest-card {
  min-height: 105px;
  padding: 18px;
  border: 1px solid var(--line);
  border-radius: 14px;
  background: #fff;
}

.interest-card strong {
  display: block;
  margin-bottom: 6px;
  font-size: 1rem;
}

.interest-card span {
  color: var(--muted);
  font-size: 0.9rem;
}

.pub-list {
  display: grid;
  gap: 14px;
}

.pub-card {
  padding: 17px 18px;
  border: 1px solid var(--line);
  border-radius: 14px;
  background: #fff;
}

.pub-title {
  margin-bottom: 5px;
  font-weight: 700;
  line-height: 1.45;
}

.pub-meta {
  margin: 0;
  color: var(--muted);
  font-size: 0.93rem;
  line-height: 1.55;
}

.pub-links {
  margin-top: 8px;
  font-size: 0.9rem;
  font-weight: 600;
}

.service-list {
  columns: 2;
  column-gap: 38px;
  margin: 0;
  padding-left: 1.1rem;
}

.service-list li {
  break-inside: avoid;
  margin: 0 0 8px;
}

.news-list {
  position: relative;
  margin: 0;
  padding: 0;
  list-style: none;
}

.news-list::before {
  content: "";
  position: absolute;
  left: 4px;
  top: 8px;
  bottom: 8px;
  width: 1px;
  background: var(--line);
}

.news-item {
  position: relative;
  display: grid;
  grid-template-columns: 92px minmax(0, 1fr);
  gap: 16px;
  padding: 0 0 20px 20px;
}

.news-item:last-child {
  padding-bottom: 0;
}

.news-item::before {
  content: "";
  position: absolute;
  left: 0;
  top: 8px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--accent);
  box-shadow: 0 0 0 4px #fff;
}

.news-date {
  color: var(--muted);
  font-size: 0.88rem;
  font-weight: 700;
  white-space: nowrap;
}

.news-text {
  min-width: 0;
}

@media (max-width: 760px) {
  .profile-hero {
    grid-template-columns: 1fr;
    gap: 20px;
  }

  .profile-photo {
    grid-row: 1;
    width: 128px;
    height: 128px;
    border-radius: 20px;
  }

  .interest-grid {
    grid-template-columns: 1fr;
  }

  .service-list {
    columns: 1;
  }

  .news-item {
    grid-template-columns: 1fr;
    gap: 3px;
  }
}
</style>

<div class="profile-page">

<section class="profile-hero">
  <div>
    <p class="profile-kicker">Intelligent Robotics · Multimodal AI</p>
    <h1 class="profile-name">Liman Wang <span style="font-weight:500;">(王莉漫)</span></h1>
    <p class="profile-intro">
      PhD student in Intelligent Robotics at the
      <a href="https://www.york.ac.uk/#/">University of York</a>, based at the
      <a href="https://www.york.ac.uk/safe-autonomy/">Institute for Safe Autonomy</a>,
      supervised by Dr. <a href="https://jihong-zhu.github.io/">Jihong Zhu</a>.
    </p>
    <p class="profile-summary">
      My research focuses on <strong>robotic manipulation</strong>,
      <strong>dexterous hands and grippers</strong>, and
      <strong>multimodal AI for robotics</strong>.
      Before starting my PhD, I received my Master's degree in Intelligent Robotics
      from the University of York with <strong>Distinction</strong>, ranking
      <strong>first in my cohort</strong>. Previously, I worked as an Algorithm Engineer
      at <a href="https://www.se.com/ww/en/#/">Schneider Electric</a> for three years.
    </p>

    <ul class="focus-tags">
      <li>Robotic Manipulation</li>
      <li>Dexterous Hands</li>
      <li>Multimodal AI</li>
    </ul>
  </div>

  <img class="profile-photo" src="images/bio.png" alt="Liman Wang">
</section>

<section class="profile-section">
  <h2>Research Interests</h2>
  <div class="interest-grid">
    <div class="interest-card">
      <strong>Robotic Manipulation</strong>
      <span>Learning and planning for reliable interaction with real-world objects.</span>
    </div>
    <div class="interest-card">
      <strong>Dexterous Hands &amp; Grippers</strong>
      <span>Adaptive grasping and manipulation with dexterous robotic end-effectors.</span>
    </div>
    <div class="interest-card">
      <strong>Multimodal AI for Robotics</strong>
      <span>Connecting vision, language, and action for intelligent robotic systems.</span>
    </div>
  </div>
</section>

<section class="profile-section">
  <h2>Selected Publications</h2>
  <p class="section-subtitle">A selection of recent work in robotics, multimodal learning, and AI.</p>

  <div class="pub-list">
    <article class="pub-card">
      <div class="pub-title">MLLM-Fabric: Multimodal Large Language Model-Driven Robotic Framework for Fabric Sorting and Selection</div>
      <p class="pub-meta"><strong>Liman Wang</strong>, et al.<br>
      <em>IEEE Robotics and Automation Letters (RA-L), to be presented at IEEE International Conference on Robotics and Automation (ICRA), 2026</em></p>
      <div class="pub-links"><a href="https://arxiv.org/abs/2507.04351">Preprint ↗</a></div>
    </article>

    <article class="pub-card">
      <div class="pub-title">Balancing Rigor and Utility: Mitigating Cognitive Biases in Large Language Models for Multiple-Choice Questions</div>
      <p class="pub-meta"><strong>Liman Wang</strong>, et al.<br>
      <em>Proceedings of the Annual Meeting of the Cognitive Science Society, 2025, Full Paper</em></p>
      <div class="pub-links"><a href="https://arxiv.org/abs/2406.10999">Preprint ↗</a></div>
    </article>

    <article class="pub-card">
      <div class="pub-title">LLM-SAP: Large Language Models Situational Awareness Based Planning</div>
      <p class="pub-meta"><strong>Liman Wang</strong>, et al.<br>
      <em>IEEE International Conference on Multimedia &amp; Expo Workshops (ICMEW), Workshop on Multimodal Learning for Social Good, 2024</em></p>
      <div class="pub-links"><a href="https://www.computer.org/csdl/proceedings-article/icmew/2024/10645429/1ZNT7zHkzew">Proceedings ↗</a></div>
    </article>

    <article class="pub-card">
      <div class="pub-title">FENet: Focusing Enhanced Network for Lane Detection</div>
      <p class="pub-meta"><strong>Liman Wang</strong>, et al.<br>
      <em>IEEE International Conference on Multimedia &amp; Expo (ICME), 2024, Oral Presentation</em></p>
      <div class="pub-links"><a href="https://www.computer.org/csdl/proceedings-article/icme/2024/10687857/20F0GXZBkEU">Proceedings ↗</a></div>
    </article>

    <article class="pub-card">
      <div class="pub-title">Deformable Object Manipulation in Caregiving Scenarios: A Review</div>
      <p class="pub-meta"><strong>Liman Wang</strong>, et al.<br>
      <em>Machines, 2023, 11(11), 1013</em></p>
      <div class="pub-links"><a href="https://www.mdpi.com/2075-1702/11/11/1013#/">Journal Paper ↗</a></div>
    </article>
  </div>
</section>

<section class="profile-section">
  <h2>Reviewing Service</h2>
  <ul class="service-list">
    <li>IEEE Transactions on Automation Science and Engineering (T-ASE)</li>
    <li>Conference on Robot Learning (CoRL)</li>
    <li>IEEE International Conference on Robotics and Automation (ICRA)</li>
    <li>IEEE Robotics and Automation Letters (RA-L)</li>
    <li>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</li>
    <li>Artificial Intelligence Review (AIR)</li>
    <li>IEEE International Conference on Multimedia &amp; Expo (ICME)</li>
  </ul>
</section>

<section class="profile-section">
  <h2>News &amp; Updates ✨</h2>
  <ul class="news-list">
    <li class="news-item">
      <div class="news-date">Oct 2025</div>
      <div class="news-text">Our paper <em>MLLM-Fabric</em> has been accepted to <em>IEEE Robotics and Automation Letters (RA-L)</em> and will be presented at ICRA 2026 in Vienna, Austria. <a href="https://arxiv.org/abs/2507.04351">Preprint ↗</a></div>
    </li>
    <li class="news-item">
      <div class="news-date">Apr 2025</div>
      <div class="news-text">Our work <em>Balancing Rigor and Utility</em> has been accepted as a full paper at <a href="https://cognitivesciencesociety.org/cogsci-2025/">CogSci 2025</a> and will be presented as a poster in San Francisco. <a href="https://arxiv.org/abs/2406.10999">Preprint ↗</a></div>
    </li>
    <li class="news-item">
      <div class="news-date">Jun 2024</div>
      <div class="news-text">I received a full scholarship for my PhD studies at the University of York.</div>
    </li>
    <li class="news-item">
      <div class="news-date">Apr 2024</div>
      <div class="news-text">Our work <em>LLM-SAP</em> has been accepted to the <a href="https://vista-h.github.io/MML4SG_2024/#/">ICME 2024 Workshop on Multimodal Learning for Social Good</a>. <a href="https://www.computer.org/csdl/proceedings-article/icmew/2024/10645429/1ZNT7zHkzew">Proceedings ↗</a></div>
    </li>
    <li class="news-item">
      <div class="news-date">Mar 2024</div>
      <div class="news-text">Our work <em>FENet</em> has been accepted to <a href="https://2024.ieeeicme.org/#/">ICME 2024</a> as an oral paper. <a href="https://www.computer.org/csdl/proceedings-article/icme/2024/10687857/20F0GXZBkEU">Proceedings ↗</a></div>
    </li>
    <li class="news-item">
      <div class="news-date">Dec 2023</div>
      <div class="news-text">Our review <em>Deformable Object Manipulation in Caregiving Scenarios</em> was published in <a href="https://www.mdpi.com/2075-1702/11/11/1013#/">Machines</a>.</div>
    </li>
    <li class="news-item">
      <div class="news-date">Nov 2023</div>
      <div class="news-text">I received my Master's degree in Intelligent Robotics from the University of York with Distinction, ranking first in my cohort.</div>
    </li>
    <li class="news-item">
      <div class="news-date">Jun 2023</div>
      <div class="news-text">I achieved 130% annual performance as an NLP Algorithm Engineer at Schneider Electric (China) Co., Ltd.</div>
    </li>
    <li class="news-item">
      <div class="news-date">Jun 2022</div>
      <div class="news-text">As an independent inventor, I obtained a national invention patent on knowledge graphs and graph algorithms, issued by the <a href="https://www.cnipa.gov.cn/#/">China National Intellectual Property Administration</a>.</div>
    </li>
  </ul>
</section>

</div>
