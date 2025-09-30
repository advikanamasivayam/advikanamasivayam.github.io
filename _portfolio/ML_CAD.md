---
layout: post
title: MIT DeCoDE Lab ML for CAD UROP
img: "assets/img/portfolio/chamfer-distance.png"
date: 2025-06-01
tags: [Research, CAD, Rhinoceros 3D, Python]
---
Over the summer, I worked on CAD and machine learning algorithms for hull optimization and a surface generation research project with Myles Wortham for the Design Computation and Digital Engineering Lab of Professor Faez Ahmed. In this process, I developed Python and Rhino pipelines for B-spline surface generation and CAD mesh repair with Git version control, improving geometric accuracy over traditional mesh-based methods. I also implemented ship-hull optimization using genetic algorithms (an evolutionary AI technique) to generate physically accurate hull models.

**Genetic Algorithm Data Output**  
![image]({{ '/assets/img/portfolio/ga-data.png' | relative_url }})

**Hull Chamfer Distance Minimization Visual**  
<img src="{{ "/assets/img/portfolio/hull-overlay.png" | relative_url }}" alt="Hull Overlay" width="50%"><img src="{{ "/assets/img/portfolio/chamfer-distance.png" | relative_url }}" alt="Chamfer Distance" width="50%">

**Generating single continuous surfaces using b-spline NURBS surface**
Usually these are generated as individual faces and then combined due to the sharp edges  
<img src="{{ "/assets/img/portfolio/platonic.png" | relative_url }}" alt="Platonic Solids" width="100%"><img src="{{ "/assets/img/portfolio/icosahedron.png" | relative_url }}" alt="icosahedron" width="50%"><img src="{{ "/assets/img/portfolio/prisms.png" | relative_url }}" alt="prisms" width="50%"><img src="{{ "/assets/img/portfolio/square-pipe.png" | relative_url }}" alt="square-pipe" width="50%"><img src="{{ "/assets/img/portfolio/half-pipe.png" | relative_url }}" alt="half-pipe.png" width="50%">  

**Varying the degrees of the functions**  
<img src="{{ "/assets/img/portfolio/degs.png" | relative_url }}" alt="Degree Variations.png" width="100%">
