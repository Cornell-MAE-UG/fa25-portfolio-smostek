---
layout: project
title: Wind Turbine Design
description: MAE 4272 Design Project
technologies: [MATLAB]
image: /assets/images/stockWindFarm.jpg
---
One of the required courses for MAE Majors is MAE 4272 Fluids and Heat Transfer Laboratory, a class focused on applying the math of previous courses to physical fluids and heat transfer systems. As a class project teams of students were tasked with designing and testing a wind turbine blade.

Another MAE Major requirement is a Senior Design Class, for which I chose MAE 4021 Wind Power. This course covered many aspects of wind energy, from structural mechanics to siting to blade erosion, but a large portion of the final project was the development of software to desing and test a wind turbine blade.

You might be able to see how these two facts are connected.

I, unsurprisingly, chose to take on the design portion of the MAE 4272 project, so rather than giving an exhautive description of how I derived formulae for blade geometry in this bad markup language, I'll just link to [my report]({{ "/assets/Wind_Power_Final_Project" | relative_url }}) written in a slightly less bad markup language.

The main takeaway, regardless, is this: I'm smarter than my textbook. Ok, well, that's not really fair. Essentially, the equations for blade geomtry come from the pairing up of two models: one, a fluid dyanmical model of an actuator disk that doesn't assume drag; and a more geometric model of the forces on an airfoil that can easily incorporate drag. The textbook went through the calculations assuming no drag only to attach an additional term, Prandtl's tip loss factor, and claim it allowed for the equality of the two models with drag included. I was able to show this to be false: the equality as written could not hold given the other assumptions. So I did what any normal person would do in this situation and rederived everything from scratch. The result was a piece of software that, at least for the dataset we were given as reference, was significantly better at predicting airfoil performance than commercial CFD sofware. If you want more detail than that, go read the report.
