[![](https://img.shields.io/badge/python-3.4+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)
<p align="center">
  <img src="/docs/satellite_scheduling.png" >
</p>

A Genetic Algorithm for satellite scheduling optimization

## Description

Earth observing satellites (EOS) are able to acquire images on the Earth's surface while moving along their orbits, and are widely used in many fields, such as environmental protection, meteorology, natural disasters and military applications.

However, typically the number of requests for imaging exceed what can feasibly be accomplished. So, the process of satellite task scheduling consists in selecting and schedule a subset of requests for maximizing one or more objective functions. 

EOS have a limited window of opportunity for imaging each target, dictated by orbit parameters. Moreover, satellites operate under several complicating operational constraints such as resource availability, task priorities, limited  on-board memory and maximum slewing (that reflects its observation capability).  

This large number of constraints makes satellite scheduling optimization a hard combinatorial problem that exact methods cannot solve. On the other hand, approximate methods like Genetic Algorithms are aimed at finding near-optimal solutions to large-scaled problems in a reasonable amount of time.

It is developed here a Genetic Algorithm (GA) for solving the satellite scheduling optimization problem. Detailed problem description and mathematical programming model will be included too.
