---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<font color="DarkCyan"><b><i>Postdoctoral research:</i></b></font>

**Constraining cumulus and stratocumulus cloud feedbacks in climate models using satellite observations** 

Low-cloud feedbacks contribute strongly to the multimodel spread in equilibrium climate sensitivity. In my postdoctoral research I employ satellite observations to constrain low-cloud feedbacks in a suite of CMIP5 and CMIP6 climate models. The principal aim of this research is to separately evaluate feedbacks related to the two main low-cloud categories: shallow cumulus and stratocumulus. To accomplish this task I utilize the [Cumulus And Stratocumuls CloudSat-CALIPSO Dataset (CASCCAD)](https://data.giss.nasa.gov/clouds/casccad/) recently created by Cesana et al. (2019).<br/> 

![CASCCAD](/images/figNCrnivec_CASCCAD_CuSc_global.png)

<font color="DarkCyan"><b><i>Doctoral research:</i></b></font>

**Cloud-radiation interaction modeling to advance parameterizations in weather and climate models**<br/> 

The cloud-radiation interaction represents a persistent source of uncertainty in weather and climate models. In my doctoral research I investigated the three-dimensional (3-D) interaction between atmospheric radiation and highly-resolved heterogeneous cloud structures in order to improve its representation in regional and global models.

![Cloud-radiation interaction modeling](/images/acp-2020-Fig1-web_CrnivecMayer.png)
<em><font color="Grey">Divergent modelling of cloud-radiation interaction (figure courtesy of Črnivec and Mayer, 2020)</font></em>

The first objective of my PhD was to quantify the radiative bias in regional NWP models for an evolving shallow cumulus cloud field (visualized below), comprising scenarios of broken cumulus as well as more uniform stratocumulus clouds. 
Specifically, I assessed the cloud-radiative bias in regional models arising from two chief shortcomings.
First, the poor representation of unresolved clouds, which are normally approximated as horizontally homogeneous partial cloudiness. 
Second, the intrinsic constraint of two-stream radiation schemes, which neglect horizontal photon flow. 
I further examined the bias dependence on various parameters such as the solar zenith angle, surface albedo, cloud cover and liquid water path. 
I conducted the offline radiative transfer experiments with the [libRadtran](http://www.libradtran.org/) software, the main advantage of which is an accurate benchmark 3-D Monte Carlo radiation model MYSTIC (Mayer, 2009). As a technical challenge, I coded a common regional model radiation scheme, namely the <em>δ-Eddington two-stream method with maximum-random overlap assumption for partial cloudiness</em>, which was implemented into libRadtran for the purpose of this research subject ([Črnivec and Mayer, 2019](https://acp.copernicus.org/articles/19/8083/2019/)). 

![Shallow cumulus - MYSTIC visualization](/images/cumulus_UCLA-LES_MYSTICvis_Crnivec.gif)
<font color="Grey"><i>MYSTIC visualization of a cumulus rising into stratocumulus generated with the UCLA-LES model (figure courtesy of Črnivec and Mayer, 2019)</i></font>

The second objective of my PhD was to advance the cloud-radiation interchange parameterization in coarse-resolution global models, focusing on the issues related to misrepresentation of cloud horizontal inhomogeneity. This subject was tackled with the state-of-the-art Tripleclouds radiative solver, the fundamental feature of which is the inclusion of the optically thicker and thinner cloud fraction. Inspired by the Tripleclouds concept primarily introduced by Shonk and Hogan (2008), I constructed the <em>Tripleclouds radiation scheme based on the core-shell model for convective clouds</em> ([Črnivec and Mayer, 2020](https://acp.copernicus.org/articles/20/10733/2020/)). I subsequently demonstrated the potential of the Tripleclouds scheme for diverse cloud types, comprising case studies of cumulus, stratocumulus, cirrus and cumulonimbus. It was overall found that the optimal Tripleclouds configuration minimizing the radiative bias essentially depends on cloud type, which supports the use of cloud regime dependent methodologies in next-generation atmospheric models ([Črnivec and Mayer, 2021](https://gmd.copernicus.org/articles/14/3663/2021/)).


<font color="DarkCyan"><b><i>Master thesis research:</i></b></font>

**Tropical cyclone intensification & tropical climatology**

Tropical cyclones (TCs) are among nature's most powerful phenomena, yet accurate forecasts of TC intensity change still remain a challenge. To that end, the main goal of my research is to improve physical understanding of TC intensification. I perform high-resolution 3-D numerical simualtions of TCs in an idealized framework using open-source [NCAR Cloud Model (CM1)](http://www2.mmm.ucar.edu/people/bryan/cm1/). 
In particular, I investigated how various environmental factors, such as latitude and sea surface temperature, affect the early period of TC intensification, including the rapid intensification phase ([Črnivec et al., 2016](https://rmets.onlinelibrary.wiley.com/doi/abs/10.1002/qj.2752)). For this purpose I first implemented a balanced TC vortex following the theory of Smith (2006) as a new initialization option into the CM1 model. The subsequent numerical experiments relate to the prototype problem for TC intensification assuming an <em>f</em>-plane with a prescribed sea surface temperature and employ the Dunion moist tropical sounding (Dunion, 2011) to characterize the background thermodynamic TC environment, which is widely used in idealized TC modelling. 
The Dunion sounding, however, is based on the observations in the Caribbean and the question that we addressed in a follow-up study ([Črnivec and Smith, 2016](https://rmets.onlinelibrary.wiley.com/doi/abs/10.1002/joc.4687)) is to what extent is the Dunion sounding representative to TC environments in other parts of the globe. I therefore derived mean radiosonde soundings for the Australian monsoon/cyclone season, documented their various characteristics and finally examined how they control vortex amplification. 
The initial arguments were based on an axisymmetric perspective, invoking the classical axisymmetric spin‐up mechanism. As an upgrade, we have recently investigated the relevance of non-axisymmetric features on the intensification process ([Montgomery et al., 2020](https://rmets.onlinelibrary.wiley.com/doi/10.1002/qj.3837)).


<font color="DarkCyan"><b><i>Numerical Weather Prediction (NWP) Experience:</i></b></font>

While working as a meteorologist in the NWP branch at the Slovenian Environment Agency I had a chance to experience operational weather forecasting. For the purpose of the WMO project SEE-MHEWS (South-East European Multi-Hazard Early Warning Advisory System) our NWP group set up the mesoscale model ALADIN in a novel configuration covering a larger domain over South-East Europe compared to the Slovenian operational version. I was mainly responsible for model validation (utilizing kinetic energy spectra), testing/optimization of model performance at ECMWF's HPC facility and post-processing of output fields on various grids using Python package EPyGrAM ([GitHub repository](https://github.com/NinaCrnivec/epygram_postprocessing)). I was subsequently involved in the project eGAFOR (Electronic General Aviation FORecast), whereby I processed meteorological fields of interest for aviation pilots on standard height levels.



