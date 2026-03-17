---
layout: archive
title: "Background"
permalink: /background/
author_profile: false
redirect_from:
  - /resume
  - /CV/
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
    margin-top: 2.4rem;
    margin-bottom: 1rem;
  }

  .cv-wrap ul {
    margin-bottom: 1.2rem;
  }

  .cv-wrap li {
    margin-bottom: 0.65rem;
  }

  .cv-logo-row {
    display: flex;
    align-items: center;
    gap: 20px;
    margin-bottom: 1.4rem;
  }

  .cv-logo {
    width: 120px;
    min-width: 120px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .cv-logo img {
    max-width: 110px;
    max-height: 55px;
    width: auto;
    height: auto;
    object-fit: contain;
    display: block;
  }

  .cv-logo-text {
    flex: 1;
    min-width: 0;
    line-height: 1.7;
  }

  .cv-logo-text strong {
    font-size: 1.05rem;
  }

  @media (max-width: 900px) {
    .cv-wrap,
    .archive__subtitle,
    .page__title {
      max-width: 100%;
    }

    .cv-logo-row {
      flex-direction: column;
      align-items: flex-start;
      gap: 12px;
    }

    .cv-logo {
      width: auto;
      min-width: 0;
    }

    .cv-logo img {
      max-width: 120px;
      max-height: 60px;
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

    <strong>Massachusetts Institute of Technology (MIT)</strong><br>
    Postdoctoral Researcher, Chemical Engineering — Present
  </div>
</div>

<h2>Research Experience</h2>

<div class="cv-logo-row">
  <div class="cv-logo">
    <img src="/images/MIT.png" alt="MIT logo">
  </div>
  <div class="cv-logo-text">
    <strong>Massachusetts Institute of Technology (MIT)</strong><br>
    Ultrafast laser spectroscopy and microscopy of semiconductor interfaces — Present
  </div>
</div>

<div class="cv-logo-row">
  <div class="cv-logo">
    <img src="/images/KAUST.webp" alt="KAUST logo">
  </div>
  <div class="cv-logo-text">
    <strong>King Abdullah University of Science and Technology (KAUST)</strong><br>
    Ultrafast Scanning Electron Microscopy (U-SEM), charge-carrier dynamics in semiconductors and energy materials — 2020–2025
  </div>
</div>

<div class="cv-logo-row">
  <div class="cv-logo">
    <img src="/images/UCSB.jpg" alt="UCSB logo">
  </div>
  <div class="cv-logo-text">
    <strong>University of California, Santa Barbara (UCSB)</strong><br>
    Tracking thermal effects using backscattered electron diffraction (BSED) — 2024
  </div>
</div>

<div class="cv-logo-row">
  <div class="cv-logo">
    <img src="/images/KAUST.webp" alt="KAUST logo">
  </div>
  <div class="cv-logo-text">
    <strong>King Abdullah University of Science and Technology (KAUST)</strong><br>
    Synthesis of MXene for a self-healing material — 2019
  </div>
</div>

<div class="cv-logo-row">
  <div class="cv-logo">
    <img src="/images/KAUST.webp" alt="KAUST logo">
  </div>
  <div class="cv-logo-text">
    <strong>King Abdullah University of Science and Technology (KAUST)</strong><br>
    Transfer of graphene to suitable substrates — 2018
  </div>
</div>

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

<h2>Skills</h2>
<ul>
  <li><strong>Ultrafast Spectroscopy & Microscopy:</strong> 4D-USEM, pump–probe techniques.</li>
  <li><strong>Optical Setups:</strong> Fiber laser, Ti:Sapphire system, free-space optics, hands-on alignment and optimization.</li>
  <li><strong>Materials Characterization:</strong> Surface and interfacial carrier dynamics, recombination pathways, ion migration.</li>
  <li><strong>Data Analysis:</strong> Quantitative analysis of time-resolved measurements using MATLAB and Python.</li>
</ul>

</div>
