---
layout : post
title : Lumped Matter Discipline
description : Circuit and Electronics provides an abstraction over the maxwell's equations of electromagnetics. Lumped circuit model help us in simplifying the complex physical property of elements, indeed, to make it more abstract and meaningful.
mathjax: true
categories : [Analog and Digital Electronics, Lumped circuit Abstraction]
---

*This post is part of Circuit and Electronics, 6.02, Lectures by Prof. Anant Agarwal of MIT EECS Department and his book Foundations of Analog and Digital Electronics circuit. I write this post as summarisation of my learning from lecture 1 and greatful to the prof. for this wonderful lecture series. Lecture 1 is the introduction of circuit abstraction and how from electrons, Engineers created abstractions by considering different patterns to create millions of electronic devices, that we are enjoying nowadays!*

# The Circuit Abstraction
### The Power of Abstraction

Electromagnetics from physics point of view, As we know that whole electromagnetics is governed by Maxwell's law which includes laws of electrostatics, Magnetostatics, Faraday's law of Induction and Continuity equation, these equations were formulated by great scientists by conducting various experiments and with certain data to keep in mind, Though physicists are mostly interested in phenomenons, how they are occuring naturally inside and how they react with other elements.

Electrical engineers are those which make purposeful use of Maxwell's Equations, indeed as we know maxwell's equation use calculus criterion of approximating the values we are interested in viz. Electric Fields, Current Density, but These equations can make our analysis of system quite cumbersome, thus we need abstraction to build some simple stuffs on top of these.

Abstractions make our life easy but with certain constraints, Constraints are situations under which our element performs according to simple equations as we need. If you have read about ohm's law or maybe we take simplest form of abstraction in mechanics, we may all know about Newton's second law of force

$$F=m*a$$

where, m is mass of body and a is acceleration which is rate of change of velocity, here we have use point mass simplification for the whole body to understand what will be the Acceleration if we had applied some known force.

point mass simplification as suggests for the accuracy purposes we consider point masses of the body then summation over the volume of body to get whole mass of system, which will be quite cumbersome if we have weight machines to simply weight them, then take mass to get Acceleration and it's direction on the body.

Abstraction is supported by discretizing Discipline that is to make complex systems, we have to start with a discrete element for an eg, Resistor for our circuit, so discretizing Discipline is about providing values to discrete element.