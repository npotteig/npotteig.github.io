---
layout: about
title: home
permalink: /

profile:
  align: right
  image: self.jpeg

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

I am currently a third-year Computer Science Ph.D. Candidate at Vanderbilt University under the advisorship of [Dr. Xenofon Koutsoukos](https://engineering.vanderbilt.edu/bio/xenofon-koutsoukos). My research primarily revolves around explainable AI, safety, and reinforcement learning for autonomous cyber-physical systems, specifically UAVs. Before starting my academic endeavors at Vanderbilt, I completed a bachelor's degree in Computer Sceince and Mathematics at the University of Maryland, Baltimore County (UMBC). During my time at UMBC, I had the privelege of conducting research in multiple summer undergraduate experiences at the University of Notre Dame, Yale University, and Vanderbilt University. There, I explored topics involving big data workflows, image classification of galaxies, and anomaly detection in vehicle cameras. This led me to enjoy understanding the various facets that machine learning can be applied to solve our society's toughest challenges.

## Software

<!-- code for GitHub repositories -->
{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}