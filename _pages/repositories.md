---
layout: page
permalink: /repositories/
title: repositories
description: Selected open-source projects and security research repositories by Shuo Yang.
nav: true
nav_order: 4
---

{% if site.data.repositories.github_users %}

## GitHub users

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>

---

{% if site.repo_trophies.enabled %}
{% for user in site.data.repositories.github_users %}
{% if site.data.repositories.github_users.size > 1 %}

  <h4>{{ user }}</h4>
  {% endif %}
  <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo_trophies.liquid username=user %}
  </div>

---

{% endfor %}
{% endif %}
{% endif %}

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-stretch">
  {% for repo in site.data.repositories.github_repos %}
    {% assign repo_url = repo | split: '/' %}
    {% if site.data.repositories.github_users contains repo_url.first %}
      {% assign show_owner = false %}
    {% else %}
      {% assign show_owner = true %}
    {% endif %}
    {% assign max_lines = site.data.repositories.repo_description_lines_max | default: 2 %}
    {% assign stats_url = site.external_services.github_readme_stats_url | default: 'https://github-stats-extended.vercel.app' %}
    <div class="repo p-2 text-center" style="display: flex; flex-direction: column;">
      <a href="https://github.com/{{ repo }}" style="display: block; width: 100%; height: 100%;">
        <img
          class="only-light w-100"
          alt="{{ repo }}"
          src="{{ stats_url }}/api/pin/?username={{ repo_url[0] }}&repo={{ repo_url[1] }}&theme={{ site.repo_theme_light }}&locale={{ lang | default: 'en' }}&show_owner={{ show_owner }}&description_lines_count={{ max_lines }}&browser_rendering=true"
          onerror="this.closest('.repo').style.display='none'"
        >
        <img
          class="only-dark w-100"
          alt="{{ repo }}"
          src="{{ stats_url }}/api/pin/?username={{ repo_url[0] }}&repo={{ repo_url[1] }}&theme={{ site.repo_theme_dark }}&locale={{ lang | default: 'en' }}&show_owner={{ show_owner }}&description_lines_count={{ max_lines }}&browser_rendering=true"
          onerror="this.closest('.repo').style.display='none'"
        >
      </a>
    </div>
  {% endfor %}
</div>
{% endif %}
