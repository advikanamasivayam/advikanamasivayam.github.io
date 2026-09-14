---
layout: post
title: Knobbi
order: 4
img: "assets/img/portfolio/knobbi.JPEG"
feature-img: "assets/img/portfolio/background.jpg" 
tags: [CAD, Onshape]
display-date: "February 2026"
---
I participated in **MakeMIT**, a 24-hour hardware hackathon at MIT. Our team won **1st place in the Home Security Track** sponsored by Sauron. 

Our team designed and fabricated **_knobbi_**, a retractable doorknob with a custom tri-bar linkage and autolock features. We integrated mechanical hardware with software for user authentication via camera-based facial recognition.

I worked on engineering the housing to eliminate external leverage points and improve forced-entry resistance, as well as the linkage mechanism required for the doorknob to smoothly retract, flush to the housing.

<div style="display: flex;">
    <img src="{{ "/assets/img/portfolio/knobbi/cad1.png" | relative_url }}" alt="knobbi CAD" style="width: 40%;">
        <img src="{{ "/assets/img/portfolio/knobbi/cad2.png" | relative_url }}" alt="knobbi CAD" style="width: 40%;">
</div>
<p align="center"><i>Initial CAD designs</i></p>

<div style="display: flex;">
        <img src="{{ "/assets/img/portfolio/knobbi/knobbi1.JPEG" | relative_url }}" alt="knobbi image" style="width: 40%;">
<img src="{{ "/assets/img/portfolio/knobbi/knobbi2.JPEG" | relative_url }}" alt="knobbi image" style="width: 49%;">
</div>
<p align="center"><i>Final Prorotype</i></p>

## Inspiration
As our team was brainstorming ideas, one of the problems we echoed was pets and kids opening doors as a safety hazard. It is challenging to babyproof or pet-proof doors without making it a hassle for the adults themselves. We realized that this concept also applies to home security with facial recognition, but this is something that already exists--what makes this different? As we were discussing deterring tactics, we mentioned how Tesla car door retraction makes it less attractive for robberies. We sought to incorporate this into our design, knobbi.

## What is knobbi
knobbi is a smart door with facial recognition that enables access to only authorized users, with the door knob not extracting when access is denied. This is particularly useful for dementia and Alzheimer's patients, senior living care, child proofing medical cabinets, and home security. We used OpenCV for the facial recognition, uploading the team members images for training. knobbi has an incorporated camera that provides live feed for real time facial recognition. We laser cut wood for a mockup cabinet to prototype our locking and doorknob retraction mechanisms.

<div style="display: flex;">
    <img src="{{ "/assets/img/portfolio/knobbi/knobbi3.JPEG" | relative_url }}" alt="knobbi image" style="width: 30%;">
    <img src="{{ "/assets/img/portfolio/knobbi/knobbi4.JPEG" | relative_url }}" alt="knobbi image" style="width: 30%;">
</div>

## Challenges we ran into
Facial recognition proved to be a challenge as we tested in various brightness and lighting conditions, with false positive cabinet access for wrong person access. This took a lot of iteration to get to a better position. Moreover, integration between the cabinet, the servos, and the electronics for access proved a large challenge as the mechanical interactions behaved unexpectedly. In the end, we were able to successfully train our model to recognize our team and integrated the peripheral camera feed and servos for locking and unlocking within the time constraint that we were challenged with.

## Hackathon Submission Video
<iframe width="1120" height="630"
        src="https://www.youtube.com/embed/k5NtzphyoIU?mute=1"
        title="YouTube video player"
        frameborder="0"
        allowfullscreen></iframe>
