---
layout: default
title: Portfolio
permalink: /portfolio/
description: Past projects that I worked on
---

  {% for portfolio in site.portfolio %}
  <div class="col-sm-3" style="padding-top:20px">
    <div class="card" style="width: 20rem; height: 20rem;">
      <div class="card-body">
        <h4 class="card-title no-anchor" style="margin-top: -20px; font-size: 20px;">
        {{ portfolio.title }}<br>
        <a href="{{ portfolio.url }}"><img src="/assets/images/portfolio/{{ portfolio.icon }}" alt="{{ portfolio.title }} logo" style="width:200px; height:200px;"></a>
        </h4>
        <p class="card-text">{{ portfolio.description }}</p>
        <a href="{{ portfolio.url }}" class="btn btn-outline-secondary btn-sm stretched-link">Learn more</a>
      </div>
    </div>
  </div>
  {% endfor %}