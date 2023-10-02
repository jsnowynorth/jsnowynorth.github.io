---
layout: archive
# title: "Research"
title: ""
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


# Probablistic Basis Functions

When working with large data (such as spatio-temporal data) it is often convenient to represent it using a low-rank process, which can done using matrix factorization methods such as singular value decomposition (SVD).
SVD decomposes matrix-valued data into the product of basis functions, the left- and right-singular vectors, and associated vector lenghts, the singular values.
The singular vectors can be grouped into an orthonormal matrix (a matrix whose columns are of unit length and orthogonal to the other columns).
For space-time processes, these basis functions can have physical representation and are useful when modeling the process.
I am currently developing distributions and models to estimate the basis functions from SVD, or more generally for any orthonormal matrix, in a probablistic manner and incorporate these estimates within more complex spatio-temporal model (paper to come).
Check out my [code]({% link _pages/code.md %}) page if you're interested in using this!


# Climate Extremes

Climate change has resulted in the increase in frequency and severity of extreme weather events such as the 2021 North America heat wave or Hurricane Harvy.
One of the main goals of the CASCADE group is to investigate the drivers and variability of these extreme events to determine if they could be predicted from the historic record.
I am currently investigating whether the 2021 North American heat wave "falls" within the natural variability of its climate system and, if not, the external forcing that caused such a severe heat wave.

<!-- As a member of the CASCADE group, I am involved in projects aimed at understanding the drivers and variability of extreme events and at our ability to properly model extremes. -->


# Data-Driven Discovery of Nonlinear Dynamics

Many real-world scientific processes are governed by complex nonlinear dynamic systems that can be represented by differential equations.
However, because of the complexity of the processes, the differential equations used to represent these systems are rarely known.
My dissertation work focused on Bayesian methods to discover the nonlinear dynamic equations governing complex real-world processes.
If you are interested in using any of the methods I developed, check out my [code]({% link _pages/code.md %}) page!


# Collaborations

I am fortunate enough to be working with a talented group of aquatic ecologists at the University of Minnesota Twin Cities and Pennsylvania State University developing statistical models to investigate the effects of a changing climate on freshwater ecosystems. Our main area of focus is on how the distribution, abundance, and composition of freshwater fish have changed in response to water conditions. We use a combination of spatio-temporal statistics, species distribution modeling, and physiological information to answer these complex ecolgical questions.