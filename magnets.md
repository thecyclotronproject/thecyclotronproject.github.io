---
layout: page
title: The Magnets
permalink: /magnets-link/
---

### “The best unit for quantifying fire risk is the Tesla” 



![The magnets](/magnets.jpg)

![magnet Test](/magnetTest.jpg)


The magnets make up one of three critical subsystems in a cyclotron. They generate the magnetic 
field for containing the particles and they present a host of interesting engineering challenges. Our magnets 
are designed to run up to 0.03T, and they are by no means efficient at doing this. Inefficiencies are the primary 
opponent when designing huge electromagnets like these. If we were operating on a large budget, we would make all 
of our design decisions with respect to two quantities: magnetic field strength and heat generation/dissipation. 
As we pump high currents through the windings of the magnets, they heat excessively. We currently don’t have any
 mechanism by which we can actively cool the magnets, so we are limited to running them in short pulses. We essentially
 need to minimize the amount of heat absorbed by other critical components such as the vacuum chamber (particularly 
the large o-rings sealing the top and bottom of the main chamber).   


## Operating the magnets

The magnets are run using two Variac variable transformers – one for each magnet. The output of each transformer is rectified 
and fed to the coil. It is very important that we regulate the magnets carefully and that they can be controlled independently 
– varying the field characteristics in the median plane. As this must be done remotely, we drive the Variacs using stepper motors 
controlled using an Arduino which is networked to the rest of the system. 

![Magnet Driver](/MagnetDriver.jpg)


For monitoring, we have magnetic hall effect sensors in the median plane and near our ion gauge (a magnetically sensitive component).
 Thermocouples are attached to each magnet as well which give us the temperature of each magnet individually and trigger an automatic shutoff 
if either magnet begins to overheat.


## The yoke    

The solid steel yoke doubles the efficiency of our magnets, greatly reducing the current we must supply. Furthermore, the yoke acts as a large heatsink 
that helps to cool the magnet coils. It is a rather simple structure: a rectangular arrangement of solid steel bars – which have high magnetic permeability. 
The coils themselves are each  wound around a steel frame which further improves magnet performance. This structure, however, is not solid – as making it solid 
wouldbe quite expensive. Due to budgetary constraints (and the generosity of a friend) we constructed the main structure of the yoke from discarded elevator weights.
 These were cut to size and then welded together. In total, the yoke and magnets weigh a bit over 400lbs. 


![The Yoke](/yoke.jpg)
Please pardon the welds -- I am a horrible welder, but I am learning! -Reed Michael