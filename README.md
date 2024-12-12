# NSW-Fire-Data-Analysis
This project involves analyzing fire data from New South Wales (NSW) to provide actionable insights for the NSW Fire Rescue Services. Using advanced statistical techniques and R programming, the analysis answers critical questions about fire locations, durations, resource allocation, and seasonality.

## Project Overview

The NSW Fire Rescue Services have collected data on various fire incidents, including their locations, types, durations, and environmental factors such as temperature and humidity. This project utilizes this data to:
1.	Map Fire Densities:
     * Estimated fire occurrence density using multivariate normal mixture models.
     * Visualized density across NSW with heatmaps and 3D plots.
     * Estimated the density of fire occurrences at Western Sydney University.
       
2.  Analyze Humidity’s Effect on Fire Duration:Built regression mixture models to explore relationships between humidity and fire duration.
     * Identified hidden factors influencing fire duration using model comparisons (AIC/BIC).
       
3.  Allocate Firefighting Equipment:
     * Calculated probabilities of fire types (forest, grassland, desert) based on fire duration.
     * Recommended proportions of fire retardants for durations of 35-45 minutes based on conditional probabilities.
       
4.  Identify Seasonal Effects:
     * Fitted a mixture model to the temperature variable to uncover seasonal clusters.
     * Highlighted temperature ranges corresponding to fire-prone seasons.
