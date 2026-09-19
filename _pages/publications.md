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
<!-- ================= CATEGORIE 1 : LIVRES & CHAPITRES ================= -->
  <h2 class="category" style="margin-top: 2rem;">Livres & Chapitres</h2>
  {% bibliography -q @book%}
  
  <!-- ================= CATEGORIE 2 : ARTICLES ================= -->
  <h2 class="category" style="margin-top: 2rem;">Articles de Journal</h2>
  {% bibliography -q @article %}


  
</div>
