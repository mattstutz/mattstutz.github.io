---
layout: single
classes: wide
title: "Portfolio"
permalink: /portfolio/
collection: portfolio
entries_layout: grid
author_profile: true
classes: wide
---

<div class="entries-grid">
  {% assign sorted_portfolio = site.portfolio | sort: 'position' %}
  {% for post in sorted_portfolio %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
