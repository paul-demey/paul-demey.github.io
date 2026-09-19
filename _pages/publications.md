---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

---
layout: page
title: publications
permalink: /publications/
description: Publications classées par catégories.
---

<div class="publications">
<!-- ================= CATEGORIE 1 : ALM ================= -->

  <h2 class="category" style="margin-top: 2rem; border-bottom: 1px solid var(--global-divider-color); padding-bottom: 0.5rem;">ALM</h2>
  {% bibliography -q @*[keywords=~ALM]* %}

  <!-- ================= CATEGORIE 2 : Gestion d'actifs ================= -->
  <h2 class="category" style="margin-top: 2rem; border-bottom: 1px solid var(--global-divider-color); padding-bottom: 0.5rem;">Gestion d'actifs</h2>
  {% bibliography -q @*[keywords=~Gestion d'actifs]* %}
  
</div>
