---
layout: page
title: Business Card Generator
description: An intuitive Flask front-end that allows users to easily generate business cards with stunning backgrounds
img: assets/img/business-card-cube-background.png
importance: 2
category: projects
---
A business card generator that produces formatted PDFs with the user's contact info.  
In addition, the generator adds a QR code, which encodes a vCard, of the user's contact info. Scanning this QR code will automatically add the contact info into a person's phone.

Flask front-end:
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/business-card-front-end.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

A QR code of a vCard containing the person's contact info is automatically generated and added to each business card
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/business-card-with-qr-code-description.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Sample backgrounds:

Cube Background:
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/business-card-cube-background.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
Diagonal Striped Background:
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/business-card-diagonal-striped-background.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
