# West Coast Aquaculture EEZ

In this analysis, we want to determine the total area of suitable habitat in km2 for different marine species within Exclusive Economic Zones. Exclusive Economic Zones are areas that extend up to 200 nautical miles of the coast where a country has domain over the natural resources. The EEZs we will use for this analysis pertain to the West coast of the U.S. We want to better understand the potential for certain aquaculture ventures on the West Coast. We will use open-source data from three sources to obtain environmental and spatial data.

## Repository structure

```{r}

EDS223-HW3
└─── README.md
└─── qmd/Rmd/Proj files
└─── aquaculture_analysis.qmd 
|   .gitignore
    └───data
        └─── wc_regions_clean.shp
        └─── depth.tif
        └─── average_annual_sst_2008.tif
        └─── average_annual_sst_2009.tif
        └─── average_annual_sst_2010.tif
        └─── average_annual_sst_2011.tif
        └─── average_annual_sst_2012.tif
```

## Author

Owner of repository: Lauren Puffer

## Data citations

Froese, R., & Pauly, D. (Eds.). (n.d.). *Panulirus interruptus* (Randall, 1840). SeaLifeBase. <https://www.sealifebase.ca/summary/Panulirus-interruptus.html>

GEBCO Compilation Group. (2025). *GEBCO 2025 grid* [Data set]. General Bathymetric Chart of the Oceans. <https://www.gebco.net/data-products/gridded-bathymetry-data>

Flanders Marine Institute. (n.d.). *EEZ boundaries* [Data set]. Marine Regions. <https://www.marineregions.org/eez.php>

## Acknowledgements

I would like to thank the authors of the paper which this analysis is based on, Gentry et al. 2017. I would also like to thank my classmates Maeve and Caitlin for working collaboratively with me to refine my output. Lastly, I would like to thank Alessandra Vidal Meza and Annie Adams for teaching me the skills necessary to perform the necessary skills to complete this analysis.
