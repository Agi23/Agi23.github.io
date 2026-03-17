---
layout: page
title: experience
permalink: /experience/
description: 
nav: true
nav_order: 3
---


<div class="edu-entry">
  <div class="edu-logo">
    <img src="{{ '/assets/img/example.jpg' | relative_url }}" alt="UCT image">
  </div>
  <div class="edu-content">
    <h2>Teaching</h2>
    <p><strong>University of Cape Town</strong></p>

    <h3>Teaching Assistant - EEE2046F: Embedded Systems I</h3>
    <p><strong>2023 Semester 1</strong></p>
    <ul>
      <li> Led weekly practical sessions for 194 students in coursework covering STM32 C programming and digital logic implementation.</li>
      <li> Managed a team of tutors achieving timeous assignment grading and fair marking guidelines.</li>
      <li> Assisted with general course administration including the creation of the EEE2046 Practical Instructions Documentation available here on <a href="https://github.com/Agi23/EEE2046Pracs" target="_blank" rel="noopener noreferrer">GitHub</a>.</li>
    </ul>
    <h3>Tutor</h3>
      <ul>
      <li>EEE2050F: Embedded Systems I (Head Tutor) – <strong>2023 Semester 2</strong> </li>
      <li>EEE3092F: Signals and Systems II – <strong>2021 Semester 1</strong> </li>
      <li>CSC1019F/CSC1017F: Introduction to Programming – <strong>2021 Semester 1</strong> </li>
    </ul>
  </div>
</div>

---
<div class="media-row">
  <div class="media-logo">
    <img src="{{ '/assets/img/ThinkstLogo.jpg' | relative_url }}" alt="Thinkst logo">
  </div>

  <div class="media-text">
    <h2>Software Development Intern</h2>
    <p><strong>Thinkst Canary</strong><br><em>2021</em></p>

    <p>
      I participated in a 3 week software development internship hosted by Thinkst Canary, a cyber security company.
      My work involved expanding their open-source site canarytokens.org to include a Windows Service that, once installed, triggers a Canarytoken if it is killed or uninstalled. This service also gives the option of hibernating the system on trigger.
    </p>
    <p>
      The Windows service was made in C# in Visual Studio, code integration was done in Python, and the user interface required some HTML/CSS.In the process I became more familiar with Git/GitHub and using Amazon EC2.
    </p>
    <p><a href="https://github.com/Agi23/canarytokens" target="_blank" rel="noopener noreferrer">GitHub Repository</a></p>
  </div>

  <div class="media-carousel">
    <div class="generic-carousel single-media">
      <div class="carousel-item active">
        <img
          src="{{ '/assets/img/canaryToken.png' | relative_url }}"
          class="d-block w-100"
          alt="Canarytoken">

        <div class="carousel-caption">
          <p>Carnarytoken UI screenshot</p>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="logo-grid">
  <img src="{{ '/assets/img/Logos/csharp.jpg' | relative_url }}" alt="csharp logo">
  <img src="{{ '/assets/img/Logos/python.jpg' | relative_url }}" alt="python logo">
  <img src="{{ '/assets/img/Logos/aws.jpg' | relative_url }}" alt="aws logo">
  <img src="{{ '/assets/img/Logos/html.jpg' | relative_url }}" alt="html logo">
  <img src="{{ '/assets/img/Logos/github.jpg' | relative_url }}" alt="github logo">
  <img src="{{ '/assets/img/Logos/vs.jpg' | relative_url }}" alt="vs logo">
  <img src="{{ '/assets/img/Logos/slack.jpg' | relative_url }}" alt="slack logo">
</div>

---
<div class="media-row">
  <div class="media-logo">
    <img src="{{ '/assets/img/Logos/cput.jpg' | relative_url }}" alt="SANAP logo">
  </div>

  <div class="media-text">
   <h2>Practical Training</h2>
    <p><strong>Cape Peninsula University of Technology</strong><br><em>2019</em></p>
    <p>
      I completed a 2 week workshop at the Cape Peninsula University of Technology, arranged by UCT,
      to equip students with practical engineering skills.
    </p>

    <ul>
      <li>CNC work</li>
      <li>Welding</li>
      <li>Fitting and turning</li>
      <li>Basic hand skills</li>
      <li>Metrology</li>
      <li>Pneumatics</li>
      <li>Electrical automation</li>
    </ul>
  </div>

  <div class="media-carousel">
    {% include carousel_data.html id="cputCarousel" folder="assets/img/CPUT" slides=site.data.carousels.cput %}
  </div>
</div>

---
# Volunteering
<div class="media-row">
  <div class="media-logo">
    <img src="{{ '/assets/img/expoLogo.jpg' | relative_url }}" alt="expo logo">
  </div>

  <div class="media-text">
   <h2>Regional Science Expo Judge</h2>
    <p><strong>Cape Town Regionals</strong><br><em>2022, 2023, 2025</em></p>
    <p>
      I volunteer at the Eskom Science Expo in Cape Town (usually in August), where I am part of the Engineering category judging team. It is phenomenal engaging with young students interested in science and engineering.
    </p>
  </div>

  <div class="media-carousel">
    {% include carousel_data.html id="expoCarousel" folder="assets/img/EXPO" slides=site.data.carousels.expo %}
  </div>
</div>
---
<div class="media-row">
  <div class="media-logo">
    <img src="{{ '/assets/img/example.jpg' | relative_url }}" alt="UCT logo">
  </div>

  <div class="media-text">
    <h2>Secretary</h2>
    <p><strong>UCT Biomimicry Society</strong><br><em>2019</em></p>

    <p>
      Biomimicry looks to nature for design inspiration when solving problems. I was involved in organising society events, managing announcements for the events, and handling other society administration.
    </p>
  </div>

  <div class="media-carousel">
    <div class="generic-carousel single-media">
      <div class="carousel-item active">
        <img
          src="{{ '/assets/img/biomimicry.jpg' | relative_url }}"
          class="d-block w-100"
          alt="Biomimicry">

        <div class="carousel-caption">
          <p>Illustration of Fibonacci spiral arrangement in nature (photo by Leonid Iastremskyi, 2015r)</p>
        </div>
      </div>
    </div>
  </div>
</div>