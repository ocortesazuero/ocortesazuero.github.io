---
permalink: /
title: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>

@media (min-width: 925px) {
  .page {
    float: none;
    width: 85%;
    margin-left: auto;
    margin-right: auto;
    padding-left: 0;
    padding-right: 0;
  }
}

.about-card {
  max-width: 2000px;
  margin: 0 auto 0 auto;
  padding: 0;
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

.about-links {
  list-style: none;
  margin: 15px 0 0 0;
  padding: 0;
}

.about-links li {
  white-space: nowrap;
}

.about-links a {
  display: block;
  margin-bottom: 5px;
  padding: 2px 5px 2px 0;
  color: inherit;
  font-size: 1em;
  text-decoration: none;
}

.about-links a:hover {
  text-decoration: underline;
}

.about-links i {
  padding-right: 1.5em;
}

@media (max-width: 800px) {
  .about-row {
    grid-template-columns: minmax(0, 1fr);
    gap: 20px;
  }

  /* Photo and links sit side by side, above the bio. */
  .about-side {
    order: -1;
    display: flex;
    gap: 16px;
  }

  .about-photo {
    flex: 0 0 min(38%, 135px);
  }

  .about-photo img {
    display: block;
    width: 100%;
  }

  /* Spreads the links over the full height of the photo. */
  .about-links {
    flex: 1 1 auto;
    min-width: 0;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin: 0;
  }

  .about-links a {
    margin-bottom: 0;
    padding: 0;
  }

  .about-links i {
    padding-right: 0;
    margin-right: 0.6em;
  }

  .about-card {
    padding: 25px 0;
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

    <div class="about-side">
      <div class="about-photo">
        <img src="/images/profile.jpeg" alt="Oscar Cortes-Azuero">
      </div>
      <ul class="about-links social-icons">
        {% if site.author.email %}
          <li><a href="mailto:{{ site.author.email }}"><i class="fas fa-fw fa-envelope" aria-hidden="true"></i>Email</a></li>
        {% endif %}
        {% if site.author.github %}
          <li><a href="https://github.com/{{ site.author.github }}"><i class="fab fa-fw fa-github" aria-hidden="true"></i>GitHub</a></li>
        {% endif %}
        {% if site.author.orcid %}
          <li><a href="{{ site.author.orcid }}"><i class="ai ai-orcid ai-fw" aria-hidden="true"></i>ORCID</a></li>
        {% endif %}
        {% if site.author.googlescholar %}
          <li><a href="{{ site.author.googlescholar }}"><i class="fas fa-fw fa-graduation-cap" aria-hidden="true"></i>Google Scholar</a></li>
        {% endif %}
      </ul>

    </div>

  </div>

</div>