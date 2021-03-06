---
layout: post
year: 2018
title: "Disaster City"
subtitle: "An RTS prototype for a game about giant monsters destroying your city"
---

I had some design ideas (and still do) about a strategy game where a player protects his/her city from kaijus, UFOs, titans, and other giant monsters. This project is an RTS prototype with the real-time unit and resource management.

A player must call and control units manually. The prototype has two types of units (tanks and airplanes), one ability (artillery strike), and one enemy with a simple logic state machine (attack the city, attack units, block attacks, and rage). 

<iframe width="650" height="346" src="https://www.youtube.com/embed/MAdxSqs7pms" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The prototype showed that RTS that relies heavily on micro-management is not a very good idea. I think that a city-builder with indirect unit control would fit the story better.

Technologies used: C#, Unity.
  
Source code: [GitHub](https://github.com/binary-machinery/DisasterCity)