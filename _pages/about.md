---
permalink: /
title: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
.about-card {
  max-width: 2000px;
  margin: 30px auto 45px auto;
  padding: 40px;
}

.about-card h1 {
  font-size: 2.3em;
  line-height: 1.1;
  margin-top: 0;
  margin-bottom: 8px;
}

.about-card h2 {
  font-size: 1.5em;
  font-style: italic;
  margin-top: 0;
  margin-bottom: 25px;
}

.about-row {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 300px;
  gap: 35px;
  align-items: start;
}

.about-text {
  font-size: 1.05em;
  line-height: 1.75;
}

.about-photo img {
  width: 300px;
  max-width: 100%;
  height: auto;
  border-radius: 6px;
}

.about-landscape {
  max-width: 1050px;
  margin: 0 auto 25px auto;
}

.about-landscape img {
  width: 100%;
  height: 300px;
  object-fit: cover;
  border-radius: 6px;
}

.about-research-note {
  max-width: 850px;
  margin: 0 auto;
  font-size: 1.1em;
  line-height: 1.75;
}

@media (max-width: 800px) {
  .about-row {
    grid-template-columns: 1fr;
  }

  .about-photo img {
    width: 100%;
  }

  .about-card {
    padding: 25px;
  }

  .about-card h1 {
    font-size: 2.2em;
  }

  .about-landscape img {
    height: 230px;
  }
}
</style>

<div class="about-card">

  <h1> Oscar Cortes-Azuero, PhD</h1>
  <h2>Infectious Disease Epidemiologist</h2>

  <div class="about-row">

    <div class="about-text">

      <p>
      I am a Postdoctoral Researcher at the <a href="https://www.pdu.gen.cam.ac.uk/">Pathogen Dynamics Unit, University of Cambridge</a>.
      </p>

      <p>
      My research focuses on developing mathematical and statistical models to understand the burden, dynamics, and evolution of pathogens, with the aim of optimizing prevention and mitigation strategies.
      </p>

      <p>
      I build models that pool information from surveillance, serological, genomic, and behavioral data. Much of my work focuses on emerging infectious diseases: how they spread, how our changing climate can shift their threat, and how novel countermeasures can mitigate their burden.
      </p>


    </div>

    <div class="about-photo">
      <img src="/images/profile.jpeg" alt="Oscar Cortes-Azuero">
    </div>

  </div>

</div>