---
layout: default
title: Home
homepage: true
hero: /assets/img/romania_cave.JPG
hero_pos: "center 40%"
hero_opacity: .45
hero_tint: .40
---
<style>
/* Exact 50/50 two-column layout; stacks on small screens */
.split-equal{
  display:grid;
  grid-template-columns: 1fr 1fr;         /* equal widths */
  gap: clamp(16px, 3vw, 28px);
  align-items:start;
}
.split-equal > .col{ min-width:0; }       /* prevent overflow/wrapping issues */

@media (max-width: 760px){
  .split-equal{ grid-template-columns: 1fr; }
}


a.hover-sage:hover{
  text-color: var(--sage);
  text-decoration-color: var(--sage);
}
</style>

<!-- 1) Intro – plain background -->
<section class="section intro">
  <div class="intro-title">
    <h1><strong>Integrity in research begins with safety and respect in the field.</strong></h1>
<br>
    <h2 style="font-weight:600;">
      We’re redefining fieldwork protocols to center consent, dignity, and accountability — because harm has no place in science.
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
      
      <p>This project was built from urgency — to make fieldwork safer for ourselves, our students, and our colleagues. It offers accessible, customizable tools to help researchers prevent and report sexual misconduct and other forms of behavioral harm during field research.</p>
      <br>
       <p>We cannot protect our science without protecting the people who do it. Safety begins with accountability: clearly stated expectations, transparent reporting systems, and a shared commitment to safeguarding not just our data, but each other.
        We are researchers, educators, and students — and we deserve to work in environments built on dignity, consent, and respect.</p>
    </div>
  </div>
</section>

<div class="stripe stripe--wave-dark"
     style="--stripe-bleed-top:30px; --stripe-bleed-bottom:5px;">
<!-- 2) PREVALENCE — shared split -->
<section class="section">
<h2 class="pillhead pill--orange pill--clip-right">Prevalence of Fieldwork Harassment and Assault
</h2>
  <div class="split">
    <div class="text">
       <p>A 2014 survey sampling &gt;650 anthropologists revealed high frequencies of harassment and assault, and low frequencies of awareness of reporting procedures (Clancy <em>et&nbsp;al.</em>, 2014; DOI: <strong><a class= "hover-sage" href="https://doi.org/10.1371/journal.pone.0102172"  target="_blank" 
     rel="noopener noreferrer"  style="color:var(--slate);">10.1371/journal.pone.0102172</a></strong>).</p>
    </div>
    <figure class="art">
      <img
        src="{{ '/assets/img/prevalencegraphic.png' | relative_url }}"
        alt="Infographic summarizing findings of Clancy et al., 2014.
64% of participants experienced sexual harassment during fieldwork, 21% of participants experienced sexual assault during fieldwork, 20% were aware of reporting mechanisms prior to the survey."
        loading="lazy" decoding="async">
    </figure>
  </div>
</section>
</div>


<!-- 3) PREPARING — pillband -->
<section class="pillband pill--soil pill--clip-left pill--earlywrapl">
  <div class="section resources">    
<h2>Preparing for fieldwork includes proactive safety planning.</h2>
<div class="resources-grid">
      <article class="resource-card">
        <h3>Fieldwork Safety Plan</h3>
        <p>A personal safety plan template for researchers.</p>
        <p>
          <a class="btn-doc"
  href="https://docs.google.com/document/d/1OkEMW4VhpsccA_VZTTEvgBBq5vs0mCOEDg9Xk6f34Ss/edit?usp=sharing"
             target="_blank" rel="noopener noreferrer">Open Google Doc</a>
        </p>
      </article>

      <article class="resource-card">
        <h3>Collaborator Safety Commitment</h3>
        <p>A team-wide agreement on ethical and safe fieldwork protocols.</p>
        <p>
          <a class="btn-doc"
             href="https://docs.google.com/document/d/18SmymYAFKUz_drbDhcsx8NWaiNG6-SQflWPj0OaZ76c/edit?usp=sharing"
             target="_blank" rel="noopener noreferrer">Open Google Doc</a>
        </p>
      </article>
    </div>
  </div>
</section>

<section class="section section--prep">
    <div class="split split--prep">
      <div class="text">
        <p>
          <strong>This website provides essential resources and education for researchers to
          prevent and report harmful behavior. This website will help you:</strong>
        </p>
      <figure class="art">
        <img
          src="{{ '/assets/img/prep.png' | relative_url }}"
          alt="1. Identify local emergency and institutional contacts — police, hospitals, embassies, and campus safety offices.
2. Review key local laws and policies (e.g., recording, misconduct) with links to verify details.
3. Learn clear, respectful ways to communicate boundaries that protect your safety and professionalism in research settings.
4. Customize a fieldwork safety-plan & complete step-by-step checklists to map contacts, risks, and action steps.
5. Commit to safe fieldwork practices with your collaborators by customizing  and signing the collaborator safety agreement."
          loading="lazy" decoding="async">
      </figure>
    </div>
  <div class="text text--right"> 
  <p>
    A growing body of research suggests that training in boundary-setting and self-defense is
    not just reactive — it can <strong>shift how we respond under threat</strong>. For example,
  </p>
  <ul>
    <li>empowerment self-defense (ESD) programs have demonstrated increased assertiveness, reduced fear in risky environments, and stronger self-protective decision-making <a href="https://doi.org/10.1177/08862605221082734"  target="_blank" 
     rel="noopener noreferrer">(Beaujolais, 2023; </a><a href="https://doi.org/10.33043/SSWJ.2.1.63-76"  target="_blank" 
     rel="noopener noreferrer">Follo, 2022).</a></li>
    <li>Other efforts in trauma prevention and rape-resistance place such training within evidence-based prevention strategies <a href="https://doi.org/10.1080/10926771.2022.2046224">(Basile, 2022).</a></li>
  </ul>
  <p>
    These suggest that when we practice setting boundaries and preparing responses in advance,
    we may be less likely to default to appeasement or freeze patterns in moments of threat.
  </p>
</div>
</div>
</section>

<div class="stripe stripe--wave-dark"
     style="--stripe-bleed-top:30px; --stripe-bleed-bottom:5px;">
<!-- 4) SUPPORT — consistent grid utility -->
<section class="section">
<h2 class="pillhead pill--slate pill--clip-right">Survivor Support</h2>
  <div class="split-equal">
    <div class="col"> 
 <h3><a class="hover-sage" href="{{ '/support.html' | relative_url }}"  target="_blank" 
     rel="noopener noreferrer"  style="color:var(--slate);">Supporting You</a></h3>
<p>Access survivor-centered resources focused on emotional support, recovery, and community care. This page highlights mental-health hotlines, trauma-informed care networks, and guidance on seeking help after an incident—because your safety and well-being come first.</p>
</div>
   <div class="col">
<div class="inline-elements">   
<h4><a class="hover-sage" href="https://takebackthenight.org/"  target="_blank" 
     rel="noopener noreferrer"  style="color:var(--slate);">TBTN</a>: <p>Take Back the Night</p></h4></div>
<p>National Sexual Assault Legal Hotline: Free Legal Assistance for Survivors Call 567-SHATTER (567-742-8837)</p>
<br>
<div class="inline-elements">   
<h4><a class="hover-sage" href="https://www.hotpeachpages.net/a/countries.html"  target="_blank" 
     rel="noopener noreferrer"  style="color:var(--slate);">Hot Peach Pages</a>: <p>International List of Sexual & Domestic Violence Agencies</p></h4></div>
<br>
<div class="inline-elements">   
<h4><a class="hover-sage" href="https://www.interaction.org/wp-content/uploads/resource-library/international_centers_for_survivors_of_sexual_assault_45553.pdf"  target="_blank" rel="noopener noreferrer"  style="color:var(--slate);">interaction.org</a>: <p>Handbook of International Centers for Survivors of Sexual Assault and Harassment</p></h4></div>
<br>
<div class="inline-elements">   
<h4><a class="hover-sage" href="https://rainn.org/"  target="_blank" 
     rel="noopener noreferrer"  style="color:var(--slate);">RAINN</a>: <p>Rape, Abuse & Incest National Network</p></h4></div>
<br>
<div class="inline-elements">   
<h4><a class="hover-sage" href="https://ilga.org/"  target="_blank" 
     rel="noopener noreferrer"  style="color:var(--slate);">ILGA World</a>: <p>International Lesbian, Gay, Bisexual, Trans, and Intersex Association</p></h4></div>
</div>
</div>
</section>
<br>
</div>

<!-- 5) REPORTING — consistent grid utility -->
<section class="pillband pill--sage pill--clip-left pill--tight">
 <div class="section">
    <h2>Reporting sexual misconduct in the field is possible whether you conduct research domestically or internationally.</h2>
    <p class="lede">Whether you wish to file a report or not, there are resources available to support you.</p>
</div>
</section> 
  
<section class="section">
  <div class="pill-grid"> 
 <article class="card card--glass">
      <h3>Prevention</h3>
      <p>The <strong><a href="https://docs.google.com/document/d/1jdA2Iz-ALuxHU-jHoH5CLHHMJhotDdCoATkuu8lDrug/edit?usp=sharing" target="_blank" rel="noopener">Pre-Fieldwork Safety Checklist</a></strong> helps you plan proactively—identifying risks, setting clear expectations, and documenting safety measures before entering the field. It also includes options for capturing proof of misconduct to support reporting without fear of dismissal.
      </p>
    </article>

<article class="card card--glass">
      <h3>Action</h3>
 <p>The <strong><a href="https://docs.google.com/document/d/1MJgV6zWpse_j56-pG34uMZzVBxhifiIYZdU-F7TGbes/edit?usp=sharing" target="_blank" rel="noopener">Emergency Procedure Checklist</a></strong> outlines step-by-step actions prior to and following sexual misconduct outlining how to collect evidence, who to contact, how to document, and how to ensure inter-institutional accountability.</p>
<br>   
<p>Find clear, verified paths to <strong><a href="{{ '/reporting.html' | relative_url }}"  target="_blank" rel="noopener noreferrer">report misconduct</a></strong> through your institution, funding agencies, embassies, and local authorities—with documentation tools designed to preserve your evidence and amplify your voice.
      </p>
    </article>

 <article class="card card--glass">
      <h3>Creating Change</h3>
  <p>
    Help us understand the current state of fieldwork safety by participating in our  <strong>anonymous survey</strong>. The 
    <strong><a href="https://forms.gle/YjAmqWd9xDC5WCJk8" target="_blank" rel="noopener">Fieldwork Misconduct Survey</a></strong> 
    gathers community-driven, anonymous data on harassment and misconduct to update the only major prevalence study (<em>Clancy et&nbsp;al.,&nbsp;2014</em>). 
    Your participation helps highlight how much change is still needed—and why these resources matter. Together, we can use these data to drive 
    accountability and create safer fieldwork environments.
  </p>
 </article>
  </div>
</section>


