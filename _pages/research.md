---
layout: archive
title: "Research" 
permalink: /research/
author_profile: true
---

My research addresses questions related to infectious disease and microbial transmission by integrating infectious disease modeling, building science, and environmental microbiology. I use modeling techniques to generate hypotheses that can be tested through epidemiological, behavioral, genomic, and environmental data. Specifically, my research aims to answer: (1) What factors drive infectious disease transmission at the population level? (2) What factors drive microbial transmission, and what are microbial exposure levels in built environments? (3) How do invading microbial species interact with native indoor microbial communities during invasions? Insights from my work can inform optimized strategies for microbial surveillance and infection control.

Infectious disease transmission at the population level
------
<!-- ![infectious disease population](/images/research/infectious disease population.png) -->
<figure>
  <img
    src="/images/research/infectious disease population.png"
    alt="infectious disease population">
  <figcaption class="research-figcap">
    Schematic of infectious disease transmission modeling. Mechanistic models incorporating human mobility and climate conditions simulate transmission dynamics within subpopulations and identify epidemiological connections between regions.
  </figcaption>
</figure>

Despite sustained routine childhood vaccination coverage of ≥ 95% since 2005, measles outbreaks in China have persisted and exhibited pronounced seasonality across Provincial-Level Administrative Divisions (PLADs). Epidemiological evidence suggests that seasonal worker migration and climate conditions potentially shape measles epidemics. To test these hypotheses, I examined the roles of inter-PLAD rural-to-urban migrant workers ([Wang _et al_. 2025, _Under review_](https://doi.org/10.1101/2025.06.21.25330021)), who originate from less-developed rural regions with potentially lower vaccination coverage, and climate conditions (Wang _et al_. 2025, _Under review_) in driving measles epidemics across PLADs between 2005 and 2014. I developed a networked metapopulation and climate-forced Susceptible–Exposed–Infectious–Recovered model that incorporated detailed mobility patterns and climate conditions, and used Bayesian inference techniques to estimate model parameters.

For the mobility component, simulations of measles transmission dynamics within both local and migrant worker subpopulations identified key epidemiological connections between migrant workers origin and host PLADs. Modeling results showed that epidemics in host PLADs were driven by susceptibility replenishment from under-vaccinated migrant workers during annual Chinese New Year migration periods. Additionally, epidemics in origin PLADs were synchronized and facilitated by case importation from migrant workers returning from endemic host PLADs, and the strength of this seeding effect depended on migrant worker flow volumes. Conversely, traveler mobility had minimal impact on measles epidemics. Counterfactual modeling of pre-migration vaccination showed a ~50% reduction in incidence nationwide. For the climate component, the model indicated a bimodal effect of humidity, which, together with temperature, modulated measles transmission. These findings provide mechanistic insights into how seasonal worker migration and climate conditions shape measles epidemics and could inform targeted intervention strategies. 

Microbial transmission in built environments
------
<figure>
  <img
    src="/images/research/infectious disease building.png"
    alt="infectious disease building">
  <figcaption class="research-figcap">
    Schematic of microbial transmission modeling. Mechanistic models incorporating human surface touching behaviors were calibrated using tracer contamination data. The calibrated models were used to simulate microbial transmission dynamics and quantify human exposure.
  </figcaption>
</figure>

Fomites are important vectors for spreading infectious diseases, yet the underlying human behavioral drivers and realistic exposure levels associated with fomite transmission routes remain unclear. To identify these behaviors and quantify exposure, I developed multiplex qPCR assays (Wang _et al_. 2025, _Under review_; [Wang _et al_. 2021, _Build Environ_](https://doi.org/10.1016/j.buildenv.2021.107869)) to quantify surrogate bacterial tracers (*Lactobacillus* species) that are non-toxic, non-human-origin, and absent from built environments. I also constructed surface touch networks ([Wang _et al_. 2021, _J Hazard Mater_](https://doi.org/10.1016/j.jhazmat.2021.126137); Zhao _et al_. 2025, _Under review_) to identify behaviors facilitating fomite transmission. Subsequently, I developed agent-based models ([Wang _et al_. 2021, _J Hazard Mater_](https://doi.org/10.1016/j.jhazmat.2021.126137); Zhao _et al_. 2025, _Under review_), calibrated with tracer contamination data from skin and surfaces, to simulate microbial transmission dynamics, evaluate the influence of specific surface touching behaviors, and quantify human exposure levels.

The developed qPCR assays quantifying tracer genes showed high specificity (amplifying exclusively target tracer genes in environmental samples), accuracy (aligning with fluorometer measurements), and sensitivity (detecting down to 10 copies). In field experiments conducted in office and household environments, tracers were spread by designated carriers during normal daily activities, and high-resolution surface-touch data were simultaneously collected. Counterfactual agent-based modeling showed that contact with public (e.g., door handles) and hidden public surfaces (e.g., desks, chair seatbacks), hand-to-hand contacts, the presence of active carriers, and the size of social groups containing carriers significantly contributed to tracer spread. These natural and unsupervised experiments showed realistic exposure levels for mouth (~1–10 ppm of total tracers introduced by carriers), nostrils (~1 ppm), and eyes (~0.1 ppm). These findings provide mechanistic insights into how human surface touching behaviors facilitate fomite transmission and provide quantitative assessments of fomite exposure risks in built environments.

Built environment microbiome
------
<figure>
  <img
    src="/images/research/built environment microbiome.png"
    alt="built environment microbiome">
  <figcaption class="research-figcap">
    Schematic of built environment microbiome research. Microbial invasion ecology of fomite transmission was examined using microbial interaction networks, ecological statistical models, and human surface touch networks.
  </figcaption>
</figure>

Fomite transmission contributes to infectious disease spread. However, pathogens in fomite transmission are either typically studied individually without considering the context of native microbiota or are studied indiscriminately within broader microbial dispersal. To examine the microbial invasion ecology of fomite transmission in built environments, I adopted an ecology framework in which pathogens are considered invaders, the surface environment as an ecosystem, and human behaviors as the drivers of microbial dispersal ([Wang _et al_. 2022, _mSystems_](https://doi.org/10.1128/msystems.00211-22)).

I hypothesized that invaders in fomite transmission are trackable, neutrally distributed between hands and environmental surfaces, and exhibit a proximity effect. To test this hypothesis, a surrogate invader, *Lactobacillus delbrueckii* subsp. *bulgaricus*, was spread by a root carrier in an office environment undertaking normal activities, and the microbiota on skin and environmental surfaces were sequenced and analyzed before and after invasion. First, I found that the invader was trackable. Its identity and emission source could be determined using microbial interaction networks, and the root carrier could be identified using a rank analysis. Without prior information, *L. bulgaricus* was identified as the invader emitted from a source that exclusively contained the invader, and the probable root carrier was located. In addition to the single-taxon invasion by *L. bulgaricus*, multiple-taxa invasion was observed as genera from sputum/saliva exhibited co-occurrence relationships on skin and environmental surfaces. Second, the invader had a below-neutral distribution in a neutral community model, suggesting that hands accrued higher invader contamination than environmental surfaces. Third, a proximity effect was observed on a surface touch network. Invader contamination on surfaces decreased with increasing geodesic distance from the hands of the carrier, indicating that the carrier’s touching behaviors were the main driver for fomite transmission. These findings demonstrate the invasion ecology principles in fomite transmission and suggest that intervention strategies for fomite transmission should focus on microbial communities and human behaviors, in addition to pathogens themselves.
