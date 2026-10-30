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


# Data-Driven Discovery and Physics-Informed Models

Many real-world scientific processes are governed by complex nonlinear dynamic systems that can be represented by differential equations.
However, because of the complexity of these processes, the equations are rarely known.
My dissertation work focused on Bayesian methods to discover the nonlinear dynamic equations governing complex real-world processes, with uncertainty quantification.
I am now combining this with physics-informed neural networks to embed physical equations in statistical models and quantify uncertainty in the dynamics.
<!-- If you are interested in using any of the methods I developed, check out my [code]({% link _pages/code.md %}) page! -->


# Probabilistic Basis Functions

When working with large data (such as spatio-temporal data), it is often convenient to represent it using a low-rank process, which can be done using matrix factorization methods such as singular value decomposition (SVD).
SVD decomposes matrix-valued data into the product of basis functions, the left- and right-singular vectors, and associated vector lengths, the singular values.
The singular vectors can be grouped into an orthonormal matrix (a matrix whose columns are of unit length and orthogonal to the other columns).
For space-time processes, these basis functions can have a physical interpretation and are useful when modeling the process.
The catch is that they are usually treated as fixed, which makes it hard to say anything about uncertainty.
I developed a prior distribution for orthonormal matrices that lets you estimate the basis functions in a probabilistic manner and use them within a spatio-temporal mixed-effects model.
I have since extended this to tensor-valued, non-Gaussian data with a Bayesian tensor decomposition model for exponential families.
<!-- Check out my [code]({% link _pages/code.md %}) page if you're interested in using this! -->



# Climate Extremes

Much of the CASCADE group's work is about understanding the drivers of extreme weather and climate events, and a lot of my recent work in this area has focused on snow.
Snow is one of the largest freshwater reserves in the western United States, and it is vulnerable to both warming and extreme events that compound one another.
I led the statistical analysis for a study of "snow-eater" heat waves, multi-day warm spells that eat away at snowpack.
I also worked on how back-to-back atmospheric rivers affect runoff along the West Coast, and I am working with students on the joint likelihood of the multiple extremes behind the 1997 California New Year's flood and on a probabilistic model for rain-on-snow events.

I also work on AI weather and climate emulators, which can generate huge ensembles that would be impractical with traditional models.
I helped validate and calibrate a neural network for extreme weather emulation using large-sample statistics.
That led to a bigger question: observational records are short, which makes very rare events and long return periods hard to characterize, so can emulator output help?
I developed a Bayesian extreme value framework that blends observations with emulator ensembles and tests where the emulator adds value.
Applied to the contiguous US, it reduces uncertainty in temperature upper bounds over the western and eastern regions, but not over most of the southern, central, and southwestern regions.



# Fish Population Ecology

I also work with a great group of aquatic ecologists at multiple institutions developing statistical models to investigate the effects of a changing climate on freshwater ecosystems.
Our main focus is on how the distribution, abundance, and composition of freshwater fish have changed in response to water conditions.
We use a combination of spatio-temporal statistics, species distribution modeling, and physiological information to answer these complex ecological questions.
More recently, we have turned to estuaries, building models to understand how vessel traffic affects Atlantic Sturgeon in New York Harbor, a project funded by the Hudson River Foundation.