---
layout: page
title: CORA
description: certifiable optimization for robot autonomy
img: assets/img/new_imgs/cora_input_output.png
importance: 1
category: robotics
related_publications: 
---

CORA (Certifiable Optimization for Robot Autonomy) is a SLAM backend that combines speed with rigorous performance guarantees. Built on tools from convex optimization, geometry, and graph theory, CORA represents a significant advancement in enabling reliable long-term autonomous navigation.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/cora_input_output.png" title="CORA Input/Output" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    CORA transforms factor graphs (input) into globally optimal pose estimates (output) with provable guarantees.
</div>

## Key innovation: speed + guarantees

Traditional SLAM backends face a fundamental tradeoff: fast local optimization methods like Gauss-Newton can get stuck in local minima, while global methods that provide guarantees are prohibitively slow. CORA breaks this tradeoff.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/cora_runtime_speedup.png" title="Runtime Performance" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    CORA achieves significant speedups over existing certifiable methods while maintaining global optimality guarantees.
</div>

## The mathematics behind CORA

The key insight is formulating SLAM as a convex relaxation over the spectrahedron - the set of positive semidefinite matrices with unit trace. This geometric structure enables efficient optimization while allowing us to certify global optimality.

<div class="row justify-content-sm-center mt-3">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/rotating_spectrahedron.gif" title="Spectrahedron Geometry" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The spectrahedron: the geometric structure underlying CORA's convex relaxation approach.
</div>

## Real-world performance

CORA has been extensively tested on challenging real-world datasets, demonstrating robust performance across urban environments, outdoor scenarios, and multi-robot systems.

<div class="row mt-3">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/mit_outdoor_cora_solution.gif" title="MIT Outdoor Dataset" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/plaza1_solution.gif" title="Urban Plaza" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: CORA solving the MIT outdoor dataset with multiple robots. Right: Robust performance in complex urban environments.
</div>

<div class="row mt-3">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/tiers_solution.gif" title="Multi-level Environment" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/new_imgs/goats_solution.gif" title="GOATS Dataset" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    CORA handles diverse scenarios including multi-level environments and challenging outdoor benchmarks.
</div>

## Impact

This work enables:
- Reliable underwater navigation for ocean monitoring missions
- Robust multi-robot systems with provable consistency
- Long-term autonomous operation in GPS-denied environments
- Real-time performance for time-critical applications

The combination of speed and guarantees makes CORA particularly valuable for safety-critical applications and long-duration missions where reliability is paramount.

---

*For technical details, see our publications on [arXiv](https://arxiv.org/abs/2302.11614).*
