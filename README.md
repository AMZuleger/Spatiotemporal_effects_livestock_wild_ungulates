# Spatiotemporal effects of livestock on wild ungulates
Data and Code used for analysis of the manuscript ***From Summer Facilitation to Winter Avoidance: Seasonal Shifts in Livestock-Wild Ungulate Temporal Coexistence*** (DOI: 10.1002/ece3.73705)

Zenodo: https://doi.org/10.5281/zenodo.20209695
Publication: https://doi.org/10.1002/ece3.73705

**Abstract:**

Traditional pastoralism has long shaped Southern European ecosystems, but widespread agricultural abandonment is transforming these landscapes. Yet, extensive livestock grazing remains a persistent driver of ecological dynamics. Simultaneously, the concept of agricultural rewilding has gained attention as a means of using domestic livestock to restore functions once filled by wild ungulates. However, the ecological interactions between livestock and native wild ungulates, especially across seasons, remain poorly understood. Using long-term camera trap data from Peneda-Gerês National Park, Portugal, we examined how free-ranging cattle and horses influence the spatiotemporal activity of roe deer and wild boar across summer and winter. We assessed diel activity levels and patterns, and applied generalized linear mixed models to evaluate the effects of livestock abundance and activity, as well as the presence of herding dogs, using encounter rates as a proxy for livestock abundance. Cattle and horses were predominantly diurnal, whereas roe deer and wild boar were mainly crepuscular and nocturnal, showing increased nocturnality in summer. Both wild ungulate species showed  seasonal differences in response to cattle: activity was higher at high cattle abundance sites in summer but declined in winter. This pattern suggests that grazing may facilitate resource access when plant productivity is high but drive temporal avoidance and competition when resources are limited. Herding dog presence further modified these responses, reinforcing  positive associations in summer, particularly outside of core cattle activity periods. In contrast, horse presence was associated with higher wild ungulate activity across seasons and times of day, indicating facilitative interactions. This highlights the seasonal variability in wildlife-livestock relationships and demonstrates that conclusions based solely on summer data risk underestimating livestock impacts. It further underscores the need for year-round monitoring and adaptive, species-specific grazing strategies that account for livestock-associated disturbance factors such as herding dogs to balance biodiversity restoration with sustainable pastoral management.

**Data structure:**

- *Spatiotemporal_effects_livestock_R.Rmd* - R Notebook document for the entire analysis.
  - Code runs all models and produces all results and figures (except for maps, which were created using QGIS).
- *Spatiotemporal_effects_livestock_R.html* - HTML document created from R *Spatiotemporal_effects_livestock.Rmd* 
  
- Datasets used for analysis:

  - *CT_Peneda_data_new.csv* - Occurrence data of all species from 2015 - 2024 obtained through camera trapping in Peneda-Gerês National Park, PT.
          
  - *GLMM_dataset.csv* - Dataset used for the Generalized Linear Mixed Model (GLMM) analysis.
 
- *Figures.zip* - Contains all figures of the main document:
  - *Figure_1_Peneda_map_new.png* - Study Location and Sampling Design.
  - *Figure_2_Season.png* - Summer and Winter activity patterns per species
  - *Figure_3_Cattle.png* - Activity patterns per wild species depending on cattle abundance and season. 
  - *Figure_4_Horse.png* - Activity patterns per wild species depending on horse abundance and season.
  - *Figure_5_GLMMs.png* - Results of GLMMs analysis - Effects of cattle and horse abundance & activity per species and season.
  - *Figure_S2_Horse.png* - Activity pattern of horses depending on cattle abundance/dog presence and season.
  - *Figure_S3_Dog.png* - Activity pattern per wild species depending on dog presence and season.
    

