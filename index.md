---
layout: archive
permalink: /
title: "Welcome"
image:
  feature: banner-wide.svg
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

## Affiliations
Our Research Group is affiliated to the following institutions at the [University of Paris-Saclay](https://www.universite-paris-saclay.fr/en "https://www.universite-paris-saclay.fr/en"):
- [Institut Micalis](https://www.micalis.fr/micalis_eng/Home/Micalis-Institute/ "https://www.micalis.fr/micalis_eng/Home/Micalis-Institute/")
- [ENS Paris-Saclay](https://ens-paris-saclay.fr/en "https://ens-paris-saclay.fr/en")


## Funding Support
We thanks the following funding sources for supporting our research. 
- [ANR, project DREAMY](https://dreamy.run/ "https://dreamy.run/")
- U.Paris-Saclay, project ETSHI
- INRAE MICA, project PHEMO
- Ile-de-France DIM-RFSI, project COMBACT
- U.Paris-Saclay STIC, project DEPEC-MODE
- INS2I CNRS, project BACON

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
