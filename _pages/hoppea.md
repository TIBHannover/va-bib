---
layout: page
permalink: /hoppea
title: Dr. Anett Hoppe
description: Publications in reversed chronological order. Generated by jekyll-scholar.
nav: true
nav_type: false
nav_year: true
nav_order: 3  # 1 - group, 2 - group leader, 3 - postdocs, 4 - phds
---

<!-- _pages/hoppea.md -->
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} --query @*[author ~= Hoppe] %}

</div>
