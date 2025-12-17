# Spatiotemporal effects of livestock on wild ungulates
Data and Code used for analysis of the manuscript ***From Summer Facilitation to Winter Avoidance: Seasonal Shifts in Livestock-Wild Ungulate Temporal Coexistence***

[insert DOI for Zenodo repository when available]

**Abstract:**

Traditional pastoralism has long shaped Southern European ecosystems, but widespread agricultural abandonment is transforming these landscapes, where extensive livestock grazing remains one of the few persistent drivers of ecological dynamics. At the same time, the concept of agricultural rewilding has gained attention as a means of using domestic livestock to restore functions once filled by wild ungulates. Yet, the ecological interactions between domestic livestock and native wild ungulates, especially across seasons, remain poorly understood. Using long-term camera trap data (2015–2023) from 64 sites in Peneda-Gerês National Park, northern Portugal, we examined how free-ranging cattle and feral horses influence the spatiotemporal distribution of roe deer and wild boar, the most abundant wild herbivores in this region, across summer and winter. We assessed diel activity levels and patterns, and applied generalized linear mixed models to evaluate the effects of livestock abundance and activity on wild ungulates, using encounter rates as a proxy for livestock abundance. Cattle and horses were predominantly diurnal, whereas roe deer and wild boar were mainly crepuscular and nocturnal, showing increased nocturnal activity in summer. Both wild ungulate species showed strong seasonal differences in response to cattle: activity was higher at high cattle abundance sites in summer but significantly lower in winter, particularly during peak cattle activity hours. This reversal suggests that grazing may facilitate resource access during summer when plant productivity is high but drive temporal avoidance and competition when resources are limited in winter. In contrast, horse presence was consistently associated with higher wild ungulate activity across seasons and times of day, with particularly strong positive effects for wild boar and weaker yet still positive responses for roe deer in winter, indicating generally facilitative interactions. Our results highlight the strong seasonal variability in wildlife-livestock relationships and demonstrate that conclusions based solely on summer data risk underestimating livestock impacts. By linking seasonal dynamics to agricultural rewilding, this study underscores the need for year-round monitoring and adaptive, species-specific grazing strategies to balance biodiversity restoration with sustainable pastoral management.

**Data structure:**

- *Spatiotemporal_effects_livestock.Rmd* - R Notebook document for the entire analysis.
  - Code runs all models and produces all results and figures (except for maps, which were created using QGIS).
- *Spatiotemporal_effects_livestock.html* - HTML document created from R *Spatiotemporal_effects_livestock.Rmd* 
  
- Datasets used for analysis:

  - *CT_Peneda_data_new.csv* - Occurrence data of all species from 2015 - 2024 obtained through camera trapping in Peneda-Gerês National Park, PT.
          
  - *GLMM_dataset.csv* - Dataset used for the Generalized Linear Mixed Model (GLMM) analysis.
 
- *Figures_main.zip* - Contains all figures of the main document:
  - *Figure_1_Peneda_map.png* - Study Location and Sampling Design.
  - *Figure_2_Summer_Winter.png* - Summer and Winter activity patterns per species
  - *Figure_3_Cattle.png* - Activity patterns per wild species depending on cattle abundance and season. 
  - *Figure_4_Horse.png* - Activity patterns per wild species depending on horse abundance and season.
  - *Figure_5_GLMMs.png* - Results of GLMMs analysis - Effects of cattle and horse abundance & activity per species and season.
  - *Figure_S1_Cattle_Horse.png* - Activity pattern of horses depending on cattle abundance and season. 
    

