---
layout: page
title: Next-Gen VTOL UAS Design (2022-2023)
description: A novel wing-foldable VTOL tail-sitter design with double-swashplate.
img: assets/img/project_Swift/Swift_closeup.jpg
importance: 3
category: other
---

## Project Overview

This project focuses on the development of a next-generation VTOL (Vertical Take-Off and Landing) unmanned aircraft system, conducted at Texas A&M University's Advanced Vertical Flight Laboratory under the supervision of Prof. Moble Benedict. This project is my undergraduate capstone project. The ultimate goal of this project is to design a small-footprint VTOL UAS that can be used for long-endurance missions.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Swift/Swift_group_photo.jpg" title="Group Photo" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


### Phase 1: Full-scale Conceptual Design (Sept 2022 - Dec 2022)

The initial phase focused on the theoretical design and realization of a next-generation long-endurance VTOL unmanned aircraft. Key accomplishments include:

- Led the flight dynamics modeling sub-team and developed control laws
- Successfully demonstrated transition flights between fixed-wing and hovering modes in Simulink simulation
- Derived equations of motion and developed a 2D nonlinear longitudinal dynamic simulation
- Validated transition flight capabilities using CFD (Computational Fluid Dynamics) data

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Swift/Swift_fullscale.png" title="Full-scale Conceptual Design" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Swift/Swift_sim.gif" title="Simulation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Full-scale conceptual design of the VTOL tail-sitter. Right: Dynamic simulation of the VTOL tail-sitter showing transition flight capabilities.
</div>

### Phase 2: Scaled Prototype Development (Jan 2023 - May 2023)

The second phase involved creating a scaled prototype to validate the design concepts:

- Led a 20-person team in design, fabrication, and flight testing of a 4-lb subscale prototype (I was the chief engineer)
- Implemented a double-swashplate-based control system with wing-folding capability
- Integrated control logics using ELKA (Embedded Lightweight Kinematic Autopilot)
- Successfully demonstrated indoor hovering with mid-flight wing deployment

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Swift/Swift_components.png" title="Swift Components" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Swift/Swift_closeup.jpg" title="Swift Prototype" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: The components of the VTOL tail-sitter. Right: Physical prototype during testing.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Swift/Swift_swashplate.gif" title="Double Swashplate" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Swashplate mechanism of the VTOL tail-sitter.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-10">
        <div style="position: relative; width: 100%; padding-bottom: 56.25%;">
            <iframe src="https://www.youtube.com/embed/HDEgZ_7VioM" class="img-fluid rounded z-depth-1" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
    </div>
</div>
<div class="caption">
    Flight test demonstrating hovering capabilities and stable vertical flight control of the scaled VTOL tail-sitter prototype.
</div>

## Conclusion
The project successfully demonstrated the feasibility of a novel VTOL tail-sitter design incorporating wing-folding mechanisms and double-swashplate control. The prototype validated both hovering capabilities and successful wing deployment during flight.
