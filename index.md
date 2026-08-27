---
layout: page
---

<style>
.profile {
  color: #2f2f2f;
  font-size: 16px;
  line-height: 1.65;
}

.profile a {
  color: #2f5d8a;
  text-decoration: none;
}

.profile a:hover {
  text-decoration: underline;
}

.profile-header {
  display: flex;
  align-items: flex-start;
  gap: 28px;
  margin-bottom: 36px;
}

.profile-header img {
  width: 125px;
  height: 125px;
  object-fit: cover;
  border-radius: 50%;
  flex: 0 0 auto;
}

.profile-header h1 {
  margin: 0 0 12px;
  font-size: 2.25rem;
  line-height: 1.15;
}

.profile-header p {
  margin: 0 0 10px;
}

.profile section {
  margin-top: 34px;
}

.profile h2 {
  margin: 0 0 14px;
  padding-bottom: 7px;
  border-bottom: 1px solid #e5e5e5;
  font-size: 1.45rem;
}

.interests {
  margin: 0;
  padding-left: 20px;
}

.publication {
  margin-bottom: 20px;
}

.publication-title {
  font-weight: 600;
}

.publication-meta {
  color: #555;
}

.service-list {
  columns: 2;
  column-gap: 36px;
  margin: 0;
  padding-left: 20px;
}

.news {
  margin: 0;
  padding: 0;
  list-style: none;
}

.news li {
  margin-bottom: 12px;
}

.news-date {
  display: inline-block;
  min-width: 88px;
  color: #666;
  font-weight: 600;
}

@media (max-width: 700px) {
  .profile-header {
    display: block;
  }

  .profile-header img {
    margin-bottom: 18px;
  }

  .service-list {
    columns: 1;
  }

  .news-date {
    display: block;
    margin-bottom: 2px;
  }
}
</style>

<div class="profile">

<div class="profile-header">
  <img src="images/bio.png" alt="Liman Wang">

  <div>
    <h1>Liman Wang (王莉漫)</h1>

    <p>
      I am a PhD student in Intelligent Robotics at the
      <a href="https://www.york.ac.uk/#/">University of York</a>, UK, based at the
      <a href="https://www.york.ac.uk/safe-autonomy/">Institute for Safe Autonomy</a>,
      under the supervision of Dr.
      <a href="https://jihong-zhu.github.io/">Jihong Zhu</a>.
    </p>

    <p>
      My research focuses on <strong>robotic manipulation</strong>,
      <strong>dexterous hands and grippers</strong>, and
      <strong>multimodal AI for robotics</strong>.
    </p>

    <p>
      Before starting my PhD, I received my Master's degree in Intelligent Robotics
      from the University of York with <strong>Distinction</strong>, ranking
      <strong>first in my cohort</strong>. Previously, I worked as an Algorithm Engineer
      at <a href="https://www.se.com/ww/en/#/">Schneider Electric</a> for three years.
    </p>
  </div>
</div>

<section>
  <h2>Research Interests</h2>
  <ul class="interests">
    <li>Robotic Manipulation</li>
    <li>Dexterous Hands and Grippers</li>
    <li>Multimodal AI for Robotics</li>
  </ul>
</section>

<section>
  <h2>Selected Publications</h2>

  <div class="publication">
    <div class="publication-title">
      MLLM-Fabric: Multimodal Large Language Model-Driven Robotic Framework for Fabric Sorting and Selection
    </div>
    <div><strong>Liman Wang</strong>, et al.</div>
    <div class="publication-meta">
      <em>IEEE Robotics and Automation Letters (RA-L), to be presented at IEEE International Conference on Robotics and Automation (ICRA), 2026</em>
    </div>
    <div><a href="https://arxiv.org/abs/2507.04351">Preprint</a></div>
  </div>

  <div class="publication">
    <div class="publication-title">
      Balancing Rigor and Utility: Mitigating Cognitive Biases in Large Language Models for Multiple-Choice Questions
    </div>
    <div><strong>Liman Wang</strong>, et al.</div>
    <div class="publication-meta">
      <em>Proceedings of the Annual Meeting of the Cognitive Science Society, 2025, Full Paper</em>
    </div>
    <div><a href="https://arxiv.org/abs/2406.10999">Preprint</a></div>
  </div>

  <div class="publication">
    <div class="publication-title">
      LLM-SAP: Large Language Models Situational Awareness Based Planning
    </div>
    <div><strong>Liman Wang</strong>, et al.</div>
    <div class="publication-meta">
      <em>IEEE International Conference on Multimedia &amp; Expo Workshops (ICMEW), Workshop on Multimodal Learning for Social Good, 2024</em>
    </div>
    <div>
      <a href="https://www.computer.org/csdl/proceedings-article/icmew/2024/10645429/1ZNT7zHkzew">Proceedings</a>
    </div>
  </div>

  <div class="publication">
    <div class="publication-title">
      FENet: Focusing Enhanced Network for Lane Detection
    </div>
    <div><strong>Liman Wang</strong>, et al.</div>
    <div class="publication-meta">
      <em>IEEE International Conference on Multimedia &amp; Expo (ICME), 2024, Oral Presentation</em>
    </div>
    <div>
      <a href="https://www.computer.org/csdl/proceedings-article/icme/2024/10687857/20F0GXZBkEU">Proceedings</a>
    </div>
  </div>

  <div class="publication">
    <div class="publication-title">
      Deformable Object Manipulation in Caregiving Scenarios: A Review
    </div>
    <div><strong>Liman Wang</strong>, et al.</div>
    <div class="publication-meta">
      <em>Machines, 2023, 11(11), 1013</em>
    </div>
    <div>
      <a href="https://www.mdpi.com/2075-1702/11/11/1013#/">Journal Paper</a>
    </div>
  </div>
</section>

<section>
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

<section>
  <h2>News and Updates</h2>
  <ul class="news">
    <li>
      <span class="news-date">Oct 2025</span>
      Our paper <em>MLLM-Fabric</em> has been accepted to <em>IEEE Robotics and Automation Letters (RA-L)</em> and will be presented at ICRA 2026.
      <a href="https://arxiv.org/abs/2507.04351">Preprint</a>
    </li>

    <li>
      <span class="news-date">Apr 2025</span>
      Our work <em>Balancing Rigor and Utility</em> has been accepted as a full paper at
      <a href="https://cognitivesciencesociety.org/cogsci-2025/">CogSci 2025</a>.
      <a href="https://arxiv.org/abs/2406.10999">Preprint</a>
    </li>

    <li>
      <span class="news-date">Jun 2024</span>
      I received a full scholarship for my PhD studies at the University of York.
    </li>

    <li>
      <span class="news-date">Apr 2024</span>
      Our work <em>LLM-SAP</em> has been accepted to the
      <a href="https://vista-h.github.io/MML4SG_2024/#/">ICME 2024 Workshop on Multimodal Learning for Social Good</a>.
    </li>

    <li>
      <span class="news-date">Mar 2024</span>
      Our work <em>FENet</em> has been accepted to
      <a href="https://2024.ieeeicme.org/#/">ICME 2024</a> as an oral paper.
    </li>

    <li>
      <span class="news-date">Dec 2023</span>
      Our work <em>Deformable Object Manipulation in Caregiving Scenarios: A Review</em> was published in
      <a href="https://www.mdpi.com/2075-1702/11/11/1013#/">Machines</a>.
    </li>

    <li>
      <span class="news-date">Nov 2023</span>
      I received my Master's degree in Intelligent Robotics from the University of York with Distinction, ranking first in my cohort.
    </li>

    <li>
      <span class="news-date">Jun 2023</span>
      I achieved 130% annual performance as an NLP Algorithm Engineer at Schneider Electric (China) Co., Ltd.
    </li>

    <li>
      <span class="news-date">Jun 2022</span>
      As an independent inventor, I obtained a national invention patent on knowledge graphs and graph algorithms, issued by the
      <a href="https://www.cnipa.gov.cn/#/">China National Intellectual Property Administration</a>.
    </li>
  </ul>
</section>

</div>
