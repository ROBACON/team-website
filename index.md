---
layout: archive
permalink: /
title: "Welcome"
image:
  feature: 
---

The Cellular Computing group is an interdisciplinary research group focusing
on bioengineering of genetic circuits in bacterial cells, with increasing
levels of complexity: going from molecular-level models to multicellular
circuits. By integrating experimental data with mathematical modeling, we
strive to understand and predict the behavior of these circuits, facilitating
their optimization and scaling up. Finally, we use the knowledge generated to
build computer-aided design (CAD) tools to automate the process of designing
new genetic circuits with diverse functionalities. We aim to advance the field
of synthetic biology and pave the way for transformative applications in
biotechnology and beyond.

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
