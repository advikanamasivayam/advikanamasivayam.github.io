---
layout: post
title: MIT Solar Electric Vehicle Team Roll Cage
order: 1
img: "assets/img/portfolio/inside.png"
feature-img: "assets/img/portfolio/background.jpg"
tags: [CAD, SolidWorks, FEA, Ansys, Manufacturing]
display-date: "September 2024 – May 2026"
---
As Roll Cage Lead for the MIT Solar Electric Vehicle Team, I led the design and fabrication of the roll cage for _Solstice_, our multi-occupant solar vehicle competing in the 2026 _Formula Sun Grand Prix_. The roll cage is a TIG-welded steel structure designed to protect the occupants while integrating with the vehicle's carbon-fiber composite chassis and surrounding mechanical systems.

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

## Design Iteration
The roll cage went through multiple iterations as I evaluated both structural performance and integration with the vehicle. Strength requirements drove the addition and placement of gussets, while manufacturing constraints influenced tube geometry, joint design, and weld accessibility.

The final design also needed to interface with multiple vehicle systems. In addition to the chassis mounting points, I considered hardpoint placement relative to other components.

## Manufacturing 
After completing the design and manufacturing plan, I worked through the fabrication process with the team. Tube welding required consideration of weld accessibility, fixturing, and distortion, particularly as the structure was assembled.
<div style="display: flex;">
    <img src="{{ "/assets/img/portfolio/welding.JPG" | relative_url }}" alt="Welding" style="width: 55%;">
    <img src="{{ "/assets/img/portfolio/rc_car.jpg" | relative_url }}" alt="Roll Cage" style="width: 30%;">
</div>

We also performed an Instron test of representative welds to verify weld strength and provide data for our analysis of the loading cases.
<img src="{{ "/assets/img/portfolio/testpiece.JPEG" | relative_url }}" alt="test" width="40%">

Beyond the roll cage, I contributed to manufacturing other vehicle systems, including the rear suspension, battery mounting, and steering systems.
<div style="display: flex;">
    <img src="{{ "/assets/img/portfolio/backsus.JPEG" | relative_url }}" alt="Back Sus" style="width: 30%;">
    <img src="{{ "/assets/img/portfolio/mounts.png‎‎" | relative_url }}" alt="Mounts" style="width: 55%;">
</div>

## Results
_Solstice_ competed in the 2026 _Formula Sun Grand Prix_ in Brainerd, Minnesota, and went on to place 5th overall in the Multi-Occupant Vehicle (MOV) class.

The completed roll cage reduced mass by 25% compared with the team's previous vehicle while meeting the structural and integration requirements of the new vehicle.

<img src="{{ "/assets/img/portfolio/Car.JPG" | relative_url }}" alt="Solstice" width="50%">


