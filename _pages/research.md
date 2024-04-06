---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

I combine theory, numerical modeling and observations to study various physical and dynamical processes of the Earth system. A brief overview of my research experience is given below.

<font color="DarkCyan"><b><i>Postdoctoral research:</i></b></font>

**Evaluating marine tropical shallow cumulus and stratocumulus clouds, associated radiative fluxes and feedbacks in climate models using satellite observations** 

Low clouds cover substantial regions of dark tropical oceans, reflect a huge amount of sunlight back to space and thereby cool the Earth, yet this phenomenon has been poorly simulated in several previous generations of climate models and it has been highly uncertain how this phenomenon will change in the future. In my postdoctoral research I employed satellite observations to evaluate the representation of low clouds over tropical oceans, associated radiative fluxes and feedbacks in a suite of newest global climate models. The focus was thereby laid on discriminating individual low-cloud regimes such as stratocumulus (Sc) and shallow cumulus (Cu), which are governed by a distinct interplay of physical processes within moist marine boundary layer and exhibit a contrasting response to global warming. To accomplish this task I utilized the [Cumulus And Stratocumuls CloudSat-CALIPSO Dataset (CASCCAD)](https://data.giss.nasa.gov/clouds/casccad/) created by Cesana et al. (2019) who exploited precise instrumentation on board of the NASA A-train satellite constellation to classify low clouds into various regimes based on cloud morphology.<br/> 

![CASCCAD](/images/figNCrnivec_CASCCAD_CuSc_global.png)

<em><font color="Grey">Shallow cumulus and stratocumulus cloud regimes derived from CASCCAD – in the tropics extensive Sc decks are typically located off the west coast of continents, whereas more scattered Cu clouds are commonly found further west over the open ocean.</font></em>

Assessing the representation of Sc and Cu in climate model output, however, is challenging, because Coupled Model Intercomparison Project (CMIP) diagnostics include only a single low-cloud cover variable without distinguishing between stratiform and convective clouds. Utilizing a novel observation-based method to establish low-cloud regimes based on cloud properties we first assessed models' fidelity to represent Sc and Cu together with their radiative effect at the top of the atmosphere in the present-day climate. We thereby examined twelve climate models stemming from various modeling centers participating in phase 6 of CMIP. Our study demonstrated that the stubborn “too few, too bright” bias, where previous generations of climate models commonly underestimated the amount of tropical oceanic low-level clouds and simultaneously overestimated their reflectivity, persists in the entire set of analyzed CMIP6 models within both Sc- and Cu- regimes, which should fuel further climate model development ([Črnivec et al., 2023](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2022JD038437)).

![Taylor diagrams](/images/Crnivec_etal_2023_JGRA_FigTaylorDiagrams.png)

<em><font color="Grey">Taylor diagrams are a handy tool for model evaluation – demonstrating that CMIP6 models struggle capturing geographical distributions of tropical marine low-cloud cover (LCC) and associated shortwave cloud-radiative effect (CRE) within Sc- and Cu- regimes (figure courtesy of Črnivec et al., 2023).</font></em>

We subsequently addressed the question how has the representation of marine tropical Sc and Cu clouds and associated feedbacks for the abrupt 4xCO2 scenario changed between CMIP5 and CMIP6. We thereby found that, collectively, CMIP6 models notably increased Sc cloud cover and slightly increased Cu cloud cover compared to their CMIP5 predecessors, and are thus closer to observations. We further showed that CMIP6 models notably improved the representation of Sc feedback (in terms of mean and pattern) and slightly improved the representation of Cu feedback compared to CMIP5 models. Yet CMIP6 models still underestimate the magnitude of positive Sc and Cu feedbacks relative to observationally inferred estimates. We finally demonstrated that the change in marine tropical low-cloud feedback between two consecutive model versions stemming from the same climate modeling center correlates well with the change in Sc cloud cover. In simple words, the addition of Sc clouds, which produce a larger positive feedback, naturally resulted in an increased low-cloud feedback in CMIP6 ensemble ([Cesana et al., 2023](https://iopscience.iop.org/article/10.1088/2515-7620/acc78a)).

<font color="DarkCyan"><b><i>Doctoral research:</i></b></font>

**Cloud-radiation interaction modeling to advance parameterizations in weather and climate models**<br/> 

The cloud-radiation interaction represents a persistent source of uncertainty in weather forecasts and climate projections. In my doctoral research I investigated the three-dimensional (3-D) interaction between atmospheric radiation and highly-resolved heterogeneous cloud structures in order to improve its representation in regional and global models.

![Cloud-radiation interaction modeling](/images/acp-2020-Fig1-web_CrnivecMayer.png)

<em><font color="Grey">Diverse modeling of cloud-radiation interaction (figure courtesy of Črnivec and Mayer, 2020)</font></em>

The first objective of my PhD was to quantify the radiative bias in regional NWP models for an evolving shallow cumulus cloud field (visualized below), comprising scenarios of broken cumulus as well as more uniform stratocumulus clouds. 
Specifically, I assessed the cloud-radiative bias at the regional scale arising from two chief shortcomings: poor representation of unresolved clouds and neglected horizontal photon flow. 
I examined the bias dependence on various parameters such as the solar zenith angle, surface albedo, cloud cover and liquid water path. 
I conducted the offline radiative transfer experiments with the [libRadtran](http://www.libradtran.org/) software, the main advantage of which is the accurate benchmark 3-D Monte Carlo radiation model MYSTIC (Mayer, 2009). As a technical challenge, I coded a common regional model radiation scheme, namely the <em>δ-Eddington two-stream method with maximum-random overlap assumption for partial cloudiness</em>, which was implemented into libRadtran for the purpose of this research subject ([Črnivec and Mayer, 2019](https://acp.copernicus.org/articles/19/8083/2019/)). 

![Shallow cumulus - MYSTIC visualization](/images/cumulus_UCLA-LES_MYSTICvis_Crnivec.gif)

<em><font color="Grey">MYSTIC visualization of a cumulus rising into stratocumulus generated with the UCLA-LES model (figure courtesy of Črnivec and Mayer, 2019)</font></em>

The second objective of my PhD was to advance the cloud-radiation interchange parameterization in coarse-resolution global models, focusing on the issues related to misrepresentation of cloud horizontal inhomogeneity. This subject was tackled with the Tripleclouds radiative solver, the fundamental feature of which is the inclusion of the optically thicker and thinner cloud fraction. Inspired by the Tripleclouds concept primarily introduced by Shonk and Hogan (2008), I constructed the <em>Tripleclouds radiation scheme based on the core-shell model for convective clouds</em> ([Črnivec and Mayer, 2020](https://acp.copernicus.org/articles/20/10733/2020/)). I subsequently explored the potential of the Tripleclouds scheme for diverse cloud types, comprising case studies of cumulus, stratocumulus, cirrus and cumulonimbus. It was overall found that the optimal Tripleclouds configuration minimizing the radiative bias essentially depends on cloud type, which supports the use of cloud regime dependent methodologies in next-generation atmospheric models ([Črnivec and Mayer, 2021](https://gmd.copernicus.org/articles/14/3663/2021/)).


<font color="DarkCyan"><b><i>Master thesis research:</i></b></font>

**Tropical cyclone intensification & tropical climatology**

Tropical cyclones (TCs) are among nature's most powerful phenomena, yet accurate forecasts of TC intensity change still remain a challenge. To that end, the main goal of my research is to improve physical understanding of TC intensification. I perform high-resolution numerical simulations of TCs using open-source [NCAR Cloud Model (CM1)](http://www2.mmm.ucar.edu/people/bryan/cm1/). 
In particular, I investigated how various environmental factors, such as latitude and sea surface temperature, affect the early period of TC intensification, including the rapid intensification phase ([Črnivec et al., 2016](https://rmets.onlinelibrary.wiley.com/doi/abs/10.1002/qj.2752)). For this purpose I first implemented a balanced TC vortex following the theory of Smith (2006) as a new initialization option into the CM1 model. The subsequent numerical experiments relate to the prototype problem for TC intensification assuming an <em>f</em>-plane with prescribed sea surface temperature and employ the Dunion moist tropical sounding (Dunion, 2011) to characterize the background thermodynamic TC environment, which is widely used in idealized TC modeling. 
The Dunion sounding, however, is based on the observations in the Caribbean and the question that we addressed in a follow-up study ([Črnivec and Smith, 2016](https://rmets.onlinelibrary.wiley.com/doi/abs/10.1002/joc.4687)) is to what extent is the Dunion sounding representative to TC environments in other parts of the globe. I therefore derived mean radiosonde soundings for the Australian monsoon/cyclone season, documented their various characteristics and finally examined how they control vortex amplification. 
The initial arguments were based on an axisymmetric perspective, invoking the classical axisymmetric spin‐up mechanism. As an upgrade, we have recently investigated the relevance of non-axisymmetric features on the intensification process ([Montgomery et al., 2020](https://rmets.onlinelibrary.wiley.com/doi/10.1002/qj.3837)).

![Tropical Cyclone](/images/figNCrnivec_TropicalCyclone_NCAR_CM1.png)

<em><font color="Grey">Tropical cyclone simulated with the NCAR Cloud Model configured as described in Črnivec et al. (2016)</font></em>

<font color="DarkCyan"><b><i>Numerical Weather Prediction Experience:</i></b></font>

While working as a meteorologist in the numerical weather prediction (NWP) department at the Slovenian Environment Agency (ARSO) I had a chance to experience operational weather forecasting. 

I was predominantly employed on the project _[South-East European Multi-Hazard Early Warning Advisory System (SEE-MHEWS-A)](https://www.see-mhews.org/)_ of the World Meteorological Organization. Due to pressing climate change the intensity and frequency of extreme weather events and related hydrometeorological hazards has been increasing, causing substantial socioeconomic damage and threatening human lives. The overarching goal of the SEE-MHEWS-A project was to provide harmonized forecasts and improve early warnings for major hazards such as severe storms and winds, heavy rainfall and floods, as well as heatwaves, droughts and wildfires, in a consortium of countries in South-East Europe. To accomplish the SEE-MHEWS-A project endeavours, our NWP group at ARSO set up the regional weather model ALADIN in a novel configuration covering a larger domain over South-East Europe compared to the Slovenian operational version ALADIN-SI. I was mainly responsible for model validation (utilizing kinetic energy spectra), testing/optimization of model performance at [ECMWF's HPC facility](https://www.ecmwf.int/en/computing/our-facilities/supercomputer-facility) and post-processing of output fields on various grids using Python package EPyGrAM (code in [GitHub repository](https://github.com/NinaCrnivec/epygram_postprocessing)). 

With a growing computational power the resolution of NWP models is progressively refined. During my time at ARSO, our NWP department was concurrently setting up a new convection-permitting ALADIN-SI configuration with a reduced horizontal grid spacing of 1.3 km (compared to 4.4 km employed in previous operational version). I assisted with verification of a new high-resolution ensemble forecast suite.

I was subsequently involved in the project <em>Electronic General Aviation FORecast (eGAFOR)</em>, whereby I processed meteorological fields of interest for aviation pilots on standard height levels. Some final products and visualizations can be found at [ARSO METEO Aviation webpage](http://www.meteo.si/met/sl/aviation/).

![SEEMHEWS](/images/figNCrnivec_SEEMHEWS_domain_s0-6.png)

<em><font color="Grey">Increased ALADIN model domain size in the SEE-MHEWS configuration</font></em>

