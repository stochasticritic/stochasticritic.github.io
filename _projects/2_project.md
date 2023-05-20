---
layout: page
title: Reinforcement Learning for Autonomous Navigation of vehicles on uncertain terrain
description: Work started as a part of the IROS 2022 Safe Robot Learning Competition)
img: assets/img/proj1_1.jpg
importance: 2
category: Research Projects
---
Word done with [Dr. M Vidyasagar FRS](https://people.iith.ac.in/m_vidyasagar/) (IIT Hyderabad) 

• The major problem that we tried to solve is online and local planning of UGVs for unstructured, uneven, and uncertain terrain.
• Fitted the problem in a DeepRL pipeline and implemented the A3C algorithm in an end-to-end manner.
• Added the feature for the operator to add user-defined obstacles. Using Octomaps for occupancy grid mapping. Tried to extend it to
Truncated Signed Distance Field for representing terrain traversability heightmaps.

Follow <a href="https://github.com/stochasticritic/DeepRL-for-Autonomous-Navigation" >this repository</a> for more details.
<!--
    ---
    layout: page
    title: Agile autonomous flight in cluttered environments with safety constraints
    description: The goal of this project is to achieve minimum time flight in an environment with gates and obstacles. Additional internal/external perturbations and disturbances are injected into the environment (gate positions, wind gusts).
    img: /assets/img/proj1_1.jpg
    ---
-->
<div class="row justify-content-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj1_1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The above fig. shows the path tracked by a crazflie quadrotor while abiding by the preimposed safety constraints
</div>



