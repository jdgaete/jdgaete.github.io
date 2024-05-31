---
layout: page
title: Ray Tracer
description: Performed a Ray-Tracer algorithm in C++ with ray-object collision detection by using BVH.
img: assets/img/ray_tracer.jpg
importance: 1
category: work
related_publications: false
---

In this project, Lamha and I we implemented a ray-tracing algorithm with ray-object collision detection by using bounding volume hierarchy (BVH). We also included texture and cube mapping, antialiasing by adaptive supersampling, adaptive termination criterion for tracing rays based on ray contribution and implementation of stochastic (jittered) supersampling.

[CODE](https://github.com/lamhagoel/GraphicsRayTracing.git)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ray_tracer.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/head.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cubes.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>