---
layout: page
permalink: /ewerthr-type
title: Prof. Dr. Ralph Ewerth
description: Publications by categories in reversed chronological order. Generated by jekyll-scholar.
nav: true
nav_type: true
nav_year: false
nav_order: 2  # 1 - group, 2 - group leader, 3 - postdocs, 4 - phds
---

<!-- _pages/ewerthr-type.md -->
<div class="publications">

{% assign groupby = "type, year" %}
{% bibliography -f {{ site.scholar.bibliography }} --query @*[author ~= Ewerth] --group_by {{ groupby }} %}

</div>
