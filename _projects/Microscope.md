---
layout: page
title: Microscope
description: Lattices with single site resolved imaging
img: assets/img/microscope_SC.jpg
importance: 1
years: [2022,2021,2020]

# category: work
---
In this project we are buidling a quantum gas microscope for ultracold molecules. 

Ultracold molecules 

A quantum gas microscope is an ultracold experiment where the particles are trapped in an optical lattice, and a high resolution imaging system is used to see indivdual atoms on their lattice sites



Picture of QGM







<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f Microscope -q @*[year={{y}}]* %}
{% endfor %}

</div>