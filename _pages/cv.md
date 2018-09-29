---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Tech. in Electronics and Communication Engineering, Manipal Institute of Technology, 2014
* M.S. in Electrical and Computer Engineering, Georgia Institute of Technology, 2016
* Ph.D in Electrical and Computer Engineering, Georgia Institute of Technology, 2019 (expected)

Work experience
======
* Spring 2016-Present: Graduate Research Assistant (under Dr. Magnus Egerstedt)
  * to-be-updated
  * Georgia Institute of Technology

* Summer 2015: Autopilot Team Intern
  * Conceptualized schemes to diagnose anomalous driving conditions and realized them in embedded C.  These schemes detect potentially dangerous conditions by taking into account factors such as vehicle dynamics, driver reaction times and current road parameters.
  * Developed a Software-In-Loop simulator to compute safety performance metrics using test-drive data.
  * Implemented MATLAB scripts to automatically facilitate cross-checking of the simulator output with field data and generate statistics to fine tune the design parameters.
  * Implemented a spline interpolation method to generate estimates of the road curvature based on intermittent trajectory and GPS data.
* Mar 2011 - Dec 2013: Team Leader, PARIKSHIT STUDENT SATELLITE TEAM, Manipal, India
  * Designed and successfully tested a fully autonomous three-axis PID control system for stabilization of the satellite.
  * Managed a team of 7, supervising and aiding the design of attitude estimation algorithms (using Kalman Filters), orbit determination algorithms, hardware design and system integration.
  * Designed and developed an integrated satellite environment simulator on MATLAB, featuring modules for torque analysis, performance testing and orbital positioning. The whole system was later implemented in C.


Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Currently signed in to 43 different slack teams
