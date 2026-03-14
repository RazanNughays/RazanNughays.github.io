---
layout: archive
title: "Curriculum Vitae"
permalink: /CV/
author_profile: false
redirect_from:
  - /resume
---

<style>
  .cv-wrap {
    max-width: 1200px;
    margin: 0 auto;
    width: 100%;
  }

  .archive__subtitle,
  .page__title {
    max-width: 1200px;
    margin-left: auto !important;
    margin-right: auto !important;
    text-align: left !important;
    width: 100%;
  }

  .cv-wrap h2 {
    margin-top: 2.2rem;
  }

  .cv-wrap ul {
    margin-bottom: 1.2rem;
  }

  @media (max-width: 900px) {
    .cv-wrap,
    .archive__subtitle,
    .page__title {
      max-width: 100%;
    }
  }
</style>

<div class="cv-wrap">

<h2>Education</h2>
<ul>
  <li><strong>Ph.D., Materials Science and Engineering</strong>, KAUST, Thuwal, Saudi Arabia, 2025.</li>
  <li><strong>M.Sc., Materials Science and Engineering</strong>, KAUST, Thuwal, Saudi Arabia, 2020.</li>
  <li><strong>B.Sc., General Physics</strong>, King Abdulaziz University (KAU), Jeddah, Saudi Arabia, 2017.</li>
</ul>

<h2>Current Position</h2>
<ul>
  <li><strong>Postdoctoral Researcher, Chemical Engineering</strong>, MIT, United States.</li>
</ul>

<h2>Research Experience</h2>
<ul>
  <li><strong>MIT</strong> — Ultrafast Laser Microscopy, Present.</li>
  <li><strong>KAUST</strong> — Ultrafast Scanning Electron Microscopy (U-SEM), 2020–2025.</li>
  <li><strong>University of California, Santa Barbara</strong> — Tracking thermal effects using backscattered electron diffraction (BSED), 2024.</li>
  <li><strong>KAUST</strong> — Synthesis of MXene for a self-healing material, 2019.</li>
  <li><strong>KAUST</strong> — Transfer of graphene to suitable substrates, 2018.</li>
</ul>

<h2>Mentoring and Teaching Experience</h2>
<ul>
  <li>2025: Mentored two students from KAUST Academy in a research-based summer internship, including experiments, data interpretation, literature reading, and scientific communication.</li>
  <li>2025: Teaching Assistant for Materials Characterization course.</li>
  <li>2025: Mentored a Ph.D. student on U-SEM.</li>
  <li>2024: Teaching Assistant for Materials Characterization course.</li>
  <li>2022: Mentored a Ph.D. student on U-SEM.</li>
</ul>

<h2>Selected Publications</h2>
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

<h2>Conference Participation (selected)</h2>
<ul>
  <li><strong>MRS Fall Meeting</strong>, Boston, USA — Oral presentation (Dec 2024).</li>
  <li><strong>IMC20</strong>, Busan, South Korea — Poster presentation (Sep 2023).</li>
  <li><strong>SPIE Conference</strong>, San Francisco, USA — Poster presentation (Jan 2023).</li>
</ul>

<h2>Awards</h2>
<ul>
  <li><strong>Ibn Khaldun Postdoctoral Fellowship</strong> (2025).</li>
  <li><strong>KAUST Dean’s Award</strong> (2023–2024).</li>
  <li><strong>IMC20 Best Poster Presentation Award</strong> (2023).</li>
</ul>

<h2>Technical Skills</h2>
<ul>
  <li><strong>Programming:</strong> Python, MATLAB, LaTeX.</li>
  <li><strong>Data analysis:</strong> Origin, MS Excel.</li>
  <li><strong>Laboratory:</strong> Femtosecond fiber laser maintenance, optical alignment.</li>
</ul>

</div>
