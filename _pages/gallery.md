---
layout: page
title: Research Highlights
permalink: /gallery/
description: Visual demonstrations of algorithms and field deployments
nav: true
nav_order: 3
---

Exploring the intersection of robotics, optimization, and autonomous systems.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/intelligent_ocean_monitoring.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## SLAM & Localization

Advanced simultaneous localization and mapping algorithms designed for challenging real-world environments.

<div class="row mt-3">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/mit_outdoor_all_odometries.gif" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/mit_outdoor_cora_solution.gif" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/mit_outdoor_gtsam_solution.gif" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Multi-robot odometry traces showing drift. Center: CORA optimization converging to global optimum. Right: GTSAM baseline comparison.
</div>

<div class="row mt-3">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/mit_outdoor_cam1.gif" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/mit_outdoor_cam2.gif" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/mit_outdoor_cam3.gif" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Multiple camera perspectives of the same optimization process, revealing different geometric relationships.
</div>

<div class="row mt-3">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/plaza1_solution.gif" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/plaza2_solution.gif" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Urban plaza scenarios with multiple loop closures.
</div>

<div class="row mt-3">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/tiers_solution.gif" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/goats_solution.gif" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Multi-level environment. Right: GOATS benchmark dataset.
</div>

## CORA: Certifiable Optimization for SLAM

A state-of-the-art SLAM backend combining speed with rigorous performance guarantees through convex relaxation.

<div class="row mt-3">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/cora_input_output.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/cora_runtime_speedup.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: CORA's input/output pipeline transforming factor graphs into optimized trajectories. Right: Runtime speedup benchmarks showing computational efficiency.
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/rotating_spectrahedron.gif" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The spectrahedron: geometric structure underlying CORA's convex relaxation and certification process.
</div>

## Field Deployments

Real-world testing and deployment of autonomous systems in challenging aquatic environments.

<div class="row mt-3">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/alan_brendan_river_experiments.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/brendan_on_river_experiments.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    River field experiments deploying autonomous systems in dynamic freshwater environments.
</div>

---

*For more details on specific projects, see <a href="{{ '/publications/' | relative_url }}">publications</a> and <a href="{{ '/projects/' | relative_url }}">projects</a>.*
