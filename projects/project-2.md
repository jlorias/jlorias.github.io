---
layout: project
type: project
image: images/vacay-square.png
title: Vacay
permalink: projects/bikealarm
# All dates must be YYYY-MM-DD format!
date: 2018-04-30
labels:
  - Javascript
  - Node.js
  - IBM Bluemix
  - Raspberry Pi
  - NodeRed
summary: A bike/alarm implemented through a Raspberry Pi and NodeRed on IBM Bluemix for EE 491. 
---

<img class="ui medium right floated rounded image" src="../images/vacay-home-page.png">

As a commuter school with high parking fees, one of the best ways to travel onto campus 
(besides bus) is to ride a moped. However, a lot of mopeds means a lot more thefts -- 
which is exactly the problem we addressed in the Bike Alarm project for our EE 491 class.
The goal of the project was to implement a bike/moped alarm via a Raspberry Pi, and whenever 
the Pi detected unauthorized movement, it would send an alert directly to your phone.

We didn't add anything extra to the Pi itself, as it already contained a SenseHat that displayed
an array of lights. The lights changed color from green to red as soon as unauthorized movement is
detected. We delegated the project in three tasks: 
  <ol>
    <li> Motion detecting </li>
    <li> Phone Alarm </li>
    <li> Testing </li> 
  </ol>

I was in charge of creating a script that detected unauthorized movement. 
