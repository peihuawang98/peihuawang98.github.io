---
layout: archive
title: "Research" 
permalink: /research/
author_profile: true
---

My research strengthens the resilience of public health systems by developing computational models that integrate infectious disease epidemiology with urban and built environment research.

Infectious disease transmission at the population level
------
<figure>
  <img
    src="/images/research/infectious disease population_300dpi.png"
    alt="infectious disease population">
  <figcaption class="research-figcap">
    Epidemic model for simulating transmission dynamics and identifying epidemiological connections.
  </figcaption>
</figure>

Despite routine childhood vaccination coverage exceeding the herd immunity threshold and substantial supplementary immunization activities toward the WHO Western Pacific Region’s measles elimination goal, measles epidemics have persisted in China. Epidemiological evidence suggests that worker migration and climate conditions may shape these epidemics. To test these hypotheses, I developed a climate-forced, networked metapopulation Susceptible–Exposed–Infectious–Recovered model that incorporated human mobility, demographic structure, and climate conditions, and used Bayesian iterated filtering for parameter inference ([Wang _et al_. 2026, _PLoS Comput Biol_](https://doi.org/10.1371/journal.pcbi.1014182); [Wang _et al_. 2025, _Epidemiol Infect_](https://doi.org/10.1017/S095026882510054X)). 

The model showed that measles epidemics were driven by the seasonal mobility of under-vaccinated rural-to-urban migrant workers around Chinese New Year and identified epidemiological connections between provinces. Counterfactual analysis showed that targeted vaccination of migrant workers could reduce incidence by ~50% nationwide. The model further identified a bimodal humidity effect, whereby both low and high absolute humidity levels increased measles transmissibility. By mechanistically modeling population and climate factors, I identified previously overlooked susceptible subpopulations as key epidemic drivers and showed how climate conditions modulate transmission. These findings can inform targeted vaccination strategies and support measles elimination efforts.

Microbial transmission at the building level
------
<figure>
  <img
    src="/images/research/infectious disease building_300dpi.png"
    alt="infectious disease building">
  <figcaption class="research-figcap">
    Transmission models calibrated with field tracer measurements for simulating fomite transmission dynamics and quantifying occupant exposure.
  </figcaption>
</figure>

Fomite and airborne transmission are important infectious disease transmission routes, yet their human behavioral and environmental drivers, as well as realistic occupant exposure levels, remain unclear. To investigate fomite transmission, I developed surface touch networks and agent-based models to simulate transmission dynamics and occupant exposure in built environments ([Zhao _et al_. 2025, _Environ Sci Technol_](https://doi.org/10.1021/acs.est.5c06069); [Wang _et al_. 2021, _J Hazard Mater_](https://doi.org/10.1016/j.jhazmat.2021.126137)). To provide molecular evidence for model calibration, I developed multiplex qPCR assays to quantify non-toxic, non-human-origin surrogate tracers (_Lactobacillus_ species) on skin and surfaces (Wang _et al_. 2026, _Under review_; [Wang _et al_. 2021, _Build Environ_](https://doi.org/10.1016/j.buildenv.2021.107869)). The qPCR-calibrated models showed that occupant exposure levels of the mouth, nostrils, and eyes to carrier introduced tracers were ~1–10 parts per million. Targeted hygiene of high eigenvector centrality public surfaces and timely handwashing upon entry to built environments could reduce exposure by one order of magnitude. These findings can support targeted hand and surface hygiene practices to control fomite transmission.

As a member of the Hong Kong special task force, I investigated SARS-CoV-2 airborne transmission by integrating building physics models with SF<sub>6</sub> tracer gas experiments, showing that the chimney effect in soil stacks was a potential mechanism driving vertical transmission from lower to upper floors in high-rise residential buildings during winter. These findings have been translated into engineering control strategies, including maintaining drainage stacks and sealing water traps, to control vertical airborne transmission.

Built environment microbiome
------
<figure>
  <img
    src="/images/research/built environment microbiome1_300dpi.png"
    alt="built environment microbiome">
  <figcaption class="research-figcap">
    Invasion ecology of fomite transmission.
  </figcaption>
</figure>

I further analyzed skin and surface samples to examine the invasion ecology of fomite transmission ([Wang _et al_. 2022, _mSystems_](https://doi.org/10.1128/msystems.00211-22)). Microbiome interaction networks identified _Lactobacillus_ as the invader, indicating that the invader was trackable. Neutral community models suggested a preferential association of the invader with skin over environmental surfaces. Additionally, surface touch networks showed an invader proximity effect, indicating that carrier’ behavior was the key driver of fomite transmission. These findings show the potential of applying invasion ecology theory to infectious disease research for pathogen tracing.
