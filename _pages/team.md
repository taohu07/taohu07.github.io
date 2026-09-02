---
layout: default
permalink: /team/
title: team
nav: true
nav_order: 4
# pagination:
#   enabled: true
#   collection: posts
#   permalink: /page/:num/
#   per_page: 5
#   sort_field: date
#   sort_reverse: true
#   trail:
#     before: 1 # The number of links before the current page
#     after: 3 # The number of links after the current page
---

<style>
  .team-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.5rem 1.25rem;
    margin-bottom: 2rem;
  }
  .team-card {
    flex: 1 1 150px;
    min-width: 140px;
    max-width: 200px;
    text-align: center;
  }
  .team-card img {
    width: 100%;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    object-position: center 20%;
    border-radius: 8px;
    display: block;
    background-color: var(--global-bg-color);
  }
  .team-card .team-name {
    display: block;
    margin-top: 0.6rem;
    font-weight: 600;
    line-height: 1.3;
  }
  .team-card .team-role {
    display: block;
    margin-top: 0.15rem;
    font-size: 0.85rem;
    color: var(--global-text-color-light);
    line-height: 1.3;
  }
</style>

#### PhD Students

<div class="team-grid">
  <div class="team-card">
    <img src="{{ '/assets/img/people/people_ehsan.jpg' | relative_url }}" alt="Ehsan Foroutan" loading="lazy">
    <span class="team-name">Ehsan Foroutan</span>
    <span class="team-role">Geography</span>
  </div>
  <div class="team-card">
    <img src="{{ '/assets/img/people/yu_una.jpg' | relative_url }}" alt="Una Lixiaona Yu" loading="lazy">
    <span class="team-name">Una Lixiaona Yu</span>
    <span class="team-role">Geography</span>
  </div>
</div>

---

#### Master Students

<div class="team-grid">
  <div class="team-card">
    <img src="{{ '/assets/img/people/taiping.jpg' | relative_url }}" alt="Taiping Liu" loading="lazy">
    <span class="team-name">Taiping Liu</span>
    <span class="team-role">Statistics</span>
  </div>
  <div class="team-card">
    <img src="{{ '/assets/img/people/charen-small.jpeg' | relative_url }}" alt="Venkat Sai Divyacharan Jarugumalli" loading="lazy">
    <span class="team-name">Venkat Sai Divyacharan Jarugumalli</span>
    <span class="team-role">Computer Science</span>
  </div>
  <div class="team-card">
    <img src="{{ '/assets/img/people/karthik-small.jpg' | relative_url }}" alt="Sai Karthik Nakka" loading="lazy">
    <span class="team-name">Sai Karthik Nakka</span>
    <span class="team-role">Engineering</span>
  </div>
</div>

---

#### Undergraduate Students

<div class="team-grid">
  <div class="team-card">
    <img src="{{ '/assets/img/people/kim_beatrice.jpg' | relative_url }}" alt="Beatrice Kim" loading="lazy">
    <span class="team-name">Beatrice Kim</span>
    <span class="team-role">Computer Science</span>
  </div>
  <div class="team-card">
    <img src="{{ '/assets/img/people/jacob.jpg' | relative_url }}" alt="Jacob Mote" loading="lazy">
    <span class="team-name">Jacob Mote</span>
  </div>
  <div class="team-card">
    <img src="{{ '/assets/img/people/nobody.png' | relative_url }}" alt="Alexis Moran" loading="lazy">
    <span class="team-name">Alexis Moran</span>
  </div>
</div>
