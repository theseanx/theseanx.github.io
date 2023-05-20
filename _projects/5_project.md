---
layout: page
title: Shifty Quadtree
description: A C++ image pixelator
img: 
importance: 3
category: academic
---
Developed a program that recursively splits an image (into four partitions) according to a formula that minimizes the variability in the pixels.
The program then returns a pixelated version of the image.
Implemented an auxiliary structure that holds the information about the variability of each pixel so that the recursive splitting algorithm runs in time proportional to the size of the image.

Given an image such as:

The app will produce the following pixelated image:


[//]: # (which uses smaller rectangles and thus has more details in parts that have more variability and uses larger rectangles and thus has fewer details in parts that have less varability (?maybe->between neighbouring pixels)