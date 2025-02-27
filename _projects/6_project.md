---
layout: page
title: Remote-Controlled Boat for eSMART Competition (2020)
description: Design and development of a high-speed RC boat with comprehensive hydrodynamic analysis.
img: assets/img/project_eSMART/eSMART_boat_v2.png
importance: 4
category: other
---

## Project Overview

From February 2020 to June 2020, I participated in the eSMART Competition where we designed and built a remote-controlled boat optimized for maximum speed in actual sea-water conditions. The project involved comprehensive hydrodynamic analysis, stability calculations, and validation through both computational and physical testing.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_eSMART/eSMART_CAD.jpg" title="RC Boat Overview" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_eSMART/eSMART_boat_v1.jpg" title="RC Boat Overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The remote-controlled boat design for eSMART Competition.
</div>

## Technical Analysis and Development

### Key Contributions:

- Conducted static stability analysis by calculating the boat's metacentric height
- Developed Python-based simulation tools for performance prediction
- Performed comprehensive drag calculations using the Guldhammer & Harvald method
- Implemented thrust calculations using KT-J and Kq-J Charts for Wageningen B-Series Propeller
- Validated design through two-phase CFD simulations and physical experiments

## Performance Simulation

We developed a comprehensive simulator that integrated various hydrodynamic calculations to predict the acceleration, velocity, distance covered in water.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_eSMART/eSMART_plots.png" title="Dynamic Simulation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_eSMART/eSMART_CFD.png" title="CFD Analysis" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_eSMART/eSMART_plot2.png" title="Fn_vs_Cr" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Dynamic simulation of the RC boat design. Middle: Two-phase CFD simulation showing the hydrodynamic behavior of the boat design. Right: Fn_vs_Cr.
</div>

## Experiment

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_eSMART/eSMART_test0.gif" title="Physical Testing" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sea water testing of the RC boat design.
</div>

## New Design

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_eSMART/eSMART_boat_v2.png" title="Design Process" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This is the new design of the RC boat. It has a more streamlined shape and a larger aspect ratio for smaller resistance.
</div>
