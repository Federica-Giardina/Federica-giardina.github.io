---
title: SchiSTOP
subtitle: 'Beyond mass drug administration: understanding schistosomiasis dynamics to STOP transmission'
layout: project
description: SchiSTOP, an agent-based modelling framework for Schistosoma mansoni transmission and control.
facts:
  - label: Funding
    value: Marie Skłodowska-Curie Individual Fellowship, Horizon 2020 (grant 846873)
  - label: Period
    value: 2021 – 2023
  - label: Partners
    value: Radboudumc (coordinator), Erasmus MC, University of Glasgow
  - label: Team
    value: Federica Giardina, Veronica Malizia
  - label: Collaborators
    value: Sake J. de Vlas (Erasmus MC), Poppy Lamberton (University of Glasgow)
links:
  - label: Model code on GitHub
    url: https://github.com/VeronicaMalizia/SchiSTOP_model
    icon: fa-brands fa-github
  - label: Project page (CORDIS)
    url: https://cordis.europa.eu/project/id/846873
figures:
  - src: images/papers/schistop-prevalence-2024.png
    alt: Simulated prevalence in school-aged children during and after mass drug administration
    caption: 'Prevalence timelines in school-aged children during and after treatment. Malizia et al. 2024, [PLOS NTD](https://doi.org/10.1371/journal.pntd.0012464), CC BY 4.0.'
  - src: images/papers/schistop-age-intensity-2024.png
    alt: Age-intensity profiles of infection under different assumptions
    caption: 'Age-intensity profiles under different assumptions on age-exposure and anti-reinfection immunity. Malizia et al. 2024, [PLOS NTD](https://doi.org/10.1371/journal.pntd.0012464), CC BY 4.0.'
related_dois:
  - 10.1371/journal.pntd.0012464
---
Schistosomiasis is one of the most widespread neglected tropical diseases.
Control relies on mass drug administration (MDA) with praziquantel, but in
areas with moderate or high prevalence, infection levels often rebound quickly
after each treatment round, and the reasons for this are poorly understood.

SchiSTOP is a modelling framework built to explain this rebound and to explore
how current and new control strategies can best be combined to move towards
elimination. It is a stochastic agent-based model of *Schistosoma mansoni*
transmission in an age-structured human population, with an integrated ODE
module that simulates infection dynamics in the snail intermediate host. Users
can specify alternative assumptions about the mechanisms that regulate
transmission and compare how they affect the outcomes of control programmes.

Methods to calibrate the model with history matching and emulation are
described in a submitted manuscript. The framework is designed to be adapted to
other infections targeted by MDA, and the model code is openly available on
GitHub.
