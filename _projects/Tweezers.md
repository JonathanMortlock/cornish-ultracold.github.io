---
layout: page
title: Tweezers
description: Assembling molecules one atom at a time
img: assets/img/tweezer_plan.png
importance: 2
years: [2022,2021,2020]

# category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tweezer_plan.png" title="Tweezer Overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

# Overview of research goals

This experiment aims to explore new avenues of quantum science with ultracold polar molecules by forming single RbCs molecules in optical tweezers by associating individual Rb and Cs atoms.

Controllable arrays of ultracold molecules offer an exciting new platform for quantum experiments. For example, such arrays may be used for quantum simulation of problems ubiquitous to condensed matter physics such as lattice spin models. Alternatively, with precise single-site control, the molecules may be independently moved around and merged together in miniature particle colliders, allowing for the study of ultracold chemistry on a single particle level where quantum effects dominate.

The aim of this experiment is to form such an interacting quantum system of ultracold RbCs molecules using individual Rb and Cs atoms confined in optical tweezers. An optical tweezer is a tightly focused beam of light with a typical beam waist of around 1 μm. The tightly focused beam enables light assisted collisions to reduce the trap occupancy to no more than one atom, allowing experimental manipulation on the single particle level.

By trapping and cooling individual Rb and Cs atoms in optical tweezers, we will assemble single molecules by merging the tweezers confining Rb and Cs into a single trap containing both atoms. By preparing both atoms in the lowest motional state of the trap, the atom pair may be associated into a weakly bound molecular state by performing magnetoassociation, a technique performed by ramping an applied magnetic field over an interspecies Feshbach resonance. Subsequently, we will transfer this weakly-bound molecule into its rovibrational ground state using STIRAP (stimulated Raman adiabatic passage).

Detection of the associated molecules will be achieved by dissociating the remaining molecules back into atoms by reversing the formation process described above. The remaining atoms may then be detected using fluorescence imaging.

Using an acousto-optic deflector (AOD) to create multiple tweezers will enable the trapping of many Rb and Cs atoms which will allow us to scale up our experiment to create several ground state molecules, each in a different optical tweezer trap. These molecule-filled traps may then be rearranged to create the aforementioned controllable arrays, allowing a new realm of physics to be explored.

The group has recently realised the trapping and imaging of single Rb and Cs atoms in individual tweezers. Currently, the group is working on the cooling of the individual Rb and Cs atoms trapped in optical tweezers, a necessary step before the atoms can be brought together and magnetoassociated into a weakly-bound molecule. This cooling will be implemented using Raman sideband cooling, a technique which allows the motional quantum number in the tweezer to be reduced by coherently driving transitions between different motional levels.

## Recent Publications

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f Tweezer -q @*[year={{y}}]* %}
{% endfor %}

</div>