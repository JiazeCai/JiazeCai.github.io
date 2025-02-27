---
layout: page
title: High-DoF Flapping-Wing Robot (2024-present)
description: A bio-inspired flapping-wing Robot with high degrees of freedom for agile flight. Leveraging learning-based control, the robot is designed to perform agile maneuvers and adapt to complex environments.
img: assets/img/project_Flappy/Flappy_maneuvers.gif
importance: 2
category: research
related_publications: true
---

## Project Overview

This ongoing project focuses on the development of a high degree-of-freedom (DoF) flapping-wing UAV inspired by bird flight. The UAV is designed to perform agile maneuvers and adapt to complex environments.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Flappy/Flappy_CAD.png" title="Flapping Mechanism Design" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Flight Test

This is a priliminary flight test of the flapping-wing UAV to demonstrate the capability of a sustained flight.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/Flappy_flight.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Flight test demonstrating sustained flapping-wing flight.
</div>

## Design

The current design of the flapping-wing UAV incorporates several innovative features to enhance its flight capabilities. It has individual degree-of-freedom (DoF) for each wing for pitching and flapping, which allows for more complex flight patterns. Note that the recent design is partially referenced from Prof. Raphael Zufferey's paper {% cite zufferey2021eflap %}.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Flappy/Flappy_overview.jpg" title="Flapping Mechanism Design" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Flappy/Flappy_wing_camber.jpg" title="Flapping Mechanism Design" class="img-fluid rounded z-depth-1" %}
    </div> 
</div>
<div class="caption">
    Left: Overview of the flapping-wing UAV. Right: A close-up view of the wings.
</div>

## Control

We are working on using reinforcement learning to control the flappy-wing robot. This method allows the UAV to perform agile maneuvers and adapt to various flight conditions. This methods has shown great performance in the simulation. For more details on the control strategy, refer to the [video demonstration](https://www.youtube.com/watch?v=54Gcbvgfz7Q) shown below and paper {% cite cai2024learning %}.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Flappy/Flappy_turn.gif" title="Turning Maneuver" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Flappy/Flappy_turn_traj.png" title="Turn Trajectory" class="img-fluid rounded z-depth-1" %}
    </div> 
</div>
<div class="caption">
    Left: Animation of the turning maneuver. Right: Trajectory plot of the turning motion.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Flappy/Flappy_climb.gif" title="Climbing Maneuver" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Flappy/Flappy_climb_traj.png" title="Climb Trajectory" class="img-fluid rounded z-depth-1" %}
    </div> 
</div>
<div class="caption">
    Left: Animation of the flapping-wing robot climbing. Right: Trajectory plot of the climbing motion.
</div>

### Control Video Demonstration

<div class="row justify-content-sm-center">
    <div class="col-sm-10">
        <div style="position: relative; width: 100%; padding-bottom: 56.25%;">
            <iframe src="https://www.youtube.com/embed/54Gcbvgfz7Q" class="img-fluid rounded z-depth-1" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
    </div>
</div>

<div class="caption">
    Video demonstration of the learning-based control on the flapping-wing robot in MuJoCo simulation.
</div>

This control framework is released [here](https://arxiv.org/html/2411.15130v1).

## Experiments

We also conducted experiments to test the performance of the flapping-wing UAV in the real world and use the data to improve the simulation accuracy.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_Flappy/Flappy_experiment.jpg" title="Experiment Setup" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Experiment setup for the flapping-wing UAV. The UAV is mounted on a Force Torque Sensor (FTS) to measure the force and torque on the UAV. The UAV in the picture is an early prototype of the flapping-wing UAV.
</div>

## Conclusion

The High_DoF Flapping-Wing UAV project showcases the potential of combining innovative design with advanced control strategies to achieve agile and adaptive flight capabilities for flapping-wing robots. The integration of these elements allows the UAV to unlock the potential of flapping-wing robots to perform complex maneuvers and operate effectively in diverse environments!
