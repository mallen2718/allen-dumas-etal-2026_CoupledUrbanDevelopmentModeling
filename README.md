[![DOI](https://zenodo.org/badge/265254045.svg)](https://zenodo.org/doi/10.5281/zenodo.10442485)


`metarepo` is short for meta-repository, a GitHub repository that contains instructions to reproduce results in a published work. This repo is a template for creating your own metarepo.

## Purpose
A meta-repository creates a single point of access for someone to find all of the components that were used to create a published work for the purpose of reproducibility. This repository contains references to all minted data and software as well as any ancillary code used to transform the source data and execute the contributing software.

# allen-dumas-etal_2026_CoupledUrbanDevelopmentModeling

Coupled Model Urban Development Scenarios for Evaluation of Future City-Scale Extreme Weather Impacts **(once published, will include a link to the text)**

Melissa R. Allen-Dumas<sup>1\*</sup>, Bhartendu Pandey<sup>1</sup>,  Hang Li<sup>1</sup>, Vivek Kumar Singh<sup>1</sup>, 
Ryan A. McManamay<sup>1</sup>,  Shovan Chowdhury<sup>1</sup>, Joshua R. New<sup>1</sup>, and Chris Vernon<sup>1, 2</sup>

<sup>1 </sup>Oak Ridge National Laboratory, Oak Ridge, TN, USA.

<sup>2 </sup> Baylor University, Waco, TX, USA

<sup>2 </sup> Pacific Northwest National Laboratory, Richland, WA, USA

\* corresponding author:  allenmr@ornl.gov

## Abstract
Built structures in cities affect the energy balance of urban microclimate.
To understand and quantify effects of urban form on local micrometeorology,
high resolution urban parameter inputs to numerical simulation models
are needed. Furthermore, with future overall average large-scale weather
systems change and increasing urban population density, the capability to
assess the impact of new buildings and their collective morphology (shape
and arrangement) on local weather and energy demand is important. Yet
new built infrastructure is difficult to project at decadal scale. To address
this challenge, we have developed a chain of models that can produce ensembles
of new neighborhoods that may be built in the future for a given city. 

This model chain integrates population predictions, high-resolution city-scale
Land Use Land Cover Change projections, Generative Adversarial Network
(GAN) output of potential building footprints, heights and placement for
new neighborhoods based on historical training examples and urban scaling
theory, and future building archetypes with and without energy-saving technologies
used in simulation with a building energy model. Here we describe
the components of this modeling chain and demonstrate, using an example
morphological projection under a population intensification scenario, how,
under current and future weather regimes, new neighborhood morphologies
and technologies in Los Angeles may evolve to facilitate energy efficient built
areas.

## Journal reference


## Code reference
https://github.com/IMMM-SFA/naturf

https://github.com/pandeyb1/GANUrbanMorph

AutoBEM software download: https://www.ornl.gov/content/automatic-building-energy-modeling-autobem

McManamay, R. A., Raad, A., Vernon, C. R., Thurber, T., Gao, J., Powers, S., & O’Neill, B. (2024). Divergent urban land trajectories under alternative population projections within the Shared Socioeconomic Pathways. Environmental Research Letters, 19(4), 044025.

## Data reference
McManamay, R., Vernon, C., Thurber, T., Gao, J., & O'Neill, B. (2024). Data for "Divergent urban land trajectories under alternative population projections within the shared socioeconomic pathways" (Version v1) [Data set]. MSD-LIVE Data Repository. https://doi.org/10.57931/2318472 .

Pandey, B., & Allen-Dumas, M. (2025). Projected Urban Morphology of the Los Angeles Area by the Year 2100 (Version v2) [Data set]. MSD-LIVE Data Repository. https://doi.org/10.57931/2999982 .

### Input data
New, J., Singh, V. K., & Li, H. (2025). Future Building Archetypes for Los Angeles (2100 Projection) (Version v1) [Data set]. MSD-LIVE Data Repository. https://doi.org/10.57931/3000560 .

Locations of TMY and fTMY data used:
TMY : USA_CA_Los.Angeles.Intl.AP.722950_TMY3.zip (https://climate.onebuilding.org/WMO_Region_4_North_and_Central_America/USA_United_States_of_America/index.html#IDIL_Illinois-) .

FTMY: Shovan Chowdhury, Fengqi Li, Avery Stubbings, Joshua R. New, Deeksha Rastogi, and Shih-Chieh Kao (2023). "Future Typical Meteorological Year (fTMY) US Weather Files for Building Simulation for every US County (Cross-Model version-SSP5-RCP8.5)." ORNL internal Scientific and Technical Information (STI) report, doi: 10.5281/zenodo.10420668, Dec 2023.  (Future Typical Meteorological Year (fTMY) US Weather Files for Building Simulation for every US County in CONUS (Cross-Model Version-SSP5-RCP8.5)) .


