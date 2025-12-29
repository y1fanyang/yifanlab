---
title: Gallery
nav:
  order: 5
  tooltip: Our lab gallery
---

# {% include icon.html icon="fa-solid fa-images" %}Gallery

Welcome to our lab gallery! Here you can find photos showcasing our research activities, team events, lab equipment, and memorable moments from our scientific journey.

{% include section.html %}

## Research Highlights

{% include list.html 
    data="gallery.research" 
    component="image"
    style="square"
%}

{% include section.html %}

## Lab Activities

{% include list.html 
    data="gallery.activities" 
    component="image"
    style="square"
%}

{% include section.html %}

## Equipment & Facilities

{% include list.html 
    data="gallery.equipment" 
    component="image"
    style="square"
%}
## Recent Memories

A collection of recent moments that capture the spirit of our lab - from research breakthroughs to team building activities that strengthen our collaborative environment.

{% include section.html %}

{% capture content %}

{% include figure.html 
    image="images/gallery/qiuyou1.jpg" 
    caption="Autumn 2025: Hiking in JiuXi" 
%}

{% include figure.html 
    image="images/gallery/qiuyou2.jpg" 
    caption="Autumn 2025: Hiking in JiuXi" 
%}

{% include figure.html 
    image="images/gallery/qiuyou3.jpg" 
    caption="Autumn 2025: Hiking in JiuXi" 
%}

{% include figure.html 
    image="images/gallery/qiuyou4.jpg" 
    caption="Autumn 2025: Hiking in JiuXi" 
%}

{% include figure.html 
    image="images/gallery/research1.jpg" 
    caption="Single-cell analysis pipeline" 
%}

{% include figure.html 
    image="images/gallery/research2.jpg" 
    caption="Computational biology workflow" 
%}

{% endcapture %}

{% include grid.html 
    style="square" 
    content=content 
    size="medium"
%}