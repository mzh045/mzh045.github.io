---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<!-- 书籍暂不展示：如需恢复，在下方加回
     ## Books
     <div class="publications">{% bibliography -f books %}</div>
     （books.bib 数据仍保留在 _bibliography/ 中） -->

## Papers

<div class="publications">

{% bibliography -f papers %}

</div>
