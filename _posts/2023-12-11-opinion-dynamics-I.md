---
title: "Opinion dynamics in social networks: From models to data"
date: 2023-12-11
---

# Overview

I decided to start getting into the topic by picking a more or less random review paper. This particular one drew my eye since the title hinted at a desire to connect mathematical toy models to observational or experimental data.

As expected the paper gives an overview about different mathematical models of opinion dynamics and than proceeds to a review of recent work in connecting some of those models to experimental or observational data. 

# Main Takeaway
The main things to be taken from this paper are the references to experimental studies, and some background that will make those studies easier to read. 

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

The most noteworthy multi-opinion model mentioned is the **Axelrod model** , which models agents as having $q$ cultural traits and has them adopting traits from other agents based not only on connectivity but also based on distance in opinion space.  
This model shows a transition from a mono to a multi-cultural state as the number of cultural states increases. 

## Continuous Opinions

Continuous models of opinions model opinions as taking on values on the reals. A model highlighted in the paper is the Deffuant model aka bounded confidence dynamics, which confines opinions to the interval $[0,1]$ and has people only interact if their distance in opinion space is not to large. 

The authors claim that this model is one of the few empirical validated opinion dynamic models. A brief overview of phenomena that can be observed in this model is given. \


# Connection to Data

This section mainly gives references to empirical studies.

## Discreet Models
For discreet opinion dynamics there does not seem to be an universally agreed upon best fit for even the shape of the transition rates.

>  Given the variability in experimental setups and their sometimes conﬂicting results (Mercier and Morin, 2019), we can expect empirical data on F to depend on the social context studied and the particularities of each experiment.

## Continuous Opinions 

> In the spirit of bounded conﬁdence models, subjects state their opinion and conﬁdence in it, engaging in this process over several rounds. The experiment of Chacoma and Zanette (2015) identiﬁes three behavioral categories based on how individuals inﬂuence each other: (i) keep, where the opinion of a person remains unchanged; (ii) adopt, where the subject copies a reference opinion; and (iii) compromise, where the individual approaches the reference opinion (see Fig. 1c).

> Results indicate that the most common behavior is keep, followed by compromise and ﬁnally adopt. The chosen behavior depends on the diﬀerence in conﬁdence between the individual and reference opinions. The keep behavior is more probable when the subject is more conﬁdent than the reference; the compromise and adopt behaviors are more common in the opposite case. Curiously, there is no signiﬁcant correlation between the opinion diﬀerence and the class of inﬂuence behavior. Thus, a metric comparison with reference opinions has a negligible eﬀect on how agents respond to inﬂuence, in contrast to some of the continuous opinion models.


# Current limitation




