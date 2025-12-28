---
layout: post
title: MIT Solar Electric Vehicle Team Roll Cage
order: 1
img: "assets/img/portfolio/rc-fea.png"
feature-img: "assets/img/portfolio/rc.png"
tags: [CAD, SolidWorks, FEA, Ansys]
display-date: "September 2024 – Present"
---
I am currently leading our 2-4 person team in the design and fabrication of the roll cage for the MIT Solar Electric Vehicle Team's new car, _Solstice_, to compete at the 2026 American Solar Challenge, a 1,500 mile route across the US. The roll cage is a TIG-welded steel frame ensuring occupant safety.  

**Roll Cage Design:**  
<div style="display: flex;">
    <img src="{{ "/assets/img/portfolio/rc.png" | relative_url }}" alt="Roll Cage" style="width: 49%;">
    <img src="{{ "/assets/img/portfolio/solstice-inside.png" | relative_url }}" alt="Roll Cage" style="width: 49%;">
</div>

## Design and Analysis 
I used SolidWorks to design the roll cage and make sure it can be integrated with the rest of the car. Some of the specifications were as follows:
- The front elements of the roll cage must be angled at least 15 degrees backwards from the vertical
- Must be fixed and to the structural chassis
- Must be made of metal elements
- Must be TIG-welded

Throughout the design process, I made sure that the design was manufacturable, and made changes as necessary, as ease of welding had to be prioritized. For example, when modelling welds in the CAD, I made sure that there were no welds added at the corner of gussets, which we added for strength, as a welding torch would not fit in that space.

I also worked on ensuring optimal placement of hardpoints on the mounts that connect the roll cage to the chassis of the car. The chassis is made of carbon fiber composite panels which we layed up ourselves. 

I ran simulations for stress analysis using Ansys FEA to test various load cases specified by the competition guidelines. The load cases were to pass when applied on both the front corners and back corners of the roll cage. There were two sideways angled loading cases, one sideways horizontal loading case, one rearward horizontal loading case, and one combined loading case to be applied on a loading patch less than 150mm in diameter. The FEA is required to use 3D elements at the joints. 

<img src="{{ "/assets/img/portfolio/rc-fea.png" | relative_url }}" alt="Roll Cage FEA" width="100%">
<div style="display: flex;">
    <img src="{{ "/assets/img/portfolio/sizing.png" | relative_url }}" alt="Roll Cage" style="width: 49%;">
    <img src="{{ "/assets/img/portfolio/mesh.png" | relative_url }}" alt="Roll Cage" style="width: 49%;">
</div>

## Manufacturing 
We are beginning the manufacturing process of the car and will be TIG-welding the roll cage starting in the winter. We performed an Instron test to verify the strength of our welds for analysis as well. 

Weld Test Piece
<img src="{{ "/assets/img/portfolio/testpiece.JPEG" | relative_url }}"
     alt="Solstice"
     width="50%"
     style="display:block; margin-left:auto; margin-right:auto;">

