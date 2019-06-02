---
layout: project
title: Close-up Cloud
subtitle: 
ref: leuchttisch
permalink: "/close-up-cloud/"
tag: project
excerpt: Collection Exploration Concept
external-link: 
exhibition-link: dh2019.adho.org/
exhibition-note: Featured as a Short Paper and presentation at DH2019 in Utrecht
year: 2018
role: Concept, Design, Web Development
tools: Pixi.js, D3.js
team: Pauline Junginger (Research, Concept), Barbara Avila Vissirini (Concept, Design), Anastasia Voloshina (Concept, Design)
supervision: Prof. Dr. Marian Dörk
color-primary: '#f7c29c'
order: 4
---

{:.m-image__fullwidth}
![Leuchttisch: Collection]({{site.baseurl}}/img/leuchttisch_intro-cloud.jpg)

{:.m-text__highlighted style="border-color: {{ page.color-primary }};"}
When visualising high-resolution image collections, rich with metadata and descriptive tags, there is an opportunity to reveal both the visual details of individual images and the iconographic patterns prevalent within the collection. Presented here is an approach of bringing together both aspects and thereby contributing a different perspective to the domain of cultural collection visualisation.

## CONTEXT
For years the _University of Applied Sciences Potsdam_ has been focussing on the visualisation of cultural collections in the [VIKUS](https://uclab.fh-potsdam.de/projects/vikus/) research project. As part of a course on exploring new ways of approaching and interacting with collections this exploration concept was developed and later implemented as a web-based prototype. 

A collection of digitised historic glass negatives depicting arts and crafts objects was exemplarily used.

## PROJECT
The concept rearranges the common visualisation opposites of _Overview_ and _Detail_: Cropped closeups of collection images are assembled into a __collage of details__ that serves as the starting point for exploring the collection based on visual patterns.

The user is offered an interface of three stages, the _Cloud_ view, the _Tag_ view and the _Object_ view, each illuminating __different characteristics of the collection__.

The _Cloud_ view presents a collage of close-ups. Each close-up represents one occuring tag. Their spatial arrangement is based on topic, their size on the frequency of the depicted tag within the collection. Over time the depictions change, always creating a different random collage.

{:.m-image__fullwidth}
![Leuchttisch: Collection Collages]({{site.baseurl}}/img/leuchttisch_general-cloud.jpg)

Selecting a close-up, and therefore a tag, opens the _Tag_ view that appears as a traditional image grid, displaying all close-ups referring to the selected tag.

{:.m-image__fullwidth .m-image__border}
![Leuchttisch: Hover Interaction]({{site.baseurl}}/img/leuchttisch_tag-hover.jpg)

Selecting a close-up in the _Tag_ view directs to the _Object_ view that allows interactive examination of a specific image by highlighting areas of interest.

{:.m-image__fullwidth .m-image__border}
![Leuchttisch: Object Hover]({{site.baseurl}}/img/leuchttisch_object_animation.gif)

This view is gradually zoomable, with the full-resolution image and all its visual details being displayed.

{:.m-image__fullwidth .m-image__border}
![Leuchttisch: Object Zoom]({{site.baseurl}}/img/leuchttisch_object-zoom.jpg)

Selected areas of interest remain highlighted when zooming in.

{:.m-image__fullwidth .m-image__border}
![Leuchttisch: Object Zoom]({{site.baseurl}}/img/leuchttisch_object-zoom-2.jpg)

All views are interconnected and invite for __serendipitous paths__ through the collection, this way aiming for __unconventional exploration and sense-making__.