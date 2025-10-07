---
layout: default
title: Home
homepage: true
hero: /assets/img/romania_cave.JPG
hero_pos: "center 40%"
hero_opacity: .34
hero_tint: .60
---

<!-- 1) Intro — plain background, black text; H1 in var(--logo-orange) -->
<section class="section intro">
  <div class="intro-title">
    <h1 style="color:var(--logo-orange);">
      <strong>Integrity in research begins with safety and respect in the field.</strong>
    </h1>
    <h2 style="margin-top:.5em; font-weight:normal;">
      <strong>We’re redefining fieldwork protocols to center consent, dignity, and accountability — because harm has no place in science.</strong>
    </h2>
  </div>

  <div class="intro-row">
    <figure class="intro-graphic">
      <img
        src="{{ '/assets/img/accountability.png' | relative_url }}"
        alt="Accountability hub with callouts: clearly stated expectations, transparent reporting systems, and shared commitment to safety."
        loading="lazy" decoding="async" fetchpriority="low">
    </figure>

    <div class="intro-copy">
      <p>
        This project was built from urgency — to make fieldwork safer for ourselves, our students, and our colleagues.
        It offers accessible, customizable tools to help researchers prevent and report sexual misconduct and other forms of behavioral harm during field research.
      </p>
      <p>
        We cannot protect our science without protecting the people who do it. Safety begins with accountability:
        clearly stated expectations, transparent reporting systems, and a shared commitment to safeguarding not just our data, but each other.
        We are researchers, educators, and students — and we deserve to work in environments built on dignity, consent, and respect.
      </p>
    </div>
  </div>
</section>

<!-- 2) Prevalence — orange pill, side-by-side -->
<section class="pillband pill--orange">
  <div class="section split">
    <div class="text">
      <h2>Prevalence of Fieldwork Harassment and Assault</h2>
      <p>
        A 2014 survey sampling &gt;650 anthropologists revealed high frequencies of harassment and assault,
        and low frequencies of awareness of reporting procedures (Clancy <em>et&nbsp;al.</em>, 2014;
        DOI: <a href="https://doi.org/10.1371/journal.pone.0102172">10.1371/journal.pone.0102172</a>).
      </p>
    </div>

    <figure class="art">
      <img src="{{ '/assets/img/prevalence-graphic.png' | relative_url }}" alt="Infographic summarizing prevalence findings.">
      <!-- <figcaption>64% experienced sexual harassment; 21% experienced sexual assault during fieldwork.</figcaption> -->
    </figure>
  </div>
</section>

<!-- 3) What’s at stake -->
<section class="pillband pill--sage pill--clip-right">
  <div class="section">
    <h2>What’s at stake</h2>
    <p>Unsafe fieldwork harms people and science. It drives students out of the discipline, silences witnesses, and biases what gets studied, published, and funded.</p>
    <blockquote style="margin:0; font-style:italic; opacity:.95">
      “I didn’t know who to tell without risking my degree.”
    </blockquote>
  </div>
</section>

<!-- 4) Our approach -->
<section class="pillband pill--slate pill--clip-left">
  <div class="section" style="gap:22px;">
    <h2 style="color:#fff; margin-bottom:.2em;">Our approach</h2>
    <div class="section" style="padding:0; grid-template-columns:repeat(auto-fit,minmax(240px,1fr)); gap:16px;">
      <div class="card">
        <h3>Prevention</h3>
        <p>Clear expectations, advisor–advisee agreements, and pre-fieldwork safety planning.</p>
      </div>
      <div class="card">
        <h3>Reporting</h3>
        <p>Straightforward paths to Title IX, funding bodies, and professional associations—with documentation tools.</p>
      </div>
      <div class="card">
        <h3>Accountability</h3>
        <p>Transparent follow-ups, climate surveys, and culture change grounded in data.</p>
      </div>
    </div>

    <div>
      <h3 style="color:#fff;">Start with practical tools</h3>
      <p><a class="bubble" href="{{ '/preparing/' | relative_url }}">Pre-Fieldwork Safety Checklist</a></p>
      <p><a class="bubble" href="{{ '/reporting/'  | relative_url }}">Reporting portals</a></p>
      <p><a class="bubble" href="{{ '/surveys/'    | relative_url }}">Anonymous surveys</a></p>
    </div>
  </div>
</section>

<!-- Optional: Resources block (standard section, no pill) -->
<section class="section">
  <div class="docs-container safety-plan">
    <h2>Build Your Fieldwork Safety Plan</h2>
    <p>Download and customize your safety materials below to protect yourself and your team.</p>
    <div class="doc-links" style="display:grid; grid-template-columns:repeat(auto-fit,minmax(260px,1fr)); gap:16px;">
      <div class="doc-card card">
        <h3>Fieldwork Safety Plan</h3>
        <p>A personal safety plan template for researchers.</p>
        <a href="https://docs.google.com/document/d/1OkEMW4VhpsccA_VZTTEvgBBq5vs0mCOEDg9Xk6f34Ss/edit?usp=sharing"
           target="_blank" rel="noopener noreferrer">Open Google Doc</a>
      </div>
      <div class="doc-card card">
        <h3>Collaborator Safety Commitment Agreement</h3>
        <p>A team-wide agreement on ethical and safe fieldwork protocols.</p>
        <a href="https://docs.google.com/document/d/18SmymYAFKUz_drbDhcsx8NWaiNG6-SQflWPj0OaZ76c/edit?usp=sharing"
           target="_blank" rel="noopener noreferrer">Open Google Doc</a>
      </div>
    </div>
  </div>
</section>
