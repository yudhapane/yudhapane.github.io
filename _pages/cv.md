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
* Ph.D in Mechanical Engineering, KU Leuven, 2022  
  * Thesis: *Composing Concurrent Reactive Robot Skills: Integration of Task Specification and Control with Symbolic Planning and CAD Information*
* M.Sc. in Systems and Control, TU Delft, 2015  
  * Thesis: *Reinforcement learning based compensation methods for robot manipulators*
* B.Sc. in Electrical Engineering, Bandung Institute of Technology, 2013

Work experience
======
* November 2023 – Present: Robotics Software Engineer  
  * **Movu Robotics**, Lokeren  
  * Developing and managing the software stack for the Eligo picking robot, including vision, path planning, and picking strategy.

* October 2021 – Present: Robotics Engineer  
  * **Magics Technologies**, Geel  
  * Led robotics development initiatives, focusing on grasp and motion planning for autonomous picking of unknown objects.

* February 2016 – September 2021: PhD Researcher  
  * **KU Leuven**, Leuven  
  * Developed sensor-based robotic skills for industrial tasks. Participated in Flanders Make projects:  
    * **FINROP (ICON)**: Fast and intuitive robot programming  
    * **MULTIROB (SBO)**: Multi-robot assembly skills

* December 2015 – February 2016: Control Engineer  
  * **Tocano**, Delft  
  * Developed control systems for inkless printer prototypes.

Skills
======
* Robotics Engineering
  * Sensor-based control
  * Grasp and motion planning
* 3D Computer Vision
  * Point Cloud Library
* Programming
  * C++, Python, Java
  * Embedded systems, Docker
* Middleware and Tools
  * Robot Operating System (ROS)
  * Git, Docker

Languages
======
* English (highly proficient)
* Indonesian (native)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Initiated robotics R&D at Magics Technologies
* Contributed to multi-institution collaborative projects (Flanders Make)
