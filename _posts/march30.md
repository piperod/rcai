---
layout: default
title: Journal March 30 
---

# Journal RC Coqui Car

# March 30 : Kick off Meeting

## Team : 

- Ivan F. Rodriguez 
- Jeffrey Chan  
- Chhaya Katiyar 

## Objective

- Define modules of work. We will focus on three different modules:
	-Car Hardware: Sensors, Optimizations for the car movement, speed, energy, etc.
	- Car Software :  Controllers, Input and output, File system, logging, etc. 
	- Artificial Intelligence: Training and testing datasets, datascience, computer vision, etc. 

- Define every stage and the scope.

* stage 1 :
- Car hardware: Out of the box working  ( picar project)
- Car software :Out of the box package + dataset creation  ( https://github.com/piperod/SunFounder_PiCar-V) 
- Artificial Intelligence : Simple object detection for marker recognition. 

- * Stage 2: 
- Car Hardware : Sensors + Speed optimization
- Car Software : Input from sensors.  And logging for RL training. 
- Artificial Intelligence : RL Module easy scenario. 

- * Stage 3: 

- Car Hardware : Wheels and optimization for out of the lab exploration
- Car Software : Rl integration 
- Artificial Intelligence : Maze mapping and solution. 

## Achievements. 

Out of the box working. We followed the instruction of the Sun Founder Project and got the car working. 
We started our own fork  https://github.com/piperod/SunFounder_PiCar-V  to create our own dataset sampling at 20fps. 

## To Do > 

Finalize recording module to also include controls. We want a dataset with video and controls as input for our RL algorithm. 

Finalize object detector. 