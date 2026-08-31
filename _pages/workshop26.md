---
layout: default
permalink: /workshop26/
title: Workshop on Geometry, Learning and 3D Understanding 2026
description: A pre-ECCV mini-workshop in Lund on September 7, 2026.
nav: false
hide_navbar: true
noindex: true
sitemap: false
---

<main class="workshop26">
  <header class="workshop-hero">
    <p class="workshop-kicker">Pre-ECCV mini-workshop</p>
    <h1>Workshop on Geometry, Learning and 3D Understanding 2026</h1>
    <p class="workshop-intro">
      An afternoon of talks and discussion on learning-based 3D vision, spanning image matching, reconstruction,
      geometric reasoning, and structured scene representations. Attendance is open to everyone.
    </p>
    <ul class="workshop-facts" aria-label="Workshop details">
      <li><i class="fa-solid fa-calendar" aria-hidden="true"></i> Monday, September 7, 2026</li>
      <li><i class="fa-solid fa-clock" aria-hidden="true"></i> 15:00–17:15</li>
      <li><i class="fa-solid fa-location-dot" aria-hidden="true"></i> MH:Riesz, first floor, Mathematics Building, Lund University</li>
    </ul>
  </header>

  <section class="workshop-section" aria-labelledby="schedule-heading">
    <h2 class="workshop-section-title" id="schedule-heading">Schedule</h2>
    <p class="schedule-status">Preliminary schedule — subject to change</p>
    <ol class="workshop-schedule">
      <li class="schedule-item is-break">
        <time class="schedule-time" datetime="2026-09-07T15:00">15:00–15:15</time>
        <span class="schedule-session">Welcome coffee</span>
        <span class="schedule-note">15 minutes</span>
      </li>
      <li class="schedule-item">
        <time class="schedule-time" datetime="2026-09-07T15:15">15:15–15:45</time>
        <span class="schedule-session">Na Zhao</span>
        <span class="schedule-note">Talk and questions</span>
      </li>
      <li class="schedule-item">
        <time class="schedule-time" datetime="2026-09-07T15:45">15:45–16:15</time>
        <span class="schedule-session">David Nordström</span>
        <span class="schedule-note">Talk and questions</span>
      </li>
      <li class="schedule-item is-break">
        <time class="schedule-time" datetime="2026-09-07T16:15">16:15–16:30</time>
        <span class="schedule-session">Break</span>
        <span class="schedule-note">15 minutes</span>
      </li>
      <li class="schedule-item">
        <time class="schedule-time" datetime="2026-09-07T16:30">16:30–17:00</time>
        <span class="schedule-session">Fadi Khatib</span>
        <span class="schedule-note">Talk and questions</span>
      </li>
      <li class="schedule-item">
        <time class="schedule-time" datetime="2026-09-07T17:00">17:00–17:15</time>
        <span class="schedule-session">Gustav Hanning</span>
        <span class="schedule-note">15-minute talk</span>
      </li>
    </ol>
  </section>

  <section class="workshop-section" aria-labelledby="speakers-heading">
    <h2 class="workshop-section-title" id="speakers-heading">Speakers</h2>
    <div class="speaker-list">
      <article class="speaker-card">
        <a href="https://na-z.github.io/" aria-label="Visit Na Zhao’s website">
          <img class="speaker-portrait" src="{{ '/assets/img/workshop26/na-zhao.png' | relative_url }}" alt="Na Zhao">
        </a>
        <div>
          <h3 class="speaker-name"><a href="https://na-z.github.io/">Na Zhao</a></h3>
          <p class="speaker-affiliation">Singapore University of Technology and Design</p>
          <h4 class="talk-title">Generalizable, Semantic, and Editable 3D Scene Reconstruction</h4>
          <p class="talk-abstract">
            Recent advances have made high-quality 3D reconstruction increasingly practical. However, photorealistic
            rendering alone is not enough for many downstream applications: reconstructed scenes should also generalize
            to unseen environments, capture meaningful semantic structure, and support intuitive editing and manipulation.
            In this talk, I will present our recent work toward this broader goal of generalizable, semantic, and editable
            3D scene reconstruction. I will first discuss generalizable reconstruction from sparse views, focusing on how
            explicit geometric constraints and learned multi-view correspondence can be combined for robust and efficient
            reconstruction. I will then show how geometry can serve not only as an output, but also as a foundation for
            cross-view semantic reasoning, progressing from geometry–semantics synergy to open-vocabulary 3D semantic
            fields from unposed images. Finally, I will introduce compositional scene representations that combine
            interpretable geometric primitives with high-fidelity 3D Gaussians, enabling part-aware and physically
            meaningful editing. Together, these works explore how 3D reconstruction can evolve toward building structured,
            understandable, and actionable representations of the 3D world.
          </p>
        </div>
      </article>

      <article class="speaker-card">
        <a href="https://www.davnords.com/" aria-label="Visit David Nordström’s website">
          <img class="speaker-portrait" src="{{ '/assets/img/workshop26/david-nordstrom.jpg' | relative_url }}" alt="David Nordström">
        </a>
        <div>
          <h3 class="speaker-name"><a href="https://www.davnords.com/">David Nordström</a></h3>
          <p class="speaker-affiliation">Chalmers University of Technology</p>
          <h4 class="talk-title">Learning to Understand 3D</h4>
          <p class="talk-tba">Talk details forthcoming.</p>
        </div>
      </article>

      <article class="speaker-card">
        <a href="https://fadikhatib.github.io/" aria-label="Visit Fadi Khatib’s website">
          <img class="speaker-portrait" src="{{ '/assets/img/workshop26/FadiKhatib_2025.jpg' | relative_url }}" alt="Fadi Khatib">
        </a>
        <div>
          <h3 class="speaker-name"><a href="https://fadikhatib.github.io/">Fadi Khatib</a></h3>
          <p class="speaker-affiliation">Weizmann Institute of Science</p>
          <p class="talk-tba">Talk title and abstract to be announced.</p>
        </div>
      </article>

      <article class="speaker-card">
        <a href="https://ghanning.github.io/" aria-label="Visit Gustav Hanning’s website">
          <img class="speaker-portrait" src="{{ '/assets/img/workshop26/gustav-hanning.jpeg' | relative_url }}" alt="Gustav Hanning">
        </a>
        <div>
          <h3 class="speaker-name"><a href="https://ghanning.github.io/">Gustav Hanning</a></h3>
          <p class="speaker-affiliation">Lund University</p>
          <h4 class="talk-title">PolyLayout: Multi-room Manhattan Layout Estimation</h4>
          <p class="talk-abstract">
            Gustav will present PolyLayout, his ECCV 2026 paper on multi-room Manhattan layout estimation. The talk will
            introduce the problem, outline the proposed approach, and discuss how it reconstructs consistent indoor geometry
            across multiple rooms.
          </p>
        </div>
      </article>
    </div>
  </section>
</main>
