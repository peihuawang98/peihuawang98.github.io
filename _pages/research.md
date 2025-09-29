---
layout: archive
title: "Research" 
permalink: /research/
author_profile: true
---

My research strengthens the resilience of public health systems at the national and building levels by developing mathematical and computational models that integrate infectious disease modeling, building science, and environmental microbiome.

Infectious disease transmission at the national level
------
<figure>
  <img
    src="/images/research/infectious disease population_300dpi.png"
    alt="infectious disease population">
  <figcaption class="research-figcap">
    Mechanistic models incorporating human mobility and climate conditions simulate transmission dynamics within subpopulations and identify epidemiological connections.
  </figcaption>
</figure>

Despite substantial effort on routine and catch-up vaccinations for children, measles elimination in China has not been achieved. Epidemiological evidence suggests that seasonal movement of adult migrant workers and climate conditions may shape measles epidemics. To test these hypotheses, I developed a networked metapopulation and climate-forced Susceptible–Exposed–Infectious–Recovered model that incorporated mobility patterns of rural-to-urban migrant workers between Provincial-Level Administrative Divisions (PLADs) and climate conditions, and used Bayesian inference to estimate model parameters ([Wang _et al_. 2025, _Under review_](https://doi.org/10.1101/2025.06.21.25330021); [Wang _et al_. 2025, _Epidemiol Infect_](https://doi.org/10.1017/S095026882510054X)).

Modeling results showed that epidemics in host PLADs (e.g., Beijing) were driven by susceptibility replenishment from under-vaccinated migrant workers during annual Chinese New Year migration periods. Epidemics in origin PLADs (e.g., Hebei) were synchronized by case importation from migrant workers returning from endemic host PLADs. Traveler mobility had minimal impact on epidemics. Counterfactual modeling of pre-migration vaccination showed a ~50% reduction in incidence nationwide. The model further indicated a bimodal effect of humidity, which, together with temperature, modulated measles transmission. 

By mechanistically modeling the human mobility and climate conditions, I identified previously overlooked susceptible subpopulations that fuel outbreaks and showed how seasonal migration patterns and climate conditions shape epidemic seasonality. These findings can guide public health policy to optimize targeted vaccination strategies and support measles elimination.

Microbial transmission in built environments
------
<figure>
  <img
    src="/images/research/infectious disease building_300dpi.png"
    alt="infectious disease building">
  <figcaption class="research-figcap">
    Mechanistic models that incorporate surface touch behaviors and are calibrated with tracer contamination data simulate microbial transmission dynamics and quantify human exposure.
  </figcaption>
</figure>

Fomites are important vectors for spreading infectious diseases, yet the underlying human behavioral drivers and realistic exposure levels associated with fomite transmission remain unclear. To address this, I developed surface touch networks and agent-based models ([Wang _et al_. 2021, _J Hazard Mater_](https://doi.org/10.1016/j.jhazmat.2021.126137); Zhao _et al_. 2025, _Under review_) to simulate microbial transmission dynamics on skin and surfaces, evaluate the influence of specific surface touch behaviors, and quantify human exposure levels. To provide molecular evidence for model calibration, I developed multiplex qPCR assays (Wang _et al_. 2025, _Under review_; [Wang _et al_. 2021, _Build Environ_](https://doi.org/10.1016/j.buildenv.2021.107869)) to quantify non-toxic and non-human-origin surrogate tracers (Lactobacillus species) on skin and surfaces.

The developed qPCR assays showed high specificity, accuracy, and sensitivity. In field experiments conducted in office and household environments, tracers were spread by designated carriers, and surface touch data were simultaneously collected. Counterfactual agent-based modeling showed that contact with public surfaces (e.g., door handles), hand-to-hand contacts, the presence of active carriers, and the size of social groups containing carriers significantly contributed to tracer spread. These natural and unsupervised experiments showed realistic exposure levels for mouth (~1–10 parts per million (ppm) of total tracers introduced by carriers), nostrils (~1 ppm), and eyes (~0.1 ppm).

By using a methodological framework that integrates tracer quantification and behavioral modeling, the calibrated models reproduced transmission dynamics, identified behavioral drivers of fomite transmission, and estimated realistic fomite exposure at the ppm level. These findings can support targeted surface and hand hygiene practices based on behavior patterns to control fomite transmission in built environments.

Built environment microbiome
------
<figure>
  <img
    src="/images/research/built environment microbiome1_300dpi.png"
    alt="built environment microbiome">
  <figcaption class="research-figcap">
    Microbial invasion ecology of fomite transmission was examined using microbial interaction networks, ecological statistical models, and human surface touch networks.
  </figcaption>
</figure>

Fomite transmission contributes to infectious disease spread. However, pathogens in fomite transmission are either typically studied individually without considering the context of native microbiome or are studied indiscriminately within broader microbial dispersal. To examine the microbial invasion ecology of fomite transmission in built environments, I adopted a framework in which pathogens are considered invaders, the surface environment as an ecosystem, and human behaviors as the drivers of microbial dispersal ([Wang _et al_. 2022, _mSystems_](https://doi.org/10.1128/msystems.00211-22)).

I hypothesized that invaders in fomite transmission are trackable, neutrally distributed between hands and environmental surfaces, and exhibit a proximity effect. To test this hypothesis, a non-toxic, non-human-origin surrogate invader, Lactobacillus bulgaricus, was spread by a root carrier. First, invader was trackable, as L. bulgaricus was identified as the invader using microbial interaction networks, and the root carrier was located. Additionally, multiple-taxa invasion from sputum was identified. Second, the invader had a below-neutral distribution in a neutral community model, suggesting that hands accrued higher invader contamination than surfaces. Third, a proximity effect was observed on a surface touch network, indicating that the carrier’s behaviors were the main driver for fomite transmission.

By adopting an invasion ecology framework, the built environment microbiome can serve as an important data source for identifying microbial invaders and tracing their sources. These findings demonstrate the potential of using microbiome data for early detection of pathogen circulation in built environments and suggest that intervention strategies for fomite transmission should focus on entire microbial communities rather than pathogens alone.