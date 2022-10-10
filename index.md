---
layout: page
title: The Cyclotron Project
---
#### The ongoing quest to bring garage-grown, locally produced antimatter to a random basement near you. 

![IMAGE](/splash.jpg)

# FAQs\: 

## What is a cyclotron?


A cyclotron is a form of particle accelerator which leverages the Lorentz force exerted on charged particles 
moving in a magnetic field. This allows otherwise long beam-lines to be 'wound' into small volumes. As a result, cyclotrons 
are often very compact compared to linear accelerators achieving similar energies. Our cyclotron has a target energy of 1.1MeV 
(mega electron-volts) and fits in a garden shed (hereafter referred to as *The Shed*)! The space in which the particles circulate is a cylindrical chamber only 16" in diameter and 4" tall.


## Why are you building one? 

Why not build a particle accelerator in your backyard? The project began in school, where a teacher asked us if we wanted to try building a cyclotron. They 
were clearly ignorant to how much effort this would take, and we were too, but we started the project nonetheless. We are both extremely interested in physics,
and so this was a natural project to pursue. We each possessed a useful subset of the skills needed, and we took this as an opportunity to develop those as well as
build off one another's core competencies. 


## What is left to do? 

We currently have all subsystems running at some level or another, but we are yet to fully integrate all systems. The vacuum system needs to undergo a second cryogenic test 
before we can declare it complete. We recently fixed some leaks and replaced one of our isolation valves, so those changes need to be tested in concert with the sorption pump. 
So far we have achieved ~10<sup>-4</sup> torr, which we will soon lower with another cryogenic test. 

The magnets are functional to ~.1T, and need an improved rectifier before running them at higher field strengths. The magnets are a limiting aspect of the system, 
as they are passively cooled and heat very quickly during operation.

The RF oscillator is complete but needs additional testing at higher amplitudes. Our target peak to peak amplitude is 1.2kV.


## Where is this, is it safe? 

  

The setup takes up the left half of Reed Michael's garden shed, although the "whole" cyclotron essentially inhabits the entirety of *The Shed*. 
We designed *The Shed*, in part, to contain the cyclotron – and it is certianly not your typical garden shed. We have a 12 kilowatt electrical connection divided
 between two 120V AC circuits and a 240V AC circuit. *The Shed* is also a Faraday cage, and all of the electrical lines are run underground to minimize RF 
leakage. Our greatest risk is fire, which is mitigated by accessible fire extinguishers and appropriate thermal control. Everything is controlled via a server running 
fault tolerant Linux and, of course, we have a mechanical power disconnect. When running, the cyclotron will also be an X-ray source. We have plans to
 cover the chamber in lead foil, and we have a personal dosimeter and will have dosimeters in and outside of *The Shed*. Everything is controlled from a distance over a 
redundant wireless link (with mechanical shutoffs). 
 

## What are the specs? 


Our cyclotron is a small, 1.1MeV proton cyclotron with 14" diameter "dees." Our magnets produce a field of about 0.3T in the median plane. We have no azimuthal correction, so
our energy is relativistically limited. Our vacuum target (not yet met) is 10e-5 torr. We use two mechanical pumps and one cryosorption pump to achieve this. 
A comprehensive overview of all systems is coming to this website soon. 



