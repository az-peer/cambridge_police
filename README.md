# cambridge_police

<img src="police_badge.png" alt="description" width="400" height="400">

Authors:
Anders Steines, Aziz Malouche, Azfal Peermohammed

Public safety is a foundational pillar of any thriving community. Effective police resource allo-
cation is a critical challenge for public safety agencies, especially in urban environments where
crime dynamics vary spatially and temporally. Police departments often face constraints in
staffing, limiting their ability to respond promptly to incidents, and maintain public trust. Op-
timally restructuring where officers are stationed and how they are assigned could help mitigate
the challenges caused by reduced personnel, ensuring that the limited resources available are
used where they can make the greatest impact.
Using crime data from Cambridge, Massachusetts, this analysis seeks to determine the optimal
locations for police stations and the allocation of officers to address crime patterns efficiently. By
aligning resource placement with areas of greatest need, this approach aims to improve outcomes
despite staffing constraints.
Although focused on Cambridge, the methodology offers insights that are relevant to cities
nationwide. Any municipality with access to similar data can apply this approach to reimagine
its police station and officer allocation strategies, enhancing its ability to respond to and solve
crimes. In a time of increased scrutiny and constrained resources, optimizing police resources can
be a vital step toward building safer, more resilient communities. By improving the efficiency
and equity of resource distribution, this data-driven approach has the potential to maintain
public trust in law enforcement and strengthen the relationship between police departments and
the communities they serve. This project both employs an adaptive stochastic optimization model and a deterministic model.
The motivation for a two-stage stochastic optimization model for police station location is to
account for the inherent variability in crime dynamics over time to provide robust/generalizable
solutions, which will be evaluated on an out-of-sample test set (first 5 months of 2024). The
deterministic formulation is almost equivalent, the main difference is that the adaptive stochastic
optimization model includes scenarios for second stage decision variables.

