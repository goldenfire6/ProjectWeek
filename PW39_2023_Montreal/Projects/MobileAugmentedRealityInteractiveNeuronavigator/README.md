---
layout: pw39-project

project_title: 'MARIN: Mobile Augmented Reality Interactive Neuronavigator (in Slicer)'
category: IGT and Training

key_investigators:
- firstname: Mehrdad
  lastname: Asadi
  affiliation: Concordia University
  country: Canada
  
- firstname: Étienne
  lastname: Léger
  affiliation: Montreal Neurological Institute
  country: Canada
  
- firstname: Bahar
  lastname: Jahani
  affiliation: Concordia University
  country: Canada

- firstname: Zahra
  lastname: Asadi
  affiliation: Concordia University
  country: Canada
---

# Project Description

<!-- Add a short paragraph describing the project. -->
[MARIN](https://github.com/AppliedPerceptionLab/MARIN) is an application that can be used in conjunction with a neuronavigation platform to enable in situ AR guidance on a mobile device. It currently supports iOS and works in conjunction with [Ibis](https://github.com/IbisNeuronav/Ibis) (with the additional [MARIN plugins](https://github.com/AppliedPerceptionLab/IbisPluginsExtraMARIN)). The goal of this project is to implement the same support in Slicer.

## Objective

<!-- Describe here WHAT you would like to achieve (what you will have as end result). -->

1. Add Slicer support for MARIN (provide the same functionalities that Ibis currently does)

## Approach and Plan

<!-- Describe here HOW you would like to achieve the objectives stated above. -->

MARIN is a mobile application that can overlay virtual structures over the live camera feed from a device, enabling *in situ* augmented reality navigation for surgical applications (see image below). The MARIN application itself can interface with any platform, provided that the platform supports real-time communication, can handle tracking and generate 3D renderings. Slicer has all of these capabilities. Communication between Slicer and MARIN can be set-up through the OpenIGTLinkIF module. The main components that will have to be implemented are Slicer modules to handle device configuration and rendering of tracked virtual objects.

## Progress and Next Steps

<!-- Update this section as you make progress, describing of what you have ACTUALLY DONE.
     If there are specific steps that you could not complete then you can describe them here, too. -->

TODO

# Illustrations

<!-- Add pictures and links to videos that demonstrate what has been accomplished.
![Description of picture](Example2.jpg)
![Some more images](Example2.jpg)
-->

MARIN demo, with Ibis:
![teaser_looped_small](https://github.com/the-mercury/ProjectWeek39/assets/17100565/b0f84128-5ce2-46ae-9e5b-3a12c778468f)

# Background and References

<!-- If you developed any software, include link to the source code repository.
     If possible, also add links to sample data, and to any relevant publications. -->
Article: Léger, É., Reyes, J., Drouin, S., Popa, T., Hall, J. A., Collins, D. L., Kersten-Oertel, M., "MARIN: an Open Source Mobile Augmented Reality Interactive Neuronavigation System", International Journal of Computer Assisted Radiology and Surgery (2020). 
https://doi.org/10.1007/s11548-020-02155-6

Source code repository: [MARIN](https://github.com/AppliedPerceptionLab/MARIN/tree/master)