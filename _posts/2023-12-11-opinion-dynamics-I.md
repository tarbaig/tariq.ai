---
title: "Opinion dynamics in social networks: From models to data"
date: 2023-12-11
---

# Overview

I decided to start getting into the topic by picking a more or less random review paper. This particular one drew my eye since the title hinted at a desire to connect mathematical toy models to observational or experimental data.

As expected the paper gives an overview about different mathematical models of opinion dynamics and than proceeds to a review of recent work in connecting some of those models to experimental or observational data. 

# Models of Opinion Dynamics
Common to all models reviewed is that they view individual as nodes in a graph and are concerned with how nodes change an internal representation of opinion based on the opinion of connected nodes.
Tow brad classes of Models are mentioned: Those with discreet opinion representation and those with continuous opinion representation. 

## Discreet Opinions

### Binary Opinion
Discreet models of opinion treat the internal opinion variables as limited to on of several states. The simplest model is that of a single binary variable. 

The binary case has a large overlap with models of disease spread, and the underlying assumption simplifies the mathematical treatment and opinion spread can be studied in terms of the transition rates $F$ and $R$.  

Models can than be formulated e.g. in terms of the transition rates and their functional forms and noise.  

A particularly well studied model seem to be the case of a simple linear dependency between the opinion of an agents neighbors and his own; this called the voter model.  

### Non Binary Case
The paper claims that multi state versions of opinions could be reduced to binary versions by appropriate rescaling, but unfortunately this claim is not accompanied by a citation.  
The most noteworthy multi-opinion model mentioned is the **Axe;rod model$$, which models agents as having $q$ cultural traits and has them adopting traits from other agents based not only on connectivity but also based on distance in opinion space.






