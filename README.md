Evaluating the Impact of Removing the MBTA Green Line D Branch


📌 Overview

This project evaluates the impacts of removing the MBTA Green Line D Branch on travel behavior and roadway network performance in the Boston metropolitan area.
Using a four-step travel demand modeling framework, the study analyzes mode choice shifts, traffic demand reallocation, and congestion impacts under a transit service removal scenario.

The analysis compares a base case network with an alternative no–D branch scenario, isolating the effects of transit network modification on system performance.

✨ Objectives

Assess changes in traffic volumes, congestion, and travel times following removal of the Green Line D Branch

Examine home-based work (HBW) mode choice reallocation between auto and transit

Compare base case and no–D branch network conditions

Provide insights into transit system resilience and planning implications

1. Study Area & Data

The study area covers the Boston metropolitan region, as defined by the Boston MPO, including a dense multimodal network of roadways and MBTA transit services.

Data sources include:

MBTA GTFS data for transit routes, schedules, and travel times

Boston MPO roadway network data (capacity, speed, lanes)

Transportation Analysis Zones (TAZs) for regional demand modeling

All datasets were processed to ensure spatial and modal consistency prior to model implementation.

2. Travel Demand Modeling Framework

A four-step travel demand modeling approach was implemented in TransCAD:

2.1 Trip Generation & Distribution

Home-based work (HBW) trips were generated and distributed using fixed OD matrices

Trip generation and distribution were held constant across scenarios

2.2 Mode Choice

Mode choice was modeled using a nested logit formulation

Utility functions included:

Travel time

Monetary cost

Parking cost

Household income

Mode choice probabilities were applied to fixed OD matrices to allocate trips between auto and transit.

2.3 Traffic Assignment

Auto trips were assigned using user-equilibrium (UE) assignment

Congestion effects were captured using volume–delay functions

Outputs include link-level volumes, delays, travel times, and V/C ratios

3. Scenario Analysis: Removal of the Green Line D Branch

In the alternative scenario, the Green Line D Branch was removed from the transit network.
Corresponding transit skims were regenerated, and the mode choice and traffic assignment steps were re-run using identical demand inputs.

This approach isolates the effect of transit service removal on:

Mode allocation

Roadway congestion

Network performance

📈 Results
✔ Mode Choice Response

Mode choice shifts are driven by relative generalized travel cost changes

Increased auto congestion reduces driving utility, producing non-intuitive mode reallocation effects

✔ Network Performance

Modest increases observed in:

Traffic volumes

Vehicle miles traveled (VMT)

Vehicle hours traveled (VHT)

Congestion impacts are spatially concentrated along corridors parallel to the former D Branch

✔ System Interpretation

Removal of a high-capacity rail service produces localized but measurable congestion effects

Results highlight the nonlinear relationship between transit availability and roadway performance

🛠 Tools & Methods

TransCAD

Four-step travel demand modeling

Nested logit mode choice modeling

User-equilibrium traffic assignment

GTFS-based transit skimming

📚 References

Train, K. — Discrete Choice Methods with Simulation

Wardrop, J. — Traffic assignment equilibrium theory

MBTA — Green Line D Branch service documentation
