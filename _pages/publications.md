---
layout: page
title: publications
permalink: /publications/
description: 
nav: true
nav_order: 2
display_categories: [ALM, Gestion d'actifs]
horizontal: false
---



<div class="publications">


<!-- ================= CATEGORIE 1 : ALM ================= -->

  <h2 class="category" style="margin-top: 2rem; border-bottom: 1px solid var(--global-divider-color); padding-bottom: 0.5rem;">ALM</h2>
{% bibliography -q @*[keywords=ALM]* %}

  <!-- ================= CATEGORIE 2 : Gestion d'actifs ================= -->
  <h2 class="category" style="margin-top: 2rem; border-bottom: 1px solid var(--global-divider-color); padding-bottom: 0.5rem;">Gestion d'actifs</h2>
{% bibliography -q @*[keywords=GA]* %}

  
  <!-- ================= CATEGORIE 2 : Credit ================= -->
  <h2 class="category" style="margin-top: 2rem; border-bottom: 1px solid var(--global-divider-color); padding-bottom: 0.5rem;">Risque de crédit</h2>
{% bibliography -q @*[keywords=Credit]* %}
  
</div>
