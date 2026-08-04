---
layout: archive
permalink: /
title: "Welcome"
image:
  feature: banner-wide.svg
---

The Cellular Computing team is an interdisciplinary research team focusing
on bioengineering of genetic circuits in cells, with increasing
levels of complexity: going from molecular-level models to multicellular
circuits. By integrating experimental data with mathematical modeling, we
strive to understand and predict the behavior of these circuits, facilitating
their optimization and scaling up. Finally, we use the knowledge generated to
build computer-aided design (CAD) tools to automate the process of designing
new genetic circuits with diverse functionalities. We aim to advance the field
of synthetic biology and pave the way for transformative applications in
biotechnology and beyond.

## CELLS Workshop

We are organizing the workshop [Computing Among Cells (CELLS)](https://www.cellularcomputing.team/CELLS).

## Affiliations

Our Research Team is located at the following institutions of the [Université Paris-Saclay](https://www.universite-paris-saclay.fr/en):

- [Institut Micalis](https://www.micalis.fr/), [Université Paris-Saclay](https://www.universite-paris-saclay.fr/en) / [INRAE Jouy-en-Josas](https://www.inrae.fr/en/centres/ile-france-jouy-josas-antony) / [AgroParisTech](https://www.agroparistech.fr/en)
- [Laboratoire Méthodes Formelles](https://lmf.cnrs.fr/), [Université Paris-Saclay](https://www.universite-paris-saclay.fr/en) / [CNRS](https://www.cnrs.fr/en) / [ENS Paris-Saclay](https://ens-paris-saclay.fr/en)

## Funding Support

We thank the following funding sources for supporting our research.

<style>
.funder-grid > p {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  gap: 20px;
  align-items: center;
  justify-items: center;
  margin: 2em 0;
}
.funder-grid img { max-width: 100%; height: auto; }
</style>

<div class="funder-grid" markdown="1">
![ANR](/images/anr_logo.png)
![UPSaclay](/images/upsaclay.png)
![INRAE_MICA](/images/mica_dept.png)
![DIM_RFSI](/images/dim_rfsi.png)
![CNRS_INS2I](/images/cnrs_ins2i.jpg)
![PEPR](/images/pepr.jpg)
![France 2030](/images/france2030.png)
![France Excellence Eiffel scholarship](/images/logo_eiffel_bourse.jpg)
![UPSaclay Graduate School Life Sciences and Health](/images/GS_LSH.jpg)
![UPSaclay Living Machines @ Work interdisciplinary object](/images/OI_LMW.jpg)
![DIM BioConvergence for Health](/images/Logo-Bioconvs-2-medium.png)
</div>




{% for post in site.posts %}
 {% include post-grid.html %}
{% endfor %}
