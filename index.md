---
layout: home
title: Home
nav_order: 0
description: >-
    Course website for EECS 106/206A Fall 2022
---
<!-- <div class="parallax-window" data-parallax="scroll" data-image-src="/assets/background.png" data-speed="0.1">/div> -->
# EECS C106A/206A | Introduction to Robotics
{: .mb-2 }
Fall 2022
{: .mb-0 .fs-6 .text-grey-dk-200 }

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

{% if site.announcements %}
{{ site.announcements.last }}
<a href="{{ site.baseurl }}/announcements" class="btn btn-outline fs-3">
  All Announcements
</a>
{% endif %}

## Navigating the Website

All assignment due dates can be found in the *Policies* tab under *Due Dates*.

Looking for the weekly lab, discussion, lecture, or office hours schedule? Check out the *Weekly Schedule* tab!

Looking for the semester plan, discussion worksheets, project assignments, or homework assignments? Check out the *Semester Calendar* tab!

Have a question about our course policies? Check out the *Policies* tab!

Looking for a TA or professor's email? Check out the *Staff* tab!

Looking for resources for projects, homeworks, and lecture? Check out the *Resources* tab!

## Course Description

This course is an introduction to the field of robotics. It covers the fundamentals of kinematics, dynamics, and control of robot manipulators, robotic vision, and sensing. The course deals with forward and inverse kinematics of serial chain manipulators, the manipulator Jacobian, force relations, dynamics, and control. It presents elementary principles on computer vision and robot motion planning. The course concludes with current applications of robotics in active perception, medical robotics, autonomous vehicles, and other areas.

The lectures are supplemented with homeworks and experimental work in the laboratory using several <a href="http://www.rethinkrobotics.com/baxter/">Baxter</a>, <a href="http://www.rethinkrobotics.com/sawyer/">Sawyer</a>, and <a href="http://www.turtlebot.com/turtlebot2/">TurtleBot</a> robots. There are two midterms, but no final exam. The last month of the course is devoted to the design and implementation of a final project, carried out individually or in groups of approximately four students.