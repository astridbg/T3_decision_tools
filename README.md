# T3 Decision Tools

This repository contains analysis for the project T3 - Prototyping Decision Support Tools for Earth System Tipping Points. The analysis is inspired by Laybourn et al. (2024), investigating climatic differences in the period after and before abrupt cooling over the Subpolar Gyre in a selection of CMIP6 models. A variety of different climatic indices and visualisations are investigated, to be later used to understand which information is most useful in workshops with policymakers. 

The CMIP6 models investigated are NorESM2-LM, CESM2-WACCM and MRI-ESM2.0, all in the scenario SSP2-4.5, following the analysis of Laybourn et al. (2024) and Swingedouw et al. (2021). Some CMIP6 models which do not exhibit abrupt cooling in this scenario is also investigated, namely MPI-ESM1-2-LR and GFDL-ESM4. Data downscaled to 0.25°x0.25° using NASA Earth Exchange Global Daily Downscaled Projections was also used. 

The visualistion of climatologies is also inspired by van Westen et al. (2024). 

Laybourn L, Abrams J F, Benton D, Brown K, Evans J, Elliott J, Swingedouw D, Lenton T M and Dyke J G
(2024) The security blind spot: Cascading climate impacts and tipping points threaten national security,IPPR. http://www.ippr.org/articles/security-blind-spot

Swingedouw, D., Bily, A., Esquerdo, C., Borchert, L. F., Sgubin, G., Mignot, J., & Menary, M. (2021). On the risk of abrupt changes in the North Atlantic subpolar gyre in CMIP6 models. Annals of the New York Academy of Sciences, 1504(1), 187–201.

René M. van Westen et al., Physics-based early warning signal shows that AMOC is on tipping course.Sci. Adv.10,eadk1189(2024).DOI:10.1126/sciadv.adk1189

### Investigate the SPG cooling

The notebook *compare_SPG_cooling.ipynb* specifically investigates the nature of the cooling over subpolar gyre in the different model runs.

### Investigate differences in temperature and precipitation across seasons

The notebook *plot_seasonal_temp_and_precip.ipynb* investigates changes in temperature and precipitation in annual means and for different season for different periods in the CMIP6 scenarios.

### Calculate climate indices for CMIP6 data

The notebook *temp_climate_indices.ipynb* calculates different temperature-based climate indices for CMIP6 data. 

The notebook *precip_climate_indices.ipynb* calculates different precipitation-based climate indices for CMIP6 data.

The notebook *growing_season_length.ipynb* calculates growing season length for CMIP6 data using some different methods. 

The notebook *growing_degree_days.ipynb* calculates growing degree days for CMIP6.


### Calculate city climatologies for downscaled data

The notebook *city_climatologies.ipynb* computes and visualizes climatologies for different cities using downscaled data. 

### Calculate pdf distributions

The notebook *pdf_distributions.ipynb* computes and visualizes changes in temperatures and precipitation for cities using various forms of histograms and boxplots. 

### Visualize climate indices

The notebook *climate_indices_visualization.ipynb* visualizes climate indices using maps and timeseries. 

### Workshops

The notebooks *berlin_workshop.ipynb* and *oslo_workshop.ipynb* specifically contains the code to specifically reproduce the plots used in the different workshops. 


