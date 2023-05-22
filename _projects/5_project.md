---
layout: page
title: Shifty Quadtree
description: A C++ image pixelator
img: assets/img/cplusplus-logo.png
importance: 5
category: projects
---

[//]: # (CITATION: cplusplus-logo.png from https://github.com/isocpp/logos)
Developed a program that recursively splits an image (into four partitions) according to a formula that minimizes the variability in the pixels.  
The program then returns a pixelated version of the image.  
Implemented an auxiliary structure that holds the information about the variability of each pixel so that the recursive splitting algorithm runs in time proportional to the size of the image.

Given an image such as:
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cplusplus-image-pixelator-original.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The app will produce the following pixelated image:
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cplusplus-image-pixelator-after.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

[//]: # (CITATION: cplusplus-image-pixelator-original.png and cplusplus-image-pixelator-after.png were both taken from the assignment page)
[//]: # (which uses smaller rectangles and thus has more details in parts that have more variability and uses larger rectangles and thus has fewer details in parts that have less varability (?maybe->between neighbouring pixels)

Citation: C++ logo from https://github.com/isocpp/logos