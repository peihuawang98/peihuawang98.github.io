---
layout: archive
title: "Research" 
permalink: /research/
author_profile: true
---

My research strengthens the resilience of public health systems by developing computational models that integrate infectious disease epidemiology with built and urban environment research.

Infectious disease transmission at the population level
------
<figure>
  <img
    src="/images/research/infectious disease population_300dpi.png"
    alt="infectious disease population">
  <figcaption class="research-figcap">
    Mechanistic models incorporating human mobility and climate conditions simulate transmission dynamics within subpopulations and identify epidemiological connections.
  </figcaption>
</figure>

Despite substantial efforts on routine childhood vaccination, measles epidemics in China have persisted. Epidemiological evidence suggests that worker migration and climate conditions may shape measles epidemics. To test these hypotheses, I developed a networked metapopulation and climate-forced Susceptible–Exposed–Infectious–Recovered model that incorporated human mobility, demographic structure, and climate conditions, and used Bayesian iterated filtering for parameter inference ([Wang _et al_. 2025, _PLoS Comput Biol_](https://doi.org/10.1371/journal.pcbi.1014182); [Wang _et al_. 2025, _Epidemiol Infect_](https://doi.org/10.1017/S095026882510054X)).

Modeling results showed that epidemics in migrant worker host provinces were driven by susceptibility replenishment from under-vaccinated rural-to-urban migrant workers during annual Chinese New Year migration periods. Epidemics in origin provinces were synchronized by case importation from these migrant workers returning from endemic host provinces. Counterfactual modeling of pre-migration vaccination showed a ~50% reduction in incidence nationwide. The model further indicated a bimodal effect of humidity, whereby both low and high absolute humidity levels increased measles transmissibility. 

By mechanistically modeling population and climate factors, I identified previously overlooked susceptible subpopulations that fuel epidemics and showed how seasonal migration patterns and climate conditions shape epidemic seasonality. These findings can guide public health policy to optimize targeted vaccination strategies and support measles elimination.

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

Fomite transmission is an important route for infectious diseases, yet its human behavioral drivers and realistic exposure levels remain unclear. To address this, I developed surface touch networks and agent-based models to simulate fomite transmission dynamics and human exposure in built environments ([Zhao _et al_. 2025, _Environ Sci Technol_](https://doi.org/10.1021/acs.est.5c06069); [Wang _et al_. 2021, _J Hazard Mater_](https://doi.org/10.1016/j.jhazmat.2021.126137)). To provide molecular evidence for model calibration, I developed multiplex qPCR assays to quantify non-toxic, non-human-origin surrogate tracers (_Lactobacillus_ species) on skin and surfaces (Wang _et al_. 2025, _Under review_; [Wang _et al_. 2021, _Build Environ_](https://doi.org/10.1016/j.buildenv.2021.107869)).

During unsupervised office and household experiments, tracers were spread by designated carriers, and surface touch data were collected by video surveillance. qPCR-calibrated modeling results showed that contact with public surfaces and the presence of active carriers significantly increased tracer spread, and that the exposure levels of the mouth, nostrils, and eyes to carrier introduced tracers were ~1–10 parts per million. Tracer contaminations on air conditioning filters that were twice the median of all samples indicated potential airborne transmission through particle resuspension from fomites. 

By integrating tracer quantification and behavioral modeling, these analyses support targeted hand and surface hygiene practices to control fomite transmission and highlight the risk of airborne transmission originating from fomites.

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

I hypothesized that invaders in fomite transmission are trackable, neutrally distributed between hands and environmental surfaces, and exhibit a proximity effect. To test this hypothesis, a non-toxic, non-human-origin surrogate invader, _Lactobacillus bulgaricus_, was spread by a root carrier. First, invader was trackable, as _L. bulgaricus_ was identified as the invader using microbial interaction networks, and the root carrier was located. Additionally, multiple-taxa invasion from sputum was identified. Second, the invader had a below-neutral distribution in a neutral community model, suggesting that hands accrued higher invader contamination than surfaces. Third, a proximity effect was observed on a surface touch network, indicating that the carrier’s behaviors were the main driver for fomite transmission.

These findings show the potential of applying invasion ecology theories to infectious disease research for pathogen tracing.